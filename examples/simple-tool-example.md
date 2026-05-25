# Simple Tool Example

This example shows how Progressive B Discovery can be used to build a small AI-assisted tool when the final target is not fully clear at the beginning.

Vietnamese name: **Ví dụ tool đơn giản cho Điểm B phát triển**

---

## 1. Example context

A human wants to build a small tool.

The tool should help turn messy notes into structured drafts.

At the beginning, the human does not know the exact interface, file structure, prompt design, or output format.

The human only knows this:

```
I often have messy notes.
I want AI to help me turn them into usable drafts.
I do not want to rewrite everything by hand.
I want the result to be structured enough to continue later.
```

This is a good situation for Progressive B Discovery.

The target B is not clear yet.

The first job is not to build the perfect tool.

The first job is to build a rough version, use it, capture feedback, checkpoint what is learned, then improve or rebuild from a clearer B.

---

## 2. Rough intent

Original human intent:

```
I want a tool that helps me turn messy notes into structured drafts.
```

Why this matters:

```
I collect many ideas in rough form.
They are useful, but hard to reuse.
I need a way to turn them into drafts, templates, or method notes faster.
```

Who will use it:

```
One person first.
Maybe a small team later.
```

Real problem:

```
Good ideas are scattered in notes and chats.
Without structure, they are hard to turn into output.
```

---

## 3. Current B — first version

Current B at the beginning:

```
A lightweight tool that takes messy notes as input and returns a structured draft with title, summary, main sections, action items, and next-step suggestion.
```

This B is still rough.

It may change after real use.

---

## 4. First rough version

The first rough version does not need a database, account system, dashboard, or complex UI.

A minimal version can be:

```
input: messy notes
output: structured markdown draft
```

Suggested output structure:

```
Title
Short summary
Main idea
Key points
Possible structure
Action items
Open questions
Next step
```

The first version can be built with a simple prompt.

Example prompt:

```
Turn the following messy notes into a structured markdown draft.

Keep the original meaning.
Remove repetition.
Make the structure easy to continue.
Add a short summary.
Add open questions if something is unclear.
Add the next recommended action.

Messy notes:
...
```

This is not the final product.

It is a probe.

---

## 5. First runtime test

The human tests the rough version with real notes.

Example messy notes:

```
Need something for AI tool building.
I usually do not know exact spec.
AI can make tool fast but can create debt.
Need checkpoint.
Need lineage.
Human only knows if it works.
Maybe rebuild after B clearer.
This is like 3D printing.
First print ugly but gives shape.
Later print better.
```

AI output from rough version:

```
Title:
AI Tool Building with Progressive Checkpoints

Summary:
This note describes a method for using AI to build tools when the final target is unclear. The method uses rough versions, real feedback, lineage, checkpoints, and rebuilds.

Main idea:
AI can build quickly, but speed alone does not ensure direction. A human can guide the process through real-use feedback and checkpoints.

Key points:
- The first version does not need to be perfect.
- Human feedback is the main reality signal.
- Lineage keeps the path recoverable.
- Checkpoints preserve what has been learned.
- Rebuild becomes easier when B is clearer.

Action items:
- Create a checkpoint template.
- Create a construction trail.
- Decide when to patch or rebuild.

Open questions:
- Who is the first audience?
- Should this become a public method or internal process?
- What is the minimum useful template?

Next step:
Create a simple checkpoint template for the first loop.
```

---

## 6. Human feedback after first use

The human reviews the result.

Feedback:

### What works

* The output is structured.
* The main idea is easier to see.
* The note can now become a draft.
* The action items are useful.
* Open questions help reveal what is still unclear.

### What does not fit yet

* The output feels too generic.
* It does not preserve enough of the original wording.
* It does not separate public-facing content from internal notes.
* It does not show whether the draft is ready, partial, or needs review.

### Missing

* Source state.
* Trust state.
* Version label.
* Human decision point.
* Patch or rebuild recommendation.

### Excessive

* Some sections may be too formal for quick notes.
* The tool may not need open questions every time.

### Not trusted yet

* The AI may silently remove important nuance.
* The output may sound clean but lose the original intent.
* The next step may be too confident without enough context.

### Feels right

* The rough version is useful.
* A simple markdown-first tool is enough for now.
* No database is needed yet.
* The next loop should improve the output format, not redesign the tool.

---

## 7. First checkpoint

# Progressive B Checkpoint

## Checkpoint ID

```
NOTE-DRAFT-CP-001
```

## Current B

```
A lightweight AI-assisted tool that turns messy notes into structured markdown drafts while preserving meaning, source state, trust state, and next-step clarity.
```

## Current version

```
A simple prompt takes messy notes and returns title, summary, main idea, key points, action items, open questions, and next step.
```

## What works

* Messy notes become easier to read.
* The output has useful structure.
* Action items help continue the work.
* The tool is lightweight enough to use immediately.

## What does not fit yet

* Output is too generic.
* Original nuance may be lost.
* Source state is not visible.
* Trust state is not visible.
* The tool does not yet say whether the result is draft, review, or ready.

## Human feedback

Useful:

* Structure works.
* Markdown output is good.
* First version is enough to test.

Missing:

* Source state.
* Trust state.
* Version label.
* Human decision point.

Excessive:

* Open questions may not be needed every time.

Not trusted yet:

* Meaning preservation.
* Over-cleaning by AI.

## Known debt

