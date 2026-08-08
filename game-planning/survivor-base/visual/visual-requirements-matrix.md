# Survivor Base — Visual Requirements Matrix

**Status:** active project-local working requirements view\
**Canonical project source:** [`../game-planning-draft.md`](../game-planning-draft.md)\
**Gameplay-loop view:** [`../views/gameplay-loop-scenario.md`](../views/gameplay-loop-scenario.md)\
**Reusable visual method:** [`../../../game-analysis-reference/visual-design-analysis-and-planning.md`](../../../game-analysis-reference/visual-design-analysis-and-planning.md)

## 1. Purpose And Authority Boundary

This file asks:

> What must the visual system be able to communicate, preserve or make the player perceive throughout the current Survivor Base gameplay loop?

It does not choose the final art style. It does not convert a reference into a literal implementation. It does not override Planning Items.

Requirements use project-local IDs (`SB-VR-*`). Reusable `V01–V11` labels are analysis tags only.

The matrix may add original project/situation/element-specific concerns when the reusable lenses are insufficient.

## 2. Current Source Skeleton

The current loop view organizes play approximately as:

```text
read operating state
→ notice a problem / opportunity / information gap
→ gather or interpret information
→ make a plan
→ commit people / space / resources
→ let the living system execute
→ encounter a trade-off / exception / crisis
→ intervene
→ pay and read consequences
→ recover / update
→ enter a changed state.
```

The visual plan therefore needs to work across routine, uncertainty, preparation, boundary control, exploration, emergency, tactical contact and recovery — not only during attacks.

## 3. Working Situation Map

These are derived planning situations, not immutable game taxonomy.

| ID | Situation | Current role in visual planning |
|---|---|---|
| `S01` | Routine / living operational base | Establish the normal readable state against which crisis has meaning |
| `S02` | Information gap / suspicious state | Show uncertainty and evidence without replacing hidden truth with omniscient markers |
| `S03` | Planning / preparation / configuration | Let the player inspect and alter intended routes, roles, zones, rules and contingencies |
| `S04` | Boundary / intake / controlled transfer | Make physical and procedural crossings legible for people and objects |
| `S05` | Local unknown / physical exploration | Distinguish genuinely unverified local space from already-known facility space |
| `S06` | Alarm / emergency / containment response | Transform a familiar workplace under partial report, rapid decisions and containment pressure |
| `S07` | Direct tactical contact | Support small-squad movement, thresholds, threat contact and retreat without becoming a separate visual game |
| `S08` | Aftermath / contamination / recovery / reclaim | Make consequences, closure, sanitation, repair and reopening visually persistent |
| `S09` | External operation / regional pressure | Contrast controlled facility scale with outside uncertainty, expeditions and larger infected pressure |

## 4. Coverage Summary

Legend: `●` load-bearing, `○` useful/secondary, `?` currently unresolved, `—` not currently a planning focus.

| Situation | V01 | V02 | V03 | V04 | V05 | V06 | V07 | V08 | V09 | V10 | V11 |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| `S01` Routine | ○ | ● | ● | ● | ● | ● | ● | ● | ○ | ● | ● |
| `S02` Information gap | ○ | ● | ● | ○ | ○ | ○ | ● | ○ | ○ | ● | ○ |
| `S03` Planning | ○ | ○ | ● | ● | ○ | ○ | ○ | ○ | ○ | ● | ○ |
| `S04` Boundary | ○ | ● | ● | ● | ● | ● | ● | ● | ● | ● | ● |
| `S05` Local unknown | ○ | ● | ● | ● | ● | ○ | ● | ● | ● | ● | ○ |
| `S06` Emergency | ● | ● | ● | ● | ● | ● | ● | ● | ● | ● | ● |
| `S07` Tactical contact | ○ | ● | ● | ● | ● | ○ | ● | ○ | ● | ● | ● |
| `S08` Aftermath | ○ | ● | ● | ● | ○ | ● | ● | ● | ○ | ● | ● |
| `S09` External | ● | ● | ● | ● | ? | ? | ● | ? | ○ | ● | ● |

