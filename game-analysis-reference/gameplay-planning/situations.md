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
what the player knows / expects;
which choices are materially different;
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
a Scenario gap.
```

These are **ideation inputs**, not shortcuts around detailed planning.

Example route:

```text
desired experience / content need / risk / reference
→ candidate Situation
→ meaningful-decision check
→ occurrence / state / choices / experience / consequences
→ structural + experience + visual review
→ keep, revise, split or reject.
```

A project's collection of detailed Situation Types is already its Situation inventory. Do not create a second “Situation Bank” layer unless a project has a separate justified navigation need.

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

### Illustrative example only

This example explains the distinction; it does **not** introduce a project mechanic.

```text
sneeze
≠ Gameplay Situation

sneeze
+ reason to care
+ risk / opportunity
+ meaningful response options
+ consequences
= Gameplay Situation.
```

## 4. Occurrence Model

Plan occurrence and frequency together.

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
external pressure.
```

### Frequency Controls

What determines how often the Situation actually appears?

If very few restrictive conditions exist, explicitly ask:

> Why does this Situation not happen constantly?

Frequency itself later becomes a balance, pacing and repetition concern.

## 5. Relevant State / Economy

`State / economy` is intentionally broad.

Record variables or qualitative states that materially affect:

```text
occurrence;
stakes;
expectations;
option availability;
option cost / value;
risk;
consequences.
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

## 6. Information State

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

## 7. Player Goals, Stakes, Expectations And Plan

Do not compress all of this into a vague `motivation` field.

The point of this block is the rational/causal side of the player's current direction: why the decision matters, what future the player predicts, and what state or later Situation they are trying to create or avoid. Emotional willingness to execute that plan is recorded separately in `Player Experience Around The Situation`.

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

Strategic gameplay often begins here: the player acts now because they predict a later Situation or future experience and want to enter it from a better state.

## 8. Player Experience Around The Situation

Experience is not only an emotional reward after the decision.

> **A Gameplay Situation may inherit an emotional/mental context from how the player reached it, create an experience during deliberation itself, contain anticipation of a future experience, and create another experience through the result of the choice.**

Keep these concepts distinguishable:

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
= whether / how I want the expected path and result;

Experience
= what I experience before, during and after the decision.
```

Especially preserve:

```text
I want the outcome
≠
I want to perform the action required to get it.
```

A player may strongly want to save the base while strongly not wanting to perform the sacrifice they believe is necessary.

Illustrative example only — this does not introduce a mechanic into any project:

```text
Goal:
  obtain medicine.

Stakes:
  without it an important person may die.

Expectation:
  the raid will probably provide medicine,
  but it will be very dangerous.

Plan:
  send the best group now while the window is open.

Affective stance:
  "I really do not want to do this;
   I am afraid of losing these people;
   but I think there is no other reasonable option."
```

This is why:

```text
I want the outcome
≠
I want to perform the action required to get it.
```

### Entry / Contextual State

What emotional/mental state does the player carry into the Situation from earlier play?

Illustrative example:

```text
lost half the base to an outbreak
→ enters the next Situation already
  depressed / cautious / angry / tense.
```

The decision structure can be similar while the experience is very different.

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

What future experience does the player imagine as a reward, loss, threat or relief?

This may overlap with Expectations/Plan for a useful reason:

```text
Expectations / Plan
→ anticipated result as a reason for the decision;

Experience
→ anticipated feeling / value as a design target.
```

### Outcome / Consequence Experience

What experience should arise when the result becomes legible?

Examples: relief, regret, pride, loss, surprise, validation of a plan, curiosity, desire to repair, mastery.

### Residual Experience

What emotional/mental state does the player carry out of this Situation into later play?

### Anti-Experience / Wrong Response

What local player response would mean that this Situation is producing the wrong experience or the right pressure for the wrong reason?

Examples can include helplessness instead of costly agency, confusion instead of intended uncertainty, indifference instead of meaningful stakes, or rote execution instead of a real decision. This local field describes failure in the context of this Situation; the reusable `Player Experience / Anti-Experience` pass below still checks the broader experience families and anti-experience patterns.

## 9. Decision Options

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

`Wait / do nothing` is an option only when inaction is itself meaningful because it changes exposure, outcome/state or otherwise has meaningful consequences.

## 10. Consequence Fan-Out

Do not assume one choice has one next node.

A decision may create:

