# Gameplay Situations, Loops And Scenarios — Principles And Terminology

Status: active reusable principle-and-terminology owner
Scope: canonical planning meanings and stable distinctions for meaningful gameplay decisions, recurrent causal processes and concrete chronological scenarios, including their boundary and relationship to Gameplay Dynamics.

## 1. Purpose And Authority

This file owns the canonical working meanings of:

```text
Gameplay Situation;
Situation Type;
Situation Instance;
Active Situation;
Direct Situation Transition;
State-Mediated Transition;
General Downstream Effect;
Tight Situation Dependency;
Gameplay Loop;
Loop Phase;
Scenario;
Scenario Beat;
the terminology boundary between Gameplay Situation and broader Visual Context.
```

Detailed planning schemas and questions remain in [`Game Analysis Reference / Gameplay Planning`](../game-analysis-reference/gameplay-planning/README.md).

The canonical meaning of `Gameplay Dynamic` / `System Dynamic` remains in [`Mechanics Create Dynamics`](mechanics-create-dynamics-principles-and-terminology.md). This file owns the boundaries between that systemic term and Gameplay Situation / Loop / Scenario.

`Gameplay Situation` is a **specific planning term**. It does not redefine every ordinary-language “situation” or every Dynamic. A systemic pattern such as resource starvation may be a Dynamic without itself being a Gameplay Situation.

## 2. Gameplay Situation

> **Gameplay Situation is any moment in which the player has a meaningful game decision: the player has a goal, stake, desire or reason to care; there is a risk or opportunity to improve or worsen the current position; and there are materially different ways to act. Waiting or doing nothing is also a decision when it meaningfully exposes the player to consequences.**

`Waiting / doing nothing` is meaningful only when inaction materially changes exposure, outcome/state or otherwise has meaningful consequences.

Therefore:

```text
event / trigger / observation
≠ Gameplay Situation automatically.
```

A useful test is:

```text
What does the player care about here?
What materially different choices exist?
Why might a reasonable player choose each one?
What can change because of the choice or because the player waits?
```

One Gameplay Situation can contain many materially different options. The number of options does not by itself imply several Situations.

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

Likewise, `resource starvation` may be an emergent Dynamic. It becomes a Gameplay Situation when the current state creates a meaningful player decision with stakes and materially different responses.

### Situation boundary

If one decision resolves and a new meaningful decision appears with substantially changed state, motivation, stakes, uncertainty or available options, treat that as a candidate **next Situation** instead of extending one record indefinitely.

## 3. Situation Type, Instance And Active Situation

### Situation Type

A reusable planning description of a class of meaningful decision problems.

It may describe possible occurrence conditions, decisions, consequences, experience and possible/typical Loop participation.

### Situation Instance

One concrete occurrence of a Situation Type in an actual Scenario or playthrough.

It carries the specific current people, resources, history, knowledge, concurrent problems, available options, chosen branch and actual Loop participation of that occurrence.

The same Situation Type may participate in different Loops under different concrete conditions.

### Active Situation

An `Active Situation` is a **currently unresolved meaningful decision problem available, relevant or pressing to the player**.

```text
state changed
≠ Active Situation automatically;

meaningful decision is currently present
= Active Situation.
```

At one moment there may be zero, one or several Active Situations.

## 4. Occurrence And Frequency Principle

A Gameplay Situation can be enabled by different kinds of conditions:

```text
Hard Preconditions
  → without them the Situation cannot occur.

Occurrence Drivers / Alternative Causes
  → non-mandatory causes or states that can create it
     or make it more likely.

Frequency Controls
  → what determines how often it actually appears.
```

If a Situation has almost no restrictive conditions, ask why it does not occur constantly.

Previous player decisions may alter later prerequisites, drivers and frequency.

## 5. State And Economy Are Broader Than Currency

For Situation / Loop / Dynamic reasoning, relevant `state / economy` includes any quantitative or qualitative state that materially affects:

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

Examples can include labor availability, capacity, time, evidence confidence, stock, distance, preparedness, route availability, the value of a particular person or an authority/relationship consequence.

Do not automatically record the entire game state.

## 6. One Decision May Fan Out

A decision does not have exactly one “next node.” It may cause:

