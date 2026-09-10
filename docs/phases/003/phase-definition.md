---
type: Phase Definition
title: Phase 003 — Concept Definition, Operational Principles & Behavioral Specification
description: Converts viable concept candidates into explicit behavioral concept specifications grounded in purpose and operational principle.
tags: [phase-003, concept-definition, operational-principle, state, actions, concept-design]
---

# Phase 003 — Concept Definition, Operational Principles & Behavioral Specification

## Role in the lifecycle

Phase 003 turns viable candidates into explicit concept specifications. A proposed concept must become understandable through its own purpose and observable behavior rather than merely through a name or feature description.

## Methodological intention

Specify each viable concept through purpose, operational principle, abstract state, actions, conditions, effects, outputs, invariants, and other relevant user-visible semantics.

## Primary design questions

- What precise purpose does each concept serve?
- What archetypal operational principle demonstrates how the concept fulfills that purpose?
- What abstract state must exist for the concept's behavior to be explained?
- What actions can relevant actors perform or observe?
- What are the meaningful preconditions, effects, outputs, and invariants?
- What lifecycle, authority, correction, or historical semantics are intrinsic to the concept?
- Can the concept be specified without smuggling in another application concept or an implementation mechanism?

## Prerequisites

Phase 002 must have produced a sufficiently broad and reasoned candidate set with purpose associations and unresolved boundary questions available for specification.

## Expected durable outputs

Typically includes concept definitions and purposes, operational principles, abstract state descriptions, action semantics, relevant preconditions/effects/outputs/invariants, intrinsic authority/lifecycle/temporal/correction/history semantics where applicable, and unresolved specification questions for Phase 004.

## Explicit exclusions

Abstract concept state is not a database schema. Concept actions are not API endpoints. Behavioral specification must not select persistence structures, classes, services, messages, frameworks, protocols, infrastructure, or executable state machines.

## Entry criteria

Candidate concepts are sufficiently mature to justify detailed behavioral examination without assuming their current boundaries are correct.

## Exit criteria

The phase may exit when retained concepts are behaviorally explicit enough to be challenged for specificity, completeness, independence, and genericity; their purposes and operational principles are clear; hidden implementation assumptions have been removed; and unresolved boundary problems are visible rather than obscured.

## Control structure

The phase begins with a mandatory `003-A` start gate, which derives the project-specific specification subphases. The final subphase is the Phase 003 consolidation, exit review, and handoff.

## Implementation state

- **Readiness:** not ready
- **Execution:** not started
- **Authorization:** not yet
