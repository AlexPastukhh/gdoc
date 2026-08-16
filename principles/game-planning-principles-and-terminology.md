# Game Planning — Principles And Terminology

Status: active reusable principle-and-terminology owner
Scope: stable principles for maintaining game directions from rough seeds and multiple possible Concepts through Scenario/Spine planning, reusable planning units, Ideas, evidence and revision.

## 1. Purpose And Authority

This file owns reusable planning meanings that apply across game projects regardless of particular mechanics.

It owns:

- `Concept`;
- `Design Direction`;
- `Brainstorm Prompt`;
- scoped `Idea workspace`;
- `Low-Level Element`;
- `Idea Variant` and `Planning Unit Variant`;
- reusable contextual `Version` across planning entities when useful;
- `Content Premise`;
- integration review / optional lightweight `Integration Probe` wording;
- Local / Integrated / Combination Evaluation distinctions;
- `Game Domain` as a planning ownership boundary;
- owner/detail boundaries and independent-owner criterion;
- legacy/transitional `Game Planning Draft` responsibility;
- flexible planning depth and valid entry points;
- evidence and decision states used during game planning;
- treatment of directional or incomplete design input;
- the principle that planning is iterative rather than append-only.

It does not own:

- the complete zero-to-one creation route — use [`Game Creation Workflow`](../game-creation-workflow.md);
- the complete Scenario/Spine route — use [`Scenario / Spine Planning Workflow`](../game-planning-spine-workflow.md);
- element-level working procedure — use [`Low-Level Element Planning Workflow`](../low-level-element-planning-workflow.md);
- Gameplay Situation / Event / Loop / Scenario terminology — use [`Gameplay Situations, Loops And Scenarios`](gameplay-situations-loops-and-scenarios-principles-and-terminology.md);
- the canonical definition of Gameplay Dynamic — use [`Mechanics Create Dynamics`](mechanics-create-dynamics-principles-and-terminology.md);
- detailed structural, experience or visual question sets — use [`Game Analysis Reference`](../game-analysis-reference/README.md);
- a complete Game Domain template, economy methodology, Balance methodology, Strategy schema or Implementation Slice template;
- project-specific accepted meaning.

## 2. Documentation Meaning Versus Example

When a reusable concept or boundary is difficult to understand abstractly, use a concrete example where it materially improves clarity.

Preserve:

```text
canonical definition / invariant
  → owns the reusable meaning;

illustrative example
  → explains that meaning;

full practical example
  → may later demonstrate a complete real artifact;

project artifact
  → owns actual project meaning/status.
```

Example:

```text
"restricted admission" in an illustrative example
≠ a required mechanic for every project
≠ accepted Survivor Base content automatically.
```

Examples should reduce ambiguity, not silently create rules.

## 3. Concept

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

A Concept is not a small duplicate of every detailed project owner.

Several Concepts may exist simultaneously while the designer explores possible games. Their candidate/open status should remain visible from owner/location/status. Do not rename the reusable object `Concept Candidate` merely because several Concepts are being compared.

### Broad Core Loop inside a Concept

A Concept may use a broad `Core Loop` view to explain:

```text
what the player repeatedly attends to;
what kinds of entities/state matter;
what kinds of decisions recur;
what execution / feedback changes the next decision state.
```

That broad design thesis does not automatically equal one concrete `Gameplay Loop`.

## 4. Need / Problem Framing

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

When changing an existing solution, reference, subsystem or planning object, decompose it when useful:

```text
responsibilities;
parts;
dependencies;
value-producing parts;
problem-producing parts;
required vs accidental parts;
transformation target.
```

Preserve:

> **Do not lose the fundamental task while solving a local subproblem.**

The result may legitimately be `do not change this object` when another route satisfies the underlying need better.

## 5. Design Direction, Brainstorm Prompt And Scoped Ideas

### Design Direction

A `Design Direction` is one area of the design space being explored, such as:

```text
Governance And Leadership;
Infection Evolution;
Session Structure;
Raid Information;
Visual Readability.
```

It is an optional navigation/exploration container. It is not a decision status, not the same thing as the whole project's current direction, and not required before every Prompt or Idea workspace.

