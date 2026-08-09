# Gameplay Planning — Situations, Loops, Dynamics And Scenarios

Status: active reusable detailed-planning method map
Scope: responsibility boundaries and routing for detailed Gameplay Situation, Loop, Dynamic and Scenario planning.

Canonical Situation / Loop / Scenario terms and stable distinctions are owned by [`Gameplay Situations, Loops And Scenarios — Principles And Terminology`](../../principles/gameplay-situations-loops-and-scenarios-principles-and-terminology.md).

Canonical Dynamic terminology is owned by [`Mechanics Create Dynamics — Principles And Terminology`](../../principles/mechanics-create-dynamics-principles-and-terminology.md).

## 1. Purpose

This area answers:

> Once I choose detailed gameplay as the current planning depth, what do I plan locally, recurrently, systemically and chronologically, and which reusable review surfaces apply at each scale?

Use:

```text
Situations
  → meaningful local decision problems;

Loops
  → recurrent causal processes through decisions,
     execution, state change and later decisions;

Dynamics
  → recurrent / persistent / directionally developing
     systemic tendencies in what gameplay becomes over time;

Scenarios
  → concrete chronology integrating Situation Instances,
     Loops, state change and non-decision gameplay time,
     where candidate Dynamics may manifest.
```

## 2. File Responsibilities

| Owner | Owns | Does not own |
|---|---|---|
| [`situations.md`](situations.md) | Detailed reusable Situation planning method, occurrence/state/decision/experience/dependency/balance fields | One project's actual Situation inventory |
| [`loops.md`](loops.md) | Detailed Loop planning, recurrence, phases, causal membership, overlap, learning, produced Dynamics and Loop-level balance | A universal fixed Loop taxonomy |
| [`dynamics.md`](dynamics.md) | Detailed Dynamic planning/review method, causal basis, state/opportunity trajectory, strategy effects, Scenario manifestations and evidence | A mandatory project-wide Dynamic Bank or the canonical definition of Dynamic |
| [`scenarios.md`](scenarios.md) | Scenario Beats, concrete Situation Instances, concurrency, pacing/challenge integration, Dynamic manifestations and AI scenario exploration | Generic rules of every Situation Type or proof that one observed pattern is a stable Dynamic |

Project-specific detailed records belong in project-local owners, for example `game-planning/<game>/gameplay/`.

## 3. Shared Planning Rule

`Gameplay Situation` remains the main **local** detailed planning unit.

> **Loops, Dynamics and Scenarios do not replace Situation-level planning. They add recurrent-causal, systemic-tendency and chronological/integration views over the gameplay model.**

These scales are related but not a simple hierarchy:

```text
Situation
  → can contribute consequences to a Dynamic;

Loop
  → can produce one or several Dynamics through recurrence;

Dynamic
  → can emerge across several Loops and shared state;

Scenario
  → can show a concrete manifestation of a Dynamic
     without proving that the Dynamic is stable.
```

A project can start at whichever scale makes the current problem clearer. Important findings must still be reconciled into the high-level Game Planning Draft when they change cross-cutting current meaning.

## 4. Reusable Pass Coverage

Use reusable review surfaces as discovery surfaces, not mandatory forms.

| Planning scale | Game Structure Analysis | Player Experience / Anti-Experience | Visual Design Analysis And Planning |
|---|---:|---:|---:|
| Gameplay Situation | Yes | Yes | Yes |
| Gameplay Loop | Yes | Yes | Yes |
| Gameplay Dynamic | Yes | Yes | Not a default Dynamic-scale pass |
| Scenario | Yes | Yes | Yes |

For `Game Structure Analysis` and `Player Experience And Anti-Experience`, the same concern/family set is inspected proportionally at the current scale and only material findings are recorded.

For visual planning, do not automatically run the full `V01–V11` pass on an abstract Dynamic. If a Dynamic creates a real visual problem — for example, how a long-term state trajectory becomes legible — route that question through concrete Scenarios / Visual Contexts or another justified visual study rather than inventing a generic Dynamic visual checklist.

