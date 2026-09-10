---
type: Phase Start Gate
title: 000-A — Phase Intent, Intake Scope, Evidence Posture & Subphase Planning
description: Mandatory start gate for tailoring Phase 000 to a cloned project's actual intake needs before substantive intake work begins.
tags: [phase-000, start-gate, intake, planning, evidence]
---

# 000-A — Phase Intent, Intake Scope, Evidence Posture & Subphase Planning

## Purpose

This start gate determines how Phase 000 should be executed for the cloned project.

It must be completed before substantive intake subphases are defined or performed.

The gate exists to prevent two common failures:

1. forcing every project through a fixed document sequence regardless of context; and
2. allowing an initially compelling solution idea, incumbent structure, or stakeholder assertion to harden into design authority before the project is adequately understood.

`000-A` plans intake. It does not itself complete intake and does not begin Jackson concept discovery.

## Governing Phase 000 contracts

Before planning the phase, review:

- [Phase 000 — Project Intake & Product Definition](index.md);
- [Phase 000 Intake Knowledge & Evidence Contract](intake-knowledge-contract.md);
- [Phase 000 Consolidation, Exit Review & Phase 001 Handoff Template](exit-review-template.md);
- the repository-wide [Phase Lifecycle Contract](../../methodology/phase-lifecycle.md);
- the [Canonical and Historical Knowledge Authority](../../methodology/knowledge-authority.md).

## 1. Restate the contemplated project neutrally

Capture the starting point without converting it into a solution model:

- What application, product, service, or software-enabled capability is being contemplated?
- What prompted the project now?
- What is believed to need improvement, creation, replacement, coordination, or support?
- Who supplied the current framing?
- Which statements are evidence-backed observations, stakeholder/source assertions, external constraints, assumptions, hypotheses, open questions, proposals, or intake decisions?

If the initial request already contains proposed features, concepts, architecture, or workflows, preserve them as labeled proposals or context rather than accepting them as design truth.

## 2. Establish intake evidence posture

Identify what information currently exists, what it can legitimately support, and how authoritative or uncertain it is.

Possible sources include:

- direct stakeholder statements;
- observed workflows or problems;
- policy, regulatory, legal, or contractual material;
- existing product documentation;
- existing software behavior;
- domain references;
- market or operational research;
- prior design documents;
- analytics or measurements;
- support history or incident evidence;
- informal proposals or conversations.

For material sources, consider:

- provenance;
- authority;
- freshness;
- scope;
- conflicts;
- uncertainty;
- consequence of being wrong.

Do not create false certainty merely to make the intake look complete.

## 3. Perform the Phase 000 coverage assessment

Every project must assess the required intake dimensions below. This is a **coverage requirement**, not a requirement for one file or subphase per dimension.

| Intake dimension | Planning disposition |
|---|---|
| Contemplated product/application definition | Adequate on entry / needs work / not applicable with rationale |
| Problem or opportunity context | Adequate on entry / needs work / not applicable with rationale |
| Actors, stakeholders, and materially affected parties | Adequate on entry / needs work / not applicable with rationale |
| Desired outcomes or changes sought | Adequate on entry / needs work / not applicable with rationale |
| Scope boundaries and non-goals | Adequate on entry / needs work / not applicable with rationale |
| Domain terminology and contextual distinctions | Adequate on entry / needs work / not applicable with rationale |
| Known external constraints | Adequate on entry / needs work / not applicable with rationale |
| Assumptions and hypotheses | Adequate on entry / needs work / not applicable with rationale |
| Open questions and uncertainty | Adequate on entry / needs work / not applicable with rationale |
| Evidence/source posture | Adequate on entry / needs work / not applicable with rationale |
| Legacy/current-state context | Adequate on entry / needs work / not applicable with rationale |

`Not applicable` requires a short rationale. It must not be used to avoid examining an inconvenient dimension.

Dimensions marked `needs work` become candidates for substantive Phase 000 workstreams.

## 4. Decide where separate subphases are justified

Do not mechanically translate the coverage table into eleven subphases.

Create a separate subphase when doing so materially improves:

- dependency safety;
- evidence reconciliation;
- stakeholder/authority clarity;
- ability to isolate a difficult ambiguity;
- reviewability;
- traceability;
- ability to revisit one conclusion without destabilizing unrelated intake work.

Related dimensions may be combined when they can be examined coherently without hiding dependencies or uncertainty.

