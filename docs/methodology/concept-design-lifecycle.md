---
type: Methodology Lifecycle
title: Jackson-Aligned Concept Design Lifecycle
description: Defines the reviewed high-level Base lifecycle from pre-methodology project intake through complete concept-design closure.
tags: [methodology, lifecycle, concept-design, jackson, design-only]
---

# Jackson-Aligned Concept Design Lifecycle

## Status and authority

This document defines the reviewed high-level lifecycle used by Base.

The lifecycle operationalizes Daniel Jackson's software concept-design methodology into dependency-safe project phases. The numbering and phase boundaries are Base conventions; they are not presented as an official phase sequence prescribed by Jackson.

Every high-level phase remains governed by the [Phase Lifecycle Contract](phase-lifecycle.md), including its mandatory `NNN-A` start gate, dynamically derived substantive subphases, final consolidation/exit review, and explicit handoff.

## Lifecycle

| Phase | Name | Primary methodological purpose |
|---|---|---|
| `000` | Project Intake & Product Definition | Define the contemplated product, problem space, actors, outcomes, scope, constraints, evidence posture, assumptions, and uncertainties before concept design begins. |
| `001` | Purpose, Context, Need & Success Framing | Establish the human purposes, needs, contextual conditions, desired improvements, success framing, and tensions that concepts must ultimately justify. |
| `002` | Concept Discovery, Candidate Inventory & Divergent Exploration | Discover alternative candidate concepts as coherent user-facing behavioral units without prematurely converging on the first decomposition. |
| `003` | Concept Definition, Operational Principles & Behavioral Specification | Define viable concepts through purpose, operational principle, abstract state, actions, invariants, conditions, outputs, and other observable behavioral semantics. |
| `004` | Concept Modularity, Boundary, Specificity, Completeness & Independence | Challenge whether proposed concepts are correctly factored, independently meaningful, complete for their purposes, sufficiently specific, and appropriately generic. |
| `005` | Concept Composition, Synchronization, Automation & Synergy | Define how independent concepts combine through explicit synchronization to produce application behavior without hiding conceptual dependence. |
| `006` | Concept Dependence, Product-Family, Subset & Scope Analysis | Distinguish intrinsic concept independence from extrinsic application inclusion dependencies and identify coherent product/application subsets and scope boundaries. |
| `007` | Concept Mapping, Interaction Semantics & User-Visible Representation | Map concept semantics into perceivable, invocable, understandable user-facing representations and interactions without implementing an interface. |
| `008` | Familiarity, Reuse, Genericity & Concept-Catalog Refinement | Challenge unnecessary novelty, compare against familiar concepts, improve genericity and naming, and justify concepts that truly require innovation. |
| `009` | Concept Integrity, Cross-Concept Coherence & Interference Audit | Verify that every concept preserves its independent promise and purpose when composed with the complete concept system. |
| `010` | Scenario, Misfit, Exception, Failure & Adversarial Design Validation | Exercise the conceptual design against representative, edge, temporal, failure, misuse, recovery, authority, and domain-misfit scenarios. |
| `011` | Methodology Completeness, Canonical Consolidation & Concept-Design Closure | Audit the complete design against the methodology, reconcile canonical truth, close or disposition gaps, and determine whether concept design is complete. |

## Dependency-safe progression

The lifecycle is deliberately not a mechanical transcription of a book chapter sequence.

Its progression is:

1. **Frame** — establish the project and the purposes to be served (`000–001`).
2. **Diverge** — discover candidate conceptual structures (`002`).
3. **Define and factor** — specify concepts and challenge their boundaries before relying on them (`003–004`).
4. **Compose and scope** — make cross-concept behavior and application-level dependence explicit (`005–006`).
5. **Map** — ensure the conceptual model can be understood and controlled through user-visible behavior (`007`).
6. **Refine and attack** — challenge familiarity, integrity, interference, exceptions, failures, and misfits (`008–010`).
7. **Close** — demonstrate methodology-wide completeness and consolidate authoritative design truth (`011`).

Later analysis may require reopening earlier conclusions. The lifecycle therefore expresses dependency order, not an irreversible waterfall.

## Cross-cutting design obligations

The following concerns remain active throughout the lifecycle even when one phase provides a dedicated audit:

- purpose traceability;
- specificity;
- completeness;
- independence;
- familiarity;
- integrity;
- genericity;
- observable semantics;
- authority and actor implications;
- temporal and historical semantics;
- misfit awareness;
- evidence and uncertainty discipline;
- implementation abstinence.

A later dedicated phase does not authorize earlier phases to ignore that concern.

## Representation and implementation boundary

Completion of concept design does not mean that representation design or implementation has already been performed.

During `000–010`, implementation remains:

- **Readiness:** not ready
- **Execution:** not started
- **Authorization:** not yet

Phase `011` may change the state only after a successful methodology-completeness and design-closure determination to:

- **Readiness:** ready
- **Execution:** not started
- **Authorization:** concept design authorizes subsequent representation/architecture/implementation design work under an appropriate downstream process

No Base concept-design phase may create application implementation merely because implementation implications have become clearer.

## Refinement status

This lifecycle establishes the high-level phase intentions only.

Each phase must be refined before substantive use so that its template declaration adequately establishes methodological intent, entry/exit criteria, durable knowledge expectations, design-only exclusions, and start-gate guidance. Its project-specific substantive subphases remain dynamically derived by the phase start gate rather than pre-populated as a fixed sequence.
