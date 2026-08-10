# Survivor Base — Representative Scenarios Working View

**Status:** derived working view\
**Canonical source:** [`../game-planning-draft.md`](../game-planning-draft.md)\
**Candidate content input:** [`../content-premises.md`](../content-premises.md)\
**Related Loop view:** [`gameplay-loops.md`](gameplay-loops.md)\
**Reusable method:** [`../../../game-analysis-reference/gameplay-planning/scenarios.md`](../../../game-analysis-reference/gameplay-planning/scenarios.md)\
**Authority boundary:** this file owns project-local representative Scenarios assembled from current source meaning. It may also expand clearly marked candidate Content Premises into working Scenarios, but it does not promote those premises into accepted cross-cutting game rules, override `CHAT-PI-*` states, convert an inference into an accepted decision or claim that one selected chronology is the only valid playthrough.

## 1. Purpose

A Scenario asks what **actually happens through time** when concrete decisions, system execution, information reveals, consequences and recovery interact.

The current owner starts with one representative Scenario:

- **Incomplete Alarm In A Working Sector**.

It is a **working representative Scenario**, not the frozen first-demo screenplay.

The chronology is concrete enough to review integration, but some branch details remain unresolved in the source. Keep those branch points explicit instead of silently selecting missing mechanics or content.

`../content-premises.md` now preserves preliminary content units before they are detailed enough for this view. A premise belongs here only after chronology/integration work becomes useful; preserving a premise alone does not require inventing Scenario Beats.

## 2. Scenario And Beat Boundary

Use current reusable terminology directly:

```text
Scenario
  → one concrete chronological planning / test path;

Scenario Beat
  → one chronological portion of that path;

Gameplay Situation Instance
  → present only when that concrete Beat contains
     a meaningful player decision.
```

A Beat may instead or additionally be system execution, observation/information reveal, transition, consequence/payoff or recovery.

The Beat roles below are working classifications for review. They do not create a strict project Situation inventory automatically.

Likewise, a systemic tendency visible in this Scenario is only a possible Dynamic manifestation / evidence candidate. One Scenario does not prove a stable Gameplay Dynamic.

## 3. Representative Scenario — Incomplete Alarm In A Working Sector

**Status:** working representative Scenario assembled only from current accepted/preliminary systems; one source branch parameter remains unresolved.\
**Scenario responsibility:** test whether the current base, information, emergency, tactical and recovery systems can interact in one coherent crisis without inventing a second game.\
**Not yet:** frozen first-demo screenplay or final implementation chronology.

### Starting State

- The base is in routine operation.
- A residential/work sector contains multiple people and at least one route needed by normal logistics.
- The sector has a prepared primary evacuation route, a reserve route and a shelter instruction.
- A response group exists but is not already standing in every room.
- The player knows the normal geometry of this sector.

### Explicitly Unresolved Branch Details

The source does not yet select:

- the exact revealed threat at contact: fresh infected, animal, intruder, breach or another source-backed alternative;
- exact tactical squad size;
- exact time-control model and command set;
- exact route/topology failure details that may change execution.

Until these are selected or tested, keep them as visible Scenario parameters / branch points rather than treating one invented choice as current project meaning.

### Scenario Beats

