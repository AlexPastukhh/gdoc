# Game Development Planning Workflow

Status: active reusable workflow
Scope: from an initial game idea or reference to an evolving, evidence-driven Game Planning Draft and a justified next depth of work.

## 1. Purpose

This workflow coordinates the six principle-and-terminology owners:

- [`Player Experience First`](principles/player-experience-first-principles-and-terminology.md)
- [`Mechanics Create Dynamics`](principles/mechanics-create-dynamics-principles-and-terminology.md)
- [`Reference First And Controlled Transformation`](principles/reference-first-and-controlled-transformation-principles-and-terminology.md)
- [`Audience Is Part Of The Game`](principles/audience-is-part-of-the-game-principles-and-terminology.md)
- [`Market And Platforms`](principles/market-and-platforms-principles-and-terminology.md)
- [`Prototypes, Hypotheses And Tests`](principles/prototypes-hypotheses-and-tests-principles-and-terminology.md)

It does not require one fixed document sequence or one file per stage.

## 2. Core Route

```text
idea / reference / fantasy / mechanic / market observation
  → initial game note
  → evolving Game Planning Draft
  → coherent audience, promise, experience and reference baseline
  → reference and causal analysis
  → gameplay, implementation and production picture
  → selected uncertainty
  → minimum evidence
  → revision
  → next-depth decision.
```

The process is iterative. A later result may revise an earlier stage.

## 3. Start Simple, Structure When Needed

Begin with the smallest useful representation.

A first note may contain only:

```text
idea;
source or reference;
why it is interesting;
current audience guess;
current experience guess;
main unknown;
next action.
```

That note is already the beginning of the Game Planning Draft when it serves as the high-level plan.

Create a separate file only when independent review, linking, research, testing, reuse, change tracking, parallel work or navigation justifies the extra coordination.

## 4. Evidence And Decision States

Keep distinct:

```text
confirmed:
  explicit project decision or checked source fact;

inference:
  reasoned interpretation awaiting review;

question:
  material unknown;

hypothesis:
  testable claim;

decision candidate:
  option under consideration;

decision:
  explicit selected choice with rationale;

evidence:
  inspectable result from research, prototype,
  playtest, telemetry or market behavior.
```

```text
suggestion
  ≠ decision;

risk
  ≠ proven failure;

implementation idea
  ≠ accepted architecture;

prototype candidate
  ≠ build decision;

generated explanation
  ≠ canonical documentation automatically.
```

## 5. Game Planning Draft

A `Game Planning Draft` is the single readable high-level owner for one game direction.

It evolves throughout planning. It is not created only after every stage is complete.

It may contain, when useful:

```text
Game Concept And Current State;
Audience And Purchase Fantasy;
Target Player Experience;
Reference Baseline And Transformation;
Player Experience And Gameplay Full Picture;
Implementation And Production Full Picture;
Questions, Hypotheses And Validation Full Picture;
Full Picture Matrix;
Evidence And Decisions;
Selected Planning Depth;
Current Conclusion;
Next Action.
```

Omit sections that do not improve current work.

## 6. Stage 0 — Capture The Seed

### Inputs

A project may begin from:

- a game the designer likes;
- a mechanic;
- a fantasy;
- a setting;
- a market observation;
- a technical possibility;
- a desired player experience;
- a combination or mutation of references.

### Actions

1. Preserve the source and current wording.
2. State what is attractive about the seed.
3. Separate known facts from interpretations.
4. Record the most important unknown.
5. State the next planning or evidence action.

### Result

An initial game note or minimal Game Planning Draft.

## 7. Stage 1 — Build The Promise Triangle

Develop these meanings together:

```text
Audience
  ↔ Purchase Fantasy / Player Promise
  ↔ Target Player Experience
  ↔ Dominant Reference or other baseline.
```

### Questions

- Who already values a neighboring promise?
- What role and activity should be understood before play?
- What experience is central?
- What game or pattern proves a related value can work?
- What makes the new direction meaningfully different?

### Gate 1 — Coherent Concept Baseline

Continue when a provisional answer exists for:

- audience;
- promise;
- target experience;
- baseline;
- intended difference.

The answers remain hypotheses until supported by evidence.

## 8. Stage 2 — Analyze The Dominant Reference

Use the [`Reference First`](principles/reference-first-and-controlled-transformation-principles-and-terminology.md) owner.

For a whole-game or large-subsystem baseline, inspect:

1. Player promise and audience.
2. Core loop and session loop.
3. Player verbs and decisions.
4. Rules, resources and economy.
5. Challenge, failure and progression.
6. Interface, feedback and readability.
7. Content structure and pacing.
8. Market position and comparables.

