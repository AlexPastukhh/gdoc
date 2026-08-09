# Gameplay Loop Planning

Status: active reusable detailed-planning method
Scope: how to identify, describe and review recurrent causal gameplay processes without collapsing the whole simulation into one Loop.

Canonical Loop terminology is owned by [`Gameplay Situations, Loops And Scenarios — Principles And Terminology`](../../principles/gameplay-situations-loops-and-scenarios-principles-and-terminology.md).

## 1. Purpose

Use Loop planning when repeated gameplay is better explained as a recurrent causal process than as a generic action list.

A Loop can contain:

```text
Gameplay Situations;
player decisions;
system execution;
state accumulation / change;
feedback;
recovery / adaptation;
later Situations.
```

Its Situations need not be adjacent in time.

## 2. Derive Loops From Recurrent Causality

A generic thesis such as:

```text
observe → decide → act → consequence
```

may be useful, but it should not be the sole evidence for concrete game Loops.

Look for **frequently recurring functional causal structures** across Situation Types and state transitions.

A simple example can look like:

```text
Situation A
→ decision
→ execution
→ changed state
→ Situation B
→ decision
→ recovery / new state
→ conditions recur.
```

The path may contain other gameplay and other Loops between A and B.

## 3. Loop Membership

Do not use shared state alone as membership.

```text
shared state
≠ same Loop;

same time period
≠ same Loop;

one shared Situation
≠ automatic Loop merge.
```

A useful Loop normally has:

```text
recurrence / frequency;
functional coherence;
a typical causal mechanism that connects its parts;
player-learnable or at least analyzable causal continuity;
value in reviewing its decisions together for
  pacing / economy / strategy / mastery / balance.
```

Avoid `the whole simulation is one giant Loop` unless that scale genuinely answers a real question.

Illustrative example only:

```text
failed raid
→ worker dies
→ population -1

later:
  manpower shortage affects another decision.
```

The later decision is **not automatically a direct node of the raid Loop** merely because the raid changed a shared population state. Membership still needs recurrent functional/causal coherence.

## 4. Direct And State-Mediated Relations

A Loop may use both:

```text
Direct Situation Transition
  → local decision/result creates the next Situation;

State-Mediated Transition
  → decision changes state;
     execution/time/other gameplay occurs;
     changed state recurrently creates a later Situation.
```

A general downstream effect is not automatically part of the Loop.

Explicit relations should remain selective enough that the Loop is understandable.

## 5. Loop Phase

Use `Loop Phase` only when naming functional portions clarifies the process.

Example only:

```text
pressure becomes salient
→ decision / commitment
→ execution
→ accumulation / system response
→ consequence becomes legible
→ adaptation.
```

Do not impose this phase list on every Loop.

## 6. Parallel / Overlapping Loops

Loops can progress simultaneously.

```text
Loop A
  → execution in progress

Loop B
  → active decision

Loop C
  → pressure accumulating
```

The player may resolve B while A is still physically executing.

One Situation Instance may participate in more than one Loop when one decision genuinely serves several recurrent causal processes.

That does not merge the Loops if their broader functional cycles remain distinct.

## 7. Interactions Between Loops

Record interactions only when they are useful.

Possible descriptions include:

```text
shared Situation;
specific triggering relation;
tight dependency;
competition for labor / time / attention / capacity;
reinforcement;
suppression;
state coupling;
parallel execution.
```

These are analysis labels, not a mandatory closed taxonomy.

A broad state effect can connect distant systems without making them one Loop.

## 8. Decision-Order Effects

If two Situations from different or overlapping Loops are simultaneously active, the order of resolving them may itself be meaningful.

```text
A first → B's options / risk changes
B first → A's options / risk changes.
```

Record this where it is a specific recurring interaction. Scenario planning is usually the best place to inspect the concrete pacing/challenge effect.

## 9. Loop Timing And Pacing Questions

For each important Loop, ask proportionally:

