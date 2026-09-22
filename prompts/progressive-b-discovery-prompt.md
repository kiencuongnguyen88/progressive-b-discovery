# Progressive B Discovery Prompt

This prompt helps a human and an AI agent run a Progressive B Discovery loop.

Vietnamese name: **Prompt Điểm B phát triển**

Use this prompt when the final target is not fully clear yet, but you want to build, test, learn, checkpoint, and move toward a clearer B.

---

## 1. What this prompt does

This prompt asks the AI agent to help you:

* clarify the current B;
* identify what is already known;
* use observed evidence from real use, tests, readback, runtime results, or workflow friction;
* build or improve a rough version inside explicit boundaries;
* capture human feedback, including workflow or manual effort;
* return bounded-work evidence to the larger Current B;
* preserve lineage;
* create a checkpoint that separates work completion from B acceptance;
* detect known debt;
* keep Proposed Next B separate until it is adopted;
* preserve a working checkpoint while exploring a newer candidate;
* suggest patch, rebuild, retest, gather feedback, or accept the current scope;
* prepare the next loop.

Short principle:

```
When the destination is unclear,
build a rough B,
use it,
capture feedback,
preserve lineage,
checkpoint what is now understood,
then rebuild from a clearer B.
```

---

## 2. Main Prompt

Copy this prompt and fill in the sections.

---

# Progressive B Discovery Request

I want to use Progressive B Discovery to move toward a clearer product, tool, workflow, or method target.

The final target is not fully clear yet.

Help me run one bounded loop.

## Current Intent

What I roughly want:

```
...
```

Why this matters:

```
...
```

Who will use it:

```
...
```

What real problem it should help with:

```
...
```

---

## Current B

My current best understanding of the target is:

```
...
```

This may be incomplete or unclear.

Help me make it clearer through runtime, not through over-planning.

## Current B Status

Acceptance scope:

```
...
```

Current B state:

```
still developing / accepted for this scope / blocked by missing evidence / needs another real-use test
```

Proposed Next B, if any:

```
...
```

Proposal state:

```
proposal / adopted as Current B / rejected / parked
```

---

## Current State

What already exists:

* ...

Examples:

* rough idea;
* notes;
* README draft;
* prototype;
* repo;
* files;
* database;
* previous output;
* checkpoint;
* human feedback;
* construction trail.

---

## Inputs

Use the following input materials:

* ...

Input details:

```
...
```

If any source is unclear, state what is unclear before making assumptions.

---

## Real Use Context

This will be used in:

* personal workflow;
* small team workflow;
* tool-building;
* document drafting;
* public method writing;
* internal dashboard;
* AI agent workflow;
* product exploration;
* other: ...

Specific context:

```
...
```

---

## Observed Evidence So Far

What has already happened in reality?

Examples:

* test or readback result;
* runtime or usage result;
* observed failure or repair;
* workflow friction or repeated coordination;
* proof that confirmed or contradicted an assumption.

Observed evidence:

* ...

---

## Human Feedback So Far

What feels useful:

* ...

What feels wrong or not fitting:

* ...

What is missing:

* ...

What is excessive:

* ...

What is confusing:

* ...

What I do not trust yet:

* ...

What feels right and should continue:

* ...

Workflow / manual effort:

* ...

---

## Working Mode

Use this mode:

* clarify B;
* draft rough version;
* improve current version;
* create checkpoint;
* create construction trail;
* create agent box;
* classify known debt;
* suggest patch or rebuild;
* prepare next loop.

Selected mode:

```
...
```

---

## Scope

Work inside this scope:

```
...
```

Out of scope for now:

```
...
```

## Fixed Boundaries

What must remain fixed during this loop?

* ...

## Allowed Freedom

What may the AI vary, compare, test, or improve inside those boundaries?

* ...

---

## Allowed Actions

You may:

* ask clarifying questions only if the missing information blocks safe progress;
* infer a practical first version when enough context exists;
* structure the current B;
* identify what is known and unknown;
* create a draft;
* propose a patch;
* propose a rebuild path;
* create a checkpoint;
* create a construction trail;
* create a readback checklist;
* write next-agent instructions.

Allowed actions for this loop:

* ...

---

## Human Gate

Stop and ask for human decision when the task touches:

* live database write;
* source replacement;
* public publishing;
* irreversible deletion;
* external action;
* project authority decision;
* private data exposure;
* major architecture change;
* cost-incurring action.

Human Gate for this loop:

* ...

---

## Lenses to Use

Use these lenses when analyzing the loop:

### User Flow Lens

Does the output help the human use the tool or method more easily?

### Current B Lens

Is the target clearer than before?

### Source State Lens

Are the active source, candidate source, and reference source clear?

### Lineage Lens

Is the path preserved well enough for another AI or human to continue?

### Checkpoint Lens

Is the current state captured clearly enough to continue later?

