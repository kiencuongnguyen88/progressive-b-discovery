# Agent Box Template

An Agent Box defines a bounded working space for an AI agent.

It helps the human set the goal, scope, inputs, allowed actions, human gates, and required output before the agent starts working.

Vietnamese name: **Mẫu hộp chạy cho AI agent**

---

## 1. Why Agent Box matters

AI agents can move fast.

Fast movement is useful when the boundaries are clear.

A bounded box does not require every internal decision to be fixed in advance. The human can set what must remain stable while allowing the agent to compare, test, or improve the parts that are safe to vary.

Without a clear box, the agent may guess the goal, touch the wrong source, change too much, or create output that is hard to verify.

An Agent Box gives the agent a safe and useful working space.

Short principle:

    Human sets the boundaries and major gates.
    AI works with declared freedom inside those boundaries.
    The box returns evidence to the Current B.

---

## 2. When to use this template

Use this template when:

- the target is still developing;
- the AI needs to work through several steps;
- multiple files or sources are involved;
- the task may create technical debt;
- the output needs readback;
- the agent may need to patch, test, or propose rebuild;
- the human wants the agent to continue without asking after every small step;
- the project needs a clean handoff to another agent or chat.

This template is especially useful for Progressive B Discovery because B becomes clearer through runtime loops.

---

## 3. Agent Box

# Agent Box

## Box ID

Example:

    PBD-BOX-001

## Date

Example:

    YYYY-MM-DD

## Project / Tool / Method Name

Name:

    ...

---

## Goal

What should the agent move toward?

Write the goal in practical language.

Example:

    Improve the current README so outside readers can understand Progressive B Discovery without knowing DIAMOND OS.

Goal:

    ...

---

## Current B

What is the current best understanding of the target?

Example:

    The target is a public method repo that helps humans and AI agents build clearer products through runtime loops, feedback, lineage, checkpoints, and rebuilds.

Current B:

    ...

---

## Current State

What already exists?

Examples:

- repo created;
- README v0.1 committed;
- checkpoint template created;
- construction trail template created;
- tool prototype exists;
- database exists;
- source pack exists;
- previous checkpoint exists.

Current state:

- ...
- ...
- ...

---

## Scope

What can the agent work on in this box?

Examples:

- one file;
- one folder;
- one repo;
- one template;
- one feature;
- one checkpoint;
- one readback;
- one patch proposal.

Scope:

- ...
- ...
- ...

---

## Fixed Boundaries

What must remain fixed while the agent works?

Examples:

- problem or target boundary;
- source-of-truth boundary;
- authority boundary;
- privacy or safety boundary;
- acceptance condition;
- forbidden external actions;
- time budget;
- cost budget;
- compute budget.

Fixed boundaries for this box:

- ...
- ...
- ...

---

## Allowed Freedom

What may the agent vary, compare, test, or improve inside those boundaries?

Examples:

- implementation approach;
- candidate solution;
- prompt or strategy;
- test sequence;
- number of trials within the box limits;
- presentation or structure.

Allowed freedom for this box:

- ...
- ...
- ...

Short principle:

```text
Bounded does not mean small.
Bounded does not mean every decision is fixed.
Bounded means the working envelope is explicit.
```

---

## Out of Scope

What should stay outside this box for now?

Examples:

- live database write;
- production deploy;
- source replacement;
- public publishing;
- large redesign;
- unrelated feature;
- private data;
- internal project source.

Out of scope:

- ...
- ...
- ...

---

## Inputs

List the materials the agent should use.

### Files

- ...

### Repo

- ...

### Database

- ...

### Notes

- ...

### Previous checkpoint

- ...

### Construction trail

- ...

### Human feedback

- ...

---

## Source State

What is the current source of truth for this box?

Examples:

- GitHub README is the current public source.
- Local DB copy is read-only.
- Uploaded source pack is candidate only.
- Human-provided instruction is the current runtime source.
- Previous checkpoint is the current continuation point.

Current source state:

    ...

---

## Trust State

What can the agent trust?

### Trusted

- ...

### Partially trusted

- ...

### Not trusted yet

- ...

### Needs readback

- ...

---

## Allowed Actions

Choose what the agent can do inside this box.

- inspect;
- summarize;
- draft;
- edit;
- patch;
- refactor;
- create template;
- create readback;
- run test;
- compare versions;
- identify known debt;
- propose rebuild;
- create handoff;
- prepare commit message.

Allowed actions for this box:

- ...
- ...
- ...

---

## Working Mode

Choose one mode.

### Draft mode

The agent creates text or structure only.

### Patch mode

The agent proposes or applies small changes.

### Readback mode

