# Reference First And Controlled Transformation — Principles And Terminology

Status: active reusable principle-and-terminology owner
Research basis: [`../research/anatomy-of-a-game-reference.md`](../research/anatomy-of-a-game-reference.md)

## 1. Purpose And Authority

This file owns:

- Reference First;
- functional reference analysis;
- reference types;
- dominant and secondary references;
- reference responsibility;
- Controlled Transformation;
- combining several references;
- transformation-target principles;
- reference-transfer and compatibility principles;
- the reference/feasibility boundary used when choosing an initial game direction.

It does not own:

- the complete zero-to-one creative route — use [`Game Creation Workflow`](../game-creation-workflow.md);
- the full Player Experience taxonomy;
- detailed brainstorm techniques;
- platform algorithms;
- exact prototype execution.

## 2. Reference First

For every significant, expensive or risky design choice, use one of:

```text
a reference baseline;
a checked reusable pattern;
an explicitly marked hypothesis of novelty.
```

The rule is not meant to block small creative choices. It prevents expensive design from being built in a vacuum when relevant working solutions already exist.

When choosing a game direction from scratch, prefer a seed that can be tied to:

```text
a reference that demonstrates relevant value
+
a feasible way to reproduce enough depth/visual quality
to test that value in a representative demo.
```

Reference evidence does not prove the whole transformed game will work. It gives a causal/production anchor for part of the search.

## 3. Reference

A `Reference` is an inspectable source used to understand or transfer a particular design, experience, production or market function.

A reference is not necessarily a whole game.

### Reference Types

| Type | Responsibility |
|---|---|
| Whole game | Baseline promise, structure and tone |
| Subsystem | A large independently analyzable system |
| Mechanic | A rule, action or constraint |
| UX flow | A sequence of perception, choice and feedback |
| Economy | Resources, conversions, scarcity, costs and rewards |
| Session structure | The shape and escalation of one run, day or mission |
| Visual language | How state, role, genre and affordance are visually communicated |
| Market positioning | Comparison frame, tags, anchor, hook and store promise |
| Non-game reference | Film, physical activity, architecture, work process or another relevant real-world source |

Name the smallest reference type that owns the current design question.

## 4. Reference Responsibility

A reference should have a named responsibility:

```text
Reference:
Responsibility:
Value / cause being studied:
What may be transferred:
What must not be assumed:
```

Example shape:

```text
Reference A
  → responsibility: sparse-information tension;

Reference B
  → responsibility: individual-character social simulation.
```

A reference is not permission to copy every feature, visual surface or content layer around the useful responsibility.

## 5. Analyze Function, Not Surface

A reusable reference record should explain:

```text
what works;
why it works;
for which player;
which systems support it;
which conditions are required;
which trade-offs it creates;
what is transferable;
what must not be assumed transferable.
```

Aesthetic similarity, genre label or feature presence is insufficient.

## 6. Minimal Game Reference Map

A reusable whole-game or large-subsystem analysis should normally cover:

1. Player promise and audience.
2. Core loop and session loop.
3. Player verbs and decisions.
4. Rules, resources and economy.
5. Challenge, failure and progression.
6. Interface, feedback and readability.
7. Content structure and pacing.
8. Market position and comparables.

Use optional lenses only for a real question:

- space and traversal;
- time structure;
- narrative causality;
- social structure;
- meta-progression and retention;
- economy depth;
- onboarding;
- content-production burden;
- store communication;
- modifiability and replay variance.

For detailed concern questions, moment prompts and experience/anti-experience checks, use the [`Game Analysis Reference`](../game-analysis-reference/README.md).

For zero-to-one creation, the [`Game Creation Workflow`](../game-creation-workflow.md) may also decompose a reference through Gameplay Situations, Loops, Dynamics and Scenarios to expose transformation targets.

## 7. Causal Reference Record

```text
Reference:
Reference type:
Responsibility:
Player promise:
Mechanic / Rule:
Dynamics:
Player behavior:
Experience:
Conditions:
Trade-offs:
Production burden, if material:
Evidence:
Transfer note:
```

A reference bank should become a library of causal records, not a catalogue of games the designer likes.

## 8. Dominant Reference

A `Dominant Reference` is the main baseline for the current core promise, central loop or overall game thesis.

Working rule:

> If the current direction cannot name its dominant baseline in one clear sentence, it may still be combining wishes rather than compatible references.

A project does not always require a whole-game dominant reference. The baseline may be a known genre pattern or a clearly articulated original causal thesis. The status must remain explicit.

## 9. Secondary Reference

A `Secondary Reference` contributes one limited responsibility not sufficiently covered by the dominant baseline.

For each secondary reference, record:

```text
responsibility;
reference type;
what is taken;
why it is needed;
what it must not change;
compatibility risks;
evidence or prototype need.
```

A secondary reference is not permission to import every attractive feature from another game.

## 10. Controlled Transformation

`Controlled Transformation` changes a working reference while preserving, replacing or deliberately deleting understood causes of value.

### Working Transformation Vocabulary

| Pattern | Meaning |
|---|---|
| Reskin | Change presentation while largely preserving system structure |
| Substitution | Replace one component with a functional analogue |
| Inversion | Reverse a rule, goal, role or incentive |
| Compression | Preserve enough value while reducing duration, complexity or production burden |
| Expansion | Make a secondary element the central system |
| Perspective shift | Change role, camera or level of control |
| Context transfer | Move a mechanic into another fantasy or setting |
| Recombination | Join limited responsibilities from several references |
| Constraint mutation | Change a key limit such as time, information or capacity |
| Audience adaptation | Rework friction, session shape or complexity for another audience |
| Experience substitution | Preserve the required Experience/function while replacing the mechanism that created it |
| Conceptual deletion | Remove a component and intentionally remove/redefine the Experience/function the game is expected to provide |

