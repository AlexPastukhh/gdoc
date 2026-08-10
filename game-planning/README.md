# Game Planning — Project-Local Work

Status: active project-planning navigation owner
Scope: navigation and responsibility boundaries for game-specific planning stored under `game-planning/`.

## 1. Purpose

This area contains project-local planning meaning, including when justified:

```text
Game Planning Drafts;
project decisions and decision candidates;
hypotheses and evidence;
project-specific Ideas / Variants / Integration Probes;
Content Premises;
Situation / Loop / Dynamic / Scenario detail;
visual, production or other justified detail owners.
```

Reusable definitions do not originate here. Stable principles and terminology remain in [`../principles/README.md`](../principles/README.md), and reusable analysis/planning methods remain in [`../game-analysis-reference/README.md`](../game-analysis-reference/README.md).

Use [`../game-planning-use-case-registry.md`](../game-planning-use-case-registry.md) to find a documentation capability, [`../game-creation-workflow.md`](../game-creation-workflow.md) for zero-to-one synthesis, and [`../game-development-planning-workflow.md`](../game-development-planning-workflow.md) for ongoing planning orchestration.

## 2. Current Projects

| Project | Entry point | Current planning authority |
|---|---|---|
| [`Survivor Base`](survivor-base/README.md) | [`survivor-base/README.md`](survivor-base/README.md) | Project README points to its canonical `game-planning-draft.md`, current exploratory workspaces and justified detail owners |

## 3. Expected Project Pattern

A project may use this shape when useful:

```text
project README
  → navigation, authority and current depth;

Game Planning Draft
  → high-level current project meaning;

Idea / creative workspace, when justified
  → unresolved Ideas, Design Directions, Prompts,
    Variants and Probes without automatic promotion;

Content-Premise workspace, when justified
  → concrete candidate content units before
    detailed Scenario chronology;

justified detail owners
  → reusable-method application or project-specific detail
     that would make the high-level Draft harder to review;

research / prototypes / tests / evidence
  → feed reviewed meaning back into current owners.
```

This is an ownership pattern, not a mandatory folder template.

Do not pre-create one file per Idea, Prompt, Variant, Gameplay Situation, Loop, Dynamic, Scenario or visual topic merely for symmetry. Split detail only when independent review, navigation, reuse, testing, collaboration or production ownership makes the separate owner useful.

## 4. Authority Boundary

Project-local exploratory files may be **current working artifacts** without being canonical cross-cutting game meaning.

Preserve:

```text
saved Idea / Variant
  ≠ accepted game rule;

Integration Probe
  ≠ accepted planning unit;

Content Premise
  ≠ detailed Scenario
  ≠ automatic generic mechanic;

derived view
  ≠ canonical Draft.
```

When an explicit accepted decision changes cross-cutting project meaning, reconcile it into the project's canonical Game Planning Draft rather than allowing a narrower owner to become a silent competing source.

Project-local files may summarize or apply reusable terminology, but they do not silently redefine it.
