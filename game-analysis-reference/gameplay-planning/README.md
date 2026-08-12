# Gameplay Planning — Situations, Loops, Dynamics And Scenarios

Status: active reusable detailed-planning method map
Scope: responsibility boundaries and routing for detailed Gameplay Situation, supporting Gameplay Event, Loop, Dynamic and Scenario planning.

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
| [`situations.md`](situations.md) | Detailed Situation planning: occurrence, state, decision, consequences, experience, mechanics/rules relations, dependency and balance fields | One project's actual Situation inventory |
| [`loops.md`](loops.md) | Detailed Loop planning: recurrence, transitions, loop-sustaining causal basis, overlap, learning, produced Dynamics and Loop-level balance | A universal fixed Loop taxonomy |
| [`dynamics.md`](dynamics.md) | Detailed Dynamic planning/review: causal basis, operating conditions, state/opportunity trajectory, strategy effects, Scenario manifestations and evidence | A mandatory project-wide Dynamic Bank or the canonical definition of Dynamic |
| [`scenarios.md`](scenarios.md) | Scenario Beats, concrete Situation Instances, concurrency, operative-rule manifestations, pacing/challenge integration, Dynamic manifestations and AI exploration | Generic rules of every Situation Type or proof that one observed pattern is a stable Dynamic |

Project-specific detailed records belong in project-local owners, for example `game-planning/<game>/gameplay/`, when that split is useful.

## 3. Shared Planning Rule

`Gameplay Situation` remains the main **local meaningful-decision** unit.

> Loops, Dynamics and Scenarios do not replace Situation-level planning. They add recurrent-causal, systemic-tendency and chronological/integration views over the gameplay model.

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

A project can start at whichever scale makes the current problem clearer. Important accepted cross-cutting findings must still be reconciled into the high-level Game Planning Draft.

## 4. Shared Causal-Basis Concern

`Causal Basis` is a useful cross-scale concern, but it should **not** become one identical template copied into every planning unit.

Ask at each scale:

| Scale | Causal-basis question |
|---|---|
| **Situation** | Which rules/state make the decision problem possible, and which mechanics/rules shape information, option availability/value, stakes, consequences and intended Experience? |
| **Loop** | Which mechanics/rules/state relations create transitions, recurrence, carryover, feedback, recovery/restart and progression changes? |
| **Dynamic** | Which mechanics/rules, recurrent state, events/agents, decisions, consequences and feedback cause the systemic tendency? |
| **Scenario** | Which operative mechanics/rules are needed to understand why this concrete chronology/Beat goes this way? |

Important boundary:

```text
Situation Occurrence Model
  already owns the occurrence/generation causal basis:
  Hard Preconditions
  Occurrence Drivers / Alternative Causes
  Frequency Controls.
```

Do not add a second duplicate list called `Situation-Enabling Rules`. Instead, add the **remaining rule relations** that explain the decision space and, where material, the Experience.

For Scenario:

```text
generic rule
  → belongs in Situation / Loop / Dynamic / system owner;

operative manifestation in this exact chronology
  → may be recorded in the Scenario.
```

## 5. Shared Cross-Scale Concern Audit

Use shared concerns to discover scale-specific questions, not to copy one identical record everywhere.

```text
shared concern
→ scale-specific question
→ scale-specific field only where material

NOT
one identical template copied everywhere.
```

Inspect proportionally:

| Concern | Situation | Loop | Dynamic | Scenario |
|---|---|---|---|---|
| Identity / Source / Status | identity of decision type/version | process identity | tendency/hypothesis identity | chronology/test identity |
| Responsibility / Value | why this decision matters | why recurrence is worth grouping | why tendency matters | what chronology/question is being tested |
| Entry / Preconditions | occurrence model | recurrence/re-entry | operating range/onset | entry conditions/starting state |
| Causal Basis | occurrence + decision/experience shaping rules | loop-sustaining rules/state | causes/feedback | operative rules needed for this path |
| Relevant State | decision-relevant state/economy | carried/shared state | state/opportunity trajectory | concrete starting/changed state |
| Information / Observability | player decision information | feedback/causal legibility | signals/player model | concrete reveals/required understanding |
| Agency | meaningful options/inaction | decisions sustaining/adapting recurrence | influence/counter-strategy, not fake options | concrete decisions along selected branch |
| Experience | around one decision | repeated/learning experience | long-term lived tendency | cumulative temporal experience |
| Consequence / Output | option fan-out/state effect | carried result/feedback | developing tendency/effects | concrete consequences/what changed |
| Time | decision window/deadline | cycle/frequency/delay | horizon/onset/persistence | chronology/temporal markers |
| Relations | tight Situation/unit relations | other Loops/units | contributing Loops/Situations | mapped units/beats/events |
| Resolution / Exit | resolved/expired/transformed | stop/reset/exit conditions | weakening/reversal/exit | exit state |
| Balance / Intensity | option meaning/local challenge | recurrence/feedback/repetition | strategy viability/meta risk | cumulative overlap/pressure |
| Causal Legibility / Learning | why options/outcomes make sense | learn recurrent relation | recognize/predict tendency | connect earlier choices to later result |
| Progression / Adaptation | future-state/plan effect | progression changes recurrence | changing strategic space | concrete before/after adaptation |
| Evidence / Validation | hypotheses/tests for decision | recurrence evidence | repeated manifestation evidence | findings/counter-examples |
| Presentation / Visual | required perception of decision | recurrent-state/phase communication | route via representative contexts when needed | concrete presentation requirements |
| Production / Content Cost | cost of generating meaningful variants | recurrence/content burden | simulation/system burden | concrete authored/integration burden |