### Debt Lens

What debt is visible, acceptable, or ready for cleanup?

### Patch or Rebuild Lens

Should the next move be a small patch or a cleaner rebuild?

### Public Safety Lens

If this is public-facing, is the output safe to share?

Selected lenses:

* ...

---

## Required Output

Return the result in this structure:

### 1. Current B

State the current best understanding of B.

### 2. B status and evidence

Include acceptance scope, current B state, observed evidence received, and what remains unresolved.

A completed bounded task does not automatically accept the larger Current B.

### 3. What is known

### 4. What is still unclear

### 5. Recommended bounded work

Describe the next build, test, comparison, or probe inside the declared boundaries.

### 6. Human feedback needed

State what the human should judge or interpret next. Include workflow or manual effort where relevant.

### 7. Known debt

Classify visible debt where relevant: code, context, source, decision, verification, design, language, or process.

### 8. Evidence returned to Current B

Separate observed evidence from interpretation. State what the bounded work established, what it did not establish, its effect on Current B, and what remains unresolved outside the box.

### 9. Checkpoint draft

Include Current B, acceptance scope/state, evidence, known debt, any Proposed Next B and proposal state, plus the preserved working checkpoint while a newer candidate is explored.

### 10. Next-move recommendation

Choose the best fit: patch, checkpoint only, rebuild, retest, gather more feedback, accept this scope, create agent box, create readback, or pause.

### 11. Next agent instruction

Write a short instruction that continues from the checkpoint.

---

## Output Style

Use clear, practical language.

Prefer positive operating wording.

Focus on the path that helps the project move forward.

Keep the result structured enough to continue later.

---

## 3. Compact Prompt

Use this shorter version for small tasks.

# Compact Progressive B Discovery Prompt

I want to run one Progressive B Discovery loop.

Current intent:

```
...
```

Current B:

```
...
```

Current state:

```
...
```

What works:

* ...

What does not fit:

* ...

What is missing:

* ...

What is excessive:

* ...

What is confusing:

* ...

What is not trusted yet:

* ...

Observed evidence so far:

* ...

Scope:

```
...
```

Fixed boundaries:

* ...

Allowed freedom:

* ...

Workflow / manual effort:

* ...

Please return:

1. current B;
2. B status for the scope being decided;
3. recommended bounded work;
4. evidence returned to Current B;
5. human feedback needed to interpret or test that evidence;
6. known debt;
7. checkpoint draft;
8. Proposed Next B, if evidence suggests a target change — keep it separate from Current B until adopted;
9. next-move recommendation;
10. next agent instruction.

Use practical language and preserve enough lineage for the next loop.

---

## 4. Prompt for Building a Rough Version

Use this when you have an idea but no working version yet.

# Rough Version Prompt

I have a rough idea, but the final target is not clear yet.

Help me create the first rough version using Progressive B Discovery.

My intent:

```
...
```

The problem I want to solve:

```
...
```

Who will use it:

```
...
```

What I want the first version to help with:

```
...
```

Constraints:

```
...
```

Please create:

1. a clearer Current B;
2. a minimal first version plan;
3. a simple structure;
4. what to test or read back in real use;
5. what evidence should be recorded;
6. what feedback I should capture;
7. a checkpoint template for after the first test;
8. signs that tell us whether to patch or rebuild.

Keep the first version small enough to use.

---

## 5. Prompt for Reviewing a Version

Use this after you have used or reviewed a rough version.

# Runtime Review Prompt

I have used or reviewed the current version.

Help me process the feedback using Progressive B Discovery.

Current B:

```
...
```

Current version:

```
...
```

Observed evidence from use, testing, readback, or runtime:

* ...

What worked:

* ...

What did not fit:

* ...

What was missing:

* ...

What was excessive:

* ...

What was confusing:

* ...

What I did not trust:

* ...

What felt right:

* ...

Workflow / manual effort:

* ...

Please return:

1. Current B;
2. B status for the scope being decided;
3. what changed after runtime;
4. what should be kept;
5. what should be removed;
6. known debt;
7. evidence returned to Current B, with observed evidence separated from interpretation;
8. Proposed Next B, if the evidence suggests a target change — keep it separate until adopted;
9. checkpoint draft;
10. next move recommendation.

---

## 6. Prompt for Rebuild Decision

Use this when patching starts making the project heavier.

# Patch or Rebuild Decision Prompt

I need help deciding whether to patch or rebuild.

Current B:

```
...
```

Current version:

```
...
```

Known useful parts:

* ...

Known problems:

* ...

Known debt:

* ...

What is clearer now than before:

* ...

Construction trail available:

* yes;
* partial;
* no.

Checkpoint available:

* yes;
* partial;
* no.

Please analyze:

1. whether the structure still fits the target;
2. whether patching is still efficient;
3. what would be kept if rebuilding;
4. what would be removed if rebuilding;
5. what risk the rebuild has;
6. what readback should be done after rebuild;
7. final recommendation: patch, rebuild, or gather more feedback.

