# Gameplay Dynamic Planning

Status: active reusable detailed-planning method
Scope: how to discover, describe, review and validate load-bearing Gameplay Dynamics without confusing them with one-off consequences, Loops, Scenarios or Player Strategy.

Canonical Dynamic terminology is owned by [`Mechanics Create Dynamics — Principles And Terminology`](../../principles/mechanics-create-dynamics-principles-and-terminology.md).

Canonical Gameplay Situation / Event / Loop / Scenario terminology is owned by [`Gameplay Situations, Loops And Scenarios — Principles And Terminology`](../../principles/gameplay-situations-loops-and-scenarios-principles-and-terminology.md).

## 1. Purpose

Use Dynamic planning when the important question is broader than one local decision or one recurrent process:

> What does the operative game system tend to become over time as rules, state, events and player decisions repeatedly interact?

A Dynamic record is useful when the tendency materially affects state/economy trajectory, future opportunity structure, Situation/Event occurrence, option value, Strategy viability, long-term Experience, balance, progression or validation decisions.

Do not create a Dynamic record merely because some quantity changed once.

## 2. Boundary Check

Preserve:

```text
one consequence
≠ Dynamic;

one state change
≠ Dynamic;

one metric trend without causal interpretation
≠ automatically a Dynamic;

Gameplay Situation
≠ Dynamic;
Gameplay Loop
≠ Dynamic;
Scenario
≠ Dynamic;
Player Strategy / Behavior
≠ Dynamic.
```

A useful Dynamic describes a recurrent, persistent or directionally developing **causal tendency**.

## 3. Ways To Discover A Candidate Dynamic

A candidate may come from:

```text
repeated consequences across Situations;
recurrent Loop results;
interaction between several Loops;
positive / negative feedback;
state accumulation;
resource / territory / capability concentration;
repeated player strategy incentives;
representative Scenarios;
prototype / playtest observation;
a reference-game analysis;
an unwanted dominant strategy or anti-experience.
```

Sentence test:

> **In this game, over time, the system tends to develop so that…**

If the completion is only `one worker dies`, `food -20` or `a sector closes`, it is probably a consequence/state change rather than a Dynamic.

## 4. Causal Basis

Ground a Dynamic proportionally in:

```text
Mechanics / Rules;
current / recurrent State;
important Gameplay Events or agent behavior;
player decisions;
consequences that become conditions for later decisions;
feedback structures;
relevant Loops.
```

Useful shape:

```text
Rules / State / Events
→ Situations / Decisions
→ Consequences / State Changes
→ later decision conditions change
→ similar/interacting processes recur
→ systemic tendency develops.
```

Do not require one simple feedback loop when several systems jointly create the tendency.

## 5. Operating Conditions And Time Horizon

Record proportionally:

```text
Relevant State Range / Preconditions
  under which states does the tendency exist or become important?

Onset / Threshold
  what makes the tendency begin or become visible?

Typical Time Horizon
  over what duration / number of cycles / part of a session or campaign
  does it become material?

Persistence Conditions
  what keeps the tendency operating?

Saturation / Equilibrium
  does it hit a ceiling, stable range or self-limiting state?

Weakening / Reversal / Exit Conditions
  what state changes, counter-strategies or other processes can reduce,
  stop or reverse it?
```

This matters for strategic balance: one Strategy may be strong while a Dynamic operates and weak after the state/time horizon changes.

## 6. State / Economy / Opportunity Trajectory

Describe what the Dynamic tends to change over time when material:

```text
resources;
population / agent quality;
territory / access;
capabilities;
knowledge / information;
risk distribution;
reserves / redundancy;
constraints;
opportunities;
future Situation/Event frequency;
Situation stakes;
option availability;
option cost / value / risk.
```

Do not merely list numbers. Explain the causal direction that matters to gameplay.

Example shape only:

```text
repeated high-cost failures
→ reserve capacity decreases
→ later crises start from a worse position
→ emergency trade-offs become harsher
→ recovery consumes more long-term investment
→ reserve capacity stays low.
```

