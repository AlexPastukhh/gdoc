# Survivor Base — Game Planning

**Status:** active project-local planning entry point
**Project-layer map:** [`../README.md`](../README.md)
**Current legacy consolidated source:** [`game-planning-draft.md`](game-planning-draft.md)
**Current Scenario detail owner:** [`scenarios.md`](scenarios.md)
**Current opening-Spine working owner:** [`../../active-planning-goal-map.md`](../../active-planning-goal-map.md) until the detailed chronology is ready for `scenarios.md`
**Idea workspace:** [`ideas.md`](ideas.md)
**Content-premise workspace:** [`content-premises.md`](content-premises.md)
**Experience / Motivation planning:** [`experience-motivation/README.md`](experience-motivation/README.md)
**Source ledger:** [`../../chat-history/survivor-base-branch-01.md`](../../chat-history/survivor-base-branch-01.md)
**Imported source:** `survivor-base-planning-draft-v0.12-tactical-raids-alarms-emergency-response.md`
**Imported source SHA-256:** `d866e0d296da25d3377e363657bc6fdde871cc1101bea3e8c1b438dc4c01e933`

## 1. Responsibility

This directory owns project-specific planning for the current **Survivor Base Infection Concept** direction.

Survivor Base is currently in a **transition from a legacy consolidated Draft toward Scenario/Spine-centered planning with independently reusable low-level owners**.

```text
legacy game-planning-draft.md
  → existing consolidated Planning Items / status / provenance source;

Scenario / Spine
  → concrete selected chronology / run;

reusable low-level owners
  → broader possibility-space across Scenarios;

Low-Level Elements
  → smaller design concerns inside those owners,
    explored through scoped Ideas when useful.
```

The Draft is still actively consulted during this migration. Its continued use does **not** mean the target workflow requires a permanent monolithic Draft.

## 2. How The Legacy Draft Is Used During Migration

When building the current opening Spine or a reusable low-level owner:

```text
read relevant Draft Planning Items / status / provenance
→ preserve what the current source actually establishes
→ express the concrete manifestation in the Spine
→ extract/develop independently useful reusable owners
→ explore smaller Low-Level Elements through Ideas where useful
→ keep source/status traceable.
```

Do not assume every newly clarified owner-local detail must be written back into the Draft. Back-writing is required only when explicit migration compatibility/provenance responsibility calls for it.

Do not discard the Draft until still-useful meaning/provenance has been safely routed or intentionally retained as history.

## 3. Current Document Map

| File | Responsibility | Current authority/status boundary |
|---|---|---|
| [`game-planning-draft.md`](game-planning-draft.md) | Legacy consolidated Planning Item set, decisions, candidates, risks and imported current-source context | Active migration/source artifact; not target permanent integration center |
| [`ideas.md`](ideas.md) | Preserved system/world/mechanic/hybrid ideas, Design Directions, Brainstorm Prompts, Variants and unresolved exploratory meaning | Active creative workspace; not automatic accepted game meaning |
| [`content-premises.md`](content-premises.md) | Preliminary standalone content units before detailed chronology | Active preliminary content owner |
| [`gameplay-loops.md`](gameplay-loops.md) | Independently useful Gameplay Loop candidates/detail | Project-local gameplay detail owner |
| [`scenarios.md`](scenarios.md) | Representative Scenarios, Scenario Beats, integration questions and validation checkpoints | Project-local Scenario detail owner; selected chronology is not the only playthrough |
| [`experience-motivation/README.md`](experience-motivation/README.md) | Project Experience/Motivation and candidate Promise/Doubt planning | Active working owner; concrete units retain their own statuses |
| [`visual/README.md`](visual/README.md) | Visual-planning navigation, ownership and current depth | Project-local detail navigation |
| [`visual/visual-requirements-matrix.md`](visual/visual-requirements-matrix.md) | What visual system must communicate/support across current contexts | Working visual requirements owner; does not override gameplay/project source status |

## 4. Current Target Planning Architecture

For the current Survivor Base planning pass:

```text
selected opening Spine
→ progressively detailed concrete chronology
→ concrete Situation / Event / Execution / state / information manifestations
→ Low-Level Elements where smaller questions matter
→ reusable owners where independent responsibility is useful
→ reusable alternatives / Variants / Versions
→ compare clarified owners back against the Spine
→ later create/review other Scenario combinations.
```

The current pass is staged chronology-first for practical methodology validation. That does **not** establish a universal rule that all future projects must fully stabilize chronology before developing reusable owners.

Reusable architecture remains iterative:

```text
Scenario / Spine ↔ reusable owners ↔ Ideas / Variants / Versions ↔ new Scenarios.
```

## 5. High-Level Example Of The Current Opening Spine

**Illustrative working backbone, not frozen project choreography:**

