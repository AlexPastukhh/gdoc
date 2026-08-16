# Active Planning Goal Map

Status: active operational current-work owner
Scope: current planning direction, open concerns, next validation work and deferred dependencies. This is **not** a canonical terminology owner, historical archive or permanent backlog.

## 1. Current Goal

Validate and refine the low-level gameplay-planning model through one staged concrete Survivor Base pass while also making the reusable documentation route clear enough for new chats to follow safely.

```text
legacy Draft as migration/source context
→ coherent detailed Survivor Base Spine Scenario
→ concrete low-level unit manifestations inside the Spine
→ Low-Level Elements / candidate responsibilities / handoffs
→ separate reusable low-level expansion where independent ownership is useful
→ compare clarified owners back against the Spine
→ later recombine reusable units into additional Scenarios.
```

The current Survivor Base pass first keeps one selected non-branching Scenario coherent enough to review as chronology. During that work, preserve material responsibilities, concrete unit manifestations, Low-Level Elements and candidate handoffs, but do not immediately expand every candidate into its full reusable possibility-space. After chronology stabilizes enough, expand independently useful reusable owners separately and compare them back against the Spine.

This is a **current-work tactic**, not the universal reusable sequence. General architecture remains iterative:

```text
Scenario / Spine ↔ reusable owners ↔ Ideas / Variants / Versions ↔ new Scenarios.
```

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

Do not turn this file into a second methodology document or historical backlog. Explanations below exist only to make current work actionable.

## 3. Active Concerns — Close Through The Next Staged Spine Pass

### Current Opening Spine Selection / Gameplay Entry

**Status:** active working selection; backbone selected for current methodology pass, concrete details not frozen project truth.
**Why it matters:** current pass needs one stable chronology to expose real low-level boundaries without repeatedly reopening its basic path.
**Current working owner:** `game-planning/survivor-base/scenarios/opening-spine.md`; this Goal Map now tracks the concern/next validation rather than owning the chronology.
**Selected backbone:** `newcomers arrive / are detected → intake → admission decision → integration / work → people become more known → ambiguous evidence → response → investigation → assessment → persistent procedure / policy change`.
**Entry boundary:** First Contact / pre-play may establish virus/world context, game/base context and gameplay-entry player-side state, but is not automatically Gameplay Phase 0. Gameplay T0 for this Spine is arrival/detection of newcomers. Existing base and clean trusted core are Starting State.
**Open:** whether explicit trusted-core setup occurs between launch and Gameplay T0; exact presentation of virus/world and game/base context; exact newcomers, symptoms, work, diagnosis and final policy.
**Legacy Draft check:** consult relevant Planning Items/status/provenance in `game-planning/survivor-base/game-planning-draft.md` while constructing the Spine. Treat the Draft as migration/source context, not the permanent target owner. Do not require back-writing every new owner-local clarification into it; write back only when explicit migration compatibility/provenance responsibility requires it.
**Closed when:** detailed selected chronology reaches persistent operating adaptation and remaining Scenario Assumptions, owner handoffs and source relationships are explicit.
**Next check:** continue this selected opening Spine in `game-planning/survivor-base/scenarios/opening-spine.md` rather than choosing another backbone.

### Spine Role / Handoff

**Status:** active.
**Why it matters:** Spine must remain readable as one concrete chronology while carrying enough information to discover and feed low-level owners/elements.
**Current owners:** `game-planning-spine-workflow.md`, `game-analysis-reference/gameplay-planning/scenarios.md`.
**Working boundary:** Spine contains concrete low-level manifestations itself; reusable owners expand broader possibility-space across Scenarios. Extraction into a reusable owner does not remove the concrete occurrence from Spine.
**Questions:** Does `Spine Scenario` remain a useful named planning role? Is `Timeline + expandable Beat / Step / Interval detail` convenient? How much selected-branch detail stays inline? Which temporal tracks recur?
**Closed when:** one real staged pass is readable as coherent chronology and by independently useful reusable owner without important duplication or missing handoffs.
**Next check:** preserve concrete manifestations, candidate responsibilities and handoffs while building detailed Spine; expand full reusable alternatives only after chronology stabilizes enough for review.

