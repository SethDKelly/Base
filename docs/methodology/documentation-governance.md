---
type: Documentation Governance Contract
title: Documentation Integrity & OKF Governance Contract
description: Defines repository-wide rules for OKF conformance, progressive disclosure, canonical ownership, cross-linking, anti-duplication, and documentation-drift control.
tags: [okf, documentation, governance, drift, coherence, indexing, references]
sources:
  - id: okf-v02
    resource: https://github.com/GoogleCloudPlatform/knowledge-catalog/blob/main/okf/SPEC.md
    title: Open Knowledge Format v0.2 Specification
---

# Documentation Integrity & OKF Governance Contract

## Purpose

A Base-derived repository must remain useful as a knowledge system throughout a long design process. Correct design conclusions are not enough if current truth becomes hard to find, indexes become stale, references break, or many phase documents restate conflicting versions of the same rule.

This contract therefore governs every Base phase alongside the concept-design methodology.

## OKF bundle contract

`docs/` is the OKF v0.2 bundle root.

The bundle must follow these structural rules from OKF v0.2:[^okf-v02]

- every non-reserved `.md` concept document has parseable YAML frontmatter with a non-empty `type`;
- `index.md` and `log.md` are reserved filenames and are not ordinary concept documents;
- a non-root `index.md` contains no frontmatter;
- the bundle-root `index.md` may carry `okf_version` and should otherwise remain a progressive-disclosure entry point;
- standard Markdown links connect knowledge documents and form traversable graph edges;
- `sources` records provenance when a concept materially derives from another artifact;
- unknown producer-defined frontmatter may be used sparingly when it adds durable value.

[^okf-v02]: Open Knowledge Format v0.2 Specification.

## Progressive disclosure and indexes

Every directory that contains multiple knowledge documents or meaningful child directories should have an `index.md` unless omission is deliberately justified.

An index should answer quickly:

- what knowledge exists here;
- which documents are authoritative entry points;
- what each linked document contributes;
- which child areas should be traversed next.

Indexes must remain concise. They navigate knowledge; they must not become duplicate canonical documents.

When a concept document is created, moved, renamed, deprecated, or superseded, affected indexes must be reviewed in the same phase of work.

## Canonical ownership: one current rule, one natural home

Every durable design statement should have a natural canonical owner.

Before creating a new document, ask:

1. Does an existing canonical document already own this meaning?
2. Can that document be refined instead of creating another source of truth?
3. Is the proposed document a genuinely distinct semantic unit that merits its own identity and links?
4. Will a future reader know which document is authoritative if both exist?

Prefer a reference to existing knowledge over restating it.

A short local summary is acceptable when it materially aids comprehension, but it should link to the authoritative statement and must not introduce subtly different semantics.

## Phase records versus canonical knowledge

Phase records may repeat enough context to make historical reasoning understandable, but they must not become alternative canonical repositories.

Substantive phase work should:

- link to incoming canonical knowledge instead of copying it wholesale;
- record new analysis, alternatives, evidence, decisions, and unresolved issues;
- promote durable conclusions into their canonical owners;
- leave rejected or superseded reasoning in phase history rather than canonical current truth.

The [Canonical and Historical Knowledge Authority](knowledge-authority.md) governs conflicts between these layers.

## Cross-linking and reference discipline

Use standard Markdown links to express meaningful relationships among documents. OKF consumers may treat links as directed graph edges.[^okf-v02]

References should be purposeful rather than decorative. Link when the target supplies authority, prerequisite context, a dependency, rationale, evidence, a superseding rule, or the next relevant knowledge node.

Prefer stable bundle-relative or valid relative paths supported by OKF. When a file is moved or renamed, review inbound and outbound links affected by its path identity.

Use `sources` for provenance when a document derives claims or rules materially from external or internal source artifacts. Do not create a redundant bibliography when links or structured provenance already express the relationship.

## Frontmatter discipline

Use the smallest useful frontmatter. `type` is the only universally required field for ordinary concept documents under OKF v0.2.[^okf-v02]

Base concept documents should normally also provide concise `title` and `description` values because they improve indexing, search snippets, and generated navigation. `tags` should be meaningful rather than exhaustive.

Do not invent verification, freshness, provenance, or lifecycle metadata that cannot be supported.

## Drift and coherence hazards

Treat the following as documentation defects requiring disposition:

- two current documents asserting incompatible rules;
- the same current rule copied into many documents and drifting independently;
- phase history being cited as current truth after canonical knowledge changed;
- stale terminology surviving after a canonical rename or conceptual refinement;
- an index omitting important current knowledge or pointing at superseded material as primary;
- broken or misleading internal links;
- orphan concept documents with no discoverable incoming navigation or meaningful graph relationship;
- provisional conclusions losing their provisional status through repetition;
- deprecated knowledge lacking a clear current replacement where one exists;
- frontmatter or reserved-file usage that violates the adopted OKF version.

## Start-gate documentation check

Every `NNN-A` phase start gate must include a documentation/coherence planning check that:

- identifies the incoming canonical documents the phase will rely on;
- identifies unresolved or historical records that matter without treating them as current authority;
- determines expected canonical owners for durable outputs;
- identifies likely new documents only where distinct semantic identities are justified;
- identifies indexes and cross-links likely to require updates;
- checks for known documentation conflicts or drift that could bias the phase;
- confirms the planned subphases will reference rather than needlessly restate established knowledge.

## Subphase documentation discipline

Each substantive subphase should state which existing knowledge it consumes, which current documents it may change, and what new semantic knowledge—if any—requires a new document.

Do not create a document merely because a subphase exists. A subphase record and a canonical concept are different things.

## Exit-gate documentation integrity audit

Every phase exit review must verify:

- durable conclusions have been promoted to their canonical owners;
- canonical documents are mutually coherent to the extent affected by the phase;
- known superseded current statements have been corrected or explicitly lifecycle-managed;
- phase records remain historical evidence rather than competing authority;
- required indexes reflect the current corpus;
- important internal references resolve and point to the intended authority;
- new concept documents are discoverable through indexes and/or meaningful graph links;
- avoidable duplication introduced during the phase has been consolidated;
- ordinary concept documents and reserved files conform to the adopted OKF structural rules;
- carry-forwards name both their design destination and, where relevant, their canonical knowledge destination.

A phase is not ready to exit merely because its planned phase files exist.

## Refactoring documentation without rewriting history

Documentation structure may be improved as the design grows. When refactoring:

- preserve phase history;
- move current meaning to the clearest canonical owner;
- update links and indexes;
- avoid preserving duplicates solely for path nostalgia;
- record supersession when readers could otherwise mistake old material for current truth.

Knowledge coherence takes precedence over maintaining an accidental early file layout.

## Implementation boundary

This contract governs knowledge organization only. It does not authorize documentation generators, linters, CI checks, indexes produced by code, or other executable tooling during the Base concept-design lifecycle. Such tooling may be considered in a downstream process after concept-design closure.
