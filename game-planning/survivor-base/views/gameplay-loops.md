# Survivor Base — Gameplay Loops Working View

**Status:** derived working view\
**Canonical source:** [`../game-planning-draft.md`](../game-planning-draft.md)\
**Related structural view:** [`game-building-blocks.md`](game-building-blocks.md)\
**Related Scenario owner:** [`scenarios.md`](scenarios.md)\
**Reusable method:** [`../../../game-analysis-reference/gameplay-planning/loops.md`](../../../game-analysis-reference/gameplay-planning/loops.md)\
**Authority boundary:** this file reorganizes current source meaning around recurrent gameplay structure. Broad operating-cycle, session/day and long-term views are not automatically concrete Gameplay Loop records. Concrete Loop formulations remain inference / decision candidates until explicitly reviewed, and the imported draft still defers the final core/session-loop formulation.

## 1. Purpose

A feature list does not show what the player repeatedly does over time. This view separates:

1. a **broad recurrent operating cycle** that summarizes ordinary play;
2. a **Session / Day Arc** used to reason about escalation, recovery and return motivation;
3. a **Long-Term Adaptation Arc** used to reason about growth and changing strategic possibility;
4. candidate **Gameplay Loops** where a recurrent functionally coherent causal process is specific enough to review as such.

Use the strict reusable Gameplay Loop term only when recurrent causal membership is actually useful. Do not force every broad scale-oriented view into one giant Loop.

## 2. Source-Backed Operating Skeleton

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

## 3. Broad Recurrent Operating Cycle Candidate

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

### Why this is a recurrent operating cycle

The output of steps 9–10 changes the inputs of step 1. The game should not merely rotate through scripted events; player-created structure and previous consequences should alter what the next problem means.

This broad cycle may contain several concrete Gameplay Loops and periods of execution from several Loops at once. Do not treat every numbered step as a universal Loop Phase or assume the whole simulation must be one Loop.

## 4. Player Verbs Inside The Operating Cycle

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

## 5. Session / Day Arc Candidate

**Status:** inference. Exact timings and event frequency remain open.

This is a broad temporal/pacing view, not a concrete Gameplay Loop record by itself.

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

## 6. Long-Term Adaptation Arc Candidate

**Status:** inference. The exact final run objective remains unresolved.

This is a broad long-term progression/adaptation view. Treat it as a concrete Gameplay Loop only if later review finds recurrent functional/causal membership useful at that scale.

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

## 7. Candidate Gameplay Loop — Tactical Raid And Reintegration

**Status:** inference / decision candidate.

A raid should connect to the same living operating system rather than form an independent game:

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

This is a useful Gameplay Loop candidate because preparation, tactical execution, return and reintegration can form a recurrent causal process whose consequences alter later needs and options.

The important integration check is whether decisions made **before** and **after** the tactical site matter as much as the fight itself. Final Loop membership, frequency and concrete Situation Types still require review rather than being implied by this broad chain.

## 8. Readability Requirements For Recurrent Gameplay

For recurrent gameplay to produce agency/mastery, the player should usually be able to answer:

- What am I trying to protect or gain right now?
- What do I know, and what is still uncertain?
- Which action is possible here?
- What did I commit by choosing it?
- What physically/systemically happened next?
- Why did the outcome differ from my plan?
- What can I change before the next similar situation?

This does **not** require perfect information. It requires usable feedback about causes.

## 9. Current Loop Questions

The current source still leaves several loop-level questions open:

- What is the final core/session-loop wording, if one broad formulation remains useful?
- Which parts of the broad operating cycle are best modelled as distinct concrete Gameplay Loops?
- How do exact event frequency and timing affect recurrence without creating alarm spam?
- Which Situation Types recur strongly enough to define specific Loop membership?
- Does the tactical raid-and-reintegration candidate remain causally integrated with base play when implemented, or drift into a separate game?

Do not answer these questions merely by renaming broad phases. Use the reusable Loop method, concrete Scenarios and later evidence when the distinction becomes load-bearing.