The important planning object is the tendency, not one decrement.

## 7. Relation To Situations, Events And Loops

### Situation contribution

```text
Situation decision
→ state effect
→ possible Dynamic contribution.
```

One contribution does not prove the Dynamic.

### Gameplay Event relation

A Gameplay Event may contribute as a recurrent/important occurrence, signal, pressure or consequence when it has causal relevance. An Event is not itself a Dynamic merely because it repeats.

### Loop output

```text
Loop recurrence
→ repeated / accumulating state effects
→ Dynamic candidate.
```

### Cross-Loop Dynamic

One Dynamic may emerge because several distinct Loops share state, incentives or capacity without being one Loop.

```text
Loop A
+
Loop B
+
Loop C
→ recurrent shared-state pressure
→ Dynamic.
```

Shared state therefore can be a cause of a Dynamic without merging the Loops.

## 8. Observability / Player Model

A Dynamic may be causally real yet poor strategic gameplay if the player cannot form a usable model of it.

Ask proportionally:

```text
What signals reveal the Dynamic?
How early can it be noticed?
What is directly known vs inferred?
Can the player distinguish it from unrelated fluctuation?
Can its direction be predicted without perfect hidden numbers?
How can the player tell whether a counter-strategy changed it?
```

Observability does not require perfect information. It requires enough causal legibility for intended prediction/adaptation.

## 9. Strategy Effects And Player Response

The canonical causal Dynamic ↔ Player Behavior / Strategy relation remains owned by [`Mechanics Create Dynamics`](../../principles/mechanics-create-dynamics-principles-and-terminology.md). The fields below apply that boundary at Dynamic-record scale.

Keep the boundary:

```text
Dynamic
  → what the system tends to do/become;
  → changes incentive / opportunity structure;

Player Strategy
  → deliberate player-authored plan/policy over decisions/time,
    based on a model of the system;
  → what the player chooses to do in response/anticipation.
```

Ask:

```text
Which Strategies become more/less advantageous?
Under what states does that ordering change?
Does the system converge toward one dominant meta-strategy?
Can the player counter, exploit or redirect the tendency?
```

Player Strategy can feed back and strengthen, weaken, redirect or reverse the Dynamic.

The detailed Strategy methodology/filesystem remains separate and unresolved; do not turn this Dynamic record into a complete Strategy record.

## 10. Downstream Gameplay Effects

When material, record how the Dynamic changes later gameplay:

```text
Situation occurrence / frequency / stakes;
Gameplay Event occurrence / intensity;
Loop occurrence / intensity / structure;
option availability / cost / value;
future opportunity structure;
possible Strategy viability.
```

Do not create exhaustive links for every broad downstream state effect.

## 11. Planning State And Evidence Boundary

Do not create a separate Dynamic-specific status system. Use the repository's existing planning/evidence discipline and keep accepted current meaning visibly separate from unaccepted candidates/hypotheses.

Practical organization rule:

```text
Current / Accepted Dynamics
  → Dynamics that belong to current project meaning;

Candidate / Hypothesized Dynamics
  → useful causal possibilities that still need review or evidence.
```

The headings are an organizational boundary, not a new lifecycle taxonomy. A project may use different local headings if the separation remains explicit.

Do not silently move a candidate into current meaning because it appears plausible in one Scenario or causal model. Conversely, a candidate does not need to be discarded merely because it is not yet accepted; keep it in the candidate/hypothesis area while useful to planning/testing.

Design intent can be noted separately when material: a tendency may be desired, tolerated or unwanted, and it may arise emergently from system interaction. This is not a substitute for evidence or acceptance state.

## 12. Game Structure Analysis Review

Use the full [`Game Structure Analysis`](../game-structure-analysis.md) concern set as the structural quality pass. Especially inspect proportionally:

