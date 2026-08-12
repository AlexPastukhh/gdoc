# Game Development Planning Workflow

Status: active reusable workflow
Scope: orchestration from Concepts/current game direction through detailed planning, evidence, revision and the next useful depth of work.

## 1. Purpose And Authority

This is the main reusable entry point for **how ongoing game planning proceeds after or alongside creative synthesis**.

Start here when the question is:

> Given what I currently know about this game or Concept, what is the next useful planning, analysis or evidence step?

Use [`Game Creation Workflow`](game-creation-workflow.md) when the main problem is instead:

> How do I invent/transform several possible answers or whole-game Concepts?

Use [`Game-Planning Documentation — Use-Case Registry`](game-planning-use-case-registry.md) when the current documentation capability/route itself is unclear.

This workflow coordinates, but does not replace, principle-and-terminology owners and detailed planning/analysis references.

Stable meta-planning meanings remain in [`Game Planning`](principles/game-planning-principles-and-terminology.md). Gameplay Situation / Loop / Scenario terminology remains in [`Gameplay Situations, Loops And Scenarios`](principles/gameplay-situations-loops-and-scenarios-principles-and-terminology.md). Gameplay/System Dynamic terminology remains in [`Mechanics Create Dynamics`](principles/mechanics-create-dynamics-principles-and-terminology.md).

Specialized owners remain:

- [`Player Experience First`](principles/player-experience-first-principles-and-terminology.md)
- [`Mechanics Create Dynamics`](principles/mechanics-create-dynamics-principles-and-terminology.md)
- [`Reference First And Controlled Transformation`](principles/reference-first-and-controlled-transformation-principles-and-terminology.md)
- [`Audience Is Part Of The Game`](principles/audience-is-part-of-the-game-principles-and-terminology.md)
- [`Market And Platforms`](principles/market-and-platforms-principles-and-terminology.md)
- [`Prototypes, Hypotheses And Tests`](principles/prototypes-hypotheses-and-tests-principles-and-terminology.md)
- [`Visual Design, Assets, And AI-Assisted Art`](principles/visual-design-assets-and-ai-assisted-art-principles-and-terminology.md)

Detailed reusable planning and analysis methods remain in [`Game Analysis Reference`](game-analysis-reference/README.md).

## 2. Working Model

A project may have several open `Concepts` while comparing possible whole games.

Once one direction is the active current game, planning normally maintains one evolving, readable high-level `Game Planning Draft`.

```text
seed / references / Ideas
        ↓
Game Creation Workflow
        ↓
one or more Concepts
        ↓
select / pursue current direction
        ↓
Game Planning Draft
  current high-level picture
        ↕
justified detail owners
        ↕
analysis / prototypes / research / tests
        ↓
revised current meaning
        ↓
next useful depth.
```

Do not force every exploratory Variant into the Draft. Scoped Idea work may stay beside the owner whose unresolved question it serves.

A separate file is justified only when independent review, linking, reuse, research, testing, change tracking, parallel work or navigation makes the extra owner useful.

Planning is iterative and not append-only. Later evidence or explicit decisions can supersede earlier current meaning while preserving provenance and rationale.

## 3. Valid Starting Points

A project or planning pass may begin from:

```text
an Idea;
a Concept;
a game or other reference;
a fantasy / role;
a desired Player Experience;
a mechanic or system;
a market observation;
a technical possibility;
an interesting risk / trade-off;
a Gameplay Situation;
a Gameplay Loop;
a Gameplay Dynamic;
a Scenario / Content Premise;
a production concern;
a prototype or playtest result;
a material unknown.
```

There is no requirement to complete a broad template before detailed planning can begin.

### If the task is creative synthesis

Route to [`Game Creation Workflow`](game-creation-workflow.md) when the current problem is:

```text
generate several possible answers;
change a reference;
compare transformation axes;
assemble several possible whole games;
evaluate/integrate Variants.
```

That workflow may return one or more Concepts or a new Brainstorm Prompt.

### Common current-direction route

```text
current Concept / Game Planning Draft
→ identify the most influential uncertainty / underlying need
→ if the concrete question is unclear, inspect relevant planning surfaces
→ form the material question / scoped Idea workspace
→ choose the detailed planning / analysis / evidence scale
→ record material findings
→ reconcile accepted cross-cutting changes
→ select next uncertainty.
```

### Discover the question before choosing the answer route

If the next answer-seeking question is not yet clear, inspect only relevant planning surfaces/fields as discovery lenses:

