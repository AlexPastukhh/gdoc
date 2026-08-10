# Gameplay Situation Planning

Status: active reusable detailed-planning method
Scope: how to discover, define, inspect and later balance a meaningful local player-decision Situation.

Canonical Situation terminology is owned by [`Gameplay Situations, Loops And Scenarios — Principles And Terminology`](../../principles/gameplay-situations-loops-and-scenarios-principles-and-terminology.md).

## 1. Purpose

A `Gameplay Situation` is the main local unit for detailed gameplay planning.

Use this method when you need to understand:

```text
why this decision exists;
why the player cares;
when it can occur and how often;
what rules/state make it possible;
what the player knows / expects;
which choices are materially different;
which mechanics/rules shape those choices;
what each choice changes;
what experience exists around the choice;
which tight relations connect it to other Situations;
what future balance questions the decision creates;
which load-bearing Dynamics repeated / accumulated consequences may contribute to.
```

Do not use a Situation record merely as an event description.

## 2. Ways To Discover A Candidate Situation

A candidate may start from:

```text
desired Player Experience;
player goal / desire;
interesting risk or trade-off;
reference moment;
mechanic / rule;
world or economy state;
need for more / different gameplay content;
an observed emergent Dynamic;
a Scenario gap;
an Integration Probe.
```

These are ideation inputs, not shortcuts around detailed planning.

Example route:

```text
desired experience / content need / risk / reference
→ candidate Situation
→ meaningful-decision check
→ occurrence / state / rules / choices / experience / consequences
→ structural + experience + visual review
→ keep, revise, split or reject.
```

A project's collection of detailed Situation Types is already its Situation inventory. Do not create a second “Situation Bank” unless a separate navigation need justifies it.

## 3. Meaningful-Decision Check

Before expanding a record, ask:

```text
What does the player want, protect, obtain or avoid?
Why does this matter now?
What materially different choices exist?
Why could a reasonable player prefer each choice?
What happens if the player waits / does nothing?
Can the decision improve or worsen the current/future position?
```

If no meaningful decision exists, the thing may instead be:

```text
a trigger;
an observation;
a state;
an execution step;
a consequence;
a Visual Context;
a Scenario Beat.
```

Do not broaden `Gameplay Situation` merely to capture an Experience moment with no decision. Scenario planning already owns observation, waiting, execution, consequence and recovery Beats.

## 4. Occurrence Model — The Situation's Generating Causal Basis

Plan occurrence and frequency together.

The `Occurrence Model` already owns the mechanics/rules/state that make a Situation possible or cause it to appear. Do **not** duplicate this in a second `Situation-Enabling Rules` list.

### Hard Preconditions

Conditions without which the Situation cannot occur.

Do not repeat trivial universal conditions unless they clarify the problem.

### Occurrence Drivers / Alternative Causes

Non-mandatory causes or states that can produce the Situation or make it more likely.

Drivers may come from:

```text
economy / resource state;
environment;
previous choices;
other Situations;
events;
agent behavior;
progression;
external pressure;
mechanics / rules.
```

### Frequency Controls

What determines how often the Situation actually appears?

If very few restrictive conditions exist, ask:

> Why does this Situation not happen constantly?

Frequency later becomes a balance, pacing and repetition concern.

## 5. Mechanics / Rules Relations

Occurrence explains **why the decision problem appears**. Also make visible the rules that determine **what kind of decision it becomes**.

Do not dump every game rule into the Situation. Record only relations that materially shape this decision.

### Decision-Shaping Mechanics / Rules

Ask which mechanics/rules materially affect:

```text
Information;
Option Availability;
Option Cost / Value;
Stakes / Risk;
Expected Consequences;
Actual Consequences;
Wait / Do Nothing;
Desired Future State / Plan, when material.
```

A useful compact relation is:

```text
Rule / Mechanic:
  <reference or short statement>

Affects:
  Information;
  Option Availability;
  Consequences;
  Stakes;
  Wait / Do Nothing.
```

One rule may affect several facets. Define it once and list its relations rather than copying the full rule under every field.

### Experience-Shaping Mechanics / Rules — If Material

Some rules directly create or sustain intended Experience.

Record this only when the relation is useful.

Possible affected experiences include:

```text
pressure;
uncertainty;
reluctance;
anticipation;
ownership;
relief;
dread;
curiosity;
planning satisfaction.
```

Example shape:

```text
Rule:
  a barrier is temporary rather than absolute.

Decision effect:
  waiting exposes the player to worsening risk.

Experience effect:
  safety feels provisional;
  pressure/anticipation persist.
```

Do not use an Experience-Shaping field to claim that one mechanic alone causes the complete Player Experience.

## 6. Relevant State / Economy

`State / economy` is intentionally broad.

Record variables or qualitative states that materially affect:

```text
occurrence;
stakes;
expectations;
option availability;
option cost / value;
risk;
consequences;
rule effects.
```

Examples:

