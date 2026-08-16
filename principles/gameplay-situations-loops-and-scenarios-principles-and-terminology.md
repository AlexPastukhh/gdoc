# Gameplay Situations, Loops And Scenarios — Principles And Terminology

Status: active reusable principle-and-terminology owner
Scope: canonical planning meanings and stable distinctions for meaningful gameplay decisions, supporting player-facing Events, recurrent causal processes and concrete chronological Scenarios, including their boundary and relationship to Gameplay Dynamics.

## 1. Purpose And Authority

This file owns the canonical working meanings of:

```text
Gameplay Situation;
Situation Type / Family;
Situation Variant;
Situation Version application;
Situation Instance;
Active Situation;
Direct Situation Transition;
State-Mediated Transition;
General Downstream Effect;
Tight Situation Dependency;
Gameplay Event;
Gameplay Loop;
Loop Phase;
Scenario;
Scenario Beat;
the terminology boundary between Gameplay Situation and broader Visual Context.
```

General `Variant`, reusable contextual `Version`, `Low-Level Element`, Idea and planning-owner meanings are owned by [`Game Planning`](game-planning-principles-and-terminology.md). This file applies those general meanings to gameplay structures and owns Situation-specific semantics.

Detailed planning schemas/questions remain in [`Game Analysis Reference / Gameplay Planning`](../game-analysis-reference/gameplay-planning/README.md).

The canonical meaning of `Gameplay Dynamic` / `System Dynamic` remains in [`Mechanics Create Dynamics`](mechanics-create-dynamics-principles-and-terminology.md).

`Gameplay Situation` is a specific planning term. It does not redefine every ordinary-language “situation” or every Dynamic.

## 2. Gameplay Situation

> **Gameplay Situation is any moment in which the player has a meaningful game decision: the player has a goal, stake, desire or reason to care; there is a risk or opportunity to improve or worsen the current position; and there are materially different ways to act. Waiting or doing nothing is also a decision when it meaningfully exposes the player to consequences.**

`Waiting / doing nothing` is meaningful only when inaction materially changes exposure, outcome/state or otherwise has meaningful consequences.

Therefore:

```text
event / trigger / observation / state
≠ Gameplay Situation automatically.
```

Useful test:

```text
What does the player care about here?
What materially different choices exist?
Why might a reasonable player choose each one?
What can change because of the choice or because the player waits?
```

One Gameplay Situation can contain many materially different options. Number of options alone does not imply several Situations.

### Illustrative example only

The following example explains the distinction. It does **not** introduce a mechanic into any project.

```text
sneeze
≠ Gameplay Situation

sneeze
+ reason to care
+ risk / opportunity
+ meaningful choice
+ consequences
= Gameplay Situation.
```

Likewise, `resource starvation` may be an emergent Dynamic. It becomes a Gameplay Situation when current state creates a meaningful player decision with stakes and materially different responses.

A state such as `Food = Low` is state/information. It becomes a Gameplay Situation when the player perceives/reasons about it inside a meaningful decision problem with choices such as ration / trade / raid / wait.

### Situation boundary

If one decision resolves and a new meaningful decision appears with substantially changed state, motivation, stakes, uncertainty or available options, treat that as a candidate **next Situation Instance** instead of extending one occurrence indefinitely.

Do not infer that every reusable change of circumstances requires a different Situation Type. A materially different reusable context/configuration may instead be a Situation Version when the fundamental meaningful-decision responsibility remains the same.

## 3. Situation Type / Family, Variant, Version, Instance And Active Situation

### Situation Type / Family

A reusable planning identity for one fundamental class/responsibility of meaningful decision problems.

It may group several alternative designs or contextual records when they still answer the same underlying decision responsibility.

A Situation family does not require one canonical main record merely to sit above several alternatives.

### Situation Variant

A `Situation Variant` is an alternative integrated design of the whole Situation.

Different Variants may use different mechanics, option structures, causal models or combinations of lower-level Idea Variants while still addressing the same fundamental Situation responsibility.

### Situation Version

A `Situation Version` applies the general planning `Version` concept to a Situation: it is a **complete Situation Record for one materially different reusable context/configuration of one Situation design/Variant**.