```text
Situation / Loop / Dynamic / Scenario;
Game Structure Analysis;
Player Experience;
Visual;
Production / Feasibility;
Reference analysis;
other justified fields.
```

Preserve:

```text
Need / Problem Framing
→ WHY does this matter?

planning surfaces
→ WHAT QUESTIONS are material?

scoped Prompt / Idea workspace
→ WHAT ANSWER is being sought now?
```

Do not mechanically traverse every surface. Stop when no additional material question is found.

### Detail-first route

```text
desired experience
OR interesting risk
OR reference moment
OR mechanic
OR content need
OR concrete decision idea
        ↓
candidate planning unit
        ↓
detailed Situation / Loop / Dynamic / Scenario work
        ↓
structural + experience + visual review as useful
        ↓
mechanics / requirements / questions become clearer
        ↓
revise Concept / Draft
        ↓
integrate through Scenario / evidence when useful.
```

Routes can alternate repeatedly.

## 4. Evidence And Decision Discipline

Use the canonical distinctions from [`Game Planning`](principles/game-planning-principles-and-terminology.md):

```text
confirmed;
inference;
question;
hypothesis;
decision candidate;
decision;
evidence.
```

Preserve:

```text
suggestion ≠ decision;
risk ≠ proven failure;
implementation idea ≠ accepted architecture;
prototype candidate ≠ build decision;
generated explanation ≠ canonical documentation automatically;
Idea / Variant ≠ accepted game meaning;
integrated candidate Planning Unit Variant ≠ accepted planning unit.
```

### Directional and incomplete design input

Input such as:

```text
"I want a vibe like X";
"this should feel more procedural";
"something between A and B, but not exactly either";
```

is valid design input.

Preserve source wording, expose ambiguity and keep interpretations as inference/Variants until review or evidence justifies a narrower meaning.

## 5. Build And Revise The High-Level Game Picture

The Game Planning Draft should hold enough current high-level meaning to make the active direction reviewable.

Depending on the project, useful areas can include:

```text
Game Concept And Current State;
Audience And Purchase Fantasy / Player Promise;
Target Player Experience;
Reference Baseline And Controlled Transformation;
Broad Core Loop / Gameplay Picture;
Key Systems / State / Dynamics;
Visual Direction And Asset Strategy;
Implementation And Production Picture;
Questions / Hypotheses / Validation;
Evidence And Decisions;
Selected Planning Depth;
Current Conclusion;
Next Action.
```

These are responsibilities, not mandatory headings.

The Draft may summarize a broad Core Loop thesis, but concrete Gameplay Loops remain detailed recurrent-causal objects and should be planned separately when their causality matters.

### Promise triangle

Develop together when relevant:

```text
Audience
  ↔ Purchase Fantasy / Player Promise
  ↔ Target Player Experience
  ↔ Dominant Reference or other baseline.
```

Useful questions:

- Who already values a neighboring promise?
- What role/activity should be understood before play?
- What Experience is central?
- What game/pattern proves related value can work?
- What makes the active direction meaningfully different?
- Can a feasible representative demo actually prove the promise?

A provisional coherent answer is enough to continue; it remains a hypothesis until supported.

## 6. Route Reference Questions

Use [`Reference First And Controlled Transformation`](principles/reference-first-and-controlled-transformation-principles-and-terminology.md) for canonical reference/transformation rules.

Use [`Game Creation Workflow`](game-creation-workflow.md) when the reference is being used to:

```text
decompose a whole-game baseline;
choose what to change;
generate alternative Variants;
combine several references;
form/revise Concepts.
```

Use deeper reference analysis when:

- it is unclear **why** a reference creates the needed value;
- a reference responsibility is too broad;
- several references conflict in gameplay, audience, session structure, readability, production or Experience;
- a proposed transformation depends on conditions that may not survive the transfer;
- an expensive baseline component might need substitution or deliberate conceptual deletion.

If a supposed secondary reference changes core gameplay, audience anchor and session structure together, review whether the project is selecting a new baseline.

## 7. Detailed Gameplay Routing

Use [`Gameplay Planning — Situations, Loops, Dynamics And Scenarios`](game-analysis-reference/gameplay-planning/README.md).

Choose the scale from the current uncertainty:

