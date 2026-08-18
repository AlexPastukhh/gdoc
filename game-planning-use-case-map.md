# Game Planning — Use-Case Map

Status: active reusable practical navigation owner
Scope: supported game-planning capabilities and the exact repository read routes needed to understand and perform them.

## 1. Purpose And Boundary

Use this file to answer:

> What am I trying to do with this documentation, and which files should I read before doing it?

This map owns **navigation by practical capability**. It does not own complete workflow behavior, canonical terminology, detailed planning schemas or project meaning.

For each use case, read the listed paths in order. Expand into optional/deeper material only when the current work actually needs it.

```text
Use-Case Map
→ tells you where to read;

workflow
→ tells you how work proceeds;

principle / invariant / terminology owner
→ tells you what meanings and boundaries must remain true;

detailed method
→ gives fields, questions and checks;

project owner
→ contains actual current project meaning.
```

Examples in this map are only navigation examples. High-level conceptual examples belong with the relevant principle/workflow/method. Full practical examples are linked here when they actually exist.

## UC-01 — Bootstrap Into Game Planning Documentation

**Purpose:** understand the documentation through the practical work you are going to perform instead of reading the repository in arbitrary order.

**Read order:**

1. [`README.md`](README.md)
2. this Use-Case Map
3. select the use cases relevant to the current task
4. read every **Required Reading** path for those use cases
5. read linked high-level examples where useful
6. read full practical examples when they exist
7. read the current project entry point and affected project owners when the work is project-specific

**Required Reading:**

- [`README.md`](README.md)
- [`principles/README.md`](principles/README.md)

**Project-local application:**

- [`game-planning/README.md`](game-planning/README.md)
- then `game-planning/<project>/README.md`

**Bootstrap quality rule:** if a required path is important to the selected use case, superficial reading is not sufficient. Reread it before relying on a strong conclusion.

## UC-02 — Build Or Expand A Spine Scenario

**Purpose:** obtain a high-level concrete picture of one selected game run and use that chronology as the skeleton for progressively deeper planning.

**Required Reading:**

1. [`game-planning-spine-workflow.md`](game-planning-spine-workflow.md)
2. [`principles/gameplay-situations-loops-and-scenarios-principles-and-terminology.md`](principles/gameplay-situations-loops-and-scenarios-principles-and-terminology.md)
3. [`game-analysis-reference/gameplay-planning/scenarios.md`](game-analysis-reference/gameplay-planning/scenarios.md)

**Optional / deeper reading:**

- [`game-analysis-reference/gameplay-planning/README.md`](game-analysis-reference/gameplay-planning/README.md)
- [`game-analysis-reference/game-structure-analysis.md`](game-analysis-reference/game-structure-analysis.md)
- [`game-analysis-reference/player-experience-motivation-planning.md`](game-analysis-reference/player-experience-motivation-planning.md)
- [`game-analysis-reference/visual-design-analysis-and-planning.md`](game-analysis-reference/visual-design-analysis-and-planning.md)

**High-level example:** [`game-planning-spine-workflow.md`](game-planning-spine-workflow.md), `High-Level Example`.

**Full practical example:** not yet maintained as a separate frozen documentation artifact.

**Project-local application:** project README → project Scenario/Spine owner or current working owner named by that README/Goal Map.

## UC-03 — Detail A Concrete Low-Level Unit Inside A Spine

**Purpose:** describe a concrete low-level manifestation in the selected Scenario path without pretending that one occurrence exhausts the reusable design space.

**Required Reading:**

1. [`game-planning-spine-workflow.md`](game-planning-spine-workflow.md)
2. [`game-analysis-reference/gameplay-planning/scenarios.md`](game-analysis-reference/gameplay-planning/scenarios.md)
3. the detailed method matching the concrete unit, when independent detail is useful:
   - Situation → [`game-analysis-reference/gameplay-planning/situations.md`](game-analysis-reference/gameplay-planning/situations.md)
   - Event → [`game-analysis-reference/gameplay-planning/README.md`](game-analysis-reference/gameplay-planning/README.md), `Supporting Gameplay Event Record`
   - Execution → [`game-analysis-reference/gameplay-planning/executions.md`](game-analysis-reference/gameplay-planning/executions.md)
   - Loop → [`game-analysis-reference/gameplay-planning/loops.md`](game-analysis-reference/gameplay-planning/loops.md)
   - Dynamic → [`game-analysis-reference/gameplay-planning/dynamics.md`](game-analysis-reference/gameplay-planning/dynamics.md)

