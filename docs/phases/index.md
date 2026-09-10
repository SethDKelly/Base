---
type: Knowledge Index
title: Design Phase Records
description: Chronological records and high-level phase definitions for the complete Base design lifecycle.
tags: [phases, history, design, evidence, lifecycle]
---

# Design Phase Records

This directory contains the chronological work history and high-level phase definitions for the Base design lifecycle.

Phase records are evidence of how the design was developed. They are not automatically the current source of truth; durable conclusions belong under [`../canonical/`](../canonical/index.md).

The adopted high-level sequence is defined by the [Jackson-Aligned Concept Design Lifecycle](../methodology/concept-design-lifecycle.md).

## Phase control structure

Each high-level phase:

1. begins with an `NNN-A` start gate;
2. reviews the phase intention and incoming handoff;
3. derives only the dependency-safe substantive subphases required by the project;
4. proceeds through those design subphases;
5. ends with a consolidation, exit review, and handoff;
6. updates canonical knowledge as durable conclusions become established.

The phase definitions below establish high-level methodological obligations. They do **not** pre-populate a fixed B–X work sequence for every cloned project.

## Lifecycle

- [000 — Project Intake & Product Definition](000/index.md) — pre-methodology project definition and intake.
- [001 — Purpose, Context, Need & Success Framing](001/index.md) — establish why the product should exist and what meaningful purposes the design must serve.
- [002 — Concept Discovery, Candidate Inventory & Divergent Exploration](002/index.md) — explore alternative candidate concepts without premature convergence.
- [003 — Concept Definition, Operational Principles & Behavioral Specification](003/index.md) — specify viable concepts through purpose and observable behavior.
- [004 — Concept Modularity, Boundary, Specificity, Completeness & Independence](004/index.md) — challenge and stabilize concept factoring before composition.
- [005 — Concept Composition, Synchronization, Automation & Synergy](005/index.md) — define explicit cross-concept behavior while preserving independence.
- [006 — Concept Dependence, Product-Family, Subset & Scope Analysis](006/index.md) — distinguish concept independence from application-level inclusion dependence and scope.
- [007 — Concept Mapping, Interaction Semantics & User-Visible Representation](007/index.md) — map conceptual semantics into understandable user-facing behavior without implementation.
- [008 — Familiarity, Reuse, Genericity & Concept-Catalog Refinement](008/index.md) — challenge unnecessary novelty and improve reuse, naming, and genericity.
- [009 — Concept Integrity, Cross-Concept Coherence & Interference Audit](009/index.md) — verify that composed concepts preserve their independent promises.
- [010 — Scenario, Misfit, Exception, Failure & Adversarial Design Validation](010/index.md) — attack the mature design with scenarios likely to expose conceptual weakness or misfit.
- [011 — Methodology Completeness, Canonical Consolidation & Concept-Design Closure](011/index.md) — perform the whole-methodology completion audit and, if justified, authorize downstream design work.

## Template refinement status

The complete high-level lifecycle has been reviewed and adopted.

The next Base-template activity is to refine each phase definition and its start-gate guidance in dependency order so that future cloned repositories have strong instructions for planning and executing that phase. This refinement must preserve dynamic project-specific subphase derivation rather than turning Base into a fixed checklist of predetermined B–X documents.

## Implementation invariant

Through Phases `000–010`, and until Phase `011` successfully closes:

- **Readiness:** not ready
- **Execution:** not started
- **Authorization:** not yet

Successful Phase `011` closure may change the state to **implementation ready / not started**, meaning the completed conceptual design may hand off to an appropriate downstream representation/architecture/implementation design process. It does not itself begin implementation.
