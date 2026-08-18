# Survivor Base — Visual Planning

**Status:** active project-local visual planning detail owner\
**Project entry point:** [`../README.md`](../README.md)\
**Legacy source/status context:** [`../game-planning-draft.md`](../game-planning-draft.md)\
**Reusable direction:** [`../../visual/README.md`](../../visual/README.md)\
**Reusable method:** [`../../../game-analysis-reference/visual-design-analysis-and-planning.md`](../../../game-analysis-reference/visual-design-analysis-and-planning.md)\
**Idea workspace:** [`ideas/README.md`](ideas/README.md)

## 1. Responsibility

This directory owns detailed visual-planning work for Survivor Base when visual requirements, realization questions or evidence have independent review/change responsibility.

Current depth begins with requirements rather than an accepted art direction:

```text
Gameplay Situation / Loop or Loop Phase / Scenario or Scenario Beat / Visual Context
  → meaningful elements
  → required perception / target experience
  → reusable visual lenses + Survivor Base-specific concerns
  → visual requirements
  → later realization candidates / references / tests.
```

A `Visual Context` is a project-local visual-planning context that may matter even when no new meaningful Gameplay Situation begins there. Routine operation, system execution, waiting and aftermath can therefore remain valid visual inputs without being promoted into Gameplay Situations.

The visual files do not silently override `CHAT-PI-*` meanings. Accepted visual realization belongs in the appropriate visual owner; when it materially changes gameplay or broader project meaning, update the affected real owner(s). Back-write the legacy Draft only when migration compatibility/provenance responsibility requires it.

## 2. Current Files

| File | Responsibility | Status |
|---|---|---|
| [`visual-requirements-matrix.md`](visual-requirements-matrix.md) | Working visual-context/element requirements and coverage map | Active working owner |
| [`ideas/README.md`](ideas/README.md) | Survivor Base-specific unresolved visual questions / Brainstorm Prompts / Idea Variants | Active exploratory workspace navigation |

## 3. Current Boundary

This directory does **not** yet contain:

- an accepted final art direction;
- a canonical visual frame;
- a final palette;
- a final character/environment rendering style;
- a production asset specification;
- a complete reference bank;
- separate realization-option or test owners.

Those files should appear only when independent review, research, testing or production ownership justifies them.

## 4. Requirements Are Not Limited To Reusable Lenses

The reusable `V01–V11` lenses are prompts, not a closed taxonomy.

Survivor Base may add:

```text
project-wide concerns;
context-specific concerns;
element-specific concerns;
original requirements that have no reusable category yet.
```

Do not distort a real requirement merely to fit it into a reusable category. Mark the local scope and keep the requirement's own `SB-VR-*` identity.

## 5. Reference Boundary

A reference cue may appear directly beside a requirement, including a phrase such as "vibe like X". That does not select a literal realization.

Reference responsibilities may include:

- target experience;
- visual-language function;
- production feasibility;
- market/comparison context.

When realization work begins, preserve what value is being taken, what must not transfer and how the result changes enough to belong to Survivor Base.

## 6. Next Depth Rule

Create a separate file such as `realization-options.md`, `reference-map.md`, `tests.md` or a narrower topic/context owner only after the requirements matrix reveals a load-bearing question with enough independent material to justify that file.