| Beat | Working Beat role | What the player receives / what happens | Meaningful decision / working branch | Building blocks | Intended experience contribution |
|---|---|---|---|---|---|
| **1. Partial alarm** | Observation / Information Reveal + Situation Instance | Report such as `WEST RESIDENTIAL — Pavel heard glass / movement — threat UNKNOWN` | Act immediately, gather another signal, or start a prepared response | Information, people, emergency | Curiosity + tension without perfect knowledge |
| **2. First containment choice** | Situation Instance | People are still working/sleeping in different rooms; shared corridor may be dangerous | Evacuate A/B, shelter in place, seal locally, or call response first | Facility, policy, people, security | Agency under time pressure |
| **3. Physical execution begins** | System Execution + possible Situation Instance | People move according to actual route/door state; some are slow, blocked or need help | Override the plan, open another corridor, assign escort, or accept someone remaining inside | Facility, people, emergency | Plan ownership; consequences of preparation |
| **4. Investigation** | Situation Instance + System Execution | Response squad reaches the boundary; exact threat still may be unknown | Light/check, open and fall back, lure, watch doorway, or enter | Information, tactics, facility | Tactical tension + controlled discovery |
| **5. Contact / revelation** | Information Reveal + Situation Instance | Threat becomes specific, using one source-backed branch that is not yet selected | Engage, retreat, isolate, or pursue source/breach as the concrete branch permits | Infection/external, tactics | Relief of uncertainty followed by a new decision |
| **6. Containment outcome** | Consequence / Payoff + Situation Instance | Threat is removed, trapped or pushed away; some doors/routes may be damaged or unavailable | Keep sector sealed or begin controlled reopening | Facility, policy, security | Consequence rather than instant reset |
| **7. Aftermath** | Consequence / Recovery + Situation Instance | Blood/body/injury/dirty surfaces and displaced people remain | Allocate sanitation/medical/labor; reroute production | Production/logistics, infection, people | Cost of success; recovery work |
| **8. Find the cause** | Observation / Information Reveal + Situation Instance | A broken window/hole/route, report chain or exposure history may explain the event | Repair boundary, investigate source, update evidence | Facility, information, infection | Discovery + causal understanding |
| **9. Update the operating system** | Situation Instance + Recovery | Player has new information about a weak point and actual emergency behavior | Change route, refuge, checkpoint, sector policy, staffing or drill | Policy, facility, people, emergency | Mastery and adaptation |
| **10. Return to routine** | Recovery / Transition | Sector reopens fully/partially or remains lost; the base is operational but changed | Choose the next priority when a new meaningful decision becomes active | All | Payoff: the base survived because/where the plan worked, and now has a new problem/opportunity |

The table is a Scenario chronology. It does **not** assert that every row is a reusable Gameplay Situation Type.

### Why This Scenario Is Useful

It exercises existing systems instead of inventing a bespoke scripted mechanic:

```text
partial information
+ people in a physical facility
+ prepared plan
+ actual door/route constraints
+ direct small-squad response
+ infection/threat uncertainty
+ sanitation aftermath
+ revised policy/layout
```

If the Scenario cannot be made legible and interesting with these blocks, that is a stronger warning than adding more event types.

### Relationship To Recurrent Gameplay

This Scenario traverses part of the broad operating cycle in [`gameplay-loops.md`](gameplay-loops.md):

```text
read current state
→ notice / receive a problem
→ interpret incomplete information
→ commit a plan
→ system execution
→ crisis tests the plan
→ intervention
→ consequences
→ recovery / adaptation
→ changed operating state.
```

The Scenario can expose where concrete Gameplay Loops overlap or fail to integrate, but it does not define Loop membership merely by putting events in one chronology.

## 4. Scenario Validation Checkpoints

The reusable observation reference suggests moments that map well to this project:

| Moment | Survivor Base question |
|---|---|
| First meaningful decision | Did the player understand at least two materially different plans? |
| First formed plan | Did the player use knowledge about people/space rather than follow an obvious preset? |
| First unexpected systemic result | Could the player identify which rules/states collided? |
| First failure | Could the player explain one thing to change next time? |
| First discovery | Did new evidence change a belief or action? |
| First repeated situation | Did it still require adaptation, or become rote execution? |
| First boredom/friction | Is the player doing clerical work instead of making decisions? |
| Session payoff | What changed in the base that makes another period worth playing? |

These checkpoints can be used by this Scenario, later representative Scenarios or a fuller demo chronology. They are not evidence until observed.

## 5. Open Questions That Block A Frozen Demo Scenario

The imported draft still leaves these for later passes:

1. exact tactical squad size;
2. real-time / pause / time-control model;
3. exact command set and combat abstraction;
4. exact dark-wing topology and local hearing/vision;
5. alarm severity/scope model;
6. how prepared plans fail on blocked routes / personality / damage;
7. emergency-drill balance;
8. first-demo intake layout and population density;
9. exact timing of capability opportunity and migrating infected pressure;
10. the exact threat branch selected for the incomplete-alarm Scenario;
11. frame-by-frame demo choreography.

Do not fill these gaps silently in this view.

## 6. Current Content-Premise Handoff

The preliminary owner currently contains:

- `CP-001 — Prolonged Horde / "Nuclear Winter" Siege`;
- `CP-008 — Most Of The Facility Lost`;
- `CP-009 — First Floor Lost — Descend From Above`.

These are **not yet additional Scenarios in this view**.

When one is selected for deeper work:

```text
Content Premise
→ identify unresolved generic rules/dependencies
→ use the reusable Scenario method
→ create concrete chronology / Beats / Situation Instances
→ keep unaccepted generic mechanics outside the Scenario
→ add the resulting working Scenario here.
```

Hybrid examples still stored only in `ideas.md` should not be pulled into this file until they have first become independent content units or a direct Scenario exploration is explicitly chosen.