Examples can include stable contextual packages such as Summer, Winter or Siege when they materially change occurrence/state/information/options/stakes/consequences while the fundamental decision responsibility remains the same.

Preserve:

```text
Situation Version
≠ delta / patch against a mandatory base record;

Situation Version
≠ alternative design merely renamed;

Situation Version
≠ document revision;

first/original contextual form
= also a Version once the Version distinction is useful.
```

When several Situation Variants coexist, each Version is scoped unambiguously to its Variant through ownership/location and/or naming.

The same general `Version = contextual/configurational form of the same design` distinction may be used at other planning scales where it is materially useful. Each detailed method remains responsible for how that Version is represented at its own scale.

### Situation Instance

One concrete occurrence of a Situation Type/Variant/Version in an actual Scenario or playthrough.

It carries the specific current people, resources, history, knowledge, concurrent problems, available options, chosen branch and actual Loop participation of that occurrence.

Illustrative boundary:

```text
Reusable Situation:
  Admission Under Uncertain Risk
  → several possible entry paths / options / consequences.

Situation Instance in one Spine:
  these newcomers
  + this evidence
  + these available options
  + restricted admission selected
  + this concrete aftermath.
```

The reusable owner expands broader possibility-space. The Instance remains part of the selected Scenario chronology.

### Active Situation

An `Active Situation` is a currently unresolved meaningful decision problem available, relevant or pressing to the player.

```text
state changed
≠ Active Situation automatically;

meaningful decision is currently present
= Active Situation.
```

At one moment there may be zero, one or several Active Situations.

## 4. Gameplay Event

> **Gameplay Event is an independently useful player-facing occurrence without a mandatory meaningful player decision.**

Use a separate Event only when the occurrence has enough independent planning responsibility to be reused/reviewed outside one chronology.

Preserve:

```text
one-off decisionless chronology detail
  → Scenario Beat;

independently useful decisionless occurrence
with its own planning responsibility
  → Gameplay Event;

meaningful player decision problem
  → Gameplay Situation.
```

A Gameplay Event is a supporting local unit, not a fifth equal heavy planning scale.

Do not require Event stages/phases, Active Event lifecycle, Event Bank, mandatory taxonomy, mandatory project-wide `events.md` or mandatory Loop participation.

## 5. Occurrence And Frequency Principle

A Gameplay Situation or Event can be enabled by different kinds of conditions:

```text
Hard Preconditions
  → without them the unit cannot occur;

Occurrence Drivers / Alternative Causes
  → non-mandatory causes/states that create it
    or make it more likely;

Frequency Controls
  → what determines how often it actually appears.
```

If a reusable unit has almost no restrictive conditions, ask why it does not occur constantly.

Previous player decisions may alter later prerequisites, drivers and frequency.

## 6. State And Economy Are Broader Than Currency

Relevant `state / economy` includes any quantitative or qualitative state that materially affects:

```text
occurrence;
stakes;
expectations;
option availability;
option cost / value;
risk;
consequences;
future decision conditions.
```

Examples include labor availability, capacity, time, evidence confidence, stock, distance, preparedness, route availability, value of a particular person or authority/relationship consequence.

Do not automatically record the entire game state.

## 7. One Decision May Fan Out

A decision does not have exactly one next node. It may cause:

```text
0..N direct next Situations
+
changes to already-active Situations
+
shared-state / economy changes
+
delayed conditions for future Situations / Events.
```

Example:

```text
seal sector
→ trapped-people Situation
AND
→ production-route-loss Situation.
```

At the same time it may change options of a raid-preparation Situation already active. Direct next Situations may belong to different Loops without merging those Loops automatically.

## 8. Situation Relations

### Direct Situation Transition

```text
Situation A
→ decision / immediate result
→ Situation B
```

B follows through strong local causal continuity.

### State-Mediated Transition

```text
Situation A
→ decision
→ important world/economic state changes
→ simulation continues
→ changed state recurrently creates Situation B.
```

The relation is delayed but recurrent/load-bearing enough to analyse explicitly.

### General Downstream Effect

