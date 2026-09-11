---
type: Concept-Design Closure Contract
title: Concept-Design Closure & Downstream Handoff Contract
description: Defines methodology-wide traceability, orphan detection, canonical reconciliation, unresolved-item disposition, closure evidence, readiness transition, and downstream handoff rules for Phase 011.
tags: [phase-011, closure, methodology, traceability, canonical, handoff, readiness]
sources:
  - id: jackson-distillation
    resource: https://essenceofsoftware.com/posts/distillation/
    title: The Essence of the Essence — Daniel Jackson
  - id: jackson-design-engineering
    resource: https://essenceofsoftware.com/tutorials/design-general/design-vs-engineering/
    title: Design vs. engineering — Daniel Jackson
  - id: jackson-integrity
    resource: https://essenceofsoftware.com/posts/sample-chapters/eos-11-concept-integrity.pdf
    title: Concept Integrity — Daniel Jackson
---

# Concept-Design Closure & Downstream Handoff Contract

## Purpose

Phase 011 determines whether the Base concept-design lifecycle has actually produced a complete, coherent, traceable, validated, and discoverable conceptual design.

It is stronger than an ordinary phase exit because it audits the **entire lifecycle and current knowledge graph**.

Closure is justified only when a competent reader can understand why the product should exist, what concepts fulfill its purposes, how those concepts behave and compose, which product variants are in scope, how users experience them, what limitations exist, and what evidence supports the claim that the design is fit enough to hand to a downstream process.

## Methodological posture

Base operationalizes Daniel Jackson's concept-design method into numbered phases, but those phase numbers are Base's lifecycle structure rather than Jackson's prescribed project phases.

Jackson's central principles remain closure criteria:

- **specificity** — purposes and concepts are appropriately aligned rather than orphaned, redundant, or overloaded;
- **familiarity** — familiar concepts are reused where semantically appropriate and false familiarity is avoided;
- **integrity** — concepts still fulfill their purposes when composed.[^jackson-distillation]

Phase 011 also verifies the concept structure, purpose, operational principle, state/action behavior, composition, dependence, mapping, and validation work performed earlier in the lifecycle.

[^jackson-distillation]: Daniel Jackson, "The Essence of the Essence."

## Closure is not implementation

Jackson distinguishes software design from engineering: concept design determines user-facing behavior and meaning, while engineering must later realize that design reliably in technology.[^jackson-design]

Phase 011 therefore may establish that the conceptual design is **ready to hand downstream**, but it must not begin implementation as evidence of readiness.

[^jackson-design]: Daniel Jackson, "Design vs. engineering."

## The closure chain

A project should be able to traverse a coherent chain of current knowledge:

`project context / affected need`
→ `purpose / design obligation`
→ `concept`
→ `operational principle`
→ `abstract state / actions / invariants`
→ `synchronization / application action`
→ `dependence / product subset / scope`
→ `user-visible mapping`
→ `familiarity / reuse / genericity refinement`
→ `whole-system integrity`
→ `representative and adversarial validation`
→ `accepted limitations / downstream obligations`

Not every node must have its own document. The requirement is semantic traceability through authoritative knowledge and meaningful links.

## Methodology-completeness discipline

Phase 011 should verify that every methodology obligation required by the actual project has been addressed or explicitly dispositioned.

A useful audit asks whether the current design can answer:

- What human/domain change justifies the product?
- Whose needs/interests matter?
- What distinct design purposes exist?
- What concepts fulfill those purposes?
- How does each concept fulfill its purpose?
- What does each concept remember and permit?
- Are the concept boundaries specific, complete, independent, and sufficiently generic?
- How do independent concepts compose?
- Which concept combinations form coherent products/variants?
- How are concept/application semantics made intelligible to users?
- Which familiar ideas are reused, and which novelty is intentional?
- Do concepts preserve their promises in composition?
- Has the mature design survived representative and adversarial validation?
- What limitations, uncertainties, and downstream obligations remain?

A project need not create a giant closure document containing all answers. It must make the answers discoverable from current authority.

## Orphan-detection discipline

Closure must deliberately search for elements that are present but not justified, or obligations that exist but are not fulfilled.

### Purpose-side orphans

Look for:

- affected needs with no design response where one is required;
- important purposes with no concept intended to fulfill them;
- success framing unsupported by the final design;
- accepted limitations that silently negate a required purpose.

### Concept-side orphans

Look for:

- concepts with no current purpose;
- concepts retained only because they existed earlier;
- concepts whose operational principle no longer matches their current behavior;
- concepts superseded by Phase 008 refinement but still indexed as current.

