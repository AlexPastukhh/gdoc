# Scenario / Spine Planning Workflow

Status: active reusable workflow
Scope: how to use one concrete Scenario as the temporal/integration spine of planning, progressively detail concrete low-level manifestations, develop reusable planning units and feed clarified meaning back into Scenarios.

## 1. Purpose And Authority

Use this workflow when chronology is the clearest way to build or inspect the current game direction.

It owns the repeated planning route:

```text
high-level selected Scenario / Spine
→ progressively detailed concrete chronology
→ concrete low-level units / occurrences / elements
→ independently useful reusable owners
→ reusable alternatives / Variants / Versions / deeper detail
→ clarified units recombined into revised or new Scenarios
→ repeat.
```

It does not replace:

- canonical Scenario/Situation/Loop/Event terminology in [`principles/gameplay-situations-loops-and-scenarios-principles-and-terminology.md`](principles/gameplay-situations-loops-and-scenarios-principles-and-terminology.md);
- general planning-unit/Idea/Variant/Version/Low-Level Element meanings in [`principles/game-planning-principles-and-terminology.md`](principles/game-planning-principles-and-terminology.md);
- complete Scenario fields in [`game-analysis-reference/gameplay-planning/scenarios.md`](game-analysis-reference/gameplay-planning/scenarios.md);
- complete Situation fields in [`game-analysis-reference/gameplay-planning/situations.md`](game-analysis-reference/gameplay-planning/situations.md);
- project-local meaning.

## 2. Spine Responsibility

A `Spine Scenario` is a normal Scenario used as the main temporal/integration surface of a planning pass.

Its primary responsibility is:

```text
one selected concrete possibility through time.
```

The Spine may show nearby alternatives when they help explain a decision, but chronology continues through one selected path.

The Spine can contain low-level detail directly. It may include concrete Situation Instances, Event occurrences, Executions, state/information changes, options, selected actions, experience/visual requirements and other operative detail needed to understand this specific run.

```text
Spine
≠ only a high-level outline;

Spine
≠ exhaustive branch tree;

Spine low-level manifestation
≠ reusable possibility-space automatically.
```

## 3. High-Level Example

**Illustrative high-level example only.** This exists to explain the Spine role, not to define complete Scenario fields or Survivor Base canon.

```text
newcomers arrive / are detected
→ intake
→ admission decision
→ distribution / integration / work
→ people become more known
→ ambiguous symptom / evidence
→ response
→ investigation
→ assessment
→ persistent procedure / policy change.
```

The actual complete Scenario/Beat field set remains in:

- [`game-analysis-reference/gameplay-planning/scenarios.md`](game-analysis-reference/gameplay-planning/scenarios.md)

A future full practical example may preserve a completed real Spine as a frozen documentation artifact. This high-level example remains useful even after such a complete example exists because it explains the concept quickly.

## 4. Progressively Detail One Selected Run

Start at the minimum chronology that makes the current game/question understandable. Add detail only where material uncertainty requires it.

```text
high-level Beat / transition
→ relevant BEFORE state
→ concrete occurrence / decision / execution INSIDE
→ AFTER state / HANDOFF
→ next chronology condition.
```

For a meaningful decision, preserve enough concrete context to know why this Player Context selects the branch used by the Spine.

Example:

```text
Admission decision in this run

BEFORE:
  newcomers are outside the protected area;
  one is useful for current work;
  infection evidence is incomplete.

INSIDE:
  options visible here include refuse / hold / restricted admit;
  this Player Context selects restricted admission.

AFTER / HANDOFF:
  the newcomer enters controlled work;
  observation/evidence production continues;
  later symptoms can reactivate the risk problem.
```

This example is intentionally incomplete. The complete Situation and Scenario records remain in their detailed methods.

## 5. Concrete Occurrence → Reusable Unit

A concrete unit inside a Spine answers:

> What is happening **here, in this selected run**?

A reusable planning owner answers:

> What is the broader possibility-space for this responsibility across different Scenarios/configurations?

Example:

```text
Spine occurrence:
  newcomer has useful skill + uncertain infection status
  → player chooses restricted admission
  → controlled work begins.

Reusable Situation:
  Admission Under Uncertain Risk

Possible entry paths:
  strangers at gate;
  rescued survivor;
  expedition return;
  prisoner after a raid;
  known resident whose status becomes uncertain.

Possible decisions:
  refuse;
  delay / hold;
  quarantine;
  restricted admission;
  full admission;
  split group, when supported.
```

**The lists above are illustrative and intentionally incomplete.** They explain the boundary, not the full record schema.

Extraction/development of the reusable Situation does **not** remove the concrete Situation Instance from the Spine. The Spine still owns the concrete occurrence and selected chronology.

## 6. Reusable Unit → New Scenario Combination

Reusable owners protect the design from treating one Scenario's accidental path as the whole game.

Scenarios protect the design from separately planned units that never compose into a meaningful temporal experience.

Therefore the relationship is cyclic:

```text
Scenario
→ discovers/grounds concrete units
→ reusable owners expand possibility-space
→ reusable units expose Variants / Versions / alternatives
→ units are recombined into another Scenario
→ that Scenario tests composition and exposes new gaps
↺
```

Example only:

```text
Scenario A:
  strangers arrive
  → restricted admission
  → symptom report
  → investigation.

Scenario B using the same reusable Situation family:
  expedition member returns
  → evidence looks reassuring
  → full admission
  → later contradictory evidence changes the risk problem.
```

The second Scenario is not automatically required; it is useful when another combination/path answers a material question.

## 7. Low-Level Elements Inside Units

Detailed Spine work may expose an unresolved concern smaller than a whole reusable unit.

Example:

```text
Situation Instance:
  Admission Under Uncertain Risk

Low-Level Element question:
  What exactly should "restricted admission" permit?
```

Do not create a new planning entity merely because this question exists. Route the element through [`low-level-element-planning-workflow.md`](low-level-element-planning-workflow.md) and the existing Idea methodology when useful.

If repeated use later proves independent reuse/review/research/testing/change responsibility, the element may justify extraction into a real owner.

## 8. Legacy Consolidated Draft During Migration

Some existing projects may still have a monolithic `Game Planning Draft` imported from an earlier workflow.

During migration:

```text
legacy Draft
→ consult existing project meaning / status / provenance
→ build or refine the Spine
→ identify concrete units and Low-Level Elements
→ develop reusable owners
→ preserve the old source while responsibility is routed.
```

The Draft is therefore useful as a **migration/source artifact** while the new structure is being built.

This does **not** mean:

```text
every new conclusion must be back-written into the Draft;

every future project needs a Draft;

the Draft remains the permanent integration center.
```

Back-writing to a legacy Draft is required only when explicit migration compatibility/provenance responsibility calls for it.

## 9. General Workflow Versus Current Project Staging

The reusable architecture is iterative:

```text
Spine ↔ reusable owners ↔ Ideas / Variants / Versions ↔ new Scenarios.
```

A concrete project may choose a staged tactic for one pass.

Example:

```text
Current Survivor Base pass:
coherent chronology first
→ preserve candidate responsibilities/handoffs
→ later expand reusable possibility-spaces
→ compare them back against the Spine.
```

This does **not** establish a universal rule that every project must fully stabilize a Scenario before any reusable owner is developed.

## 10. Stop / Continue Rule

Continue deeper only while the next detail materially improves:

- chronology/causality;
- meaningful decision understanding;
- reusable ownership;
- testing/research responsibility;
- integration across units;
- experience/presentation requirements;
- a decision that can actually change.

Do not pre-create every possible low-level owner or fill every method field mechanically.

## 11. Do Not

- Do not turn the Spine into an exhaustive branch tree.
- Do not remove concrete low-level occurrences from the Spine merely because reusable owners exist.
- Do not assume every concrete occurrence deserves a separate reusable file.
- Do not treat a missing owner as proof that a new entity type is required.
- Do not treat one Scenario manifestation as proof of a stable Dynamic.
- Do not universalize one project's current staging tactic.
- Do not use a legacy Draft as the target permanent architecture merely because it is still consulted during migration.
