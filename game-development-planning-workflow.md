# Game Development Planning Workflow

Status: active reusable workflow
Scope: orchestration from an initial game direction to an evolving Game Planning Draft, justified detailed planning, evidence, revision and the next useful depth of work.

## 1. Purpose And Authority

This is the main reusable entry point for **how game planning proceeds**.

It coordinates, but does not replace, the repository's principle-and-terminology owners and detailed planning/analysis references.

Operational summaries in this file are routing aids. When a term, schema, concern set or checklist has a linked owner, that owner remains canonical and this workflow should not maintain a second complete copy.

Start here when the question is:

> How should I move from what I currently know about a game to the next useful planning or evidence step?

Stable meta-planning principles remain in [`Game Planning`](principles/game-planning-principles-and-terminology.md). Gameplay Situation / Loop / Scenario terminology remains in [`Gameplay Situations, Loops And Scenarios`](principles/gameplay-situations-loops-and-scenarios-principles-and-terminology.md). Gameplay / System Dynamic terminology remains in [`Mechanics Create Dynamics`](principles/mechanics-create-dynamics-principles-and-terminology.md).

The specialized principle owners remain:

- [`Player Experience First`](principles/player-experience-first-principles-and-terminology.md)
- [`Mechanics Create Dynamics`](principles/mechanics-create-dynamics-principles-and-terminology.md)
- [`Reference First And Controlled Transformation`](principles/reference-first-and-controlled-transformation-principles-and-terminology.md)
- [`Audience Is Part Of The Game`](principles/audience-is-part-of-the-game-principles-and-terminology.md)
- [`Market And Platforms`](principles/market-and-platforms-principles-and-terminology.md)
- [`Prototypes, Hypotheses And Tests`](principles/prototypes-hypotheses-and-tests-principles-and-terminology.md)
- [`Visual Design, Assets, And AI-Assisted Art`](principles/visual-design-assets-and-ai-assisted-art-principles-and-terminology.md)

Detailed reusable planning and analysis methods remain in [`Game Analysis Reference`](game-analysis-reference/README.md).

## 2. Working Model

Game planning normally maintains one evolving, readable high-level `Game Planning Draft` for the current game direction.

```text
rough seed / concrete problem / evidence
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

The Draft has a logical structure, but its headings are flexible. Use the structure that makes the current project easiest to understand and review.

A separate file is justified only when independent review, linking, reuse, research, testing, change tracking, parallel work or navigation makes the extra owner useful.

Planning is iterative and not append-only. Later evidence or explicit decisions can supersede earlier current meaning while preserving provenance and rationale.

Start with the smallest useful representation. A first high-level note / Draft may contain only:

```text
idea / source / reference;
why it is interesting;
current audience guess;
current experience guess;
main unknown;
next action.
```

That note already serves as the beginning of the Game Planning Draft when it is the current high-level plan.

Possible later detail owners can include individual reference analyses, prototype plans/results, gameplay systems, economy/progression, technical architecture, content architecture, visual design brief/asset strategy, production planning, level/content pipeline or release planning. Create them only when independent ownership reduces total complexity.

## 3. Valid Starting Points

A project or planning pass may begin from:

```text
an idea;
a game or other reference;
a fantasy / role;
a desired Player Experience;
a mechanic or system;
a market observation;
a technical possibility;
an interesting risk / trade-off;
a concrete Gameplay Situation;
an observed / expected Gameplay Dynamic;
a production concern;
a prototype or playtest result;
a material unknown.
```

There is no requirement to complete a broad concept template before detailed planning can begin.

### Common broad-first route

```text
seed
→ minimal Game Planning Draft
→ audience / promise / experience / reference baseline
→ broad gameplay and feasibility picture
→ detailed Gameplay Situations / Loops / Dynamics / Scenarios where useful
→ evidence / validation
→ Draft revision.
```

This is a common route, **not a required ordering**.

### Situation-first / detail-first route

```text
desired experience
OR interesting risk
OR reference moment
OR mechanic
OR content need
OR concrete decision idea
        ↓
candidate Gameplay Situation
        ↓
detailed Situation planning
        ↓
structural + experience + visual review
        ↓
mechanics / requirements / Loops / possible Dynamics / uncertainties become clearer
        ↓
create or revise the high-level Game Planning Draft
        ↓