The table is only a routing view. It is not evidence that every marked cell needs a separate requirement.

## 5. Project-Specific Cross-Cutting Concerns

These concerns are useful for Survivor Base even though none should automatically become a new universal `V12+` category.

### `SB-PC-01` — Same-Map Continuity

The same physical base should remain recognizably the same place through:

```text
routine
→ uncertain report
→ alarm
→ response
→ aftermath
→ sanitation / repair
→ reopen.
```

A crisis state should transform a known workplace rather than swap to an unrelated battle-board representation.

**Scope:** project-wide, especially `S01`, `S06`, `S08`.

### `SB-PC-02` — Threshold Grammar

Doors, checkpoints, shutters, breaches and other thresholds are unusually load-bearing because containment, routing, access, tactical control and emergency response all depend on them.

Threshold states may need more visual grammar than an ordinary environment prop family.

**Scope:** project-wide / element-specific.

### `SB-PC-03` — Known Space Vs Genuinely Unknown Space

Local darkness and incomplete information must not arbitrarily erase the player's established knowledge of the base. Genuinely unverified rooms or outside spaces may justify stronger uncertainty.

**Scope:** `S01`, `S05`, `S06`, `S09`.

### `SB-PC-04` — Threat Scale Separation

A fresh individual infection/breach and a distant old infected mass or horde pressure are different information scales. Their representation should not collapse into one generic red-danger language.

**Scope:** `S02`, `S06`, `S07`, `S09`.

### `SB-PC-05` — Material Consequence And Recovery

Violence, contamination, closure, cleanup and reclaim should leave readable physical traces. Resolution is not complete merely because an enemy disappears.

**Scope:** `S06`, `S07`, `S08`.

## 6. Detailed Requirements

### `SB-VR-001` — Routine Base Must Read As A Working Place

**Situation:** `S01`\
**Element:** whole facility + people + work objects\
**Status:** inference / working requirement

**Requirement:** The normal base view must read as a populated working facility in which people, routes, rooms, jobs and physical objects matter, not as an empty schematic board waiting for an alarm.

**Required perception / experience:** operational calm, ownership of a living system, enough ordinary life that later disruption has contrast.

**Reusable lenses:** `V02`, `V03`, `V04`, `V05`, `V08`, `V09`, `V11`.

**Project-specific concern:** `SB-PC-01`.

**Risk / anti-requirement:** a diagrammatic representation can become too empty or abstract to support attachment, material consequence or readable daily activity.

**Representative check:** one ordinary sector with expected people, furniture/workstations, carried objects and movement should remain readable without relying on a crisis overlay.

### `SB-VR-002` — Normal Operation Must Establish The Visual Baseline

**Situation:** `S01`\
**Element:** whole screen state\
**Status:** inference / working requirement

**Requirement:** Routine state needs a stable value, lighting and information baseline so alarm, blackout, contamination and closure can be perceived as meaningful changes rather than permanent visual noise.

**Reusable lenses:** `V02`, `V06`, `V07`, `V10`.

**Risk / anti-requirement:** if normal play already uses maximum alarm contrast, later escalation has nowhere to go.

### `SB-VR-003` — People Must Remain Individually Operable At Population Scale

**Situation:** `S01`, `S03`, `S06`\
**Element:** people\
**Status:** inference / working requirement

**Requirement:** At the intended base population scale, the player should be able to locate and distinguish relevant individuals, current activity and exceptional states without permanent large labels covering the physical space.

**Reusable lenses:** `V03`, `V04`, `V05`, `V09`, `V10`, `V11`.

**Open detail:** exact target crowd size for the first representative visual test should follow the current gameplay scope rather than be invented here.

### `SB-VR-004` — Uncertainty Must Show Knowledge State, Not Hidden Truth

**Situation:** `S02`\
**Element:** person / report / disease evidence\
**Status:** source-backed direction + working visual requirement

