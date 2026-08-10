# Game Creation Workflow

Status: active reusable workflow
Scope: how to create and transform possible games from seed ideas and references, generate multiple answers to design problems, integrate them into wider gameplay, and form one or more Concepts before or alongside detailed planning.

## 1. Purpose And Authority

Use this workflow when the question is not merely:

> What is already in this game and how does it work?

but:

> What game could I make, what should I change, what alternatives exist, and how do I turn scattered ideas into coherent possible games?

This workflow owns the **creative synthesis route**. It does not replace:

- stable terminology in [`Game Planning`](principles/game-planning-principles-and-terminology.md);
- detailed reference rules in [`Reference First And Controlled Transformation`](principles/reference-first-and-controlled-transformation-principles-and-terminology.md);
- Situation / Loop / Dynamic / Scenario methods in [`Gameplay Planning`](game-analysis-reference/gameplay-planning/README.md);
- detailed Game Structure, Player Experience or visual analysis;
- future specialized brainstorming methods.

Use the semantic capability map in [`Game-Planning Documentation — Use-Case Registry`](game-planning-use-case-registry.md) when the current task is unclear.

## 2. Core Working Objects

### Concept

A `Concept` is a compact representation of one possible whole game.

It should normally make understandable, proportionally:

```text
player promise / role;
reference baseline or original causal thesis;
broad Core Loop view;
key player-controlled and world entities;
important states / dependencies;
the character of recurring decisions;
important Dynamics / long-term direction, when known;
target Player Experience;
major transformation from the baseline;
demo / visual / production feasibility;
main unresolved questions.
```

A Concept is not a small copy of the full Game Planning Draft.

Several Concepts may coexist while the designer compares possible whole games. The fact that a Concept is one option should normally be clear from its location/status; do not rename the entity `Concept Candidate`.

A broad Core Loop inside the Concept explains **what kind of recurrent play the game contains**. It may summarize a repeated decision/adaptation thesis and does not automatically equal one concrete Gameplay Loop.

### Design Direction

A `Design Direction` is one area of the design space being explored.

Examples:

```text
Governance And Leadership;
Infection Evolution;
Raid Information;
Infected Physiology;
Session Structure;
Visual Readability.
```

It is a navigation/exploration container, not a decision state and not the same thing as the current whole-game direction.

### Brainstorm Prompt

A `Brainstorm Prompt` is a bounded piece of answer-seeking work inside a Design Direction.

Useful prompt types include:

```text
Question;
Task;
Requirement;
Problem.
```

Examples:

```text
Question:
  Who actually holds power in the shelter?

Requirement:
  The player must be able to infer meaningful threat
  before direct visual contact.

Task:
  Replace the expensive authored mission layer
  without losing planning tension.

Problem:
  The baseline's recovery phase is repetitive.
```

An Idea can appear before a Prompt exists. Do not block spontaneous ideation by requiring every thought to be filed under a pre-existing question.

### Variant

A `Variant` is one possible answer, rule, mechanic, transformation, combination or causal model for a Prompt.

Variants can be:

```text
alternatives;
complements;
refinements;
dependencies;
conflicts;
combinations.
```

### Integration Probe

An `Integration Probe` is a temporary hypothetical planning artifact:

> If this Variant were accepted, what would the wider game look like?

Useful labels include:

```text
PROBE-SIT;
PROBE-LOOP;
PROBE-DYN;
PROBE-SCN;
PROBE-CONTENT;
PROBE-CONCEPT.
```

A Probe is **not** accepted project meaning.

### Evaluation Types

```text
Local Evaluation
  → how well the Variant answers the Prompt itself;

Integrated Evaluation
  → how good the Variant is when placed into the wider game;

Combination Evaluation
  → how two or more Variants behave together.
```

These are different passes. A locally strong answer may integrate badly, and two mediocre isolated ideas may form a strong combination.

## 3. Valid Inputs

Creation work can start from almost any useful seed:

