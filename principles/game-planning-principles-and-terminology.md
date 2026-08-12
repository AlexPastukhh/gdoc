# Game Planning — Principles And Terminology

Status: active reusable principle-and-terminology owner
Scope: stable principles for maintaining game directions from rough seeds and multiple possible Concepts through high-level planning, detailed planning, evidence and revision.

## 1. Purpose And Authority

This file owns reusable planning meanings that apply across game projects regardless of particular mechanics.

It owns:

- `Game Planning Draft`;
- `Concept`;
- `Design Direction`;
- `Brainstorm Prompt`;
- scoped `Idea workspace`;
- `Idea Variant` and `Planning Unit Variant`;
- `Content Premise`;
- integration review / optional lightweight `Integration Probe` wording;
- Local / Integrated / Combination Evaluation distinctions;
- `Game Domain` as a planning ownership boundary;
- high-level owner versus detail-owner boundaries;
- flexible planning depth and valid entry points;
- evidence and decision states used during game planning;
- treatment of directional or incomplete design input;
- the principle that planning is iterative rather than append-only.

It does not own:

- the complete zero-to-one creation route — use [`Game Creation Workflow`](../game-creation-workflow.md);
- the complete ongoing planning route — use [`Game Development Planning Workflow`](../game-development-planning-workflow.md);
- Gameplay Situation / Event / Loop / Scenario terminology — use [`Gameplay Situations, Loops And Scenarios`](gameplay-situations-loops-and-scenarios-principles-and-terminology.md);
- the canonical definition of Gameplay Dynamic — use [`Mechanics Create Dynamics`](mechanics-create-dynamics-principles-and-terminology.md);
- detailed structural, experience or visual question sets — use [`Game Analysis Reference`](../game-analysis-reference/README.md);
- a complete Game Domain template, economy methodology, Balance methodology, Strategy schema or Implementation Slice template;
- project-specific accepted meaning.

## 2. Concept

A `Concept` is a compact representation of one possible **whole game**.

Its purpose is to make a possible game understandable enough to compare and develop before every detailed system is known.

A Concept may contain proportionally:

```text
player promise / role;
reference baseline or original causal thesis;
broad Core Loop view;
key entities and important dependencies;
the character of recurring decisions;
important Dynamics / longer-term direction, when known;
target Player Experience;
major transformation from the baseline;
demo / visual / production feasibility;
important unresolved questions.
```

A Concept is not a small duplicate of the full Game Planning Draft.

Several Concepts may exist simultaneously while the designer explores possible games. Their candidate/open status should normally be visible from their owner/location/status. Do not rename the reusable object `Concept Candidate` merely because several Concepts are being compared.

### Broad Core Loop inside a Concept

A Concept may use a broad `Core Loop` view to explain:

```text
what the player repeatedly attends to;
what kinds of entities/state matter;
what kinds of decisions recur;
what execution / feedback changes the next decision state.
```

That broad design thesis does not automatically equal one concrete `Gameplay Loop`. Concrete recurrent causal processes remain owned by the Loop methodology.

## 3. Need / Problem Framing

Before solving a local task, keep it traceable to the underlying need.

Useful questions include:

```text
Why is this needed?
What more fundamental need does it serve?
Does that need still exist?
Must this object actually change?
Could the need be satisfied another way?
What happens if nothing changes?
What evidence says the problem is here?
```

A `Need Chain` is a reasoning aid, not a mandatory record type.

When changing an existing solution, reference, subsystem or planning object, decompose it before generating replacement answers when that decomposition matters:

```text
responsibilities;
parts;
dependencies;
value-producing parts;
problem-producing parts;
required vs accidental parts;
transformation target.
```

Preserve the stable principle:

> **Do not lose the fundamental task while solving a local subproblem.**

The result may legitimately be `do not change this object` when another route satisfies the underlying need better.

## 4. Design Direction, Brainstorm Prompt And Scoped Ideas

### Design Direction

A `Design Direction` is one area of the design space being explored, such as:

```text
Governance And Leadership;
Infection Evolution;
Session Structure;
Raid Information;
Visual Readability.
```

It is an optional navigation/exploration container. It is not a decision status, it is not the same thing as the whole project's current game direction, and it is **not required before every Prompt or Idea workspace can exist**.

### Brainstorm Prompt