integrate through Scenario / evidence when useful.
```

The two routes can alternate repeatedly in the same project.

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

Preserve in particular:

```text
suggestion ≠ decision;
risk ≠ proven failure;
implementation idea ≠ accepted architecture;
prototype candidate ≠ build decision;
generated explanation ≠ canonical documentation automatically.
```

### Directional and incomplete design input

Input such as:

```text
"I want a vibe like X";
"this should feel more procedural";
"something between A and B, but not exactly either";
```

is valid design input.

Preserve the source wording, expose ambiguity and keep interpretations as inference/candidates until review or evidence justifies a narrower current meaning.

For example:

```text
Incoming:
  "I want a vibe like Duskers."

Confirmed:
  Duskers is a named directional reference.

Not yet confirmed:
  palette, interface, sparse information,
  remote procedural tension, isolation,
  control distance or another cause.
```

Use reference analysis rather than silently converting the visible surface of the reference into a requirement.

## 5. Build And Revise The High-Level Game Picture

The Game Planning Draft should hold enough current high-level meaning to make the direction reviewable.

Depending on the project, useful areas can include:

```text
Game Concept And Current State;
Audience And Purchase Fantasy / Player Promise;
Target Player Experience;
Reference Baseline And Controlled Transformation;
Broad Gameplay And System Picture;
Visual Direction And Asset Strategy;
Implementation And Production Picture;
Questions / Hypotheses / Validation;
Evidence And Decisions;
Selected Planning Depth;
Current Conclusion;
Next Action.
```

These are possible responsibilities, not mandatory headings.

### Promise triangle

Develop these meanings together when relevant:

```text
Audience
  ↔ Purchase Fantasy / Player Promise
  ↔ Target Player Experience
  ↔ Dominant Reference or other baseline.
```

Useful questions:

- Who already values a neighboring promise?
- What role and activity should be understood before play?
- What experience is central?
- What game or pattern proves a related value can work?
- What makes the current direction meaningfully different?

A provisional coherent answer is enough to continue; it remains a hypothesis until supported.

## 6. Route Reference Questions To Their Owners

Use [`Reference First And Controlled Transformation`](principles/reference-first-and-controlled-transformation-principles-and-terminology.md) for canonical reference / transformation rules and [`Game Analysis Reference`](game-analysis-reference/README.md) for reusable analysis surfaces.

This workflow owns **when to route into reference work and what planning question should return from it**. It does not duplicate the reference record, transformation record or compatibility checklist.

A useful route is:

```text
a reference materially shapes the direction
  → identify the smallest responsibility being borrowed / compared
  → analyze that responsibility through the reference owner
  → inspect structural / experience / other concerns proportionally
  → expose transfer assumptions or conflicts
  → validate the uncertain link when it can change the decision
  → reconcile accepted cross-cutting meaning back into the Draft.
