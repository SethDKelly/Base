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

- `purpose/` — human purposes, needs, intended outcomes, and problem framing;
- `concepts/` — concept definitions, operational principles, state, actions, invariants, and independence boundaries;
- `synchronizations/` — explicit cross-concept interactions and their triggering/precondition/postcondition semantics;
- `dependencies/` — concept dependencies, ordering constraints, and application-family relationships;
- `authority/` — actors, protected decisions, authority seams, and non-substitutable responsibilities;
- `experience/` — mappings from concepts into user-visible behavior and experience contracts;
- `principles/` — project-specific design principles, accepted constraints, and durable policy;
- `decisions/` — durable design decisions that do not fit more naturally in another canonical family;
- `open-questions/` — unresolved design questions that remain current and require later closure.

These are suggested knowledge categories, not mandatory Jackson concepts or a fixed taxonomy required by OKF.

## Authority

When a phase conclusion becomes durable, promote the stable design meaning here rather than forcing future readers to reconstruct current truth from historical phase documents.

See [Canonical and Historical Knowledge Authority](../methodology/knowledge-authority.md).