**Requirement:** Visual presentation must distinguish what is observed, inferred, reported, scientifically assessed or unknown without exposing infection truth simply because the engine knows it.

**Required perception / experience:** uncertainty that supports reasoning rather than arbitrary opacity.

**Reusable lenses:** `V02`, `V03`, `V10`.

**Risk / anti-requirement:** an omniscient infected-marker would collapse the evidence and policy game into direct truth reading.

**Reference cue:** a "procedural evidence console" may be a useful responsibility; no literal visual style is selected.

### `SB-VR-005` — Evidence UI Must Preserve Source And Confidence

**Situation:** `S02`, `S03`\
**Element:** evidence / dossier / expert assessment\
**Status:** source-backed direction + working visual requirement

**Requirement:** When the player inspects disease or person evidence, the interface should make it possible to understand what is known, why it is believed and what remains uncertain. Scientific assessment, leadership assumption and policy should remain distinguishable layers.

**Reusable lenses:** `V02`, `V03`, `V10`.

**Reference cue:** the current draft's "working epidemiologist board" / strain evidence direction is a source-backed cue, not a final UI specification.

### `SB-VR-006` — Planning View Must Connect Intention To Physical Space

**Situation:** `S03`\
**Element:** zones / routes / staffing / rules / contingency\
**Status:** inference / working requirement

**Requirement:** Planning overlays should make intended routes, permissions, zones, staffing and emergency preparations legible while preserving the underlying room/door geometry they act upon.

**Reusable lenses:** `V03`, `V04`, `V10`.

**Project-specific concern:** `SB-PC-01`, `SB-PC-02`.

**Risk / anti-requirement:** a detached spreadsheet/policy screen can make physical containment feel abstract.

### `SB-VR-007` — Boundary State Must Be Readable Before Text Inspection

**Situation:** `S04`, `S06`, `S07`\
**Element:** door / checkpoint / sluice / threshold\
**Status:** inference / working requirement

**Requirement:** A load-bearing threshold should communicate its important physical state at gameplay scale before the player opens a detail panel.

Potential states may include open, closed, locked, sealed, jammed, broken, held, blocked or breached, but this file does not freeze a final enum.

**Reusable lenses:** `V03`, `V05`, `V06`, `V09`, `V10`.

**Project-specific concern:** `SB-PC-02`.

**Risk / anti-requirement:** encoding all threshold meaning only by color or tiny icons.

### `SB-VR-008` — Intake And Transfer Must Read As A Physical Process

**Situation:** `S04`\
**Element:** people + objects + waiting/inspection/decon space\
**Status:** inference / working requirement

**Requirement:** Intake and cross-zone transfer should visually read as people and objects moving through real constrained space and procedures, not as an abstract accept/reject popup detached from contamination logic.

**Required perception / experience:** operational responsibility and cost of safe movement.

**Reusable lenses:** `V02`, `V03`, `V04`, `V08`, `V09`, `V10`, `V11`.

### `SB-VR-009` — Unknown Space Must Be Local And Physical

**Situation:** `S05`\
**Element:** unexplored room / corridor / doorway\
**Status:** source-backed direction + working visual requirement

**Requirement:** Information hiding in unexplored facility space should arise from local darkness, blocked view, closed thresholds, incomplete sensors or similar physical causes. It should not behave as arbitrary fog covering already-known normal base geometry.

**Reusable lenses:** `V02`, `V03`, `V04`, `V07`, `V10`.

**Project-specific concern:** `SB-PC-03`.

**Directional reference cue:** a Duskers-like sense of remote procedural uncertainty may be explored for experience responsibility without copying its terminal-green identity or exact UI.

### `SB-VR-010` — Alarm Starts From A Partial Report

**Situation:** `S06`\
**Element:** alarm/report layer\
**Status:** source-backed direction + working visual requirement

**Requirement:** The first alarm state should communicate that something meaningful happened, where the report or signal came from and how certain it is, without immediately resolving the unknown into a precise enemy marker.