Use additional lenses only for specific questions.

### Causal Records

For load-bearing parts, record:

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

### Gate 2 — Transferable Design Thesis

The analysis is sufficient for the current step when it explains:

- why the reference works;
- which cause is needed;
- what is transferable;
- which conditions are required;
- what the reference costs;
- what remains uncertain.

## 9. Stage 3 — Define The Controlled Transformation

### Actions

1. Name the baseline.
2. State the value to preserve.
3. Name the axis being changed.
4. Select a useful transformation pattern when it clarifies the change.
5. State expected new value.
6. State inherited conditions and trade-offs.
7. Identify the cheapest evidence that can detect failure.

### Secondary References

Add a secondary reference only for a named responsibility.

For each secondary reference:

```text
responsibility;
reference type;
needed value;
what it must not change;
compatibility questions;
evidence need.
```

### Compatibility Review

Review:

- loop;
- decisions;
- economy;
- session;
- readability;
- audience;
- production;
- experience.

If a secondary reference changes core loop, audience anchor and session structure together, review it as a candidate new baseline.

## 10. Stage 4 — Build The Gameplay Model

The gameplay model must include enough to explain how the intended experience should emerge.

### Loops

#### Core Loop

What the player repeatedly does over seconds and minutes.

#### Session Loop

How one run, day, mission or session starts, escalates, resolves and motivates another.

#### Long-Term Loop

How mastery, progression, content, relationships or strategy change over time.

Not every game needs all three as separate diagrams. Keep the meaning inline when that is clearer.

### Player Verbs And Decisions

Record:

- recurring actions;
- important decisions;
- trade-offs;
- information available;
- consequences;
- feedback.

### Key Gameplay Situations

A `Key Gameplay Situation` is a coherent situation selected for early depth because it affects value, viability, differentiation, risk, audience promise or production.

It may describe:

```text
player role and context;
starting state;
current intention or goal;
available verbs;
important decisions;
rules and constraints;
system responses;
branches;
failure and recovery;
observable result;
target experience;
supporting reference;
open uncertainty.
```

Possible candidates include:

- first readable central interaction;
- one complete core loop;
- a session payoff;
- first meaningful failure and recovery;
- a progression payoff;
- a demo proof situation.

Do not select all candidates mechanically.

### Gate 3 — Coherent Causal Model

The current gameplay model should explain why its load-bearing mechanics are expected to create the desired behavior and experience.

## 11. Player Experience And Gameplay Full Picture

This view answers:

> What does the player do, decide, perceive and experience?

It may include:

- fantasy and role;
- target experiences;
- loops;
- verbs;
- decisions;
- resources;
- challenge;
- feedback;
- failure and recovery;
- pacing;
- progression;
- key situations;
- unwanted behavior or experience.

It is a view inside the Game Planning Draft unless independent detail is justified.

## 12. Stage 5 — Build The Feasibility Picture

Game feasibility includes more than code.

Review proportionally:

```text
game systems;
engine and tool assumptions;
input, camera, UI and feedback;
save and state;
economy and balance;
content requirements;
art and audio requirements;
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

### Gate 4 — Testable Scope

Identify a minimum scope that can genuinely test the central value without pretending to be the complete game.

## 13. Implementation And Production Full Picture

This view answers:

> What systems, technology, content and production capability would support the planned game?

It should expose:

- necessary capabilities;
- assumptions;
- candidate solutions;
- production costs;
- dependencies;
- high-cost unknowns;
- decisions not yet justified.

It should not silently accept architecture.

## 14. Stage 6 — Build The Validation Picture

Classify major uncertainties.

### Experience Hypotheses

Does the game create the intended experience, at the intended level, for the intended audience?

### Causal Hypotheses

Do the mechanics create the expected dynamics and behavior?

### Reference-Transfer Hypotheses

Does the transformed design preserve the value taken from the reference?

### Audience And Promise Hypotheses

Does the audience recognize the anchor, fantasy and differentiator?

### Market Hypotheses

Do assets, tags, page and demo communicate and prove the right promise?

### Implementation And Production Hypotheses

Can the team build and sustain the design within constraints?

For each important hypothesis:

```text
claim;
why it matters;
decision affected;
minimum useful test;
evidence to observe;
success interpretation;
failure interpretation;
inconclusive interpretation;
current result;
next decision.
```

## 15. Questions, Hypotheses And Validation Full Picture

This view answers:

> What is not known, how can it be learned, and what decision changes afterward?

One prototype may address several questions. One question may require several tests or sources.

Full working logs may remain in separate owners when they have an independent lifecycle.

## 16. Full Picture Matrix

A sufficient mature Game Planning Draft should contain a compact cross-view matrix when it improves review.

| Game / flow point | Player Experience And Gameplay | Implementation And Production | Questions / Hypotheses / Validation | Evidence / status / next action |
|---|---|---|---|---|

Possible flow points:

- store first look;
- first interaction;
- core loop;
- failure and recovery;
- session end;
- progression payoff;
- demo proof;
- content production.

Rules:

- keep cells concise;
- link to complete sections or detail owners;
- allow many-to-many links;
- do not copy full research, prototype or implementation bodies into the table;
- treat the matrix as a view, not a separate canonical artifact;
- do not require three separate full-picture files.

## 17. Stage 7 — Select The Next Evidence

Choose the uncertainty with the greatest influence on direction, cost or late-change risk.

Possible routing:

```text
concept baseline conflicts
  → revise audience, promise, experience or reference;