The agent checks what exists and reports state.

### Rebuild proposal mode

The agent designs a cleaner rebuild path but does not execute it yet.

### Autonomous box mode

The agent runs multiple steps inside the box until it reaches the defined output or a human gate.

Selected mode:

    ...

---

## Human Gate

The agent should stop and ask for human decision when touching major authority points.

Human Gate examples:

- live database write;
- source replacement;
- active source pin;
- public publish;
- irreversible delete;
- external action;
- account setting;
- security-sensitive change;
- project authority decision;
- canon promotion;
- private data exposure;
- cost-incurring action.

Human Gate for this box:

- ...
- ...
- ...

---

## Required Output

Define what the agent must return.

Examples:

- summary of work;
- changed files;
- proposed file content;
- patch notes;
- readback;
- known debt;
- risks;
- next recommendation;
- commit message;
- handoff note.

Required output:

- ...
- ...
- ...

---

## Readback Requirement

What should be verified before the box closes?

Examples:

- file path is correct;
- headings render correctly;
- no private content is included;
- source state is clear;
- template can be used directly;
- links work;
- output matches scope;
- no unintended file changed;
- next step is clear.

Readback checklist:

- ...
- ...
- ...

---

## Known Debt to Watch

What kinds of debt should the agent look for?

### Code debt

- ...

### Context debt

- ...

### Source debt

- ...

### Decision debt

- ...

### Verification debt

- ...

### Design debt

- ...

### Language debt

- ...

### Process debt

- ...

---

## Lens to Use

Choose the lenses the agent should use.

### User Flow Lens

Is the output easy for the human to use?

### Source State Lens

Does the agent know which source is active, candidate, or reference?

### Checkpoint Lens

Is the current state preserved well enough to continue later?

### Debt Lens

What debt is visible, acceptable, or ready for cleanup?

### Rebuild Lens

Is this still a patch job, or has the target outgrown the structure?

### Public Safety Lens

Is the output safe to share publicly?

### Simplicity Lens

Can this be made clearer or lighter?

Selected lenses:

- ...
- ...
- ...

---

## Evidence Returned to Current B

What should this box return to the larger Progressive B loop?

### What this box established

- ...

### What this box did not establish

- ...

### Evidence from real use or testing

- ...

### Effect on Current B

- ...

### What remains unresolved outside this box

- ...

A successful Agent Box does not automatically accept the larger Current B.

---

## Box Exit Condition

When should the agent stop?

Examples:

- required file is drafted;
- readback is complete;
- patch is proposed;
- checkpoint is created;
- rebuild proposal is ready;
- human gate is reached;
- uncertainty blocks safe progress.

Exit condition:

    ...

---

## Next Move Options

After the box closes, choose one:

- commit;
- patch again;
- create checkpoint;
- create construction trail;
- create readback;
- create another agent box;
- rebuild;
- pause;
- publish;
- archive.

Selected next move:

    ...

Reason:

    ...

---

## Agent Instruction

Write the exact instruction for the agent.

Example:

    Work inside this Agent Box.
    Use the current source state and checkpoint.
    Create the requested template.
    Keep the output public-safe.
    Return the file content, readback checklist, known debt, and next recommendation.
    Stop at Human Gate if the task requires publishing, source replacement, or irreversible action.

Instruction:

    ...

---

## Short Agent Box

Use this compact version for small tasks.

### Goal

    ...

### Current B

    ...

### Scope

    ...

### Fixed Boundaries

    ...

### Allowed Freedom

    ...

### Inputs

- ...

### Allowed Actions

- ...

### Human Gate

- ...

### Required Output

- ...

### Exit Condition

    ...

### Evidence Returned to Current B

What this box established:

    ...

What remains unresolved outside this box:

    ...

### Next Move

    ...

---

## Example Agent Box

### Box ID

    PBD-BOX-001

### Goal

    Create a clean checkpoint template for Progressive B Discovery.

### Current B

    Progressive B Discovery is becoming a public method repo.
    The repo needs templates that help humans and AI agents preserve learning between runtime loops.

### Scope

    Create one markdown file:
    templates/checkpoint-template.md

### Inputs

- README.md v0.1
- Progressive B Discovery concept
- current repo structure

### Allowed Actions

- draft;
- structure;
- simplify;
- create public-safe template;
- propose commit message.

### Human Gate

- publishing;
- deleting files;
- changing repo structure beyond this template.

### Required Output

- full markdown file content;
- short readback;
- commit message;
- next recommendation.

### Exit Condition

    The checkpoint template is ready to paste into GitHub.

### Next Move

    Commit the file, then create construction-trail-template.md.