Context debt:

* The tool does not preserve enough original context.

Source debt:

* Input source is not labeled.

Decision debt:

* The output does not show what is proposal, draft, or accepted.

Verification debt:

* There is no readback checklist.

Language debt:

* The output may sound too generic.

## Keep if rebuild

* Markdown-first format.
* Simple prompt-based start.
* Title and summary.
* Action items.
* Next-step suggestion.

## Remove if rebuild

* Overly generic phrasing.
* Unnecessary open questions in every output.
* Hidden assumptions about audience.

## Next move

```
Patch.
```

Reason:

```
The current structure still fits.
The tool is useful enough.
The next improvement is small: add source state, trust state, version label, and readback checklist.
```

---

## 8. Patch after checkpoint

Patch goal:

```
Make the output more recoverable and easier to continue.
```

Updated output structure:

```
Title
Version state
Source state
Trust state
Short summary
Preserved original intent
Main idea
Key points
Draft structure
Action items
Open questions, if needed
Readback checklist
Next step
```

Updated prompt:

```
Turn the following messy notes into a structured markdown draft.

Preserve the original intent.
Do not over-clean the meaning.
Add source state and trust state.
Label the result as draft, review, or ready.
Add a short readback checklist.
Add next recommended action.

Messy notes:
...
```

---

## 9. Second runtime result

After the patch, the tool returns a stronger draft.

Example output:

```
Title:
Progressive B Discovery for AI Tool Building

Version state:
draft

Source state:
based on messy human notes

Trust state:
partial — needs human review for nuance

Short summary:
This draft explains a method for building AI-assisted tools when the final target is unclear. It uses rough versions, real feedback, lineage, checkpoints, and rebuilds.

Preserved original intent:
The human does not need to fully understand code. The human needs to know whether the tool works in reality. AI can use the construction trail and checkpoints to reduce technical debt over time.

Main idea:
Build a rough B, use it, capture feedback, checkpoint what is learned, then patch or rebuild from a clearer B.

Key points:
- The first version is a probe.
- Human feedback is the main reality signal.
- Lineage helps AI continue later.
- Checkpoints make rebuild safer.
- Technical debt is acceptable when the path remains recoverable.

Readback checklist:
- original intent preserved: partial
- source state visible: yes
- trust state visible: yes
- next step clear: yes
- human review needed: yes

Next step:
Create a construction trail template.
```

---

## 10. Human feedback after patch

The human reviews the patched version.

Feedback:

### What works

* Source state is useful.
* Trust state prevents overconfidence.
* Preserved original intent is valuable.
* Readback checklist helps review.
* The output is easier to continue.

### What does not fit yet

* The prompt is now longer.
* For very small notes, the output may be too heavy.

### Missing

* A compact mode for small notes.
* A full mode for important notes.

### Direction change

B is now clearer.

The tool should have two modes:

```
compact mode for small notes
full mode for important notes
```

### Next move

```
Patch again.
```

Reason:

```
The structure still fits.
The clearer B only requires mode separation, not rebuild.
```

---

## 11. Updated Current B

After two loops, B becomes clearer:

```
A markdown-first AI tool that turns messy notes into structured drafts, with compact mode and full mode.

Compact mode is for quick notes.
Full mode is for important notes that need source state, trust state, readback, and next-step guidance.
```

This is a better B than the starting point.

The human did not need to define this perfectly at the beginning.

The clearer B emerged through runtime.

---

## 12. What this example shows

This example shows the core Progressive B Discovery pattern:

```
vague intent
→ rough version
→ real use
→ human feedback
→ checkpoint
→ patch
→ clearer B
→ next loop
```

The tool did not start with a perfect specification.

It started with a rough need.

The human used the output and gave practical feedback.

The AI used that feedback to improve the structure.

The checkpoint preserved what was learned.

The next B became clearer.

---

## 13. Patch or rebuild decision

In this example, patching is enough.

Why?

* The rough version is useful.
* The structure still fits.
* The target B is clearer, but not radically different.
* The needed changes are small.
* Debt is visible and manageable.

A rebuild would become useful later if:

* the tool grows into a full app;
* multiple input/output formats are needed;
* a database is added;
* user settings are added;
* the prompt becomes too complex;
* the structure no longer fits the clearer B.

Short rule:

```
Patch while the structure still fits.
Rebuild when the target has outgrown the structure.
```

---

## 14. Final checkpoint summary

```
The project started as a vague idea:
turn messy notes into structured drafts.

The first version proved that markdown output is useful.

Runtime feedback showed that source state, trust state, and readback matter.

The patched version became more recoverable.

The current B is now clearer:
a markdown-first note-to-draft tool with compact and full modes.

Next move:
create compact mode and full mode prompts.
```

---

## 15. Next agent instruction

```
Continue from NOTE-DRAFT-CP-001.

Build two prompt modes:
compact mode for quick notes;
full mode for important notes.

Preserve the core output structure:
title, summary, preserved intent, key points, action items, and next step.

In full mode, include source state, trust state, readback checklist, and human review signal.

Keep the tool markdown-first.
Do not add database, UI, or automation yet.
Recommend patch or rebuild after the next runtime test.
```

---

## 16. Key lesson

The human did not need to know the final specification.

The human only needed to give reality feedback.

The AI used that feedback, plus lineage and checkpoint, to move toward a clearer B.

That is Progressive B Discovery.
