# Mechanics Create Dynamics — Principles And Terminology

Status: active reusable principle-and-terminology owner
Research basis:

- [`../research/player-experience-research.md`](../research/player-experience-research.md)
- [`../research/anatomy-of-a-game-reference.md`](../research/anatomy-of-a-game-reference.md)

## 1. Purpose And Authority

This file owns the causal vocabulary connecting designed rules to system behavior, player behavior and experience.

It owns the canonical repository meaning of `Gameplay Dynamic` / `System Dynamic`. Canonical meanings of `Gameplay Situation`, `Gameplay Loop` and `Scenario` remain in [`Gameplay Situations, Loops And Scenarios`](gameplay-situations-loops-and-scenarios-principles-and-terminology.md).

It does not define the complete experience taxonomy, reference-selection process or project-specific implementation architecture.

## 2. Core Causal Model

A useful compressed planning model is:

```text
Mechanics / Rules
+ current state / economy
+ game events / agent behavior
        ↓
Gameplay Situations / player decisions
        ↓
consequences / state changes
        ↓
System Dynamics over time
        ↓
incentives / opportunities / future decision conditions
        ↓
Observable Player Behavior / Strategy
        ↓
Player Experience
        ↓
Memory, return, recommendation or rejection.
```

This is not a one-way deterministic pipeline. Later player behavior and decisions feed back into state and can strengthen, weaken, redirect or reverse a Dynamic.

The model is a planning and testing aid, not a guarantee of deterministic human response.

## 3. Mechanic

A `Mechanic` is a designed unit of interaction or rule-governed possibility that participates in play.

Depending on the analytical scale, it may include:

- an action;
- a rule;
- a resource;
- a conversion;
- a constraint;
- a procedure;
- a feedback operation;
- a content-delivery unit.

A mechanic should be named at the scale that owns the current question.

## 4. Rule, Constraint, Resource And Feedback

### Rule

A condition governing what may happen and how state changes.

### Constraint

A limit that shapes possible action, choice or outcome.

### Resource

A stateful quantity, object, opportunity or capacity that may be acquired, spent, exchanged, preserved or lost.

### Feedback

Information returned to the player about action, state, consequence, risk or progress.

Feedback is part of the causal system. A mechanic with unclear feedback may produce different behavior from the same abstract rule with readable feedback.

## 5. Gameplay / System Dynamic

`Gameplay Dynamic` and `System Dynamic` refer to the same canonical systemic concept in this repository. `Gameplay Dynamic` is preferred when discussing gameplay planning scale; `System Dynamic` is useful when emphasizing operative system behavior.

> **A Gameplay Dynamic is a recurrent, persistent or directionally developing causal pattern in what the operative game system tends to become over time as Mechanics / Rules operate, current state, events and agent behavior interact, players make decisions where gameplay exposes them, and resulting consequences / state changes become conditions for later system behavior and decisions.**

A shorter player-facing working formulation is:

> **Dynamic describes what the game tends to turn into as its rules operate, the player makes decisions, and the consequences of those decisions become conditions for later decisions.**

Approved Russian working formulation:

> **Dynamic — это закономерность того, во что игра имеет тенденцию превращаться по мере того, как её правила работают, игрок принимает решения и последствия этих решений становятся условиями следующих решений.**

A Dynamic may manifest through recurrent or developing changes in:

```text
game state / economy;
resources / capabilities / territory / knowledge;
risk and opportunity distributions;
which Gameplay Situations become more or less likely or frequent;
Situation stakes;
option availability;
option cost / value / risk;
which broader player strategies become more or less advantageous.
```

Examples can include:

- escalation;
- risk concentration;
- resource starvation;
- snowballing;
- loss spirals;
- stabilization through negative feedback;
- specialization pressure;
- opportunity concentration;
- expansion overreach;
- dominant-strategy convergence.

Dynamics are not merely authored rules. They are causal tendencies of the operative system across time and repeated/interacting play.

