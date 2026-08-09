# Gameplay Scenario Planning

Status: active reusable detailed-planning method
Scope: how to plan, inspect and validate one concrete chronological traversal through Gameplay Situations and Loops, including non-decision time and concurrent processes.

Canonical Scenario terminology is owned by [`Gameplay Situations, Loops And Scenarios — Principles And Terminology`](../../principles/gameplay-situations-loops-and-scenarios-principles-and-terminology.md).

## 1. Purpose

A Scenario turns reusable gameplay structure into one concrete chronology detailed enough to plan, implement or test.

It is especially useful when the important question is not one isolated decision but:

```text
what happens before and after it;
which previous decisions are still executing;
which other Situations become active;
which Loops overlap;
how pressure rises/falls;
what the player understands and experiences over time.
```

A selected branch is a planning/test path, not a claim that every playthrough follows it.

## 2. Scenario Is More Than Situation Nodes

A concrete Scenario may include:

```text
orientation;
routine;
observation;
meaningful decisions;
planning;
system execution;
waiting;
information reveals;
transitions;
consequences;
payoff;
recovery;
breathing room.
```

Do not invent fake Gameplay Situations for periods in which no new meaningful decision exists.

## 3. Situation Instance

A Scenario normally references a reusable Situation Type and records the concrete `Situation Instance`:

```text
specific people;
specific resources / capacity;
specific previous losses;
specific knowledge / expectations;
specific other Active Situations;
specific available options;
specific actual Loop participation;
specific selected branch;
specific consequences.
```

Do not duplicate every generic Situation rule when a reference is sufficient.

## 4. Scenario Beat

A `Scenario Beat` is a chronological portion of the Scenario.

Useful roles include:

```text
Situation Instance;
System Execution;
Observation / Information Reveal;
Routine / Waiting;
Transition;
Consequence / Payoff;
Recovery.
```

The list is not mandatory or closed.

One Beat may contain several simultaneous facts when they form one causal-temporal moment, for example:

```text
decision in Situation A
+
active Situation B changes because of it
+
execution from Loop C continues
+
new information becomes visible.
```

One Loop Phase may span several Beats. Conversely, one Beat may contribute to or change phases in several Loops when those processes overlap in the same moment.

## 5. Scenario Beat Record

Use proportionally:

```text
Beat ID / Title
Temporal Marker
Beat Role

Situation Type Reference, if any
Loop / Loop Phase Mapping, if useful

Starting / World State
What Happens

Player Goals / Stakes / Expectations / Plan, as relevant
Developer Purpose
Intended Player Response

Information Available
Required Understanding
What Should Remain Unknown

Meaningful Decisions, if this is a Situation Instance
Decision Availability
Why Each Option May Be Attractive
Selected Scenario Branch

System Response
Immediate Consequences
State Effects
0..N Direct Next Situations, if any
Actual Loop Participation, if this is a Situation Instance

Active Situation Count
Active Loop Count
Ongoing Executions
Time-Sensitive Decisions
Specific Tight Dependencies
Decision-Order Effects

Player Experience
Gameplay Requirements
Presentation Requirements
Visual Requirements / Checks
References + Responsibility

Questions
Assumptions
Hypotheses
Risks
Validation Questions
Exit State
```

Not every Beat needs every field.

## 6. Intended Player Response Is Broader Than Emotion

A design target may be:

```text
emotion;
impulse;
desire;
attention shift;
question;
belief;
hesitation;
reaction;
planning impulse;
ownership;
curiosity;
relief.
```

For example, `the player should themselves want to obtain this capability` is a valid Intended Player Response even though it is not merely an emotion.

## 7. Presentation Is Broader Than Visuals

Scenario presentation requirements can include:

```text
visual;
audio;
UI / information presentation;
timing / pacing;
agent/world behavior;
control feedback.
```

Do not ask the visual layer alone to produce an experience whose cause belongs to pacing, audio, information or system behavior.

## 8. Concurrent Situations And Loops

At a concrete time, the Scenario may have several Active Situations while earlier decisions continue executing.

Track when useful:

```text
Active Situation count;
Active Loop count;
ongoing executions;
time-sensitive decisions;
specific tight dependencies;
decision-order effects.
```

These values are not automatic scores. There is no need to turn them into a universal formula or to solve passive/background-loop counting abstractly before looking at a concrete example.

> **The number of simultaneously active Situations and Loops can be used as one indicator of gameplay load, pacing and challenge. The number itself does not prove that there is too much or too little load; interpret it in the concrete Scenario.**

A simple chronology can therefore record:

```text
00:00  Situations 0 / Loops 1
04:00  Situations 1 / Loops 2
11:00  Situations 3 / Loops 3
15:00  Situations 1 / Loops 2
```

without pretending those numbers alone determine quality.

## 9. Parallel Loop Tracks

When it helps, represent Scenario chronology as several parallel tracks:

```text
Time →

Production Loop   ───── execution ───── Situation ───
Disease Loop             Situation ─── execution ────
Raid Loop        Situation / preparation ────────────

Active Situations        1      2       3      1
Active Loops              1      2       3      2
Player decisions          ↓      ↓              ↓
```

The representation is optional; the principle is that Loops need not wait for each other sequentially.

A Scenario may cross several Loops that interact only through shared state. Showing them in the same chronology does **not** merge them into one Loop.

## 10. Tight Dependencies In Scenario

It is acceptable to repeat a tight dependency already owned by Situation planning if doing so makes the concrete Scenario understandable.

```text
Situation owner:
  dependency exists generally.

Scenario:
  resolving A first here removes option B2,
  changing the concrete pacing/challenge problem.
```

If the Scenario reveals a general specific dependency that was not recorded in the Situation Type, audit/update the Situation owner.

