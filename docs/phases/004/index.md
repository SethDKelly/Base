---
type: Phase Definition
title: Phase 004 — Concept Modularity, Boundary, Specificity, Completeness & Independence
description: Audits whether proposed concepts are correctly factored, sufficiently specific, behaviorally complete, independently meaningful, and appropriately generic before composition.
tags: [phase-004, modularity, specificity, completeness, independence, genericity, concept-design]
---

# Phase 004 — Concept Modularity, Boundary, Specificity, Completeness & Independence

## Role in the lifecycle

Phase 004 is the deliberate convergence and factoring audit that occurs before cross-concept composition becomes authoritative. It challenges whether the concepts specified in Phase 003 are actually good concepts rather than merely plausible domain decompositions.

## Methodological intention

Refine concept boundaries so that each retained concept serves a coherent purpose, contains the behavior necessary to fulfill that purpose, can be understood independently of other application concepts, and is generic where broader applicability improves the design.

## Primary design questions

- Is each concept serving one coherent purpose, or has unrelated functionality been combined?
- Is the behavior required to fulfill that purpose complete within the concept?
- Can the concept be understood and specified independently?
- Are references to other application concepts actually hidden dependence that should be removed or represented later through synchronization?
- Should a concept be split, merged, reframed, rejected, or generalized?
- Are generic parameters or broader target types needed to avoid accidental application-specific coupling?
- Does the concept remain user-facing, semantic, behavioral, and purposive after refinement?

## Prerequisites

Phase 003 must provide sufficiently explicit behavioral specifications to make structural weaknesses visible and reviewable.

## Expected durable outputs

Typically includes:

- stabilized concept boundaries;
- specificity, completeness, and independence findings;
- split/merge/reframe/reject decisions and rationale;
- genericity decisions and parameters where appropriate;
- revised concept specifications;
- remaining composition questions for Phase 005.

## Explicit exclusions

This phase must not replace conceptual independence with implementation modularity. Packages, services, bounded contexts, persistence ownership, deployment units, and code dependencies are outside scope.

## Entry criteria

Concept candidates have explicit purposes, operational principles, and behavioral specifications adequate for modularity analysis.

## Exit criteria

The phase may exit when the retained concept set is sufficiently stable for composition; concepts are independently comprehensible; overloaded and fragmentary boundaries have been addressed; important genericity opportunities have been resolved or carried forward; and no implementation decomposition has been substituted for concept factoring.

## Control structure

The phase begins with a mandatory `004-A` start gate, which derives the project-specific modularity and boundary-review subphases. The final subphase is the Phase 004 consolidation, exit review, and handoff.

## Implementation state

- **Readiness:** not ready
- **Execution:** not started
- **Authorization:** not yet