A `Brainstorm Prompt` is one bounded piece of answer-seeking work.

It may live inside a Design Direction or arise directly from a material local question/problem owned by a Situation, Domain, Loop, Dynamic, Scenario or another justified planning object.

Useful Prompt types include:

```text
Question;
Task;
Requirement;
Problem.
```

The type list is a working vocabulary, not a mandatory enum.

A useful Idea may appear before any Prompt exists. The documentation must not block spontaneous ideation by requiring a designer to classify a thought first.

### Planning Surfaces As Question-Discovery Lenses

When the next useful question is unclear, inspect only relevant planning surfaces/fields to discover it.

Possible surfaces include:

```text
Situation;
Loop;
Dynamic;
Scenario;
Game Structure Analysis;
Player Experience;
Visual;
Production / Feasibility;
Reference analysis;
other justified fields.
```

Preserve the distinction:

```text
Need / Problem Framing
  → WHY does this matter?

planning surfaces / fields
  → WHAT QUESTIONS are material?

Brainstorm Prompt
  → WHAT ANSWER is being sought now?
```

Do not require a fixed Situation → Loop → Dynamic → Scenario traversal. Stop when no additional material question is found.

### Scoped Idea Workspace

An `Idea workspace` is an owner-local exploration area for an unresolved question/problem.

It may contain proportionally:

```text
source wording / Need;
question / Prompt;
Idea Variants;
evidence / references / tests;
Local Evaluation;
integration findings;
Combination Evaluation;
Current Conclusion.
```

`Idea workspace` is not a gameplay scale and not an acceptance state.

It may exist at project scope for cross-cutting/unrouted work or beside a meaningful owner such as a Domain, Situation, Planning Unit Variant, Situation Version, Loop, Dynamic or Scenario.

Keep one primary home for one planning question. Use links/categories/relations for cross-cutting relevance rather than maintaining divergent duplicated copies.

Place the workspace at the highest scope where its question remains genuinely shared; specialize lower only when the meaning differs.

## 5. Variants

Keep two useful scopes distinguishable.

### Idea Variant

An `Idea Variant` is one possible answer, rule, mechanic, transformation, combination or causal model for one scoped question/Prompt.

Idea Variants may be:

```text
alternatives;
complements;
refinements;
dependencies;
conflicts;
combinations.
```

### Planning Unit Variant

A `Planning Unit Variant` is an **integrated alternative design of the whole planning unit** being compared.

A whole-unit Variant can combine several local Idea Variants and may exist, when useful, for a Situation, Loop, Dynamic, Scenario or another meaningful planning unit.

This general Variant distinction does **not** automatically establish a contextual `Version` concept at every scale. The current Situation-specific `Variant / Version / Instance` distinction is owned by the gameplay terminology.

A Variant remains exploratory until explicitly selected or otherwise promoted with the appropriate evidence/decision state.

Questions discovered while evaluating a Variant may belong to different scopes:

```text
Prompt-Level Question
  → uncertainty about the current question/task/requirement itself;

Variant Question
  → uncertainty about one particular answer;

Cross-System Question
  → wider uncertainty exposed only after integration.
```

Use these labels only when helpful. They are not mandatory standalone object types.

## 6. Content Premise

A `Content Premise` is a sufficiently concrete **playable/content unit** worth preserving and evaluating independently before its full chronology is defined.

Examples may include a crisis, encounter, special base/world state, start configuration, event or another concrete piece of playable content.

Preserve:

```text
Idea
  → may be one mechanic, rule, direction, world thought or hybrid;

Content Premise
  → concrete enough to stand as one candidate content unit;

Scenario
  → concrete chronological traversal with Beats,
    Situation Instances, execution, observation,
    waiting, consequences and recovery.
```

A Content Premise may depend on unresolved mechanics and does not itself accept them.

```text
Content Premise
≠ accepted generic mechanic
≠ accepted cross-cutting Draft meaning
≠ detailed Scenario.
```

Project-local owners may keep candidate Content Premises when independent preservation/review is useful. Detailed Scenario chronology belongs to the reusable Scenario method and the justified project Scenario owner.

## 7. Integration And Evaluation Layers

Integration asks:

> If this local answer were used, what does the relevant wider planning unit become?

The current preferred route is:

