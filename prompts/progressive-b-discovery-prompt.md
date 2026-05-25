# Progressive B Discovery Prompt

This prompt helps a human and an AI agent run a Progressive B Discovery loop.

Vietnamese name: **Prompt Điểm B phát triển**

Use this prompt when the final target is not fully clear yet, but you want to build, test, learn, checkpoint, and move toward a clearer B.

---

## 1. What this prompt does

This prompt asks the AI agent to help you:

* clarify the current B;
* identify what is already known;
* build or improve a rough version;
* capture human feedback;
* preserve lineage;
* create a checkpoint;
* detect known debt;
* suggest patch or rebuild;
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

State the current best understanding of B in simple language.

### 2. What is known

List what is already clear.

### 3. What is still unclear

List what needs runtime, feedback, or readback.

### 4. Recommended next build

Describe the rough next version or next improvement.

### 5. Human feedback needed

Tell me what I should test or judge in real use.

### 6. Known debt

Classify visible debt:

* code debt;
* context debt;
* source debt;
* decision debt;
* verification debt;
* design debt;
* language debt;
* process debt.

### 7. Checkpoint draft

Create a compact checkpoint for this loop.

### 8. Patch or rebuild recommendation

Choose one:

* patch;
* checkpoint only;
* rebuild;
* gather more feedback;
* create agent box;
* create readback;
* pause.

Explain the reason.

### 9. Next agent instruction

Write a short instruction for the next AI or agent to continue from this point.

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

Scope:

```
...
```

Please return:

1. current B;
2. what is known;
3. what is unclear;
4. recommended next build;
5. human feedback needed;
6. known debt;
7. checkpoint draft;
8. patch or rebuild recommendation;
9. next agent instruction.

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
4. what to test in real use;
5. what feedback I should capture;
6. a checkpoint template for after the first test;
7. signs that tell us whether to patch or rebuild.

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

Please return:

1. updated Current B;
2. what changed after runtime;
3. what should be kept;
4. what should be removed;
5. known debt;
6. patch candidates;
7. rebuild signals;
8. checkpoint draft;
9. next move recommendation.

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

Current version:

```
...
```

Real use context:

```
...
```

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
4. What works;
5. What does not fit;
6. Human feedback;
7. Known debt;
8. Keep if rebuild;
9. Remove if rebuild;
10. Next move;
11. Next agent instruction.

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

Inputs:

* ...

Allowed actions:

* ...

Human Gate:

* ...

Required output:

* ...

Please create:

1. Box ID suggestion;
2. Goal;
3. Current B;
4. Scope;
5. Out of scope;
6. Inputs;
7. Source state;
8. Trust state;
9. Allowed actions;
10. Human Gate;
11. Required output;
12. Readback checklist;
13. Exit condition;
14. Next move options;
15. Exact agent instruction.

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
* Are Human Gates respected?
* Can another AI continue from the result?

Short readback:

```
clearer B: yes / partial / no
usable next step: yes / partial / no
lineage preserved: yes / partial / no
checkpoint ready: yes / partial / no
patch/rebuild decision clear: yes / partial / no
```

---

## 11. Short Version

Progressive B Discovery prompt in one paragraph:

```
Help me move toward a clearer B.
The final target is not fully clear yet.
Use the current intent, current state, and human feedback to clarify B, preserve lineage, create a checkpoint, detect known debt, and recommend whether the next move should be patch, rebuild, readback, or more feedback.
Keep the output practical and easy to continue.
```
