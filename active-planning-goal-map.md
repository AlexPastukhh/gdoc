# Active Planning Goal Map

Status: active operational current-work owner
Scope: current planning direction, open concerns, next validation work and deferred dependencies. This is **not** a canonical terminology owner, historical archive or permanent backlog.

## 1. Current Goal

Validate and refine the low-level gameplay-planning model through one paired concrete pass:

```text
Survivor Base Spine Scenario
        ↕
full low-level units actually used by that Spine.
```

The current qualitative update establishes working rules/templates only. The next pass should use one non-branching Scenario as a Spine and develop the reusable low-level units it actually exposes.

## 2. Goal-Map Lifecycle

For each material concern preserve proportionally:

```text
Concern / Question
Status: active / deferred
Why It Matters
Current Owner / Working Files
What Would Count As Closed
Next Check / Evidence / Planning Pass
Dependencies, if any
```

When a concern closes:

```text
durable conclusion
→ store/reconcile it in the real semantic/method/project owner;

Goal Map
→ remove the closed concern
  or retain only a still-live next dependency.
```

Do not turn this file into a second methodology document or historical backlog. The explanations below exist only to make current work actionable.

## 3. Active Concerns — Close Through The Next Paired Spine Pass

### Spine Role / Handoff

**Status:** active
**Why it matters:** the Spine must remain readable as one concrete chronology while still carrying enough information to discover and feed every low-level owner.
**Current owners:** `game-analysis-reference/gameplay-planning/scenarios.md`, `game-development-planning-workflow.md`.
**Questions:** Does `Spine Scenario` remain a useful named planning role? Which concrete fields stay in Spine vs reusable alternative-space in owners? Is `Timeline + expandable Beat / Step / Interval detail` convenient? How much selected-branch detail stays inline? Which temporal tracks recur?
**Closed when:** one real paired pass is readable both chronologically and by unit without important duplication or missing handoffs.
**Next check:** build the first non-branching Survivor Base Spine and its full low-level handoffs.

### Situation Activation / Salience / Long-Lived Decisions

**Status:** active
**Why it matters:** objective opportunity, player awareness/understanding, motivation/salience and Active Situation are not the same thing; one Situation may also remain unresolved while its state changes.
**Current owner:** `game-analysis-reference/gameplay-planning/situations.md`.
**Questions:** Which prerequisite/driver dimensions are useful? Does `Activation Threshold / Salience Shift` help? How should `not perceived / not understood / not salient / deferred / attention-crowded` be represented? How should Events/state/information/execution modify one still-Active Situation? Is descriptive `Decision Situation` wording useful enough to retain while canonical term remains `Gameplay Situation`?
**Closed when:** concrete Situation records explain occurrence, salience and active evolution without inventing false new Situations or over-modeling every state change.
**Next check:** expand the first two Situation Types discovered by the Spine and compare their alternate activation paths/options against the concrete Instances.

### Project Experience

**Status:** active
**Why it matters:** project-specific Experience needs an owner distinct from reusable family vocabulary and from evidence-only `Experience Hypothesis` responsibility.
**Current owners:** `game-analysis-reference/player-experience-motivation-planning.md`, project-local `experience-motivation/` owner.
**Questions:** Which fields survive real use? Does 0..N reusable family classification actually improve quality? Does the lifecycle `arises → persists → strengthens/weakens → resolves/fades/breaks` describe useful design work? How should repeated-play learning deepen/change Experience? Where is the clean boundary with `Experience Hypothesis`?
**Closed when:** a concrete Project Experience can be designed, improved through reusable lenses, tracked through its lifecycle and tested without duplicate evidence ownership.
**Next check:** create only the Project Experience records that genuinely emerge from the Spine and run their family-specific quality passes.

### Project Motivation

**Status:** active
**Why it matters:** Motivation explains why gameplay becomes worth pursuing/salient but must not erase Situation Goal/Stake/Expectation/Plan.
**Current owners:** `game-analysis-reference/player-experience-motivation-planning.md`, Situation/Scenario links.
**Questions:** Which fields cleanly distinguish meta/experiential Motivation, in-play Motivation and Situation Goal? Does the lifecycle `arises → persists → strengthens/weakens → satisfies/resolves/dies/inverts` help? How should Motivation relate to Experience, Strategy and Plan? Are `seek / deepen / preserve / restore / resolve / avoid / validate` useful without becoming a rigid taxonomy? Should Motivation later receive canonical reusable ownership?
**Closed when:** real decisions can be explained through Motivation without collapsing rational Situation fields or creating duplicate taxonomy.
**Next check:** for each selected Spine decision, state the concrete Motivation from Player Context and compare it to the local owner's alternative option motivations.

