# Gameplay Loop Planning

Status: active reusable detailed-planning method
Scope: how to identify, describe and review recurrent causal gameplay processes without collapsing the whole simulation into one Loop.

Canonical Loop terminology is owned by [`Gameplay Situations, Loops And Scenarios — Principles And Terminology`](../../principles/gameplay-situations-loops-and-scenarios-principles-and-terminology.md). Canonical Dynamic terminology is owned by [`Mechanics Create Dynamics`](../../principles/mechanics-create-dynamics-principles-and-terminology.md).

## 1. Purpose

Use Loop planning when repeated gameplay is better explained as a recurrent causal process than as a generic action list.

A Loop can contain:

```text
Gameplay Situations;
Gameplay Events as supporting triggers/feedback/payoffs when material;
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

may be useful as a broad Core Loop view, but it should not be the sole evidence for concrete Gameplay Loops.

Look for **frequently recurring functionally coherent causal structures** across Situation Types and state transitions.

Example shape:

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

## 5. Causal Basis / Loop-Sustaining Mechanics And Rules

A Loop record should make visible **why the process recurs**, not only which nodes appear in it.

Record proportionally the mechanics/rules/state relations that create or sustain:

```text
transitions between important states / Situations;
recurrence / re-entry conditions;
state carryover between cycles;
feedback;
recovery / reset / restart;
escalation or decay;
progression changes to the Loop;
conditions that stop or radically alter the Loop.
```

Useful shape:

```text
Rule / State Relation
→ transition / execution
→ state carried forward
→ later Situation or phase becomes possible
→ feedback / recovery
→ recurrence.
```

Do not duplicate every member Situation's local rules. Link or summarize only the causal relations needed to understand the Loop as one recurrent process.

Ask:

```text
Which rule makes the next step likely/possible?
Which state is carried between cycles?
Why does the same functional problem return?
What stops recurrence?
What creates feedback?
What allows recovery / restart?
How does progression alter these relations?
```

This is the Loop-scale version of `Causal Basis`. It does not replace the Dynamic Causal Basis, which asks why a broader systemic tendency develops.

## 6. Loop Phase

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

## 7. Parallel / Overlapping Loops

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

## 8. Interactions Between Loops

Record interactions only when useful.

Possible descriptions include:

```text
shared Situation;
specific triggering relation;
tight dependency;
competition for labor / time / attention / capacity;
reinforcement;
suppression;
state coupling;
parallel execution;
one Loop modifying another Loop's Causal Basis.
```

These are analysis labels, not a mandatory closed taxonomy.

A broad state effect can connect distant systems without making them one Loop.

## 9. Decision-Order Effects

If two Situations from different or overlapping Loops are simultaneously active, the order of resolving them may itself be meaningful.

```text
A first → B's options / risk changes
B first → A's options / risk changes.
```

Record this where it is a specific recurring interaction. Scenario planning is usually the best place to inspect the concrete pacing/challenge effect.

## 10. Dynamics Produced By Loop Recurrence

A Gameplay Loop and a Gameplay Dynamic are related but not identical:

```text
Loop
  → recurrent functionally coherent causal process;

Dynamic
  → recurrent / persistent / directionally developing tendency
     in what one or more operative processes make the game become.
