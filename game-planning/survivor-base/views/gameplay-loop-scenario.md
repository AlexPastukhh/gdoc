# Survivor Base — Gameplay Loop And Representative Scenario Working View

**Status:** derived working view\
**Canonical source:** [`../game-planning-draft.md`](../game-planning-draft.md)\
**Related structural view:** [`game-building-blocks.md`](game-building-blocks.md)\
**Authority boundary:** this is a temporal/causal synthesis. The imported draft explicitly defers a frozen frame-by-frame demo screenplay and final core/session-loop formulation.

## 1. Purpose

A feature list does not show what the player repeatedly does over time. This view asks three separate questions:

1. **Core loop:** what perception/decision/action/consequence cycle repeats across ordinary play?
2. **Session / day arc:** how does routine escalate, resolve and leave a reason to continue?
3. **Representative gameplay situation:** can the currently accepted systems actually interact in one concrete crisis without inventing a second game?

## 2. Source-backed loop skeleton

The source package's bootstrap summarizes the current center as:

```text
build containment + operate base
→ observe people / produce evidence
→ assign / restrict people
→ production / social pressure pushes against safety
→ outbreak / breach tests architecture
→ seal / shelter / evacuate / fight
→ cleanup / reclaim
→ adapt rules and layout
```

The canonical draft's `Cross-system picture` expresses the same feedback structure through physical base, people/objects/information, rules/production, decisions, consequences, new observations and revised knowledge/rules.

## 3. Core loop candidate

**Status:** `inference / decision candidate` until explicitly reviewed.

```text
1. Read the current operating state
   people + rooms + production + risk + reports

2. Notice a problem, opportunity or information gap
   shortage / suspicious person / dirty route / alarm / outside target / unknown space

3. Gather or interpret enough information to act
   observation / dossier / report / test / spatial check / expert assessment

4. Make a plan
   zone / permission / staffing / route / intake / emergency plan / raid plan

5. Commit people, space and resources
   assign / restrict / move / open / close / guard / investigate / prepare

6. Let the living system execute
   people work, move, obey/refuse, produce, report and encounter constraints

7. A trade-off, exception or crisis tests the plan
   infection / breach / blocked route / shortage / social conflict / tactical contact

8. Intervene at the appropriate control level
   policy change / reassignment / shelter / evacuation / seal / response squad / retreat

9. Pay and read the consequences
   injuries / infection risk / lost labor / contaminated space / saved people / evidence / loot

10. Recover and update
   sanitation / repair / reclaim / dossier/evidence update / new rule / redesigned route

11. Enter the next cycle with a changed base and changed knowledge
```

### What makes this a loop rather than a checklist

The output of step 9–10 changes the inputs of step 1. The game should not merely rotate through scripted events; player-created structure and previous consequences should alter what the next problem means.

## 4. Player verbs inside the loop

The draft currently supports several levels of control. They should coexist rather than compete.

### Operational / policy verbs

```text
assign
restrict / permit
prioritize
inspect / investigate
admit / hold / refuse
set route / zone / rule
prepare contingency
allocate scarce labor/resources
```

### Spatial / emergency verbs

```text
evacuate via A/B
shelter in place
lock/seal room
seal sector
compartmentalize
open evacuation corridor
call security response
all clear / controlled reopen
```

### Direct tactical verbs

```text
move / hold
watch / cover doorway
open / close / breach
light / investigate
make noise / lure
engage / avoid
retreat
carry / drag
```

The current design direction says the direct tactical language should be shared by raid squads and some base responses.

## 5. Session / day arc candidate

**Status:** inference. Exact timings and event frequency remain open.

```text
A. Routine operating state
   → production, intake, staffing, cleaning, observation and preparation

B. A near-term goal or pressure becomes salient
   → capability opportunity, shortage, incoming people, outside window, suspicious evidence

C. The player reallocates the base around a plan
   → labor, routes, restrictions, preparedness, raid setup

D. Uncertainty or risk escalates
   → partial report, new evidence, tactical exploration, outside contact, outbreak/breach

E. Decisive situation
   → accept risk, delay, refuse, seal, evacuate, shelter, fight, retreat or sacrifice

F. Aftermath / recovery
   → injuries, contamination, closed space, lost work, social effects, new evidence

G. New stable-but-changed state
   → reclaim/reopen, revise policy/layout, unlock capability or expose a new problem

H. Return motivation
   → a new question, new capability, unresolved person/strain issue or next spatial/strategic objective
```

A healthy session rhythm probably needs meaningful routine and planning between crisis peaks. The imported source explicitly warns against alarm spam and against turning the base into constant warfare.

## 6. Long-term adaptation loop candidate

The exact final run objective is unresolved, but v0.12 supports a long-term learning/growth loop:

```text
small trusted clean core
→ assess/integrate people
→ stabilize production
→ reclaim usable territory
→ improve knowledge and preparedness
→ pursue external capability/resource goals
→ face new biological/social/spatial risks
→ revise organization and containment
→ operate a larger/more capable but more complex community
```

Progress should ideally change **what strategies are possible**, not only increase numbers.

## 7. Representative gameplay situation — incomplete alarm in a working sector

**Status:** working scenario assembled only from current accepted/preliminary systems. It is not the frozen first-demo screenplay.

### Starting state

- The base is in routine operation.
- A residential/work sector contains multiple people and at least one route needed by normal logistics.
- The sector has a prepared primary evacuation route, a reserve route and a shelter instruction.
- A response group exists but is not already standing in every room.
- The player knows the normal geometry of this sector.

### Scenario flow

| Stage | What the player receives / sees | Meaningful decision | Building blocks involved | Intended experience contribution |
|---|---|---|---|---|
| **1. Partial alarm** | Report such as `WEST RESIDENTIAL — Pavel heard glass / movement — threat UNKNOWN` | Act immediately, gather another signal, or start a prepared response | Information, people, emergency | Curiosity + tension without perfect knowledge |
| **2. First containment choice** | People are still working/sleeping in different rooms; shared corridor may be dangerous | Evacuate A/B, shelter in place, seal locally, or call response first | Facility, policy, people, security | Agency under time pressure |
| **3. Physical execution begins** | People move according to actual route/door state; some are slow, blocked or need help | Override the plan, open another corridor, assign escort, accept someone remaining inside | Facility, people, emergency | Plan ownership; consequences of preparation |
| **4. Investigation** | Response squad reaches the boundary; exact threat still may be unknown | Light/check, open and fall back, lure, watch doorway, or enter | Information, tactics, facility | Tactical tension + controlled discovery |
| **5. Contact / revelation** | Threat becomes specific: e.g. fresh infected, animal, intruder or breach | Engage, retreat, isolate, pursue source/breach | Infection/external, tactics | Relief of uncertainty followed by new decision |
| **6. Containment outcome** | Threat is removed, trapped or pushed away; some doors/routes may be damaged or unavailable | Keep sector sealed or begin controlled reopening | Facility, policy, security | Consequence rather than instant reset |
| **7. Aftermath** | Blood/body/injury/dirty surfaces and displaced people remain | Allocate sanitation/medical/labor; reroute production | Production/logistics, infection, people | Cost of success; recovery work |
| **8. Find the cause** | A broken window/hole/route, report chain or exposure history may explain the event | Repair boundary, investigate source, update evidence | Facility, information, infection | Discovery + causal understanding |
| **9. Update the operating system** | Player has new information about a weak point and actual emergency behavior | Change route, refuge, checkpoint, sector policy, staffing or drill | Policy, facility, people, emergency | Mastery and adaptation |
| **10. Return to routine** | Sector reopens fully/partially or remains lost; the base is operational but changed | Choose the next priority | All | Payoff: the base survived because/where the plan worked, and now has a new problem/opportunity |

### Why this scenario is useful

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

If the scenario cannot be made legible and interesting with these blocks, that is a stronger warning than adding more event types.

## 8. Alternate loop insertion — tactical raid and return

A raid should connect to the same operating loop rather than form an independent game:

```text
base need / capability target
→ strategic target and squad preparation
→ travel / site entry
→ direct tactical exploration/contact
→ loot / evidence / injuries / contamination
→ return to perimeter
→ own-raid intake / decon / medical assessment
→ integrate resources/evidence back into base
→ consequences change production, knowledge and future risk
```

The important integration check is whether decisions made **before** and **after** the tactical site matter as much as the fight itself.

## 9. Readability requirements for the loop

For the loop to produce agency/mastery, the player should usually be able to answer:

- What am I trying to protect or gain right now?
- What do I know, and what is still uncertain?
- Which action is possible here?
- What did I commit by choosing it?
- What physically/systemically happened next?
- Why did the outcome differ from my plan?
- What can I change before the next similar situation?

This does **not** require perfect information. It requires usable feedback about causes.

## 10. Future validation checkpoints

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

## 11. Open questions that block a frozen screenplay

The imported draft itself leaves these for later passes:

1. exact tactical squad size;
2. real-time / pause / time-control model;
3. exact command set and combat abstraction;
4. exact dark-wing topology and local hearing/vision;
5. alarm severity/scope model;
6. how prepared plans fail on blocked routes / personality / damage;
7. emergency-drill balance;
8. first-demo intake layout and population density;
9. exact timing of capability opportunity and migrating infected pressure;
10. final core/session-loop wording and frame-by-frame demo choreography.

Do not fill these gaps silently in this view.
