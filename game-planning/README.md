# Game Planning — Project-Local Work

Status: active project-planning navigation owner
Scope: navigation and responsibility boundaries for game-specific planning stored under `game-planning/`.

## 1. Purpose

This area contains project-local planning meaning, including when justified:

```text
Game Planning Drafts;
project decisions and decision candidates;
hypotheses and evidence;
project-wide and owner-local Ideas / Variants;
Content Premises;
Game Domains;
Situation / Loop / Dynamic / Scenario detail;
visual / presentation, production or other justified detail owners.
```

Reusable definitions do not originate here. Stable principles and terminology remain in [`../principles/README.md`](../principles/README.md), and reusable analysis/planning methods remain in [`../game-analysis-reference/README.md`](../game-analysis-reference/README.md).

Use [`../game-planning-use-case-registry.md`](../game-planning-use-case-registry.md) to find a documentation capability, [`../game-creation-workflow.md`](../game-creation-workflow.md) for zero-to-one synthesis, and [`../game-development-planning-workflow.md`](../game-development-planning-workflow.md) for ongoing planning orchestration.

## 2. Current Projects

| Project | Entry point | Current planning authority |
|---|---|---|
| [`Survivor Base`](survivor-base/README.md) | [`survivor-base/README.md`](survivor-base/README.md) | Project README points to its canonical `game-planning-draft.md`, current exploratory workspaces and justified detail owners |

## 3. Project Ownership Pattern

Use the smallest structure that keeps ownership and review clear.

```text
project README
  → navigation, authority and current depth;

Game Planning Draft
  → high-level current project meaning;

project-level ideas/
  → cross-cutting, unrouted or parent-unknown exploration when useful;

named Game Domain owners, when useful
  → reusable project truth: state, relations, operations,
    rules/invariants and economic/resource meaning;

planning-unit owners
  → Situation / Loop / Dynamic / Scenario / other justified units;

Content-Premise workspace, when justified
  → concrete candidate content units before
    detailed Scenario chronology;

justified visual / presentation / production detail owners
  → independently useful accepted or exploratory detail
    that would make the high-level Draft harder to review;

research / prototypes / tests / evidence
  → feed reviewed meaning back into current owners.
```

A planning unit may remain one file while simple. Turn it into a folder only when independent review, navigation, reuse, testing, collaboration or production ownership makes local structure useful.

Do not pre-create empty folders merely to mirror a possible ontology.

## 4. Scoped Ideas

`ideas/` is a reusable **exploration mechanism**, not one special project-wide gameplay scale.

An Idea workspace may live beside the owner whose unresolved question it serves:

```text
project/ideas/
Domain/ideas/
Situation/ideas/
Variant/ideas/
<Situation Version>/ideas/
Loop/ideas/
Dynamic/ideas/
Scenario/ideas/
...
```

Keep one primary workspace/home for one planning question. Use links, relations or categories for cross-cutting relevance rather than maintaining divergent physical copies of the same question.

Place the workspace at the highest scope where its question remains genuinely shared. Specialize lower only when the meaning differs:

```text
shared across a Situation family
  → Situation-level ideas/;

specific to one whole-unit design Variant
  → Variant-level ideas/;

specific to one contextual Situation Version
  → Version-level ideas/.
```

Ideas may be grouped into semantic categories derived from the current owner's meaningful components or reusable analysis surfaces, for example record concerns, analysis, Experience, Visual, Balance or Production. Materialize only categories that simplify planning.

The exact category tree is project- and owner-specific. This repository does **not** require `ideas/record/...` or any other universal nesting scheme.

## 5. Variants And Situation Versions

Keep two Variant scopes distinguishable:

```text
Idea Variant
  → one candidate answer to one scoped question/problem;

Planning Unit Variant
  → an integrated alternative design of the whole planning unit.
```

A whole-unit Variant can combine several local Idea Variants. When broader integration is material, create/use the real candidate planning unit at the relevant scale instead of a separate `PROBE-*` artifact family.

For `Gameplay Situation`, also preserve the contextual `Version` distinction owned by the gameplay terminology:

```text
Situation Variant
  → alternative design;

Situation Version
  → full Situation record for one materially different
    reusable context/configuration of that design;

Situation Instance
  → one concrete occurrence in a Scenario/playthrough.
```

A Version is a complete Situation record, not a delta against an obligatory main file.

Simple one-design / one-Version case may remain compact:

```text
SIT-X/
  SIT-X-summer.md
```

If several contextual Versions become independently useful:

```text
SIT-X/
  versions/
    summer/
      SIT-X-summer.md
    winter/
      SIT-X-winter.md
```

If several whole-Situation design Variants coexist, Versions are scoped unambiguously to their Variant:

```text
SIT-X/
  ideas/                    # shared, when useful
  variants/
    VAR-A/
      ideas/                # only VAR-A-specific work
      versions/
        summer/
          SIT-X-VAR-A-summer.md
          ideas/            # only Version-specific work, when useful
        winter/
          SIT-X-VAR-A-winter.md
    VAR-B/
      ...
```

No canonical root `SIT-X.md` is required when several Variants coexist. A navigation file is optional and exists only when it improves navigation/identity review.

The new contextual `Version` meaning above is Situation-specific until other planning scales are reviewed explicitly.

## 6. Project-Specific Categories

Project-specific Situation grouping should support **many-to-many navigation** when one Situation belongs to several meaningful concerns.

Prefer category/link navigation over forcing every Situation into one physical category parent. The actual project taxonomy and whether any category also affects physical hierarchy remain project-specific decisions.

## 7. Authority And Promotion Boundary

Project-local exploratory files may be **current working artifacts** without being canonical cross-cutting game meaning.

Preserve:

```text
saved Idea / Idea Variant
  ≠ accepted game rule;

candidate Planning Unit Variant
  ≠ accepted planning unit;

Content Premise
  ≠ detailed Scenario
  ≠ automatic generic mechanic;

derived view
  ≠ canonical Draft.
```

When an explicit accepted decision changes cross-cutting project meaning, reconcile it into the project's canonical Game Planning Draft rather than allowing a narrower owner to become a silent competing source.

Accepted reusable visual/presentation realization should move from a local exploratory Idea workspace into the appropriate project visual/presentation owner when such independent ownership is useful; the originating gameplay owner keeps the requirement/relation rather than becoming a duplicate presentation owner.

Project-local files may summarize or apply reusable terminology, but they do not silently redefine it.