### Experience Opportunity / Legibility / Experiential Expectation

**Status:** active
**Why it matters:** an Experience may be mechanically possible but never become motivationally relevant if the player does not understand/believe it is available.
**Current owner:** `game-analysis-reference/player-experience-motivation-planning.md`.
**Working relation:** `Experience Opportunity → Legibility / Awareness → Experiential Expectation → Motivation`.
**Questions:** Which stages need explicit fields vs lenses? What belongs in Scenario vs Experience/Motivation owners?
**Closed when:** a concrete pass can explain why a supported Experience does or does not become an expectation and Motivation without requiring unnecessary standalone objects.
**Next check:** trace the chain for at least one Experience/Motivation that actually affects a selected Spine decision.

### Experience Promise

**Status:** active candidate-unit question
**Why it matters:** communication/demonstration of a specific Experience may have an independent lifecycle across pre-play/onboarding/in-play/repeated confirmation.
**Current owner:** candidate section in `game-analysis-reference/player-experience-motivation-planning.md`.
**Questions:** Does it deserve an independent owner? How does it remain distinct from generic `Player Promise` and actual `Experiential Expectation`? Can one Promise support several Motivations/contexts?
**Closed when:** real use shows either independent reuse/change responsibility or a simpler stable field/relation home.
**Next check:** create a Promise record only if the Spine needs the same Experience expectation to be communicated/confirmed across several moments or units.

### Doubt / Concern

**Status:** active candidate-unit question
**Why it matters:** a player may decline/abandon an otherwise valid motivation because they expect unwanted gameplay or doubt the desired Experience exists.
**Current owner:** candidate section in `game-analysis-reference/player-experience-motivation-planning.md`.
**Questions:** Does it have independent reuse/change responsibility? How do true gameplay problems, insufficient proof/communication and audience mismatch stay distinct? How does Doubt weaken/redirect Motivation?
**Closed when:** real use shows whether a separate owner improves reasoning more than an inline Experience/Motivation field.
**Next check:** preserve only Doubts that materially change a Spine decision, activity choice or motivation.

### Player Context / Expertise

**Status:** active
**Why it matters:** the same objective state/information can produce different perceived options, decisions and Experiences for different prior knowledge/preferences/expertise.
**Current owners:** `game-analysis-reference/player-experience-motivation-planning.md`, Situation and Scenario methods.
**Questions:** Which dimensions are useful: Rules Familiarity, Causal-Model Accuracy, Pattern Familiarity, Option Awareness, Strategic Repertoire, Execution Fluency, Content Familiarity, others? How should entry Player Context differ from evolving Mental Model/Expertise? When is multi-context replay of one Scenario useful?
**Closed when:** the first Spine explains selected decisions/learning without mixing game-provided Information with prior player knowledge or expertise.
**Next check:** state one concrete Player Context for the Spine and record only expertise changes that materially alter later decision space.

### Gameplay Event Method

**Status:** active
**Why it matters:** reusable decisionless occurrences need planning responsibility, but gradual state/info/motivation changes must not all become Events.
**Current owner:** supporting Event record in `game-analysis-reference/gameplay-planning/README.md`.
**Questions:** Is the enriched inline record sufficient? Which Event→State/Information/Situation/Execution/Experience/Motivation/delayed relations recur? Does repeated use justify `events.md` later?
**Closed when:** concrete Events are plan-able proportionally without becoming fake Situations or an oversized universal taxonomy.
**Next check:** use the Event record only for independently useful occurrences actually found in the Spine.

### Execution Unit

**Status:** active provisional-unit validation
**Why it matters:** while process variants/timing/intermediate states are unresolved, execution has planning questions not owned cleanly by Domain Operation, Scenario occurrence or Visual realization alone.
**Current owner:** `game-analysis-reference/gameplay-planning/executions.md`.
**Questions:** Which fields/Variants recur? Where is the stable boundary with Domain/Scenario/Visual? What reconciles into Domain/Visual after design stabilizes? Does Execution later deserve canonical terminology?
**Closed when:** several real executions can be planned without duplicate systemic truth or missing gameplay-time responsibility.
**Next check:** use the provisional record on the different execution processes encountered by the Spine; compare whether the same fields remain useful.

### Cross-Unit Relations

**Status:** active
**Why it matters:** many gaps are causal/reference relations between existing owners, not evidence that another entity type is needed.
**Current owner:** working relation map in `game-analysis-reference/player-experience-motivation-planning.md` plus scale-specific owners.
**Questions:** Which links recur and are worth naming? Which become graph noise or are better represented through shared state?
**Closed when:** the first paired pass has a small relation vocabulary that explains handoffs/causality without exhaustive graphing.
**Next check:** record only links needed to understand the selected chronology and local reusable alternatives; review repeated relation types afterward.