promise is unreadable
  → concept/store readability test;

central action is unclear
  → interaction prototype;

causal chain is uncertain
  → core-loop or system prototype;

references conflict
  → prototype the conflict point;

session payoff is uncertain
  → session prototype;

production is uncertain
  → technical or content-production spike;

market fit is uncertain
  → store-page, demo or audience test.
```

Do not generate a large prototype roadmap when only the next evidence choice is needed.

## 18. Stage 8 — Observe And Update

Collect evidence appropriate to the question:

- observed behavior;
- focused qualitative report;
- suitable questionnaire items;
- telemetry;
- session outcomes;
- return behavior;
- store and demo behavior;
- production measurements;
- technical measurements.

Then:

1. classify the result;
2. update affected hypotheses;
3. update causal records;
4. update audience or reference interpretation;
5. update implementation or production direction;
6. correct the Game Planning Draft;
7. state the next decision.

Planning is not append-only. Replace disproven current meaning while preserving evidence and rationale.

## 19. Stage 9 — Select The Next Depth

Possible results:

```text
revise purchase fantasy;
change target audience;
change dominant reference;
narrow or remove a secondary reference;
change mechanic;
reduce scope;
run another narrow prototype;
build a fuller gameplay prototype;
prepare a demo;
plan a vertical slice;
create production planning;
freeze the concept;
reject the concept.
```

## 20. Sufficiency For A First Prototype

A Game Planning Draft may be sufficient for a first prototype when it identifies:

- provisional audience;
- purchase fantasy or player promise;
- target experience;
- baseline reference or original causal thesis;
- intended transformation;
- main loop or gameplay situation;
- causal hypothesis;
- key unknown;
- minimum test;
- interpretation criteria.

## 21. Sufficiency For Deeper Development

Before more expensive development, understand proportionally:

- session loop;
- failure and recovery;
- progression;
- content and production burden;
- implementation constraints;
- comparison set and platform assumptions;
- evidence for the central gameplay promise;
- high-cost unresolved risks.

## 22. Production Entry

Production entry does not require every answer. It requires enough evidence that:

- the central experience can emerge;
- the intended audience can understand the promise;
- the reference combination is coherent;
- the core loop works;
- scope is producible;
- remaining uncertainty can be resolved without repeatedly replacing the entire game.

## 23. Optional Deep Documents

Possible later details:

- individual reference analyses;
- prototype plans and results;
- gameplay systems;
- economy and progression;
- technical architecture;
- content architecture;
- production plan;
- level/content pipeline;
- release plan.

Create them only when they reduce total complexity.

## 24. Checks Before Returning A Planning Result

- Current source and current game direction are clear.
- Facts, hypotheses, decisions and evidence remain distinct.
- Audience, promise, experience and reference do not silently contradict.
- Reference roles are explicit.
- Causal claims expose conditions and trade-offs.
- Implementation ideas are not accepted automatically.
- Prototype scope matches the uncertainty.
- Market claims have evidence labels and freshness where needed.
- The Game Planning Draft remains the high-level entry point.
- Additional files were not created mechanically.
- Current conclusion and next action are explicit.

## 25. Do Not

- Do not require template-ordered input.
- Do not wait until the end to consider audience and market.
- Do not treat scenarios as the only structure of a game.
- Do not replace loops and causal reasoning with a feature list.
- Do not mix references without assigned responsibilities.
- Do not build a polished slice to answer a cheap fundamental question.
- Do not force every project into many files.
- Do not treat a matrix as the canonical owner of complete meaning.
- Do not confuse implementation verification with game validation.
