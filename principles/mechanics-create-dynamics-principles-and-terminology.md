# Mechanics Create Dynamics — Principles And Terminology

Status: active reusable principle-and-terminology owner
Research basis:

- [`../research/player-experience-research.md`](../research/player-experience-research.md)
- [`../research/anatomy-of-a-game-reference.md`](../research/anatomy-of-a-game-reference.md)

## 1. Purpose And Authority

This file owns the causal vocabulary connecting designed rules to system behavior, player behavior and experience.

It does not define the complete experience taxonomy, reference-selection process or project-specific implementation architecture.

## 2. Core Causal Chain

```text
Mechanics / Rules
  → System Dynamics
  → Observable Player Behavior
  → Player Experience
  → Memory, return, recommendation or rejection.
```

The chain is a planning and testing model, not a guarantee of deterministic human response.

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

## 5. Dynamics

`Dynamics` are patterns and situations that emerge during actual interaction among rules, state, players and context.

Examples include:

- escalation;
- risk concentration;
- resource starvation;
- build specialization;
- cooperation;
- camping;
- snowballing;
- cautious exploration;
- repeated experimentation;
- avoidance;
- dominant strategies.

Dynamics are not merely authored rules. They are the behavior of the operative system.

## 6. Player Behavior

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

## 7. Intended And Emergent Dynamics

### Intended Dynamics

Patterns the design is deliberately trying to produce.

### Emergent Dynamics

Patterns arising from interactions that were not fully specified as explicit outcomes.

Emergent does not automatically mean good. It may be:

- valuable;
- neutral;
- confusing;
- exploitable;
- destructive to the intended experience.

## 8. Causal Hypothesis

For an important decision, record:

```text
Mechanic / Rule:
  what is designed;

Expected Dynamics:
  what system behavior should emerge;

Expected Player Behavior:
  what players should begin doing;

Target Experience:
  what value should result;

Conditions:
  what must remain true;

Trade-offs:
  what is gained and lost;

Possible Side Effects:
  unwanted dynamics or behavior;

Evidence:
  reference analysis, prototype, playtest, telemetry or source;

Decision:
  what changes if the hypothesis is supported or rejected.
```

## 9. Feedback Loops And Incentives

A feedback loop returns a system result into future state.

- Positive feedback amplifies an advantage or trend.
- Negative feedback counteracts or stabilizes a trend.

An incentive changes the expected value of a choice. Players respond to actual operative incentives, not only to the story the designer tells about them.

Check for:

- rewards that contradict the desired fantasy;
- safe actions that dominate interesting risks;
- recovery systems that erase meaningful failure;
- snowballing that removes later decisions;
- randomness that obscures agency;
- progression that makes mastery irrelevant.

## 10. Dominant Strategy

A `Dominant Strategy` is a strategy that is sufficiently effective across relevant states that it suppresses meaningful alternatives.

Not every common strategy is a problem. It becomes a design concern when it destroys:

- decision quality;
- expression;
- adaptation;
- uncertainty;
- the intended experience.

## 11. Mechanics Are Evaluated Through Consequences

A mechanic is not justified merely because:

- another successful game has it;
- it sounds novel;
- it fits the setting;
- it is technically feasible;
- it creates more content.

Evaluate it through the causal chain and the target audience.

## 12. Affordance, Signifiers And Readability

A possible action must often be perceived before it can participate in the intended dynamics.

Preserve the distinctions:

- affordance: what action is possible;
- perceived affordance: what the player believes is possible;
- signifier: what communicates that possibility;
- feedback: what communicates the result;
- conceptual model: how the player understands the system.

A mechanic may be structurally sound and still fail because the player cannot read it.

## 13. Consequences For Reference Analysis

When a reference is used, extract:

```text
the mechanic or rule;
the dynamics it produces;
the behavior it encourages;
the experience it supports;
the conditions and feedback that make it work;
the trade-offs and production cost.
```

Copying only the visible feature or setting does not preserve the causal value.

## 14. Consequences For Prototyping

Prototype the earliest uncertain link in the chain.

Examples:

- uncertain input feel → interaction prototype;
- uncertain dynamics → system toy or core-loop prototype;
- uncertain behavior → observed playtest;
- uncertain experience → combined observation and player report;
- uncertain long-term loop → repeated-session or progression test.

## 15. Do Not

- Do not equate mechanic with experience.
- Do not assume intended dynamics will emerge.
- Do not infer player motivation from behavior alone.
- Do not explain every problem as balance when readability may be the cause.
- Do not add layers to the causal chain unless they help a real decision.
- Do not treat emergent behavior as automatically desirable.