### Visual / Attention / Pacing / Reachability

**Status:** active
**Why it matters:** whether a Situation becomes perceived/salient and whether chronology feels overloaded depends on presentation, attention competition and timing, not only objective mechanics.
**Current owners:** `game-analysis-reference/gameplay-planning/scenarios.md`, reusable visual-planning owner.
**Questions:** Which interval concerns matter: foreground/background focus, missable signals, active/time-sensitive Situations, ongoing Executions, decision density, unresolved-decision age, new-information rate, interruptions, feedback delay, breathing room? Are `Mandatory / path-inevitable / Conditional / Player-initiated / Discoverability-dependent / Attention-dependent` useful?
**Closed when:** the Spine can explain perception/pacing/reachability without fake numeric precision.
**Next check:** annotate only material attention/pacing intervals and mark mandatory/conditional/discoverability distinctions where they change interpretation.

### Situation Likelihood / Probability

**Status:** active but not yet quantitative
**Why it matters:** one selected Spine cannot establish how likely a Decision Situation is across players/paths.
**Current owners:** Scenario/Situation methods; future balance/evidence work.
**Question:** what evidence is sufficient before numeric likelihood is meaningful?
**Closed when:** either qualitative reachability proves sufficient for the design need or a later method combines multiple paths, player contexts, Event frequencies and attention/discoverability evidence.
**Next check:** do **not** assign percentages in the first Spine; record qualitative reachability and missing evidence.

### Project Filesystem Shape

**Status:** active
**Why it matters:** physical structure should follow actual reuse/review responsibility, not ontology symmetry.
**Current owners:** `game-planning/README.md`, project README(s).
**Questions:** when should units remain one file vs folders, and which owner-local `ideas/` workspaces become useful?
**Closed when:** real unit count/reuse makes the smallest clear structure obvious.
**Next check:** create no empty mirroring structure during the first Spine pass; split only when an owner actually needs it.

## 4. Deferred / Next-Order Methodology Concerns

These are recognized gaps. They do not block the first paired Spine pass unless they become load-bearing.

### Gameplay Loop Validation
**Status:** deferred.
**Concern:** empirical/source-backed Loop-boundary validation; recurrence vs current `frequently recurring` wording; extracting Loops from recurrent causality rather than one Scenario chronology.
**Resume when:** the Spine shows repeated/re-entered causal structures worth testing as Loops.

### Player Strategy
**Status:** deferred.
**Concern:** canonical definition/owner/boundaries and relation to Motivation, Goal, Plan and Dynamics.
**Resume when:** repeated player-authored planning across decisions becomes load-bearing for the next analysis.

### Broader Balance
**Status:** deferred.
**Concern:** architecture spanning Situation Versions, Domain/economy, Strategies, Dynamics and session/campaign horizons.
**Resume when:** Strategy and temporal structure are clearer or a real balance decision requires it.

### Dynamic ↔ Progression
**Status:** deferred.
**Concern:** authored/structured unlock/ownership change vs operative systemic tendency.
**Resume when:** a concrete candidate Dynamic/progression relation becomes ambiguous.

### Game Domain / Economy Detailed Method
**Status:** deferred.
**Concern:** exact reusable Domain/economy planning method when current state/operation ownership becomes insufficient.
**Resume when:** the Spine/Execution pass exposes missing Domain ownership or repeated economy-model questions.

### Complete Planning Operating Model
**Status:** deferred.
**Concern:** orchestration gaps not solved by the current workflow/Goal Map.
**Resume when:** repeated use exposes a concrete failure rather than an abstract desire for completeness.

### Use-Case Registry
**Status:** explicitly deferred by current planning decision.
**Concern:** use-case wording should describe a stable owner/component set rather than churn with current experiments.
**Resume/close when:** low-level parts are stable enough to describe supported use cases without immediate rewrite. Do **not** update `game-planning-use-case-registry.md` before then.

## 5. Immediate Next Work

After this qualitative update is applied and reviewed:

```text
choose one concrete non-branching Survivor Base Scenario as Spine
→ set one explicit Player Context
→ walk chronology forward
→ simultaneously create/expand every independently useful
  Situation / Event / Execution / Experience / Motivation /
  Promise / Doubt unit actually needed
→ preserve Domain + Visual handoffs
→ trace Loop/Dynamic candidates only when recurrence/tendency appears
→ revise templates from real use.
```