```text
0..N direct next Situations
+
changes to already-active Situations
+
shared-state / economy changes
+
delayed conditions for future Situations.
```

Example shape:

```text
seal sector
→ trapped-people Situation
AND
→ production-route-loss Situation
```

At the same time it may change the options of a raid-preparation Situation that was already active. The direct next Situations may belong to different Loops, and one decision may therefore affect several Loops without automatically merging them.

## 7. Situation Relations

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

The relation is delayed but recurrent and load-bearing enough to analyse explicitly.

### General Downstream Effect

```text
Situation A
→ state changes
→ that state may later affect many systems.
```

This does not create an explicit edge to every future Situation.

> **Explicit Situation-to-Situation transitions should represent strong local causal continuity or a recurrent load-bearing state-mediated relation, not every downstream effect of changed game state.**

### Tight Situation Dependency

A tight dependency exists when one concrete decision directly changes another known Situation in a decision-relevant way, for example:

```text
activates or cancels it;
removes a prerequisite;
adds or removes a concrete option;
materially changes its stakes / risks / decision space;
changes it depending on which of two active decisions is resolved first.
```

> **Situation-to-Situation dependency is recorded only when the relation is specific and decision-relevant. Broad influence through shared economy or world state remains a state effect rather than an explicit Situation dependency.**

For example, `worker count -1` may affect many later systems. That alone is not a tight dependency to every later staffing Situation.

## 8. Gameplay Loop

A useful chain-shaped shorthand, especially when deriving a concrete Loop from repeated Situation relations, is:

> **Gameplay Loop is a recurrent, functionally coherent causal chain of meaningful Situation types, where decisions/results either directly create next situations or modify world/economic state that regularly creates later situations in the same functional cycle.**

The broader canonical definition is:

> **Gameplay Loop is a recurrent, functionally coherent causal process involving Gameplay Situations, player decisions, system execution and state change. Its progression may be asynchronous; its Situations need not be adjacent in time; and it may interact with other Loops through shared Situations, shared state, concurrent execution and decision-order effects.**

The first wording is a useful special case. The second prevents a Loop from being reduced to adjacent decision nodes when execution, delay or other gameplay occurs between its Situations.

`Chain` may describe a simple local example, but a Gameplay Loop is not required to be a contiguous chain of decision nodes.

For example:

```text
Situation A
→ decision
→ workers execute for some time
→ state changes

while that execution continues:
  the player resolves Situation B from another Loop

later:
  the changed state contributes to the next Situation in Loop A.
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

Loop membership requires recurrent functional/causal coherence that is useful to analyse as one process.

> **Two Situations are not members of the same Loop merely because they influence the same shared state. Two Loops are not merged merely because they overlap in time, share one Situation, or affect each other. Loop membership requires recurrent functional/causal coherence.**

## 9. Loop Phase

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

Concrete Loops do not have to use one universal phase taxonomy.

```text
Loop Phase
= functional / causal;

Scenario Beat
= chronological.
```

One Loop Phase may occupy several Scenario Beats. One Scenario Beat may also contribute to or change phases in several Loops when several recurrent processes are unfolding in the same causal-temporal moment.

## 10. Parallel And Interacting Loops

> **Loops may run in parallel while their previous decisions are still being executed. A player can make a decision in another Loop during that execution. Multiple Situations may be active at once, and resolving one may change the conditions, options, stakes or risks of another before it is resolved.**

Illustrative structure:

```text
Situation A — staffing decision
→ player assigns workers

Execution A continues:
  workers move / work / produce

WHILE THAT HAPPENS:

Situation B — another Loop
→ player makes another decision

Situation C may already remain unresolved.
```

A Situation Instance can therefore participate in several Loops without collapsing them into one large Loop.

## 11. Decision-Order Interaction

If A and B are both active:

```text
resolve A first
→ B changes
```

may differ materially from:

```text
resolve B first
→ A changes.
```

Record this as a tight dependency when the relation is specific. Do not treat every broad economic interaction as a decision-order relation.

## 12. Gameplay Dynamic Relationship

`Gameplay Dynamic` is canonically defined in [`Mechanics Create Dynamics`](mechanics-create-dynamics-principles-and-terminology.md). The operational boundary here is:

```text
Gameplay Situation
  → local meaningful decision problem;

