---
type: Phase Definition
title: Phase 006 — Concept Dependence, Product-Family, Subset & Scope Analysis
description: Distinguishes intrinsic concept independence from extrinsic application inclusion dependencies and identifies coherent concept subsets, product families, and scope boundaries.
tags: [phase-006, dependence, product-family, subset, scope, concept-design]
---

# Phase 006 — Concept Dependence, Product-Family, Subset & Scope Analysis

## Role in the lifecycle

Phase 006 examines which independently defined concepts must or may be included together in a particular application, product variant, or coherent subset. It separates application-level inclusion dependence from intrinsic conceptual dependence.

## Methodological intention

Determine how the concept system can be scoped without weakening concept independence, and identify required, optional, conditional, or alternative concept groupings that form coherent products or application variants.

## Primary design questions

- Which concepts are independently defined but extrinsically required together for a particular application?
- Which concepts are optional, conditional, alternative, or mutually constraining at the product level?
- What coherent subsets constitute sensible products or variants?
- Which dependencies are genuine product-scope relationships rather than hidden concept dependence?
- What scope boundaries or product-family distinctions become visible from the dependency structure?
- Are there variants whose concept sets require different synchronization or mapping considerations later?

## Prerequisites

Phase 005 must provide an explicit concept set and composition model sufficient to distinguish interaction from inclusion dependence.

## Expected durable outputs

Typically includes concept-inclusion dependency model, required/optional/conditional relationships, coherent subset/product-family definitions, application-scope boundaries, variant-specific constraints, and unresolved mapping implications for Phase 007.

## Explicit exclusions

This phase does not define code-module dependencies, package graphs, service dependencies, deployment topology, build graphs, runtime infrastructure, or implementation layering.

## Entry criteria

The concept and synchronization model is sufficiently stable to reason about application inclusion and product scope separately from concept definition.

## Exit criteria

The phase may exit when extrinsic concept dependencies are explicit; coherent subsets and product-family boundaries are understandable; hidden intrinsic dependence has not been normalized as product dependence; and resulting scopes are ready to be mapped into user-visible behavior.

## Control structure

The phase begins with a mandatory `006-A` start gate, which derives project-specific dependence, subset, and scope-analysis subphases. The final subphase is consolidation, exit review, and handoff.

## Implementation state

- **Readiness:** not ready
- **Execution:** not started
- **Authorization:** not yet
