# Gameplay Scenario Planning

Status: active reusable detailed-planning method
Scope: how to plan, inspect and validate one concrete chronological traversal through Gameplay Situations and Loops, including non-decision time, concurrent processes, operative rule manifestations and concrete manifestations of candidate Dynamics.

Canonical Scenario terminology is owned by [`Gameplay Situations, Loops And Scenarios — Principles And Terminology`](../../principles/gameplay-situations-loops-and-scenarios-principles-and-terminology.md). Canonical Dynamic terminology is owned by [`Mechanics Create Dynamics`](../../principles/mechanics-create-dynamics-principles-and-terminology.md).

## 1. Purpose

A `Scenario` turns reusable gameplay structure into one concrete chronology detailed enough to plan, implement or test.

It is especially useful when the important question is not one isolated decision but:

```text
what happens before and after it;
which previous decisions are still executing;
which other Situations become active;
which Loops overlap;
which rules manifest materially in this concrete path;
how pressure rises/falls;
which candidate Dynamics become visible;
how viable strategic space changes from entry to exit;
what the player understands and experiences over time.
```

A selected branch is a planning/test path, not a claim that every playthrough follows it.

## 2. Scenario Is More Than Situation Nodes

A concrete Scenario may include:

```text
orientation;
independently useful Gameplay Events;
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

A decisionless but important Experience moment can remain a Scenario Beat, Observation, Execution, Consequence, Recovery or Visual Context. Do not broaden `Gameplay Situation` merely to give that moment a planning owner.

## 3. Top-Level Scenario Record

A Scenario needs a compact owner-level record in addition to detailed Beats when independent review/testing is useful.

Use proportionally:

```text
Scenario ID / Name
Purpose / Question Being Tested
Source / Status
Target Game Version / Scope
Document Revision, when independently useful

Entry Conditions
Starting State
Initial Knowledge
Assumed Player Context, when material
Relevant Units / Configurations

Chronology / Beats

Dynamic Hypotheses Being Tested
Integration Questions

Exit State
What Changed
Evidence / Findings
```

This record owns the concrete chronology/test responsibility; it does not duplicate generic rules already owned by Situation / Loop / Dynamic / Game Domain owners.

`Target Game Version / Scope` states which coherent game configuration the chronology assumes. By default a project Scenario belongs to the project's current target game version; write the field explicitly when version/scope ambiguity is material. `Document Revision` only tracks revision of the Scenario document and must not be used as a substitute for the game version being planned.

If a useful finding belongs to another or still-undefined future game version, mark that departure instead of silently mixing incompatible assumptions into the current chronology. Prefer a separate Scenario pass when the future version needs its own coherent chronology. This narrow Scenario field does not establish a generic `Planning Unit Version` ontology or resolve broader `Game Version / Game Variant` terminology.

## 4. Situation Instance

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

## 5. Scenario Beat

A `Scenario Beat` is a chronological portion of the Scenario.

Useful roles include:

```text
Situation Instance;
Gameplay Event occurrence / reference;
System Execution;
Observation / Information Reveal;
Routine / Waiting;
Transition;
Consequence / Payoff;
Recovery.
```

The list is not mandatory or closed.

One Beat may contain several simultaneous facts when they form one causal-temporal moment:

```text
decision in Situation A
+
active Situation B changes because of it
+
execution from Loop C continues
+
new information becomes visible.
```

One Loop Phase may span several Beats. Conversely, one Beat may contribute to/change phases in several Loops.

A project may also use a `Scenario Phase` or similarly named section as a readable chronological grouping of several Beats. That label is presentation/chronology inside one Scenario, not a new gameplay scale and not evidence that the grouped material is a Gameplay Loop. A recurrent Loop may cross several Scenario sections, and one Scenario section may contain manifestations of several Loops.

## 6. Scenario Beat Record

Use proportionally:

```text
Beat ID / Title
Temporal Marker
Beat Role

Situation Type Reference, if any
Gameplay Event Reference, if any
Loop / Loop Phase Mapping, if useful

Relevant State Before
What Happens / Causal Work Inside

Player Goals / Stakes / Expectations / Plan, as relevant
Developer Purpose
Intended Player Response

Information Available
Required Understanding
What Should Remain Unknown
Player Model / Expertise Change, if material

Project Experience / Motivation, if material
Experience Promise / Doubt, if material

