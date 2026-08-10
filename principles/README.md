# Game-Planning Principles And Terminology

Status: active reusable owner map
Scope: navigation and responsibility boundaries for stable game-planning principles and working terminology.

## 1. Purpose

Files in this directory marked `principle-and-terminology owner` answer:

```text
What does this term mean in the repository?
Which stable distinctions or design principles must not be silently changed?
```

They do **not** replace workflows, detailed planning methods, project decisions or evidence.

Use the repository layers as:

```text
principles / terminology
  → stable meanings and invariants;

use-case registry
  → which documentation capability/route is relevant;

workflow
  → how creation/planning moves between questions and depths;

analysis / planning references
  → detailed questions, schemas and lenses;

project documents
  → current project-specific decisions,
    ideas, hypotheses, evidence and detail.
```

For zero-to-one creative synthesis, use [`../game-creation-workflow.md`](../game-creation-workflow.md). For ongoing planning orchestration, use [`../game-development-planning-workflow.md`](../game-development-planning-workflow.md).

## 2. Current Owners

| Owner | Responsibility |
|---|---|
| [`Game Planning`](game-planning-principles-and-terminology.md) | `Concept`, `Design Direction`, `Brainstorm Prompt`, `Variant`, `Integration Probe`, Local/Integrated/Combination Evaluation, the Game Planning Draft, iterative/flexible planning, evidence/decision discipline and high-level/detail-owner boundaries |
| [`Gameplay Situations, Loops And Scenarios`](gameplay-situations-loops-and-scenarios-principles-and-terminology.md) | Canonical meanings and stable distinctions for Gameplay Situation, Loop, Scenario, their relations, and the boundary preventing broader visual/presentation contexts from being mislabeled as Gameplay Situations |
| [`Player Experience First`](player-experience-first-principles-and-terminology.md) | Player Experience, experience goals, experience levels and experience-first design principles |
| [`Mechanics Create Dynamics`](mechanics-create-dynamics-principles-and-terminology.md) | Mechanics/rules, Dynamics, behavior, feedback, incentives and causal design reasoning |
| [`Reference First And Controlled Transformation`](reference-first-and-controlled-transformation-principles-and-terminology.md) | Reference responsibilities, transfer, transformation, transformation-target and reference-risk principles |
| [`Audience Is Part Of The Game`](audience-is-part-of-the-game-principles-and-terminology.md) | Audience, purchase fantasy and audience-facing promise principles |
| [`Market And Platforms`](market-and-platforms-principles-and-terminology.md) | Market/platform assumptions and related terminology |
| [`Prototypes, Hypotheses And Tests`](prototypes-hypotheses-and-tests-principles-and-terminology.md) | Hypothesis/testing/prototype distinctions and evidence logic |
| [`Visual Design, Assets, And AI-Assisted Art`](visual-design-assets-and-ai-assisted-art-principles-and-terminology.md) | Visual-design, asset-strategy and reusable visual-production principles |

Other files in `principles/` may be research-derived notes, category references or topic material without the same canonical terminology responsibility.

## 3. Ownership Rule

Before adding a reusable definition:

1. Find the narrowest existing principle owner whose responsibility already includes the concept.
2. Add the definition there if it genuinely belongs to that responsibility.
3. Create a new principle owner only when the concept has an independent reusable boundary and enough meaning to justify it.
4. Detailed question sets and record schemas belong in reusable planning/analysis methods, not in this folder merely because they use canonical terms.
5. A project-local phrase or temporary label does not automatically become reusable terminology.

Avoid two competing canonical definitions. Other files should link to the owner and may give a short operational summary only when the workflow or local task needs it.