### Low-Level Elements

**Status:** active newly clarified reusable concept/application.
**Why it matters:** many planning questions are smaller than a whole Situation/Execution/Domain/etc. They need Idea work without automatically becoming new entities.
**Current owners:** `principles/game-planning-principles-and-terminology.md`, `low-level-element-planning-workflow.md`; project placement in `game-planning/README.md`.
**Working rule:** a Low-Level Element is a meaningful design part/question inside a planning unit that remains parent detail unless independent reuse/review/research/testing/change responsibility emerges.
**Example:** one option such as `restricted admission`, one information rule, one consequence relation or one Execution interruption rule.
**Closed when:** real Spine/unit work shows that the concept routes smaller design questions cleanly without creating unnecessary units/files.
**Next check:** use scoped Idea work on the first material element-level question discovered in the opening Spine.

### Current-Stage Low-Level Boundary Discovery

**Status:** active; scoped to current discovery stage.
**Why it matters:** current low-level unit/entity boundaries are not complete, so missing final ownership must not erase a material planning responsibility.
**Working rule:** if omitting a responsibility would make selected chronology/causality materially incomplete, preserve the responsibility and mark owner/boundary unresolved. Missing current ownership does not by itself prove invalidity or need for a new entity. A concern may remain a Low-Level Element inside an existing owner.
**Closed when:** staged Spine/reusable-owner comparison shows which responsibilities recur with independent review, reuse, test or change lifecycles.
**Next check:** capture concrete responsibility first; decide unit/element/field/file boundaries from repeated real use.

### Planning Entity Versions

**Status:** active documentation/model clarification.
**Why it matters:** reusable contextual/configurational `Version` should not be artificially limited to Situation when same distinction is useful for other planning entities.
**Current owner:** `principles/game-planning-principles-and-terminology.md`; Situation-specific application remains in gameplay terminology.
**Working distinction:** `Variant = alternative design`; `Version = materially different reusable context/configuration of same design`; `Document Revision = document edit history`. Not every entity needs Versions.
**Closed when:** at least two real planning scales use the distinction without Variant/Revision confusion or forced empty structure.
**Next check:** apply Version only when a real contextual/configurational difference becomes independently useful.

### Situation Activation / Salience / Long-Lived Decisions

**Status:** active.
**Why it matters:** objective opportunity, player awareness/understanding, motivation/salience and Active Situation are not the same thing; one Situation may remain unresolved while its state changes.
**Current owner:** `game-analysis-reference/gameplay-planning/situations.md`.
**Questions:** Which prerequisite/driver dimensions are useful? Does `Activation Threshold / Salience Shift` help? How should `not perceived / not understood / not salient / deferred / attention-crowded` be represented? How should Events/state/information/execution modify one still-Active Situation? Is descriptive `Decision Situation` wording useful enough to retain while canonical term remains `Gameplay Situation`?
**Closed when:** concrete Situation records explain occurrence, salience and active evolution without inventing false new Situations or over-modeling every state change.
**Next check:** expand first two Situation Types discovered by Spine and compare alternate activation paths/options against concrete Instances.

### Project Experience

**Status:** active.
**Why it matters:** project-specific Experience needs an owner distinct from reusable family vocabulary and evidence-only `Experience Hypothesis` responsibility.
**Current owners:** `game-analysis-reference/player-experience-motivation-planning.md`, project-local `experience-motivation/` owner.
**Questions:** Which fields survive real use? Does 0..N reusable family classification improve quality? Does lifecycle `arises → persists → strengthens/weakens → resolves/fades/breaks` describe useful design work? How should repeated-play learning deepen/change Experience? Where is clean boundary with `Experience Hypothesis`?
**Closed when:** concrete Project Experience can be designed, improved through reusable lenses, tracked through lifecycle and tested without duplicate evidence ownership.
**Next check:** create only Project Experience records that genuinely emerge from Spine.

### Project Motivation

