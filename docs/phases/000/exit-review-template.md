---
type: Phase Exit Review Template
title: Phase 000 Consolidation, Exit Review & Phase 001 Handoff Template
description: Phase-specific completion and handoff criteria for determining whether project intake is sufficient to begin Jackson-aligned purpose and need framing.
tags: [phase-000, exit-review, handoff, phase-001, template]
---

# Phase 000 Consolidation, Exit Review & Phase 001 Handoff Template

## Purpose

The final project-specific Phase 000 subphase uses this template to determine whether intake has done enough to support Phase 001 without carrying hidden context, false certainty, or premature solution structure forward.

This is a Phase-000-specific specialization of the repository-wide [Phase Lifecycle Contract](../../methodology/phase-lifecycle.md).

The final subphase letter is determined by the project's `000-A` decomposition. This file is therefore a reusable exit-review template, not a predetermined `000-X` phase record.

## Review inputs

Review at least:

- the approved `000-A` subphase plan;
- all completed Phase 000 subphase records;
- current canonical intake knowledge;
- unresolved questions and assumptions;
- material evidence and conflicts;
- any solution proposals recorded during intake;
- the Phase 001 high-level definition.

## 1. Planned-work disposition

Confirm that every subphase planned by `000-A` is one of:

- completed;
- superseded by a documented refinement;
- explicitly removed because it became unnecessary;
- still incomplete and therefore blocking exit.

Document existence alone is not completion evidence.

## 2. Intake coverage review

Assess every required intake dimension from the [Phase 000 Intake Knowledge & Evidence Contract](intake-knowledge-contract.md).

For each dimension, record one of:

- **Established** — sufficiently understood for Phase 001;
- **Established with uncertainty** — useful current understanding exists and uncertainty is explicit;
- **Not applicable** — genuinely irrelevant, with rationale;
- **Incomplete — carry-forward** — unresolved but does not prevent purpose/need analysis;
- **Incomplete — blocking** — Phase 001 would be distorted by proceeding.

Required dimensions are:

- contemplated product/application definition;
- problem or opportunity context;
- actors, stakeholders, and materially affected parties;
- desired outcomes or changes sought;
- scope boundaries and non-goals;
- domain terminology and contextual distinctions;
- known external constraints;
- assumptions and hypotheses;
- open questions and uncertainty;
- evidence/source posture;
- legacy/current-state context when applicable.

## 3. Evidence and uncertainty audit

Confirm that material statements can be distinguished as appropriate among:

- evidence-backed observations;
- stakeholder/source assertions;
- external constraints;
- assumptions;
- hypotheses;
- open questions;
- proposals/solution ideas;
- intake decisions.

Check specifically for:

- claims presented as fact without adequate basis;
- stale or weak evidence being treated as current authority;
- unresolved source conflicts hidden by summary prose;
- assumptions that became requirements merely through repetition;
- high-consequence uncertainty that lacks an explicit disposition.

## 4. Legacy and inherited-structure audit

If an existing product, repository, workflow, or system was studied, verify that Phase 000 did not accidentally preserve its decomposition as future design authority.

Record any inherited behavior that remains ambiguous between:

- genuine domain/user need;
- external constraint;
- historical policy;
- implementation artifact;
- accidental behavior;
- unknown rationale.

A material ambiguity that would predetermine concept design should block exit or be explicitly carried to the earliest phase capable of resolving it.

## 5. Premature-solution audit

Search Phase 000 conclusions for solution lock-in.

Challenge statements that presume:

- final software concepts;
- final feature decomposition;
- fixed workflows;
- UI structures;
- data models or schemas;
- services or modules;
- API boundaries;
- technical architecture;
- infrastructure or framework choices;
- implementation sequencing.

A solution idea may remain as labeled evidence or a proposal. It must not enter Phase 001 as unquestioned design truth.

## 6. Canonical authority review

Confirm that durable current intake conclusions have canonical homes and that phase records are not being used as the only current source of truth.

Verify that:

- canonical knowledge reflects the best current intake understanding;
- known superseded statements are not still presented as current;
- assumptions and open questions remain visibly provisional;
- evidence/rationale can be reached from canonical knowledge where useful;
- canonical intake material remains concise enough for progressive disclosure.

## 7. Phase 001 readiness test

Ask whether a competent reader can begin **Phase 001 — Purpose, Context, Need & Success Framing** using repository knowledge alone.

The answer should be yes to all of the following:

- Is the contemplated product/application understandable?
- Is the motivating context sufficiently clear to investigate purposes and needs?
- Are relevant actors and affected parties visible enough to avoid obvious stakeholder omission?
- Are desired outcomes recorded without assuming the final solution?
- Are scope and non-goals clear enough to constrain Phase 001 inquiry?
- Are material domain terms and external constraints understandable?
- Can the reader tell what is known, asserted, assumed, hypothesized, proposed, and unresolved?
- Can Phase 001 revisit intake framing if purpose analysis exposes a flaw?
- Has Phase 000 avoided preselecting the concept solution?

If any material answer is no, Phase 000 should not exit.

## 8. Carry-forward discipline

A Phase 000 issue may be carried forward only when:

- it does not undermine the basic intelligibility of the project;
- purpose/need discovery can proceed without pretending the issue is resolved;
- its uncertainty is explicit;
- its destination or reconsideration trigger is identified.

Typical destinations may include:

- Phase 001 for purpose/need clarification;
- Phase 002 for candidate concept exploration;
- a later concept-design phase when the issue genuinely cannot be resolved earlier.

Do not use carry-forward to bypass missing foundational intake.

## 9. Exit decision

Use the repository-wide outcomes:

### PASS

Phase 000 fulfills its intake purpose and Phase 001 may begin.

### PASS WITH CARRY-FORWARD

Phase 000 fulfills its intake purpose, while explicitly identified non-blocking uncertainties continue with named destinations or triggers.

### NOT READY TO EXIT

Material intake gaps, evidence conflicts, hidden assumptions, or premature solution commitments would make Phase 001 unreliable. Define additional Phase 000 work before closing.

## 10. Required Phase 001 handoff

A successful exit must record:

- concise current project/product definition;
- motivating problem/opportunity context;
- relevant actor/stakeholder/affected-party context;
- desired outcomes/change sought;
- scope and non-goals;
- material terminology;
- external constraints;
- assumptions and hypotheses still active;
- unresolved questions and carry-forwards;
- important evidence conflicts or interpretation cautions;
- quarantined solution proposals that Phase 001 must not treat as authority;
- canonical documents that constitute the intake baseline;
- confirmation that Phase 001 may revisit intake conclusions when warranted;
- implementation readiness state.

## Implementation state at Phase 000 exit

Even after a successful Phase 000 exit:

- **Readiness:** not ready
- **Execution:** not started
- **Authorization:** not yet

The only authorized next step is the Phase 001 start gate and subsequent concept-design work.