If no detailed method/supporting record exists yet for a material local responsibility, preserve enough concrete Scenario-local detail to understand the selected run and mark the method/owner gap. Do not invent a reusable schema merely to satisfy this use case.

**Concrete-detail rule:** when a Situation Instance, Event occurrence, Execution occurrence, Loop manifestation or other low-level unit becomes material inside the selected Scenario, describe it using the **applicable/materially useful fields of that unit's detailed method**. Those answers are scoped to this concrete Scenario/run. They do not automatically define the reusable unit's complete record or possibility-space. Do not mechanically fill irrelevant fields.

**Boundary:** a concrete unit/occurrence in the Spine remains part of that chronology even if a reusable owner is later extracted/developed from it.

**Related use case:** UC-04 when the unit needs reusable cross-Scenario ownership; UC-06 when the unresolved question concerns something smaller than the whole unit.

## UC-04 — Extract Or Develop A Reusable Planning Unit

**Purpose:** develop an independently useful planning unit as a broader possibility-space reusable across different Scenarios/configurations.

**Required Reading:**

1. [`principles/game-planning-principles-and-terminology.md`](principles/game-planning-principles-and-terminology.md)
2. [`game-planning-spine-workflow.md`](game-planning-spine-workflow.md)
3. [`game-analysis-reference/gameplay-planning/README.md`](game-analysis-reference/gameplay-planning/README.md)
4. the detailed method for the relevant unit

**Optional / deeper reading:**

- [`game-creation-workflow.md`](game-creation-workflow.md) when alternatives/Variants must be generated and compared
- [`low-level-element-planning-workflow.md`](low-level-element-planning-workflow.md) when one internal element needs its own scoped exploration

**High-level example:** [`game-planning-spine-workflow.md`](game-planning-spine-workflow.md), `Concrete Occurrence → Reusable Unit`.

**Full practical example:** not yet maintained as a separate frozen documentation artifact.

## UC-05 — Capture And Develop An Idea

**Purpose:** preserve a useful thought without prematurely accepting it, then develop/evaluate alternatives when the question warrants deeper work.

**Required Reading:**

1. [`principles/game-planning-principles-and-terminology.md`](principles/game-planning-principles-and-terminology.md)
2. [`game-creation-workflow.md`](game-creation-workflow.md)
3. [`game-planning/README.md`](game-planning/README.md) for direction/project placement
4. the nearest direction/project `README.md` when the Idea belongs to Concepts, Visual, Marketing, Brainstorming or a concrete game owner

**Boundary:** Idea / Idea Variant ≠ accepted game rule. An Idea may exist before a formal Brainstorm Prompt. Put one planning question in one primary workspace; direction-level Ideas do not silently become project-local accepted meaning.

## UC-06 — Work On A Low-Level Element Through Ideas

**Purpose:** explore a design concern smaller than a whole planning unit, for example one field/relation/option/rule question inside a Situation record, without automatically creating a new reusable entity.

**Required Reading:**

1. [`principles/game-planning-principles-and-terminology.md`](principles/game-planning-principles-and-terminology.md), `Low-Level Element`
2. [`low-level-element-planning-workflow.md`](low-level-element-planning-workflow.md)
3. [`game-creation-workflow.md`](game-creation-workflow.md) for Idea generation/evaluation/integration
4. the parent planning unit's detailed method
5. [`game-planning/README.md`](game-planning/README.md) for project-local workspace placement

**High-level example:** [`low-level-element-planning-workflow.md`](low-level-element-planning-workflow.md).

**Boundary:** low-level element ≠ separate planning unit automatically. Promote/extract a separate owner only when independent reuse/review/research/testing/change responsibility makes it useful.

## UC-07 — Work With Planning Entity Variants And Their Scoped Child Work

**Purpose:** compare mutually exclusive/alternative integrated designs of the same planning responsibility while keeping Variant-specific Ideas, Versions, child units and low-level elements scoped correctly.

