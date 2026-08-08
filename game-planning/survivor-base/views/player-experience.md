# Survivor Base — Player Experience Working View

**Status:** derived working view\
**Canonical source:** [`../game-planning-draft.md`](../game-planning-draft.md)\
**Authority boundary:** this file reorganizes current source meaning; it does not override `CHAT-PI-*` states or turn an inference into an accepted decision.

## 1. Why this view exists

The draft already labels Planning Items with `CAT-10 — Fun, anti-fun, and risks`, but that category is intentionally broad. In the imported v0.12 set it appears on 54 of 57 Planning Items. It is therefore useful as a cross-cutting warning/review label, but not precise enough to answer:

> What is the player actually supposed to value, enjoy, fear, learn or feel ownership over while playing this game?

The repository's `Player Experience First` owner also distinguishes valuable experience from uninterrupted positive emotion. Tension, uncertainty, pressure, vulnerability and moral discomfort can be part of the intended value when they lead to meaningful agency, learning, relief or consequence.

## 2. Central experience thesis — inference for review

**Status:** `inference`, not accepted project wording.

> **Build and operate a functioning survival/containment system under incomplete information; make consequential plans about people, space and risk; then watch real crises test those plans, learn from the consequences and redesign the system more intelligently.**

A compact form is:

```text
agency / ownership of plan
+ incomplete knowledge
+ consequential tension
+ systemic aftermath
+ learning and adaptation
```

This synthesis is grounded mainly in `CHAT-PI-002–007`, `015–022`, `035–038`, `040–057` and the draft's `Cross-system picture`, but the exact sentence has not been explicitly accepted by the user.

### Essential-experience candidate

**Decision candidate:** the smallest value worth protecting may be:

> **I make a plan for a living base under uncertainty, and the world gives me legible reasons to feel that the result was meaningfully caused by my plan — including when the plan fails.**

The important word is **legible**. If outcomes feel arbitrary, the same infection uncertainty that should create tension destroys agency and mastery instead.

## 3. Experience-family map

| Experience family | Current project expression | Main source Planning Items | Current status |
|---|---|---|---|
| **Autonomy / agency** | Create zones, access rules, routes, intake decisions, emergency plans and tactical responses; choose how much risk to accept instead of following one universal safe answer | `PI-002–006`, `017`, `020`, `031–033`, `039`, `049–050`, `054`, `056–057` | Strong source-backed direction; delivered experience untested |
| **Challenge / tension / relief** | Valuable specialist vs infection risk; time windows; partial alarms; breaches; raids; containment decisions; recovery after acute events | `PI-002`, `006–008`, `019–020`, `044`, `047`, `051`, `054–057` | Strong source-backed direction; exact pacing untested |
| **Curiosity / discovery** | Uncertain people, disease evidence, hidden motives/skills, local unexplored space, unknown breach/source, current-strain host/vector questions | `PI-015`, `021–022`, `034–038`, `051–055` | Strong source-backed direction; information density risk remains |
| **Competence / mastery** | Learn better zoning, staffing, evidence interpretation, sanitation, emergency preparation, tactical positioning and recovery; revise systems after readable failures | `PI-005–006`, `017`, `021–022`, `024–033`, `040–050`, `054–057` | Strong inference from repeated adaptation loops; needs prototype evidence |
| **Fantasy / embodiment** | Act as the operational leadership of a functioning human base whose decisions connect disease knowledge, production, security and spatial containment | `PI-001`, `011–020`, `040–046` | Direction exists; exact player-fiction / Command Circle relationship remains open |
| **Meaning / empathy / reflection** | Decide who is admitted, isolated, armed, sacrificed, trusted or denied; consequences persist in people, social order and space | `PI-004`, `006`, `011–020`, `029`, `038–046`, `049` | Source-backed decision space; emotional delivery untested |
| **Expression / creativity** | Design a working spatial/social operating system rather than decorate a base: player-defined zones, boundaries, routes, policies and contingency plans | `PI-003–006`, `017`, `031–032`, `049–050`, `056–057` | Source-backed systemic direction; risk of one dominant layout must be tested |
| **Sensation** | Tactical movement, lighting, alarm feedback, weapon/impact feel, sound and readable emergency-state changes could provide immediate feel | `PI-023`, `051`, `054–057` | **Underdefined.** Current draft does not yet justify a strong sensory-pleasure claim |
| **Fellowship / relatedness** | Attachment to recurring survivors, trust networks and the sense of maintaining a community may support relatedness | `PI-011–020`, `034–038`, `042–046` | Possible single-player relational value; not yet specified as a central experience family |
| **Competition / status** | No clear current core | — | Not a current experience target in the imported draft |

## 4. Load-bearing causal hypotheses

These records deliberately keep mechanics, dynamics, behavior and experience separate.

### PX-H1 — Quarantine is a real trade-off, not an automatic answer

**Supporting source:** `PI-002`, `003`, `016`, `017`, `024`, `031`.

```text
Mechanics / rules:
  suspicious or risky people remain operationally valuable;
  isolation consumes labor, space, guards and supply;
  intermediate access/work modes exist.

Expected dynamics:
  risk cannot be minimized independently of production;
  different people and sectors produce different acceptable compromises.

Expected player behavior:
  compare operational need with infection evidence;
  create limited routes/work cells/temporary permissions;
  accept some risk deliberately.

Target experience:
  agency + consequential tension.

Failure mode:
  one always-correct quarantine threshold or unreadable infection randomness.
```

### PX-H2 — The player's own architecture becomes a preparedness system

**Supporting source:** `PI-005`, `006`, `048`, `050`, `056`, `057`.