```

Route into deeper reference work when, for example:

- it is unclear **why** a reference creates the needed value;
- a secondary reference has no narrow responsibility;
- several references appear to conflict in gameplay, audience, session structure, readability, production or experience;
- a proposed transformation depends on conditions that may not survive the transfer.

If a supposed secondary reference changes core gameplay, audience anchor and session structure together, review whether the project is actually selecting a new baseline.

Keep detailed causal records, transformation fields and compatibility questions in their linked owners instead of maintaining another complete copy here.

## 7. Detailed Gameplay Routing

Use [`Gameplay Planning — Situations, Loops, Dynamics And Scenarios`](game-analysis-reference/gameplay-planning/README.md) as the detailed gameplay method map. Canonical terms remain in their principle-and-terminology owners.

Choose the scale from the current uncertainty:

| Current question | Planning scale | Detailed method |
|---|---|---|
| What meaningful local decision exists here? | Gameplay Situation | [`Situations`](game-analysis-reference/gameplay-planning/situations.md) |
| What recurrent functionally coherent causal process exists? | Gameplay Loop | [`Loops`](game-analysis-reference/gameplay-planning/loops.md) |
| What systemic tendency / state-opportunity trajectory develops over time? | Gameplay Dynamic | [`Dynamics`](game-analysis-reference/gameplay-planning/dynamics.md) |
| What concretely happens through time when systems, decisions and consequences interact? | Scenario | [`Scenarios`](game-analysis-reference/gameplay-planning/scenarios.md) |

These scales can be entered in any useful order and revisited as discoveries change the model.

`Core Loop`, `Session Loop` and `Long-Term Loop` may remain useful broad scale-oriented views, but they do not replace concrete Gameplay Loop analysis when the recurrent causal process itself matters.

A Scenario is a selected planning / test chronology, not the only valid playthrough. It may expose a candidate Dynamic manifestation without proving that the Dynamic is stable.

## 8. Route Reusable Review Passes

The detailed gameplay method map owns the current scale-coverage matrix. This workflow only routes the review need:

| Review need | Reusable owner |
|---|---|
| Structure, decisions, economy, balance, pacing, causal legibility, strategic space | [`Game Structure Analysis`](game-analysis-reference/game-structure-analysis.md) |
| Intended experience, learning, mastery and anti-experience | [`Player Experience And Anti-Experience`](game-analysis-reference/player-experience-and-anti-experience.md) |
| Presentation / visual communication requirements in concrete gameplay contexts | [`Visual Design Analysis And Planning`](game-analysis-reference/visual-design-analysis-and-planning.md) |

Use each owner as a **discovery surface** at the current scale:

```text
inspect the relevant concern set
→ record material findings
→ do not invent content merely to fill the surface
→ return cross-cutting accepted meaning to the Draft when it changes the game direction.
```

Do not maintain a second copy of the full pass-coverage matrix or scale-specific checklists in this workflow.

An abstract Gameplay Dynamic does not automatically require a full visual pass. Route a real Dynamic-related visual problem through representative Scenarios / Visual Contexts or another justified visual study.

## 9. Route Content And System Questions Through Situations When Useful

When a mechanic, content element or system is being judged by the gameplay it creates, a useful routing question is:

> **Which meaningful Gameplay Situations does this create or materially change?**

Candidate Situations may originate from experience goals, risks, references, mechanics, state/economy, observed or expected Dynamics, or content needs. The detailed Situation method owns the actual decision, occurrence, consequence, experience and balance review.

There is no mandatory separate Situation Bank. More Situations are not automatically better; value depends on the quality, variety, frequency and production cost of the decisions they create.

## 10. Route Balance Questions To Game Structure Analysis

When `balance` is too vague to guide the next step, route it to the shared [`Game Structure Analysis`](game-analysis-reference/game-structure-analysis.md) balance concern.

Use the current planning scale to locate the problem:

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

The canonical balance taxonomy and detailed questions live in Game Structure Analysis and the gameplay-planning method map. Do not duplicate them here or invent numerical values without evidence.

## 11. Feasibility And Production

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

A minimum prototype or demo scope should genuinely test the central value without pretending to be the complete game.

## 12. Route Uncertainty Into Validation

Use [`Prototypes, Hypotheses And Tests`](principles/prototypes-hypotheses-and-tests-principles-and-terminology.md) for canonical hypothesis, evidence and prototype distinctions.

This workflow owns the transition from a planning uncertainty to the next useful evidence step:

```text
material unknown
  → state the question / hypothesis
  → identify the decision it can change
  → choose the earliest / cheapest useful evidence method
  → observe and classify the result
  → update the affected owner
  → reconcile accepted cross-cutting change into the Draft
  → choose the next decision or depth.
```

One prototype may answer several questions and one important question may require several tests or sources. Keep evidence tied to decisions rather than generating a large prototype roadmap by default.

Detailed prototype forms, test records, fidelity rules and evidence-result classifications remain in their owner instead of being copied into this workflow.

## 13. Full-Picture Views

Full-picture views are optional views inside the Game Planning Draft unless independent detail ownership is justified.

### Player Experience And Gameplay

This view answers:

> What does the player do, decide, perceive and experience?

It may summarize fantasy/role, target experiences, Situations/Loops/Dynamics, verbs/decisions, resources, challenge, feedback, failure/recovery, pacing, progression, strategic space and unwanted behavior/experience while linking to deeper owners.

### Implementation And Production

This view answers:

> What systems, technology, content and production capability would support the planned game?

It should expose necessary capabilities, assumptions, candidate solutions, production costs, visual/asset constraints, dependencies, high-cost unknowns and decisions not yet justified. It must not silently accept architecture.

### Questions, Hypotheses And Validation

This view answers:

> What is not known, how can it be learned, and what decision changes afterward?

Full working logs may remain in separate owners when they have an independent lifecycle.

### Cross-view matrix

A mature Draft may use compact cross-view navigation when it improves review.

| Game / flow point | Player Experience And Gameplay | Implementation And Production | Questions / Validation | Evidence / status / next action |
|---|---|---|---|---|

Possible flow points include store first look, first contact, first meaningful decision, routine, repeated Loop, developing Dynamic, failure/recovery, session payoff, progression payoff, demo proof and content production.

The matrix is a view, not a second canonical body. Keep cells concise, allow many-to-many links and link to detailed owners rather than copying their complete bodies.

## 14. Select The Next Evidence Or Depth

Choose the uncertainty with greatest influence on direction, player value, cost or late-change risk.

Possible routing:

```text
concept baseline conflicts
  → revise audience / promise / experience / reference;