**Required Reading:**

1. [`principles/game-planning-principles-and-terminology.md`](principles/game-planning-principles-and-terminology.md), `Variants And Versions`
2. [`game-creation-workflow.md`](game-creation-workflow.md)
3. the parent entity/unit's detailed method
4. [`game-planning/README.md`](game-planning/README.md) for project-local ownership/placement

**Boundary:** Variant = alternative design. A Variant-specific child does not silently become shared meaning of other Variants.

## UC-08 — Work With Planning Entity Versions And Their Scoped Child Work

**Purpose:** preserve materially different reusable contextual/configurational forms of the same entity/design, including Version-specific Ideas, child units and low-level elements when useful.

**Required Reading:**

1. [`principles/game-planning-principles-and-terminology.md`](principles/game-planning-principles-and-terminology.md), `Variants And Versions`
2. the entity/unit's relevant detailed method
3. [`game-planning/README.md`](game-planning/README.md) for project-local ownership/placement
4. [`game-creation-workflow.md`](game-creation-workflow.md) when the Version has unresolved local Ideas/Variants

**Boundary:** Version ≠ alternative design and ≠ document revision. Not every entity needs Versions.


## UC-09 — Create, Analyze Or Validate A Game Concept

**Purpose:** create or inspect one possible whole game, test whether its gameplay/experience/visual/market/production promises compose, and revise the Concept using evidence from representative detailed planning.

**Required Reading:**

1. [`game-creation-workflow.md`](game-creation-workflow.md)
2. [`game-analysis-reference/game-concept-analysis-and-planning.md`](game-analysis-reference/game-concept-analysis-and-planning.md)
3. [`game-planning/concepts/README.md`](game-planning/concepts/README.md)
4. the current Concept record and concrete project README when project-specific

**Optional / deeper reading:**

- [`game-analysis-reference/game-structure-analysis.md`](game-analysis-reference/game-structure-analysis.md)
- [`game-analysis-reference/player-experience-and-anti-experience.md`](game-analysis-reference/player-experience-and-anti-experience.md)
- [`game-analysis-reference/player-experience-motivation-planning.md`](game-analysis-reference/player-experience-motivation-planning.md)
- [`game-analysis-reference/visual-design-analysis-and-planning.md`](game-analysis-reference/visual-design-analysis-and-planning.md)
- [`principles/audience-is-part-of-the-game-principles-and-terminology.md`](principles/audience-is-part-of-the-game-principles-and-terminology.md)
- [`principles/market-and-platforms-principles-and-terminology.md`](principles/market-and-platforms-principles-and-terminology.md)
- [`game-planning-spine-workflow.md`](game-planning-spine-workflow.md) + UC-02/UC-03 when representative concrete chronology is the next proof step

**Project-local application:** `game-planning/concepts/<concept-record>` owns the compact whole-game Concept; the concrete game workspace owns detailed Scenarios, Experience, Visual, Marketing and other game-specific work.

**Boundary:** Concept analysis is not a requirement to fill every lens before any gameplay work. A Concept may be revised while detailed planning proceeds. A representative Spine can provide strong validation evidence only when its material local units are detailed enough to expose the actual game rather than remaining headings.

## 2. Current Project Entry

After selecting a use case, enter a concrete project through:

- [`game-planning/README.md`](game-planning/README.md)
- then the project README

For Survivor Base:

- whole-game Concept: [`game-planning/concepts/survivor-base.md`](game-planning/concepts/survivor-base.md)
- concrete game workspace: [`game-planning/survivor-base/README.md`](game-planning/survivor-base/README.md)

The Survivor Base legacy Draft is still consulted as a migration/source artifact while the Spine, reusable units and low-level elements are being developed. This is project migration behavior, not a requirement that every future project maintain a monolithic Draft.

## 3. Do Not

- Do not copy workflow bodies into this map.
- Do not define canonical terms here when a principle owner exists.
- Do not copy full method schemas here.
- Do not imply every use case is mandatory in every planning session.
- Do not list a full practical example path until that frozen example actually exists.
- Do not treat listed order as one universal project lifecycle; the map is capability navigation.