A Dynamic is not automatically a universal law of the whole game. Describe the relevant state range, conditions and time horizon in which the tendency materially operates. A tendency may appear only after a threshold, persist while particular conditions hold, saturate into an equilibrium, or weaken / reverse when state or player strategy changes.

## 6. Dynamic Boundaries

Preserve these distinctions:

```text
one consequence
≠ Dynamic;

one state change
≠ Dynamic;

Gameplay Situation
≠ Dynamic;

Gameplay Loop
≠ Dynamic;

Scenario
≠ Dynamic;

Player Behavior / Strategy
≠ Dynamic.
```

A single consequence can **contribute to** a Dynamic when similar consequences repeat, accumulate or interact.

A Gameplay Situation is a local meaningful decision problem. A Situation may expose or contribute to a Dynamic, but the Dynamic is not the decision itself.

A Gameplay Loop is a recurrent, functionally coherent causal process. A Dynamic is a pattern or tendency produced as one or more operative processes repeatedly change state.

Therefore:

```text
one Loop
→ may produce several Dynamics;

one Dynamic
→ may emerge through several Loops.
```

A Scenario is a concrete chronology. It can show a manifestation of a Dynamic, but one selected Scenario does not by itself prove that a pattern is stable.

Repeated representative Scenarios, simulation, prototype runs, playtests or telemetry can provide evidence that an expected Dynamic actually emerges.

## 7. Player Behavior And Strategy

`Player Behavior` is what players observably do in response to the operative system.

Examples:

- repeat an action for its feel;
- hoard or spend;
- compare alternatives;
- optimize;
- explore optional areas;
- exploit a safe strategy;
- cooperate;
- abandon a route;
- restart;
- form and revise hypotheses.

System Dynamics and Player Behavior are related but not identical. A system pattern may exist even when a player does not notice it; player behavior may also be influenced by prior genre knowledge, interface, social context or misunderstanding.

A Dynamic can change the expected value of strategies without making the strategy itself a Dynamic:

```text
Dynamic changes state / opportunity structure
→ some strategies become more / less advantageous
→ player recognizes or misreads that tendency
→ player forms a plan / strategy
→ later decisions feed back into the system
→ the Dynamic may strengthen, weaken, redirect or reverse.
```

Strategically rich systemic play often allows players to recognize important Dynamics, form plans around them and deliberately influence which future states and Dynamics become more likely.

## 8. Planning State And Evidence Boundary

Do not introduce a separate Dynamic-specific status taxonomy merely to classify records. Use the repository's existing planning / evidence discipline for whether a statement is current accepted meaning, an inference, a hypothesis, a candidate, a question or supported evidence.

When a project contains both accepted current Dynamics and unaccepted candidate / hypothesized Dynamics, keep them visibly separated by placement or headings. Do not place an unaccepted candidate inside current / accepted meaning without an explicit label.

A Dynamic can therefore be useful to analyse before it is accepted as current project meaning. Scenario reasoning or a causal model can justify a hypothesis; repeated simulation, prototype / playtest evidence or telemetry may strengthen or reject it.

Design intent is a separate note from planning state. A tendency may be deliberately desired, tolerated, unwanted or arise emergently from system interaction. `Emergent` does not automatically mean good, accepted or proven.

## 9. Causal Hypothesis

For an important decision, record proportionally:

```text
Mechanic / Rule:
  what is designed;

Dynamic Hypothesis:
  what systemic tendency should emerge and why;

Expected Player Behavior:
  what players should begin doing in response;

Target Experience:
  what value should result;

Conditions:
  what must remain true;

Trade-offs:
  what is gained and lost;

Possible Side Effects:
  unwanted Dynamics or behavior;

Evidence:
  reference analysis, Scenario, simulation, prototype,
  playtest, telemetry or source;

Decision:
  what changes if the hypothesis is supported or rejected.
```

## 10. Feedback Loops And Incentives

A feedback loop returns a system result into future state.

