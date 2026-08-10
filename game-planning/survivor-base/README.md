# Survivor Base — Game Planning

**Status:** active project-local planning entry point
**Project-layer map:** [`../README.md`](../README.md)
**Canonical planning owner:** [`game-planning-draft.md`](game-planning-draft.md)
**Idea workspace:** [`ideas.md`](ideas.md)
**Content-premise workspace:** [`content-premises.md`](content-premises.md)
**Source ledger:** [`../../chat-history/survivor-base-branch-01.md`](../../chat-history/survivor-base-branch-01.md)
**Imported source:** `survivor-base-planning-draft-v0.12-tactical-raids-alarms-emergency-response.md`
**Imported source SHA-256:** `d866e0d296da25d3377e363657bc6fdde871cc1101bea3e8c1b438dc4c01e933`

## 1. Responsibility

This directory owns project-specific planning for the current **Survivor Base Infection Concept** direction.

The high-level source of truth is [`game-planning-draft.md`](game-planning-draft.md).

The project also has two current exploratory/detail owners:

```text
ideas.md
  → preserved Game Ideas, hybrid ideas, Design Directions,
    Brainstorm Prompts, Variants and unresolved exploratory meaning;

content-premises.md
  → preliminary standalone playable/content units
    that may later be expanded into detailed Scenarios.
```

These are **current working owners**, but neither silently overrides the canonical Draft.

The files under [`views/`](views/) are also current derived working views. They reorganize current project meaning for particular questions. A view may include clearly marked candidate/inference material from linked working owners when that helps planning, but it does not silently convert an Idea, Premise or inference into an accepted cross-cutting decision.

Reusable game-planning principles remain in the repository root workflow and `principles/`; reusable analysis and design-planning lenses remain in `game-analysis-reference/`. Project-local visual planning lives under [`visual/`](visual/).

## 2. Current Document Map

| File | Responsibility | Authority |
|---|---|---|
| [`game-planning-draft.md`](game-planning-draft.md) | Complete consolidated current Planning Item set, decisions, candidates, risks, transformations and next passes | Canonical project-local planning owner |
| [`ideas.md`](ideas.md) | Preserved system/world/mechanic/hybrid ideas, Design Directions, Brainstorm Prompts, Variants and unresolved exploratory meaning | Active project-local creative workspace; not automatic Draft meaning |
| [`content-premises.md`](content-premises.md) | Preliminary standalone content units that can later be evaluated/expanded as Scenarios | Active project-local preliminary content owner |
| [`views/player-experience.md`](views/player-experience.md) | What experience/value the current systems appear intended to create; anti-experience and evidence gaps | Derived working view |
| [`views/game-building-blocks.md`](views/game-building-blocks.md) | Large systemic building blocks and their interfaces | Derived working view |
| [`views/gameplay-loops.md`](views/gameplay-loops.md) | Broad recurrent operating/session/long-term views plus candidate concrete Gameplay Loops | Derived working view |
| [`views/scenarios.md`](views/scenarios.md) | Representative Scenarios, Scenario Beats, integration questions and validation checkpoints | Derived working view |
| [`visual/README.md`](visual/README.md) | Visual-planning navigation, ownership and current depth | Project-local detail navigation |
| [`visual/visual-requirements-matrix.md`](visual/visual-requirements-matrix.md) | Visual-context and element requirements for what the visual system must communicate or support | Project-local visual requirements working owner; does not override Planning Items |

## 3. Idea / Premise / Scenario Boundary

Use:

```text
Game Idea
  → mechanic, rule, system direction, Dynamic direction,
    world/lore hypothesis or hybrid exploratory meaning;

Content Premise
  → concrete playable/content unit
    worth preserving independently
    but not yet expanded into detailed chronology;

Scenario
  → concrete chronological planning/test traversal
    with Beats, Situation Instances, execution,
    observation, waiting, consequences and recovery.
```

Current routing rule:

```text
Hybrid idea
  → ideas.md by default;

embedded content fragment
  → content-premises.md only when it becomes useful
    as an independently evaluated content unit;

premise developed deeply enough
  → reusable Scenario method
  → views/scenarios.md or another justified Scenario owner.
```

A premise may depend on unresolved mechanics. It does not have to wait for every dependency to be accepted before it can be preserved.

## 4. Source And Discussion Provenance

The August 2026 Idea/Content-Premise consolidation uses:

- [`../../chat-history/survivor-base-branch-01.md`](../../chat-history/survivor-base-branch-01.md) for the selected transcript boundary, later-message coverage and destination checking;
- the incoming numbered gameplay-idea source recorded there as `SB-B01-SRC01`;
- subsequent user refinements and explicit acceptance recorded in the ledger.

The ledger is provenance/supporting history, not a competing design owner.

## 5. Current Imported Draft State

The imported planning source is version `v0.12-tactical-raids-alarms-emergency-response`, whose source file describes itself as an **accepted working Planning Item set**.

Important distinctions from that source remain intact:

- accepted / preliminary / candidate / speculative / deferred / superseded meanings remain different states;
- `CHAT-PI-*` items remain semantic owners inside the draft;
- `CHAT-II-*` items remain relation-backed implementation candidates rather than accepted requirements;
- `CAT-01…CAT-10` remain local analytical labels inside this planning draft and are **not** repository `categories/` definitions;
- detailed frame-by-frame demo choreography is still deferred in the imported source;
- detailed visual realization and final art direction remain unresolved; the project has a separate visual-requirements planning layer under `visual/`.

The current Ideas/Premises update does **not** automatically promote every saved idea into this imported accepted Planning Item set.

## 6. Earlier Import Provenance

The historical Survivor Base import package was assembled after checking repository state at `AlexPastukhh/gdoc` HEAD `ef72beb5640683fb9617fa11e92fddcb51bf32a8`. That commit is package/import provenance, not a claim about the repository's current HEAD.

Project-content provenance came from the previously supplied source package:

- package: `survivor-base-fresh-chat-pack-v0.12(1).zip`;
- package SHA-256: `a435f17c3f57306f5035cd7b1f0f2d83b94e0b2e3af87d9572316bf2bc33ffc5`;
- authoritative draft: `survivor-base-planning-draft-v0.12-tactical-raids-alarms-emergency-response.md`;
- draft SHA-256: `d866e0d296da25d3377e363657bc6fdde871cc1101bea3e8c1b438dc4c01e933`.

The raw `S1–S7` provenance owner named by the draft, `survivor-base-planning-items-review-v0.4-accepted.md`, is not migrated here. The current draft still records that provenance relationship.

## 7. Current Gameplay-Planning Coverage

The reusable gameplay-planning methods distinguish four related planning/review scales:

```text
Gameplay Situation;
Gameplay Loop;
Gameplay Dynamic;
Scenario.
```

Survivor Base has derived owners for loop-oriented recurrent structure and representative Scenario chronology:

```text
views/gameplay-loops.md
  → broad operating / session / long-term views
    + candidate concrete Gameplay Loops;

views/scenarios.md
  → representative Scenarios
    + Scenario Beats
    + integration / validation questions.
```

This does not mean:

```text
broad operating cycle / Session Arc / Long-Term Arc
  = one concrete Gameplay Loop;

candidate Gameplay Loop
  = accepted Loop;

representative Scenario
  = frozen demo screenplay
  = only valid playthrough;

one Scenario manifestation
  = proof of a stable Gameplay Dynamic.
```

The project does not currently require a strict standalone Situation inventory or Dynamic inventory. Create additional records only when they materially improve review, balance, experience planning, validation, implementation or collaboration.

## 8. Working Rule For Current Views

When a current derived view produces or uses a formulation:

```text
Draft-backed wording
  → may be summarized with traceability;

Idea / Premise / inference
  → may appear when useful,
    but its non-canonical status must stay clear;

new explicit user decision
  → reconcile accepted cross-cutting meaning
    into the canonical Game Planning Draft;

evidence
  → update the affected hypothesis/decision
    rather than merely accumulate beside it.
```

Views are allowed to be shorter and more selective than the Draft. Their job is to make a specific planning question reviewable.

## 9. Visual Planning Boundary

The visual layer starts from project gameplay/context inputs and requirements rather than from an assumed art style.

```text
Gameplay Situation / Loop or Loop Phase / Scenario or Scenario Beat / Visual Context
  → meaningful elements
  → required perception and target experience
  → reusable visual lenses plus project-specific concerns
  → visual requirement
  → later realization candidates / references / representative tests.
```

A broader `Visual Context` such as routine operation, execution, waiting or aftermath does not become a Gameplay Situation merely because it needs visual planning.

The reusable visual lenses are not a closed taxonomy. Survivor Base may add project-wide, context-specific or element-specific concerns when the generic lenses do not describe the real planning problem.

The visual requirements owner may carry reference cues such as `"vibe like X"` without treating them as literal style-copy instructions. A reference must have a named responsibility; visual realization remains separate until explicitly selected.
