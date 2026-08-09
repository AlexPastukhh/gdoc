# Game Planning — Principles And Terminology

Status: active reusable principle-and-terminology owner
Scope: stable principles for maintaining a game direction from a rough seed through high-level planning, detailed planning, evidence and revision.

## 1. Purpose And Authority

This file owns the reusable planning meanings that apply across game projects regardless of a project's particular mechanics.

It owns:

- `Game Planning Draft`;
- high-level owner versus detail-owner boundaries;
- flexible planning depth and valid entry points;
- evidence and decision states used during game planning;
- treatment of directional or incomplete design input;
- the principle that planning is iterative rather than append-only.

It does not own:

- the complete game-planning route — use [`Game Development Planning Workflow`](../game-development-planning-workflow.md);
- Gameplay Situation / Loop / Scenario terminology — use [`Gameplay Situations, Loops And Scenarios`](gameplay-situations-loops-and-scenarios-principles-and-terminology.md);
- detailed structural, experience or visual question sets — use [`Game Analysis Reference`](../game-analysis-reference/README.md);
- project-specific accepted meaning.

## 2. Game Planning Draft

A `Game Planning Draft` is the evolving readable **high-level picture** of one current game direction.

It should make the current game understandable enough to review:

```text
what game is currently being pursued;
what experience / promise matters;
what broad gameplay and production picture supports it;
what is accepted, inferred, unresolved or risky;
which detail owners contain deeper work;
what evidence or next planning depth matters now.
```

A project normally keeps one current high-level Draft for one active direction rather than several competing summaries.

### Flexible structure

The Draft needs logical structure, not one universal section template.

```text
same responsibility
≠ same headings in every project.
```

A concept-heavy game may organize around promise, experience, gameplay and feasibility. A systemic project may need stronger state/system sections. A project currently driven by a concrete scenario may foreground that scenario and link outward.

Use the structure that makes the **current game** easiest to understand and update.

## 3. Planning Depth Is Flexible

Planning does not require a fixed progression from broad to detailed.

Useful starting points include:

```text
idea;
reference;
desired Player Experience;
fantasy;
mechanic;
market observation;
interesting risk / trade-off;
concrete Gameplay Situation;
production or implementation uncertainty;
prototype result.
```

Two common routes are both valid:

```text
Broad-first:
seed → high-level Draft → deeper gameplay → evidence → Draft revision.

Detail-first:
concrete Situation / experience / risk / reference
→ detailed planning
→ mechanics / requirements / Loops / questions become clearer
→ high-level Draft is created or revised.
```

These are not project modes. Work may move between them repeatedly.

A broad picture does not have to be complete before useful detailed work begins. Detailed work also does not replace the need for a readable high-level picture.

When a concrete Gameplay Situation is already the clearest useful object, detailed Situation planning may begin immediately, including structural, Player Experience and visual-planning passes, and the resulting meaning can then feed back into the broader Draft.

## 4. Detail Owners

Create a separate detail owner only when independent review, linking, reuse, testing, change tracking, parallel work or navigation justifies the coordination cost.

```text
high-level Draft
  → current cross-cutting meaning and navigation;

detail owner
  → the complete meaning inside one justified narrower responsibility.
```

A detail owner may become more precise than the high-level Draft. If that precision changes an accepted cross-cutting game decision, update the Draft rather than allowing the two to diverge silently.

Do not copy a complete detail body into the Draft merely to keep it “complete.” Link it and preserve the high-level consequence.

## 5. Evidence And Decision States

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
designer intent ≠ delivered-player-experience evidence.
```

## 6. Directional And Incomplete Design Input

Useful design input may be directional before it is precise.

Examples:

```text
"I want a vibe like X";
"this should feel more procedural";
"I imagine something between A and B, but not exactly either";
"the base should feel alive, but I do not yet know what visual treatment creates that".
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
  → decision candidate;

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
→ form plausible interpretations
→ inspect references / alternatives when useful
→ compare what value each interpretation preserves
→ narrow when evidence or explicit preference justifies it
→ promote the clearer meaning into the current plan.
```

Not every ambiguity must be resolved immediately by asking for a more precise sentence. Several interpretations may stay open while evidence, references or representative examples make the actual value clearer.

Example:

```text
Incoming:
  "I want a vibe like Duskers."

Confirmed:
  Duskers is an explicitly named directional reference.

Not yet confirmed:
  whether the desired value is palette, interface, sparse information,
  remote procedural tension, isolation, control distance or another cause.

Useful next work:
  separate several plausible reference responsibilities
  and compare what each interpretation preserves.
```

Reference analysis and controlled transformation may be used to discover what value actually matters before a realization is selected.

## 7. Planning Is Iterative And Not Append-Only

New evidence or an explicit decision may supersede earlier current meaning.

```text
new information
→ review affected meaning
→ update current owner
→ preserve evidence / rationale / historical provenance
→ stop presenting disproven or superseded meaning as a competing current answer.
```

Do not preserve every historical formulation as if it remained current. Do preserve enough provenance to understand why a material decision changed.

## 8. Requirements, Realizations And Implementation Ideas

Keep different planning levels separate:

```text
design requirement
  ≠ realization candidate
  ≠ implementation idea
  ≠ accepted implementation decision.
```

The same requirement may have several viable realizations. A technically convenient implementation does not automatically justify the requirement that it appears to satisfy.

## 9. Next Depth And Minimum Evidence

Choose the next planning or evidence depth from the uncertainty with the greatest effect on value, direction, cost or late-change risk.

Possible next depths include:

```text
clarify promise / audience / experience;
reference analysis;
Gameplay Situation planning;
Loop planning;
Scenario planning;
visual requirement planning;
balance questions;
interaction/system prototype;
production spike;
market test;
fuller demo / vertical slice planning.
```

Do not build a large roadmap when one smaller question is the actual blocker.

## 10. Do Not

- Do not require template-ordered input.
- Do not require a complete broad Draft before any detailed planning.
- Do not allow detail work to drift away from the high-level current direction without reconciliation.
- Do not create a new file for every heading or temporary concern.
- Do not silently promote inferences, examples or generated candidates into decisions.
- Do not treat planning as append-only accumulation.
