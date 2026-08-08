# Survivor Base — Game Building Blocks Working View

**Status:** derived structural working view\
**Canonical source:** [`../game-planning-draft.md`](../game-planning-draft.md)\
**Authority boundary:** the block map below is an analytical decomposition of current Planning Items. It is not a new category system and does not reclassify repository files.

## 1. Source skeleton

The imported draft already contains a cross-system picture whose main causal shape is:

```text
PHYSICAL BASE
  → PEOPLE / OBJECTS / INFORMATION
  → RULES / PRODUCTION
  → DECISIONS
  → CONSEQUENCES
  → NEW OBSERVATIONS
  → NEW KNOWLEDGE
  → NEW RULES AND A CHANGED BASE
```

The draft then adds explicit chains for intake, sanitation, security, disease evidence, vectors, tactical raids, exploration and emergency response.

This view expands that source skeleton into a small set of **building blocks** so that the game can be reasoned about above the level of 57 individual Planning Items.

## 2. Candidate block map

The following decomposition is an `inference for review`. A Planning Item may participate in several blocks.

| Block | Main responsibility | Representative Planning Items |
|---|---|---|
| **B1. Facility / spatial containment** | Physical space, rooms, boundaries, doors, routes, refuges, lost/reclaimed sectors | `PI-004–006`, `032`, `041`, `048–050`, `055–057` |
| **B2. People / roles / social order** | Individuals, skills, needs, authority, loyalty, relationships, trust and consequences for people | `PI-011–020`, `033–040`, `042–043`, `046` |
| **B3. Infection / biological state** | Exposure, disease course, carriers/recovered states, infected humans, animals and vectors | `PI-014`, `016`, `021–022`, `030`, `051–053` |
| **B4. Information / evidence / knowledge** | Observations, reports, dossiers, confidence, rumors, scientific evidence and expert assessment | `PI-015`, `018`, `021–022`, `034–038`, `052`, `055–056` |
| **B5. Rules / policies / access** | Player-defined categories, permissions, quarantine compromises, intake decisions, exceptions and enforcement rules | `PI-002–005`, `012–013`, `017`, `020`, `031–032`, `039`, `049–050`, `056–057` |
| **B6. Production / logistics / material state** | Food, water, energy, heat, clothes, tools, medicine, objects, ownership, transfer and sanitation capacity | `PI-002`, `024–033`, `039`, `048–049`, `053` |
| **B7. Security / emergency / tactics** | Armed force, checkpoints, alarms, preparedness, response squads, direct tactical control and rapid containment actions | `PI-008`, `012–013`, `043`, `050–051`, `054–057` |
| **B8. External world / raids / ecology** | Strategic outside layer, expedition targets, outsiders, regional infected pressure and animal/environment reservoirs | `PI-007–008`, `019`, `044`, `047`, `051–053`, `054` |
| **B9. Run goals / progression / capability growth** | Starting configuration, opening pressure, local objectives, usable-territory growth, capability unlocks and unresolved global objective | `PI-040–047`, plus consequences from `PI-006`, `022`, `044` |

Cross-cutting concerns such as visual language, UI/readability, production cost, audience and market position are important but are not treated here as gameplay blocks unless they own operative game state.

## 3. Block records

### B1. Facility / spatial containment

**State / entities**

- rooms and sectors;
- doors, shutters, windows and other physical boundaries;
- normal, dirty/unverified, lost and reclaimed space;
- alternate routes, refuge points and transition points;
- local unexplored physical space.

**Player decisions**

- where to place or reinforce boundaries;
- which routes to keep open or redundant;
- when to lose/close/reclaim a sector;
- where people shelter or evacuate;
- which room/sector to seal and which corridor to preserve.

**Interfaces with other blocks**

```text
facility ↔ rules/access
facility ↔ production/logistics
facility ↔ emergency/tactics
facility ↔ infection/sanitation
facility ↔ information (known vs physically unverified space)
```

**Core design claim:** architecture is not decoration; it should change future containment options.

### B2. People / roles / social order

**State / entities**

- needs and personality;
- skills and claimed/verified experience;
- trust, relationships and rumors;
- authority, armed force and loyalty;
- private property and personal stakes;
- leaders / Command Circle / specialists / ordinary residents.

**Player decisions**

- assign work and responsibility;
- promote or restrict access;
- trust, investigate, isolate or punish;
- decide who receives scarce safety/privilege;
- choose who performs risky work or joins a raid/response group.

**Interfaces**

People are simultaneously labor for **B6**, uncertain biological entities for **B3**, information sources for **B4**, subjects of **B5**, and agents who physically execute **B7** plans.

### B3. Infection / biological state

**State / entities**

- hidden infection/exposure state;
- disease course and uncertainty;
- carrier/recovered/resistant possibilities;
- fresh / conserved / retained-function infected;
- blood, carcasses and contaminated material;
- animal hosts and possible insect/vector states.

**Player decisions**

The player usually should not edit biological truth directly. The main verbs occur through other blocks:

```text
observe / test / infer
→ set policy
→ isolate / admit / treat / use / kill / wait
→ clean / contain / investigate
```

**Boundary:** current-strain scientific truth must remain separate from evidence, expert assessment and leadership policy.

### B4. Information / evidence / knowledge

**State / entities**

- observations and reports;
- source and confidence;
- personnel dossier;
- public/individual knowledge and rumors;
- disease evidence quality;
- expert assessment;
- partial alarms;
- known building plan vs physically unverified current state.

**Player decisions**

- seek more evidence or act now;
- decide which report/person to trust;
- inspect a person/place;
- run an experiment;
- accept or reject expert assessment in policy;
- investigate an alarm with incomplete information.