```text
local Idea Variant
→ real candidate Planning Unit Variant at the relevant scale
→ Integrated Evaluation
→ compare / combine / revise / reject / select.
```

Do not require a separate family of `PROBE-SIT`, `PROBE-LOOP`, `PROBE-DYN`, `PROBE-SCN`, `PROBE-CONTENT` or `PROBE-CONCEPT` artifacts.

The phrase `Integration Probe` may still be used operationally for a temporary **integration review/activity** when useful, but it does not create a separate planning ontology or exempt the resulting candidate unit from normal status/ownership rules.

Promotion from exploratory work into a normal planning-unit candidate is **not acceptance**. Acceptance remains an explicit evidence/decision-state change.

Keep evaluation layers distinct:

```text
Local Evaluation
  → how well does the Idea Variant answer its scoped problem?

Integrated Evaluation
  → how good is the Variant after wider interactions,
    dependencies and consequences are considered?

Combination Evaluation
  → how do several Variants work together?
```

Risks, questions, pros/cons, evidence and refinement ideas belong to the evaluation context; they are not the Variant itself.

### Cross-Unit Relations

Independent planning units may conflict without becoming Variants of one common identity.

Use relations proportionally, for example:

```text
conflicts-with;
incompatible-with;
mutually-exclusive-with;
alternative-to;
requires;
enables;
supersedes.
```

When material, preserve the condition/reason for the relation rather than only a bare label.

A formal Alternative Set / configuration constraint object remains optional/unresolved and is not required by this principle.

## 8. Evidence Context For Ideas And Variants

For substantial exploration, preserve the scope of evidence rather than treating any reference as validation of the whole answer.

A proportional `Evidence Context` may contain:

```text
References / Analogues
Research Evidence
Prototype / Simulation / Playtest Results

What This Evidence Supports
What It Does Not Establish

Conflicting Evidence
Remaining Assumptions
Current Evidence-Based Conclusion
```

Preserve:

```text
reference exists
≠ Variant validated;

prototype worked technically
≠ gameplay value proven;

one Scenario supports a manifestation
≠ Dynamic proven;

evidence supports one claim
≠ evidence proves the entire Variant.
```

Do not duplicate the detailed test/result classification owned by [`Prototypes, Hypotheses And Tests`](prototypes-hypotheses-and-tests-principles-and-terminology.md).

## 9. Game Domain Ownership

A `Game Domain` is a named semantic area that owns reusable game truth needed by several gameplay/planning contexts.

A Domain may own proportionally:

```text
concepts / entities;
state and quantities;
relations;
operations / actions;
mechanics / rules;
constraints / invariants;
resource / economic meaning;
allowed transitions and results.
```

Prefer coherent semantic areas over mechanically splitting the whole game into global technical buckets such as `entities/`, `rules/`, `resources/` and `mechanics/` when that would fragment one concept's meaning.

DDD-like consistency is a semantic goal: planning language and later C#/Unity domain language should not silently diverge. Documentation structure and code structure do not have to mirror one another.

For state/operation ownership:

```text
state-level invariant
  → lives near the state/model it constrains;

operation
  → owns operation-specific preconditions,
    transition and postconditions;

operation
  → preserves applicable state invariants.
```

Meaningful mutable Domain state should preferably change through owned Domain operations rather than arbitrary unrelated mutation when that distinction is useful to the model.

Canonical reusable rule/value ownership remains in the Domain. A Situation may reference/project the relevant value or rule without becoming a second canonical owner.

```text
Domain canonical rule/value
→ referenced/projected into Situation
→ broader analysis / Balance may reveal a tuning need
→ accepted tuning changes the Domain owner
→ dependent representations are refreshed/reconciled.
```

A copied/derived summary that is not a live projection should retain enough source relation to trigger reconciliation when its source changes.

The exact Domain folder taxonomy, record template and economy methodology remain separate open design work.

## 10. Game Planning Draft

A `Game Planning Draft` is the evolving readable **high-level picture of one current game direction**.

It should make the current game understandable enough to review:

```text
what game is currently being pursued;
what experience / promise matters;
what broad gameplay and production picture supports it;
what is accepted, inferred, unresolved or risky;
which detail owners contain deeper work;
what evidence or next planning depth matters now.
```

A project normally keeps one current high-level Draft for one active direction rather than several competing canonical summaries.

