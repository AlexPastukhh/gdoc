# Gameplay Planning — Situations, Loops And Scenarios

Status: active reusable detailed-planning method map
Scope: responsibility boundaries and routing for detailed Gameplay Situation, Loop and Scenario planning.

Canonical terms and stable distinctions are owned by [`Gameplay Situations, Loops And Scenarios — Principles And Terminology`](../../principles/gameplay-situations-loops-and-scenarios-principles-and-terminology.md).

## 1. Purpose

This area answers:

> Once I choose detailed gameplay as the current planning depth, what do I plan locally, recurrently and chronologically, and how do I apply the reusable analysis/experience/visual surfaces?

Use:

```text
Situations
  → meaningful local decision problems;

Loops
  → recurrent causal processes through decisions,
     execution, state change and later decisions;

Scenarios
  → concrete chronology integrating Situation Instances,
     Loops and non-decision gameplay time.
```

## 2. File Responsibilities

| Owner | Owns | Does not own |
|---|---|---|
| [`situations.md`](situations.md) | Detailed reusable Situation planning method, occurrence/state/decision/experience/dependency/balance fields | One project's actual Situation inventory |
| [`loops.md`](loops.md) | Detailed Loop planning, recurrence, phases, causal membership, overlap, learning and Loop-level balance | A universal fixed Loop taxonomy |
| [`scenarios.md`](scenarios.md) | Scenario Beats, concrete Situation Instances, concurrency, pacing/challenge integration and AI scenario exploration | Generic rules of every Situation Type |

Project-specific detailed records belong in project-local owners, for example `game-planning/<game>/gameplay/`.

## 3. Shared Planning Rule

`Gameplay Situation` is the main **local** detailed planning unit.

> **Loops and Scenarios do not replace Situation-level planning. They add recurrent-causal and chronological/integration views over the detailed Situation model.**

A project can start with detailed Situation planning before its high-level Game Planning Draft is mature. Important findings must still be reconciled into the high-level Draft when they change cross-cutting current meaning.

## 4. Three Reusable Passes

Situation, Loop and Scenario planning can each consult:

1. [`Game Structure Analysis`](../game-structure-analysis.md)
2. [`Player Experience And Anti-Experience`](../player-experience-and-anti-experience.md)
3. [`Visual Design Analysis And Planning`](../visual-design-analysis-and-planning.md)

Use all three as discovery surfaces:

```text
inspect the full available set
→ ask whether there is anything meaningful at this scale
→ keep only material findings.
```

This means a Situation, Loop or Scenario may be walked through all Game Structure concerns, all relevant Player Experience / Anti-Experience records, and all `V01–V11` visual lenses. Do not mechanically invent an answer for a point that has nothing material to say.

## 5. Scale Differences

### Situation

Main question:

> What meaningful decision exists here, why does the player care, what do they expect and experience, which choices are meaningful and what follows?

### Loop

Main question:

> Which recurrent functionally coherent causal process appears across repeated Situations, execution and state change, and what does repetition do to strategy, pacing, balance and experience?

### Scenario

Main question:

> What actually happens in time when concrete Situation Instances and Loops overlap, earlier decisions continue executing, pressure changes and the player experiences one concrete path?

## 6. Balance Boundary

Situation planning records the variables and state ranges that make different decisions meaningful.

Loop planning asks how recurrence, feedback delay, frequency, progression and overlap affect those decisions.

Scenario planning checks whether individually plausible decisions and Loops combine into acceptable pacing, challenge and experience in time.

Do not fix numerical balance without evidence merely because the record has a balance field.

## 7. Visual Boundary

`Gameplay Situation` keeps its strict meaningful-decision meaning.

Visual work may also need a broader `Visual Context` such as routine, execution, aftermath, waiting or a store-first-look. Those contexts are not automatically Gameplay Situations.

Detailed Scenario Beats may own exact local visual requirements and tests. Cross-scenario/project-wide visual requirements may remain in a separate project visual owner.

## 8. Intentional Duplication

A small amount of duplication is allowed when it answers a different-scale question.

Example:

```text
Situation owner:
  a tight dependency exists in general.

Scenario:
  that dependency occurs here,
  in this state and order,
  and affects this concrete pacing/challenge moment.
```

If a Scenario exposes a general tight dependency missing from the Situation owner, treat that as an audit signal and update the Situation record.

## 9. Evidence And Status

Keep source-backed project meaning, inference, hypotheses and decision candidates visibly distinct. A reusable method does not authorize promotion of a project inference into a decision.

## 10. When To Split Further

Do not pre-create one file per Situation, Loop or Scenario.

A Situation or Scenario should own the **required gameplay / experience / presentation result** at its scale. If a hard realization problem later needs its own lifecycle — for example, how to create the intended feeling through gameplay, visuals, audio, UI or another production discipline — a separate realization deep-dive may be justified and linked back to the requirement.

Do not create all such realization files preemptively.

Split a detailed owner only when independent review, reuse, navigation, testing or collaboration makes the split useful. Preserve one clear navigation owner and avoid competing canonical copies.