Typical project-specific workstreams may include:

- product/problem definition;
- actor, stakeholder, and affected-party discovery;
- desired-outcome and project-boundary framing;
- domain terminology/context reconstruction;
- external constraint qualification;
- legacy/current-state intent reconstruction;
- evidence conflict and assumption reconciliation;
- uncertainty/open-question closure.

These are examples, not a canonical subphase list.

## 5. Establish dependency order

Order the required work so that later subphases do not depend on conclusions that have not yet been established.

Examples:

- terminology may need clarification before stakeholder statements can be reconciled;
- legacy intent may need reconstruction before deciding whether current behavior expresses a need or an old technical limitation;
- affected-party discovery may expose outcomes or scope boundaries that the initial sponsor omitted;
- an external constraint may need qualification before deciding whether it truly bounds the product or is only one interpretation.

Dependency safety is more important than maintaining a preferred alphabetical count.

## 6. Identify inherited-structure and solution-lock risks

Explicitly inspect the starting material for structures that could bias later concept design.

Potential risks include:

- proposed feature lists treated as requirements;
- database entities treated as domain truth;
- incumbent service/module boundaries treated as concept boundaries;
- current screens treated as the future interaction model;
- existing workflows treated as immutable needs;
- legacy terminology that conflates distinct purposes;
- implementation limitations presented as user requirements;
- stakeholder preferences presented as external constraints.

For each material risk, decide whether Phase 000 needs a dedicated de-biasing or intent-reconstruction workstream.

## 7. Define project-specific Phase 000 subphases

Create only the substantive subphases needed for this project.

For each proposed subphase, define:

- title;
- purpose;
- intake dimensions covered;
- inputs and evidence;
- key questions;
- dependencies;
- expected phase-record outputs;
- expected canonical knowledge affected;
- explicit exclusions;
- completion evidence;
- unresolved-item handoff.

Reserve the final project-specific subphase for Phase 000 consolidation, exit review, and Phase 001 handoff using [the Phase 000 exit-review template](exit-review-template.md).

## 8. Define canonical destinations

For each expected durable intake conclusion, identify where it should become current canonical knowledge.

A cloned project may use a compact `canonical/project/` family or another coherent topology. Do not create a directory or file merely to satisfy a template category.

At minimum, future readers must be able to discover the current authoritative statements for the project's:

- definition and context;
- actors/affected parties;
- intended outcomes;
- scope/non-goals;
- constraints;
- terminology;
- assumptions and unresolved questions.

Phase records may contain the richer evidence and reasoning history.

## 9. Define Phase 000 exit evidence

Before substantive work begins, confirm what evidence will demonstrate readiness for Phase 001.

The planned exit review must be capable of showing that:

- the product/application is understandable without hidden conversational context;
- the motivating problem/opportunity context is sufficiently clear for purpose analysis;
- important actors and affected parties are visible;
- intended outcomes are known without predetermining the solution;
- scope and non-goals constrain inquiry without freezing concept design;
- material terminology and external constraints are understandable;
- evidence, assertions, assumptions, hypotheses, proposals, and open questions are distinguishable;
- material legacy/current-state bias has been exposed where applicable;
- canonical intake knowledge reflects current truth;
- no final concept solution has been selected;
- no representation, architecture, or implementation work has begun.

## 10. Check whether the gate itself can pass

`000-A` may authorize substantive Phase 000 work only if there is enough starting context to define a responsible intake plan.

If the project is so underspecified that even the intake workstreams cannot be identified, record what precondition is missing rather than fabricating a regular-looking phase plan.

## Required output

The completed `000-A` record should end with:

1. neutral starting project statement;
2. evidence/source posture summary;
3. completed intake coverage assessment;
4. identified inherited-structure or solution-lock risks;
5. approved project-specific Phase 000 subphase sequence;
6. rationale and dependency order for that decomposition;
7. canonical knowledge destinations;
8. completion evidence for each substantive subphase;
9. planned final consolidation/exit-review subphase;
10. known intake risks, ambiguities, and open questions;
11. confirmation of implementation status.

## Gate outcome

Use one of:

- **READY TO BEGIN PHASE 000 SUBPHASES**
- **NOT READY — INTAKE PRECONDITIONS MISSING**

The gate itself must not declare Phase 000 complete.

## Implementation state

- **Readiness:** not ready
- **Execution:** not started
- **Authorization:** not yet
