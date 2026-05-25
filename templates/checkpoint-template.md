# Progressive B Checkpoint Template

A checkpoint captures the current understanding of a project after a meaningful runtime loop.

It helps humans and AI agents preserve what has been learned, what works, what does not fit yet, and what should guide the next patch or rebuild.

Vietnamese name: **Mẫu checkpoint cho Điểm B phát triển**

---

## 1. When to use this template

Use this template when:

- a rough version has been built;
- the tool or workflow has been used in reality;
- the human has feedback;
- the target B is becoming clearer;
- the current version may need a patch or rebuild;
- the project needs a stable point to continue from later.

A checkpoint is useful when the project has moved forward enough that the current state should not be lost.

---

## 2. What this checkpoint should do

A good checkpoint should answer:

- What are we trying to build now?
- What does the current version do?
- What works?
- What does not fit yet?
- What did real use reveal?
- What is trusted?
- What is still unclear?
- What debt is visible?
- What should be kept if rebuilding?
- What should be removed if rebuilding?
- What is the next move?

The checkpoint should make the next loop easier.

---

## 3. Checkpoint Template

# Progressive B Checkpoint

## Checkpoint ID

Example:

    PBD-CP-001

## Date

Example:

    YYYY-MM-DD

## Project / Tool Name

Name of the tool, workflow, or product being built.

---

## Current B

What is the current best understanding of the target?

Write in simple language.

Example:

    I want a tool that helps me turn messy notes into structured public method drafts.

---

## Current Version

What does the current version do?

Describe only the current working state.

Example:

    The current version can generate a draft README from a rough method note, but it does not yet separate templates into individual files.

---

## Runtime Context

Where was this version used?

Examples:

- personal workflow;
- small team workflow;
- GitHub repo setup;
- internal tool test;
- document drafting;
- dashboard prototype;
- database-backed tool;
- AI agent workflow.

Write the real use context here:

    ...

---

## What Works

List the parts that are already useful.

- ...
- ...
- ...

---

## What Does Not Fit Yet

List the parts that feel wrong, heavy, unclear, missing, or poorly shaped.

- ...
- ...
- ...

---

## Human Feedback

Use practical feedback from real use.

### Useful

- ...

### Missing

- ...

### Excessive

- ...

### Confusing

- ...

### Too slow / too heavy

- ...

### Not trusted yet

- ...

### Feels right

- ...

---

## AI / Agent Observation

What did the AI or agent notice during the loop?

Examples:

- unclear input;
- missing source state;
- repeated manual steps;
- fragile structure;
- messy output;
- poor naming;
- weak checkpoint;
- possible rebuild point.

Notes:

- ...
- ...
- ...

---

## Current Source State

What files, repo, database, or notes are being used as the current source?

Examples:

- README.md
- docs/progressive-b-discovery.md
- templates/checkpoint-template.md
- local database copy
- source pack
- previous checkpoint

Current source state:

- ...
- ...
- ...

---

## Current Trust State

What can be trusted now?

### Trusted

- ...

### Partially trusted

- ...

### Not trusted yet

- ...

### Needs readback

- ...

---

## Known Debt

Debt means any part that may slow down future work if left unclear.

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

---

## Keep If Rebuild

If the project is rebuilt from a clearer B, what should be preserved?

- ...
- ...
- ...

---

## Remove If Rebuild

If the project is rebuilt, what should be removed, simplified, or replaced?

- ...
- ...
- ...

---

## Patch Candidates

Small changes that may improve the current version.

- ...
- ...
- ...

---

## Rebuild Signals

Signals that the project may be ready for a cleaner rebuild.

- The current B is much clearer than before.
- The current structure feels heavier than the target.
- Patching creates more complexity.
- The useful parts are known.
- The removable parts are known.
- The construction trail is clear enough to rebuild safely.

Project-specific rebuild signals:

- ...
- ...
- ...

---

## Next Move

Choose one:

- patch;
- checkpoint only;
- rebuild;
- pause;
- gather more feedback;
- create a new agent box;
- create a readback;
- split into a separate method or file.

Selected next move:

    ...

Reason:

    ...

---

## Next Agent Instruction

Write a short instruction for the next AI or agent.

Example:

    Continue from this checkpoint. Preserve the current B, keep the useful parts, simplify the heavy parts, and propose whether the next move should be patch or rebuild.

Instruction:

    ...

---

## Short Summary

Write 3–5 lines that capture the checkpoint.

Example:

    The current tool is useful for creating a first README draft.
    The target B is now clearer: this should become a public method repo.
    The README works as a public seed.
    The next move is to split templates into separate files.
    Rebuild is not needed yet.

Summary:

    ...
