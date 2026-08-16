# Game Planning And Analysis Repository

Status: active repository navigation entry point

This repository contains reusable game-planning principles and methods, supporting research/reference material, and project-local planning documents.

For the **current active planning direction, open concerns and next validation work**, use [`active-planning-goal-map.md`](active-planning-goal-map.md). The Goal Map is operational/current-work navigation, not a canonical terminology owner or historical backlog.

## Start Here

Use [`game-planning-use-case-map.md`](game-planning-use-case-map.md) first when the practical question is:

> What can I do with this documentation system, and which files must I read to understand and perform that use case?

The Use-Case Map is a navigation owner. It gives practical capabilities, exact repository paths and read order. It does **not** redefine terminology, repeat complete workflows or copy detailed planning schemas.

Use [`game-development-planning-workflow.md`](game-development-planning-workflow.md) when the question is broad ongoing orchestration across Concepts, evidence and planning depth. Use [`game-planning-spine-workflow.md`](game-planning-spine-workflow.md) when the current route is specifically Scenario/Spine-centered planning from a concrete run into reusable planning units and back.

Use [`game-creation-workflow.md`](game-creation-workflow.md) when the question is:

> How do I generate, transform, compare and integrate possible game ideas or whole-game Concepts rather than only analyze a direction that already exists?

Use [`low-level-element-planning-workflow.md`](low-level-element-planning-workflow.md) when one smaller element inside an existing planning unit needs its own scoped Idea work without automatically becoming a new reusable unit.

## Documentation Layers

Keep these responsibilities explicit:

| Layer | Responsibility | Entry point |
|---|---|---|
| Use-Case Map | What practical work is supported and which exact paths to read | [`game-planning-use-case-map.md`](game-planning-use-case-map.md) |
| Principles / invariants / terminology | Stable reusable meanings, distinctions and boundaries | [`principles/README.md`](principles/README.md) |
| Workflows | How repeated work proceeds through steps, branches, returns and handoffs | [`game-creation-workflow.md`](game-creation-workflow.md), [`game-development-planning-workflow.md`](game-development-planning-workflow.md), [`game-planning-spine-workflow.md`](game-planning-spine-workflow.md), [`low-level-element-planning-workflow.md`](low-level-element-planning-workflow.md) |
| Detailed planning / analysis methods | Complete reusable questions, fields, schemas and lenses | [`game-analysis-reference/README.md`](game-analysis-reference/README.md) |
| Practical examples | Concrete application examples; complete examples are separate only when a full real planning artifact is worth preserving | Linked from the owning method/use case when they exist |
| Project-local planning | Current game-specific decisions, hypotheses, Ideas, Scenarios, reusable units, evidence and migration sources | [`game-planning/README.md`](game-planning/README.md) |

Preserve:

```text
Use-Case Map
≠ workflow;

workflow
≠ principle / terminology owner;

principle / invariant
≠ detailed method;

high-level illustrative example
≠ full practical example;

practical example
≠ project canon;

project owner authority
≠ content acceptance status.
```

## Examples And Documentation Hardening

Use concrete examples wherever they materially reduce ambiguity. Important concept boundaries, `A ≠ B` distinctions, scope/status distinctions and workflow handoffs should normally have an illustrative example when a useful example can be given without inventing project truth.

A short example stays inline with the principle/workflow/method it explains. Do **not** create a separate example file merely because a paragraph benefits from an example.

Create a separate full practical-example file only when a complete real planning artifact is useful to study as a whole, for example a completed Spine Scenario or a complete reusable Situation record. Such a documentation example should be frozen from active project evolution and changed only when the reusable method/example itself needs revision.

When a real reader/chat makes a reasonable wrong inference:

```text
correct the current understanding
→ inspect why the inference was possible
→ decide whether navigation / wording / scope / status /
  ownership / example / counterexample should improve
→ apply the smallest useful clarification.
```

Periodically test navigation as a fresh reader:

```text
practical question
→ Use-Case Map
→ required read route
→ correct workflow / principle / method
→ project owner only when project meaning is needed.
```

## Current Project Planning

Current project-local planning is indexed from [`game-planning/README.md`](game-planning/README.md).

The active project currently listed there is:

- [`Survivor Base`](game-planning/survivor-base/README.md)

Survivor Base still contains a legacy consolidated `game-planning-draft.md`. It remains a migration/source artifact while the Spine and reusable low-level owners are developed. Its current existence does **not** make a monolithic Draft a required target architecture for future projects.

## Supporting And Historical Material

The repository also contains supporting/reference areas such as:

- `categories/` — category and genre reference material;
- `research/` — research notes and reusable source-derived material;
- `prototype-fixtures/` — fixtures/examples used for prototype or tooling work;
- `game-anal/` — concrete game-analysis material outside the maintained reusable reference map;
- `chat-history/` — supporting transcripts/source ledgers and historical conversation provenance;
- older root notes such as `design-principles*` — historical or exploratory material.

These areas may contain useful information, but they do not override active workflow, principle owners, analysis-reference owners or project-local semantic owners unless an active owner explicitly links them for that responsibility.

## Ownership Rule

When meanings disagree or seem duplicated:

1. start from the Use-Case Map, relevant README or workflow entry point;
2. follow the named owner for the term, method or project meaning;
3. ask separately **where the meaning belongs** and **what its current content status is**;
4. preserve project evidence/status distinctions;
5. do not promote supporting notes, Ideas, exploratory Variants/Versions, examples or derived views into accepted meaning without explicit review.

Example:

```text
game-planning/<project>/scenarios.md
  = project-local Scenario owner;

Scenario X inside that file
  = may still be working / representative / candidate.

Owner
≠ accepted content.
```
