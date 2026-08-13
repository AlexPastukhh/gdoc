# Player Experience First — Principles And Terminology

Status: active reusable principle-and-terminology owner
Research basis: [`../research/player-experience-research.md`](../research/player-experience-research.md)

## 1. Purpose And Authority

This file owns the working definitions, distinctions and stable principles used to reason about the experience a game should make possible.

It does not own:

- the complete mechanics-to-dynamics causal model;
- reference-analysis procedure;
- platform discovery rules;
- exact prototype execution;
- project-specific experience decisions.

## 2. Player Experience

`Player Experience` is the subjective, multilayered result of a player's interaction with a game.

It may include:

- emotional states;
- attention and cognition;
- motivation;
- bodily and sensory response;
- social response;
- interpretation and meaning;
- remembered value;
- willingness to continue, return, discuss or recommend.

Player Experience is not identical to:

```text
the game;
a mechanic;
a feature list;
designer intention;
constant pleasure;
one questionnaire score.
```

A game creates conditions from which experience may emerge. It cannot directly guarantee one identical internal state for every player.

## 3. Player Experience First

`Player Experience First` means that important design choices are evaluated against a stated valuable experience rather than against feature novelty alone.

The principle does not require completing a perfect experience specification before exploration begins. It requires making the current experience hypothesis visible enough to guide:

- reference selection;
- mechanic choice;
- trade-offs;
- prototyping;
- playtest observation;
- scope decisions.

## 4. Valuable Experience

A valuable experience need not be continuously pleasant.

A game may intentionally create:

- tension;
- fear;
- uncertainty;
- grief;
- temporary frustration;
- moral discomfort;
- pressure;
- vulnerability;

when these states participate in an experience the intended audience values.

Therefore:

```text
valuable experience
  ≠ uninterrupted positive emotion.
```

### Experience, Motivation And Goal Planning Boundary

The broad `Player Experience` definition may include a felt motivational state. Detailed planning still benefits from separating responsibilities:

```text
Project Experience planning
  → what concrete subjective Experience is being supported;
Project Motivation planning
  → what the player wants to seek / continue / preserve /
    restore / resolve / avoid / validate and may act on;
in-play Goal
  → what concrete future result/state the player is trying to achieve now.
```

Desired/anticipated Experience can be upstream of engagement and decisions as well as a downstream result. A player may seek a tense/uncertain/serious game while their in-play Motivation is to avoid the loss or danger producing that tension.

The player also needs some basis to understand/expect that an intended Experience is available. Exact `Opportunity / Legibility / Experiential Expectation / Experience Promise` planning remains in the provisional detailed method.

## 5. Experience Goal, Essential Experience And Player Promise

### Experience Goal

A design statement describing an interesting state or situation the player should experience.

It should be more specific than “fun” and less implementation-bound than a feature specification.

### Essential Experience

The smallest coherent experiential value the game must preserve to remain the intended game.

It helps distinguish load-bearing design elements from decorative or replaceable surface.

### Player Promise

The experience and activity the game claims it will deliver to the player.

The promise is partly communicated before play and must be confirmed by actual play.

`Player Promise` is a reusable game-level term. It does **not** require a standalone low-level project record. A separately justified project-local `Experience Promise` candidate is a different detailed-planning responsibility.

### Target Player Experience

The current project hypothesis about what the intended audience should experience.

### Delivered Player Experience

What players actually appear to experience, inferred from observation, report, choices, outcomes and other evidence.

```text
target experience
  ≠ delivered experience automatically.
```

## 6. Levels Of Experience

Use only the levels that clarify the current game.

| Level | Planning question |
|---|---|
| Moment-to-moment | What should an individual action or interaction feel like? |
| Decision | What should choosing, risking and accepting consequences feel like? |
| Session | What emotional and motivational arc should one run, day or session create? |
| Long-term | What should mastery, progression, attachment or return create over time? |
| Social | What should cooperation, rivalry, status, care or shared understanding create? |
| Pre-play expectation | What experience does the player imagine before purchase or download? |

