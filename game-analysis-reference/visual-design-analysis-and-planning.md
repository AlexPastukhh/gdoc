# Visual Design Analysis And Planning

Status: active reusable analysis and planning reference
Scope: practical visual-analysis lenses and a gameplay/context-to-requirement method for game planning and reference transfer.

Canonical visual-design principles remain in [`Visual Design, Assets, And AI-Assisted Art`](../principles/visual-design-assets-and-ai-assisted-art-principles-and-terminology.md). Canonical Gameplay Situation / Loop / Scenario meanings and the repository boundary to the broader working term `Visual Context` remain in [`Gameplay Situations, Loops And Scenarios`](../principles/gameplay-situations-loops-and-scenarios-principles-and-terminology.md). Reference ownership and Controlled Transformation remain in [`Reference First And Controlled Transformation`](../principles/reference-first-and-controlled-transformation-principles-and-terminology.md).

## 1. Purpose And Authority

This file helps answer:

> What must the visual layer communicate, support or make the player perceive in a concrete Gameplay Situation, Loop/phase, Scenario/Beat or broader Visual Context, before choosing one implementation or art style?

It owns a reusable practical method for:

- decomposing Gameplay Situations, Loop/Scenario moments and broader Visual Contexts into visual planning elements;
- connecting player tasks and desired experience to visual requirements;
- inspecting a planning input with reusable visual lenses;
- preserving project-specific concerns that do not fit a generic taxonomy;
- separating a requirement from a realization candidate;
- decomposing directional requests such as "I want a vibe like X";
- assigning a named responsibility to visual, experience, production and market references;
- defining representative checks before accepting a visual solution.

It does not own:

- one concrete game's accepted visual direction;
- final art-style decisions;
- one game's reference bank;
- final asset-production specifications;
- canonical Player Experience definitions;
- canonical reference-transfer principles.

## 2. Core Route

```text
Gameplay Situation / Loop or Loop Phase / Scenario or Scenario Beat / Visual Context
  → meaningful elements inside the planning input
  → player task / decision
  → required perception
  → target experience / vibe
  → reusable visual lenses
  + project-specific original concerns
  → visual requirements
  → realization candidates
  → references / controlled transformations
  → representative gameplay-context test
  → clearer requirement or accepted decision.
```

The route is iterative. A directional request may remain unresolved while alternatives are explored.

### 2.1 Planning Inputs And Terminology

Visual planning can start from several gameplay-scale inputs without treating them as synonyms.

```text
Gameplay Situation
  = strict meaningful-decision term owned by gameplay terminology.

Gameplay Loop / Loop Phase
  = recurrent causal process / functional part of that process.

Scenario / Scenario Beat
  = concrete chronology / chronological part of that Scenario.

Visual Context
  = broader context that matters for visual planning but does not
    necessarily contain a new meaningful gameplay decision.
```

Examples of `Visual Context` can include routine operation, system execution, waiting, aftermath, store-first-look or another stable presentation context.

Therefore:

```text
Visual Context
≠ Gameplay Situation automatically.
```

For Gameplay Situation, Loop and Scenario planning, `V01–V11` may be inspected as a full discovery surface, in the same way that `Game Structure Analysis` and `Player Experience And Anti-Experience` can be walked at those scales. Record only the lenses with material findings; do not fill all eleven mechanically.

## 3. Requirement Before Realization

Keep these meanings separate:

```text
Visual requirement:
  what must be perceptually, functionally or experientially true.

Realization candidate:
  one possible way to satisfy one or more requirements.

Reference:
  an inspectable source useful for a named responsibility.

Accepted visual decision:
  a realization explicitly selected after sufficient review or evidence.
```

Example:

```text
Requirement:
  the player can distinguish a safe route from a blocked or compromised route
  under emergency attention pressure.

Candidate realization:
  shape-coded threshold state + local light + small status overlay.
```

Do not silently turn the candidate into the requirement.

## 4. Reusable Visual Lenses

The identifiers below are working reusable handles. They are not a claim that every visual problem consists of exactly eleven categories.