`Gameplay Event` remains a lightweight supporting unit. Reuse only the concerns needed by the Event rather than forcing it into a fifth heavy matrix column.

## 6. Reusable Pass Coverage

Use reusable review surfaces as discovery surfaces, not mandatory forms.

| Planning scale | Game Structure Analysis | Player Experience / Anti-Experience | Visual Design Analysis And Planning |
|---|---:|---:|---:|
| Gameplay Situation | Yes | Yes | Yes |
| Gameplay Loop | Yes | Yes | Yes |
| Gameplay Dynamic | Yes | Yes | Not a default Dynamic-scale pass |
| Scenario | Yes | Yes | Yes |

For `Game Structure Analysis` and `Player Experience And Anti-Experience`, inspect the same concern/family set proportionally at the current scale and keep only material findings.

For visual planning, do not automatically run the full visual pass on an abstract Dynamic. Route real Dynamic-related visual questions through concrete Scenarios / Visual Contexts or another justified study.

## 7. Scale Differences

### Situation

Main question:

> What meaningful decision exists here, why does the player care, what do they know/expect, which choices are meaningful, which rules shape those choices and what follows?

### Loop

Main question:

> Which recurrent functionally coherent causal process appears across repeated Situations, execution and state change, which rules sustain recurrence, and what does repetition do to strategy, pacing, balance, Dynamics and Experience?

### Dynamic

Main question:

> What causal tendency does gameplay develop toward over time, which rules/state changes/decisions sustain it, what future opportunities/strategies does it make more or less likely, and can the player understand/influence that trajectory?

### Scenario

Main question:

> What actually happens in time when concrete Situation Instances and Loops overlap, earlier decisions continue executing, state changes accumulate, operative rules manifest, candidate Dynamics appear and the player experiences one concrete path?

## 8. Balance Boundary

The scale-specific passes below are **local balance lenses / inputs**, not a complete Balance architecture. Broader Balance may aggregate multiple Situations/Versions, Game Domain/economy flows, Player Strategies, Dynamics and representative session/campaign horizons. Do not assume the current Gameplay Loop inventory is automatically the canonical session/balance horizon.

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
  → strategies becoming more/less advantageous,
     state/opportunity trajectory and dominant-meta risk;

Scenario
  → integration balance in concrete chronology,
     including overlap and cumulative pressure.
```

Do not fix numerical balance without evidence merely because a record has a balance field.

## 9. Visual Boundary

`Gameplay Situation` keeps its strict meaningful-decision meaning.

Visual work may also need a broader `Visual Context` such as routine, execution, aftermath, waiting or a store-first-look. Those contexts are not automatically Gameplay Situations.

Detailed Scenario Beats may own exact local visual requirements and tests. Cross-scenario/project-wide visual requirements may remain in a separate project visual/presentation owner. When a reusable realization is accepted, promote it out of local exploratory visual-Idea work into that appropriate owner and keep the gameplay requirement/relation linked.

## 10. Intentional Duplication

A small amount of duplication is allowed when it answers a different-scale question.

Example:

```text
Situation:
  a rule changes option availability in general;

Loop:
  recurrence of the same relation shapes feedback/carryover;

Dynamic:
  the repeated effects create a hypothesized tendency;

Scenario:
  this exact branch manifests the relation here.
```

If a Scenario exposes a general tight dependency or rule relation missing from the Situation owner, treat that as an audit signal and update the more general owner.

If repeated Scenarios expose a load-bearing Dynamic missing from planning, create/update a Dynamic record only when independent review is useful.

## 11. Evidence And Status

Keep source-backed project meaning, inference, hypotheses, decision candidates and evidence visibly distinct.

In particular:

```text
expected Dynamic
≠ observed Dynamic;

one Scenario manifestation
≠ proof of a stable Dynamic;

integrated candidate Planning Unit Variant
≠ accepted Situation / Loop / Dynamic / Scenario automatically.
```

A reusable method does not authorize promotion of a project inference into a decision.

## 12. Supporting Gameplay Event Record

Use a separate Gameplay Event only when a decisionless player-facing occurrence has enough independent responsibility to plan/reuse outside one Scenario Beat.

A proportional record may contain:

```text
Event ID / Name
Status / Source

What Happens
Why It Matters

Occurrence / Conditions, if needed
Player Perception / Information, if needed
Intended Experience / Response, if needed

Consequences
  State Changes
  Triggered / Changed Situations, if any

Loop / Dynamic Relations, if material
Evidence / Questions
```

Timing, frequency, presentation and content cost are added only when material.

Do not introduce mandatory Event taxonomy, Event phases, Active Event, Event Bank, a separate `events.md` or mandatory Loop participation.

## 13. When To Split Further

Do not pre-create one file per Situation, Loop, Dynamic or Scenario.

Do not create a mandatory project-wide Dynamic Bank.

Split a detailed owner only when independent review, reuse, navigation, testing, collaboration or production ownership makes the split useful.

Each planning owner should preserve the **required gameplay / Experience result** at its scale. Exact local presentation requirements normally belong to concrete Situation / Scenario / Visual Context work rather than an abstract Dynamic.

Do not create all realization/deep-dive files preemptively.