Meaningful Decisions, if this is a Situation Instance
Decision Availability
Why Each Option May Be Attractive
Selected Scenario Branch
Why This Player Context Selected It
Similarly Plausible Alternative, only when genuinely useful
Why A Visible Opportunity Was Not Taken, if material
  not perceived / not understood / not salient / deferred / attention-crowded

Operative Mechanics / Rules, if needed
  only rules whose concrete manifestation is
  needed to understand this Beat/path

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

Foreground Focus / Background Monitoring, if material
Attention Competition / Missable Signals, if material
Pacing / Load Note, if material

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
Relevant State After / Handoff
```

Not every Beat needs every field.

For a sufficiently detailed Beat/Step, preserve the causal continuity proportionally:

```text
relevant state BEFORE
→ concrete occurrence / decision / execution / causality INSIDE
→ relevant state AFTER / HANDOFF.
```

Possible state dimensions include World/Domain state, Economy/Capacity, Information, ongoing Execution, Situation state and player-side state. Do not copy the complete game state into every Beat. Record only what is needed to understand why the Beat unfolds as written and why the next chronological condition follows.

## 6A. Spine Scenario Planning Role

A `Spine Scenario` is a normal concrete Scenario deliberately used as the temporal/integration spine of a planning pass.

```text
Spine → concrete chronology / selected branch / temporal changes
  ↕
low-level owners → reusable alternatives / variants / prerequisites / full local design.
```

Rules: one selected chronology; not necessarily short; not a claim about all playthroughs; selected decisions preserve why this Player Context chose them; if several choices are similarly plausible, note them when useful but select one branch; preserve as much concrete selected-branch detail as useful; local owners expand reusable alternative-space.

For a first-play Spine, First Contact / pre-play material may establish expectations and feed a gameplay-entry state without automatically becoming Gameplay Phase 0. Keep the handoff explicit and state where gameplay chronology begins.

Preferred representation:

```text
A. readable Timeline / chronology;
B. expandable Beat / Step / Interval detail where useful.
```

Temporal-change tracks may include World/Domain State, Economy/Capacity, Information, Player Model/Expertise, Experience, Motivation/Doubt, Active Situation changes and Execution progress. These are chronology facts, not automatically new unit types.

Optional qualitative reachability/salience labels: `Mandatory`, `path-inevitable`, `Conditional`, `Player-initiated/optional`, `Discoverability-dependent`, `Attention-dependent`. One Scenario does not establish numeric probability.

## 7. Operative Mechanics / Rules Boundary

Scenario owns **concrete manifestation**, not every generic rule.

Use `Operative Mechanics / Rules` only when the reader needs to know why this exact chronology behaves as described.

Example:

```text
generic Situation rule:
  weak barriers can fail after sustained pressure;

Scenario manifestation:
  this damaged door is expected to hold only long enough
  for the selected evacuation branch.
```

The generic rule belongs in the Situation/system owner. The Scenario records its concrete use.

If Scenario work discovers a general mechanic/rule relation missing from the Situation/Loop/Dynamic owner, treat that as an audit signal and update the more general owner after review.

## 8. Intended Player Response Is Broader Than Emotion

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

## 9. Presentation Is Broader Than Visuals

Scenario presentation requirements can include:

```text
visual;
audio;
UI / information presentation;
timing / pacing;
agent/world behavior;
control feedback.
```

Do not ask the visual layer alone to produce an Experience whose cause belongs to pacing, audio, information or system behavior.

## 10. Concurrent Situations And Loops

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

These values are not automatic scores.

> The number of simultaneously active Situations and Loops can be used as one indicator of gameplay load, pacing and challenge. The number itself does not prove that there is too much or too little load; interpret it in the concrete Scenario.

Example:

```text
00:00  Situations 0 / Loops 1
04:00  Situations 1 / Loops 2
11:00  Situations 3 / Loops 3
15:00  Situations 1 / Loops 2
```

## 11. Parallel Loop Tracks

When it helps, represent Scenario chronology as parallel tracks:

```text
Time →

Production Loop   ───── execution ───── Situation ───
Disease Loop             Situation ─── execution ────
Raid Loop        Situation / preparation ────────────

