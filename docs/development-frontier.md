# Development Frontier — Progressive B beyond v0.1.2

> **Status:** working development note.  
> This file records current method development that is **not yet integrated into the public v0.1.2 baseline**.
> The stable public repo state remains **v0.1.2 — early public method seed**.

Date: 2026-09-22

---

## 1. Public baseline that remains valid

The current public method still starts from a simple loop:

```text
rough intent
→ rough version
→ real use
→ human feedback
→ lineage
→ checkpoint
→ patch / rebuild
→ clearer B
```

That loop remains useful.

The development below does not replace it. It explores what happens when a Progressive B loop becomes deeper, longer, more search-heavy, or needs stronger completion proof.

---

## 2. Outer discovery and inner execution are not the same thing

A stronger current model separates two layers:

```text
Progressive B Discovery
= outer discovery / target-development loop

Locked Execution Box
= inner bounded execution / search loop
```

A possible relationship is:

```text
rough or current B
→ Discovery / Probe
→ choose bounded execution/search scope
→ run inside a Locked Execution Box
→ Reality Return
→ update evidence + frontier
→ compare current best-known candidates
→ update B
→ repeat or close the exact accepted scope
```

The outer loop asks:

- What should B become?
- What is still unknown?
- What evidence changes the target?
- What deserves another search or execution box?

The inner loop asks:

- What is allowed to vary here?
- What can be tested inside this box?
- What result is best-known under this declared search?
- What evidence returns to the parent loop?

This distinction matters because finishing one inner box does not automatically finish the outer discovery problem.

---

## 3. Field-level degrees of freedom

A bounded box does not mean every field is fixed.

Different parts of the problem may have different freedom:

- fixed;
- selectable from a known set;
- locally optimizable;
- open to search;
- open to reframing;
- blocked behind a Human Gate.

This makes the box bounded **without forcing the whole problem to be small or predetermined**.

The current working rule is:

```text
bounded != small
bounded = explicit boundary + explicit freedom + explicit acceptance
```

---

## 4. Search Epoch and Search Run

For deeper discovery, one logical problem may need more than one search attempt.

Working terminology:

### Search Epoch

A larger search period owned by one logical task/problem.

It preserves:

- the same parent objective;
- the same parent acceptance surface;
- the accumulated frontier;
- the current best-known result;
- the evidence and constraints that should survive between runs.

### Search Run

One bounded attempt inside the epoch.

A run may change:

- model;
- tool;
- prompt;
- strategy;
- candidate family;
- search budget;
- execution environment;
- degrees of freedom.

A run should return evidence to the same parent epoch instead of silently declaring the parent complete.

---

## 5. Frontier before promotion

Discovery should preserve a frontier of live candidates, unresolved questions, contrary evidence, and promising directions before promoting one result as the current best-known answer.

A working flow is:

```text
Probe
→ evidence
→ candidate/frontier update
→ comparison
→ current best-known
→ Reality Return
→ next search or promotion decision
```

The frontier is not only a list of unfinished items.

It is the current search surface: what is still materially alive, what has been rejected, what is unresolved, and what could change the decision.

---

## 6. Best-known convergence

A search-heavy loop should avoid pretending that it has found an absolute optimum.

A more defensible claim is:

```text
best-known under the declared search,
evidence,
constraints,
tools,
and acceptance surface
```

This allows the system to converge operationally without claiming that no better answer can ever exist.

A later Reality Return can reopen the frontier when new material evidence appears.

---

## 7. Critical scope rule

The strongest current boundary is:

```text
EMPTY_REGISTERED_FRONTIER
!=
PARENT_ACCEPTANCE_PASS
```

Related forms:

```text
CHILD_PASS != PARENT_PASS

LOCAL_CONVERGENCE != WHOLE_PARENT_CONVERGENCE

FRONTIER_COMPLETE != TARGET_ACCEPTED
```

An inner box can finish correctly while the parent Point B remains unresolved.

An empty or completed registered frontier proves a coverage/inventory state. It does **not** by itself prove that the whole parent target has passed its acceptance conditions.

Parent closeout needs acceptance proof bound to the **exact parent scope**.

This protects against a common false-close pattern:

```text
child loop finishes
→ no local open item remains
→ system incorrectly widens that fact
→ parent is declared complete
```

The intended pattern is:

```text
child loop finishes
→ Reality Return
→ parent frontier/evidence update
→ exact parent acceptance check
→ continue, park, block, or close
```

---

## 8. Scale and fit are multidimensional

