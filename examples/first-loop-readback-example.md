# First Loop Readback Example

This example shows what one small Progressive B Discovery iteration can leave behind.

It uses this repo as the object of the loop.

---

## Rough intent

Make Progressive B Discovery easier for a first-time public reader to try.

## Current B

A small public method repo with:

- a README;
- a quick-start guide;
- one simple example;
- prompt and template files;
- a public feedback issue;
- a public sample iteration issue.

## Current version

`v0.1.2` — early public method seed.

## Real use / review context

A first-time reader opens the repo and needs to know:

1. what Progressive B Discovery is;
2. what file to open first;
3. how to leave feedback;
4. how to create a checkpoint;
5. what the next smallest improvement should be.

## Human feedback

```md
What works:
The repo already has a README, quick-start guide, templates, prompt pack, and a simple example.

What is confusing:
The method is easier to understand after seeing one completed readback.

What is missing:
A compact example showing feedback, checkpoint, known debt, and next move in one place.

What feels too heavy:
Adding automation or a large process before real feedback.

What should stay small:
The repo should remain a practical method kit, not a large framework.
```

## What works

- The public source surface is small.
- The README explains the core loop.
- The quick-start guide gives a usable first path.
- The templates separate feedback and checkpointing.
- The repo has public issues for feedback and one sample iteration.

## What does not fit yet

- A first-time reader may still need a concrete readback example.
- The repo has not yet collected enough real user feedback.
- v0.2 should not add heavy structure before feedback exists.

## Known debt

### Documentation debt

- The README points to the simple example, but not yet to a completed readback example.
- The quick-start guide should point to a concrete readback output.

### Feedback debt

- Real external user feedback is still missing.

### Trust debt

- The method is public, but still early.
- The repo should not claim broad validation yet.

## Checkpoint

```md
Current B:
A small public method repo that helps users move from unclear target to clearer B through real use, feedback, checkpointing, and iteration.

Current version:
v0.1.2 early public method seed.

What works:
README, quick-start, simple example, prompt pack, and templates already exist.

What does not fit yet:
The repo needs a completed readback example for first-time readers.

Known debt:
Documentation debt and feedback debt.

Keep:
Small public method-kit shape, quick-start path, templates, and public feedback loop.

Remove:
Any pressure to add automation, private handoff files, release claims, or broad maturity claims before real feedback.

Next move:
Patch by adding this first-loop readback example and linking it from the quick-start guide.
```

## Patch or rebuild decision

**Decision:** patch.

Reason:

- The current repo structure still fits.
- The missing piece is small.
- The next useful change is a documentation example, not a rebuild.

## Next move

1. Add this example file.
2. Link it from `docs/quick-start.md`.
3. Optionally link it from `README.md` in a later docs cleanup.
4. Use public issue feedback to decide the v0.2 candidate scope.

## Readback checklist

- [x] Rough intent is stated.
- [x] Current B is stated.
- [x] Current version is stated.
- [x] Human feedback is captured.
- [x] What works is named.
- [x] What does not fit yet is named.
- [x] Known debt is named.
- [x] Checkpoint is preserved.
- [x] Patch or rebuild decision is made.
- [x] Next move is small and practical.
- [x] No private handoff, audit, zip, release, or broad maturity claim is included.