```text
spontaneous game idea;
reference game / subsystem / mechanic;
desired Player Experience;
Gameplay Situation idea;
Gameplay Loop idea;
Gameplay Dynamic idea;
Scenario / Content Premise;
mechanic / rule;
Game Structure concern;
visual idea;
specific visual concern;
world / lore idea;
market or audience observation;
technical possibility;
production constraint;
prototype result.
```

Do not force the seed through a universal broad template before useful exploration can begin.

## 4. Preferred Early Anchor: Idea + Reference + Feasible Proof

When choosing a direction from scratch, prefer a seed that can be attached to a real working reference or clearly stated novelty hypothesis.

A strong early direction often has:

```text
interesting Seed Idea
+
Reference Anchor
+
Demo Feasibility
+
Visual Feasibility
+
enough achievable implementation depth
to demonstrate the central value.
```

The purpose is not to prove that the entire final game is cheap.

The question is:

> Can I build a demonstrable slice deep enough and visually credible enough to prove the central value of this direction?

Check proportionally:

```text
system depth;
required simulation breadth;
content burden;
visual/asset burden;
UI / information complexity;
technical dependencies;
time needed before the interesting decision appears.
```

A design may be creatively attractive but still be a poor initial direction when its value depends on a production layer the team cannot realistically demonstrate.

## 5. Reference Decomposition

When starting from a reference, do not treat the whole game as one indivisible object.

Use relevant existing planning surfaces to decompose what actually makes it work:

```text
Situations;
Loops;
Dynamics;
Scenarios;
Game Structure Analysis;
Player Experience;
Visual Design;
content / production burden;
reference causal records.
```

The point is to expose possible transformation axes and load-bearing dependencies.

Useful questions:

```text
Which parts generate the central decisions?
Which parts generate the central Experience?
Which systems are only supporting infrastructure?
Which elements are expensive?
Which relations are load-bearing?
Which parts could change independently?
Which parts only work because another part exists?
```

## 6. Select The Transformation Target

If the part to change is already obvious, choose it and continue.

When it is not obvious, use `Transformation Target Prompts` as optional discovery questions rather than a mandatory checklist.

### Weakness / Value Prompts

```text
What seems weak in the reference?
What creates anti-experience or low-value repetition?
What appears to exist mostly from genre habit?
What is present but not actually doing much useful work?
What secondary element is more interesting than the element currently treated as central?
```

### Aging / Familiarity Prompts

```text
What feels outdated in game design, UX, pacing or information flow?
What is so common that it contributes little identity?
Which old solution now has a better-known alternative?
```

### Available-Idea Prompts

```text
Can this part be replaced by an idea already saved elsewhere?
Is there a strong unused idea from another project or Idea Bank?
Does another reference solve this same responsibility better?
Can an existing Variant be transplanted here under new constraints?
```

### Trend Prompts

```text
Is there a current design pattern that serves this responsibility better?
Would a trend-backed replacement actually improve the function,
rather than being added only because it is fashionable?
```

### Compression Prompts

```text
Can the reference be conceptually simplified while keeping the core value?
Can several systems be collapsed into one?
Can a supporting layer be removed so production space is freed for a stronger feature?
Does this Variant make another system redundant?
```

### Production-Cost Prompts

```text
Which part is expensive relative to the value it creates?
Can the same Experience be produced more cheaply?
Can the game be redesigned so that this Experience is no longer required at all?
Can authored content be replaced by systems?
Can an expensive simulation be replaced by curated content?
```

Preserve the distinction:

```text
Cost replacement:
  remove expensive X
  → another mechanism still produces Experience Y;

Conceptual deletion:
  remove expensive X
  → change the Concept so Experience Y
    is no longer an obligation of the game.
```

Do not remove X while silently continuing to rely on the value X used to produce.

### Rule / Perspective Prompts

```text
What happens if a key constraint changes?
What happens if information becomes more/less complete?
What happens if time/capacity/permanence/risk changes?
What happens if agency moves to another actor or another control level?
What happens if a secondary system becomes the main system?
```

## 7. Form The Brainstorm Prompt

