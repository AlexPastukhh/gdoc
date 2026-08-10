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
| **Capture A Game Idea** | A mechanic, rule, world idea, Experience idea, Situation/Loop/Dynamic/Scenario idea, visual idea or other useful thought appears | The source wording and useful meaning are preserved without promoting it into a decision | Project-local idea owner when justified; [`Game Creation Workflow`](game-creation-workflow.md) |
| **Organize Ideas Around A Design Direction** | Several ideas concern one part of the game | A `Design Direction` with one or more Brainstorm Prompts and related Variants/Ideas | [`Game Creation Workflow`](game-creation-workflow.md) |
| **Start From A Reference** | A known game/subsystem looks like a feasible baseline | Reference responsibility, causal value, feasibility assumptions and transformation target candidates | [`Reference First And Controlled Transformation`](principles/reference-first-and-controlled-transformation-principles-and-terminology.md) → [`Game Creation Workflow`](game-creation-workflow.md) |
| **Decompose A Reference** | The designer needs to understand what parts of a reference can be kept or changed | Reference structure inspected through relevant planning scales and analysis concerns | [`Game Creation Workflow`](game-creation-workflow.md) → [`Game Analysis Reference`](game-analysis-reference/README.md) |
| **Select A Transformation Target** | The reference works overall, but some part should change | One or more explicit axes/components selected for exploration, with preserved value and constraints visible | [`Game Creation Workflow`](game-creation-workflow.md) + [`Reference First`](principles/reference-first-and-controlled-transformation-principles-and-terminology.md) |
| **Form A Brainstorm Prompt** | A design gap, question, goal, requirement or problem becomes material | A bounded `Brainstorm Prompt` inside a `Design Direction`, with context and constraints sufficient to search for answers | [`Game Creation Workflow`](game-creation-workflow.md) |
| **Generate Variants** | A Brainstorm Prompt needs possible answers | Several `Variants` from independent thought, references, transformation/recombination, novel ideation or a hybrid | [`Game Creation Workflow`](game-creation-workflow.md); detailed brainstorming methods are a current methodology gap |
| **Evaluate Variants Locally** | Several answers exist to the same Prompt | Pros, cons, risks, questions, evidence and a shortlist based on how well each Variant answers the Prompt | [`Game Creation Workflow`](game-creation-workflow.md) |
| **Run An Integration Probe** | A promising Variant may change wider gameplay | Temporary `PROBE-*` Situations/Loops/Dynamics/Scenarios/Content/Concept views showing what the game would look like if the Variant were accepted | [`Game Creation Workflow`](game-creation-workflow.md) + relevant detailed planning method |
| **Evaluate A Variant In Context** | Integration Probes expose wider consequences | Integrated pros/cons/risks/questions, dependencies, redundancy and new design Prompts | [`Game Creation Workflow`](game-creation-workflow.md) |
| **Evaluate Variant Combinations** | Two or more Variants may reinforce or conflict with one another | Synergy/conflict comparison and a stronger combination, rejection or new Prompt | [`Game Creation Workflow`](game-creation-workflow.md) |
| **Develop A Concept** | Enough compatible ideas exist to describe one possible whole game | A compact `Concept` with player promise, broad Core Loop view, key entities/dependencies/decision character, reference baseline and feasibility picture | [`Game Creation Workflow`](game-creation-workflow.md) |
| **Select The Next Planning Depth** | A Concept/current Draft is coherent but material uncertainty remains | The next useful Situation/Loop/Dynamic/Scenario/GSA/PX/visual/reference/prototype/research step | [`Game Development Planning Workflow`](game-development-planning-workflow.md) |

## 3. Detailed Gameplay Use Cases

