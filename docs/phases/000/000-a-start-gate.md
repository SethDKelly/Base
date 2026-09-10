---
type: Phase Start Gate
title: 000-A — Phase Intent, Intake Scope, Evidence Posture & Subphase Planning
description: Mandatory start gate for tailoring Phase 000 to a cloned project's actual intake needs before substantive intake work begins.
tags: [phase-000, start-gate, intake, planning]
---

# 000-A — Phase Intent, Intake Scope, Evidence Posture & Subphase Planning

## Purpose

This start gate determines how Phase 000 should be executed for the cloned project.

It must be completed before substantive intake subphases are defined or performed.

The gate exists to prevent two common failures:

1. forcing every project through a fixed checklist regardless of context; and
2. allowing an initially compelling solution idea to harden into design authority before the problem and product are adequately defined.

## Required review

### 1. Restate the contemplated project

Capture the project in neutral terms:

- What application, product, service, or software-enabled capability is being contemplated?
- What prompted the project?
- What is believed to need improvement, creation, replacement, or support?
- Which statements are observed facts, stakeholder claims, assumptions, or hypotheses?

Do not yet convert these into candidate software concepts.

### 2. Determine intake evidence posture

Identify what information currently exists and how authoritative it is.

Possible sources include:

- direct stakeholder statements;
- observed workflows or problems;
- policy or regulatory material;
- existing product documentation;
- existing software behavior;
- domain references;
- market research;
- prior design documents;
- informal proposals or conversations.

Record meaningful conflicts, gaps, stale information, or uncertain provenance.

### 3. Identify intake dimensions that need deliberate work

Determine which dimensions require their own subphase. Typical examples include:

- product/application definition;
- problem and opportunity framing;
- actor/stakeholder and affected-party discovery;
- outcome and success-intent framing;
- scope, non-goals, and boundary definition;
- domain terminology and context;
- external policy, regulatory, contractual, or operational constraints;
- legacy-system intent reconstruction;
- evidence and assumption reconciliation;
- uncertainty, risk, and unresolved-question inventory.

These are candidates, not a mandatory list.

### 4. Establish dependency order

Order the required work so that later subphases do not depend on conclusions that have not yet been established.

Examples:

- terminology may need clarification before stakeholder statements can be reconciled;
- legacy intent may need reconstruction before determining whether a stated requirement is intentional or accidental;
- product scope may need refinement after actor and outcome discovery.

Dependency safety is more important than maintaining a preferred alphabetical count.

### 5. Guard against premature solutioning

Review proposed intake work for accidental concept or implementation commitment.

During Phase 000, avoid prematurely fixing:

- software concept names or boundaries;
- data models;
- service boundaries;
- UI structures;
- workflows treated as immutable because an incumbent system uses them;
- technical architecture;
- persistence or integration technologies;
- implementation sequencing.

If a solution idea is important context, record it as a proposal or hypothesis, not as design truth.

### 6. Define project-specific Phase 000 subphases

Create only the subphases needed for this project.

For each proposed subphase, define:

- title;
- purpose;
- inputs;
- key questions;
- expected design/intake outputs;
- dependencies;
- explicit exclusions;
- completion evidence.

Reserve the final subphase for Phase 000 consolidation, exit review, and handoff.

### 7. Define canonical destinations

For each expected durable intake conclusion, identify where it should become current canonical knowledge.

Do not use the phase document itself as the only durable source of truth.

### 8. Confirm exit evidence

Before substantive Phase 000 work begins, confirm what evidence will be required to establish that the project is ready to enter Jackson-aligned concept design.

At minimum this should cover:

- understandable product/application definition;
- problem-space framing;
- actor or stakeholder context;
- intended outcomes;
- scope and non-goals;
- assumptions and uncertainties;
- material external constraints;
- canonical promotion completeness;
- absence of premature concept lock-in;
- absence of implementation work.

## Required output

The completed `000-A` record should end with:

1. the approved Phase 000 subphase sequence;
2. rationale for the decomposition;
3. identified dependencies;
4. canonical knowledge destinations;
5. known intake risks or ambiguities;
6. the planned final exit-review subphase;
7. confirmation of implementation status.

## Gate outcome

Use one of:

- **READY TO BEGIN PHASE 000 SUBPHASES**
- **NOT READY — INTAKE PRECONDITIONS MISSING**

The gate itself must not declare Phase 000 complete.

## Implementation state

- **Readiness:** not ready
- **Execution:** not started
- **Authorization:** not yet
