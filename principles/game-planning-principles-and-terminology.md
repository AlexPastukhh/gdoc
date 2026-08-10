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
- `Variant`;
- `Content Premise`;
- `Integration Probe`;
- Local / Integrated / Combination Evaluation distinctions;
- high-level owner versus detail-owner boundaries;
- flexible planning depth and valid entry points;
- evidence and decision states used during game planning;
- treatment of directional or incomplete design input;
- the principle that planning is iterative rather than append-only.

It does not own:

- the complete zero-to-one creation route — use [`Game Creation Workflow`](../game-creation-workflow.md);
- the complete ongoing planning route — use [`Game Development Planning Workflow`](../game-development-planning-workflow.md);
- Gameplay Situation / Loop / Scenario terminology — use [`Gameplay Situations, Loops And Scenarios`](gameplay-situations-loops-and-scenarios-principles-and-terminology.md);
- detailed structural, experience or visual question sets — use [`Game Analysis Reference`](../game-analysis-reference/README.md);
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

## 3. Design Direction, Brainstorm Prompt And Variant

### Design Direction

A `Design Direction` is one area of the design space being explored, such as:

```text
Governance And Leadership;
Infection Evolution;
Session Structure;
Raid Information;
Visual Readability.
```

It is a navigation/exploration container. It is not a decision status and it is not the same thing as the whole project's current game direction.

### Brainstorm Prompt

A `Brainstorm Prompt` is one bounded piece of answer-seeking work inside a Design Direction.

Useful Prompt types include:

```text
Question;
Task;
Requirement;
Problem.
```

The type list is a working vocabulary, not a mandatory enum.

A useful Idea may appear before any Prompt exists. The documentation must not block spontaneous ideation by requiring a designer to classify a thought first.

### Variant

A `Variant` is one possible answer, rule, mechanic, transformation, combination or causal model for a Brainstorm Prompt.

Variants may be:

```text
alternatives;
complements;
refinements;
dependencies;
conflicts;
combinations.
```

A Variant remains exploratory until it is explicitly selected or otherwise promoted with the appropriate evidence/decision state.

Questions discovered while evaluating a Variant may belong to different scopes:

```text
Prompt-Level Question
  → uncertainty about the design question / task / requirement itself;

Variant Question
  → uncertainty about one particular answer;

Cross-System Question
  → wider uncertainty exposed by integration.
```

Use these labels only when the distinction helps. They are not mandatory standalone object types.

### Content Premise

A `Content Premise` is a sufficiently concrete **playable/content unit** worth preserving and evaluating independently before its full chronology is defined.

Examples may include:

```text
a crisis;
an encounter;
a special base/world state;
a start configuration;
an event;
another concrete piece of playable content.
```

Preserve the boundary:

```text
Idea
  → may be one mechanic, rule, direction, world thought or hybrid;

Content Premise
  → concrete enough to stand as one candidate content unit;

Scenario
  → concrete chronological traversal with Beats, Situation Instances, execution, observation, waiting, consequences and recovery.
```

A Content Premise may depend on unresolved mechanics and does not itself accept them.

```text
Content Premise
≠ accepted generic mechanic
≠ accepted cross-cutting Draft meaning
≠ detailed Scenario.
```

Project-local owners may keep candidate Content Premises when independent preservation/review is useful. Detailed Scenario chronology belongs to the reusable Scenario method and the justified project Scenario owner.

## 4. Integration Probe And Evaluation Layers

### Integration Probe

An `Integration Probe` is a temporary hypothetical planning artifact used to ask:

> If this Variant were accepted, what would a wider part of the game look like?

Working labels may include:

```text
PROBE-SIT;
PROBE-LOOP;
PROBE-DYN;
PROBE-SCN;
PROBE-CONTENT;
PROBE-CONCEPT.
```

The labels make status visible; they are not separate canonical planning-scale definitions.

Preserve:

```text
Probe
≠ accepted Gameplay Situation;
Probe
≠ accepted Gameplay Loop;
Probe
≠ accepted Gameplay Dynamic;
Probe
≠ accepted Scenario;
Probe
≠ accepted project meaning.
```