| ID | Lens | Main question |
|---|---|---|
| `V01` | Visual promise / genre / market signal | What game does this look like, what promise does it make, and what comparison frame does it trigger? |
| `V02` | Experience / perception contribution | How should the situation feel or be interpreted, and what part of that result belongs to the visual layer? |
| `V03` | Readability / information hierarchy | What must be noticed first, second and later? Which state or affordance must survive attention pressure? |
| `V04` | Camera / space / composition | What scale, framing, spatial relation and information density support the player's task? |
| `V05` | Shape / silhouette / proportion | Which roles, objects or states must remain distinct before color and fine detail? |
| `V06` | Color / value / contrast | Which value groups, accents and state meanings must remain readable and coherent? |
| `V07` | Light / shadow / visibility | How do illumination and occlusion guide attention, atmosphere and information access? |
| `V08` | Materials / surface / rendering / detail | Which surface, edge, texture and detail rules communicate world state without unnecessary production cost? |
| `V09` | Motion / animation / VFX / timing | What movement, timing or effect communicates life, impact, danger or state transition? |
| `V10` | UI / typography / iconography / overlays | Which abstract information needs interface representation and how should it relate to the physical world? |
| `V11` | Production / asset strategy / consistency | Can the visual solution be produced, reused, modified and kept coherent at the required scale? |

Use the lenses as a discovery surface for the current planning input. Do not fill every lens mechanically.

## 5. Project-Specific And Context-Specific Concerns

Reusable lenses are a starting analysis surface, not a closed taxonomy.

A concrete project, Gameplay Situation, Loop/Scenario moment, Visual Context or visual problem may require an additional original criterion, question or requirement that is not documented in the reusable list.

```text
If a local concern is real and useful:
  record it.

If no reusable lens describes it well:
  do not force it into an unrelated category.

Mark its scope:
  project-wide / Situation-specific / Scenario-specific / Visual-Context-specific / element-specific.

If the same concern proves reusable across several projects:
  review it as a candidate addition to this reference.
```

A project-specific concern can also cut across several reusable lenses. For example, "the same physical room must remain recognizably the same place across routine, alarm and aftermath" may involve composition, color, lighting, materials, state representation and production simultaneously.

The requirement itself should keep its own project-local ID. `V01–V11` are analysis tags, not requirement IDs.

## 6. Select The Right Gameplay / Presentation Input

A visual plan should begin from a gameplay or presentation context in which perception matters. When detailed gameplay planning already has a Gameplay Situation, Loop or Scenario, use that owner instead of inventing a second visual-only gameplay ontology.

Useful sources include:

- Gameplay Situations;
- Loop stages / Loop Phases;
- Scenario Beats;
- routine / execution / recovery Visual Contexts;
- first readable central interaction;
- failure and recovery;
- progression payoff;
- a representative crisis;
- a market/store first look when that is the question.

The input should be stable enough to survive likely implementation changes. Prefer meanings such as "controlled boundary crossing" over narrow implementation names when the latter may disappear.

For each input, identify meaningful elements only when they matter:

```text
space / route / boundary;
player-controlled unit or group;
other people / agents;
objects / interactables;
threat / uncertainty;
state-changing event;
UI/report/command layer;
materials / contamination / damage;
other project-specific elements.
```

## 7. Planning-Input-To-Requirement Record

A useful detailed record may contain:

```text
Requirement ID:
Planning input type / ID:
Element:
Player task / decision:
Requirement:
Required perception:
Target experience / vibe:
Reusable lenses:
Project-specific concern:
Source / evidence status:
Reference cue:
Realization status:
Risk / anti-requirement:
Minimum representative check:
Status:
```

Not every field is mandatory. Keep the smallest record that preserves the real design problem.

A compact coverage matrix may summarize `planning input × V01–V11`, but it is a navigation view. Detailed requirements own the actual meaning.

## 8. Experience And Vibe Are Not Purely Visual

A useful target may be expressed as a perception or vibe:

```text
procedural tension;
controlled institutional calm;
physical vulnerability;
uncertainty without randomness;
relief after regaining control;
a living workplace rather than a decorative diorama.
```

The visual layer may contribute to that result without owning all of it.

```text
Target experience / vibe
  ↘ visual language
  ↘ audio
  ↘ pacing
  ↘ information model
  ↘ controls
  ↘ world / agent behavior.
```

Record which contribution is being planned instead of asking color, lighting or UI to create an experience that depends on another system.