**Reusable lenses:** `V02`, `V03`, `V06`, `V09`, `V10`.

**Risk / anti-requirement:** dramatic alarm treatment that gives the player more truth than the fictional information system possesses.

### `SB-VR-011` — Emergency Must Transform The Same Familiar Sector

**Situation:** `S06`\
**Element:** whole sector\
**Status:** explicit project visual-planning requirement from current discussion

**Requirement:** A familiar working sector should remain spatially and materially recognizable through alarm and response. Crisis treatment may change light, overlays, occupancy, damage and motion, but should not replace the underlying place with a separate tactical-board identity.

**Reusable lenses:** `V02`, `V04`, `V06`, `V07`, `V08`, `V09`, `V10`, `V11`.

**Project-specific concern:** `SB-PC-01`.

**Representative check:** compare the same sector in routine → uncertain report → alarm → response → aftermath → reopen.

### `SB-VR-012` — Emergency Attention Hierarchy Must Support Rapid Decisions

**Situation:** `S06`\
**Element:** people / route / threshold / threat report / response group\
**Status:** inference / working requirement

**Requirement:** Under alarm pressure, the visual hierarchy should prioritize the current source/uncertainty, affected people, usable or blocked routes, threshold state and available response without turning the whole screen into equal-intensity warning color.

**Reusable lenses:** `V03`, `V06`, `V07`, `V09`, `V10`.

### `SB-VR-013` — Tactical Control Reuses The World's Visual Grammar

**Situation:** `S07`\
**Element:** response squad / raid squad / doors / cover / threats\
**Status:** source-backed direction + working visual requirement

**Requirement:** Direct tactical control should reuse the same physical space, thresholds and command meanings used elsewhere rather than introducing a visually unrelated combat mode.

**Reusable lenses:** `V02`, `V03`, `V04`, `V05`, `V09`, `V10`, `V11`.

**Reference cue:** Door Kickers-like spatial command clarity may be studied for a narrow responsibility; police-operation identity and exact UI are not implied transfers.

### `SB-VR-014` — Tactical Readability Must Not Erase Material Life

**Situation:** `S07`\
**Element:** room / furniture / props / people\
**Status:** inference / working requirement

**Requirement:** Tactical readability should simplify emphasis, not remove the physical objects whose obstruction, contamination, cover, work function or aftermath make the facility a living place.

**Reusable lenses:** `V03`, `V04`, `V05`, `V08`, `V11`.

### `SB-VR-015` — Aftermath Must Persist After The Threat Ends

**Situation:** `S08`\
**Element:** blood / damaged threshold / body / dirty objects / closed room / cleanup activity\
**Status:** source-backed direction + working visual requirement

**Requirement:** The screen should continue to show important physical consequences after immediate danger ends so sanitation, repair, closure and reclaim have visible meaning.

**Reusable lenses:** `V02`, `V03`, `V06`, `V08`, `V09`, `V10`, `V11`.

**Project-specific concern:** `SB-PC-05`.

**Risk / anti-requirement:** reset-to-clean visuals that make recovery feel like menu bookkeeping.

### `SB-VR-016` — Reopening Should Read As Regained Function, Not Cosmetic Cleanup

**Situation:** `S08`\
**Element:** room / route / work function\
**Status:** inference / working requirement

**Requirement:** Recovery/reclaim should visually communicate that a previously compromised part of the facility is usable again, while allowing persistent scars or changed organization to preserve history.

**Reusable lenses:** `V02`, `V03`, `V08`, `V09`.

**Project-specific concern:** `SB-PC-01`, `SB-PC-05`.

### `SB-VR-017` — Outside Scale Must Contrast With Facility Control

**Situation:** `S09`\
**Element:** external route / target / regional threat\
**Status:** inference / working requirement

**Requirement:** External operations should communicate less-controlled space and larger uncertainty while remaining legible as part of the same game and command language.

**Reusable lenses:** `V01`, `V02`, `V03`, `V04`, `V07`, `V10`, `V11`.

**Project-specific concern:** `SB-PC-03`, `SB-PC-04`.