```text
Mechanics / rules:
  doors, boundaries, alternate routes, refuges, guards and emergency plans are physical constraints.

Expected dynamics:
  earlier layout decisions change what is possible during a crisis.

Expected player behavior:
  prepare fallback routes;
  protect key boundaries;
  later explain a success/failure through earlier planning.

Target experience:
  ownership of plan + mastery + relief after containment.

Failure mode:
  generic door-HP combat, magic sealing, or emergency buttons that ignore actual geometry.
```

### PX-H3 — Incomplete information produces hypotheses, not blind guessing

**Supporting source:** `PI-015`, `018`, `021`, `035–038`, `052`, `055–056`.

```text
Mechanics / rules:
  reports have sources/confidence;
  people and disease states are not perfectly known;
  local unexplored space can conceal real physical facts;
  alarms may be partial.

Expected dynamics:
  evidence accumulates and changes the value of actions.

Expected player behavior:
  seek corroboration;
  inspect dossiers/evidence;
  investigate space carefully;
  revise a prior belief.

Target experience:
  curiosity + tension + competence.

Failure mode:
  information noise, perfect omniscience, or invisible punishment with no usable clues.
```

### PX-H4 — Crisis is followed by aftermath, not a reset

**Supporting source:** `PI-006`, `030`, `048`, `051`, `053`, `057`.

```text
Mechanics / rules:
  blood, bodies, contamination, closed routes, injuries and lost rooms persist after danger is removed.

Expected dynamics:
  tactical victory can create operational damage;
  recovery competes with ongoing production.

Expected player behavior:
  sanitize, reroute, reassign and decide whether/when to reopen space.

Target experience:
  consequence + recovery + mastery.

Failure mode:
  combat ends with the last enemy and the base instantly returns to normal.
```

### PX-H5 — The same control language connects base and raids

**Supporting source:** `PI-007`, `044`, `054`, `055`.

```text
Mechanics / rules:
  raid squad and base response reuse move/hold/watch/door/light/lure/retreat/carry concepts.

Expected dynamics:
  skills learned in one context transfer to another;
  raid intensity does not create a separate second game.

Expected player behavior:
  apply spatial/containment reasoning outside and inside the base.

Target experience:
  competence + coherent role/fantasy + tactical tension.

Failure mode:
  raid becomes a separate RTS/shooter or base response remains abstract and unrelated.
```

## 5. Experience by level

### Moment-to-moment

Current source supports recurring perception/decision moments such as:

- identify a boundary or route that matters;
- read a report, dossier or risk signal;
- choose an admission/access/containment action;
- position a small tactical group;
- inspect or light an uncertain area;
- observe immediate physical/system feedback.

**Open:** exact input feel, pause/time model, tactical responsiveness and audiovisual impact.

### Decision level

This is currently the best-specified experience level.

Repeated decisions should create conflicts such as:

```text
safety vs labor;
evidence vs urgency;
individual value vs group risk;
open route vs containment;
evacuation vs shelter;
short-term output vs preparedness;
known specialist vs unknown newcomer;
raid opportunity vs approaching external pressure.
```

### Session level

**Inference:** a session/day should tend to move between routine operation, mounting uncertainty or opportunity, a significant decision/crisis, consequence/recovery and a newly changed planning state.

The imported draft explicitly defers the exact final core/session-loop formulation until tactical, unexplored-space, alarm and opening passes stabilize further.

### Long-term

Current source points toward mastery through:

- better operating rules;
- larger/more reliable usable territory;
- improved people knowledge and specialist development;
- stronger disease evidence;
- capability unlocks;
- better prepared containment/security structures.

The exact final run objective is still open.

## 6. Anti-experience gates

The canonical draft contains a 58-point anti-fun / production-risk audit. This view groups the most experience-critical failure modes rather than duplicating that section.

| Intended value | Main anti-experience risk |
|---|---|
| Agency | Quarantine or one layout becomes always optimal; consequences could not have been predicted |
| Tension | Random punishment, alarm spam, permanent crisis fatigue, or stakes with no meaningful control |
| Curiosity | Noise without clues; every unknown is arbitrary; or evidence becomes perfect immediately |
| Mastery | Failure cannot be explained; simulation rules shift invisibly; progress is only numeric |
| Meaning | Moral choices are predetermined or people become disposable resource tokens |
| Expression | Configurable zones/policies are cosmetic because one meta solution dominates |
| Tactical feel | Manual micro replaces decisions, or tactical mode becomes a separate expensive game |
| Containment | Magic sector seal / generic door HP erase spatial reasoning |
| Preparedness | Emergency plans become autopilot and drills become chores |
| Role fantasy | Base management collapses into spreadsheet bureaucracy or zombie combat overwhelms operating a community |

## 7. Evidence status

No playtest evidence in the imported v0.12 source proves that these intended experiences are delivered.

Therefore:

```text
source wording
  = evidence of design intent;

derived causal record
  = hypothesis / inference;

player experience claim
  = unverified until observed in a suitable prototype/playtest.
```

Useful future observation moments already exist in `game-analysis-reference/observation-flow-and-moment-prompts.md`, especially:

- first meaningful decision;
- first strong success;
- first failure;
- first discovery;
- first formed plan;
- first unexpected systemic result;
- first repeated familiar situation;
- first boredom/friction moment;
- session payoff;
- desire to continue.

## 8. Priority questions

1. **Central experience wording:** is the thesis in section 2 actually the intended project identity, or only one useful interpretation of v0.12?
2. **Sensory value:** what specific actions should feel immediately satisfying rather than merely strategically meaningful?
3. **Session rhythm:** how much routine operation should exist between high-intensity alarms/raids?
4. **Mastery readability:** can the player explain why a containment plan worked or failed without reading a forensic log?
5. **Character attachment:** how much of the intended value should come from caring about specific survivors versus operating the institution?

Until those questions are answered, keep this file as a derived working view rather than a new decision owner.