Use this short rule:

```
Patch when the structure still fits.
Rebuild when the target has outgrown the structure.
```

---

## 7. Prompt for Creating a Checkpoint

Use this when a loop has produced meaningful learning.

# Checkpoint Creation Prompt

Create a Progressive B checkpoint from the following context.

Current B:

```
...
```

Acceptance scope:

```
...
```

Current B state:

* still developing;
* accepted for this scope;
* blocked by missing evidence;
* needs another real-use test.

Selected state:

```
...
```

Current version:

```
...
```

Real use context:

```
...
```

Observed evidence:

* ...

What works:

* ...

What does not fit:

* ...

Human feedback:

* ...

Known debt:

* ...

Source state:

* ...

Trust state:

* ...

Proposed Next B, if any:

```
...
```

Proposal state:

* proposal;
* adopted as Current B;
* rejected;
* parked.

Preserved working checkpoint:

```
...
```

Next likely move:

* patch;
* checkpoint only;
* rebuild;
* gather feedback;
* create agent box;
* create readback;
* pause.

Please create:

1. checkpoint ID suggestion;
2. compact summary;
3. Current B;
4. acceptance scope and Current B state;
5. observed evidence received, its interpretation, and what remains unresolved;
6. What works;
7. What does not fit;
8. Human feedback, including workflow or manual effort;
9. Known debt;
10. Proposed Next B and proposal state, if any;
11. preserved working checkpoint;
12. Keep if rebuild;
13. Remove if rebuild;
14. Next move;
15. Next agent instruction.

---

## 8. Prompt for Creating an Agent Box

Use this when you want the AI to work inside a bounded scope.

# Agent Box Creation Prompt

Create an Agent Box for the next Progressive B Discovery loop.

Goal:

```
...
```

Current B:

```
...
```

Current state:

```
...
```

Scope:

```
...
```

Fixed boundaries:

* ...

Allowed freedom:

* ...

Inputs:

* ...

Allowed actions:

* ...

Human Gate:

* ...

Required output:

* ...

Evidence the box should return to Current B:

* ...

Please create:

1. Box ID suggestion;
2. Goal;
3. Current B;
4. Scope;
5. Fixed Boundaries;
6. Allowed Freedom;
7. Out of scope;
8. Inputs;
9. Source state;
10. Trust state;
11. Allowed actions;
12. Human Gate;
13. Required output;
14. Evidence Returned to Current B;
15. Readback checklist;
16. Exit condition;
17. Next move options;
18. Exact agent instruction.

---

## 9. Prompt for Public Method Packaging

Use this when turning an internal method into a public-safe package.

# Public Method Packaging Prompt

I want to package an internal method into a public-safe method file.

Internal method name:

```
...
```

Public name:

```
...
```

Audience:

```
...
```

What the method helps with:

```
...
```

Internal terms that may need simplification:

* ...

Private/internal details to keep out:

* ...

Public-safe concepts to keep:

* ...

Please create:

1. public positioning;
2. short explanation;
3. method loop;
4. practical template;
5. example;
6. prompt for users;
7. public-safety readback;
8. suggested README section;
9. suggested next files.

Use practical language for outside readers.

---

## 10. Readback Checklist

After the AI returns output, check:

* Is the current B clearer?
* Is the next step easier?
* Is human feedback preserved?
* Is lineage preserved?
* Is known debt visible?
* Is the patch or rebuild recommendation clear?
* Is the output usable without hidden context?
* Is source state clear?
* Is the evidence basis visible and separated from interpretation?
* Are Human Gates respected?
* Is bounded-work completion kept separate from Current B acceptance?
* Is any Proposed Next B still a proposal unless it was explicitly adopted?
* Is the working checkpoint preserved while a newer candidate is explored?
* Can another AI continue from the result?

Short readback:

```
clearer B: yes / partial / no
usable next step: yes / partial / no
lineage preserved: yes / partial / no
evidence basis visible: yes / partial / no
checkpoint ready: yes / partial / no
bounded work vs B acceptance separated: yes / partial / no
Proposed Next B admission clear: yes / partial / no
patch/rebuild/accept decision clear: yes / partial / no
```

---

## 11. Short Version

Progressive B Discovery prompt in one paragraph:

```
Help me move toward a clearer B.
The final target is not fully clear yet.
Use the current intent, Current B, current state, observed evidence, fixed boundaries, allowed freedom, and human feedback to run one bounded loop. Return evidence to Current B, keep bounded-work completion separate from B acceptance, keep any Proposed Next B separate until adopted, preserve a working checkpoint, detect known debt, and recommend whether the next move should be patch, rebuild, retest, readback, more feedback, or acceptance for the declared scope.
Keep the output practical and easy to continue.
```
