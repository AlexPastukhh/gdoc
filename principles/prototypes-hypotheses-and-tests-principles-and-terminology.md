# Prototypes, Hypotheses And Tests — Principles And Terminology

Status: provisional active reusable principle-and-terminology owner
Research basis:

- [`../research/player-experience-research.md`](../research/player-experience-research.md)
- [`../research/anatomy-of-a-game-reference.md`](../research/anatomy-of-a-game-reference.md)
- [`../research/audience-steam-and-itchio-research.md`](../research/audience-steam-and-itchio-research.md)

Research gap: a dedicated deep dive on game prototyping, playtesting, prototype fidelity, telemetry and vertical slices has not yet been completed.

## 1. Purpose And Authority

This file owns the compact reusable distinctions needed to plan evidence-driven experiments during early game development.

It does not prescribe one universal playtest method or replace specialist technical, usability, market or production testing.

## 2. Question

A `Question` is a material unknown that may affect a decision.

A question is not automatically testable until it is made specific enough.

## 3. Assumption

An `Assumption` is a belief currently used by the plan without sufficient evidence.

It should be visible when failure would materially affect the game.

## 4. Hypothesis

A `Hypothesis` is a testable claim linking a cause, expected observation and affected decision.

Common classes:

- experience hypothesis;
- causal mechanics hypothesis;
- reference-transfer hypothesis;
- audience hypothesis;
- market hypothesis;
- implementation hypothesis;
- production hypothesis.

## 5. Risk

A `Risk` is a possible harmful outcome combined with uncertainty.

A risk is not a proven failure.

Useful dimensions:

```text
likelihood;
impact;
time to discover;
cost of late discovery;
decision affected.
```

Do not compress them into one opaque score when the dimensions matter differently.

## 6. Evidence Need

An `Evidence Need` states what must be learned before a decision can be made responsibly.

It should identify the uncertainty, not merely request “more testing.”

## 7. Prototype

A `Prototype` is a deliberately limited construction used to answer one or more important questions.

The central principle:

> Prototype the uncertainty, not a miniature version of the whole future game.

Prototype forms may include:

- paper or rules prototype;
- interaction prototype;
- system toy;
- core-loop prototype;
- conflict-point prototype for mixed references;
- session prototype;
- progression simulation;
- technical spike;
- content-production sample;
- store-page or promise test;
- demo proof;
- vertical slice.

These forms are not a mandatory sequence.

## 8. Playtest

A `Playtest` observes people interacting with a game or prototype to learn about behavior, comprehension, experience and outcomes.

The test should be designed around a question.

## 9. Experiment

An `Experiment` is a controlled or structured comparison intended to isolate an effect. Not every playtest is a formal experiment.

## 10. Verification And Validation

```text
implementation verification:
  does the build or system work as specified?;

game validation:
  does the game create the intended behavior,
  experience and value for the intended audience?;

market validation:
  does the intended audience understand and respond
  to the promise and proof?;

production validation:
  can the team produce and sustain the design
  within current constraints?
```

A verified implementation may still fail game validation.

## 11. Minimum Useful Test

For an important unknown, record:

```text
question or hypothesis;
why it matters now;
decision affected;
minimum setup;
participants or environment;
what to observe;
success interpretation;
failure interpretation;
inconclusive interpretation;
artifact/code fate;
next decision.
```

Avoid thresholds invented only to fill a template. Use qualitative interpretations where exact numeric thresholds are unjustified.

## 12. Observed Play Over Stated Opinion

Player statements are valuable, but behavior often exposes:

- misunderstanding;
- incentive conflicts;
- avoidance;
- dominant strategies;
- loss of attention;
- curiosity;
- mastery;
- hesitation;
- social coordination.

Do not treat behavior as perfect access to internal experience. Combine observation with focused questions and, where useful, metrics.

## 13. Prototype Selection By Uncertainty

| Uncertainty | Minimum likely test |
|---|---|
| Is the promise readable? | Concept, capsule, description or store-page test |
| Is the central action understandable and satisfying? | Interaction prototype |
| Do the mechanics create the expected dynamics? | System toy or core-loop prototype |
| Do two references conflict? | Prototype the exact conflict point |
| Does a session have a payoff? | Session prototype |
| Is progression motivating? | Progression simulation or repeated-session test |
| Is the design technically feasible? | Technical spike |
| Is content production feasible? | Representative content-production sample |
| Does the demo prove the store promise? | Demo and audience response test |

## 14. Fidelity

Use only the fidelity required by the question.

High visual fidelity may be necessary for:

- market promise;
- audiovisual feel;
- readability;
- production feasibility.

It may be wasteful for:

- economy;
- loop structure;
- decision quality;
- systemic dynamics.

## 15. Evidence Result

Every meaningful result should be classified:

```text
supports;
weakly supports;
contradicts;
inconclusive;
invalid test;
new question.
```

Evidence does not automatically decide the design. It updates the reasoning available to the decision.

## 16. Many-To-Many Validation

One prototype may address several questions. One question may require several prototypes or sources.

Keep links rather than copying complete evidence logs into every section.

## 17. Evidence Return

Evidence should update affected:

- target experiences;
- reference interpretations;
- mechanics and causal records;
- audience hypotheses;
- market assumptions;
- implementation ideas;
- scope;
- decisions;
- affected current project owners / representative Scenarios;
- a legacy Draft only when migration compatibility/provenance responsibility requires it.

Planning is not append-only. Correct meanings that evidence disproves.

## 18. Separate Prototype Artifacts

Keep a prototype inline in the nearest relevant current project owner when the record is small and separate prototype ownership is not useful.

Create a separate prototype plan or result only when setup, execution, evidence, reuse or review has an independent lifecycle.

## 19. Vertical Slice

A `Vertical Slice` is not automatically the first prototype.

It usually tests integrated quality, production capability and a representative end-to-end section after earlier questions are sufficiently reduced.

Do not use a polished vertical slice to discover cheaply testable fundamental loop problems.

## 20. Do Not

- Do not build the whole game to answer one question.
- Do not treat a prototype candidate as a build decision.
- Do not treat a technical success as proof of player value.
- Do not ask players to design the solution for you.
- Do not discard inconvenient observations without a reason.
- Do not call an invalid or underpowered test successful.
- Do not preserve prototype code automatically.