Before one direction is selected, several Concepts may coexist outside the Draft or in another clearly non-canonical workspace. Once one direction becomes the current game, accepted cross-cutting meaning should be reconciled into the Draft.

### Flexible structure

The Draft needs logical structure, not one universal section template.

```text
same responsibility
≠ same headings in every project.
```

A concept-heavy game may organize around promise, experience, gameplay and feasibility. A systemic project may need stronger state/system sections. A project currently driven by a concrete Scenario may foreground that Scenario and link outward.

Use the structure that makes the **current game** easiest to understand and update.

## 11. Planning Depth Is Flexible

Planning does not require a fixed progression from broad to detailed.

Useful starting points include:

```text
idea;
reference;
Concept;
desired Player Experience;
fantasy;
mechanic;
market observation;
interesting risk / trade-off;
concrete Gameplay Situation;
Gameplay Loop;
Gameplay Dynamic;
Scenario / Content Premise;
production or implementation uncertainty;
prototype result.
```

Two common routes are both valid:

```text
Creation / synthesis:
seed / reference
→ scoped Ideas / Variants
→ one or more Concepts
→ deeper planning / evidence
→ select or revise the direction.

Current-direction planning:
current Draft
→ material question discovery
→ scoped detailed planning / evidence
→ Draft revision.
```

Detailed work may also start first:

```text
concrete Situation / experience / risk / reference
→ detailed planning
→ mechanics / requirements / Loops / questions become clearer
→ Concept or Draft is created/revised.
```

These are not project modes. Work may move between them repeatedly.

## 12. Detail Owners And Idea Retention

Create a separate detail owner only when independent review, linking, reuse, testing, change tracking, parallel work or navigation justifies the coordination cost.

```text
high-level Draft
  → current cross-cutting meaning and navigation;

detail owner
  → complete meaning inside one justified narrower responsibility.
```

A detail owner may become more precise than the high-level Draft. If that precision changes an accepted cross-cutting game decision, update the Draft rather than allowing the two to diverge silently.

Candidate/exploratory workspaces do not gain canonical authority merely by existing.

After an Idea workspace reaches a conclusion, preserve proportionally:

```text
selected/current meaning
  → semantic owner;

material decision rationale
  → compact durable rationale if it remains useful;

full research/exploration
  → retain only when the reasoning itself remains useful;

exploration-only material
  → may be removed after safe reconciliation.
```

The exact durable `decisions/` / `rationale/` filesystem owner is not fixed here.

Do not copy a complete detail body into the Draft merely to keep it “complete.” Link it and preserve the high-level consequence.

## 13. Evidence And Decision States

Keep these states distinct:

```text
confirmed:
  explicit project decision or checked source fact;

inference:
  reasoned interpretation awaiting review;

question:
  material unknown;

hypothesis:
  testable claim;

decision candidate:
  option under consideration;

decision:
  explicitly selected choice with rationale;

evidence:
  inspectable result from research, prototype,
  playtest, telemetry or market behavior.
```

Preserve:

```text
suggestion ≠ decision;
risk ≠ proven failure;
implementation idea ≠ accepted architecture;
prototype candidate ≠ build decision;
generated explanation ≠ canonical documentation automatically;
designer intent ≠ delivered-player-experience evidence;
saved Idea ≠ accepted game rule;
Content Premise ≠ accepted generic mechanic;
integrated candidate Planning Unit Variant ≠ accepted planning unit.
```

## 14. Directional And Incomplete Design Input

Useful design input may be directional before it is precise.

Examples:

```text
"I want a vibe like X";
"this should feel more procedural";
"something between A and B, but not exactly either";
"the base should feel alive, but I do not yet know
 what visual treatment creates that".
```

Preserve exact incoming wording and separate it from interpretation:

```text
explicit wording
  → confirmed source fact: the requester expressed this direction;

our interpretation
  → inference;

material ambiguity
  → question;

plausible realization
  → Variant / decision candidate;

testable expectation
  → hypothesis;

explicitly selected formulation
  → decision.
```

A temporarily open search space is not a planning failure. Prematurely turning one interpretation into a requirement is.

A useful clarification route is:

```text
raw / directional request
→ preserve wording
→ expose important ambiguity
→ form plausible interpretations / Variants
→ inspect references / alternatives when useful
→ compare what value each interpretation preserves
→ integrate promising answers
→ narrow when evidence or explicit preference justifies it
→ promote clearer accepted meaning into the current plan.
```