### Brainstorm Prompt

A `Brainstorm Prompt` is one bounded piece of answer-seeking work.

It may live inside a Design Direction or arise directly from a material local question/problem owned by a Domain, Situation, Loop, Scenario, Variant, Version or another justified planning object.

Useful Prompt types include:

```text
Question;
Task;
Requirement;
Problem.
```

The type list is working vocabulary, not a mandatory enum.

A useful Idea may appear before any Prompt exists. Do not block spontaneous ideation by requiring classification first.

### Planning Surfaces As Question-Discovery Lenses

When the next useful question is unclear, inspect only relevant planning surfaces/fields.

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

Preserve:

```text
Need / Problem Framing
  → WHY does this matter?

planning surfaces / fields
  → WHAT QUESTIONS are material?

Brainstorm Prompt
  → WHAT ANSWER is being sought now?
```

Do not require a fixed Situation → Loop → Dynamic → Scenario traversal.

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

It may exist at project scope or beside the narrowest owner whose unresolved question it serves. Keep one primary home for one planning question. Use links/relations for cross-cutting relevance rather than divergent copies.

Example:

```text
shared question across all Situation Versions
  → Situation-level Idea workspace;

question only changes Variant B
  → Variant B-local workspace;

question only changes Siege Version of Variant B
  → that Version-local workspace.
```

## 6. Low-Level Element

A `Low-Level Element` is a meaningful design part/question **inside a planning unit** that is smaller than the whole unit and does not currently require independent reusable-unit ownership.

Examples can include:

```text
inside a Situation:
  one option;
  one occurrence driver;
  one information-source rule;
  one consequence relation;
  one activation/salience question;

inside an Execution:
  one interruption rule;
  one intermediate state;
  one feedback-delay question;

inside a Scenario:
  one handoff;
  one Beat-level information reveal;
  one pacing/attention concern;

inside a Domain:
  one operation precondition;
  one invariant;
  one resource-conversion question.
```

These examples are illustrative, not a mandatory element taxonomy.

Preserve:

```text
Low-Level Element
≠ separate planning entity automatically;

record field
≠ mandatory file/folder;

material local question
→ may use scoped Idea methodology;

independent reuse/review/research/testing/change lifecycle
→ may justify extraction into a real owner.
```

Concrete example:

```text
Parent Situation:
  Admission Under Uncertain Risk

Low-Level Element:
  exact restrictions of "restricted admission".

Possible work:
  generate several Idea Variants for that option
  → compare them
  → integrate the selected/current answer back into the Situation.
```

Use [`Low-Level Element Planning Workflow`](../low-level-element-planning-workflow.md) for the working route.

## 7. Variants And Versions

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

A `Planning Unit Variant` is an **integrated alternative design of the whole planning unit/entity** being compared.

A whole-unit Variant can combine several local Idea Variants and may exist, when useful, for a Situation, Loop, Dynamic, Scenario, Execution, Domain or another meaningful planning entity.

### Planning Entity Version

A `Version` is a **complete materially different reusable context/configuration of the same entity/design**.

The distinction is reusable across planning entities when useful; it is not limited to Gameplay Situations.

Preserve:

```text
Variant
  → alternative design;

Version
  → different reusable context/configuration
    of the same design;

Document Revision
  → edit/revision history of a document;

Version
≠ Variant
≠ document revision.
```

Not every entity needs Versions.

Examples only:

```text
Situation Variant A
  → Version: normal operation
  → Version: siege;

Execution Variant A
  → Version: manual staffing context
  → Version: automated staffing context;

Scenario Variant A
  → Version for another coherent target-game configuration,
    only if that contextual distinction is independently useful.
```

A Version is a complete contextual record, not merely a delta/patch against a mandatory base record.

### Scoped Child Work

When Variants or Versions coexist, child work remains scoped to the narrowest context where it is true.

```text
shared across entity
  → entity-level child work;

only Variant A
  → Variant A-local work;

only Version X of Variant A
  → Version X-local work.
```