Active Situations        1      2       3      1
Active Loops             1      2       3      2
Player decisions         ↓      ↓              ↓
```

A Scenario may cross several Loops that interact only through shared state. Showing them in one chronology does not merge them into one Loop.

## 12. Tight Dependencies In Scenario

It is acceptable to repeat a tight dependency already owned by Situation planning if doing so makes the concrete Scenario understandable.

```text
Situation owner:
  dependency exists generally;

Scenario:
  resolving A first here removes option B2,
  changing the concrete pacing/challenge problem.
```

If the Scenario reveals a general specific dependency missing from the Situation Type, audit/update the Situation owner.

Broad economy/state effects still do not need exhaustive Situation-to-Situation links.

## 13. Game Structure Review

A Scenario can use the full [`Game Structure Analysis`](../game-structure-analysis.md) concern set.

For a detailed gameplay Scenario, normally explicitly inspect at least:

```text
Core / Session / Long-Term Loops;
Player Verbs And Decisions;
Goals, Motivation And Direction;
Rules, Resources And Economy;
Challenge, Failure And Progression;
Balance, Decision Space And Strategic Diversity;
Dynamics And State / Opportunity Trajectory;
Time, Attention And Information;
Content Structure And Pacing;
Concurrency, Loop Overlap And Decision Load;
World, AI And System Response;
Causal Legibility And Strategic Planning;
Interface, Feedback And Readability.
```

`Explicit review` means look deliberately; `nothing material found` is acceptable.

For a full-demo / first-play Scenario, also explicitly inspect:

```text
Onboarding And Mental Model;
Return, Stopping And Exhaustion.
```

Use `Content-Production Model` when the Scenario is also estimating content/production burden.

## 14. Pacing / Challenge Review

Scenario scale is where concurrency, timing and cumulative pressure become visible.

Ask:

```text
How dense are meaningful Situations?
How do Active Situation / Loop counts rise and fall?
Where are peaks and breathing room?
How many previous decisions are still executing?
How many decisions are time-sensitive?
How long have important unresolved decisions remained open?
How quickly is new decision-relevant information arriving?
How many interruptions compete for attention?
How long is decision → feedback delay?
Do several individually good Loops create bad pacing together?
Does overlap create meaningful prioritization or only noise?
Does the player have time to understand consequences before the next demand?
Does repetition become rote?
```

Scenario review is also an integration-balance check. Individually meaningful Situations/Loops can combine into dominant response, deadline pressure, unreadable delayed costs or exhausting overlap.

## 15. Causal Legibility Review

Scenario chronology is a strong place to check whether the player can connect earlier choices to later outcomes.

Ask:

```text
Why does the player think this Situation arose?
Can they connect it to past state / choices?
Can they distinguish direct from delayed state-mediated effects?
Can they infer which operative rule caused the result?
Is cause distinguishable from correlation strongly enough to learn?
Can they predict direction without exact hidden numbers?
Do they recognize a recurring Situation chain / Loop?
Can they distinguish one-off consequence from developing Dynamic?
Can they prepare before the next occurrence?
Can they deliberately plan a desired future state?
Can they strengthen, counter or redirect a relevant Dynamic?
After failure, can they revise a model instead of random trial?
```

## 16. Dynamic Manifestation And Strategic-Space Review

Scenario chronology can inspect manifestations of current or hypothesized Dynamics without pretending one branch proves a stable pattern.

Record proportionally:

```text
Dynamic Manifestations / Candidate Tendencies
Evidence / Counter-Evidence For The Dynamic

Strategic Space At Entry
  which goals / approaches / strategies are viable?

Strategic Space At Exit
  which became more / less viable and why?