```text
Situation A
→ state changes
→ that state may later affect many systems.
```

This does not create an explicit edge to every future Situation.

> **Explicit Situation-to-Situation transitions should represent strong local causal continuity or a recurrent load-bearing state-mediated relation, not every downstream effect of changed game state.**

### Tight Situation Dependency

A tight dependency exists when one concrete decision directly changes another known Situation in a decision-relevant way: activates/cancels it, changes a prerequisite, adds/removes a concrete option, changes stakes/risk, or makes decision order materially change the other problem.

Broad influence through shared economy/world state remains a state effect rather than an explicit dependency to every affected future Situation.

## 9. Gameplay Loop

Useful chain-shaped shorthand:

> **Gameplay Loop is a recurrent, functionally coherent causal chain of meaningful Situation types, where decisions/results either directly create next situations or modify world/economic state that regularly creates later situations in the same functional cycle.**

Broader canonical definition:

> **Gameplay Loop is a recurrent, functionally coherent causal process involving Gameplay Situations, player decisions, system execution and state change. Its progression may be asynchronous; its Situations need not be adjacent in time; and it may interact with other Loops through shared Situations, shared state, concurrent execution and decision-order effects.**

Example:

```text
Situation A
→ decision
→ workers execute for some time
→ state changes

while that execution continues:
  player resolves Situation B from another Loop

later:
  changed state contributes to next Situation in Loop A.
```

Gameplay Events may participate as triggers, feedback, payoff or pressure occurrences when useful. But:

```text
Event → Event → Event
without load-bearing player agency
≠ Gameplay Loop automatically.
```

### Loop-membership boundary

```text
shared state
≠ same Loop automatically;

temporal overlap
≠ same Loop automatically;

one shared Situation
≠ automatic Loop merge.
```

Loop membership requires recurrent functional/causal coherence useful to analyse as one process.

## 10. Loop Phase

A `Loop Phase` is an optional functional or causal portion of a recurring Gameplay Loop.

Example only:

```text
pressure becomes salient
→ decision / commitment
→ execution
→ accumulation / system response
→ consequence becomes legible
→ adaptation.
```

```text
Loop Phase
= functional / causal;

Scenario Beat
= chronological.
```

Concrete Loops do not have to use one universal phase taxonomy.

One Loop Phase may occupy several Scenario Beats. One Scenario Beat may contribute to phases in several Loops when recurrent processes unfold in the same causal-temporal moment.

A project may group Scenario Beats under a readable `Scenario Phase`, but that chronology grouping is not automatically a Gameplay Loop.

Example:

```text
Scenario Phase: Intake
  → detection
  → contact
  → examination
  → admission decision.

This groups chronology.
It does not prove a recurrent Intake Loop exists.
```

## 11. Parallel And Interacting Loops

Loops may run in parallel while previous decisions are still executing. A player can decide in another Loop during that execution. Multiple Situations may be active at once, and resolving one may change conditions/options/stakes of another before it resolves.

Illustrative structure:

```text
Situation A — staffing decision
→ player assigns workers

Execution A continues

WHILE THAT HAPPENS:

Situation B — another Loop
→ another decision

Situation C may already remain unresolved.
```

A Situation Instance can participate in several Loops without collapsing them into one large Loop.

## 12. Decision-Order Interaction

If A and B are both active:

```text
resolve A first
→ B changes
```

may differ materially from resolving B first. Record as a tight dependency when relation is specific/recurrent; do not treat every broad economic interaction as a decision-order relation.

## 13. Gameplay Dynamic Relationship And Player Strategy Boundary

`Gameplay Dynamic` and canonical Dynamic ↔ Player Behavior / Strategy relation remain owned by [`Mechanics Create Dynamics`](mechanics-create-dynamics-principles-and-terminology.md).

Operational boundary:

```text
Gameplay Situation
  → local meaningful decision problem;

Gameplay Loop
  → recurrent functionally coherent causal process;

Gameplay Dynamic
  → recurrent / persistent / directionally developing systemic tendency;

Player Strategy
  → deliberate player-authored plan/policy across decisions/time;

Scenario
  → concrete chronological traversal where Situations / Events /
    Loops / consequences occur and candidate Dynamics may manifest.
```