- Positive feedback amplifies an advantage or trend.
- Negative feedback counteracts or stabilizes a trend.

Feedback loops are common causal mechanisms behind Dynamics, but not every Dynamic has to be represented as one simple feedback loop.

An incentive changes the expected value of a choice. Players respond to actual operative incentives, not only to the story the designer tells about them.

Check for:

- rewards that contradict the desired fantasy;
- safe actions that dominate interesting risks;
- recovery systems that erase meaningful failure;
- snowballing that removes later decisions;
- randomness that obscures agency;
- progression that makes mastery irrelevant.

## 11. Dominant Strategy And Convergence

A `Dominant Strategy` is a strategy that is sufficiently effective across relevant states that it suppresses meaningful alternatives.

Not every common strategy is a problem. It becomes a design concern when it destroys:

- decision quality;
- expression;
- adaptation;
- uncertainty;
- the intended experience.

A broader `dominant-strategy convergence` Dynamic can occur when several Mechanics / Loops appear different locally but their incentives repeatedly push players toward the same higher-level strategy.

For example:

```text
system A
system B
system C
  ↓
all are most valuable mainly because they improve strategy X
  ↓
strategy X becomes the stable meta
  ↓
other strategic paths lose relevance.
```

Mechanic variety therefore does not automatically create strategic variety.

## 12. Dynamic Quality Is Reviewed, Not Baked Into The Definition

A bad, boring, unreadable or destructive Dynamic is still a Dynamic.

Do not define quality into the term itself. Review Dynamic quality through the shared [`Game Structure Analysis`](../game-analysis-reference/game-structure-analysis.md) concerns, including proportionally:

```text
quality of meaningful decisions;
goals / motivation;
basic challenge balance;
decision balance;
strategic balance;
required decision / strategy diversity;
state / opportunity trajectory;
causal legibility;
strategic agency / adaptation;
progression / mastery;
content / pacing / information implications.
```

Use [`Player Experience And Anti-Experience`](../game-analysis-reference/player-experience-and-anti-experience.md) to review what living inside, recognizing and managing the Dynamic tends to feel like over time.

## 13. Mechanics Are Evaluated Through Consequences

A mechanic is not justified merely because:

- another successful game has it;
- it sounds novel;
- it fits the setting;
- it is technically feasible;
- it creates more content.

Evaluate it through the causal chain and the target audience.

## 14. Affordance, Signifiers And Readability

A possible action must often be perceived before it can participate in the intended Dynamics.

Preserve the distinctions:

- affordance: what action is possible;
- perceived affordance: what the player believes is possible;
- signifier: what communicates that possibility;
- feedback: what communicates the result;
- conceptual model: how the player understands the system.

A mechanic may be structurally sound and still fail because the player cannot read it.

## 15. Consequences For Reference Analysis

When a reference is used, extract:

```text
the mechanic or rule;
the Dynamics it produces;
the behavior / strategies it encourages;
the experience it supports;
the conditions and feedback that make it work;
the trade-offs and production cost.
```

Copying only the visible feature or setting does not preserve the causal value.

## 16. Consequences For Prototyping

Prototype the earliest uncertain link in the chain.

Examples:

- uncertain input feel → interaction prototype;
- uncertain Dynamic → system toy, repeated simulation or core-loop prototype;
- uncertain player behavior → observed playtest;
- uncertain experience → combined observation and player report;
- uncertain long-term tendency → repeated-session / progression test.

## 17. Do Not

- Do not equate mechanic with experience.
- Do not call one consequence or state change a Dynamic.
- Do not equate Gameplay Loop and Dynamic.
- Do not assume one Scenario proves a stable Dynamic.
- Do not equate System Dynamics with Player Behavior or Strategy.
- Do not assume a desired or hypothesized Dynamic will emerge.
- Do not infer player motivation from behavior alone.
- Do not explain every problem as balance when readability may be the cause.
- Do not require every Dynamic to be good or intended in order to name it.
- Do not add layers to the causal model unless they help a real decision.
