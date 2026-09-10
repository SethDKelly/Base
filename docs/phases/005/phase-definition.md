---
type: Phase Definition
title: Phase 005 — Concept Composition, Synchronization, Automation & Synergy
description: Defines how independent concepts combine through explicit synchronization to create application behavior without collapsing conceptual boundaries.
tags: [phase-005, composition, synchronization, automation, synergy, concept-design]
---

# Phase 005 — Concept Composition, Synchronization, Automation & Synergy

## Role in the lifecycle

Phase 005 moves from individually coherent concepts to application-level behavior. It defines how concepts interact while preserving the independence established in Phase 004.

## Methodological intention

Make cross-concept behavior explicit through synchronization rather than hidden references or merged concepts, and identify where composition creates useful automation or synergy.

## Primary design questions

- Which concept actions must synchronize to produce intended application behavior?
- What action or condition triggers each synchronization?
- Which participating actions, inputs, outputs, and conditions are involved?
- What authority initiates or constrains the synchronized behavior?
- Does a synchronization reveal that an earlier concept should actually be decomposed?
- Where does composition create useful automation or synergy?
- Does any synchronization undermine a concept's independence or purpose?

## Prerequisites

Phase 004 must have produced a sufficiently stable set of independently meaningful concepts with defensible boundaries.

## Expected durable outputs

Typically includes synchronization catalog, trigger/participation semantics, input/output and condition relationships, application-level behavioral compositions, identified automation/synergy, decomposition corrections, and unresolved inclusion/dependence questions for Phase 006.

## Explicit exclusions

Synchronizations are design relationships, not event-bus topics, queues, RPC calls, HTTP endpoints, message schemas, workflow-engine definitions, orchestration code, or service contracts.

## Entry criteria

The concept set is stable enough that composition can be analyzed without relying on obviously defective or overloaded boundaries.

## Exit criteria

The phase may exit when required cross-concept behavior is explicit; hidden coupling has been surfaced; synchronizations preserve concept independence; important automation and synergy are understood; and application-level inclusion/dependence questions are ready for separate analysis.

## Control structure

The phase begins with a mandatory `005-A` start gate, which derives project-specific composition and synchronization subphases. The final subphase is consolidation, exit review, and handoff.

## Implementation state

- **Readiness:** not ready
- **Execution:** not started
- **Authorization:** not yet
