# Player Experience / Motivation Planning

Status: working / provisional reusable detailed-planning method
Scope: project-specific Experience and Motivation planning, their availability/expectation relations, candidate Experience Promise and Doubt/Concern units, and links to gameplay contexts.

Canonical Player Experience definitions and stable principles remain in [`Player Experience First`](../principles/player-experience-first-principles-and-terminology.md). Reusable Experience-family conditions, behavioral indicators and anti-experience quality checks remain in [`Player Experience And Anti-Experience`](player-experience-and-anti-experience.md). Audience/genre fit remains owned by [`Audience Is Part Of The Game`](../principles/audience-is-part-of-the-game-principles-and-terminology.md).

This method is deliberately provisional and should be revised after a real paired `Spine Scenario ↔ low-level units` pass.

## 1. Core Planning Boundaries

```text
Project Experience
= concrete subjective Experience being planned/supported;

Project Motivation
= what the player wants to seek, continue, deepen, preserve,
  restore, resolve, avoid or validate and therefore may act on;

Situation Goal
= concrete future game result/state pursued in one decision problem.
```

This does not claim motivation is psychologically outside Player Experience. The broad Player Experience definition may include a felt motivational state; the planning responsibilities are kept separate so `experienced`, `wanted` and `pursued now` do not collapse.

Keep both causal directions:

```text
Situation / Event / Execution / observation / result
→ Experience;

previous / anticipated Experience
→ Motivation
→ Goal / Strategy / attention
→ future Situation salience / activity choice.
```

Experience/Motivation need not create a new Situation; they may enrich an existing Situation, Loop, Execution, waiting/observation period, consequence or Scenario interval.

## 2. Experience Opportunity / Legibility / Expectation

```text
Experience Opportunity
= game actually supports/affords the Experience;

Experience Legibility / Awareness
= player understands or can infer it is possible;

Experiential Expectation
= player believes engaging may produce it;

Motivation
= player wants to seek/continue/preserve/resolve/avoid/validate something.
```

Useful chain:

```text
Experience Opportunity
→ Experience Legibility / Awareness
→ Experiential Expectation
→ Motivation
→ Goal / Strategy / attention
→ engagement / Situation salience.
```

These are working distinctions, not four mandatory standalone object types.

## 3. Project Experience

A Project Experience is a concrete game-specific Experience worth independent planning/review.

It may be formulated project-first and classified later, or a reusable Experience family may be used top-down to discover a project-specific manifestation.

A Project Experience may use 0..N reusable families. Classification may be confirmed/candidate/unresolved and is mainly a **quality-analysis lens**, not just navigation.

Example:

```text
Project Experience:
  I gradually turn unknown people into a team I actually understand.

Families:
  Fantasy / Embodiment;
  Curiosity / Discovery;
  Fellowship / Relatedness;
  Autonomy / Agency.

Quality questions:
  Role → shelter leader or spreadsheet operator?
  Curiosity → meaningful unknown traits to discover?
  Relatedness → person or interchangeable stat block?
  Agency → do my organizational choices affect what I learn/trust?
```

### Suggested Project Experience Record

```text
Experience ID / Name
Status / Source

Concrete Project Experience
Why It Matters

Reusable Experience-Family Classification
  0..N; confirmed / candidate / unresolved

Classification-Based Quality Pass
  family questions / references / anti-patterns

Experience Level / Horizon
Opportunity / Supporting Conditions
Experience Legibility / Awareness
Experiential Expectation, when material
Relevant Player Context / Expertise

Carriers / Manifestations
  Situation / Event / Execution / Loop /
  Scenario / observation / consequence / other

Related Project Motivations

Lifecycle / Quality Conditions, when useful
  How It Arises / Supporting Conditions
  What Makes It Persist
  What Strengthens It
  What Weakens It
  How It Resolves / Fades
  What Breaks It / Produces Anti-Experience

Desired Development / Repeated-Play Evolution

Experience Role / Design Intent, when material
  examples only, not closed enum:
  desired / valuable;
  intentionally aversive / threatening;
  incidental / neutral / mixed;
  unwanted-design-failure candidate;
  other / unresolved

Audience-Fit Relation, when material
Anti-Experience / Wrong Response
Evidence / Questions
Experience Hypothesis / Test Relation, when separately useful
Ideas / Variants
```

