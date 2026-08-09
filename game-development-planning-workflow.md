# Game Development Planning Workflow

Status: active reusable workflow
Scope: orchestration from an initial game direction to an evolving Game Planning Draft, justified detailed planning, evidence, revision and the next useful depth of work.

## 1. Purpose And Authority

This is the main reusable entry point for **how game planning proceeds**.

It coordinates, but does not replace, the repository's principle-and-terminology owners and detailed planning/analysis references.

Start here when the question is:

> How should I move from what I currently know about a game to the next useful planning or evidence step?

Stable meta-planning principles remain in [`Game Planning`](principles/game-planning-principles-and-terminology.md). Gameplay Situation / Loop / Scenario terminology remains in [`Gameplay Situations, Loops And Scenarios`](principles/gameplay-situations-loops-and-scenarios-principles-and-terminology.md).

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
→ detailed Gameplay Situations / Loops / Scenarios where useful
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
mechanics / requirements / Loops / uncertainties become clearer
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

## 6. Analyze References And Controlled Transformations

Use [`Reference First And Controlled Transformation`](principles/reference-first-and-controlled-transformation-principles-and-terminology.md) and the [`Game Analysis Reference`](game-analysis-reference/README.md).

For a whole-game or large-subsystem baseline, useful structural concerns include:

```text
player promise / audience;
loops;
player verbs / decisions;
rules / resources / economy;
challenge / failure / progression;
interface / feedback / readability;
content structure / pacing;
market position / comparables.
```

For a load-bearing observation, connect visible design to a causal record:

```text
Mechanic / Rule
  → Dynamics
  → Player Behavior
  → Player Experience
  → Conditions
  → Trade-offs
  → Evidence
  → Transfer Note.
```

A reference analysis is sufficiently useful for the current decision when it can explain, proportionally:

```text
why the reference works;
which causal value is actually needed;
what is transferable;
which conditions are required;
what the reference costs / trades off;
what remains uncertain.
```

When changing a reference baseline, state:

```text
baseline;
value to preserve;
axis being changed;
useful transformation pattern, when one clarifies the change;
expected new value;
inherited conditions and trade-offs;
minimum evidence that can detect failure.
```

A secondary reference should have a named responsibility. Preserve proportionally:

```text
responsibility;
reference type;
needed value;
what it must not change;
compatibility questions;
evidence need.
```

When combining references, review at least the affected:

```text
Loops;
decisions;
economy;
session structure;
readability;
audience / promise;
production;
Player Experience.
```

If a secondary reference changes core gameplay, audience anchor and session structure together, review it as a possible new baseline rather than a harmless addition.

## 7. Detailed Gameplay Planning

Detailed gameplay planning uses three related scales.

### Gameplay Situation

`Gameplay Situation` is the main **local detailed planning unit**: a meaningful player decision with a goal/stake, materially different actions and consequential risk/opportunity.

Do not treat every event, report, state change or visual context as a Gameplay Situation.

A project can move into detailed Situation planning as soon as it is useful; the broad Draft does not have to be complete first.

Any Situation may be selected for deeper work because of frequency, player value, risk, differentiation, balance importance, production importance or validation importance. `Key Gameplay Situation` is not a separate entity type.

Full Situation methodology is in [`Gameplay Planning / Situations`](game-analysis-reference/gameplay-planning/situations.md).

### Gameplay Loop

A `Gameplay Loop` is a recurrent functionally coherent causal process involving Situations, decisions, system execution and state change.

Loops may progress asynchronously. The next Situation belonging to one Loop may occur only after execution and other gameplay, while the player handles Situations from other Loops.

Use [`Gameplay Planning / Loops`](game-analysis-reference/gameplay-planning/loops.md).

`Core Loop`, `Session Loop` and `Long-Term Loop` remain useful broad scale-oriented views when they clarify the game, but they do not replace concrete Situation-derived recurrent processes and do not imply exactly one Loop of each type.

### Scenario

A `Scenario` is a concrete chronological model of play that integrates Situation Instances, one or more Loops and the execution, observation, waiting, transition, consequence, payoff and recovery between meaningful decisions.

A Scenario is useful for planning a representative path deeply enough to implement and test without claiming that every playthrough follows the same path.

Use [`Gameplay Planning / Scenarios`](game-analysis-reference/gameplay-planning/scenarios.md).

### Relationship

```text
Gameplay Situation
  → one meaningful local decision problem;

Situations + decisions + execution + state change
  → recurring Gameplay Loops;

concrete Situation Instances + Loops + time
  → Scenario;

Scenario
  → integration review of pacing, challenge,
     concurrency, causality and cumulative experience.
```

Loops and Scenarios do not replace Situation-level planning. They add recurrent-causal and chronological/integration views over it.

## 8. Three Reusable Detailed Passes

For a Gameplay Situation, Gameplay Loop or Scenario, consult three reusable review surfaces when useful:

```text
Game Structure Analysis
Player Experience And Anti-Experience
Visual Design Analysis And Planning
```

Use them as **discovery surfaces**:

```text
inspect the full available concerns / families / lenses
→ ask whether anything material exists at the current scale
→ record the findings that matter
→ do not invent content merely to fill every item.
```

The default review rule is therefore broad rather than whitelist-based: a Situation, Loop or Scenario may be checked against the whole reusable set. Scenario planning additionally has a small group of structural concerns that should normally receive explicit review because pacing, concurrency and delayed integration are visible there more strongly than at one isolated Situation.

### Game Structure pass

Use [`Game Structure Analysis`](game-analysis-reference/game-structure-analysis.md) for structural/systemic concerns.