Another current development is that "bounded" and "small" should not be treated as synonyms.

Useful dimensions include:

- **semantic scale** — how large the meaning/problem space is;
- **execution grain** — how much one run is allowed to change;
- **search scale** — how many alternatives or trials may be explored;
- **recovery scale** — how much state/proof must survive interruption or handoff.

Fit is therefore not only "which model is strongest."

Fit can include:

- problem shape;
- model capability;
- tool capability;
- context available;
- authority boundary;
- search budget;
- proof requirement;
- recovery requirement;
- cost and latency when they are materially relevant.

---

## 9. Emergent-work routing

Deep execution often discovers work that did not exist at the start.

That work should not silently widen the current box.

Material emergent work needs an explicit route, for example:

- absorb into the current parent frontier;
- open a bounded child box;
- return to the parent for decision;
- defer / park;
- preserve as evidence only;
- drop as non-material.

The important property is not the exact label.

The important property is that newly discovered work has a visible disposition and does not become hidden scope expansion.

---

## 10. Exact-scope acceptance

The current direction treats terminal claims as scope-bound.

Before saying that a whole parent/development problem is complete, ask:

1. What exact scope is being closed?
2. What acceptance surface belongs to that same scope?
3. Does that acceptance actually pass?
4. Does the proof support a claim at that scope?
5. Are material frontier and emergent-work obligations resolved?
6. Is the result a real closeout, or only a local success?

This is stricter than "the loop has no more registered tasks."

---

## 11. Current working architecture

The current working model can be summarized as:

```text
Progressive B outer discovery
→ define/update target and uncertainty

Discovery / Probe
→ expose candidate directions

Field-level degrees of freedom
→ declare what may vary

Search Epoch
→ own one logical search problem

Search Run
→ execute one bounded attempt

Locked Execution Box
→ preserve scope, authority, evidence and acceptance

Reality Return
→ bring observed result back to the parent

Frontier update
→ retain live candidates / unresolved evidence

Comparison / BBR-style update
→ identify current best-known direction

Exact-scope acceptance
→ decide whether the parent can actually close

repeat as needed
```

---

## 12. What is relatively strong vs still provisional

### Relatively strong current direction

- outer discovery and inner execution should remain distinct;
- child/local success must not silently widen into parent success;
- frontier coverage is not the same as acceptance;
- terminal claims should bind to exact-scope acceptance;
- Reality Return should be able to change the parent frontier;
- best-known convergence is safer than claiming an absolute optimum.

### Still provisional

- whether **Search Epoch / Search Run** should become permanent public terms;
- the exact public shape of **Locked Execution Box**;
- how much BBR-style comparison belongs in the public method;
- whether advanced search semantics belong in the main README or a separate advanced guide;
- whether this development becomes v0.2, a later version, or remains an optional layer;
- what minimum example is enough to prove that the added machinery improves real use.

---

## 13. Public claim ceiling

This file does **not** claim:

- broad validation;
- a final architecture;
- a universal search framework;
- that every Progressive B loop needs this full machinery;
- that an empty frontier proves the target is accepted;
- that current internal terminology is final public terminology.

The current claim is narrower:

> Progressive B Discovery has developed beyond the original simple public loop, and the current frontier is exploring how to preserve search depth, local execution, Reality Return, frontier state, and exact-scope acceptance without losing the simplicity of the original method.

---

## 14. Integration gate before changing the public baseline

Before promoting this development into the stable method, re-audit alignment across:

1. `README.md`;
2. `docs/quick-start.md`;
3. `prompts/progressive-b-discovery-prompt.md`;
4. `templates/checkpoint-template.md`;
5. `templates/construction-trail-template.md`;
6. `templates/agent-box-template.md`;
7. `templates/human-feedback-template.md`;
8. the public examples.

Promotion should preserve both sides:

```text
simple first loop for new users
+
deeper search / execution machinery when the problem actually needs it
```

A future baseline update should include at least one concrete example showing:

```text
parent Point B
→ child execution/search box
→ child PASS
→ Reality Return
→ parent still open
→ further evidence
→ exact parent acceptance
```

That example would test the critical rule in practice rather than only explaining it in prose.

---

## 15. Current state

```yaml
repo_baseline: v0.1.2
repo_state: early_public_method_seed
development_frontier: provisional
integrated_into_stable_public_method: false
README_changed_by_this_note: false
quick_start_changed_by_this_note: false
prompt_changed_by_this_note: false
templates_changed_by_this_note: false
examples_changed_by_this_note: false
broad_validation_claim: false
```