A Variant/Version may have its own Ideas, lower-level planning units and Low-Level Elements where useful. Do not silently lift local meaning into sibling alternatives.

A Variant remains exploratory until explicitly selected or otherwise promoted with the appropriate evidence/decision state.

## 8. Content Premise

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

## 9. Integration And Evaluation Layers

Integration asks:

> If this local answer were used, what does the relevant wider planning unit become?

Preferred route:

```text
local Idea Variant
→ real candidate Planning Unit Variant at the relevant scale
→ Integrated Evaluation
→ compare / combine / revise / reject / select.
```

Do not require a separate family of `PROBE-*` artifacts.

`Integration Probe` may be used operationally for a temporary integration review/activity, but it does not create a separate planning ontology.

Promotion from exploratory work into a normal planning-unit candidate is **not acceptance**.

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

## 10. Evidence Context For Ideas And Variants

For substantial exploration, preserve evidence scope:

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
reference exists ≠ Variant validated;
prototype worked technically ≠ gameplay value proven;
one Scenario manifestation ≠ Dynamic proven;
evidence supports one claim ≠ whole Variant proven.
```

Detailed test/result classification remains owned by [`Prototypes, Hypotheses And Tests`](prototypes-hypotheses-and-tests-principles-and-terminology.md).

## 11. Game Domain Ownership

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

Prefer coherent semantic areas over mechanically splitting the whole game into global technical buckets when that would fragment one concept's meaning.

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

Canonical reusable rule/value ownership remains in the Domain. A Situation/Scenario may reference/project the relevant value or rule without becoming a second canonical owner.

## 12. Legacy / Transitional Game Planning Draft

A `Game Planning Draft` may exist as an evolving consolidated high-level artifact in a project imported from an earlier workflow.

Its current useful responsibilities can include:

```text
existing consolidated project meaning;
accepted/preliminary/candidate status history;
source/provenance continuity;
high-level migration context while newer owners are built.
```

The target reusable architecture does **not** require one permanent monolithic Draft.

For a project migrating from a Draft:

```text
legacy Draft
→ consult current source/status/provenance
→ build/refine Scenario / Spine
→ develop concrete low-level manifestations
→ extract/develop reusable owners
→ work on Low-Level Elements through Ideas when useful
→ retain legacy source until routing/provenance is safe.
```

Do not require every new owner-local clarification to be back-written into the Draft. Back-writing is needed only when explicit migration compatibility/provenance responsibility requires it.

Concrete example:

```text
Draft says newcomers are handled through an intake boundary.

Spine makes one concrete arrival/intake chronology explicit.

Reusable Situation owner later expands multiple ways
that uncertain-risk admission can arise and resolve.

The Draft remains a source for original project meaning,
but is not the permanent owner of all new reusable detail.
```

## 13. Planning Depth Is Flexible

Planning does not require a fixed progression from broad to detailed.

Useful starting points include:

```text
Idea;
reference;
Concept;
desired Player Experience;
mechanic;
interesting risk / trade-off;
concrete Gameplay Situation;
Gameplay Loop;
Gameplay Dynamic;
Scenario / Content Premise;
production or implementation uncertainty;
prototype result.
```

Common routes include:

```text
Creation / synthesis:
seed / reference
→ scoped Ideas / Variants
→ one or more Concepts
→ deeper planning / evidence
→ select or revise direction.

Scenario / Spine-centered:
current project meaning / migration sources
→ one concrete selected chronology
→ concrete low-level manifestations
→ reusable owners / Low-Level Elements
→ revised/new Scenarios.

Detail-first:
concrete Situation / experience / risk / reference
→ detailed planning
→ mechanics / requirements / questions become clearer
→ integrate into relevant project owners / Scenario.
```

These are not exclusive project modes.

## 14. Detail Owners And Idea Retention

Create a separate owner only when independent review, linking, reuse, research, testing, change tracking, parallel work or navigation justifies the coordination cost.

```text
Scenario / Spine
  → concrete selected chronology;

reusable owner
  → complete meaning inside one independently useful responsibility;

Low-Level Element
  → smaller parent detail unless independence emerges.