```text
How often does it recur?
How long does one cycle or meaningful portion take?
Where are the meaningful decisions?
How much execution occurs between decisions?
How delayed is feedback?
Can other Situations / Loops intervene during the delay?
Does the same decision repeat too often?
Can the player understand the relation between early decision and later result?
How does progression change the Loop?
What happens when this Loop overlaps with other Loops?
How much attention does each phase require?
Does repetition create strategy/mastery or monotony?
```

Pacing in a systemic game may emerge from several Loops being in different phases at the same time rather than from scripted event timing alone.

## 10. Causal Legibility And Strategic Learning

A Loop can support mastery when the player learns:

```text
what typically causes the next Situation;
which state changes matter;
what feedback reveals success/failure;
what can be prepared in advance;
how to alter the future cycle intentionally.
```

A delayed state-mediated Loop is weak if its central relation is effectively impossible for the player to infer.

Useful adversarial question:

> Is the Loop mechanically valid but causally unreadable, so the player experiences its later consequences as randomness?

## 11. Player Experience / Anti-Experience

Use [`Player Experience And Anti-Experience`](../player-experience-and-anti-experience.md) at the **repetition** scale.

Ask:

```text
What experience does repeated participation create?
Does repeated correction produce competence / mastery?
Does planning create agency / ownership?
Does uncertainty remain valuable?
Does the Loop become rote?
Does delayed feedback become helplessness?
Does overlap with other Loops create tension or exhausting noise?
```

## 12. Game Structure Review

Use [`Game Structure Analysis`](../game-structure-analysis.md) as a full discovery pass.

Loop planning often especially benefits from:

```text
Player Verbs And Decisions;
Rules / Resources / Economy;
Challenge / Failure / Progression;
Time / Attention / Information;
World / AI / System Response;
Content Structure / Pacing;
Causal Legibility And Strategic Planning;
Content-Production Model.
```

Do not assume the other concerns are irrelevant; inspect proportionally.

## 13. Visual Planning Review

Use [`Visual Design Analysis And Planning`](../visual-design-analysis-and-planning.md) when recurring Loop states/phases have important visual communication or experience requirements.

A Loop may need visual continuity across:

```text
normal state;
pressure becoming legible;
decision / planning;
execution;
consequence;
recovery.
```

Do not force every Loop phase to become a separate `Visual Context` if the distinction has no visual planning value.

## 14. Loop-Level Balance

Loop balance is not only the sum of balanced individual Situations.

Review:

```text
frequency;
cycle duration;
decision density;
feedback delay;
intervening Situations;
repetition / dominant response risk;
state accumulation;
recovery cost;
progression effects;
simultaneous Loop demands.
```

A choice can be locally reasonable but become dominant or exhausting because the Loop repeats it too often.

## 15. Core / Session / Long-Term Views

`Core Loop`, `Session Loop` and `Long-Term Loop` remain useful scale-oriented planning concepts.

They do **not** imply:

```text
exactly one Loop of each type;
that every recurring process belongs to one of three boxes;
that one high-level Core Loop diagram replaces concrete Situation-derived Loops.
```

A broad repeated decision/adaptation pattern may also be useful as a design thesis without being one concrete Gameplay Loop.

## 16. Suggested Loop Record

```text
Loop ID / Name
Status / Source

Function / Player Value
Member Situation Types
Relevant Loop Phases, if useful

Transition Map
  Direct
  Important State-Mediated

Important Shared State
Why These Parts Form One Loop

Expected Recurrence / Frequency
Duration / Cycle Timing
Decision Placement
Execution Between Decisions
Feedback Delay
Intervening Gameplay

Interactions With Other Loops
Decision-Order Effects, if recurrent

Player Causal Understanding
Strategic Learning / Adaptation
Progression Effects

Game Structure Review
Player Experience / Anti-Experience Review
Visual Planning Review

Pacing Concerns
Balance Concerns
Content-Production Implications
Scenario Coverage
Evidence / Questions
```

## 17. Do Not

- Do not infer Loop membership from shared state alone.
- Do not require contiguous Situation nodes.
- Do not merge overlapping Loops automatically.
- Do not call every one-off causal sequence a Loop.
- Do not balance repeated processes only by balancing each local decision independently.
- Do not assume the generic `observe → decide → act → consequence` pattern is the only concrete Loop in a game.
