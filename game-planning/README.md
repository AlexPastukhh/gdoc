# Game Planning — Project-Local Work

Status: active project-planning navigation owner
Scope: navigation and responsibility boundaries for game-specific planning stored under `game-planning/`.

## 1. Purpose

This area contains project-local planning meaning, including when justified:

```text
project decisions and decision candidates;
hypotheses and evidence;
project-wide and owner-local Ideas / Variants / Versions;
Content Premises;
Scenario / Spine chronology;
Game Domains;
Situation / Event / Execution / Loop / Dynamic / Scenario detail;
Low-Level Elements inside planning units;
Project Experience / Motivation and other justified player-context detail;
visual / presentation, production or other justified detail owners;
legacy consolidated Game Planning Drafts during migration, when a project already has them.
```

Reusable definitions do not originate here. Stable principles and terminology remain in [`../principles/README.md`](../principles/README.md), and reusable analysis/planning methods remain in [`../game-analysis-reference/README.md`](../game-analysis-reference/README.md).

Use [`../game-planning-use-case-map.md`](../game-planning-use-case-map.md) to find the practical read route, [`../game-creation-workflow.md`](../game-creation-workflow.md) for zero-to-one synthesis, [`../game-development-planning-workflow.md`](../game-development-planning-workflow.md) for broad ongoing orchestration, [`../game-planning-spine-workflow.md`](../game-planning-spine-workflow.md) for Scenario/Spine-centered planning, and [`../low-level-element-planning-workflow.md`](../low-level-element-planning-workflow.md) for smaller-than-unit Idea work.

## 2. Current Projects

| Project | Entry point | Current navigation note |
|---|---|---|
| [`Survivor Base`](survivor-base/README.md) | [`survivor-base/README.md`](survivor-base/README.md) | Legacy consolidated Draft is still consulted as a migration/source artifact while Scenario/Spine and reusable owners are developed |

## 3. Target Project Ownership Pattern

Use the smallest structure that keeps ownership and review clear.

```text
project README
  → navigation, current depth, authority/status notes
    and migration/source notes;

Scenario / Spine owner(s)
  → one selected concrete chronology / run manifestations;

named reusable planning owners, when independently useful
  → Situation / Event / Execution / Loop / Dynamic /
    Game Domain / Project Experience / Motivation /
    candidate Promise/Doubt / other reusable possibility-space;

Low-Level Elements inside an owner
  → smaller design concerns that remain parent detail
    unless independent responsibility emerges;

project-level or owner-local ideas/
  → cross-cutting, unrouted or owner-scoped exploration when useful;

owner-local Variants / Versions
  → alternative designs and contextual/configurational forms
    scoped to the responsibility where they are true;

Content-Premise workspace, when justified
  → concrete candidate content units before
    detailed Scenario chronology;

justified visual / presentation / production detail owners
  → independently useful accepted or exploratory detail
    with its own review/change responsibility;

research / prototypes / tests / evidence
  → feed reviewed meaning back into the affected real owners;

legacy consolidated Game Planning Draft, only when a project already has one
  → migration/source/provenance aid while responsibilities are routed.
```

The target architecture does **not** require one permanent monolithic Draft.

### Concrete Scenario Versus Reusable Unit

Illustrative high-level example:

```text
Spine:
  newcomer arrives with uncertain infection status
  → restricted admission is selected
  → controlled work begins.

Reusable Situation owner:
  Admission Under Uncertain Risk
  → multiple entry paths;
  → broader option space;
  → different consequences;
  → Variants / Versions when useful.
```

The concrete occurrence stays in the Spine. The reusable owner expands what one selected run cannot exhaustively contain.

A planning unit may remain one file while simple. Turn it into a folder only when independent review, navigation, reuse, research, testing, collaboration, scoped Ideas/Variants/Versions, production ownership or change tracking makes local structure useful.

Do not pre-create empty folders merely to mirror a possible ontology.
## 4. Scoped Ideas And Low-Level Elements

`ideas/` is a reusable **exploration mechanism**, not one special project-wide gameplay scale.

A `Low-Level Element` is a meaningful design concern smaller than the whole planning unit. It normally remains detail inside that owner. When it needs scoped exploration, use [`../low-level-element-planning-workflow.md`](../low-level-element-planning-workflow.md) and the normal Idea methodology rather than creating another unit automatically.

Example:

```text
Situation:
  Admission Under Uncertain Risk

Low-Level Element:
  exact meaning of restricted admission.
```

An Idea workspace may live beside the owner whose unresolved question it serves:

```text
project/ideas/
Domain/ideas/
Situation/ideas/
Variant/ideas/
Version/ideas/
Loop/ideas/
Dynamic/ideas/
Scenario/ideas/
Experience/ideas/
Motivation/ideas/
Experience-Promise/ideas/
Doubt/ideas/
Execution/ideas/
...
```

Keep one primary workspace/home for one planning question. Use links, relations or categories for cross-cutting relevance rather than maintaining divergent physical copies of the same question.