Gameplay Loop
  → recurrent functionally coherent causal process;

Gameplay Dynamic
  → recurrent / persistent / directionally developing
     systemic tendency produced as rules, state, events,
     decisions and consequences interact over time;

Scenario
  → concrete chronological traversal in which
     Situations / Loops / consequences occur and
     linked or candidate Dynamics may manifest.
```

A Situation consequence may **contribute to** a Dynamic without being the Dynamic itself.

A Loop may produce one or several Dynamics through recurrence. A Dynamic may also emerge across several distinct Loops through shared state, incentives or capacity without merging those Loops.

> **Gameplay Loop describes a recurrent causal process; Gameplay Dynamic describes a recurrent or developing tendency in what one or more operative processes make the game become.**

A Scenario can show a concrete manifestation of a Dynamic, but one selected Scenario does not by itself prove that the Dynamic is stable. Repeated representative Scenarios, simulation, prototype runs, playtests or telemetry can provide stronger evidence.

## 13. Scenario

> **Scenario is a concrete chronological model of play which selects a path through Gameplay Situations and one or more Gameplay Loops, while also preserving the execution, observation, waiting, transition, consequence, payoff and recovery periods between meaningful decisions.**

Routine and breathing-room periods can also be preserved when they are meaningful to the concrete chronology.

A Scenario is therefore not only a list of Situation nodes. It may contain routine, execution and breathing room where no new meaningful decision occurs.

A selected Scenario branch is useful for planning, implementation and testing. It does not claim that every valid playthrough follows the same path.

## 14. Scenario Beat

A `Scenario Beat` is a chronological portion of one concrete Scenario.

Possible beat roles include:

```text
Situation Instance;
System Execution;
Observation / Information Reveal;
Routine / Waiting;
Transition;
Consequence / Payoff;
Recovery.
```

This is not a closed taxonomy.

One Beat may legitimately capture one causal-temporal moment in which:

```text
a decision in Situation A occurs;
active Situation B changes because of it;
execution from Loop C continues;
new information becomes visible.
```

Do not split one coherent moment mechanically merely to satisfy a taxonomy.

## 15. Visual Context Boundary

`Visual Context` is the broader planning term used when a presentation context matters visually but does not necessarily contain a new meaningful Gameplay Situation.

Examples can include:

```text
routine operation;
system execution;
waiting;
aftermath;
store-first-look;
other stable presentation contexts.
```

Therefore:

```text
Visual Context
≠ Gameplay Situation automatically.
```

The detailed visual method owns how Visual Contexts are analysed. This definition exists here to keep the gameplay ontology and visual-planning terminology from silently using the same word `Situation` for two different concepts.

## 16. Concurrency In A Scenario

A Scenario may track:

```text
Active Situation count;
Active Loop count;
ongoing executions;
time-sensitive decisions;
specific tight dependencies;
decision-order effects.
```

The counts are observations, not automatic verdicts. Do not introduce another formal Loop category or universal load formula solely to make the count look precise. Record the concrete Active Loops that make sense in the Scenario and interpret the number from the example.

> **The number of simultaneously active Situations and Loops can be used as one indicator of gameplay load, pacing and challenge. The number itself does not prove that the player is overloaded or challenged; interpret it in the concrete Scenario.**

## 17. Causal Understanding And Strategy

A systemic game can support a progression from readable consequences to self-authored strategy:

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

This principle does not require perfect information or exact hidden numbers. It requires enough causality to learn, predict direction and deliberately prepare.

## 18. Do Not

- Do not call every event or state a Gameplay Situation.
- Do not turn every downstream state effect into an explicit Situation edge.
- Do not treat the whole simulation as one giant Loop merely because systems share state.
- Do not require Loop Situations to be adjacent in time.
- Do not turn execution/waiting into fake Situations solely to keep a Scenario as a decision-node list.
- Do not infer that one Scenario path is the only valid playthrough.
- Do not call one consequence, one state change or one metric movement a Dynamic.
- Do not equate a Gameplay Loop with the Dynamics it may produce.
- Do not treat one Scenario manifestation as proof of a stable Dynamic.
