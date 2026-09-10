---
type: Process Contract
title: Phase Lifecycle Contract
description: Defines the mandatory start gate, dynamic subphase derivation, execution discipline, exit review, and handoff structure for every high-level design phase.
tags: [phase, lifecycle, process, gate, handoff]
---

# Phase Lifecycle Contract

Every high-level phase in a repository cloned from Base follows the same control structure while allowing its substantive subphases to be derived from the actual design problem.

## 1. High-level phase declaration

A high-level phase must state:

- its number and name;
- methodological purpose;
- design questions it is intended to answer;
- prerequisites and dependencies;
- expected durable design outputs;
- explicit exclusions;
- entry criteria;
- exit criteria;
- implementation status, which remains `not ready / not started / not yet` until final design closure.

The declared phase should correspond to a meaningful portion of the Jackson-aligned concept-design methodology rather than an arbitrary amount of work.

## 2. Mandatory phase start gate

The first subphase of every high-level phase is a planning and authority gate, conventionally `NNN-A`.

Its purpose is to review the high-level phase intention before substantive phase work begins.

The start gate must:

1. restate the methodological purpose of the phase;
2. review prerequisite outputs and unresolved issues handed in from earlier phases;
3. identify dependency order within the phase;
4. identify risks of conflating concepts, purposes, authority, synchronization, or implementation concerns;
5. determine the logical design workstreams actually needed;
6. divide those workstreams into dependency-safe subphases;
7. define completion evidence for each subphase;
8. define the final consolidation and exit-review work;
9. confirm that no implementation activity is being authorized.

## 3. Dynamic subphase derivation

The template must not assume that all projects need the same number of subphases.

A phase may require `A–D`, `A–J`, or another appropriate range depending on the design problem.

Subphases should be separated when doing so improves one or more of:

- dependency safety;
- conceptual independence;
- reviewability;
- authority clarity;
- evidence traceability;
- manageable scope;
- ability to revisit a decision without invalidating unrelated work.

Subphases must not be created merely to produce a visually regular sequence.

## 4. Subphase discipline

Each substantive subphase should identify:

- purpose;
- questions under examination;
- inputs;
- analysis performed;
- alternatives or ambiguities considered;
- resulting design conclusions;
- canonical knowledge affected;
- unresolved items;
- handoff to the next subphase.

Where conclusions are provisional, label them as provisional rather than prematurely promoting them to canonical truth.

## 5. Canonical promotion during a phase

Phase records document the work performed. Durable conclusions belong in canonical knowledge.

Promotion to canonical knowledge may happen during the phase when a conclusion is sufficiently established, but the phase exit review must verify that all durable conclusions have been reflected in canonical documents and that obsolete canonical statements have been superseded or corrected.

## 6. Mandatory phase consolidation and exit review

The final subphase of each high-level phase is a consolidation, exit review, and handoff.

It must evaluate at least:

- whether the phase intention was actually fulfilled;
- whether all planned subphases completed or were explicitly dispositioned;
- whether the resulting design is internally coherent;
- whether concept boundaries remain independent and understandable;
- whether cross-concept interactions are explicit where required;
- whether relevant specificity, familiarity, and integrity concerns were examined;
- whether unresolved risks are clearly carried forward;
- whether canonical knowledge reflects current truth;
- whether superseded phase conclusions remain historical rather than authoritative;
- whether any premature implementation assumptions entered the design;
- whether the next phase has adequate inputs to begin its own start gate.

## 7. Exit outcomes

A phase exit review must produce one of three outcomes:

### PASS

The phase fulfills its intent and may hand off to the next high-level phase.

### PASS WITH CARRY-FORWARD

The phase fulfills its intent, but explicitly identified non-blocking issues must be examined later. Each carry-forward item must identify its destination or trigger for reconsideration.

### NOT READY TO EXIT

Material gaps remain that prevent a sound handoff. Additional design work must be defined and completed before the phase can close.

A phase must not be marked complete merely because its originally planned documents exist.

## 8. Handoff contract

Every successful phase exit records:

- current design state;
- canonical knowledge created or materially changed;
- important design decisions;
- unresolved items and carry-forwards;
- assumptions requiring later validation;
- dependencies imposed on the next phase;
- explicit next high-level phase;
- implementation readiness state.

The next phase begins by reviewing this handoff rather than blindly accepting it.

## 9. Reopening earlier phases

Concept design is iterative. Later analysis may expose a flaw in earlier work.

Earlier conclusions may therefore be revisited without pretending the original phase never happened.

When reopening is necessary:

1. record why the earlier conclusion is being reconsidered;
2. preserve the historical record;
3. perform the required new design work;
4. update canonical knowledge;
5. record what was superseded and why;
6. reassess downstream conclusions affected by the change.

Methodological completeness is more important than preserving a linear appearance.