```

Candidate/exploratory workspaces do not gain canonical authority merely by existing.

After an Idea workspace reaches a conclusion, preserve proportionally:

```text
selected/current meaning
  → semantic owner;

material decision rationale
  → compact durable rationale if useful;

full research/exploration
  → retain only when reasoning remains useful;

exploration-only material
  → may be removed after safe reconciliation.
```

Do not copy a complete detail body into another high-level file merely to keep it “complete.” Link it and preserve only the consequence appropriate to that owner.

## 15. Authority And Content Status

Always separate two questions:

```text
Authority / Ownership:
  Where does this meaning belong?

Content Status:
  How strongly is this meaning currently established?
```

Example:

```text
project scenarios.md
  = Scenario owner;

Scenario X
  = may still be working / representative / candidate.
```

Owner ≠ accepted meaning.

## 16. Evidence And Decision States

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

## 17. Directional And Incomplete Design Input

Useful design input may be directional before it is precise.

Examples:

```text
"I want a vibe like X";
"this should feel more procedural";
"something between A and B, but not exactly either".
```

Preserve:

```text
explicit wording
  → confirmed source fact that requester expressed this direction;

interpretation
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

Prematurely turning one interpretation into a requirement is a planning error.

## 18. Planning Is Iterative And Not Append-Only

New evidence or explicit decisions may supersede earlier current meaning.

```text
new information
→ review affected meaning
→ update real owner
→ preserve evidence / rationale / provenance
→ stop presenting superseded meaning as competing current truth.
```

An Idea workspace may intentionally retain unresolved alternatives longer than selected current meaning. That is its exploration responsibility.

## 19. Requirements, Realizations And Implementation Ideas

Keep different planning levels separate:

```text
design requirement
  ≠ realization candidate
  ≠ implementation idea
  ≠ accepted implementation decision.
```

The same requirement may have several viable realizations.

## 20. Player Strategy Boundary

Canonical Dynamic ↔ Player Behavior / Strategy relation remains in [`Mechanics Create Dynamics`](mechanics-create-dynamics-principles-and-terminology.md).

Operationally:

```text
Gameplay / System Dynamic
  → what the operative system tends to do / become over time;

Player Strategy
  → deliberate player-authored plan/policy across decisions/time.
```

The complete Strategy planning schema/filesystem remains open methodology work.

## 21. Next Depth And Minimum Evidence

Choose next planning/evidence depth from the uncertainty with greatest effect on value, direction, cost or late-change risk.

Possible next depths include:

```text
generate / compare Concepts;
frame Need / problem;
discover material questions;
form a Brainstorm Prompt;
generate / compare Idea Variants;
work on a Low-Level Element;
build / compare a Planning Unit Variant;
create / compare Versions;
reference analysis;
Gameplay Situation / Event / Loop / Dynamic / Scenario planning;
visual requirement planning;
prototype / research / market evidence.
```

Do not build a large roadmap when one smaller question is the actual blocker.

## 22. Source / Discussion Provenance

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

The ledger is supporting provenance, not a competing canonical owner.

Preserve exact source wording when available. Reconstructed material must be marked as reconstructed rather than presented as verbatim.

## 23. Do Not

- Do not require template-ordered input.
- Do not require a complete broad Draft before useful detailed planning.
- Do not require a permanent monolithic Draft in the target architecture.
- Do not require a Design Direction before every Brainstorm Prompt or Idea workspace.
- Do not require a Brainstorm Prompt before a spontaneous Idea may be saved.
- Do not call every Idea a Concept.
- Do not treat a Content Premise as a detailed Scenario or accepted generic mechanic.
- Do not rename `Concept` to `Concept Candidate` just to signal uncertainty.
- Do not make every Low-Level Element a separate owner/file/entity.
- Do not use `Version` as another word for Variant or document revision.
- Do not require every planning entity to have Variants/Versions.
- Do not create mandatory `PROBE-*` artifacts for integration.
- Do not silently promote inferences, examples or Variants into decisions.
- Do not treat planning as append-only accumulation.
- Do not duplicate canonical Domain rules merely because one Situation/Scenario displays them.