## 15. Planning Is Iterative And Not Append-Only

New evidence or an explicit decision may supersede earlier current meaning.

```text
new information
→ review affected meaning
→ update current owner
→ preserve evidence / rationale / historical provenance
→ stop presenting disproven or superseded meaning
  as a competing current answer.
```

Do not preserve every historical formulation as if it remained current. Do preserve enough provenance to understand why a material decision changed.

An Idea workspace may intentionally retain unresolved alternatives longer than the current Draft. That is its exploration responsibility, not an exception to Draft consistency.

## 16. Requirements, Realizations And Implementation Ideas

Keep different planning levels separate:

```text
design requirement
  ≠ realization candidate
  ≠ implementation idea
  ≠ accepted implementation decision.
```

The same requirement may have several viable realizations. A technically convenient implementation does not automatically justify the requirement that it appears to satisfy.

An unresolved local visual problem may live in an owner-local `ideas/visual/` workspace. When a visual/presentation solution becomes reusable accepted meaning, move/promote that realization to the appropriate project visual/presentation owner when independent ownership is useful; the gameplay owner keeps the requirement and relation rather than duplicating the presentation body.

## 17. Player Strategy Boundary

The canonical causal relationship between Gameplay Dynamics and Player Behavior / Strategy remains in [`Mechanics Create Dynamics`](mechanics-create-dynamics-principles-and-terminology.md). This file keeps only the planning boundary needed for routing and owner separation.

Operationally, keep the minimal distinction:

```text
Gameplay / System Dynamic
  → what the operative system tends to do / become over time;

Player Strategy
  → deliberate player-authored plan/policy across decisions and time,
    based on a model of how the system behaves.
```

A Dynamic can change which strategies are advantageous. Player Strategy/Behavior can in turn strengthen, weaken, redirect or counter a Dynamic.

The complete Strategy planning schema/filesystem and its relation to current Loop/session concepts remain open methodology work.

## 18. Next Depth And Minimum Evidence

Choose the next planning or evidence depth from the uncertainty with greatest effect on value, direction, cost or late-change risk.

Possible next depths include:

```text
generate / compare Concepts;
frame Need / problem;
discover material questions through relevant planning surfaces;
form a Brainstorm Prompt;
generate / compare Idea Variants;
build / compare a candidate Planning Unit Variant;
reference analysis;
Gameplay Situation / Event / Loop / Dynamic / Scenario planning;
visual requirement planning;
broader Balance questions;
interaction/system prototype;
production spike;
market test;
post-design Implementation Slice planning when design is ready.
```

Do not build a large roadmap when one smaller question is the actual blocker.

## 19. Source / Discussion Provenance

Long discussions may use a supporting message/source ledger.

The ledger can preserve:

```text
message/source ID;
source status;
captured meaning;
destination owner;
acceptance/refinement relation;
consolidation status.
```

The ledger is supporting provenance, not a competing canonical planning owner.

Preserve exact source wording when available. If an older contribution can only be reconstructed from a summary/generated working file, mark it as reconstructed rather than presenting it as verbatim.

When a later message accepts prior wording, preserve the scope of what was accepted. When a later user correction contradicts an earlier proposal, the later correction supersedes it.

## 20. Do Not

- Do not require template-ordered input.
- Do not require a complete broad Draft before useful detailed planning.
- Do not require a Design Direction before every Brainstorm Prompt or Idea workspace.
- Do not require a Brainstorm Prompt before a spontaneous Idea may be saved.
- Do not call every Idea a Concept.
- Do not treat a Content Premise as a detailed Scenario or accepted generic mechanic.
- Do not rename `Concept` to `Concept Candidate` just to signal uncertainty.
- Do not allow detail work to drift away from the high-level current direction without reconciliation.
- Do not create a new file for every heading, Prompt, Variant or temporary concern.
- Do not create mandatory `PROBE-*` artifacts for integration.
- Do not silently promote inferences, examples or Variants into decisions.
- Do not treat planning as append-only accumulation.
- Do not duplicate canonical Domain rules merely because one Situation displays them.
- Do not silently introduce exact Balance, Strategy, Domain, Version or Implementation-Slice structures that remain open.