It can be applied at several scales:

```text
whole game;
Gameplay Situation;
Gameplay Loop;
Scenario;
concrete demo.
```

### Player Experience / Anti-Experience pass

Use [`Player Experience And Anti-Experience`](game-analysis-reference/player-experience-and-anti-experience.md).

At Situation scale, inspect experience around the decision. At Loop scale, inspect experience created by repetition and learning. At Scenario scale, inspect the cumulative experience arc, transitions, pressure, relief and anti-experience.

### Visual planning pass

Use [`Visual Design Analysis And Planning`](game-analysis-reference/visual-design-analysis-and-planning.md).

At Situation, Loop and Scenario scales, inspect `V01–V11` and any justified project-specific concerns. Record only material requirements.

`Gameplay Situation` retains its strict meaningful-decision meaning. Broader presentation contexts such as routine, execution, aftermath or store-first-look may be represented as `Visual Contexts` instead of being mislabelled as Gameplay Situations.

## 9. Situation Planning As A Content And System Lens

All detailed Situation Types in a project form the current Situation inventory; there is no separate mandatory “Situation Bank” layer.

Candidate Situations can be generated from:

```text
desired experience;
player goal / desire;
interesting risk / trade-off;
reference;
mechanic;
world/economic state;
need for gameplay content.
```

Generation is only an input. Every candidate still needs the normal meaningful-decision, occurrence, state, experience, consequence and evidence review.

A mechanic/system can also be evaluated by asking what **meaningful Situations** it creates, how varied/frequent they are and how much bespoke production is required. More Situations are not automatically better.

## 10. Balance As The Next Depth

Situation planning provides a natural bridge to balance.

Before choosing numbers, ask:

> In which relevant states do different decision options remain genuinely meaningful instead of one option becoming universally correct?

Useful questions can cover:

```text
balance variables;
decision-value relations;
frequency;
thresholds;
risk / reward;
dominant-solution risk;
later numeric test needs.
```

Loop-level balance additionally considers recurrence, cycle duration, feedback delay, intervening situations, monotony, causal readability, progression and simultaneous Loop demands.

Scenario-level review exposes temporal interaction between individually reasonable decisions and Loops.

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

## 12. Build The Validation Picture

Classify material uncertainties proportionally, for example:

```text
experience hypothesis;
causal hypothesis;
reference-transfer hypothesis;
audience / promise hypothesis;
market hypothesis;
visual-direction hypothesis;
implementation / production hypothesis.
```

For an important hypothesis, preserve:

```text
claim;
why it matters;
decision affected;
minimum useful test;
evidence to observe;
success / failure / inconclusive interpretation;
current result;
next decision.
```

Prototype the earliest uncertain link that can change the decision.

One prototype may answer several questions, and one important question may require several tests or sources. Keep the unit of evidence tied to the decision rather than forcing a one-question/one-prototype mapping.

Examples:

```text
uncertain input feel → interaction prototype;
uncertain dynamics → system toy;
uncertain player behavior → observed playtest;
uncertain experience → observation + player report;
uncertain long-term process → repeated-session test;
uncertain production → technical/content-production spike;
uncertain visual direction → representative gameplay-context comparison.
```

## 13. Full-Picture Views

Full-picture views are optional views inside the Game Planning Draft unless independent detail ownership is justified.

### Player Experience And Gameplay

This view answers:

> What does the player do, decide, perceive and experience?

It may summarize fantasy/role, target experiences, Situations/Loops, verbs/decisions, resources, challenge, feedback, failure/recovery, pacing, progression and unwanted behavior/experience while linking to deeper owners.

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

Possible flow points include store first look, first contact, first meaningful decision, routine, repeated Loop, failure/recovery, session payoff, progression payoff, demo proof and content production.

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

references conflict
  → clarify responsibilities and prototype / test the conflict point;

several systems are individually plausible but their timing is unknown
  → Scenario planning;

session payoff is uncertain
  → session prototype / Scenario;

session/demo integration is unclear
  → detailed Scenario / representative demo;

visual communication is uncertain
  → Situation/Scenario visual-requirement pass;

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
main Loop or meaningful Gameplay Situation;
causal hypothesis;
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
- implementation ideas are not accepted automatically;
- prototype/evidence scope matches the uncertainty;
- market/platform claims carry suitable evidence/freshness when they matter;
- visual direction supports readability and has a feasible asset strategy when relevant;
- the Game Planning Draft remains the high-level entry point;
- additional files were not created mechanically;
- current conclusion and next action/depth are explicit.

## 18. Do Not

- Do not treat the common broad-first route as a mandatory stage sequence.
- Do not require template-ordered input.
- Do not require a complete broad Draft before Situation-level work.
- Do not wait until the end to consider audience and market when they materially affect the direction.
- Do not turn every event into a Gameplay Situation.
- Do not treat Scenarios as the only structure of a game.
- Do not turn a general state effect into an exhaustive Situation graph.
- Do not replace Loops and causal reasoning with a feature list.
- Do not treat one broad “core loop” diagram as a substitute for concrete recurring causal processes.
- Do not mix references without assigned responsibilities.
- Do not require one reference to solve every design responsibility.
- Do not build a polished slice to answer a cheap fundamental question.
- Do not force every project into many files.
- Do not treat a matrix as the canonical owner of complete meaning.
- Do not confuse implementation verification with game validation.
- Do not treat generated or purchased assets as visually coherent by default.
- Do not invent evidence, deadlines, final mechanics, balance numbers or production certainty.
- Do not keep disproven current meaning merely because it was documented earlier.