**Status:** active.
**Why it matters:** Motivation explains why gameplay becomes worth pursuing/salient but must not erase Situation Goal/Stake/Expectation/Plan.
**Current owners:** `game-analysis-reference/player-experience-motivation-planning.md`, Situation/Scenario links.
**Questions:** Which fields distinguish meta/experiential Motivation, in-play Motivation and Situation Goal? How should Motivation relate to Experience, Strategy and Plan? Are `seek / deepen / preserve / restore / resolve / avoid / validate` useful without rigid taxonomy? Should Motivation later receive canonical reusable ownership?
**Closed when:** real decisions can be explained through Motivation without collapsing rational Situation fields or creating duplicate taxonomy.
**Next check:** for each selected Spine decision, state concrete Motivation from Player Context and compare with local-owner alternative option motivations.

### Experience Opportunity / Legibility / Experiential Expectation

**Status:** active.
**Why it matters:** Experience may be mechanically possible but never become motivationally relevant if player does not understand/believe it is available.
**Current owner:** `game-analysis-reference/player-experience-motivation-planning.md`.
**Working relation:** `Experience Opportunity → Legibility / Awareness → Experiential Expectation → Motivation`.
**Questions:** Which stages need explicit fields vs lenses? What belongs in Scenario vs Experience/Motivation owners?
**Closed when:** concrete pass explains why supported Experience does/does not become expectation/Motivation without unnecessary standalone objects.
**Next check:** trace chain for at least one Experience/Motivation affecting a selected Spine decision.

### Experience Promise

**Status:** active candidate-unit question.
**Why it matters:** communication/demonstration of a specific Experience may have independent lifecycle across pre-play/onboarding/in-play/repeated confirmation.
**Current owner:** candidate section in `game-analysis-reference/player-experience-motivation-planning.md`.
**Questions:** Does it deserve independent owner? How distinct from generic `Player Promise` and actual `Experiential Expectation`? Can one Promise support several Motivations/contexts?
**Closed when:** real use shows independent reuse/change responsibility or simpler stable field/relation home.
**Next check:** create Promise record only if Spine needs same Experience expectation communicated/confirmed across several moments/units.

### Doubt / Concern

**Status:** active candidate-unit question.
**Why it matters:** player may decline/abandon otherwise valid motivation because they expect unwanted gameplay or doubt desired Experience exists.
**Current owner:** candidate section in `game-analysis-reference/player-experience-motivation-planning.md`.
**Questions:** Does it have independent reuse/change responsibility? How do true gameplay problems, insufficient proof/communication and audience mismatch stay distinct? How does Doubt weaken/redirect Motivation?
**Closed when:** real use shows whether separate owner improves reasoning more than inline Experience/Motivation field.
**Next check:** preserve only Doubts materially changing Spine decision/activity choice/motivation.

### Player Context / Expertise

**Status:** active.
**Why it matters:** same objective state/information can produce different perceived options, decisions and Experiences for different prior knowledge/preferences/expertise.
**Current owners:** `game-analysis-reference/player-experience-motivation-planning.md`, Situation and Scenario methods.
**Questions:** Which dimensions are useful: Rules Familiarity, Causal-Model Accuracy, Pattern Familiarity, Option Awareness, Strategic Repertoire, Execution Fluency, Content Familiarity, others? How should entry Player Context differ from evolving Mental Model/Expertise?
**Closed when:** first Spine explains selected decisions/learning without mixing game-provided Information with prior player knowledge/expertise.
**Next check:** state one concrete Player Context and record only expertise changes materially altering later decision space.

### Gameplay Event Method

**Status:** active.
**Why it matters:** reusable decisionless occurrences need planning responsibility, but gradual state/info/motivation changes must not all become Events.
**Current owner:** supporting Event record in `game-analysis-reference/gameplay-planning/README.md`.
**Questions:** Is enriched inline record sufficient? Which Event→State/Information/Situation/Execution/Experience/Motivation/delayed relations recur? Does repeated use justify `events.md` later?
**Closed when:** concrete Events are plan-able proportionally without becoming fake Situations or oversized universal taxonomy.
**Next check:** use Event record only for independently useful occurrences actually found in Spine.

