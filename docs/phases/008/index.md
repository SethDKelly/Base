---
type: Phase Definition
title: Phase 008 — Familiarity, Reuse, Genericity & Concept-Catalog Refinement
description: Challenges unnecessary conceptual novelty, improves reuse and genericity, and justifies concepts that genuinely require innovation.
tags: [phase-008, familiarity, reuse, genericity, refinement, concept-design]
---

# Phase 008 — Familiarity, Reuse, Genericity & Concept-Catalog Refinement

## Role in the lifecycle

Phase 008 performs a deliberate familiarity and reuse audit after the concept system has been specified, composed, scoped, and mapped. It revisits novelty with enough system context to distinguish genuine conceptual innovation from avoidable reinvention.

## Methodological intention

Prefer familiar, reusable, understandable concepts where they adequately serve the intended purposes; improve genericity and terminology where appropriate; and explicitly justify novel concepts that remain necessary.

## Primary design questions

- Does a familiar concept already serve the same purpose sufficiently well?
- Are any concepts application-specific versions of more general, reusable ideas?
- Can genericity be improved without weakening purpose clarity or behavioral integrity?
- Do names align with users' likely mental models and established terminology?
- Are there concept-catalog opportunities that reduce novelty without importing unsuitable semantics?
- Where novelty remains, what purpose or behavioral distinction justifies it?
- Would replacing a novel concept with a familiar one introduce a semantic mismatch or integrity problem?

## Prerequisites

Phase 007 must provide a sufficiently complete concept system and user-visible mapping to make familiarity, terminology, and reuse judgments meaningful in context.

## Expected durable outputs

Typically includes:

- familiarity and reuse findings;
- concept substitutions, reframings, or retained-novelty justifications;
- genericity refinements;
- terminology refinements;
- catalog/reuse candidates for future projects where appropriate;
- downstream integrity concerns exposed by any changes.

## Explicit exclusions

Reuse here concerns conceptual design knowledge, not code libraries, frameworks, services, packages, vendors, or implementation templates.

## Entry criteria

Concepts are sufficiently mature and mapped that familiarity can be judged against their actual purposes and semantics rather than names alone.

## Exit criteria

The phase may exit when unnecessary conceptual novelty has been challenged; retained novelty is justified; genericity and terminology have been deliberately reviewed; substitutions have been propagated to affected canonical design knowledge; and the concept set is ready for a system-wide integrity audit.

## Control structure

The phase begins with a mandatory `008-A` start gate, which derives the project-specific familiarity, reuse, genericity, and refinement subphases. The final subphase is the Phase 008 consolidation, exit review, and handoff.

## Implementation state

- **Readiness:** not ready
- **Execution:** not started
- **Authorization:** not yet
