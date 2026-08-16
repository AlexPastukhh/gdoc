# Low-Level Element Planning Workflow

Status: active reusable workflow
Scope: how to explore a design concern smaller than a whole planning unit through scoped Idea work while keeping ownership in the parent unit unless independent responsibility emerges.

## 1. Purpose

Use this workflow when the current question is materially smaller than a complete Situation, Loop, Scenario, Domain, Execution or other planning unit.

Canonical `Low-Level Element`, Idea, Variant and Version meanings are owned by [`principles/game-planning-principles-and-terminology.md`](principles/game-planning-principles-and-terminology.md). Idea generation/evaluation/integration remains in [`game-creation-workflow.md`](game-creation-workflow.md).

## 2. Working Route

```text
parent planning unit
→ identify one Low-Level Element / local design question
→ preserve parent scope and current evidence/status
→ open/use a nearby scoped Idea workspace when useful
→ generate Idea Variants
→ Local Evaluation
→ integrate promising answer back into the parent unit
→ review whether independent ownership has become useful.
```

Do not create another planning unit merely to make a local question feel formal.

## 3. High-Level Example — Situation Option

**Illustrative example only.** This is not a complete Situation or Idea record.

```text
Parent unit:
  Admission Under Uncertain Risk

Low-Level Element:
  restricted-admission option

Question:
  what restrictions make this option meaningfully different
  from quarantine and full admission?

Idea Variants:
  A. restricted work zones only;
  B. restricted contact network + work zones;
  C. time-limited admission pending evidence.

Integration:
  compare how each Variant changes the parent Situation's
  stakes / option value / consequences / later handoff.
```

Complete Situation fields remain in [`game-analysis-reference/gameplay-planning/situations.md`](game-analysis-reference/gameplay-planning/situations.md). Complete Idea workflow remains in [`game-creation-workflow.md`](game-creation-workflow.md).

## 4. Other Low-Level Element Examples

Examples only; none creates a mandatory entity type:

```text
Situation:
  one option;
  one occurrence driver;
  one information-source rule;
  one consequence relation;
  one activation/salience question.

Execution:
  interruption behavior;
  one intermediate state;
  one feedback-delay question.

Scenario:
  one handoff;
  one Beat-level information reveal;
  one pacing/attention question.

Domain:
  one operation precondition;
  one invariant;
  one resource conversion question.

Visual owner:
  one readability requirement;
  one realization question.
```

## 5. Workspace Placement

Keep the workspace near the owner whose element is being explored.

Conceptual examples:

```text
Situation/ideas/<question>/
Variant/ideas/<question>/
Version/ideas/<question>/
Scenario/ideas/<question>/
Domain/ideas/<question>/
```

These are examples, not a universal required folder tree. A simple question may remain inline in the parent file.

Place work at the highest scope where the question is genuinely shared. If the meaning differs by Variant or Version, scope it lower rather than maintaining divergent duplicated copies.

## 6. Variant And Version Scope

If the parent has alternative Variants:

```text
shared element question
→ parent-level Idea work;

only Variant A changes the meaning
→ Variant A-local Idea work.
```

If the same design has materially different Versions:

```text
shared across Versions
→ shared owner scope;

specific to Siege Version
→ Siege Version-local Idea work.
```

Do not let Variant- or Version-specific conclusions silently become shared truth.

## 7. Promotion / Extraction Check

After integration, ask:

```text
Does this element now have independent reuse?
Does it need independent review or collaboration?
Does it carry its own research/test lifecycle?
Does it change independently often enough to justify an owner?
Is it referenced by several parent units?
Would keeping it inline create duplication or ownership ambiguity?
```

If no, keep it as parent-unit detail.

If yes, extract/promote it into the narrowest real owner matching the discovered responsibility. Do not invent a generic `Low-Level Element Entity` family merely because extraction occurred.

## 8. Do Not

- Do not make every record field a separate entity/file.
- Do not treat every unresolved field as a Brainstorm Prompt that must have a folder.
- Do not detach a local Idea workspace from its parent responsibility.
- Do not promote an Idea Variant into accepted parent meaning without explicit selection/review.
- Do not copy Variant/Version-specific work upward merely for convenience.
- Do not create a new ontology level when ordinary parent detail remains sufficient.
