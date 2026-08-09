# Game Planning — Project-Local Work

Status: active project-planning navigation owner
Scope: navigation and responsibility boundaries for current game-specific planning stored under `game-planning/`.

## 1. Purpose

This area contains **project-local current meaning**:

```text
Game Planning Drafts;
project decisions and decision candidates;
hypotheses and evidence;
project-specific Situation / Loop / Dynamic / Scenario detail when useful;
visual, production or other justified detail owners.
```

Reusable definitions do not originate here. Stable principles and terminology remain in [`../principles/README.md`](../principles/README.md), and reusable analysis/planning methods remain in [`../game-analysis-reference/README.md`](../game-analysis-reference/README.md).

Use [`../game-development-planning-workflow.md`](../game-development-planning-workflow.md) for the repository-wide planning route.

## 2. Current Projects

| Project | Entry point | Current planning authority |
|---|---|---|
| [`Survivor Base`](survivor-base/README.md) | [`survivor-base/README.md`](survivor-base/README.md) | Project README points to its canonical `game-planning-draft.md` and justified detail owners |

## 3. Expected Project Pattern

A project may use this shape when useful:

```text
project README
  → navigation, authority and current depth;

Game Planning Draft
  → high-level current project meaning;

justified detail owners
  → reusable-method application or project-specific detail
     that would make the high-level Draft harder to review;

research / prototypes / tests / evidence
  → feed reviewed meaning back into the current project owners.
```

This is an ownership pattern, not a mandatory folder template.

Do not pre-create one file per Gameplay Situation, Loop, Dynamic, Scenario or visual topic merely for symmetry. Split detail only when independent review, navigation, reuse, testing, collaboration or production ownership makes the separate owner useful.

## 4. Authority Boundary

Project-local files may summarize or apply reusable terminology, but they do not silently redefine it.

Likewise, a derived project view does not override the project's canonical Draft merely because it is easier to read. New accepted cross-cutting meaning should be reconciled back into the project's canonical owner.