### Behavioral orphans

Look for:

- state with no behavioral role;
- purpose-critical behavior with no action;
- actions with no clear contribution to a concept's purpose;
- invariants/lifecycle/history rules that no longer match current semantics;
- authority restrictions with no current rationale or missing authority where behavior requires it.

### Composition/scope orphans

Look for:

- synchronizations with no current application behavior/purpose justification;
- application actions that expose behavior no longer intended;
- dependency edges with no contextual role rationale;
- in-scope variants with no project/purpose justification;
- variant-specific composition that does not match current synchronization authority.

### Mapping/refinement/validation orphans

Look for:

- mapping obligations with no current semantic source;
- terminology that refers to retired concepts;
- familiar/reused labels whose expected semantics are false;
- integrity findings invalidated by later correction;
- validation findings whose correction never reached canonical truth;
- accepted limitations that exist only in phase evidence.

Material orphans must be corrected, removed, or explicitly bounded before closure.

## Traceability discipline

Traceability should be **navigational and semantic**, not merely a spreadsheet full of IDs.

A closure matrix or graph can be useful, but it should point to natural canonical owners rather than reproduce their content.

Traceability should be bidirectional enough to answer both:

- Why does this concept/action/synchronization exist?
- Where is this purpose/need actually fulfilled and validated?

Do not manufacture artificial one-to-one links when the design legitimately contains contextual nuance, but closure must expose unexplained many-to-many ambiguity rather than hiding it.

## Specificity closure audit

Jackson's specificity principle highlights several closure failures, including a purpose without a concept, a concept without a purpose, redundant concepts, and overloaded concepts.[^jackson-integrity]

Phase 011 should ensure the final current design does not knowingly preserve those failures.

[^jackson-integrity]: Daniel Jackson, "Concept Integrity," summary of specificity, familiarity, and integrity principles.

If a closure audit discovers such a problem, reopen the relevant earlier phase rather than writing a final-summary exception around it.

## Familiarity closure audit

Confirm that Phase 008's final familiarity decisions are reflected in current truth:

- adopted familiar concepts have semantically compatible behavior;
- retained novelty has a current rationale where material;
- false-familiarity terminology is corrected;
- broader generalization has not erased purpose or domain semantics;
- catalog/reuse knowledge does not compete with current concept authority.

## Integrity closure audit

Confirm that no known current composition causes a retained concept to fail its purpose.

If later Phase 010 corrections changed concept behavior, composition, scope, mapping, or familiarity in ways that could affect integrity, verify the affected Phase 009 conclusions were revisited.

A known integrity violation is always blocking closure.

## Validation closure audit

Phase 010 need not prove every imaginable scenario.

Closure does require evidence that:

- representative success still works end to end;
- likely/consequential misfit families were exercised appropriately;
- material misfits were corrected or explicitly bounded;
- corrections were revalidated;
- accepted limitations are compatible with current promises;
- residual uncertainty is explicit rather than accidental.

Scenario count is not evidence of completeness.

## Accepted limitations and bounded uncertainty

Concept-design closure may coexist with limitations and uncertainty when they are honestly bounded.

An accepted limitation is closure-compatible only when:

- its context is explicit;
- it does not contradict an authoritative purpose or concept promise;
- users/affected parties are not materially misled about support where that matters;
- consequences are understood sufficiently for design closure;
- the limitation has a natural canonical owner;
- it is not simply unfinished concept-design work renamed as risk.

A bounded uncertainty is closure-compatible only when the current design remains coherent without pretending the uncertainty is resolved.

## Open-question disposition

Every material current open question must be classified before closure as one of:

- **resolved** — current canonical knowledge contains the answer;
- **accepted limitation/non-goal**;
- **bounded uncertainty compatible with closure**;
- **downstream engineering/representation question** whose conceptual obligation is already clear;
- **obsolete/superseded**;
- **concept-design blocker** requiring reopening.

A repository with a large undifferentiated `open-questions` area is not closure-ready merely because the questions are documented.

## Canonical reconciliation discipline

Phase 011 performs the lifecycle-wide application of the repository documentation-governance rules.

Closure requires:

- one natural current owner for each durable semantic rule;
- no known contradictory current authorities;
- clear supersession of retired concept identities/rules;
- historical phase records preserved as evidence rather than current truth;
- indexes reflecting the current knowledge graph;
- meaningful links among current design owners;
- current terminology propagated consistently;
- ordinary concept documents conforming to the adopted OKF structure;
- no material canonical document orphaned from progressive disclosure;
- provenance retained where materially needed;
- duplicate closure summaries consolidated rather than layered on top of canonical truth.

