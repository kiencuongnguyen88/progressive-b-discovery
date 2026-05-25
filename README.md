# Progressive B Discovery

A practical workflow for humans and AI agents to discover clearer product targets through runtime loops, feedback, lineage, checkpoints, and rebuilds.

Vietnamese name: **Điểm B phát triển**

---

## 1. What is Progressive B Discovery?

Progressive B Discovery is a method for building tools, workflows, or products when the final target is not fully clear at the beginning.

Instead of forcing a perfect specification upfront, the method starts with a rough target, builds a usable version, tests it in real work, captures feedback, creates checkpoints, and rebuilds from a clearer understanding.

Basic loop:

```
vague intent
→ rough version
→ real use
→ feedback
→ lineage
→ checkpoint
→ clearer B
→ cleaner rebuild
→ repeat
```

The goal is not perfect first code.

The goal is a recoverable path toward a better product.

---

## 2. The Core Idea

Many AI-assisted projects start with an unclear target.

This is normal.

A human may know:

* what feels useful;
* what is missing;
* what is confusing;
* what is too heavy;
* what is not trustworthy yet;
* what should be easier.

But they may not know how to write a full technical specification, database schema, architecture, or test suite.

Progressive B Discovery treats this as the starting point.

Start close enough.
Use the result.
Learn from reality.
Record what changed.
Checkpoint what is now understood.
Rebuild from a clearer B.

---

## 3. What is “B”?

“B” means the target state.

It can be:

* a tool;
* a workflow;
* a document system;
* an internal dashboard;
* an AI-assisted process;
* a small-team operating system;
* a product direction.

In many real projects, B is not fully visible at the beginning.

B becomes clearer through use.

Key sentence:

```
B is not fixed from day one.
B develops through runtime.
```

---

## 4. Who is this for?

Progressive B Discovery is useful for:

* non-developers building tools with AI;
* developers using agents to speed up work;
* founders building early products;
* operators turning workflows into tools;
* creators building personal systems;
* product managers exploring unclear requirements;
* small teams building internal tools;
* anyone using AI when the target is still fuzzy.

Developers already use stronger boxes: repos, branches, tests, CI, reviews, logs, and rollbacks.

Non-developers need a lighter version of that structure.

Progressive B Discovery gives that lighter structure.

---

## 5. Why this matters

AI can make building much faster.

But faster building does not automatically mean better direction.

Without lineage and checkpoints, AI-assisted work can create:

* messy code;
* unclear decisions;
* lost context;
* hidden technical debt;
* fragile architecture;
* repeated rework;
* projects that cannot be rebuilt cleanly.

Progressive B Discovery helps keep the path recoverable.

Key sentence:

```
Human gives reality feedback.
AI uses lineage and checkpoints to rebuild better.
```

---

## 6. The Basic Loop

### Step 1 — Start with a rough intent

You do not need a perfect spec.

Start with a simple statement:

```
I want a tool that helps me do X better.
```

### Step 2 — Build a rough version

Use AI to create the first usable version.

It may be ugly.

That is acceptable.

The first version is not the final product.
It is a probe.

### Step 3 — Use it in reality

Do not judge only by theory.

Use the tool in a real workflow.

Ask:

* Does this help?
* Where does it slow me down?
* What feels unclear?
* What is missing?
* What is too much?
* What do I not trust yet?

### Step 4 — Capture feedback

Human feedback should focus on real use.

Example:

* This part works.
* This part is confusing.
* This button is not needed.
* This output is useful but too long.
* This result needs readback.
* This workflow should be simpler.

### Step 5 — Preserve lineage

Lineage means the trail of how the tool evolved.

It records:

* what the human wanted;
* what AI built;
* why a direction was chosen;
* what worked;
* what failed;
* what should be kept;
* what can be removed;
* what should be rebuilt later.

Lineage is the map that helps AI repay technical debt.

### Step 6 — Create a checkpoint

A checkpoint freezes the current understanding.

A good checkpoint answers:

* What are we building?
* What does the current version do?
* What is the current B?
* What has been tested?
* What is trusted?
* What is still unclear?
* What debt is known?
* What should be kept if we rebuild?

### Step 7 — Patch or rebuild

After a few loops, choose:

Patch when:

* the current version is close enough;
* the structure still makes sense;
* only small changes are needed;
* the debt is visible and manageable.

Rebuild when:

* the target is now much clearer;
* the current structure no longer fits;
* patches are making the system heavier;
* the construction trail is clear enough to rebuild safely.

