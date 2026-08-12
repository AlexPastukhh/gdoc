# Game-Planning Documentation — Use-Case Registry

Status: active reusable semantic capability map
Scope: what the documentation system lets a designer do, what result each use case should leave, and which owner route to use.

## 1. Purpose And Authority

This file answers:

> What am I trying to do with the game-planning documentation, and where is the method that owns that work?

It is a **semantic Use-Case Registry**, not a command router and not a second copy of the workflows.

For each use case, preserve proportionally:

```text
Trigger / Input
Purpose
Expected Result
Owner Route
Boundaries / Handoff
Known Gap, if any
```

The linked owner remains authoritative for the actual method or terminology.

## 2. Main Creation And Planning Use Cases

| Use case | Typical trigger / input | Expected result | Owner route |
|---|---|---|---|
| **Capture A Game Idea** | A mechanic, rule, world idea, Experience idea, Situation/Loop/Dynamic/Scenario idea, visual idea or other useful thought appears | Source wording and useful meaning preserved without promotion to a decision | Project-wide or owner-local Idea workspace when justified; [`Game Creation Workflow`](game-creation-workflow.md) |
| **Frame The Need / Problem** | A task, observed problem, idea or reference suggests a change | Fundamental need, no-change consequence, alternative satisfaction route and relevant evidence are visible before answer generation | [`Game Creation Workflow`](game-creation-workflow.md) |
| **Discover Material Planning Questions** | The next answer-seeking question is unclear | Relevant planning surfaces are inspected only as needed and material questions are identified | [`Game Creation Workflow`](game-creation-workflow.md) or [`Game Development Planning Workflow`](game-development-planning-workflow.md) |
| **Organize Ideas Around A Design Direction** | Several questions/ideas concern one area of the design space | Optional `Design Direction` navigation containing related Prompts/Ideas/Variants | [`Game Creation Workflow`](game-creation-workflow.md) |
| **Start From A Reference** | A known game/subsystem looks like a feasible baseline | Reference responsibility, causal value, feasibility assumptions and transformation-target candidates | [`Reference First And Controlled Transformation`](principles/reference-first-and-controlled-transformation-principles-and-terminology.md) → [`Game Creation Workflow`](game-creation-workflow.md) |
| **Decompose A Reference Or Existing Solution** | The designer needs to understand what can be kept, changed or removed | Responsibilities, parts, dependencies, value/problem-producing elements and transformation target candidates | [`Game Creation Workflow`](game-creation-workflow.md) → relevant analysis/reference owners |
| **Select A Transformation Target** | A reference/solution works overall but some responsibility should change | Explicit axes/components selected for exploration, with preserved value and constraints visible | [`Game Creation Workflow`](game-creation-workflow.md) + [`Reference First`](principles/reference-first-and-controlled-transformation-principles-and-terminology.md) |
| **Form A Brainstorm Prompt** | A design gap, question, goal, requirement or problem becomes material | A bounded answer-seeking Prompt with context/constraints; a Design Direction is optional | [`Game Creation Workflow`](game-creation-workflow.md) |
| **Generate Idea Variants** | A scoped Prompt/problem needs possible answers | Several candidate answers from independent thought, references, transformation/recombination, novel ideation or a hybrid | [`Game Creation Workflow`](game-creation-workflow.md); detailed brainstorming techniques remain a methodology gap |
| **Evaluate Variants Locally** | Several answers exist to the same scoped problem | Pros, cons, risks, questions, evidence and shortlist based on the local problem | [`Game Creation Workflow`](game-creation-workflow.md) |
| **Integrate A Variant Into A Planning Unit** | A promising local answer may change wider gameplay | A real candidate Planning Unit Variant at the relevant scale, containing the integrated design needed for review | [`Game Creation Workflow`](game-creation-workflow.md) + relevant detailed planning method |
| **Evaluate A Variant In Context** | Integrated candidate units expose wider consequences | Integrated pros/cons/risks/questions, dependencies, redundancy and new Prompts | [`Game Creation Workflow`](game-creation-workflow.md) |
| **Evaluate Variant Combinations** | Two or more Variants may reinforce/conflict | Synergy/conflict comparison and stronger combination, rejection or new Prompt | [`Game Creation Workflow`](game-creation-workflow.md) |
| **Develop A Concept** | Enough compatible ideas exist to describe one possible whole game | Compact `Concept` with promise, broad Core Loop view, key entities/dependencies/decision character, reference baseline and feasibility picture | [`Game Creation Workflow`](game-creation-workflow.md) |
| **Select The Next Planning Depth** | A Concept/current Draft is coherent but material uncertainty remains | Next useful gameplay/analysis/visual/reference/prototype/research question or scoped Idea workspace | [`Game Development Planning Workflow`](game-development-planning-workflow.md) |

## 3. Detailed Gameplay Use Cases

