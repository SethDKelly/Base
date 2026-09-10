# Base

A cloneable, design-only repository template for taking a software product from project intake through completed concept design before implementation begins.

The design method is grounded in Daniel Jackson's software concept design methodology from *The Essence of Software*. The documentation corpus under [`docs/`](docs/index.md) is organized as an Open Knowledge Format (OKF) v0.2 knowledge bundle.

## Core rule

**Design must be complete before implementation becomes ready.**

During the design lifecycle, implementation remains:

- **Not ready**
- **Not started**
- **Not yet authorized**

The design process may identify implementation implications, constraints, risks, or questions, but it must not create application code, schemas, persistence implementations, APIs, infrastructure, executable scaffolding, or other implementation artifacts.

## How this template is used

1. Clone or create a repository from this template.
2. Begin with **Phase 000 — Project Intake & Product Definition**.
3. At the start of every high-level phase, perform its phase-intent/start-gate review and derive the dependency-safe subphases actually required for that project.
4. Complete those subphases as design work only.
5. Finish the phase with a consolidation, exit review, and explicit handoff.
6. Continue through the full Jackson-aligned concept-design lifecycle.
7. Only after final concept-design closure may the project be marked **Implementation ready / not started**.

The numbered lifecycle in this repository is an operational structure built around Jackson's methodology. It is **not** presented as a phase numbering prescribed by Jackson himself.

## Documentation model

The `docs/` bundle separates:

- **Canonical knowledge** — current design truth: purposes, concepts, invariants, synchronizations, authority boundaries, design decisions, and other durable conclusions.
- **Phase records** — chronological evidence of discovery, analysis, alternatives, decisions, reviews, and handoffs.

Phase records do not become canonical merely because they were written earlier. Durable conclusions are promoted into canonical knowledge, and superseded conclusions remain historical evidence rather than competing current truth.

Start at [`docs/index.md`](docs/index.md).