```text
workforce;
capacity;
time pressure;
evidence confidence;
stock;
distance;
preparedness;
route state;
value of a particular person;
authority / relationship consequences.
```

Do not dump the whole game state into every record.

Useful causal relation:

```text
state
→ changes stakes / expectations / plan;

decision
→ changes state;

new state
→ changes later motivations / Situations.
```

## 7. Information State

Record only information relevant to the decision:

```text
what is directly known;
what is reported;
what is inferred;
what is uncertain;
what the player expects;
what the player may be wrong about;
what should remain unknown for the intended decision.
```

The game does not need perfect information. It does need enough information for the intended kind of choice and later causal learning.

When a Decision-Shaping Rule changes what can be known, link the relation rather than describing it only as a UI issue.

## 8. Player Goals, Stakes, Expectations And Plan

Do not compress all of this into a vague `motivation` field.

The point is the rational/causal side of the player's current direction: why the decision matters, what future the player predicts, and what state/later Situation they are trying to create or avoid.

### Current Goal

What is the player currently trying to achieve?

### Stakes

Why does the result matter? What can be gained, preserved, lost or worsened?

### Expectations / Predictions

What does the player think will happen?

Useful questions:

```text
What happens if I do nothing?
What consequences do I predict?
Which future Situations do I expect?
What do I think each option will cause?
```

### Desired Future State

What future game state is the player deliberately trying to create?

### Current Plan / Intention

What broader plan is this decision part of, if one already exists?

Strategic gameplay often begins here: the player acts now because they predict a later Situation or future Experience and want to enter it from a better state.

## 9. Player Experience Around The Situation

Experience is not only an emotional reward after the decision.

> A Gameplay Situation may inherit an emotional/mental context from how the player reached it, create an experience during deliberation, contain anticipation of a future experience, and create another experience through the result.

Keep distinguishable:

```text
Goal
= what I am trying to achieve;

Stake
= why it matters;

Expectation
= what I think will happen;

Plan
= what I intend to do;

Affective Stance
= whether/how I want the expected path/result;

Experience
= what I experience before, during and after the decision.
```

Preserve especially:

```text
I want the outcome
≠
I want to perform the action required to get it.
```

### Entry / Contextual State

What emotional/mental state does the player carry in from earlier play?

### Affective Stance Toward Expectations / Plan

How does the player feel about the future they expect and the plan they believe they may need to execute?

Possible stances include eagerness, reluctance, dread, hope, curiosity, obligation, conflict or resignation.

### Decision Experience

What should deliberation itself feel like?

Examples:

```text
tension;
ownership;
uncertainty;
regret anticipation;
curiosity;
confidence;
hesitation;
sacrifice;
planning satisfaction;
"I found a way out";
"I have to choose the lesser evil".
```

### Anticipated Experience

What future Experience does the player imagine as reward, loss, threat or relief?

### Outcome / Consequence Experience

What Experience should arise when the result becomes legible?

Examples: relief, regret, pride, loss, surprise, validation of a plan, curiosity, desire to repair, mastery.

### Residual Experience

What emotional/mental state does the player carry into later play?

### Anti-Experience / Wrong Response

What local player response would mean the Situation produces the wrong Experience or the right pressure for the wrong reason?

Examples include helplessness instead of costly agency, confusion instead of intended uncertainty, indifference instead of meaningful stakes, or rote execution instead of a real decision.

## 10. Decision Options

For each materially different option, preserve proportionally:

```text
Availability Conditions;
Why This Option May Be Attractive;
Expected Benefit;
Expected Risk / Cost;
Immediate Result;
State / Economy Effects;
Direct Next Situations;
Specific Tight Situation Dependencies;
Important Recurrent State-Mediated Relations.
```

The key question is not merely “can the player click this?” but:

> Why could a reasonable player prefer this option in the current state?

`Wait / do nothing` is an option only when inaction is meaningful because it changes exposure, outcome/state or otherwise has meaningful consequences.

Cross-check important options against `Decision-Shaping Mechanics / Rules`:

```text
Which rule makes this option available?
Which rule makes it costly/valuable?
Which rule makes its consequence different?
```

## 11. Consequence Fan-Out

Do not assume one choice has one next node.

A decision may create:

```text
0..N direct next Situations;
changes to already-active Situations;
shared-state / economy changes;
delayed conditions for future Situations.
```

### Tight Dependencies Only

Record an explicit Situation dependency only when it is specific and decision-relevant.

Examples:

```text
A activates B;
A cancels B;
A removes a prerequisite of B;
A removes a concrete option from active B;
A materially changes B's stakes / risks;
resolving A before B directly changes B's decision space.
```

Do not enumerate every future Situation affected by broad changes such as `worker count -1`, `food -20` or `trust changed`.

### Potential Dynamic Contribution

An immediate consequence/state change is not itself a Dynamic.

When repeated/accumulated/interacting consequences plausibly contribute to a load-bearing systemic tendency, optionally record:

```text
Potential Dynamic Contribution:
  which current / candidate Dynamic may be affected;
  how this consequence contributes causally;
  evidence status / uncertainty.
```

Do not invent a Dynamic for every consequence.

## 12. Typical / Possible Loop Participation

A Situation Type may note Loops it commonly or possibly participates in.

Do not treat that as immutable membership. A concrete Situation Instance may participate in different Loops because current state, stakes and other active problems differ.

Shared state alone is not a reason to assign the Situation to every affected Loop.

## 13. Three Reusable Reviews

After the local decision is understandable, use the reusable surfaces as discovery passes.

### Game Structure Analysis

Use [`Game Structure Analysis`](../game-structure-analysis.md).

Inspect the full concern set and keep the concerns that materially change understanding of this Situation.

### Player Experience / Anti-Experience

Use [`Player Experience And Anti-Experience`](../player-experience-and-anti-experience.md).

This is separate from `Player Experience Around The Situation`:

```text
Player Experience Around The Situation
→ temporal/contextual experience of this concrete decision;

reusable experience pass
→ experience families, supporting conditions,
  behaviors and anti-experiences.
```

### Visual Planning

Use [`Visual Design Analysis And Planning`](../visual-design-analysis-and-planning.md).

Inspect relevant visual concerns and record requirements that materially affect the Situation.

## 14. Balance Bridge

Situation planning should prepare for balance without inventing numbers. Use the shared [`Game Structure Analysis`](../game-structure-analysis.md) balance taxonomy.

Main question:

> At which relevant states do the different choices remain genuinely meaningful instead of one choice becoming universally correct?

Possible fields:

```text
Balance Variables;
Decision-Value Relations;
Frequency Concern;
Threshold Questions;
Risk / Reward Relations;
Dominant-Solution Risk;
Later Numeric Test Needs.
```

A qualitative state such as `only qualified medic available` can be balance-relevant before an exact numeric model exists.

## 15. Scenario Usage

Record where a Situation Type is expected to be instantiated when that aids validation/navigation.

A Scenario should reference the Situation Type and record the concrete Situation Instance rather than duplicating every generic rule.

If Scenario work discovers a general tight dependency or Decision-/Experience-Shaping rule relation missing here, update the Situation owner.

## 16. Suggested Situation Record

Not every field is mandatory. Use the smallest record that preserves the real design problem.

```text
Situation ID / Name
Status / Source

Player-Facing Premise / Trigger

Occurrence Model
  Hard Preconditions
  Occurrence Drivers / Alternative Causes
  Frequency Controls

Mechanics / Rules Relations
  Decision-Shaping Mechanics / Rules
    Rule / Mechanic
    Affects:
      Information
      Option Availability
      Option Cost / Value
      Stakes / Risk
      Expected / Actual Consequences
      Wait / Do Nothing
      Plan / Desired Future State, if material

  Experience-Shaping Mechanics / Rules, if material
    Rule / Mechanic
    Affects:
      <intended Experience facets>

Relevant State / Economy
Information State

Player Goals, Stakes, Expectations And Plan
  Current Goal
  Stakes
  Expectations / Predictions
  Expected Future Situations
  Desired Future State
  Current Plan / Intention

Decision Options
  Availability
  Why Attractive
  Expected Benefit
  Expected Risk / Cost

Consequences
  Immediate Result
  State / Economy Effects
  0..N Direct Next Situations
  Changes To Already-Active Situations
  Specific Tight Dependencies
  Important Recurrent State-Mediated Relations
  Potential Dynamic Contribution, if material

Typical / Possible Loop Participation

Player Experience Around The Situation
  Entry / Contextual State
  Affective Stance Toward Expectations / Plan
  Decision Experience
  Anticipated Experience
  Outcome / Consequence Experience
  Residual Experience
  Anti-Experience / Wrong Response

Game Structure Analysis Review
Player Experience / Anti-Experience Review
Visual Planning Review

Balance Concerns
Scenario Usage
Evidence / Questions / Hypotheses
```

## 17. Content-Production Check

A system/mechanic can be reviewed by asking:

```text
Which meaningful Situations can it produce?
How different are those decisions?
Which rule relations actually make them different?
How often can they recur before becoming rote?
How much bespoke authored content is required?
Can shared rules/state generate variations cheaply?
```

This is a production/design lens, not a rule that “more Situations = better.”

## 18. Do Not

- Do not call an event a Situation only because something happened.
- Do not broaden Situation to every decisionless Experience moment.
- Do not duplicate the Occurrence Model in a second enabling-rules block.
- Do not list all mechanics/rules of the game in every Situation.
- Do not list all game state in every Situation.
- Do not equate a rational goal with emotional willingness to execute the plan.
- Do not force one next Situation per decision.
- Do not connect every broad downstream effect as an explicit Situation edge.
- Do not call one consequence/state change a Dynamic.
- Do not require every Situation to name a Dynamic contribution.
- Do not fix numeric balance without evidence.
- Do not fill Game Structure, Experience or visual reviews mechanically.