```

Ask:

```text
Which linked/candidate Dynamics appear to manifest?
Which decisions/consequences contribute?
Does the path expose an unwanted Dynamic?
What opportunities/strategies exist at entry?
What exists at exit?
Did a viable strategy become weak/unavailable?
Did a new strategy become viable because state changed?
Does one strategy look correct only because of this branch,
or do rules/balance favor it broadly?
What alternative Scenario could falsify that interpretation?
```

One Scenario manifestation is not proof of a stable Dynamic.

## 17. Player Experience / Anti-Experience Review

Use [`Player Experience And Anti-Experience`](../player-experience-and-anti-experience.md) for the cumulative arc and [`Player Experience / Motivation Planning`](../player-experience-motivation-planning.md) when Project Experience/Motivation/Promise/Doubt changes need independent links.

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

A Scenario should not be reduced to a graph of mechanics if the purpose is to validate temporal Experience.

## 18. Visual Planning Review

Use [`Visual Design Analysis And Planning`](../visual-design-analysis-and-planning.md) for concrete chronology.

A Scenario Beat can own exact local requirements such as:

```text
what must be perceived here;
what should remain uncertain;
what visual hierarchy is required;
what wrong interpretation must be avoided;
how a reference is responsible for this moment;
what representative check validates the result.
```

Project-wide/cross-scenario visual requirements may remain in a separate project visual owner.

## 19. Content Premise Handoff

A project-local `Content Premise` may exist before a detailed Scenario.

Useful route:

```text
Idea
→ Content Premise
  concrete enough to preserve independently
  but chronology still unresolved
→ Scenario planning when detailed integration is useful.
```

A premise may depend on unresolved generic mechanics. The Scenario should not silently decide those mechanics merely to fill Beats.

## 20. Demo Scenario

A full demo Scenario should include the **entire temporal Experience**, not only dramatic incidents.

Plan routine/orientation/planning/waiting/recovery as deliberately as crises when they matter to the promise.

Exact timings remain candidate/open until supported by implementation/evidence.

A detailed demo branch can be selected for implementation/testing while mechanics, screens and alternative playthroughs remain unresolved.

## 21. Event And Integration Boundary

A one-off decisionless chronology detail remains a Scenario Beat. Reference a reusable Gameplay Event when the occurrence has independent planning responsibility outside this chronology.

When an Idea Variant needs chronology-level integration, use a real candidate Scenario Variant and this normal Scenario method instead of a separate `PROBE-SCN` artifact family.

A coherent candidate Scenario Variant:

```text
≠ accepted project Scenario;
≠ accepted generic mechanic;
≠ evidence that the Variant works.
```

Use Integrated Evaluation to decide what, if anything, is later accepted/promoted.

## 22. AI Scenario Exploration

For a systemic game, literal enumeration of every possible Scenario is normally impossible.

AI can use:

```text
Situation Types
+ Loops
+ relevant state
+ tight dependencies
+ operative rules
+ expected / candidate Dynamics, when useful
```

to explore plausible paths, cluster equivalent variants and identify representative cases.

Useful targets include:

```text
frequent;
fundamental;
interesting;
risky;
cross-system;
balance-sensitive;
dominant-solution;
dominant-meta / strategic-convergence;
Dynamic manifestation / counter-example;
failure / recovery;
anti-experience;
edge-case;
boring / rote;
production-expensive;
mechanic-conflict;
causally unreadable.
```


Useful adversarial searches include:

```text
Find a Situation with formally multiple options but only one viable answer.
Find a failure whose cause the player cannot read.
Find individually good mechanics that create bad pacing together.
Find a recurring chain that becomes rote.
Find a state-mediated Loop that the player cannot infer.
Find a Scenario where several locally different systems converge toward one dominant strategy.
Find a Scenario that appears to manifest an expected Dynamic, then find a counter-Scenario that could falsify it.
Find a Scenario where several Loops overlap and create a pacing/load problem that is invisible when each Loop is reviewed alone.
Find two simultaneously Active Situations where resolving A first materially changes B, and compare the reverse order.
Find representative cases with one versus several simultaneous Active Situations so the designer can judge whether the overlap creates useful prioritization or only noise.
```

These are search prompts, not a claim that AI-generated cases are evidence by themselves.

Do not describe AI exploration as exhaustive coverage of a combinatorial system.

## 23. Do Not

- Do not make every Beat a Gameplay Situation.
- Do not broaden Situation to decisionless Experience moments merely for planning convenience.
- Do not require one chronological track when several Loops are simultaneous.
- Do not treat Active Situation/Loop counts as automatic quality scores.
- Do not duplicate all generic Situation/Loop rules in every instance.
- Do not use `Operative Mechanics / Rules` as a second generic mechanics owner.
- Do not treat one Scenario manifestation as proof of a stable Dynamic.
- Do not silently invent exact timing, final mechanics or the only valid playthrough.
- Do not make a detailed demo equal to a frozen screenplay merely because it is concrete enough to test.
- Do not promote a coherent candidate Scenario Variant into accepted project meaning without explicit review.