```text
0..N direct next Situations;
changes to already-active Situations;
shared-state / economy changes;
delayed conditions for future Situations.
```

### Tight dependencies only

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

Do **not** enumerate every future Situation that might be influenced by broad changes such as:

```text
worker count -1;
food -20;
trust changed.
```

Those remain State / Economy Effects unless a later relation is recurrent and load-bearing enough to record explicitly.

Do not add a broad mandatory field such as `what other Active Situations may coexist?` to every Situation record. Situation planning owns only known **specific, tight, decision-relevant** dependencies. Which Situations actually coexist and how their overlap affects pacing/load is primarily Scenario planning.

### Potential Dynamic Contribution

An immediate consequence or state change is **not** itself a Dynamic. When repeated, accumulated or interacting consequences plausibly contribute to a load-bearing systemic tendency, optionally record:

```text
Potential Dynamic Contribution:
  which existing / candidate Dynamic may be affected;
  how this consequence contributes causally;
  evidence status / uncertainty.
```

Do not invent a Dynamic for every consequence. Use this field only when the broader tendency matters to planning, balance, experience or validation.

## 11. Typical / Possible Loop Participation

A Situation Type may note Loops it commonly or possibly participates in.

Do not treat that as immutable membership. A concrete Situation Instance may actually participate in different Loops because current state, stakes and other active problems differ.

Shared state alone is not a reason to assign the Situation to every affected Loop.

## 12. Three Reusable Reviews

After the local decision is understandable, use the three reusable surfaces as discovery passes.

### Game Structure Analysis

Use [`Game Structure Analysis`](../game-structure-analysis.md).

Inspect the full concern set and keep the concerns that materially change understanding of this Situation.

### Player Experience / Anti-Experience

Use [`Player Experience And Anti-Experience`](../player-experience-and-anti-experience.md).

This is separate from `Player Experience Around The Situation` above:

```text
Player Experience Around The Situation
→ temporal/contextual experience of this concrete decision;

reusable experience pass
→ which experience families, supporting conditions,
  behaviors and anti-experiences are relevant.
```

Purposeful overlap is allowed.

### Visual Planning

Use [`Visual Design Analysis And Planning`](../visual-design-analysis-and-planning.md).

Inspect `V01–V11` and any justified project-specific concerns. Record the visual requirements that materially affect the Situation.

## 13. Balance Bridge

Situation planning should prepare for balance without inventing numbers. Use the shared [`Game Structure Analysis`](../game-structure-analysis.md) balance taxonomy. At Situation scale, `Decision Balance` is usually primary, while `Basic Challenge Balance` and broader strategic/Dynamic implications are inspected when material.

Main question:

> **При каких relevant states различные варианты остаются meaningful, вместо того чтобы один вариант становился universally correct?**

Equivalent working question:

> **At which relevant states do the different choices remain genuinely meaningful instead of one choice becoming universally correct?**

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

A qualitative state such as `only qualified medic available` can be balance-relevant even before an exact numeric model exists.

## 14. Scenario Usage

Record where a Situation Type is expected to be instantiated when that aids validation/navigation.

A Scenario should reference the Situation Type and record the concrete Situation Instance rather than duplicating every generic rule.

If Scenario work discovers a general tight dependency missing here, update the Situation owner.

## 15. Suggested Situation Record

Not every field is mandatory. Use the smallest record that preserves the real design problem.

```text
Situation ID / Name
Status / Source

Player-Facing Premise / Trigger

Occurrence Model
  Hard Preconditions
  Occurrence Drivers / Alternative Causes
  Frequency Controls

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

## 16. Content-Production Check

A system/mechanic can be reviewed by asking:

```text
Which meaningful Situations can it produce?
How different are those decisions?
How often can they recur before becoming rote?
How much bespoke authored content is required?
Can shared rules/state generate variations cheaply?
```

This is a production/design lens, not a rule that “more Situations = better.”

## 17. Do Not

- Do not call an event a Situation only because something happened.
- Do not list all game state in every Situation.
- Do not equate a rational goal with the player's emotional willingness to execute the plan.
- Do not force one next Situation per decision.
- Do not connect every broad downstream effect as an explicit Situation edge.
- Do not call one consequence or state change a Dynamic.
- Do not require every Situation to name a Dynamic contribution.
- Do not fix numeric balance without evidence.
- Do not fill Game Structure, experience or visual reviews mechanically.