promise is unreadable
  → concept / store readability test;

central meaningful decision or action is unclear
  → Situation planning or interaction prototype;

causal process is unclear
  → Loop planning / system prototype;

systemic tendency / state trajectory / strategy convergence is unclear
  → Dynamic planning + representative Scenarios / repeated simulation / prototype;

references conflict
  → clarify responsibilities and prototype / test the conflict point;

several systems are individually plausible but their timing is unknown
  → Scenario planning;

session payoff is uncertain
  → session prototype / Scenario;

session/demo integration is unclear
  → detailed Scenario / representative demo;

visual communication is uncertain
  → Situation / Loop / Scenario visual-requirement pass;

visual direction is uncertain
  → compare representative style frames in gameplay context;

production is uncertain
  → technical or content-production spike;

market fit is uncertain
  → audience/store/demo evidence.
```

Possible resulting decisions include:

```text
revise purchase fantasy / player promise;
change target audience;
change dominant reference;
narrow or remove a secondary reference;
change a mechanic/system;
reduce scope;
run another narrow prototype;
build a fuller gameplay prototype;
prepare a demo;
plan a vertical slice;
enter production planning;
freeze the current concept;
reject the concept.
```

Do not generate a large prototype roadmap when only the next evidence choice is needed.

## 15. Observe And Update

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
6. reconcile accepted cross-cutting changes back into the Game Planning Draft;
7. state the next decision or depth.

Planning is not append-only. Replace disproven current meaning while preserving evidence, rationale and material historical provenance.

## 16. Proportional Sufficiency And Production Entry

A Draft may be sufficient for a **first prototype** when it identifies proportionally:

```text
provisional audience;
purchase fantasy / player promise;
target Player Experience;
baseline reference or original causal thesis;
intended transformation;
main Loop, meaningful Gameplay Situation or other load-bearing gameplay structure;
causal / Dynamic hypothesis, when relevant;
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
evidence for the central gameplay promise;
high-cost unresolved risks.
```

Production entry does not require every answer. It requires enough evidence that:

```text
the central experience can plausibly emerge;
the intended audience can understand the promise;
reference responsibilities are coherent;
load-bearing gameplay works well enough for the next cost level;
the visual language / asset strategy can be sustained;
scope is producible;
remaining uncertainty can be resolved without repeatedly replacing the whole game.
```

## 17. Checks Before Returning A Planning Result

Before treating a planning result as reviewable, check proportionally:

- the current source and current game direction are clear;
- facts, hypotheses, decisions and evidence remain distinct;
- audience, promise, experience and references do not silently contradict;
- reference responsibilities are explicit;
- load-bearing causal claims expose conditions and trade-offs;
- expected Dynamics are distinguished from observed evidence when they matter;
- balance review distinguishes basic challenge, local decision and broader strategic concerns when relevant;
- implementation ideas are not accepted automatically;
- prototype/evidence scope matches the uncertainty;
- market/platform claims carry suitable evidence/freshness when they matter;
- visual direction supports readability and has a feasible asset strategy when relevant;
- the Game Planning Draft remains the high-level entry point;
- additional files were not created mechanically;
- current conclusion and next action/depth are explicit.

## 18. Do Not

- Do not treat the common broad-first route as a mandatory stage sequence.
- Do not require template-ordered input or a complete broad Draft before useful detailed work.
- Do not use this workflow as a competing terminology, analysis, balance, reference or prototype owner; follow the linked canonical owners.
- Do not copy complete owner schemas or checklists here merely to make the workflow self-contained.
- Do not wait until the end to consider audience, market, visual or production questions when they materially affect the direction.
- Do not mix references without assigned responsibilities.
- Do not build a polished slice to answer a cheap fundamental question.
- Do not force every project into many files or pre-create detail owners for symmetry.
- Do not treat a matrix or derived view as a second canonical body of complete project meaning.
- Do not confuse implementation verification with game validation.
- Do not invent evidence, deadlines, final mechanics, balance numbers or production certainty.
- Do not keep disproven current meaning merely because it was documented earlier.