```text
newcomers arrive / are detected
→ intake
→ admission decision
→ distribution / integration / work
→ people become more known
→ ambiguous symptom / evidence
→ response
→ investigation
→ assessment
→ persistent procedure / policy change.
```

Exact newcomers, symptoms, work assignment, diagnosis and final policy wording remain concrete Scenario assumptions/open details unless separately accepted.

The full reusable Scenario method is [`../../game-analysis-reference/gameplay-planning/scenarios.md`](../../game-analysis-reference/gameplay-planning/scenarios.md). The target Spine workflow is [`../../game-planning-spine-workflow.md`](../../game-planning-spine-workflow.md).

## 6. Idea / Premise / Scenario / Low-Level Element Boundary

Use:

```text
Game Idea
  → exploratory mechanic/rule/system/world/experience thought;

Content Premise
  → concrete playable/content unit worth preserving
    before full chronology is useful;

Scenario
  → concrete chronological selected path;

Low-Level Element
  → smaller design concern inside a planning unit,
    such as one option/rule/relation/field question.
```

Example:

```text
Scenario contains:
  admission decision.

Reusable Situation contains:
  broader admission possibility-space.

Low-Level Element question inside that Situation:
  exact restrictions of restricted admission.
```

Use [`../../low-level-element-planning-workflow.md`](../../low-level-element-planning-workflow.md) for the last case rather than inventing another unit automatically.

## 7. Source And Discussion Provenance

The August 2026 Idea/Content-Premise consolidation uses:

- [`../../chat-history/survivor-base-branch-01.md`](../../chat-history/survivor-base-branch-01.md) for transcript/source coverage and destination checking;
- the incoming numbered gameplay-idea source recorded there as `SB-B01-SRC01`;
- subsequent user refinements and explicit acceptance recorded in the ledger.

The ledger is provenance/supporting history, not a competing design owner.

## 8. Current Imported Draft State

The imported planning source is version `v0.12-tactical-raids-alarms-emergency-response`, whose source file describes itself as an **accepted working Planning Item set**.

Important distinctions remain intact:

- accepted / preliminary / candidate / speculative / deferred / superseded meanings remain different states;
- `CHAT-PI-*` items remain semantic records inside the legacy draft;
- `CHAT-II-*` items remain relation-backed implementation candidates rather than accepted requirements;
- `CAT-01…CAT-10` remain local analytical labels inside this planning draft and are **not** repository `categories/` definitions;
- detailed frame-by-frame demo choreography remains deferred in the imported source;
- detailed visual realization and final art direction remain unresolved; project visual planning lives under `visual/`.

Saving an Idea, Premise, Scenario detail or reusable unit does not automatically promote it into the imported accepted Planning Item set.

## 9. Earlier Import Provenance

The historical Survivor Base import package was assembled after checking repository state at `AlexPastukhh/gdoc` HEAD `ef72beb5640683fb9617fa11e92fddcb51bf32a8`. That commit is package/import provenance, not a claim about current HEAD.

Project-content provenance came from:

- package: `survivor-base-fresh-chat-pack-v0.12(1).zip`;
- package SHA-256: `a435f17c3f57306f5035cd7b1f0f2d83b94e0b2e3af87d9572316bf2bc33ffc5`;
- authoritative imported draft: `survivor-base-planning-draft-v0.12-tactical-raids-alarms-emergency-response.md`;
- draft SHA-256: `d866e0d296da25d3377e363657bc6fdde871cc1101bea3e8c1b438dc4c01e933`.

The raw `S1–S7` provenance owner named by the draft, `survivor-base-planning-items-review-v0.4-accepted.md`, is not migrated here. The current draft still records that provenance relationship.

## 10. Gameplay And Visual Boundaries

Broad operating/session/long-term summaries do not automatically become one concrete Gameplay Loop. A candidate Loop is not accepted merely because it has a detail owner. One Scenario manifestation is not proof of a stable Dynamic.

The visual layer starts from gameplay/context requirements rather than an assumed art style:

```text
Gameplay Situation / Loop / Scenario / Visual Context
→ meaningful elements
→ required perception / target experience
→ visual requirement
→ later realization candidates / references / tests.
```

A Visual Context such as routine operation, execution, waiting or aftermath does not become a Gameplay Situation merely because it needs visual planning.

## 11. Do Not

- Do not treat the legacy Draft as the target permanent planning architecture.
- Do not stop consulting the Draft while still-useful Planning Item meaning/provenance remains unrouted.
- Do not require back-writing every new low-level clarification into the Draft.
- Do not treat a project owner as proof that all content inside it is accepted.
- Do not create a standalone reusable owner for every concrete occurrence or Low-Level Element.
- Do not turn the selected opening Spine into the only valid playthrough.