After selecting the current transformation/design target, state the answer-seeking task.

A useful Prompt often contains only:

```text
Design Direction;
Prompt type;
Question / task / requirement / problem;
relevant current context;
what value must be preserved;
important constraints;
references already known;
what must not be assumed.
```

Do not over-specify the Prompt so strongly that only the first imagined answer remains possible.

## 8. Answer Discovery

Use multiple possible sources of answers.

A high-level route is:

```text
0. Independent thought
   → walk away, think, sketch, write what appears naturally;

1. Reference borrowing
   → take a working answer from another relevant reference;

2. Reference transformation
   → substitute, invert, compress, expand, mutate a constraint,
     shift perspective, adapt audience/context;

3. Recombination
   → combine limited responsibilities from several references;

4. Novel brainstorming
   → attempt a solution without a direct reference baseline;

5. Hybrid
   → reference pieces + transformation + genuinely new connective logic.
```

Reference-backed answers are often useful because they carry inspectable evidence about at least part of the causal structure.

Novelty remains valid when the Prompt cannot be solved well by known references.

This section only defines answer sources. Detailed brainstorming techniques are intentionally deferred to a future methodology owner.

## 9. Capture Variants Without Premature Commitment

A Variant may begin as one line.

Expand it only when useful.

A proportional Variant workspace can contain:

```text
Variant ID / Name
Source / References

Proposed Answer

Local Evaluation
  Pros
  Cons
  Risks
  Open Questions
  Evidence
  Refinement Ideas

Dependencies / Conflicts / Relations

Integration Probes, if justified

Integrated Evaluation
  new Pros / Cons
  new Risks
  new Questions

Combination Evaluation, if useful

Current Conclusion
```

Possible relations include:

```text
supports;
combines with;
conflicts with;
replaces;
makes redundant;
depends on;
enables;
refines;
alternative to;
example of.
```

Risk, question, evidence and refinement are not the Variant itself. Keep them distinguishable so the history of evaluation remains readable.

## 10. Local Evaluation And Shortlisting

Before spending heavily on Integration Probes, perform a cheap first pass.

Ask:

```text
Does the Variant actually answer the Prompt?
What value does it create?
What does it cost?
What obvious risk or anti-experience appears?
What evidence/reference supports it?
What assumptions does it require?
Is it meaningfully different from the other Variants?
Can it be explained clearly?
```

Then:

```text
many Variants
→ cheap comparison
→ shortlist promising Variants
→ deeper integration work.
```

Do not require one winner. Several answers may remain open.

## 11. Integration Probes

For a promising Variant, inspect wider consequences by constructing only the planning units that are useful.

Examples:

```text
mechanic affecting local choice
  → PROBE-SIT;

economy/process change
  → PROBE-LOOP + PROBE-DYN;

large structural change
  → PROBE-SCN + PROBE-CONCEPT;

content rule
  → PROBE-CONTENT + representative PROBE-SCN.
```

A deep probe may use several scales:

```text
Situation;
Loop;
Dynamic;
Scenario;
Content Premise;
Player Experience;
Visual;
Production / Feasibility.
```

Do not mechanically create all of them.

### Integration Questions

Ask proportionally:

```text
What new Situations appear?
Which existing Situations change or disappear?
How does the Variant alter option availability, costs and consequences?
Which Loops change?
Which Dynamics become stronger, weaker or newly possible?
How does chronology/pacing change in representative Scenarios?
What changes in Player Experience?
What new information/readability requirement appears?
What happens to the Concept's broad Core Loop?
What production burden changes?
Which reference conditions are no longer valid?
What does the Variant make redundant?
What can now be removed or simplified?
What previously promising idea becomes weaker?
What previously weak idea becomes stronger when combined with this one?
```

Integration is not only about additions. Explicitly look for:

```text
deletion;
simplification;
redundancy;
lost meaning;
new dominant solutions;
systems that can merge;
old requirements that no longer apply.
```

## 12. Integrated Evaluation

After the Probe, re-evaluate the Variant.

Keep local and integrated findings separate.