Place the workspace at the highest scope where its question remains genuinely shared. Specialize lower only when the meaning differs:

```text
shared across a Situation family
  → Situation-level ideas/;

specific to one whole-unit design Variant
  → Variant-level ideas/;

specific to one contextual Version of the current entity/design
  → Version-level ideas/.
```

Ideas may be grouped into semantic categories derived from the current owner's meaningful components or reusable analysis surfaces, for example record concerns, analysis, Experience, Visual, Balance or Production. Materialize only categories that simplify planning.

The exact category tree is project- and owner-specific. This repository does **not** require `ideas/record/...` or any other universal nesting scheme.

A typed temporal change or one record field inside a Scenario/Situation (state changed, information changed, Motivation changed, Execution progressed, one option, one information rule, etc.) is **not automatically a planning-unit owner**. Create a separate owner only when independent review, reuse, research, testing or change responsibility justifies it.

## 5. Variants And Versions

Keep Idea-level and whole-unit alternatives distinguishable:

```text
Idea Variant
  → one candidate answer to one scoped question/problem;

Planning Unit Variant
  → an integrated alternative design of the whole planning unit/entity.
```

A whole-unit Variant can combine several local Idea Variants. When broader integration is material, create/use the real candidate planning unit at the relevant scale instead of a separate `PROBE-*` artifact family.

Across planning entities, use the contextual/configurational `Version` distinction when it is materially useful:

```text
Variant
  → alternative integrated design;

Version
  → complete materially different reusable context/configuration
    of the same entity/design;

Document Revision
  → edit/revision history of the document, not a design Version.
```

Not every entity needs Variants or Versions.

For `Gameplay Situation`, also preserve the `Variant / Version / Instance` application owned by gameplay terminology:

```text
Situation Variant
  → alternative design;

Situation Version
  → full Situation record for one materially different
    reusable context/configuration of that design;

Situation Instance
  → one concrete occurrence in a Scenario/playthrough.
```

A Version is a complete contextual record, not merely a delta against an obligatory main file.

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

The same general `Version = contextual/configurational form of the same design` distinction may be used at other planning scales. Each detailed method remains responsible for how Version is represented at its own scale.

### Scoped Child Work

When several Variants/Versions coexist, lower-level work stays scoped to the narrowest context where its meaning is true:

```text
shared across whole entity
  → entity-level Ideas/elements;

specific to Variant A
  → Variant A-local work;

specific to Version X of Variant A
  → that Version-local work.
```

Do not silently promote Variant/Version-specific meaning upward. Physical folder structure remains proportional.
## 6. Project-Specific Categories

Project-specific Situation grouping should support **many-to-many navigation** when one Situation belongs to several meaningful concerns.

Prefer category/link navigation over forcing every Situation into one physical category parent. The actual project taxonomy and whether any category also affects physical hierarchy remain project-specific decisions.

## 7. Authority, Status And Promotion Boundary

Project-local exploratory files may be **current working artifacts** without being accepted project meaning.

Authority and content status are separate questions:

```text
Where does this meaning belong?
  → owner / authority;

How established is it?
  → confirmed / inference / preliminary / candidate / open / etc.
```

Example:

```text
scenarios.md
  = project-local Scenario owner;

Scenario X inside it
  = may still be a working representative Scenario.

Owner ≠ accepted meaning.
```

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
  ≠ a second canonical body.
```

When an explicit accepted decision changes reusable/project meaning, reconcile it into the appropriate real owner(s). Do not force every accepted cross-cutting change through a permanent Game Planning Draft.

Accepted reusable visual/presentation realization should move from a local exploratory Idea workspace into the appropriate project visual/presentation owner when such independent ownership is useful; the originating gameplay owner keeps the requirement/relation rather than becoming a duplicate presentation owner.

Project-local files may summarize or apply reusable terminology, but they do not silently redefine it.

### Legacy Draft Migration Boundary

A project that already has a consolidated Game Planning Draft may keep consulting it while moving toward Scenario/Spine + reusable-owner architecture.

```text
legacy Draft
→ existing source/status/provenance
→ consult while constructing Spine and reusable owners
→ preserve still-unrouted meaning
→ stop treating it as the permanent integration center
  once responsibility has moved.
```

Do not require every newly clarified owner-local decision to be back-written into the Draft. Back-writing is needed only when explicit migration compatibility/provenance responsibility requires it.

Do not remove the legacy source merely because target ownership is clearer; migration/removal needs its own completeness check.

## 8. Do Not

- Do not treat project-local ownership as acceptance status.
- Do not require a permanent Game Planning Draft in the target architecture.
- Do not remove a legacy Draft before its still-useful meaning/provenance is safely routed.
- Do not make every Low-Level Element a separate unit/file.
- Do not use `Version` as another word for `Variant` or document revision.
- Do not require every entity to have Variants/Versions.
- Do not pre-create folders for every theoretical unit/entity.
- Do not duplicate reusable terminology inside project files.