| Current question | Planning scale | Detailed method |
|---|---|---|
| What meaningful local decision exists here? | Gameplay Situation | [`Situations`](game-analysis-reference/gameplay-planning/situations.md) |
| What independently useful player-facing occurrence matters here without requiring a meaningful decision? | Gameplay Event (supporting) | [`Gameplay Planning`](game-analysis-reference/gameplay-planning/README.md) + Scenario/other relevant owner |
| What recurrent functionally coherent causal process exists? | Gameplay Loop | [`Loops`](game-analysis-reference/gameplay-planning/loops.md) |
| What systemic tendency / state-opportunity trajectory develops over time? | Gameplay Dynamic | [`Dynamics`](game-analysis-reference/gameplay-planning/dynamics.md) |
| What concretely happens through time when systems, decisions and consequences interact? | Scenario | [`Scenarios`](game-analysis-reference/gameplay-planning/scenarios.md) |

These scales can be entered in any useful order and revisited.

`Core Loop`, `Session Loop` and `Long-Term Loop` remain useful broad views, but one high-level Core Loop thesis does not replace concrete Gameplay Loop analysis.

A Scenario is a selected planning/test chronology, not the only valid playthrough. It may expose a Dynamic manifestation without proving the Dynamic is stable.

## 8. Causal-Basis Routing Across Scales

When a planning unit is difficult to design or evaluate because its causal support is unclear, inspect the relevant scale-specific `Causal Basis`.

```text
Situation
  → Occurrence Model already explains
    enabling/generating causes;
  → also inspect Decision-Shaping and,
    when material, Experience-Shaping rules;

Loop
  → inspect loop-sustaining rules/state:
    transitions, recurrence, carryover,
    feedback, recovery/restart, progression;

Dynamic
  → use the existing Dynamic Causal Basis:
    rules, state, events/agents, decisions,
    consequences feeding later conditions, feedback;

Scenario
  → record only operative mechanics/rules needed
    to understand this concrete chronology;
    do not duplicate every generic rule.
```

The detailed method owners define these fields.

## 9. Route Reusable Review Passes

Use:

| Review need | Reusable owner |
|---|---|
| Structure, decisions, economy, balance, pacing, causal legibility, strategic space | [`Game Structure Analysis`](game-analysis-reference/game-structure-analysis.md) |
| Intended Experience, learning, mastery and anti-experience | [`Player Experience And Anti-Experience`](game-analysis-reference/player-experience-and-anti-experience.md) |
| Presentation / visual communication requirements in concrete gameplay contexts | [`Visual Design Analysis And Planning`](game-analysis-reference/visual-design-analysis-and-planning.md) |

Use each as a discovery surface:

```text
inspect relevant concerns
→ record material findings
→ do not invent content merely to fill the surface
→ return accepted cross-cutting change to the Draft.
```

An abstract Dynamic does not automatically require a full visual pass. Route a real visual-legibility problem through concrete Scenarios/Visual Contexts or another justified study.

## 10. Route Content And System Questions

When a mechanic, content element or system is being judged by the gameplay it creates, ask:

> Which meaningful Gameplay Situations does this create or materially change?

Also ask when useful:

```text
Which Loops does it create/change?
Which Dynamics can it strengthen/weaken?
Which Scenario chronology exposes the interaction?
Which Content Premises become possible?
What does it remove or make redundant?
```

A decisionless occurrence that is independently useful to plan/reuse may be preserved as a lightweight `Gameplay Event`; a one-off decisionless chronology detail normally remains a Scenario Beat.

Reusable mechanics/rules/state/economic meaning that serves several gameplay contexts should remain in the appropriate named Game Domain owner; a Situation or Scenario references the operative meaning rather than silently becoming a duplicate canonical owner.

A project may maintain a preliminary `Content Premise` owner when concrete content units need preservation before detailed Scenario work.

There is no mandatory separate Situation Bank. More Situations are not automatically better.

## 11. Route Balance Questions

Use the shared [`Game Structure Analysis`](game-analysis-reference/game-structure-analysis.md) balance concerns as **local review lenses**, but do not treat the scale routing below as the complete Balance methodology.

Useful scale-local questions remain:

```text
local option meaning / immediate challenge
  → Situation;

recurrence / feedback / repeated-response problem
  → Loop;

systemic incentive / strategy-viability trajectory
  → Dynamic;

cumulative timing / overlap / integration pressure
  → Scenario.
```

Broader Balance work may need to aggregate across:

```text
multiple Situations / Situation Versions;
Game Domain / economy state and flows;
Player Strategies;
Dynamics;
representative cases;
session / campaign horizons.
```

Situation occurrence/frequency, relevant state, information, options, costs, consequences and timing are balance inputs; their presence does not make one Situation the owner of whole-game balance.

The canonical Dynamic ↔ Player Behavior / Strategy relationship remains owned by [`Mechanics Create Dynamics`](principles/mechanics-create-dynamics-principles-and-terminology.md). Operationally, keep the minimal boundary:

```text
Dynamic
  → what the system tends to do / become;

Player Strategy
  → deliberate player-authored plan/policy across decisions and time.
```

The complete Balance owner/tables/formulas/simulation workflow, complete Strategy planning schema and the current Loop/session/activity-cycle/Strategy reconciliation remain open methodology work.

Do not invent numbers without evidence. Do not assume current Gameplay Loops are automatically the correct session/balance horizon.

## 12. Feasibility And Production

Game feasibility includes more than code.

Review proportionally:

```text
game systems;
engine / tools;
input / camera / UI / feedback;
save / state;
economy / balance;
content requirements;
visual language / asset strategy;
art / audio;
level/content pipeline;
localization;
analytics;
performance;
platform constraints;
production burden;
dependencies;
technical unknowns;
implementation ideas.
```

Keep separate:

```text
design requirement
  ≠ implementation idea
  ≠ accepted technical decision.
```

For early direction choice, also ask whether a representative demo can reproduce enough **system depth and visual credibility** to prove the central reference/transformation value. Route that question through the Game Creation Workflow.

## 13. Route Uncertainty Into Validation

Use [`Prototypes, Hypotheses And Tests`](principles/prototypes-hypotheses-and-tests-principles-and-terminology.md).

```text
material unknown
  → state question / hypothesis
  → identify decision it can change
  → choose earliest / cheapest useful evidence
  → observe and classify result
  → update affected owner
  → reconcile accepted cross-cutting change
  → choose next decision/depth.
```

One prototype may answer several questions and one important question may require several tests/sources.

## 14. Integration Through Candidate Planning-Unit Variants

When a promising local Idea Variant needs wider-context inspection, use the integration process in [`Game Creation Workflow`](game-creation-workflow.md).

Prefer the **real candidate planning unit at the relevant scale** rather than a separate `candidate *` artifact family:

```text
local Idea Variant
→ candidate Situation / Loop / Dynamic / Scenario / other Planning Unit Variant
→ Integrated Evaluation
→ compare / combine / revise / reject / select.
```

The phrase `integration review` may be used as lightweight activity wording when useful, but it does not create a separate ontology. A candidate unit can use the full detailed method without being accepted project meaning.

Promotion from exploration into a normal candidate owner is not acceptance. Only explicit accepted meaning enters the current Draft.

## 15. Full-Picture Views

Full-picture views are optional unless independent ownership is justified.

### Player Experience And Gameplay

Answers:

> What does the player do, decide, perceive and experience?

### Implementation And Production

Answers:

> What systems, technology, content and production capability support the planned game?

### Questions, Hypotheses And Validation

Answers:

> What is not known, how can it be learned, and what decision changes afterward?

A matrix or derived view is not a second canonical body.

### Optional Cross-View Matrix

When it materially improves review, the current Draft may use a compact cross-view matrix rather than several separate projection files:

| Game / flow point | Player Experience And Gameplay | Implementation And Production | Questions / Validation | Evidence / status / next action |
|---|---|---|---|---|

Possible flow points include:

```text
store first look;
first contact;
first meaningful decision;
routine;
repeated Loop;
developing Dynamic;
failure / recovery;
session payoff;
progression payoff;
demo proof;
content production.
```

Keep cells concise and link to independently useful detail owners rather than duplicating their full bodies. The matrix is optional and remains part of the current high-level planning picture; it does not justify a project-wide `views/` layer by itself.

## 16. Select The Next Evidence Or Depth

Choose uncertainty with greatest influence on direction, player value, cost or late-change risk.

Possible routing:

```text
need several possible whole games
  → Game Creation Workflow / Concepts;

design Prompt has no good answer
  → Generate Variants / references / future brainstorming method;

promising Variant may have wide consequences
  → candidate Planning Unit Variant / integration review;

concept baseline conflicts
  → revise audience / promise / experience / reference;

promise is unreadable
  → concept/store readability test;

central meaningful decision unclear
  → Situation planning or interaction prototype;

causal recurrent process unclear
  → Loop planning / system prototype;

systemic tendency / strategy convergence unclear
  → Dynamic planning + representative Scenarios / repeated simulation;

references conflict
  → clarify responsibilities and test the conflict point;

systems individually plausible but timing/integration unknown
  → Scenario planning;

session payoff uncertain
  → session-scale Scenario / representative session test;

session or demo integration unclear
  → representative detailed Scenario / demo chronology;

visual communication uncertain
  → Situation / Loop / Scenario visual-requirement pass;

visual direction uncertain
  → compare representative visual realizations in gameplay context;

production uncertain
  → technical/content-production spike;

market fit uncertain
  → audience/store/demo evidence.
```

