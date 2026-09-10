---
type: Knowledge Index
title: Canonical Design Knowledge
description: Entry point for durable current design truth in repositories cloned from Base.
tags: [canonical, design, knowledge]
---

# Canonical Design Knowledge

This directory contains the **current authoritative design state** for a project created from Base.

Phase records explain how conclusions were reached. Canonical documents state what the design currently means.

## Expected knowledge families

A cloned project should add only the families its design actually needs. Typical families include:

- `project/` — Phase 000 current project/product definition, context, actors/affected parties, outcomes, scope/non-goals, constraints, terminology, assumptions, and open questions;
- `purpose/` — human purposes, needs, intended improvements, success framing, and problem context refined through concept design;
- `concepts/` — concept definitions, operational principles, state, actions, invariants, and independence boundaries;
- `synchronizations/` — explicit cross-concept interactions and their triggering/precondition/postcondition semantics;
- `dependencies/` — concept inclusion dependencies, ordering constraints, and application-family relationships;
- `authority/` — actors, protected decisions, authority seams, and non-substitutable responsibilities;
- `experience/` — mappings from concepts into user-visible behavior and experience contracts;
- `principles/` — project-specific design principles, accepted constraints, and durable policy;
- `decisions/` — durable design decisions that do not fit more naturally in another canonical family;
- `open-questions/` — unresolved design questions that remain current and require later closure.

These are suggested knowledge categories, not mandatory Jackson concepts, required directories, or a fixed taxonomy imposed by OKF.

A project should prefer the smallest coherent canonical structure that keeps current truth discoverable. For a modest project, several intake dimensions may live together under `project/`; a complex project may split them further when progressive disclosure benefits.

## Phase 000 intake authority

Phase 000 may establish canonical knowledge before Jackson concept discovery begins. That knowledge describes the **project and its current context**, not a preselected conceptual solution.

Canonical intake knowledge should preserve distinctions among established current understanding, assumptions, open questions, and other meaningful uncertainty. Detailed evidence gathering and historical reasoning may remain in Phase 000 records and be linked where useful.

See the [Phase 000 Intake Knowledge & Evidence Contract](../phases/000/intake-knowledge-contract.md).

## Authority

When a phase conclusion becomes durable, promote the stable design meaning here rather than forcing future readers to reconstruct current truth from historical phase documents.

See [Canonical and Historical Knowledge Authority](../methodology/knowledge-authority.md).
