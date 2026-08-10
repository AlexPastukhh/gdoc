# Game Planning And Analysis Repository

Status: active repository navigation entry point

This repository contains reusable game-planning principles and methods, supporting research/reference material, and project-local planning documents.

## Start Here

Use [`game-planning-use-case-registry.md`](game-planning-use-case-registry.md) when the question is:

> What can I do with this documentation system, and which owner should I use?

Use [`game-development-planning-workflow.md`](game-development-planning-workflow.md) when the question is:

> How should planning move from the current game direction to the next useful planning, analysis or evidence step?

Use [`game-creation-workflow.md`](game-creation-workflow.md) when the question is:

> How do I generate, transform, compare and integrate possible game ideas or whole-game Concepts rather than only analyze a direction that already exists?

Then follow the layer that owns the current question:

| Area | Responsibility | Entry point |
|---|---|---|
| Stable principles and terminology | Canonical reusable meanings, distinctions and invariants | [`principles/README.md`](principles/README.md) |
| Reusable creation/planning workflows | How work moves from seeds/references through Concepts, detailed planning and evidence | [`game-creation-workflow.md`](game-creation-workflow.md), [`game-development-planning-workflow.md`](game-development-planning-workflow.md) |
| Reusable analysis and detailed planning methods | Structural, experience, visual and Situation / Loop / Dynamic / Scenario methods | [`game-analysis-reference/README.md`](game-analysis-reference/README.md) |
| Project-local planning | Current game-specific drafts, ideas, decisions, hypotheses, evidence and justified detail owners | [`game-planning/README.md`](game-planning/README.md) |

## Repository Layers

```text
principles / terminology
  → stable reusable meanings;

use-case registry
  → semantic map of supported documentation capabilities;

workflow
  → how planning / creation moves between questions and depths;

analysis / planning references
  → reusable questions, schemas and lenses;

project documents
  → current project-specific decisions, hypotheses,
    candidate ideas/content and justified detail.
```

Prefer the active owner linked by these navigation files rather than treating nearby notes or examples as competing sources of truth.

## Current Project Planning

Current project-local planning is indexed from [`game-planning/README.md`](game-planning/README.md).

The active project currently listed there is:

- [`Survivor Base`](game-planning/survivor-base/README.md)

## Supporting And Historical Material

The repository also contains supporting/reference areas such as:

- `categories/` — category and genre reference material;
- `research/` — research notes and reusable source-derived material;
- `prototype-fixtures/` — fixtures/examples used for prototype or tooling work;
- `game-anal/` — concrete game-analysis material outside the maintained reusable reference map;
- `chat-history/` — supporting transcripts/source ledgers and historical conversation provenance;
- older root notes such as `design-principles*` — historical or exploratory material.

These areas may contain useful information, but they do not override the active workflow, principle owners, analysis-reference owners or project-local canonical owners unless an active owner explicitly links them for that responsibility.

## Ownership Rule

When meanings disagree or seem duplicated:

1. start from the relevant README, Use-Case Registry or workflow entry point;
2. follow the named owner for the term, method or project meaning;
3. preserve project evidence/status distinctions;
4. do not promote supporting notes, Ideas, Probes, examples or derived views into canonical meaning without explicit review.