Pre-play expectation is closely related to `Purchase Fantasy`, whose canonical owner is the Audience file.

## 7. Working Experience Vocabulary

No single closed taxonomy is treated as complete. The following families are a practical internal vocabulary:

| Family | Core value |
|---|---|
| Sensation | Pleasurable feel, audiovisual impact, rhythm and readable action |
| Fantasy / embodiment | Inhabiting a role, world or identity |
| Curiosity / discovery | Closing information gaps, exploring and forming hypotheses |
| Challenge / tension / relief | Stakes, uncertainty, effort and release |
| Competence / mastery | Growing skill and earned effectiveness |
| Autonomy / agency | Meaningful choice and ownership of a plan |
| Expression / creativity | Building, personalizing and demonstrating style |
| Fellowship / relatedness | Connection, cooperation, trust and shared achievement |
| Competition / status | Comparative skill, rivalry and social proof |
| Meaning / empathy / reflection | Narrative, moral, relational or personal significance |

A project may define another experience family when the current vocabulary is insufficient. It must not silently claim that the internal vocabulary is universal.

A concrete Project Experience may use **0..N families as classification/quality lenses**. Classification may remain candidate/unresolved; the project-specific formulation may precede classification, or a reusable family may be used top-down to discover a concrete project manifestation.

For project-specific Experience/Motivation planning, use [`Player Experience / Motivation Planning`](../game-analysis-reference/player-experience-motivation-planning.md). For family conditions, behavioral indicators, possible player reports and anti-experience checks, use [`Player Experience And Anti-Experience`](../game-analysis-reference/player-experience-and-anti-experience.md).

## 8. Two-Contour Model

Use two related vocabularies:

```text
design-intent vocabulary:
  what experience is intended;

verification vocabulary:
  what evidence can indicate whether it occurred.
```

MDA, Fullerton and Schell are useful for intent and causal reasoning. PENS, GEQ, PXI, IEQ, GameFlow and project-specific observation may support verification.

Do not choose a measurement instrument because it appears comprehensive. Choose it because it answers the current research question.

## 9. Experience Hypothesis Record

For an important experience, preserve proportionally:

```text
target experience;
intended audience;
experience level;
supporting mechanics/rules;
expected dynamics;
observable player behavior;
conditions;
unwanted side effects;
minimum useful test;
evidence obtained;
current confidence;
decision affected.
```

Small hypotheses may remain inline in a Game Planning Draft.

A project-specific Experience planning unit and an `Experience Hypothesis` are related but not identical: the first describes the concrete Experience being designed; the second owns a testable delivery/evidence claim. Keep them combined proportionally when simple, but do not maintain competing evidence owners.

## 10. Evidence Principles

- Designer intent is evidence of intent, not evidence of delivered experience.
- Player statements are useful but do not replace observed behavior.
- Observed behavior does not reveal internal experience perfectly.
- Combine behavior, qualitative report and suitable metrics when the decision warrants it.
- One enjoyable playtest does not prove long-term experience.
- Negative affect may be compatible with a valuable intended experience.
- Different audience segments may receive different experiences from the same system.
- Record inconclusive results instead of forcing a positive or negative conclusion.

## 11. Consequences For Game Planning

A Game Planning Draft should identify:

- the central target experience;
- supporting experience families when important;
- relevant levels of experience;
- unwanted experience risks;
- gameplay situations expected to prove the experience;
- evidence needed before expensive production.

The target experience may change after reference analysis, prototyping or audience research.

## 12. Do Not

- Do not define the game as a list of mechanics without an experience hypothesis.
- Do not use “fun” as the only experience goal.
- Do not treat one taxonomy as the complete truth.
- Do not claim that intended experience has been delivered without evidence.
- Do not optimize questionnaire scores independently of the game.
- Do not require heavy measurement for every small design question.
