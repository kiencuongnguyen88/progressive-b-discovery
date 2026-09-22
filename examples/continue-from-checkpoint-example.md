# Continue from a Checkpoint — New Chat or Agent

This example shows how a Progressive B project can continue in a new chat or with another AI agent without restarting from zero.

The key idea is:

```text
carry forward the accepted state
+
fresh-read facts that may have changed
+
continue the exact next move
```

A checkpoint carries the working state. It is not a guarantee that every mutable source fact is still current.

---

## 1. Starting point

A human is building a markdown-first tool for turning messy notes into useful drafts.

Current B:

```text
Two modes:

Compact mode
- Title
- Short summary
- Main points
- Next action

Full mode
- Source state
- Trust state
- Readback
- Human review
```

Compact mode has already been tested and accepted for its scope.

Full mode is still unresolved.

---

## 2. Agent A leaves a checkpoint

Agent A finishes the compact-mode work and writes:

```md
Checkpoint ID:
PBD-CP-014

Current B:
A two-mode markdown-first drafting tool.

Current B state:
Still developing.

Accepted for this scope:
Compact mode.

Accepted decisions:
- compact mode uses four sections;
- optional sections stay off by default;
- compact mode should not be reopened without new material evidence.

Observed evidence:
Several real notes produced useful short drafts.

Known debt:
- full mode is unresolved;
- switching between compact and full mode has not been tested.

Proposed Next B:
Automatic mode selection.

Proposal state:
Parked.

Current source state at checkpoint:
- prompts/compact.md
- prompts/full.md
- app/flow.md

Next move:
Test full mode only.

Next agent instruction:
Continue from this checkpoint. Preserve accepted compact-mode decisions.
Fresh-read the current source if it may have changed.
Test full mode and return evidence to Current B.
```

This checkpoint carries the state needed to continue.

It does not need the entire old conversation.

---

## 3. A new agent receives the checkpoint

Agent B should not immediately start building.

First, separate **continuation state** from **facts that may have gone stale**.

### Continuation state

These normally carry forward unless newer evidence or an explicit human decision changes them:

- Current B;
- accepted decisions;
- accepted scope;
- known debt;
- proposal state;
- unresolved questions;
- next move.

### Facts that may have gone stale

These need fresh readback when currentness matters:

- current repository commit;
- current file contents;
- current branch state;
- current test result;
- current database snapshot;
- current external status.

Short rule:

```text
accepted state can survive a handoff
while
mutable facts may need fresh readback
```

---

## 4. Fresh-read before continuing

Suppose Agent B finds that the repository changed after the checkpoint was written.

The checkpoint named:

```text
prompts/full.md
app/flow.md
```

as current source.

Agent B should fresh-read those files before treating the old source description as current.

If unrelated files changed, Agent B can preserve the accepted state and continue the planned full-mode test.

If a material input such as `prompts/full.md` changed, Agent B should fresh-read it, update the source state, and continue from the smallest affected point.

The checkpoint remains useful; stale facts are repaired without automatically resetting accepted decisions.

---

## 5. What Agent B should not do

A continuation agent should not ask the human to restate accepted decisions, reopen completed work without new evidence, let an old source snapshot override fresh readback, or silently promote a parked Proposed Next B.

A new chat is a new context container, not automatically a new project state.

---

## 6. Continue the exact next move

After fresh readback, Agent B resumes:

```text
Next move:
Test full mode only.
```

Suppose full mode passes its bounded test.

Agent B returns:

```md
Observed evidence:
Full mode preserves source state and trust state correctly.
Readback is understandable.
Human review is still needed before final output.

What this establishes:
Full mode works for its tested scope.

What this does not establish:
Whether switching between compact and full mode is easy enough in daily use.

Current B state:
Still developing.

Accepted:
- compact mode;
- full mode for its tested scope.

Still unresolved:
- mode switching in real use.

Proposed Next B:
Automatic mode selection.

Proposal state:
Still parked.

Next move:
Run one real-use test of manual mode switching.
```

The second agent extended the checkpoint with new evidence instead of restarting the project.

---

## 7. Updated checkpoint

```md
Checkpoint ID:
PBD-CP-015

Current B:
Two-mode markdown-first drafting tool.

Current B state:
Still developing.

Accepted decisions:
- compact mode structure accepted;
- full mode structure accepted for its tested scope;
- automatic mode selection remains parked.

Observed evidence:
- compact mode works for quick notes;
- full mode works for important notes;
- current source was fresh-read before the second test.

Known debt:
Manual switching has not yet been tested in daily use.

Next move:
Test manual switching in one real workflow.

Next agent instruction:
Continue from PBD-CP-015.
Preserve accepted mode structures.
Fresh-read mutable source facts if material.
Test only manual mode switching.
```

---

## 8. Four continuation rules

```text
checkpoint
!=
full transcript

accepted decision
!=
sender-time source fact

new chat
!=
restart from zero

fresh readback
!=
discard accepted state
```

A good checkpoint lets a new chat or agent recover the project state with less repetition while still checking the facts that can change.