### Evaluation Layers

Keep these review questions distinct:

```text
Local Evaluation
  → how well does the Variant answer its Prompt?

Integrated Evaluation
  → how good is the Variant after wider game interactions,
    dependencies and consequences are considered?

Combination Evaluation
  → how do several Variants work together?
```

Risks, questions, pros/cons, evidence and refinement ideas belong to the evaluation context; they are not the Variant itself.

## 5. Game Planning Draft

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

## 6. Planning Depth Is Flexible

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
→ several Ideas / Variants
→ one or more Concepts
→ deeper planning / evidence
→ select or revise the direction.

Current-direction planning:
current Draft
→ detailed planning / evidence
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

## 7. Detail Owners

Create a separate detail owner only when independent review, linking, reuse, testing, change tracking, parallel work or navigation justifies the coordination cost.

```text
high-level Draft
  → current cross-cutting meaning and navigation;

detail owner
  → complete meaning inside one justified narrower responsibility.
```

A detail owner may become more precise than the high-level Draft. If that precision changes an accepted cross-cutting game decision, update the Draft rather than allowing the two to diverge silently.

Candidate/exploratory workspaces such as Ideas, Content Premises or Integration Probes may be useful detail owners. Their existence does not grant them canonical authority.

Do not copy a complete detail body into the Draft merely to keep it “complete.” Link it and preserve the high-level consequence.

## 8. Evidence And Decision States

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

Preserve these distinctions:

```text
suggestion ≠ decision;
risk ≠ proven failure;
implementation idea ≠ accepted architecture;
prototype candidate ≠ build decision;
generated explanation ≠ canonical documentation automatically;
designer intent ≠ delivered-player-experience evidence;
saved Idea ≠ accepted game rule;
Content Premise ≠ accepted generic mechanic;
Integration Probe ≠ accepted planning unit.
```

## 9. Directional And Incomplete Design Input

Useful design input may be directional before it is precise.

Examples:

```text
"I want a vibe like X";
"this should feel more procedural";
"something between A and B, but not exactly either";
"the base should feel alive, but I do not yet know
 what visual treatment creates that".
```

Preserve the exact incoming wording and separate it from interpretation:

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

## 10. Planning Is Iterative And Not Append-Only

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

## 11. Requirements, Realizations And Implementation Ideas

Keep different planning levels separate:

```text
design requirement
  ≠ realization candidate
  ≠ implementation idea
  ≠ accepted implementation decision.
```

The same requirement may have several viable realizations. A technically convenient implementation does not automatically justify the requirement that it appears to satisfy.

## 12. Next Depth And Minimum Evidence

Choose the next planning or evidence depth from the uncertainty with the greatest effect on value, direction, cost or late-change risk.

Possible next depths include:

```text
generate / compare Concepts;
form a Brainstorm Prompt;
generate / compare Variants;
reference analysis;
Integration Probe;
Gameplay Situation planning;
Loop planning;
Dynamic planning;
Scenario planning;
visual requirement planning;
balance questions;
interaction/system prototype;
production spike;
market test;
fuller demo / vertical slice planning.
```

Do not build a large roadmap when one smaller question is the actual blocker.

## 13. Source / Discussion Provenance

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

When a later message says `согласен`, `фиксируй` or otherwise accepts prior wording, preserve the scope of what was accepted rather than treating the entire preceding conversation as automatically confirmed.

## 14. Do Not

- Do not require template-ordered input.
- Do not require a complete broad Draft before useful detailed planning.
- Do not require a Brainstorm Prompt before a spontaneous Idea may be saved.
- Do not call every Idea a Concept.
- Do not treat a Content Premise as a detailed Scenario or an accepted generic mechanic.
- Do not rename `Concept` to `Concept Candidate` just to signal uncertainty.
- Do not allow detail work to drift away from the high-level current direction without reconciliation.
- Do not create a new file for every heading, Prompt, Variant or temporary concern.
- Do not silently promote inferences, examples, Variants or Probes into decisions.
- Do not treat planning as append-only accumulation.