**Open:** exact world-map / local-map representation is not selected here.

### `SB-VR-018` — Individual Threat And Distant Horde Pressure Need Different Signals

**Situation:** `S06`, `S07`, `S09`\
**Element:** infected individual / distant mass pressure\
**Status:** inference / working requirement

**Requirement:** Visual treatment should help distinguish a local individual-scale acute threat from distant aggregate pressure. The distinction should support different decisions rather than only different enemy counts.

**Reusable lenses:** `V02`, `V03`, `V04`, `V06`, `V09`, `V10`.

**Project-specific concern:** `SB-PC-04`.

### `SB-VR-019` — Market Screenshot Must Show The Actual Game's Difference

**Situation:** cross-cutting / store first look\
**Element:** representative gameplay frame\
**Status:** inference / working requirement

**Requirement:** A representative screenshot should be legible as a colony/base-management survival game while also showing the game's distinctive focus on physical containment, uncertainty/evidence and operational crisis rather than looking like a direct visual copy of a neighboring title.

**Reusable lenses:** `V01`, `V02`, `V03`, `V11`.

**Risk / anti-requirement:** choosing a same-genre reference whose visible identity becomes the entire store comparison.

### `SB-VR-020` — Visual Direction Must Be Sustainable Across All States

**Situation:** all\
**Element:** asset system\
**Status:** source-backed production principle + project requirement

**Requirement:** The selected visual language must support routine, crowd state, boundaries, local darkness, alarms, direct tactical contact, contamination and recovery without requiring bespoke high-detail art for every state.

**Reusable lenses:** `V11`, with dependencies on all other lenses.

**Representative check:** produce or mock one small reusable asset family and the same representative sector across multiple states before treating a style frame as canonical.

## 7. Directional Reference Cues — Not Realization Decisions

The following cues are useful because they name a desired function or comparison. They do not select a final art direction.

| Cue | Possible responsibility | Explicit non-transfer boundary |
|---|---|---|
| `Duskers` | Remote procedural tension; value of sparse signals and incomplete information | Not automatic terminal-green palette, drone fantasy, exact UI or control scheme |
| `Door Kickers` | Tactical spatial clarity and readable command/threshold relations | Not police-operation identity or exact visual UI |
| `Project Zomboid` | Genre/comparison context; physical world and survival legibility; production comparison | Not target visual identity |
| `RimWorld` / `Prison Architect` | Dense-agent/base readability and cheap systemic asset language | Not automatic character/environment style |
| institutional / civil-defense / medical operational references | Material language, information hierarchy, facility function, preparedness | Must be transformed into coherent game presentation rather than copied as a literal real-world dashboard |

References should later be supported by inspectable source images and explicit transfer notes before they become realization evidence.

## 8. Open Questions For The Next Pass

- What existing game, film, interface or real environment best matches the imagined **normal gameplay frame**, and what exactly should be preserved or rejected from it?
- What camera/scale can show enough physical room detail while supporting the intended population and tactical readability?
- What is the minimum visual representation of a person that supports identity, activity, equipment and exceptional state at gameplay scale?
- How much furniture/prop density is required for a sector to feel physically real without hiding routes and thresholds?
- What visual changes between routine, alarm and aftermath can be produced mostly from reusable state layers rather than duplicate environment art?
- Which parts of the desired "operational facility" vibe are actually visual, and which should be carried by audio, pacing, reporting or command behavior?

These questions are not automatically separate files. The next deep owner should be selected only after one becomes load-bearing enough for independent reference research or realization comparison.

## 9. Current Next Visual Depth

The first realization pass should probably use `S01 Routine / living operational base` as the anchor and compare the **same representative sector** across later states rather than starting from an isolated moodboard.

That pass should test at least:

```text
camera / scale;
people readability;
physical furniture / prop density;
threshold readability;
normal value and light baseline;
production affordability;
continuity into alarm and aftermath.
```

This is a working next-depth recommendation, not an accepted final realization.