The repository should be usable after phase history is mentally removed: phase history adds rationale, but current design meaning must not depend on reconstructing it.

## Final design entry point

A closed project should have a clear progressive-disclosure route into the current conceptual design.

This may be provided by existing canonical indexes or, where genuinely useful, a concise dedicated final-design/handoff entry point.

Do not create a monolithic "final specification" that copies every concept, synchronization, mapping, and limitation merely for closure ceremony.

## Closure evidence versus canonical truth

Phase 011 records may include:

- completeness matrices;
- orphan registers;
- reconciliation checklists;
- conflict/supersession findings;
- closure evidence;
- downstream handoff review;
- final decision rationale.

These are closure evidence.

They do not replace the canonical design owners they reference.

## Reopening discipline during closure

Phase 011 is allowed—even expected—to reopen earlier phases when closure analysis finds a real design gap.

When that happens:

1. record the closure finding;
2. reopen the natural earlier phase/semantic owner;
3. perform the needed design work;
4. update canonical truth;
5. propagate downstream effects;
6. re-run affected later-phase audits/validation;
7. return to Phase 011 only when the closure evidence reflects the corrected design.

Do not close the lifecycle by labeling a resolvable design defect a "known issue."

## Implementation-contamination closure audit

Search current design authority for premature representation/engineering choices.

Material contamination includes current rules that unnecessarily require:

- particular source/module/service boundaries;
- database schemas/storage engines;
- API/protocol/message forms;
- runtime orchestration;
- cloud/infrastructure/deployment choices;
- frameworks/languages/vendors;
- executable test structure;
- CI/CD or repository enforcement intended for implementation;
- concrete implementation sequencing;
- identity/security mechanisms where only conceptual authority properties are required.

Preserve legitimate conceptual constraints and engineering obligations while removing contingent machinery from design authority.

## Downstream handoff discipline

The final handoff should communicate what a downstream representation/architecture/engineering process must preserve without selecting how it will do so.

Useful handoff content may include:

- canonical design entry points;
- product/variant scope;
- concept purposes and observable semantics;
- application actions/synchronizations;
- authority boundaries;
- lifecycle/history/correction obligations;
- user-visible mapping requirements;
- accepted limitations/non-goals;
- conceptual safety/privacy/interoperability/consistency properties;
- validation scenarios future work should preserve;
- unresolved engineering questions;
- provenance or domain constraints material to realization.

Avoid handoff prescriptions such as specific services, databases, APIs, deployment topologies, frameworks, or test harnesses.

## Readiness-state transition

Before successful Phase 011 closure:

- **Implementation readiness:** not ready
- **Implementation execution:** not started
- **Implementation authorization:** not yet

After a successful closure decision:

- **Implementation readiness:** ready
- **Implementation execution:** not started
- **Implementation execution authorization:** not granted by this lifecycle

Successful concept-design closure authorizes the project to begin a **separate downstream representation/architecture/engineering process**. That later process decides when and how implementation execution is authorized.

This distinction prevents "design ready" from being interpreted as "implementation underway."

## Closure outcomes

### PASS — CONCEPT DESIGN CLOSED

Use when methodology completeness, canonical reconciliation, unresolved-item disposition, validation evidence, and downstream handoff are sufficient.

The readiness state may transition to **ready / not started** under the rule above.

### PASS WITH BOUNDED CARRY-FORWARD — CONCEPT DESIGN CLOSED

Use only when all concept-design work is complete and remaining items are limited to explicit accepted limitations, bounded uncertainties compatible with closure, or downstream representation/engineering questions whose conceptual obligations are already clear.

Do **not** use this outcome for unfinished purpose, concept, behavior, composition, scope, mapping, integrity, validation, or canonical-reconciliation work.

The readiness state may transition to **ready / not started** only if the carry-forwards are genuinely non-blocking under this definition.

### NOT READY TO CLOSE

Use when any material concept-design, methodology, documentation-authority, validation, or implementation-contamination blocker remains.

Implementation stays **not ready / not started / not authorized**.

## Closure standard

The closure question is not:

> Have all phase documents been produced?

It is:

> Does the repository now contain one coherent, traceable, validated conceptual design whose current meaning can be discovered without relying on superseded history, and is that design sufficiently complete to constrain downstream work without prematurely choosing its implementation?

Only a defensible **yes** closes the Base concept-design lifecycle.