Broad economy/state effects still do not need exhaustive Situation-to-Situation links.

## 11. Game Structure Review

A Scenario can use the full [`Game Structure Analysis`](../game-structure-analysis.md) concern set.

For a detailed gameplay Scenario, normally make an **explicit review** of at least:

```text
Core / Session / Long-Term Loops;
Player Verbs And Decisions;
Goals, Motivation And Direction;
Rules, Resources And Economy;
Challenge, Failure And Progression;
Time, Attention And Information;
Content Structure And Pacing;
Concurrency, Loop Overlap And Decision Load;
World, AI And System Response;
Causal Legibility And Strategic Planning;
Interface, Feedback And Readability.
```

`Explicit review` means look deliberately; `nothing material found` is an acceptable result.

For a full-demo / first-play Scenario, also explicitly inspect:

```text
Onboarding And Mental Model;
Return, Stopping And Exhaustion.
```

Use `Content-Production Model` explicitly when the Scenario is also being used to estimate content/production burden.

Other concerns remain available when relevant.

## 12. Pacing / Challenge Review

Scenario scale is where concurrency, timing and cumulative pressure become visible.

Ask:

```text
How dense are meaningful Situations?
How do Active Situation / Loop counts rise and fall?
Where are peaks and breathing room?
How many previous decisions are still executing?
How many decisions are time-sensitive?
How long is decision → feedback delay?
Do several individually good Loops create bad pacing together?
Does overlap create meaningful prioritization or only noise?
Does the player have time to understand consequences before the next demand?
Does repetition become rote?
```

Pacing can emerge from overlapping systemic Loops rather than authored event scheduling alone.

Scenario review is also an **integration-balance** check. Individually meaningful Situations and individually healthy Loops can combine into a dominant response, excessive deadline pressure, bad resource competition, unreadable delayed costs or exhausting overlap. Do not assume that balancing each Situation independently is enough.

## 13. Causal Legibility Review

Scenario chronology is a strong place to check whether the player can connect earlier choices to later outcomes.

Ask:

```text
Why does the player think this Situation arose?
Can they connect it to past state / choices?
Can they distinguish direct from delayed state-mediated effects?
Is cause distinguishable from correlation strongly enough to learn?
Can they predict direction without exact hidden numbers?
Do they recognize a recurring Situation chain / Loop?
Can they prepare before the next occurrence?
Can they deliberately plan a desired future state?
After failure, can they revise a model instead of random trial?
```

## 14. Player Experience / Anti-Experience Review

Use [`Player Experience And Anti-Experience`](../player-experience-and-anti-experience.md) for the cumulative arc.

Inspect:

```text
entry experience;
changes of attention / desire / confidence;
tension and release;
anticipation and payoff;
ownership of plans;
loss / recovery;
curiosity and understanding;
mastery;
anti-experience accumulation;
residual experience at the end.
```

A Scenario should not be reduced to a graph of mechanics if the purpose is to validate the player's temporal experience.

## 15. Visual Planning Review

Use [`Visual Design Analysis And Planning`](../visual-design-analysis-and-planning.md) for the concrete chronology.

A Scenario Beat can own exact local requirements such as:

```text
what must be perceived here;
what should remain uncertain;
what visual hierarchy is required;
what wrong interpretation must be avoided;
how a reference is responsible for this moment;
what representative check validates the result.
```

Project-wide/cross-scenario visual requirements may remain in a separate project visual owner rather than being copied into every Beat.

Scenario owns the required result and local context, not every possible realization study. If one Beat later needs an independently reviewable deep-dive into gameplay realization, visual realization, audio, UI or another production problem, split that study only when its lifecycle justifies a separate owner and keep the link back to the Scenario requirement.

## 16. Demo Scenario

A full demo Scenario should include the **entire temporal experience**, not only dramatic incidents.

Plan routine/orientation/planning/waiting/recovery as deliberately as crises when they matter to the promise.

Exact timings remain candidate/open until supported by implementation or evidence.

A detailed demo branch can be selected for implementation/testing while mechanics, screens and alternative playthroughs remain unresolved.

## 17. AI Scenario Exploration

For a systemic game, literal enumeration of every possible Scenario is normally impossible.

AI can instead use:

```text
Situation Types
+ Loops
+ relevant state
+ tight dependencies
```

to explore many plausible paths, cluster equivalent variants and identify representative cases.

Useful targets include:

```text
frequent;
fundamental;
interesting;
risky;
cross-system;
balance-sensitive;
dominant-solution;
failure / recovery;
anti-experience;
edge-case;
boring / rote;
production-expensive;
mechanic-conflict;
causally unreadable.
```

Useful adversarial searches:

```text
Find a Situation with formally multiple options but only one viable answer.
Find a failure whose cause the player cannot read.
Find individually good mechanics that create bad pacing together.
Find a recurring chain that becomes rote.
Find a state-mediated Loop that the player cannot infer.
Find a Scenario where several Loops overlap and create a pacing/load problem that is invisible when each Loop is reviewed alone.
Find two simultaneously Active Situations where resolving A first materially changes B, and compare the reverse order.
Find representative cases with one versus several simultaneous Active Situations so the designer can judge whether the overlap creates useful prioritization or only noise.
```

Do not describe AI exploration as exhaustive coverage of a combinatorial system.

## 18. Do Not

- Do not make every Beat a Gameplay Situation.
- Do not require one chronological track when several Loops are genuinely simultaneous.
- Do not treat Active Situation / Loop counts as automatic quality scores.
- Do not duplicate all generic Situation rules in every instance.
- Do not silently invent exact timing, final mechanics or the only valid playthrough.
- Do not make a detailed demo equal to a frozen screenplay merely because it is concrete enough to test.