A Situation consequence may contribute to a Dynamic without being the Dynamic itself. A Loop may produce one or several Dynamics. A Dynamic may emerge across several Loops without merging them.

## 14. Scenario

> **Scenario is a concrete chronological model of play which selects a path through Gameplay Situations and one or more Gameplay Loops, while also preserving Gameplay Events and the execution, observation, waiting, transition, consequence, payoff and recovery periods between meaningful decisions.**

Routine and breathing-room periods can also be preserved when meaningful.

A Scenario is not only a list of Situation nodes. It may contain routine, execution and breathing room where no new meaningful decision occurs.

A selected Scenario branch is useful for planning, implementation and testing. It does not claim every valid playthrough follows the same path.

### Scenario / reusable-owner boundary

A Scenario may contain concrete low-level manifestations directly. Reusable owners expand beyond one selected chronology.

Example only:

```text
Scenario:
  this newcomer is conditionally admitted
  → this work assignment begins
  → this symptom report arrives.

Reusable owners may later expand:
  Admission Situation;
  examination Execution;
  symptom-report Event;
  related Domain rules.
```

Extraction into reusable owners does not erase the concrete occurrences from the Scenario.

## 15. Scenario Beat

A `Scenario Beat` is a chronological portion of one concrete Scenario.

Possible Beat roles include:

```text
Situation Instance;
Gameplay Event occurrence/reference;
System Execution;
Observation / Information Reveal;
Routine / Waiting;
Transition;
Consequence / Payoff;
Recovery.
```

This is not a closed taxonomy.

One Beat may capture one coherent causal-temporal moment containing a decision, changes to other active Situations, ongoing Loop execution and newly visible information.

Do not split one coherent moment mechanically merely to satisfy taxonomy.

## 16. Visual Context Boundary

`Visual Context` is a broader planning term used when a presentation context matters visually but does not necessarily contain a new meaningful Gameplay Situation.

Examples include routine operation, system execution, waiting, aftermath, store-first-look or another stable presentation context.

```text
Visual Context
≠ Gameplay Situation automatically.
```

The detailed visual method owns Visual Context analysis.

## 17. Concurrency In A Scenario

A Scenario may track Active Situation count, Active Loop count, ongoing executions, time-sensitive decisions, tight dependencies and decision-order effects.

Counts are observations, not automatic verdicts.

> **The number of simultaneously active Situations and Loops can be used as one indicator of gameplay load, pacing and challenge. The number itself does not prove overload or challenge; interpret it in the concrete Scenario.**

## 18. Causal Understanding And Strategy

A systemic game can support:

```text
rules + world response
→ observable consequences
→ causal legibility
→ mental-model refinement
→ prediction
→ planning
→ strategy / play style
→ system tests strategy
→ readable result
→ model revision
→ competence / mastery.
```

This does not require perfect information or exact hidden numbers. It requires enough causality to learn, predict direction and deliberately prepare.

## 19. Do Not

- Do not call every event/state a Gameplay Situation.
- Do not broaden Situation to every decisionless Experience moment.
- Do not treat every reusable contextual change as a new Situation Type automatically.
- Do not use Situation Version as a delta against a mandatory main record.
- Do not use `Version` as another word for alternative design or document revision.
- Do not require every gameplay entity/scale to have Versions.
- Do not turn every downstream state effect into an explicit Situation edge.
- Do not treat the whole simulation as one giant Loop merely because systems share state.
- Do not require Loop Situations to be adjacent in time.
- Do not treat a decisionless Event chain as a Gameplay Loop automatically.
- Do not turn execution/waiting into fake Situations solely to keep a Scenario as a decision-node list.
- Do not infer one Scenario path is the only valid playthrough.
- Do not remove concrete occurrences from a Scenario merely because reusable owners are developed.
- Do not call one consequence/state change/metric movement a Dynamic.
- Do not equate a Gameplay Loop with the Dynamics it may produce.
- Do not equate Player Strategy with a Dynamic.
- Do not treat one Scenario manifestation as proof of a stable Dynamic.