```text
Goals, Motivation And Direction;
Player Verbs And Decisions;
Rules, Resources And Economy;
Challenge, Failure And Progression;
Balance, Decision Space And Strategic Diversity;
Dynamics And State / Opportunity Trajectory;
Causal Legibility And Strategic Planning;
Time, Attention And Information;
Content Structure And Pacing;
World, AI And System Response.
```

Do not maintain a second Dynamic-only quality checklist here. If Dynamic work reveals a reusable quality question that also matters at Situation / Loop / Scenario scale, improve the shared Game Structure concern instead.

A systemically interesting Dynamic can still be weak gameplay if it repeatedly produces obvious/administrative/unmotivating Situations. Strong individual Situations/Loops do not guarantee a strong Dynamic if accumulated incentives collapse into one rote Strategy.

## 13. Player Experience / Anti-Experience Review

Use [`Player Experience And Anti-Experience`](../player-experience-and-anti-experience.md) at the **developing systemic tendency** scale.

Ask what living inside, recognizing and trying to manage this Dynamic tends to create over time:

```text
understanding / anticipation;
agency / ownership;
adaptation;
strategic expression;
competence / mastery;
valuable tension;
curiosity;

or

helplessness;
inevitability;
rote optimization;
permanent firefighting;
chronic anxiety without agency;
monotony;
exhaustion.
```

The Dynamic may be structurally coherent but still create the wrong long-term experience.

## 14. Scenario Manifestation And Evidence

A Scenario can show one concrete manifestation without proving a stable Dynamic.

Record proportionally:

```text
which decisions / consequences contribute;
what strategic space existed at entry;
what strategic space exists at exit;
what tendency appears to be developing;
what alternative branch could falsify interpretation.
```

Evidence ladder:

```text
causal design reasoning
→ Dynamic hypothesis;
one representative Scenario
→ concrete manifestation candidate;
several representative Scenarios / simulations
→ stronger structural evidence;
prototype / repeated playtest / telemetry
→ observed evidence at appropriate fidelity.
```

## 15. Visual Boundary

Do not automatically run the full visual-planning pass on an abstract Dynamic.

If the Dynamic creates a concrete perception/legibility problem, route it through representative Scenarios / Visual Contexts or another justified visual study.

## 16. Suggested Dynamic Record

Not every field is mandatory.

```text
Dynamic ID / Name
Source / Evidence

Dynamic Description / Tendency

Operating Conditions / Relevant State Range
Typical Time Horizon / Onset
Persistence / Saturation
Weakening / Reversal / Exit Conditions

Causal Basis
  Mechanics / Rules
  Relevant State / Economy
  Important Gameplay Events / Agent Behavior
  Player Decisions
  Consequences Feeding Later Conditions
  Feedback Structure, if useful

Contributing Situations
Contributing Events, if material
Contributing Loops
Cross-Loop Relations, if material

State / Economy / Opportunity Trajectory

Effects On Future Gameplay
  Situation Occurrence / Frequency / Stakes
  Event Occurrence / Intensity, if material
  Loop Occurrence / Intensity / Structure, if material
  Option Availability / Cost / Value / Risk

Observability / Player Model
  Signals
  Known vs Inferred
  Predictability
  Counter-Strategy Feedback

Strategies Made More / Less Advantageous
Possible Counter-Strategies / Redirections

Design Intent / Unwanted Risk, if material
Possible Unwanted Variants

Game Structure Analysis Review
Player Experience / Anti-Experience Review

Scenario Manifestations
Prototype / Simulation / Playtest Evidence
Questions / Hypotheses / Risks
```

## 17. Do Not

- Do not call every consequence/state change a Dynamic.
- Do not confuse a repeated process with the tendency that process produces.
- Do not merge Loops merely because they contribute to the same Dynamic.
- Do not equate Player Strategy with the Dynamic that makes it advantageous.
- Do not treat one Scenario as proof of a stable pattern.
- Do not create a mandatory Dynamic Bank for every project.
- Do not mix unaccepted candidates into current meaning without explicit boundary.
- Do not duplicate the full Game Structure checklist in every Dynamic record.
- Do not automatically run a generic visual pass on an abstract Dynamic.