```

A Loop may produce several Dynamics through different accumulated consequences. A Dynamic may also emerge across several distinct Loops through shared state, incentives or capacity.

For each important Loop, ask proportionally:

```text
Which current / hypothesized Dynamics may this recurrence contribute to?
Which desired or unwanted systemic tendencies are plausible?
Which consequences accumulate across cycles?
Does recurrence reinforce, stabilize, redirect or reverse a broader tendency?
Does interaction with another Loop create a Dynamic neither Loop produces alone?
Do produced Dynamics change which strategies become advantageous later?
```

Dynamics are outputs/tendencies of recurrence, not member nodes or Loop Phases.

## 11. Loop Timing And Pacing Questions

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

## 12. Causal Legibility And Strategic Learning

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

## 13. Player Experience / Anti-Experience

Use [`Player Experience And Anti-Experience`](../player-experience-and-anti-experience.md) at the repetition scale.

Ask:

```text
What Experience does repeated participation create?
Does repeated correction produce competence / mastery?
Does planning create agency / ownership?
Does uncertainty remain valuable?
Does the Loop become rote?
Does delayed feedback become helplessness?
Does overlap with other Loops create tension or exhausting noise?
Which loop-sustaining rules are directly responsible for these effects?
```

## 14. Game Structure Review

Use [`Game Structure Analysis`](../game-structure-analysis.md) as a full discovery pass.

Loop planning often especially benefits from:

```text
Player Verbs And Decisions;
Rules / Resources / Economy;
Challenge / Failure / Progression;
Balance, Decision Space And Strategic Diversity;
Dynamics And State / Opportunity Trajectory;
Time / Attention / Information;
World / AI / System Response;
Content Structure / Pacing;
Causal Legibility And Strategic Planning;
Content-Production Model.
```

Do not assume the other concerns are irrelevant; inspect proportionally.

## 15. Visual Planning Review

Use [`Visual Design Analysis And Planning`](../visual-design-analysis-and-planning.md) when recurring Loop states/phases have important visual communication or Experience requirements.

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

## 16. Loop-Level Balance

Loop balance is not only the sum of balanced individual Situations. Use the shared [`Game Structure Analysis`](../game-structure-analysis.md) balance taxonomy.

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
simultaneous Loop demands;
produced Dynamic / dominant-meta risk;
whether loop-sustaining rules make one response
  increasingly mandatory over repeated cycles.
```

A choice can be locally reasonable but become dominant/exhausting because the Loop repeats it too often.

## 17. Core / Session / Long-Term Views

`Core Loop`, `Session Loop` and `Long-Term Loop` remain useful scale-oriented planning concepts.

They do not imply:

```text
exactly one Loop of each type;
that every recurring process belongs to one of three boxes;
that one high-level Core Loop diagram replaces concrete Situation-derived Loops.
```

A broad repeated decision/adaptation pattern may be useful inside a Concept as a design thesis without being one concrete Gameplay Loop.

## 18. Suggested Loop Record

```text
Loop ID / Name
Status / Source

Function / Player Value
Member Situation Types
Relevant Gameplay Events, if material
Relevant Loop Phases, if useful

Causal Basis / Loop-Sustaining Mechanics And Rules
  Transition-Creating Rules / State Relations
  Recurrence / Re-entry Conditions
  State Carryover
  Feedback
  Recovery / Reset / Restart
  Escalation / Decay
  Progression Effects
  Exit / Stop Conditions

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

Linked Current Dynamics, if any
Dynamic Hypotheses / Desired Or Unwanted Tendencies, if material
Cross-Loop Dynamic Contributions, if material

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

## 19. Event And Integration Boundary

A Gameplay Event may participate as a trigger, feedback, payoff or pressure occurrence when it contributes to the recurrent process.

Preserve:

```text
Event → Event → Event
without load-bearing player agency
≠ Gameplay Loop automatically.
```

When a local Idea Variant needs whole-Loop integration, use a real candidate Loop Variant and normal Loop planning/evaluation rather than creating a separate `PROBE-LOOP` artifact family. Candidate coherence does not imply acceptance.

Current broad Core/Session/Long-Term views remain useful, but this method does not settle the separate open question of which existing project records are true Gameplay Loops versus Player Strategies or broad/session activity structures.

## 20. Do Not

- Do not infer Loop membership from shared state alone.
- Do not require contiguous Situation nodes.
- Do not merge overlapping Loops automatically.
- Do not equate a Loop with the Dynamics its recurrence may produce.
- Do not merge distinct Loops merely because they contribute to the same Dynamic.
- Do not call every one-off causal sequence a Loop.
- Do not call a decisionless Event chain a Gameplay Loop merely because it recurs.
- Do not assume current Loop records are automatically the canonical session/balance horizon.
- Do not duplicate every local Situation mechanic in the Loop Causal Basis.
- Do not balance repeated processes only by balancing each local decision independently.
- Do not assume the generic `observe → decide → act → consequence` pattern is the only concrete Loop in a game.
- Do not treat a broad Concept Core Loop as proof of concrete Loop membership.
