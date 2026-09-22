# Bounded Work, Current B Still Open

This example shows two Progressive B Discovery distinctions:

```text
bounded work can pass
while the larger Current B is still developing

and

Proposed Next B
!=
Current B
```

---

## 1. Starting point

A human is building a lightweight AI tool for turning messy notes into useful drafts.

Current B:

```text
A markdown-first tool with:

- compact mode for quick notes;
- full mode for important notes that need source state, trust state, readback, and human review.
```

The human tests only compact mode first.

---

## 2. Agent Box for compact mode

### Goal

Create and test a compact mode that turns a short note into a useful draft without unnecessary structure.

### Fixed boundaries

- markdown output;
- preserve the original intent;
- no database;
- no account system;
- no automation;
- do not redesign full mode.

### Allowed freedom

The agent may vary:

- prompt wording;
- output order;
- optional sections;
- the number of trials within the box limits.

### Box acceptance condition

Compact mode should:

- preserve the main intent;
- produce a useful short draft;
- avoid unnecessary sections;
- make the next action clear.

---

## 3. Box result

After several trials, the best candidate produces:

```text
Title
Short summary
Main points
Next action
```

The human tests it with real notes and accepts compact mode for this box.

```text
Agent Box: PASS
```

What the box established:

- the four-part compact structure is usable;
- optional sections should stay off by default;
- compact mode can remain small.

What it did not establish:

- whether full mode works;
- whether switching between modes is simple;
- whether the whole Current B is ready.

Therefore:

```text
Agent Box PASS
!=
Current B accepted
```

Current state:

```text
Compact mode: accepted for its tested scope.
Full mode: unresolved.
Current B: still developing.
```

---

## 4. Return evidence to Current B

The larger loop now has new evidence.

Updated Current B:

```text
Compact mode:
Title
Short summary
Main points
Next action

Full mode:
Still needs testing for source state, trust state, readback, and human review.
```

The target is clearer, but it is not closed.

---

## 5. A proposed next B

Based on the compact-mode result, the AI proposes a newer target:

```text
Proposed Next B:
Choose compact or full mode automatically instead of asking the user to choose.
```

The proposal may be useful, but it has not been tested and it changes product behavior.

Therefore the checkpoint records:

```text
Proposed Next B: automatic mode selection
Decision state: proposal
Current B: unchanged
Preserved working checkpoint: current two-mode design
```

A newer proposal is not automatically the Current B.

---

## 6. Second bounded probe

A second Agent Box tests full mode without reopening compact mode unless new material evidence requires it.

Suppose full mode passes its own box acceptance condition.

One larger-B question still remains:

```text
Is switching between compact and full mode simple enough in real use?
```

A short real-use test answers that question.

If manual switching is already simple enough, the automatic-mode proposal can remain parked instead of replacing a working Current B.

---

## 7. Accepting the Current B for this scope

Now the evidence shows:

- compact mode works for quick notes;
- full mode works for important notes;
- switching between them is understandable;
- no material unresolved item remains inside the declared scope.

The larger Current B can now be accepted for this scope.

```text
bounded-work evidence
+ required larger-scope evidence
+ no material unresolved item in the declared scope
→ Current B accepted for this scope
```

This is not a claim that the tool can never change again.

If new material evidence appears later, Progressive B Discovery can reopen the loop.

It also does not help to invent extra work after the current declared scope is already accepted.

---

## 8. Four rules

```text
Agent Box PASS
!=
Current B accepted

Empty work list
!=
Current B accepted

Proposed Next B
!=
Current B

Current B accepted for its declared scope
!=
keep inventing more work
```

That separation lets Progressive B Discovery explore when evidence is missing, preserve a working state while testing newer candidates, and close when the declared scope is genuinely ready.