### Execution Unit

**Status:** active provisional-unit validation.
**Why it matters:** while process variants/timing/intermediate states are unresolved, execution has planning questions not owned cleanly by Domain Operation, Scenario occurrence or Visual realization alone.
**Current owner:** `game-analysis-reference/gameplay-planning/executions.md`.
**Questions:** Which fields/Variants recur? Where is stable boundary with Domain/Scenario/Visual? What reconciles into Domain/Visual after design stabilizes? Does Execution later deserve canonical terminology?
**Closed when:** several real executions can be planned without duplicate systemic truth or missing gameplay-time responsibility.
**Next check:** use provisional record on different execution processes encountered by Spine.

### Cross-Unit Relations

**Status:** active.
**Why it matters:** many gaps are causal/reference relations between existing owners, not evidence that another entity type is needed.
**Current owner:** working relation map in `game-analysis-reference/player-experience-motivation-planning.md` plus scale-specific owners.
**Questions:** Which links recur and are worth naming? Which become graph noise or are better represented through shared state?
**Closed when:** staged Spine pass and reusable-owner comparison produce small relation vocabulary explaining handoffs/causality without exhaustive graphing.
**Next check:** record only links needed to understand selected chronology and local reusable alternatives; review repeated relation types afterward.

### Visual / Attention / Pacing / Reachability

**Status:** active.
**Why it matters:** whether Situation becomes perceived/salient and chronology feels overloaded depends on presentation, attention competition and timing, not only mechanics.
**Current owners:** `game-analysis-reference/gameplay-planning/scenarios.md`, reusable visual-planning owner.
**Questions:** Which interval concerns matter: foreground/background focus, missable signals, active/time-sensitive Situations, ongoing Executions, decision density, unresolved-decision age, new-information rate, interruptions, feedback delay, breathing room? Are qualitative reachability labels useful?
**Closed when:** Spine explains perception/pacing/reachability without fake numeric precision.
**Next check:** annotate only material attention/pacing intervals and reachability distinctions where interpretation changes.

### Situation Likelihood / Probability

**Status:** active but not yet quantitative.
**Why it matters:** one selected Spine cannot establish how likely a Decision Situation is across players/paths.
**Current owners:** Scenario/Situation methods; future balance/evidence work.
**Question:** what evidence is sufficient before numeric likelihood is meaningful?
**Closed when:** qualitative reachability proves sufficient or later method combines multiple paths, Player Contexts, Event frequencies and attention/discoverability evidence.
**Next check:** do not assign percentages in first Spine; record qualitative reachability/missing evidence.

### Project Filesystem Shape

**Status:** active.
**Why it matters:** physical structure should follow actual reuse/review responsibility, not ontology symmetry.
**Current owners:** `game-planning/README.md`, project README(s).
**Questions:** when should units remain one file vs folders, and which owner-local `ideas/` workspaces become useful for entities, Variants, Versions and Low-Level Elements?
**Closed when:** real unit count/reuse makes smallest clear structure obvious.
**Next check:** create no empty mirroring structure; split only when owner/workspace actually needs it.

### Documentation Examples / Hardening

**Status:** active documentation-quality rule.
**Why it matters:** abstractly correct docs can still systematically produce wrong inferences.
**Working rule:** use concrete examples wherever they materially reduce ambiguity; short examples stay inline; separate full practical example files are reserved for complete real artifacts. High-level examples remain useful even after full examples exist.
**Current examples:** target Spine/Unit/Low-Level Element high-level examples in current workflow/principle owners.
**Validation:** the Use-Case Map/bootstrap implementation is complete; use fresh-chat assimilation through UC-01 and selected gameplay use cases as one recurring hardening test rather than as a separate implementation concern.
**Closed when:** key boundaries have useful examples/counterexamples and fresh-chat review no longer repeats the same misunderstandings.
**Next check:** when a chat makes a reasonable wrong inference, inspect docs/navigation and add the smallest useful clarification; periodically rerun a fresh-chat bootstrap check.

## 4. Deferred / Next-Order Methodology Concerns

