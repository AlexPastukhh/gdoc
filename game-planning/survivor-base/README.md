# Survivor Base — Game Planning

**Status:** active project-local planning entry point\
**Project-layer map:** [`../README.md`](../README.md)\
**Canonical planning owner:** [`game-planning-draft.md`](game-planning-draft.md)\
**Imported source:** `survivor-base-planning-draft-v0.12-tactical-raids-alarms-emergency-response.md`\
**Imported source SHA-256:** `d866e0d296da25d3377e363657bc6fdde871cc1101bea3e8c1b438dc4c01e933`

## 1. Responsibility

This directory owns project-specific planning for the current **Survivor Base Infection Concept** direction.

The high-level source of truth is [`game-planning-draft.md`](game-planning-draft.md). The files under [`views/`](views/) are derived working views: they reorganize current draft meaning for a particular question, but they do not silently override Planning Items or convert inferences into accepted decisions.

Reusable game-planning principles remain in the repository root workflow and `principles/`; reusable analysis and design-planning lenses remain in `game-analysis-reference/`. Project-local visual planning lives under [`visual/`](visual/).

## 2. Current document map

| File | Responsibility | Authority |
|---|---|---|
| [`game-planning-draft.md`](game-planning-draft.md) | Complete consolidated current Planning Item set, decisions, candidates, risks, transformations and next passes | Canonical project-local planning owner |
| [`views/player-experience.md`](views/player-experience.md) | What experience/value the current systems appear intended to create; anti-experience and evidence gaps | Derived working view |
| [`views/game-building-blocks.md`](views/game-building-blocks.md) | Large systemic building blocks and their interfaces | Derived working view |
| [`views/gameplay-loop-scenario.md`](views/gameplay-loop-scenario.md) | Broad core/session/long-term loop candidates and representative scenario synthesis | Derived working view |
| [`visual/README.md`](visual/README.md) | Visual-planning navigation, ownership and current depth | Project-local detail navigation |
| [`visual/visual-requirements-matrix.md`](visual/visual-requirements-matrix.md) | Visual-context and element requirements for what the visual system must communicate or support | Project-local visual requirements working owner; does not override Planning Items |

## 3. Current source state

The imported planning source is version `v0.12-tactical-raids-alarms-emergency-response`, whose source file describes itself as an **accepted working Planning Item set**.

Important distinctions from that source remain intact:

- accepted / preliminary / candidate / speculative / deferred / superseded meanings remain different states;
- `CHAT-PI-*` items remain semantic owners inside the draft;
- `CHAT-II-*` items remain relation-backed implementation candidates rather than accepted requirements;
- `CAT-01…CAT-10` remain local analytical labels inside this planning draft and are **not** repository `categories/` definitions;
- detailed frame-by-frame demo choreography is still deferred in the imported source;
- detailed visual realization and final art direction remain unresolved; the project now has a separate visual-requirements planning layer under `visual/`.

## 4. Source and provenance boundary

The historical Survivor Base import package was assembled after checking repository state at `AlexPastukhh/gdoc` HEAD `ef72beb5640683fb9617fa11e92fddcb51bf32a8`. That commit is **package/import provenance**, not a claim about the repository's current HEAD.

Project-content provenance came from the previously supplied source package:

- package: `survivor-base-fresh-chat-pack-v0.12(1).zip`;
- package SHA-256: `a435f17c3f57306f5035cd7b1f0f2d83b94e0b2e3af87d9572316bf2bc33ffc5`;
- authoritative draft: `survivor-base-planning-draft-v0.12-tactical-raids-alarms-emergency-response.md`;
- draft SHA-256: `d866e0d296da25d3377e363657bc6fdde871cc1101bea3e8c1b438dc4c01e933`.

The raw `S1–S7` provenance owner named by the draft, `survivor-base-planning-items-review-v0.4-accepted.md`, is **not migrated in this package**. The current draft still records that provenance relationship. Move that historical source into the repository only after it is explicitly selected for migration; do not infer that every historical draft belongs beside the canonical owner.

## 5. Current gameplay-planning coverage

The repository's reusable gameplay-planning methods now distinguish four related planning/review scales:

```text
Gameplay Situation;
Gameplay Loop;
Gameplay Dynamic;
Scenario.
```

Survivor Base project files were not retroactively normalized into one strict inventory or one file per scale. The canonical project meaning remains in `game-planning-draft.md`, while the existing `views/` are earlier derived syntheses that may use broader loop/situation wording.

Therefore:

```text
existing derived view
  ≠ accepted strict Gameplay Loop record automatically;

systemic tendency mentioned or implied in a view
  ≠ accepted Gameplay Dynamic automatically;

representative chronology in a view
  → may serve as Scenario-style synthesis without becoming
    the only canonical playthrough.
```

Create or normalize separate Situation / Loop / Dynamic / Scenario records only when doing so materially improves review, balance, experience planning, validation, implementation or collaboration. Do not create them merely for symmetry with the reusable method map.

## 6. Working rule for derived views

When a derived view produces a new formulation:

```text
source-backed wording
  → may be summarized with Planning Item traceability;

inference / synthesis
  → remains marked as inference or decision candidate;

new explicit user decision
  → should be promoted back into the canonical Game Planning Draft;

evidence
  → should update the affected hypothesis/decision rather than merely accumulate beside it.
```

The views are allowed to be shorter than the draft. Their job is to make specific planning questions reviewable, not to duplicate the entire 300kB source.

## 7. Visual planning boundary

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

The reusable visual lenses are not a closed taxonomy. Survivor Base may add project-wide, context-specific or element-specific concerns when the generic lenses do not describe the real planning problem. A local concern becomes a candidate reusable lens only after broader use justifies that promotion.

The visual requirements owner may carry reference cues such as "vibe like X" without treating them as literal style-copy instructions. A reference must have a named responsibility; visual realization remains separate until it is explicitly selected.