| Use case | Expected result | Owner route |
|---|---|---|
| **Plan A Gameplay Situation** | One meaningful local decision problem with occurrence, decision space, consequences, experience, causal rule relations and balance inputs | [`Situations`](game-analysis-reference/gameplay-planning/situations.md) |
| **Preserve / Plan A Gameplay Event** | One independently useful player-facing occurrence that does not require a meaningful decision, kept lightweight and proportional | [`Gameplay Planning`](game-analysis-reference/gameplay-planning/README.md) + Scenario/other relevant owner |
| **Plan A Gameplay Loop** | One recurrent functionally coherent causal process with recurrence, transitions, loop-sustaining rules, feedback and strategic effects | [`Loops`](game-analysis-reference/gameplay-planning/loops.md) |
| **Plan A Gameplay Dynamic** | One recurrent/persistent/directionally developing systemic tendency with causal basis, operating conditions and trajectory | [`Dynamics`](game-analysis-reference/gameplay-planning/dynamics.md) |
| **Plan A Scenario** | One concrete chronology with Situation Instances, Events/Beats, execution, observation, waiting, consequences, recovery and integration checks | [`Scenarios`](game-analysis-reference/gameplay-planning/scenarios.md) |
| **Review Game Structure** | Material structural findings at the current planning scale | [`Game Structure Analysis`](game-analysis-reference/game-structure-analysis.md) |
| **Review Player Experience / Anti-Experience** | Intended experience, supporting conditions, behavior and failure modes at the current scale | [`Player Experience And Anti-Experience`](game-analysis-reference/player-experience-and-anti-experience.md) |
| **Plan Visual Communication In Gameplay** | Required perception/experience and visual checks for concrete gameplay contexts | [`Visual Design Analysis And Planning`](game-analysis-reference/visual-design-analysis-and-planning.md) |

## 4. Project-Meaning And Content Use Cases

| Use case | Typical result | Owner route |
|---|---|---|
| **Maintain The Current Game Picture** | One readable high-level current direction with accepted/inferred/open meaning and links to justified detail owners | [`Game Planning`](principles/game-planning-principles-and-terminology.md) → [`Game Development Planning Workflow`](game-development-planning-workflow.md) → project `game-planning-draft.md` |
| **Preserve A Candidate Content Unit** | `Content Premise`: concrete playable/content unit not yet expanded into detailed chronology | Project-local content-premise owner when justified |
| **Expand A Content Premise Into A Scenario** | Concrete chronology detailed enough to review/test while unresolved generic rules remain in their owners | Project premise → [`Scenarios`](game-analysis-reference/gameplay-planning/scenarios.md) → project Scenario owner |
| **Promote Accepted Cross-Cutting Meaning** | A source-backed decision is reconciled into the project Game Planning Draft | [`Game Development Planning Workflow`](game-development-planning-workflow.md) |
| **Consolidate A Long Design Discussion** | Message/source contributions checked/routed without losing provenance or silently changing status | Supporting chat/source ledger → affected project/reusable owners |
| **Return To An Unresolved Question** | Existing scoped Idea/Prompt/Variant context reopened without treating an old provisional answer as a decision | Relevant Idea workspace + [`Game Creation Workflow`](game-creation-workflow.md) |

## 5. Validation, Evidence And Production Use Cases

| Use case | Expected result | Owner route |
|---|---|---|
| **Turn An Unknown Into Evidence Work** | Question/hypothesis, decision it can change, minimum useful test and result interpretation | [`Prototypes, Hypotheses And Tests`](principles/prototypes-hypotheses-and-tests-principles-and-terminology.md) + [`Game Development Planning Workflow`](game-development-planning-workflow.md) |
| **Check Demo / Prototype Feasibility** | Proportional view of system depth, visuals, content burden and production constraints needed to prove central value | [`Game Creation Workflow`](game-creation-workflow.md) for early direction choice; [`Game Development Planning Workflow`](game-development-planning-workflow.md) for current-project validation |
| **Compare References Or Transfer A Solution** | Clear responsibility, transferable conditions, compatibility risks and minimum evidence | [`Reference First And Controlled Transformation`](principles/reference-first-and-controlled-transformation-principles-and-terminology.md) |

## 6. Current Methodology Gaps

Supported owners already establish the high-level routes above. The following details remain intentionally unresolved and must not be silently invented inside a project:

```text
detailed brainstorming techniques, including novel idea generation, reference-guided generation, systematic transformation, forced combinations, adversarial alternative search, creative breadth/depth control and brainstorm-session capture;
exact project-local ideas/ category grammar;
complete Game Domain record/template methodology;
complete economy-planning methodology;
durable decision/rationale filesystem owner;
complete Balance owner, tables, formulas and simulation workflow;
complete Player Strategy planning schema/filesystem;
current Loop / session / activity-cycle / Strategy reconciliation;
Implementation Slice record/filesystem and subtype taxonomy;
formal Alternative-Set / configuration constraint object;
generalization of Situation contextual Version semantics to other planning scales;
Game Version / Game Variant terminology reconciliation;
final reusable wording/status of the term Integration Probe;
Use-Case Registry form/granularity redesign, if later needed.
```

The minimal accepted boundaries already documented are not gaps: scoped Ideas, Planning Unit Variants, Situation Variant/Version/Instance, named Game Domain ownership, Strategy ≠ Dynamic, broader-than-one-Situation Balance reasoning and post-design Implementation Slice responsibility.

## 7. Do Not

- Do not turn this registry into a second workflow body.
- Do not treat every entry as a required project stage.
- Do not require every project to create every possible owner file.
- Do not treat `Capture A Game Idea` as acceptance.
- Do not require a Design Direction before every Prompt or spontaneous Idea.
- Do not treat a `Content Premise` as a detailed Scenario.
- Do not treat an integrated candidate Planning Unit Variant as accepted project meaning merely because it is coherent.
- Do not silently resolve a methodology gap by inventing a mandatory process inside a project file.