The vocabulary is an analytical aid, not a mandatory enum.

### Experience Substitution Versus Conceptual Deletion

Preserve this distinction:

```text
Experience substitution:
  expensive/reference component X
  creates value/Experience Y
  → remove X
  → another mechanism must still create Y.

Conceptual deletion:
  X creates Y
  → remove X
  → revise the Concept so Y is no longer
    a required promise/function of the game.
```

Do not remove X while silently continuing to rely on Y.

## 11. Transformation Target Selection

A creator does not always need a formal selection pass. When the part to change is already obvious, change it deliberately and continue.

When the target is unclear, useful prompts include:

```text
What seems weak?
What creates anti-experience?
What feels outdated?
What is overused / generic?
What has low value despite its cost?
What exists mainly from genre habit?
What stored Idea could replace this part?
What other reference solves this responsibility better?
What current/trending pattern serves the function better?
What can be compressed or merged?
What expensive part can be removed?
Can another cheaper system create the same Experience?
Can the Concept be changed so that Experience is no longer required?
What secondary part deserves expansion?
What key constraint could be mutated?
What changes if agency/perspective moves?
Can authored content become systemic?
Can expensive simulation become authored/curated content?
What can be removed without replacement?
```

These are optional idea-generation prompts, not a mandatory checklist.

A target is especially valuable when changing it:

```text
creates a meaningful new player value;
fixes a known weakness;
reduces production burden;
makes the Concept more legible/compact;
opens space for a stronger system;
or allows an existing strong Idea to integrate cleanly.
```

## 12. Transformation Record

For a meaningful transformation, state proportionally:

```text
baseline;
reference responsibility;
value being preserved;
axis being changed;
expected new value;
conditions inherited from the reference;
conditions intentionally removed;
whether any old value is replaced or deliberately deleted;
trade-offs;
risks;
production/demo implication;
minimum evidence needed.
```

Do not change many high-impact axes at once unless the project is intentionally selecting a new baseline.

## 13. Reference Choice And Demo Feasibility

A reference can be creatively suitable but still be a bad initial production anchor.

When selecting a baseline for a new direction, inspect proportionally:

```text
Can the central value appear in a small enough demo?
Can the required systemic depth be implemented?
Can the visual proof be made credible?
How much authored content is required before the game becomes representative?
Does the reference depend on expensive animation, world scale,
agent count or content breadth that the new project cannot reproduce?
Can an expensive responsibility be replaced or deliberately removed?
```

The purpose is not to require a cheap final game. It is to avoid spending design effort on a direction whose central proof depends on an unreachable production layer.

Feasibility remains a constraint/evidence question, not proof that the design is good.

## 14. Combining Several References

Several references are compatible only when their responsibilities can coexist in one understandable game.

### Compatibility Checks

| Check | Question |
|---|---|
| Loop | Do the references interfere in second-to-minute repetition? |
| Decision | Do they create competing definitions of the correct choice? |
| Economy | Are rewards, scarcity, risk and recovery compatible? |
| Session | Are pacing, duration, escalation and rest compatible? |
| Readability | Can the player understand the combined state and affordances? |
| Audience | Does the intended audience still see a familiar anchor? |
| Production | Does the mix create feasible content, UX and balancing work? |
| Experience | Do the references reinforce the same central experience or compete for attention? |

### Dominance Rule

If a secondary reference changes the core loop, audience anchor and session structure together, treat it as a possible new baseline rather than a small addition.

### Conflict Rule

When references conflict:

1. identify the exact conflicting responsibility;
2. narrow the borrowed element to a subsystem or mechanic;
3. alter the transformation;
4. choose a different reference;
5. reject the mix;
6. or revise the Concept if the old responsibility is intentionally no longer required.

### Test Strategy

Prototype the point of conflict before building the full combination.

Examples:

- a new time limit;
- a new reward economy;
- a social dependency;
- a control scheme;
- a session-length change;
- a progression layer.

## 15. Reference Selection And Audience

A design reference and a market comparable may be the same game, but their responsibilities differ.

```text
design reference:
  explains how value is produced;

comparison reference:
  explains how the audience interprets the offer.
```

Record both roles when one game serves both.

## 16. Novelty

Novelty is justified when:

- known references do not solve the current experience need;
- the new interaction has understandable affordance and feedback;
- it strengthens the central experience or promise;
- the risk can be tested proportionally.

Novelty is a hypothesis until evidence supports it.

Reference First does not mean every answer must be copied from a game. It means novel work should know which causal responsibilities are being invented rather than inherited.

## 17. Consequences For Game Creation And Planning

A Concept should make visible proportionally:

- dominant/important reference baseline;
- reference responsibilities;
- broad Core Loop/value being preserved;
- intended transformation;
- demo/visual feasibility assumptions;
- unresolved compatibility risks.

The **current selected project direction** should make visible:

- reference baseline;
- causal records that matter to the active concept;
- intended transformations;
- secondary-reference responsibilities;
- unresolved compatibility risks;
- prototype or research needs.

Detailed alternative references/Variants may remain in a project Idea/creative workspace rather than making the current project owners unreadable.

## 18. Do Not

- Do not copy a feature without understanding its function.
- Do not call every inspiration a reference of equal importance.
- Do not combine several whole games without assigning responsibilities.
- Do not assume that a mechanic transfers without its conditions and feedback.
- Do not make the reference bank a list of reviews or ratings.
- Do not treat transformation patterns as proof that a mix will work.
- Do not add a trend only because it is current.
- Do not remove a costly system while continuing to assume its missing value will somehow remain.
- Do not reject a direction only because the final game is large; ask whether a representative proof is feasible.