## 9. Directional Requests Such As "Vibe Like X"

"I want a vibe like X" is a valid directional request. It is not automatically a literal style specification.

Useful questions:

- In which Gameplay Situation, Loop/Scenario moment or Visual Context should the similarity matter?
- What exactly should the player perceive or feel?
- Which causes in X appear responsible for that effect?
- Which causes are visual, and which come from audio, pacing, information, controls or world behavior?
- Is X serving as an experience reference, visual-language reference, production reference, market/comparison reference, or several separate roles?
- What should be preserved?
- What must not be transferred?
- What would make the result look or feel like an inferior copy?
- Which transformation could preserve the useful value while changing the identity?
- What neighboring comparison would be undesirable?

Several interpretations may remain open while examples are inspected.

## 10. Reference Responsibilities

A reference may enter planning before realization is selected.

Useful roles include:

```text
Experience reference:
  proves or clarifies a desired perception or emotional effect.

Visual-language reference:
  shows how shape, value, light, composition, motion or UI supports a function.

Production reference:
  shows a feasible or reusable way to produce a similar class of content.

Market / comparison reference:
  shows how the audience may categorize, compare or misunderstand the offer.
```

One source may serve several roles, but record the roles separately.

Same-genre references are allowed. Their transfer risk is often higher because the audience can compare them directly. Ask what is being transformed, what remains distinctive and why the result is not only a cheaper copy.

Use the canonical Controlled Transformation principles when a borrowed solution becomes a meaningful design choice.

## 11. Observation Questions Vs Design-Elicitation Questions

Keep the two purposes visible.

### Observation

```text
What do I see?
What is noticed first?
Why does this state read?
Which element appears expensive?
What creates the apparent mood or tension?
```

### Design elicitation

```text
What must the player understand here?
How should this moment be perceived?
What existing example comes to mind?
Which part of that example is actually needed?
What must be different?
Which alternatives might create the same value?
```

An observation from a reference does not become a project requirement until the transfer is justified.

## 12. Production And Market Review

For each load-bearing visual requirement or realization candidate, review proportionally:

- asset count and variation burden;
- reuse/modularity;
- consistency across states and content;
- manual skill burden;
- compatibility with purchased/generated/handmade assets;
- animation/VFX cost;
- UI and world-art integration;
- screenshot and trailer legibility;
- genre recognition;
- differentiation from direct comparisons;
- risk that a borrowed visual solution becomes the visible identity of the reference rather than the current game.

Do not optimize only for cheap production if the result destroys readability or the player promise. Do not choose an attractive style that cannot be sustained.

## 12.1 Scenario-Local And Cross-Scenario Ownership

A concrete Scenario Beat can own exact local visual requirements such as:

```text
what must be perceived here;
what should remain uncertain;
intended understanding / response;
wrong reading to avoid;
local reference responsibility;
representative check.
```

A project-wide visual owner can instead own recurring/cross-scenario requirements, Visual Context coverage and links to Scenario Beats. Avoid maintaining two competing full copies of the same requirement.

## 13. Representative Checks

Prefer tests that preserve gameplay context.

Examples:

- same scene under routine, escalation and aftermath;
- crowded screen with the expected agent count;
- state recognition without reading labels;
- grayscale/value check when hue carries too much meaning;
- important state with UI reduced or removed;
- screenshot-sized market read;
- one reusable asset family produced in the proposed language;
- comparison of two realizations while keeping the underlying situation identical.

A style frame is useful when it represents the real information and production problem. A beautiful isolated illustration is weak evidence for gameplay readability.

## 14. Do Not

- Do not treat `V01–V11` as a mandatory complete form.
- Do not use `Gameplay Situation` as a broad synonym for routine, execution, aftermath, market-first-look or every visual context.
- Do not reject a useful project-specific concern because it lacks a reusable category.
- Do not promote every local concern into the reusable reference.
- Do not turn a realization candidate into a requirement.
- Do not treat "vibe like X" as an instruction to copy palette, UI or composition literally.
- Do not assume a reference's visible surface is the cause of its value.
- Do not let a same-genre reference silently define the game's visual identity.
- Do not ask the visual layer to solve an experience that primarily depends on non-visual systems.
- Do not select an art style without checking representative gameplay and production burden.