Rebuild is not failure.

Rebuild is how the system becomes cleaner after the target becomes clearer.

---

## 7. Key Principle

Technical debt is acceptable when recoverability remains.

Recoverability comes from:

* lineage;
* checkpoints;
* source state;
* feedback;
* readback;
* known debt notes;
* rebuild notes.

If these are preserved, AI can rebuild from a clearer map.

---

## 8. The 3D Print Analogy

The first version may be ugly.

The second version may still be rough.

But each version teaches you something.

You see the shape more clearly.
You measure what does not fit.
You adjust the design.
Then you print again.

Tool-building with AI works the same way.

```
The current tool is the print.
The lineage is the design trail.
The checkpoint is the current measurement.
The rebuild is the next cleaner print.
```

---

## 9. Human and AI Roles

### Human role

The human does not need to understand every line of code.

The human should provide reality feedback:

* useful or not;
* missing or excessive;
* clear or confusing;
* trusted or not trusted;
* worth continuing or worth rebuilding.

### AI role

The AI should:

* build rough versions;
* read lineage;
* preserve checkpoints;
* classify known debt;
* suggest patch or rebuild;
* create readback when needed;
* rebuild from a clearer B.

---

## 10. Minimal Checkpoint Template

Use this structure after each meaningful loop.

### Current B

What are we trying to build now?

### Current Version

What does the current version do?

### What Works

* ...

### What Does Not Fit Yet

* ...

### Human Feedback

Missing:

* ...

Excessive:

* ...

Confusing:

* ...

Useful:

* ...

Not trusted yet:

* ...

### Known Debt

Code debt:

* ...

Context debt:

* ...

Source debt:

* ...

Decision debt:

* ...

Verification debt:

* ...

### Keep If Rebuild

* ...

### Remove If Rebuild

* ...

### Next Move

Choose one:

* patch;
* checkpoint;
* rebuild;
* pause.

---

## 11. Minimal Construction Trail Template

Use this to preserve the path.

### Original Intent

What did the human want at the beginning?

### Build Steps

1. ...
2. ...
3. ...

### Major Decisions

Decision:

* ...

Reason:

* ...

State:

* proposal;
* tested;
* accepted;
* replaced.

### Runtime Feedback

* ...

### Checkpoints

Checkpoint 01:

* ...

Checkpoint 02:

* ...

### Rebuild Notes

If rebuilding from here, keep:

* ...

If rebuilding from here, remove:

* ...

---

## 12. Agent Box Template

Use this when asking an AI agent to work inside a bounded scope.

### Goal

What should the agent move toward?

### Current B

What is the current best understanding of the target?

### Scope

What can the agent work on?

### Inputs

Files:

* ...

Database:

* ...

Notes:

* ...

Previous checkpoint:

* ...

### Allowed Actions

* inspect;
* draft;
* patch;
* test;
* create readback;
* propose rebuild.

### Human Gate

The agent should stop and ask for human decision when touching:

* live database;
* source replacement;
* publishing;
* external actions;
* irreversible changes;
* project authority decisions.

### Required Output

* summary of work;
* changed files or proposed changes;
* readback;
* known debt;
* next recommendation.

---

## 13. Patch or Rebuild?

Use patch when the structure still fits.

Use rebuild when the target has outgrown the structure.

Short rule:

```
Patch when the structure still fits.
Rebuild when the target has outgrown the structure.
```

---

## 14. Positive Runtime

Progressive B Discovery works best with positive operating language.

Instead of only saying what not to do, describe the correct path.

Example:

Heavy wording:

```
Do not let AI guess the source.
```

Positive operating wording:

```
Attach source state clearly so AI can read the path.
```

Good language makes the workflow easier to continue.

Key sentence:

```
The way we write shapes the way the agent runs.
```

---

## 15. Current Status

Version: v0.1

State: early public method draft

Origin: extracted from DIAMOND OS runtime practice

First use case: AI-assisted tool-building with unclear target

This repo is an early public package.

It is meant to be improved through use.

---

## 16. Short Version

When the destination is unclear:

1. build a rough B;
2. use it;
3. capture feedback;
4. preserve lineage;
5. checkpoint what is now understood;
6. rebuild from a clearer B.

Progressive B Discovery is not about getting the first version perfect.

It is about making each loop leave behind:

* a better product;
* a clearer target;
* a better map for the next rebuild.
