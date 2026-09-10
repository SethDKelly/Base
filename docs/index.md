---
okf_version: "0.2"
---

# Base Design Knowledge

This directory is the Open Knowledge Format (OKF) v0.2 knowledge bundle for Base. It guides a cloned project from project intake through completed Jackson-aligned software concept design without beginning application implementation.

## Start here

- [Methodology](methodology/) — design authority, lifecycle, documentation governance, knowledge authority, and design-only guardrails.
- [Design phases](phases/) — Phase 000 intake followed by Phases 001–011 of the Base Jackson-aligned lifecycle.
- [Canonical knowledge](canonical/) — the compact current design truth produced by a cloned project.

## Governing contracts

- [Concept Design Methodology Authority](methodology/authority.md) — methodological authority and interpretation rules.
- [Jackson-Aligned Concept Design Lifecycle](methodology/concept-design-lifecycle.md) — reviewed high-level lifecycle.
- [Phase Lifecycle Contract](methodology/phase-lifecycle.md) — mandatory start gate, dynamic subphase derivation, exit review, and handoff.
- [Documentation Integrity & OKF Governance Contract](methodology/documentation-governance.md) — corpus coherence, indexability, cross-linking, anti-duplication, and drift control.
- [Canonical and Historical Knowledge Authority](methodology/knowledge-authority.md) — current truth versus phase evidence.
- [Design-Only Guardrails](methodology/design-only-guardrails.md) — implementation prohibition and readiness states.

## Knowledge model

Durable current design meaning belongs under [canonical knowledge](canonical/). Chronological discovery, alternatives, reviews, and handoffs belong under [phase records](phases/). Phase records are evidence, not automatically current truth.

Documents should link to existing authoritative knowledge rather than restating it. Directory indexes provide progressive disclosure; ordinary concept documents carry OKF frontmatter and form a traversable graph through standard Markdown links.

## Lifecycle invariant

Until the full concept-design lifecycle is complete:

- **Readiness:** not ready
- **Execution:** not started
- **Authorization:** not yet

Successful Phase 011 closure may change readiness to **ready** while execution remains **not started**.