| Use case | Expected result | Owner route |
|---|---|---|
| **Plan A Gameplay Situation** | One meaningful local decision problem with occurrence, decision space, consequences, experience, causal rule relations and balance questions | [`Situations`](game-analysis-reference/gameplay-planning/situations.md) |
| **Plan A Gameplay Loop** | One recurrent functionally coherent causal process with recurrence, transitions, loop-sustaining rules, feedback and strategic effects | [`Loops`](game-analysis-reference/gameplay-planning/loops.md) |
| **Plan A Gameplay Dynamic** | One recurrent/persistent/directionally developing systemic tendency with causal basis, operating conditions and trajectory | [`Dynamics`](game-analysis-reference/gameplay-planning/dynamics.md) |
| **Plan A Scenario** | One concrete chronology with Situation Instances, execution, observation, waiting, consequences, recovery and integration checks | [`Scenarios`](game-analysis-reference/gameplay-planning/scenarios.md) |
| **Review Game Structure** | Material structural findings at the current planning scale | [`Game Structure Analysis`](game-analysis-reference/game-structure-analysis.md) |
| **Review Player Experience / Anti-Experience** | Intended experience, supporting conditions, behavior and failure modes at the current scale | [`Player Experience And Anti-Experience`](game-analysis-reference/player-experience-and-anti-experience.md) |
| **Plan Visual Communication In Gameplay** | Required perception/experience and visual checks for concrete gameplay contexts | [`Visual Design Analysis And Planning`](game-analysis-reference/visual-design-analysis-and-planning.md) |

## 4. Project-Meaning And Content Use Cases

| Use case | Typical result | Owner route |
|---|---|---|
| **Maintain The Current Game Picture** | One readable high-level current direction with accepted/inferred/open meaning and links to justified detail owners | [`Game Planning`](principles/game-planning-principles-and-terminology.md) → [`Game Development Planning Workflow`](game-development-planning-workflow.md) → project `game-planning-draft.md` |
| **Preserve A Candidate Content Unit** | A `Content Premise`: a concrete playable/content unit not yet expanded into a detailed Scenario | Project-local content-premise owner when justified |
| **Expand A Content Premise Into A Scenario** | Concrete chronology detailed enough to review/test, while unresolved generic rules remain in their owners | Project content premise → [`Scenarios`](game-analysis-reference/gameplay-planning/scenarios.md) → project Scenario owner/view |
| **Promote Accepted Cross-Cutting Meaning** | A source-backed decision is reconciled into the project Game Planning Draft | [`Game Development Planning Workflow`](game-development-planning-workflow.md) |
| **Consolidate A Long Design Discussion** | Message/source contributions are checked, routed and reconciled without losing provenance or silently changing status | Supporting chat/source ledger → affected project/reusable owners |
| **Return To An Unresolved Question** | Existing Direction/Prompt/Variant context is reopened without treating an old provisional answer as a decision | Project idea workspace + [`Game Creation Workflow`](game-creation-workflow.md) |

## 5. Validation, Evidence And Production Use Cases

| Use case | Expected result | Owner route |
|---|---|---|
| **Turn An Unknown Into Evidence Work** | A question/hypothesis, decision it can change, minimum useful test and result interpretation | [`Prototypes, Hypotheses And Tests`](principles/prototypes-hypotheses-and-tests-principles-and-terminology.md) + [`Game Development Planning Workflow`](game-development-planning-workflow.md) |
| **Check Demo / Prototype Feasibility** | A proportional view of system depth, visuals, content burden and production constraints needed to prove the central value | [`Game Creation Workflow`](game-creation-workflow.md) for early direction choice; [`Game Development Planning Workflow`](game-development-planning-workflow.md) for current project validation |
| **Compare References Or Transfer A Solution** | Clear responsibility, transferable conditions, compatibility risks and minimum evidence | [`Reference First And Controlled Transformation`](principles/reference-first-and-controlled-transformation-principles-and-terminology.md) |

## 6. Current Methodology Gaps

The documentation now has a route for **when** answer generation is needed and what its input/output should be.

It does **not yet** own a detailed family of brainstorming methods for:

```text
novel idea generation;
reference-guided idea generation;
systematic transformation;
forced combinations;
adversarial alternative search;
creative breadth/depth control;
brainstorm-session capture.
```

Do not fill this gap by pretending the current high-level `Generate Variants` route is already a complete brainstorming method.

## 7. Do Not

- Do not turn this registry into a second workflow body.
- Do not treat every entry as a required project stage.
- Do not require every project to create every possible owner file.
- Do not treat `Capture A Game Idea` as acceptance of that idea.
- Do not treat a `Content Premise` as a detailed Scenario.
- Do not treat an `Integration Probe` as accepted project meaning.
- Do not silently resolve a methodology gap by inventing a mandatory process inside a project file.