These are recognized gaps. They do not block current staged Spine pass unless they become load-bearing.

### Gameplay Loop Validation
**Status:** deferred.
**Concern:** empirical/source-backed Loop-boundary validation; recurrence wording; extracting Loops from recurrent causality rather than one Scenario chronology.
**Resume when:** Spine shows repeated/re-entered causal structures worth testing as Loops.

### Player Strategy
**Status:** deferred.
**Concern:** canonical definition/owner/boundaries and relation to Motivation, Goal, Plan and Dynamics.
**Resume when:** repeated player-authored planning across decisions becomes load-bearing.

### Broader Balance
**Status:** deferred.
**Concern:** architecture spanning Versions, Domain/economy, Strategies, Dynamics and session/campaign horizons.
**Resume when:** Strategy/temporal structure is clearer or real balance decision requires it.

### Dynamic ↔ Progression
**Status:** deferred.
**Concern:** authored/structured unlock/ownership change vs operative systemic tendency.
**Resume when:** concrete candidate Dynamic/progression relation becomes ambiguous.

### Game Domain / Economy Detailed Method
**Status:** deferred.
**Concern:** exact reusable Domain/economy planning method when current state/operation ownership becomes insufficient.
**Resume when:** Spine/Execution pass exposes missing Domain ownership or repeated economy-model questions.

### Complete Planning Operating Model
**Status:** deferred.
**Concern:** orchestration gaps not solved by current workflows/Goal Map.
**Resume when:** repeated use exposes concrete failure rather than abstract desire for completeness.

### Repository Templates / Reference Objects
**Status:** deferred implementation; observe candidates during Spine.
**Concern:** repository templates should support useful recurring unit/entity files, while Reference Objects should be considered only where literal materialized copies genuinely need stale-use detection. Exact template inventory, repository ownership and RO placement remain open.
**Current tooling boundary:** `gdoc` has no supported repository-native `.linked-notes` route; do not invent live markers, IDs or cross-repository template behavior.
**Resume when:** a real independently useful file type or literal-sync responsibility appears and repository boundary is supported.

### Specialized Reference Research
**Status:** deferred as a separate future pass.
**Concern:** material uncertainty may arise from Spine, reusable owner, Low-Level Element or another planning context and become a Research Question. Recording question does not require launching full research workflow immediately.
**Target direction already preserved:** Research should route from the uncertainty to findings/evidence and then back to the affected real owners/Spine; it does not need to pass through legacy Draft.
**Resume when:** concrete question can change design decision and original specialized research source is available for reconciliation with current reference methodology.

### Full Practical Documentation Examples
**Status:** deferred until suitable real artifacts exist.
**Concern:** preserve complete real planning artifacts as frozen documentation examples without allowing active project evolution to mutate them.
**Resume when:** a complete real Spine and complete reusable unit are mature enough to copy/freeze as examples. High-level inline examples remain in place regardless.

## 5. Immediate Next Work

Current next planning sequence:

```text
continue selected non-branching opening Spine in game-planning/survivor-base/scenarios/opening-spine.md
→ consult relevant legacy Draft Planning Items/status/provenance
→ state Target Game Version / Scope
→ set one explicit Player Context
→ walk coherent chronology through persistent adaptation
→ preserve Before → Inside → After / Handoff continuity
→ record concrete unit manifestations
→ identify material Low-Level Elements / candidate responsibilities / handoffs
→ use scoped Idea work for element-level uncertainty when useful
→ preserve Domain + Visual handoffs
→ trace Loop/Dynamic candidates only when recurrence/tendency appears
→ after chronology stabilizes enough, expand independently useful reusable owners
→ compare owners back against Spine
→ later use reusable units to construct/test other Scenario combinations.
```

Use `game-planning-use-case-map.md` to bootstrap new chats or resolve required read routes; it is navigation, not a mandatory first step in every planning pass.

In parallel, note only concrete template opportunities, literal-sync/Reference Object candidates, Research Questions and unresolved owner questions as they appear. Their later implementation/research passes are not a mandatory linear tail of the Spine sequence.
