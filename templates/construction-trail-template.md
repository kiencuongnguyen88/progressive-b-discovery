# Construction Trail Template

A construction trail preserves the path of how a tool, workflow, method, or product was built.

It records the original intent, build steps, major decisions, runtime feedback, checkpoints, known debt, and rebuild notes.

Vietnamese name: **Mẫu đường xây dựng / lineage**

---

## 1. Why construction trail matters

AI-assisted building can move very fast.

Fast building is useful, but it can also create lost context, unclear decisions, hidden debt, and fragile rebuilds.

A construction trail keeps the project recoverable.

It helps future humans and AI agents answer:

- What were we trying to build?
- Why did we build it this way?
- What changed after real use?
- Which decisions were tested?
- Which parts should be kept?
- Which parts should be removed?
- What should the next agent know before continuing?
- Can this project be patched, or is it ready for rebuild?

Short principle:

    The product is the current shape.
    The construction trail is the path that explains the shape.

---

## 2. When to use this template

Use this template when:

- a project has gone through multiple AI-assisted build loops;
- the target B has changed over time;
- decisions are starting to accumulate;
- a rebuild may happen later;
- multiple agents or chats are involved;
- the human does not want the project path to be lost;
- the current version works, but the structure may need cleaning later.

This template is especially useful for Progressive B Discovery, where the target becomes clearer through runtime.

---

## 3. Construction Trail

# Construction Trail

## Trail ID

Example:

    PBD-TRAIL-001

## Date Started

Example:

    YYYY-MM-DD

## Last Updated

Example:

    YYYY-MM-DD

## Project / Tool / Method Name

Name:

    ...

## Current B

What is the current best understanding of the target?

Write this in simple language.

Example:

    We are building a public method repo that explains how humans and AI agents can discover a clearer product target through runtime loops.

Current B:

    ...

---

## 4. Original Intent

What did the human want at the beginning?

Do not rewrite the original intent too cleanly.  
Keep the roughness if it helps preserve context.

Original intent:

    ...

Why this mattered:

    ...

Initial uncertainty:

- ...
- ...
- ...

---

## 5. Starting Conditions

What was available at the start?

### Human context

- ...

### AI context

- ...

### Files / repo / database / notes

- ...

### Constraints

- ...

### Unknowns

- ...

---

## 6. Build Steps

Record the main steps in order.

Use short entries.  
Do not over-document every tiny edit.

### Step 01

Action:

    ...

Reason:

    ...

Output:

    ...

State:

- proposed;
- drafted;
- tested;
- accepted;
- replaced;
- parked.

### Step 02

Action:

    ...

Reason:

    ...

Output:

    ...

State:

- proposed;
- drafted;
- tested;
- accepted;
- replaced;
- parked.

### Step 03

Action:

    ...

Reason:

    ...

Output:

    ...

State:

- proposed;
- drafted;
- tested;
- accepted;
- replaced;
- parked.

---

## 7. Major Decisions

Use this section for decisions that changed the path.

### Decision 01

Decision:

    ...

Reason:

    ...

Evidence:

    ...

Human feedback:

    ...

State:

- proposal;
- accepted;
- reversed;
- replaced;
- needs review.

### Decision 02

Decision:

    ...

Reason:

    ...

Evidence:

    ...

Human feedback:

    ...

State:

- proposal;
- accepted;
- reversed;
- replaced;
- needs review.

---

## 8. Runtime Feedback

Record what real use revealed.

### What worked in reality

- ...
- ...
- ...

### What slowed down the workflow

- ...
- ...
- ...

### What felt confusing

- ...
- ...
- ...

### What felt too heavy

- ...
- ...
- ...

### What became clearer after use

- ...
- ...
- ...

### What changed the target B

- ...
- ...
- ...

---

## 9. Checkpoints

Link or summarize checkpoints here.

### Checkpoint 01

Checkpoint ID:

    ...

Date:

    ...

Summary:

    ...

Current B at that checkpoint:

    ...

Next move from that checkpoint:

- patch;
- rebuild;
- pause;
- gather feedback;
- create agent box;
- create readback.

### Checkpoint 02

Checkpoint ID:

    ...

Date:

    ...

Summary:

    ...

Current B at that checkpoint:

    ...

Next move from that checkpoint:

- patch;
- rebuild;
- pause;
- gather feedback;
- create agent box;
- create readback.

---

## 10. Known Debt

Debt means anything that may make future work harder if left unclear.

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

## 11. Debt Notes

Use this section to explain debt in plain language.

Example:

    The current README contains both concept and templates.
    This is acceptable for v0.1, but later the templates should be split into separate files.

Debt note 01:

    ...

Debt note 02:

    ...

Debt note 03:

    ...

---

## 12. Keep If Rebuild

If rebuilding from a clearer B, preserve these parts.

### Concepts to keep

- ...

### Files to keep

- ...

### Templates to keep

- ...

### Prompts to keep

- ...

### Decisions to keep

- ...

### Wording to keep

- ...

### User feedback to keep

- ...

---

## 13. Remove If Rebuild

If rebuilding, remove or simplify these parts.

### Remove

- ...

### Simplify

- ...

### Replace

- ...

### Archive

- ...

---

## 14. Rebuild Map

Use this when the current version is useful but the structure is no longer clean enough.

### Rebuild trigger

What tells us rebuild may be useful?

- ...

### Clearer B

What is clearer now than before?

- ...

### New structure

What should the next version look like?

- ...

### Migration notes

What should move from old version to new version?

- ...

### Risk

What might be lost if rebuilding?

- ...

### Readback needed

What must be checked after rebuild?

- ...

---

## 15. Agent Handoff Notes

Write this for the next AI agent or next chat.

### What the next agent should know

- ...

### What the next agent should preserve

- ...

### What the next agent should improve

- ...

### What the next agent should verify

- ...

### What the next agent should avoid guessing

- ...

### Suggested next instruction

Example:

    Continue from this construction trail.
    Preserve the current B, use the latest checkpoint, keep the working parts, simplify known debt, and propose whether the next move should be patch or rebuild.

Instruction:

    ...

---

## 16. Source State

List the current source materials.

### Current source files

- ...

### Current repo

- ...

### Current database

- ...

### Current notes

- ...

### Current checkpoint

- ...

### Current readback

- ...

---

## 17. Trust State

What is trusted now?

### Trusted

- ...

### Partially trusted

- ...

### Not trusted yet

- ...

### Needs readback

- ...

---

## 18. Timeline Summary

Write a short timeline.

Example:

    2026-05-25 — repo created
    2026-05-25 — README v0.1 committed
    2026-05-25 — checkpoint template added
    2026-05-25 — construction trail template added

Timeline:

- ...
- ...
- ...

---

## 19. Current State Summary

Write 5–10 lines that summarize the current state.

Summary:

    ...

---

## 20. Next Move

Choose one:

- continue patching;
- create checkpoint;
- create readback;
- create agent box;
- split file;
- rebuild;
- pause;
- archive;
- publish.

Selected next move:

    ...

Reason:

    ...

---

## 21. Short Version

Use this compact version when the project is small.

### Current B

    ...

### Original intent

    ...

### Main steps

1. ...
2. ...
3. ...

### What changed after runtime

- ...

### What to keep

- ...

### What to remove

- ...

### Known debt

- ...

### Next move

    ...