**Core connection:** this block converts raw world state into actionable but imperfect knowledge. If it becomes either perfect or arbitrary, much of the project's uncertainty value disappears.

### B5. Rules / policies / access

**State / entities**

- zones and categories created by the player;
- access/route permissions;
- work restrictions;
- screening/intake procedures;
- quarantine compromises;
- emergency plans and rapid room/sector orders;
- enforcement expectations.

**Player decisions**

This block is where evidence and risk tolerance become an operating system for the base.

```text
knowledge + current needs
→ policy / permission / procedure
→ physical execution by people in space
→ observable consequences
```

**Boundary:** policy does not automatically rewrite biological truth; expert assessment does not automatically become policy.

### B6. Production / logistics / material state

**State / entities**

- labor coverage;
- food, water, power, heat;
- clothes/textiles/tools/medicine;
- object cleanliness, ownership and history;
- transfer capacity, sanitation supplies and waste/dirty-linen capacity;
- closed livestock and meat-processing concerns.

**Player decisions**

- prioritize critical systems;
- choose safe vs efficient production arrangements;
- reroute when a space closes;
- spend labor/time on cleaning, inspection or redundancy;
- decide whether risky objects/food/people can be used before full processing.

**Core tension:** production pressure is what makes containment choices costly rather than automatic.

### B7. Security / emergency / tactics

**State / entities**

- checkpoints, guard posts, patrols and escort;
- response staffing;
- weapons, visibility, cover and position;
- alarm severity/report state;
- prepared routes/plans and rehearsed familiarity;
- room/sector emergency mode.

**Player decisions**

- prepare before a crisis;
- choose evacuate vs shelter vs seal;
- position a response group;
- investigate/light/lure/open/retreat;
- enforce or deliberately relax a rule;
- reopen only after sufficient control/recovery.

**Core production rule from the draft:** raid squad and base response squad should share one tactical command language.

### B8. External world / raids / ecology

**State / entities**

- strategic map/targets/routes;
- external groups and potential arrivals;
- finite regional infected pool;
- migration/aggregation pressure;
- outside resources/equipment;
- animal/environment reservoirs.

**Player decisions**

- whether/when/where to raid;
- who and what to send;
- how much risk to take before a pressure window closes;
- whether to admit outsiders;
- whether external threat should be fought, avoided, redirected or waited out.

**Outputs back into the base**

```text
loot / people / injuries / contamination / evidence / attention
→ intake
→ production + knowledge + policy + sanitation consequences.
```

### B9. Run goals / progression / capability growth

**State / entities**

- trusted starting core plus generated population;
- usable vs unreclaimed territory;
- visible local capability goals;
- external pressure windows;
- disease-research capability;
- unresolved long-term/global objective.

**Player decisions**

- what capability to pursue next;
- whether to expand safety or take an external opportunity;
- how much readiness to sacrifice for growth;
- which people/systems deserve investment.

**Boundary:** final run objective is still open in v0.12. This block should not invent a victory condition.

## 4. Cross-block causal chains already present in the source

### Intake chain

```text
outside / returning raid
→ configurable transition point
→ inspection / evidence / report
→ admission decision
→ sector / specialist processing / holding / refusal
→ work + observation + future trust/risk
```

Blocks: `B8 → B1/B4/B5 → B2/B3 → B6`.

### Containment-and-recovery chain

```text
fresh outbreak / breach
→ alarm / partial knowledge
→ shelter / evacuate / seal / response
→ combat or isolation outcome
→ blood / bodies / dirty space / closed route
→ sanitation + repair + reassignment
→ controlled reopen / reclaim
```

Blocks: `B3/B4 → B7/B1/B5 → B6 → B1`.

### Learning-and-policy chain

```text
observation / sample / experiment
→ evidence quality
→ expert assessment
→ leadership judgement
→ policy / access rule
→ outcomes / staff reaction / new observations
→ revised knowledge
```

Blocks: `B3 → B4 → B5/B2 → B4`.

### Raid-return chain

```text
strategic target
→ squad preparation
→ direct tactical site
→ loot / injury / contamination / evidence
→ return intake
→ use / quarantine / cleanup / research
```

Blocks: `B8 → B7 → B6/B3/B4 → B5`.

### Preparedness chain

```text
facility layout + policy
→ emergency plan / route A-B / refuge / response positions
→ alarm with imperfect information
→ plan or override
→ actual physical execution
→ success / blocked route / partial failure
→ layout/policy revision
```

Blocks: `B1/B5/B7 → B4 → B2/B7 → B1/B5`.

## 5. What should not be collapsed into one block

- **Disease truth, evidence and policy** are deliberately different layers.
- **Trust, authority, sanitary status and armed force** are different axes.
- **Ordinary base visibility and local unexplored physical space** are different information conditions.
- **Strategic raid preparation and direct tactical site control** are two layers of one outside operation, not mutually exclusive replacements.
- **Threat removal and recovery/sanitation** are different stages.
- **Repository `categories/` and draft `CAT-*` labels** are unrelated systems unless a future explicit migration says otherwise.

## 6. Coverage / gaps

This map is useful if most meaningful gameplay can be explained as interactions among a small number of blocks. It should be revised rather than expanded automatically whenever a new feature appears.

Current gaps that can change the decomposition:

1. exact player-fiction / Command Circle role;
2. exact moment-to-moment time/pause model;
3. exact global/run objective;
4. tactical-control depth;
5. alarm severity/escalation model;
6. first-demo choreography;
7. how much character simulation is required for people to feel like people rather than risk records.

If a future system cannot explain what state it owns, what decisions it creates and which existing block it connects to, that is a signal to question the system before adding another building block.
