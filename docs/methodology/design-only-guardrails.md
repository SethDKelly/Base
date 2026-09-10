---
type: Design Guardrail
title: Design-Only Guardrails
description: Prevents implementation work from beginning before complete concept-design closure.
tags: [design, guardrail, implementation, readiness]
---

# Design-Only Guardrails

## Governing invariant

The Base lifecycle is design-only until the complete concept-design process has closed.

Before final design closure, implementation is always:

- **Readiness:** not ready
- **Execution:** not started
- **Authorization:** not yet

The purpose of the design lifecycle is to reach a state in which implementation may eventually be authorized from a coherent and reviewed design. It is not itself an implementation lifecycle.

## Prohibited work during design

The following must not be created as executable or implementation artifacts during the design lifecycle:

- application source code;
- production or prototype feature implementation;
- database schemas intended for execution;
- migrations;
- persistence implementations;
- API handlers or executable API contracts;
- authentication or authorization implementation;
- infrastructure-as-code;
- deployment configuration;
- CI/CD pipelines whose purpose is application delivery;
- executable test harnesses for application behavior;
- framework or package bootstrapping intended to begin implementation;
- runtime configuration;
- service topology implementation;
- production secrets or secret-management setup;
- implementation-enforcing repository rules that prematurely constrain unresolved design.

## Allowed implementation-facing design work

Design may identify and record:

- implementation implications;
- architectural consequences;
- required qualities or constraints;
- technical risks;
- capability needs;
- data or consistency semantics;
- security properties;
- interoperability needs;
- migration or compatibility concerns;
- unresolved technical questions for later engineering.

These remain **design knowledge or downstream considerations**. They are not permission to instantiate a solution.

## Avoiding premature architecture lock-in

Concept design may expose architectural forces, but the design process must not turn contingent implementation choices into concept semantics.

Where a design conclusion could be satisfied by multiple architectures, record the required property rather than selecting machinery prematurely.

For example:

- prefer “the action must be atomic with respect to X” over prescribing a specific transaction technology;
- prefer “historical references must remain resolvable” over selecting a storage engine;
- prefer “authorization must preserve this authority boundary” over choosing an identity provider.

## Readiness transition

Only the final design-closure phase may change implementation readiness from **not ready** to **ready**.

Even then:

- implementation remains **not started**;
- no implementation work is automatically authorized;
- a subsequent implementation-planning or engineering process must begin separately.

The final design handoff should therefore use the state:

> **Implementation ready / not started**

and never “implementation underway,” “bootstrap complete,” or equivalent wording.

## Violation handling

If implementation work is discovered during a design phase:

1. stop extending it;
2. classify whether the artifact contains useful design evidence;
3. preserve only the design-relevant conclusions in the knowledge bundle;
4. quarantine or remove executable implementation artifacts as appropriate;
5. record the correction in the relevant phase history;
6. re-evaluate whether any design conclusions were biased by the premature implementation choice.