## 4. Experience Hypothesis Boundary

```text
Project Experience
→ what concrete game-specific Experience is being designed;

Experience Hypothesis
→ testable claim/evidence responsibility about whether/how
  that Experience will be or was delivered.
```

One simple record/file may carry both proportionally, but do not maintain competing evidence owners.

## 5. Project Motivation

Distinguish when useful:

```text
Meta / Experiential Motivation
= why player wants this kind of play/Experience at all;

In-Play Motivation
= what player currently wants to pursue/preserve/resolve/avoid;

Situation Goal
= concrete future result in one decision.
```

A meta player may want a difficult tense game while the in-play player wants to avoid losing the base.

Do not duplicate Experience taxonomy as `want Curiosity`, etc. Use an optional relation:

```text
Project Experience and/or reusable Experience family
+
motivational direction.
```

Working directions, not closed enum: `seek / continue-deepen / preserve / restore / resolve / avoid / validate-prove / other`.

### Suggested Project Motivation Record

```text
Motivation ID / Name
Status / Source
What The Player Wants

Motivation Scope / Context
  meta / experiential
  in-play
  keep distinct from Situation Goal

Related Project Experience(s) / Experience family
Relation / Direction
Classification-Based Motivation Quality Pass, when useful

How It Arises
  Event / previous Experience / discovery / Strategy /
  failure / progression / self-authored aspiration / other

Experience Availability / Awareness Preconditions
Relevant Player Context / Expertise

Lifecycle, when useful
  How It Arises
  What Makes It Persist / Stay Active
  What Strengthens It
  What Weakens It
  What Satisfies / Resolves It
  What Can Kill It
  What Can Invert / Replace It

Typical Goals / Strategies / Plans It Can Produce
Situations / Executions / Loops / other contexts it makes salient
Related Experience Promise(s), if useful
Related Doubts / Concerns
Failure Mode: opportunity exists but Motivation never develops/persists
Evidence / Questions
Ideas / Variants
```

Do not require desired + avoided Experience as a symmetric pair.

## 6. Intended Aversive vs Anti-Experience vs Audience Mismatch

```text
A. intended aversive in-game Experience/outcome
   loss / threat / fear / pressure / costly recovery;

B. anti-experience / design failure
   arbitrary punishment / unreadable causality / grind /
   boring clerical repetition / helplessness for wrong reason;

C. audience / genre mismatch
   coherent gameplay not valued by this player/audience.
```

Audience/genre fit remains an Audience responsibility.

## 7. Candidate Experience Promise

`Experience Promise` is a candidate low-level unit, **not** generic `Player Promise` and not the player's actual `Experiential Expectation`.

Working responsibility: how/why one specific Project Experience becomes expectable.

```text
Experience Promise ID / Name
Status / Source
Experience Being Made Expectable
Underlying Experience Opportunity, if known
How / Where Player Learns It Is Possible
  pre-play / onboarding / in-play / repeated confirmation
Experiential Expectation Being Created
Evidence / Demonstration In Play
Related Motivation(s)
Related Doubt(s)
What Confirms The Expectation
What Breaks / Misleads It
Questions / Ideas
```

Keep inline instead if communication/expectation responsibility has no independent reuse/change lifecycle.

## 8. Candidate Doubt / Concern

A Doubt/Concern is a candidate unit for a player's suspicion that unwanted gameplay Experience exists or desired Experience will not be delivered. It is not the same as rational fear of an in-game penalty.

