# Quick Start

Use this guide when you want to run your first Progressive B Discovery loop.

Vietnamese name: **Hướng dẫn bắt đầu nhanh cho Điểm B phát triển**

Progressive B Discovery helps humans and AI agents build toward a clearer target when the final product, tool, workflow, or method is not fully clear yet.

---

## 1. The 5-minute version

You do not need a perfect specification.

Start with what you know.

Use AI to build or improve a rough version.

Use the result in reality.

Give feedback.

Create a checkpoint.

Then decide whether to patch, rebuild, or gather more feedback.

Basic loop:

```
rough intent
→ rough version
→ real use
→ human feedback
→ checkpoint
→ patch or rebuild
→ clearer B
```

The goal is not to get the first version perfect.

The goal is to make each loop leave behind:

* a clearer target;
* a better working version;
* a recoverable path for the next loop.

---

## 2. What you need before starting

You only need four things.

### 1. A rough intent

Example:

```
I want a tool that helps me turn messy notes into structured drafts.
```

### 2. A current version or starting material

This can be:

* a rough idea;
* a note;
* a document;
* a prototype;
* a repo;
* an AI output;
* a workflow you already use.

### 3. Real feedback

You need to say what happens when you use or review it.

Examples:

* This part works.
* This part is confusing.
* This part is missing.
* This part is too much.
* I do not trust this output yet.
* This direction feels right.

### 4. A place to save the checkpoint

This can be:

* a markdown file;
* a project note;
* a GitHub issue;
* a document;
* a chat summary;
* a template file.

---

## 3. Step-by-step

### Step 1 — Write the current intent

Write one simple sentence.

Example:

```
I want a tool that helps me organize my AI-generated notes into reusable public method drafts.
```

This does not need to be complete.

It only needs to be clear enough to start.

---

### Step 2 — Describe the current B

“B” means the current target.

At the beginning, B can be rough.

Example:

```
Current B:
A lightweight repo that explains one method clearly and gives people templates they can use.
```

Another example:

```
Current B:
A personal dashboard that helps me see what to do next without reading all my notes again.
```

Keep it practical.

---

### Step 3 — Ask AI to create or improve a rough version

Use the compact prompt:

```
I want to run one Progressive B Discovery loop.

Current intent:
...

Current B:
...

Current state:
...

What works:
...

What does not fit:
...

What is missing:
...

What is confusing:
...

What is not trusted yet:
...

Scope:
...

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
```

---

### Step 4 — Use or review the result

Do not judge only by theory.

Use the result in a real workflow.

Ask:

* Does this help?
* Where does it slow me down?
* What feels unclear?
* What is missing?
* What is too much?
* What do I not trust yet?
* What should be easier?

---

### Step 5 — Capture human feedback

Use short, direct feedback.

Example:

```
What works:
The structure is easy to follow.

What does not fit:
The introduction is too long.

Missing:
A simple example.

Excessive:
Too many internal terms.

Not trusted yet:
I am not sure outside readers will understand the method.

Next:
Split templates into separate files and add a quick-start guide.
```

Human feedback does not need to sound technical.

It needs to reflect reality.

---

### Step 6 — Create a checkpoint

A checkpoint preserves what is now understood.

Use this compact checkpoint:

```
Current B:
...

Current version:
...

What works:
...

What does not fit:
...

Human feedback:
...

Known debt:
...

Keep if rebuild:
...

Remove if rebuild:
...

Next move:
patch / rebuild / gather feedback / pause
```

A checkpoint makes the next loop easier.

---

### Step 7 — Decide patch or rebuild

Use patch when:

* the current version is close;
* the structure still fits;
* only small changes are needed;
* the debt is visible and manageable.

Use rebuild when:

* B is much clearer now;
* the current structure feels too heavy;
* patches keep adding complexity;
* you know what should be kept;
* you know what should be removed;
* the checkpoint is clear enough to rebuild safely.

Short rule:

```
Patch when the structure still fits.
Rebuild when the target has outgrown the structure.
```

---

## 4. Minimal first loop example

### Rough intent

```
I want to create a public method repo from an internal idea.
```

### Current B

```
A simple GitHub repo that explains the method and gives people templates they can use.
```

### Current state

```
README exists, but it is long and includes too many templates inside one file.
```

### Human feedback

```
What works:
The main idea is clear.

What does not fit:
README is too long.

Missing:
Separate template files.

Excessive:
Too much explanation in one place.

Not trusted yet:
I do not know whether outside readers can use it quickly.
```

### Checkpoint

```
Current B:
Public method repo with clear README and separate templates.

What works:
Core concept and basic loop.

What does not fit:
README is too large.

Known debt:
Structure debt. Templates should be separated.

Keep if rebuild:
Core loop, 3D print analogy, checkpoint idea.

Remove if rebuild:
Repeated explanations inside README.

Next move:
Patch by splitting templates into separate files.
```

### Next AI instruction

```
Continue from this checkpoint.
Keep the core concept.
Split reusable templates into separate files.
Create a quick-start guide for first-time readers.
Preserve enough lineage for the next loop.
```

---

## 5. What files to use in this repo

Recommended order:

1. Read `README.md` for the main idea.
2. Use `docs/quick-start.md` for the first loop.
3. Use `templates/human-feedback-template.md` to capture feedback.
4. Use `templates/checkpoint-template.md` to preserve the current state.
5. Use `templates/construction-trail-template.md` when the project has multiple loops.
6. Use `templates/agent-box-template.md` when asking AI to work inside a bounded scope.
7. Use `prompts/progressive-b-discovery-prompt.md` when you want a complete prompt pack.

---

## 6. Small task version

For a small task, use this version.

```
Current intent:
...

Current B:
...

Current version:
...

What works:
...

What does not fit:
...

What is missing:
...

What is confusing:
...

What is not trusted yet:
...

Next move:
patch / rebuild / gather feedback / pause

Ask AI:
Please update the current B, identify known debt, create a compact checkpoint, and recommend the next move.
```

---

## 7. Good signs

A Progressive B loop is working when:

* B is clearer than before;
* the human knows what to test next;
* the AI has enough context to continue;
* useful parts are preserved;
* weak parts are visible;
* known debt is named;
* patch or rebuild decision is easier;
* another agent can continue from the checkpoint.

---

## 8. Common mistakes

### Trying to write the perfect spec too early

Start with a rough B.

Runtime will make B clearer.

### Letting AI build without feedback

AI needs reality feedback.

Use or review the output, then tell the AI what fits and what does not.

### Losing lineage

Keep the path.

A future rebuild needs to know why the current version exists.

### Patching forever

Patch while the structure still fits.

Rebuild when the target has outgrown the structure.

### Making the method too heavy

Use the smallest structure that preserves the next loop.

---

## 9. Core sentences

```
B is not fixed from day one.
B develops through runtime.

Human gives reality feedback.
AI uses lineage and checkpoints to rebuild better.

Technical debt is acceptable when recoverability remains.

Patch when the structure still fits.
Rebuild when the target has outgrown the structure.
```

---

## 10. Next step

Run one small loop.

Do not start with a large system.

Start with one unclear target, one rough version, one real feedback cycle, and one checkpoint.