## 5. Scale Differences

### Situation

Main question:

> What meaningful decision exists here, why does the player care, what do they expect and experience, which choices are meaningful and what follows?

### Loop

Main question:

> Which recurrent functionally coherent causal process appears across repeated Situations, execution and state change, and what does repetition do to strategy, pacing, balance, Dynamics and experience?

### Dynamic

Main question:

> What causal tendency does gameplay develop toward over time, which rules / state changes / decisions sustain it, what future opportunities and strategies does it make more or less likely, and can the player understand and influence that trajectory?

### Scenario

Main question:

> What actually happens in time when concrete Situation Instances and Loops overlap, earlier decisions continue executing, state changes accumulate, candidate Dynamics manifest and the player experiences one concrete path?

## 6. Balance Boundary

Use the shared balance taxonomy from [`Game Structure Analysis`](../game-structure-analysis.md):

```text
Basic Challenge Balance;
Decision Balance;
Strategic Balance;
Required Decision / Strategy Diversity.
```

At different planning scales:

```text
Situation
  → local option meaning and immediate challenge;

Loop
  → recurrence, feedback delay, repeated response,
     frequency, progression and overlap;

Dynamic
  → which strategies become advantageous over time,
     state/opportunity trajectory and dominant-meta risk;

Scenario
  → integration balance in concrete chronology,
     including overlap and cumulative pressure.
```

Do not fix numerical balance without evidence merely because a record has a balance field.

## 7. Visual Boundary

`Gameplay Situation` keeps its strict meaningful-decision meaning.

Visual work may also need a broader `Visual Context` such as routine, execution, aftermath, waiting or a store-first-look. Those contexts are not automatically Gameplay Situations.

Detailed Scenario Beats may own exact local visual requirements and tests. Cross-scenario/project-wide visual requirements may remain in a separate project visual owner.

A Dynamic does not automatically receive a full visual-planning pass. When a Dynamic creates a material visual-legibility or long-term-state-presentation problem, plan that problem through concrete contexts or a separately justified study.

## 8. Intentional Duplication

A small amount of duplication is allowed when it answers a different-scale question.

Example:

```text
Situation owner:
  a tight dependency exists in general.

Loop owner:
  recurrence of this relation may contribute
  to an expected Dynamic.

Dynamic owner:
  the tendency is hypothesized / observed
  across repeated state changes.

Scenario:
  this concrete branch manifests the tendency here,
  in this state and order.
```

If a Scenario exposes a general tight dependency missing from the Situation owner, treat that as an audit signal and update the Situation record.

If repeated Scenarios expose a load-bearing Dynamic missing from current planning, create or update a Dynamic record only when that separate owner helps review, balance, experience planning or validation.

## 9. Evidence And Status

Keep source-backed project meaning, inference, hypotheses, decision candidates and evidence visibly distinct.

In particular:

```text
expected Dynamic
≠ observed Dynamic;

one Scenario manifestation
≠ proof of a stable Dynamic.
```

A reusable method does not authorize promotion of a project inference into a decision.

## 10. When To Split Further

Do not pre-create one file per Situation, Loop, Dynamic or Scenario.

Do not create a mandatory project-wide Dynamic Bank. A separate Dynamic record is justified when the tendency is load-bearing enough to need independent review, balance/experience analysis, comparison across Scenarios, validation or collaboration.

Each planning owner should preserve the **required gameplay / experience result** at its scale. Exact local presentation requirements normally belong to concrete Situation / Scenario / Visual Context work rather than an abstract Dynamic. If a hard realization problem later needs its own lifecycle — for example, how to create the intended feeling through gameplay, visuals, audio, UI or another production discipline — a separate realization deep-dive may be justified and linked back to the requirement.

Do not create all such realization files preemptively.

Split a detailed owner only when independent review, reuse, navigation, testing or collaboration makes the split useful. Preserve one clear navigation owner and avoid competing canonical copies.
