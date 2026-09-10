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
- [Design-only guardrails](methodology/design-only-guardrails.md) — the implementation prohibition and readiness states.
- [Phase lifecycle](methodology/phase-lifecycle.md) — how every high-level phase starts, is subdivided, exits, and hands off.
- [Knowledge authority model](methodology/knowledge-authority.md) — how canonical current truth is separated from historical phase evidence.
- [Phase 000](phases/000/index.md) — project intake and product-definition entry point.

## Knowledge topology

### Canonical knowledge

Durable design truth belongs under [`canonical/`](canonical/index.md). This is where a cloned project records the current authoritative understanding of its purposes, concepts, invariants, synchronizations, design principles, decisions, and other stable design knowledge.

### Phase records

Chronological discovery and review work belongs under [`phases/`](phases/index.md). These records explain how decisions were reached, what alternatives were considered, what evidence was reviewed, and why a phase was allowed to hand off.

Phase records are evidence, not automatically current truth.

## Lifecycle invariant

Until the full design lifecycle is complete, implementation status remains:

- **Readiness:** not ready
- **Execution:** not started
- **Authorization:** not yet

Final design closure may change only readiness to **ready**. It must not start implementation.