Example:

```text
Local Risk:
  the mechanic may be difficult to learn.

Integrated Risk:
  after insertion it also destroys
  the decision space of a second Loop.
```

A Variant can move from promising to weak after integration, or become more valuable because it connects several systems.

## 13. Cross-Variant Synergy / Conflict Search

Do not compare Variants only against the current game.

Also ask:

```text
Which Variants solve the same responsibility and are redundant?
Which two strong Variants compete for the same decision space?
Which pair reinforces one another?
Does a new Variant make an older rejected idea worth reopening?
Can one Variant replace several smaller systems?
Do two Variants require contradictory player mental models?
Does one Variant create the missing condition another Variant needed?
```

This can produce Combination Evaluation rather than a single-answer selection.

## 14. Build Or Revise Concepts

When enough compatible meaning exists, assemble one or more Concepts.

A Concept may pull different Variants from several Design Directions.

Example:

```text
Direction A ─┐
Direction B  ├→ Concept 1
Direction C ─┘

same Directions
+ different Variants
→ Concept 2.
```

Use the Concept to see whether the parts form an understandable **whole game**.

A useful Concept review asks:

```text
What does the player basically do?
What repeats?
What is the broad Core Loop?
Which entities and state relations matter?
Where do meaningful decisions come from?
What changes over time?
What Experience is promised?
Which reference proves related value?
What is transformed?
Can a representative demo actually prove this?
What is the most dangerous unresolved dependency?
```

## 15. Choose The Next Uncertainty, Not A Fixed Scale Order

Do not impose:

```text
Idea
→ Situation
→ Loop
→ Dynamic
→ Scenario.
```

Choose the scale from the uncertainty that currently threatens the Concept most.

Examples:

```text
central local decision unclear
  → Situation;

recurrent causal process unclear
  → Loop;

long-term systemic direction unclear
  → Dynamic;

systems individually make sense
but their chronology/integration is unclear
  → Scenario;

experience claim unclear
  → Player Experience;

presentation/readability unclear
  → Visual planning;

working cause unclear
  → Reference analysis;

value still uncertain after planning
  → Prototype / test.
```

Detailed work creates new questions. Return those questions to Design Directions / Brainstorm Prompts and repeat the cycle.

## 16. Relationship To The Game Planning Draft

Several Concepts may exist while comparing possible games.

Once one direction becomes the active current game, maintain its cross-cutting current meaning in the project `Game Planning Draft`.

```text
Ideas / Variants / Probes
  ≠ accepted Draft meaning;

selected cross-cutting decision
  → reconcile into Draft;

detail owner discovers a project-wide accepted change
  → reconcile into Draft.
```

Do not use an Idea workspace or Probe folder as a competing canonical Game Planning Draft.

## 17. Discussion / Source Consolidation

Long creative conversations can create useful meaning faster than canonical owners should be edited.

When a project uses a supporting message ledger:

```text
message/source contribution
→ stable source ref
→ captured idea/question/decision/refinement
→ destination owner
→ consolidation status.
```

A source ledger preserves provenance; it does not itself accept game meaning.

Explicit acceptance such as `согласен`, `фиксируй` or a user edit should be linked to the specific prior proposal it accepts or refines.

## 18. Do Not

- Do not call every spontaneous idea a Concept.
- Do not require a Brainstorm Prompt before a useful idea is allowed to exist.
- Do not rename `Concept` to `Concept Candidate` merely because several Concepts are open.
- Do not require ten Variants or any fixed count.
- Do not run every Transformation Target Prompt mechanically.
- Do not prefer novelty merely because it has no reference.
- Do not copy a reference feature without understanding the responsibility/value being borrowed.
- Do not remove an expensive reference component while silently depending on its missing Experience.
- Do not treat a Probe as accepted Situation/Loop/Dynamic/Scenario content.
- Do not evaluate only locally when the Variant materially changes wider gameplay.
- Do not force every shortlisted Variant through every planning scale.
- Do not turn the Idea workspace into a second canonical Draft.