```text
Doubt ID / Name
Status / Source
What Player Suspects / Fears About Gameplay Experience
Expected Unwanted Experience or Missing Desired Experience
Source / Stage: pre-play / onboarding / in-play / repeated play
Related / Challenged Experience Promise, if any
Truth Status: true / false / partial / unresolved
Underlying Cause, if known
  real gameplay/design problem;
  insufficient communication / proof / legibility;
  audience / genre mismatch;
  mixed / unresolved
Affected Motivations / Experiences
What Strengthens The Doubt
What Counters It
What Would Resolve It
Possible Effect: do not start / stop / avoid activity / choose another strategy / other
Evidence / Questions
Ideas / Variants
```

## 9. Player Context / Expertise

Do not require a full persona. Preserve only context that changes the planning question.

Entry context may include genre/activity literacy/preferences, sought/disliked Experience, prior familiarity, promises/expectations already received and initial doubts.

Keep distinct:

```text
Information supplied by game
≠ what player already knows
≠ what player understands / infers
≠ what options player recognizes
≠ what player notices under current attention.
```

Possible expertise dimensions:

```text
Rules Familiarity;
Causal-Model Accuracy;
Pattern Familiarity;
Option Awareness;
Strategic Repertoire;
Execution Fluency;
Content Familiarity.
```

Useful causal relation:

```text
Objective Game State
→ available information
+
Player Context / Expertise / Mental Model
→ noticed/inferred meaning
→ perceived options
→ predicted consequences
→ perceived risk/value
→ Motivation / Goal / Plan
→ Decision
→ Outcome
→ Delivered Experience
→ Learning
→ changed Expertise / Mental Model.
```

Learning/expertise may become a prerequisite for later deeper Situations without a formal simulation unlock.

A later evaluation method may compare the **same Scenario** under several Player Contexts when audience/expertise differences are the actual question. Do not require that multi-context pass for ordinary Scenario planning.

## 10. Working Cross-Unit Relation Map

The current low-level model depends as much on relations as on unit types. Preserve a useful relation before inventing a new entity solely to carry the connection.

Working examples, all optional/proportional:

```text
Event → Information;
Event → State / Economy;
Event → activates / modifies / resolves Situation;
Event → starts / changes Execution;

Information + Player Expertise → Player Model change;
Player Model change → different perceived options / predictions;

Experience → Motivation;
Experience Promise / Legibility → Experiential Expectation;
Doubt → weakens / redirects Motivation;

Motivation + perceived opportunity/state → Situation salience;
State change → Situation stakes / option value;

Decision → State change;
Decision → starts / changes Execution;
Execution → State / Information / Event / Experience;
Execution → modifies future / already-Active Situation;
Execution → confirms / undermines Experience expectation or Promise;

Outcome / Experience → Learning;
Learning → Expertise / Mental Model change;
Expertise / Mental Model change → changed future perceived decision space;

recurrent causal structure → Loop candidate;
repeated / accumulating tendency → Dynamic candidate.
```

These are relation vocabularies, not claims that every arrow requires a standalone file, direct graph edge or exhaustive dependency map. Broad state-mediated effects can remain state-mediated.

## 11. Ideas / Variants

Use normal scoped Ideas / Idea Variants / Planning Unit Variants beside Experience, Motivation, Promise or Doubt owners when independently useful. Do not create a second Experience/Motivation-specific idea system.

## 12. Evidence / Do Not

Preserve:

```text
designer intent ≠ delivered Experience evidence;
possible Motivation ≠ observed Motivation;
Experience-family classification ≠ quality validated;
Experience Promise exists ≠ player actually formed the expectation.
```

Do not force one Experience per Situation/Loop, create fake Situations for Experience moments, collapse Motivation into Goal/Stake/Expectation/Plan, require a closed Motivation taxonomy, treat unpleasant affect as automatic failure, call audience mismatch anti-experience automatically, promote generic Player Promise into a low-level unit, or require Promise/Doubt/Player Context files when inline planning is enough.