Possible resulting decisions include, proportionally:

```text
revise purchase fantasy / player promise;
change target audience;
change dominant reference;
narrow or remove a secondary reference;
change or remove a mechanic/system;
reduce scope;
run another narrow prototype;
build a fuller gameplay prototype;
prepare a demo;
plan a post-design Implementation Slice;
enter production planning;
freeze/select the current Concept or direction;
reject the current Concept or direction.
```

This is example vocabulary, not a mandatory result enum.

Do not generate a large prototype roadmap when only the next evidence choice is needed.

## 17. Post-Design Implementation Slice Handoff

A post-design `Implementation Slice` is planning for **implementation of already-planned game meaning**, not another place to design the Domain.

Use it when the relevant Domain/gameplay meaning, selected/tuned values and presentation requirements are sufficiently clear to plan an independently implementable/testable end-to-end realization.

```text
Slice Goal
→ presentation / visual realization
→ player/application orchestration
→ Unity realization / adapters
→ tests
→ representative gameplay / readability proof.
```

The Slice consumes Domain contracts/rules; if implementation work exposes missing Domain semantics, route the question back to Domain planning rather than silently redefining the rule inside the Slice.

The relation is many-to-many:

```text
one Situation
→ may require several Implementation Slices;

one Implementation Slice
→ may support several Situations.
```

Do not confuse this with the early `demonstrable slice` feasibility question in the Game Creation Workflow, whose purpose is only to judge whether a direction's central value can be proven feasibly.

Exact Implementation Slice record/filesystem and proposed presentation/action/internal-logic subtype taxonomy remain open.

## 18. Observe And Update

Collect evidence appropriate to the question:

- observed behavior;
- focused qualitative report;
- suitable questionnaire items;
- telemetry;
- session outcomes / return behavior;
- store/demo behavior;
- visual comparisons in representative gameplay context;
- production or technical measurements.

Then:

1. classify the result;
2. update affected hypotheses;
3. update causal records;
4. update relevant detail owners;
5. update audience/reference/implementation interpretation where affected;
6. reconcile accepted cross-cutting changes into the Game Planning Draft;
7. state the next decision or depth.

Planning is not append-only.

## 19. Proportional Sufficiency And Production Entry

A current direction may be sufficient for a first prototype when it identifies proportionally:

```text
provisional audience;
purchase fantasy / player promise;
target Player Experience;
baseline reference or original causal thesis;
intended transformation;
broad Core Loop or another load-bearing gameplay structure;
central Situation/Loop/Dynamic question, when relevant;
key unknown;
minimum useful test;
interpretation criteria.
```

Before more expensive development, understand proportionally:

```text
session structure;
failure and recovery;
progression;
content and production burden;
visual direction / asset sourcing / integration constraints;
implementation constraints;
comparison set / platform assumptions;
evidence for central gameplay promise;
high-cost unresolved risks.
```

Production entry does not require every answer. It requires enough evidence that the next cost level is justified.

## 20. Checks Before Returning A Planning Result

Check proportionally:

- current source and current direction/Concept are clear;
- facts, hypotheses, decisions, Ideas and evidence remain distinct;
- audience, promise, Experience and references do not silently contradict;
- reference responsibilities are explicit;
- load-bearing causal claims expose conditions/trade-offs;
- expected Dynamics are distinguished from observed evidence;
- implementation ideas are not accepted automatically;
- integrated candidate Planning Unit Variants remain hypothetical until explicitly accepted;
- prototype/evidence scope matches uncertainty;
- visual direction supports readability and feasible asset strategy when relevant;
- the Game Planning Draft remains the active high-level entry point once a direction is selected;
- extra files were not created mechanically;
- current conclusion and next action/depth are explicit.

## 21. Do Not

- Do not treat the common broad-first route as mandatory.
- Do not require a complete Draft before useful detailed work.
- Do not use this workflow as a competing terminology/analysis/reference/prototype owner.
- Do not copy complete owner schemas/checklists here.
- Do not mix references without assigned responsibilities.
- Do not build a polished slice to answer a cheap fundamental question.
- Do not force every project into many files.
- Do not treat an Idea workspace, matrix, integrated candidate planning unit or derived view as a second canonical Draft.
- Do not confuse implementation verification with game validation.
- Do not invent evidence, deadlines, final mechanics, balance numbers or production certainty.
- Do not keep disproven current meaning merely because it was documented earlier.
