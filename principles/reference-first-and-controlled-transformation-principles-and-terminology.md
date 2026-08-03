# Reference First And Controlled Transformation — Principles And Terminology

Status: active reusable principle-and-terminology owner
Research basis: [`../research/anatomy-of-a-game-reference.md`](../research/anatomy-of-a-game-reference.md)

## 1. Purpose And Authority

This file owns:

- Reference First;
- functional reference analysis;
- reference types;
- dominant and secondary references;
- Controlled Transformation;
- combining several references;
- reference-transfer and compatibility principles.

It does not own the full Player Experience taxonomy, platform algorithms or exact prototype execution.

## 2. Reference First

For every significant, expensive or risky design choice, use one of:

```text
a reference baseline;
a checked reusable pattern;
an explicitly marked hypothesis of novelty.
```

The rule is not meant to block small creative choices. It prevents expensive design from being built in a vacuum when relevant working solutions already exist.

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

## 4. Analyze Function, Not Surface

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

## 5. Minimal Game Reference Map

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

For detailed concern questions, moment prompts and experience/anti-experience checks, use the [`Game Analysis Reference`](../game-analysis-reference/README.md). The reference expands the practical observation surface; this file remains the owner of the reference-analysis principles and minimal map.

## 6. Causal Reference Record

```text
Reference:
Reference type:
Player promise:
Mechanic / Rule:
Dynamics:
Player behavior:
Experience:
Conditions:
Trade-offs:
Evidence:
Transfer note:
```

A reference bank should become a library of causal records, not a catalogue of games the designer likes.

## 7. Dominant Reference

A `Dominant Reference` is the main baseline for the current core promise, central loop or overall game thesis.

Working rule:

> If the current direction cannot name its dominant baseline in one clear sentence, it may still be combining wishes rather than compatible references.

A project does not always require a whole-game dominant reference. The baseline may be a known genre pattern or a clearly articulated original causal thesis. The status must remain explicit.

## 8. Secondary Reference

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

## 9. Controlled Transformation

`Controlled Transformation` changes a working reference while preserving or deliberately replacing understood causes of value.

### Working Transformation Vocabulary

| Pattern | Meaning |
|---|---|
| Reskin | Change presentation while largely preserving system structure |
| Substitution | Replace one component with a functional analogue |
| Inversion | Reverse a rule, goal, role or incentive |
| Compression | Preserve value while reducing duration, complexity or production burden |
| Expansion | Make a secondary element the central system |
| Perspective shift | Change role, camera or level of control |
| Context transfer | Move a mechanic into another fantasy or setting |
| Recombination | Join parts of several references |
| Constraint mutation | Change a key limit such as time, information or capacity |
| Audience adaptation | Rework friction, session shape or complexity for another audience |
| Experience substitution | Preserve part of the structure while changing the intended experience |

The vocabulary is an analytical aid, not a mandatory enum.

## 10. Transformation Record

For a meaningful transformation, state:

```text
baseline;
value being preserved;
axis being changed;
expected new value;
conditions inherited from the reference;
conditions intentionally removed;
trade-offs;
risks;
minimum evidence needed.
```

Do not change many high-impact axes at once unless the project is intentionally selecting a new baseline.

## 11. Combining Several References

Several references are compatible only when their responsibilities can coexist in one understandable game.

### Compatibility Checks

| Check | Question |
|---|---|
| Loop | Do the references interfere in the second-to-minute repetition? |
| Decision | Do they create competing definitions of the correct choice? |
| Economy | Are rewards, scarcity, risk and recovery compatible? |
| Session | Are pacing, duration, escalation and rest compatible? |
| Readability | Can the player understand the combined state and affordances? |
| Audience | Does the intended audience still see a familiar anchor? |
| Production | Does the mix create feasible content, UX and balancing work? |
| Experience | Do the references reinforce the same central experience or compete for attention? |

### Dominance Rule

If a secondary reference changes the core loop, audience anchor and session structure together, treat it as a candidate new baseline rather than a small addition.

### Conflict Rule

When references conflict:

1. identify the exact conflicting responsibility;
2. narrow the borrowed element to a subsystem or mechanic;
3. alter the transformation;
4. choose a different reference;
5. or reject the mix.

### Test Strategy

Prototype the point of conflict before building the full combination.

Examples:

- a new time limit;
- a new reward economy;
- a social dependency;
- a control scheme;
- a session-length change;
- a progression layer.

## 12. Reference Selection And Audience

A design reference and a market comparable may be the same game, but their responsibilities differ.

```text
design reference:
  explains how value is produced;

comparison reference:
  explains how the audience interprets the offer.
```

Record both roles when one game serves both.

## 13. Novelty

Novelty is justified when:

- known references do not solve the current experience need;
- the new interaction has understandable affordance and feedback;
- it strengthens the central experience or promise;
- the risk can be tested proportionally.

Novelty is a hypothesis until evidence supports it.

## 14. Consequences For Game Planning

A Game Planning Draft should make visible:

- dominant baseline;
- reference types;
- causal records that matter to the concept;
- intended transformation;
- secondary-reference responsibilities;
- unresolved compatibility risks;
- prototype or research needs.

## 15. Do Not

- Do not copy a feature without understanding its function.
- Do not call every inspiration a reference of equal importance.
- Do not combine several whole games without assigning responsibilities.
- Do not assume that a mechanic transfers without its conditions and feedback.
- Do not make the reference bank a list of reviews or ratings.
- Do not treat transformation patterns as proof that a mix will work.
