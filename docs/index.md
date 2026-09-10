---
type: Knowledge Bundle Index
title: Base Design Knowledge
okf_version: "0.2"
description: Canonical design knowledge and phase records for a design-only, Jackson-aligned software concept design lifecycle.
tags: [design, concept-design, okf, template]
---

# Base Design Knowledge

This directory is the Open Knowledge Format (OKF) v0.2 knowledge bundle for the repository.

The bundle exists to guide a cloned project from initial intake through complete software concept design without beginning application implementation.

## Read first

- [Methodology authority](methodology/authority.md) — what governs the design process and what this template does not claim.
- [Jackson-aligned concept-design lifecycle](methodology/concept-design-lifecycle.md) — the adopted high-level sequence from Phase 000 through Phase 011.
- [Design-only guardrails](methodology/design-only-guardrails.md) — the implementation prohibition and readiness states.
- [Phase lifecycle](methodology/phase-lifecycle.md) — how every high-level phase starts, is subdivided, exits, and hands off.
- [Knowledge authority model](methodology/knowledge-authority.md) — how canonical current truth is separated from historical phase evidence.
- [Design phases](phases/index.md) — the complete high-level phase catalog and refinement status.
- [Phase 000](phases/000/index.md) — project intake and product-definition entry point for a cloned repository.

## Knowledge topology

### Canonical knowledge

Durable design truth belongs under [`canonical/`](canonical/index.md). This is where a cloned project records the current authoritative understanding of its purposes, concepts, invariants, synchronizations, design principles, decisions, and other stable design knowledge.

### Phase records

Chronological discovery and review work belongs under [`phases/`](phases/index.md). These records explain how decisions were reached, what alternatives were considered, what evidence was reviewed, and why a phase was allowed to hand off.

Phase records are evidence, not automatically current truth.

## Adopted high-level lifecycle

The Base lifecycle is:

`000 Project Intake` → `001 Purpose` → `002 Concept Discovery` → `003 Concept Specification` → `004 Modularity & Boundary` → `005 Composition & Synchronization` → `006 Dependence & Scope` → `007 Mapping` → `008 Familiarity & Reuse` → `009 Integrity` → `010 Misfit & Adversarial Validation` → `011 Methodology Closure`.

These phases are methodological obligations, not fixed quantities of work. Each phase begins by deriving the dependency-safe substantive subphases required by the actual project.

## Lifecycle invariant

Until the full design lifecycle is complete, implementation status remains:

- **Readiness:** not ready
- **Execution:** not started
- **Authorization:** not yet

Final Phase 011 concept-design closure may change readiness to **ready** and authorize a downstream representation/architecture/implementation design process. It must not start application implementation itself.
