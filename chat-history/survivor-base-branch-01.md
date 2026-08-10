# Survivor Base Branch 01 — Source And Consolidation Ledger

Status: supporting provenance / consolidation ledger
Project: Survivor Base
Canonical project owner: [`../game-planning/survivor-base/game-planning-draft.md`](../game-planning/survivor-base/game-planning-draft.md)

## 1. Purpose

This file preserves the source boundary and message-level coverage used for the August 2026 Survivor Base / game-creation-methodology consolidation.

It exists so future updates can check:

```text
which source contribution was reviewed;
what meaning it added;
where that meaning was routed;
whether it was accepted, kept as an Idea,
kept as a Content Premise, deferred,
or used to update reusable methodology.
```

This file is **not** a canonical game-design owner.

## 2. Source Boundary

### SB-B01-SRC00 — baseline dialogue transcript

Selected file at the beginning of this consolidation:

`survivor-base-dialogue-after-ideas-files(1).txt`

SHA-256: `70aca8ab06f874b9029478370887696b26b493fe6ec63fbb3fa50a5008014528`

The same transcript was later re-uploaded as `survivor-base-dialogue-after-ideas-files(2).txt`; the bytes and SHA-256 are identical. The later upload was used to point at the boundary, not to reset it.

The baseline transcript says it contains 12 main messages. Its own accuracy note remains authoritative: the first five were reconstructed from the then-available conversation summary, while messages 6–12 were available from active history.

### SB-B01-SRC01 — incoming gameplay-ideas source

`survivor-base-pdf-game-ideas (1)(4).txt`

SHA-256: `4f543c1c03b842c63694bc4a073b45dcd0ec9c1a9aebb27e67c96b08c75b49c4`

This is the gameplay/world/mechanic/content/scenario-premise source whose numbering `1, 1.1, 2, 3, 4, 5, 6, 8, 9, 12, 13, 14, 16, 17` is preserved in the project Idea/Content-Premise workspaces.

## 3. Coverage Rule

The selected boundary is `SB-B01-SRC00`.

After that source was first supplied, all substantive later discussion was reviewed for one or more destinations:

```text
Survivor Base Ideas;
Survivor Base Content Premises;
Survivor Base canonical Draft, only if explicitly accepted cross-cutting meaning required promotion;
reusable game-creation workflow;
reusable reference/transformation principles;
reusable Situation / Loop / Scenario methods;
documentation Use-Case Registry;
supporting provenance only.
```

The early post-boundary span was partly compressed by the conversation system before this repository package was built. Where exact per-message wording was no longer available, this ledger marks the contribution as `reconstructed from conversation summary / generated working files` instead of pretending to quote it verbatim.

## 4. Early Post-Boundary Consolidation Span

### SB-B01-C01 — fixed gameplay ideas and research span

Source status: reconstructed from the active conversation summary plus generated files `survivor-base-fixed-game-ideas.txt` through `v5`.

Reviewed meaning:

- user selected items `1, 6, 8, 9` for preservation and later also selected `12, 13, 14`;
- item `3` was refined into energy reserve vs short-term power/fatigue, mobilisation while a target remains attainable, and readable body-mass/energy threat;
- item `4` was split into `4A` world-history/lore variants and `4B` a separate possible near-universal infection-history model;
- item `16` was refined to a possible slave/forced-status mechanic with different reactions, without inventing a full slavery simulation;
- item `17` was refined toward political-group conflict, non-game-over regime change, player side-switching and the open problem of leadership/government/player continuity;
- items `2 + 5` were researched and then fixed as a model with continuous microvariation but a limited number of gameplay-significant strain groups;
- animal circulation/reservoir/evolution was retained as one mechanism by which significant lineages can persist, move and return;
- successful new strain groups may fail, coexist, displace an older line, or in suitable fictional biology form a new descendant profile through mixed infection/recombination/reassortment-like logic;
- player-facing strain meaning should come from evidence and behavior/symptoms/course/countermeasure differences rather than every infected receiving a unique visible strain ID.

Destinations:

- [`../game-planning/survivor-base/ideas.md`](../game-planning/survivor-base/ideas.md)
- [`../game-planning/survivor-base/content-premises.md`](../game-planning/survivor-base/content-premises.md)

Status boundary:

- preservation/fixation in the Idea workspace does not automatically promote all mechanics into the canonical Draft;
- research-supported biological plausibility is not itself a final fictional-virus architecture decision.

## 5. Later Main-Message Coverage

The IDs below are stable **ledger references**, not product/UI message IDs.

### SB-B01-U049 — provenance + documentation use cases + need for a creation workflow

Source status: user message; exact meaning available in active history.

Captured meaning:

- give messages stable numbers during work;
- maintain an updating file that records information for later consolidation and cites message numbers so omissions can be checked;
- build a real creative work process rather than only a system that asks good analysis questions;
- first create a documentation-repository use-case map/registry describing what the documentation lets the designer do and which owner explains each use case;
- only after game-planning/documentation workflow is clarified, separately develop methods for finding answers / brainstorming and documenting intermediate brainstorm work.

Destination:

- this ledger / `chat-history/Readme`;
- [`../game-planning-use-case-registry.md`](../game-planning-use-case-registry.md);
- [`../game-creation-workflow.md`](../game-creation-workflow.md).

### SB-B01-A049 — documentation-principles preflight and semantic registry distinction

Source status: assistant synthesis; accepted implicitly by continuation, not a standalone project decision.

Captured meaning:

- distinguish executable command UCM from semantic Use-Case Registry;
- treat a message ledger as provenance/workbench, not canonical project meaning;
- audit current documentation capabilities before designing detailed brainstorm methodology.

Destination:

- reusable registry and ledger boundaries.

### SB-B01-U050 — analysis system exists; synthesis workflow is missing

Captured meaning:

- current Situation/Loop/Dynamic/Scenario + analysis templates can inspect a game almost as if it already existed and can also analyze existing games;
- missing layer is how to invent a new game and form those units from zero;
- many ideas should be generated and combined rather than committing to the first one;
- introduce a whole-game `Concept` object;
- a spontaneous idea may concern any planning scale, Player Experience, a GSA concern, visual work or another specific planning field;
- questions can be generated by walking planning scales/fields;
- answers may come from references or brainstorming;
- references are extremely important;
- good zero-to-one routes include starting from a good seed attached to a reference or taking a feasible reference game and systematically changing its components.

Destination:

- `Game Creation Workflow`;
- `Game Planning` terminology.

### SB-B01-A050 — first synthesis-workflow model

Captured meaning:

- separate analysis/question generation from answer discovery, evaluation and integration;
- proposed a Concept bridge, Direction/Question/Ideas and reference decomposition;
- proposed mechanics/rules relations in Situation planning;
- proposed flexible next-depth routing rather than Situation → Loop → Dynamic → Scenario as a mandatory pipeline.

Later refinement:

- `Concept Candidate` wording was rejected in `SB-B01-U051`;
- Direction model was refined to `Design Direction → Brainstorm Prompt → Variants`.

### SB-B01-U051 — Concept, Prompt, Core Loop, feasibility, answer sources, Integration

Captured meaning:

- use `Concept`, not `Concept Candidate`;
- use Design Direction plus question/task/requirement and several variants;
- Concept should include a broad Core Loop view that explains the kinds of entities, dependencies and decisions in the game;
- an initial good idea should preferably be attachable to a reference;
- ability to actually implement a representative demo and its visuals matters when choosing an initial direction;
- reference decomposition generates questions through planning scales/fields;
- choose which reference part to change; selection can be situational or aided by principles;
- answer discovery: first borrow a part/solution from another reference; then use brainstorming to transform existing solutions or invent something without a direct reference;
- detailed brainstorm methods are a separate future task;
- after first-pass evaluation of variants, perform `Integration`: inspect each idea in a wider game context;
- add explicit Situation mechanics/rules relationships for occurrence, decisions/consequences and Experience.

Destination:

- Game Creation Workflow;
- Reference First owner;
- Situation/Loop/Scenario method updates.

### SB-B01-A051 — refined workflow + cross-scale audit proposal

Captured meaning:

- `Brainstorm Prompt` as Question/Task/Requirement/Problem;
- early `Seed + Reference + Demo Feasibility` gate;
- `Transformation Target Selection`;
- Local Evaluation → Integration → re-evaluation;
- cross-scale audit of Situation/Loop/Dynamic/Scenario fields.

Status:

- the next user message refined transformation-target prompts and Integration workspace rather than rejecting the route.

### SB-B01-U052 — transformation-target prompts + Variant workspaces + Integration Probes

Captured meaning:

Potential prompts for choosing what to change in a reference:

- weak parts;
- outdated game-design solutions;
- overused/common parts;
- replacement by ideas already stored/planned elsewhere;
- trend-backed replacement;
- conceptual simplification/compression;
- removal of expensive parts;
- replacement of the Experience created by an expensive part, or redesign so that Experience is no longer required;
- removal/replacement of low-value parts that do not really work.

Evaluation / integration work should preserve, per Variant:

- risks;
- additional/refinement ideas;
- open questions about the Prompt and the specific Variant;
- pros/cons;
- first-pass comparisons;
- wider-context evaluation through Situations/Loops/Dynamics/Scenarios/Content Premises and other Ideas;
- possibility that two individually weaker Ideas become strong in combination;
- optional deep `integration` workspace containing temporary Situation/Loop/Dynamic/Scenario/etc. versions of the game with one Variant hypothetically accepted.

Destination:

- Game Creation Workflow (`Transformation Target Prompts`, Variant Workspace, Integration Probe, Combination Evaluation).

### SB-B01-A052 — `Integration Probe` and evaluation-layer proposal

Captured meaning:

- preserve `Gameplay Situation` as a meaningful-decision unit; use Scenario Beats for decisionless experience unless a separate reusable non-decision unit later proves useful;
- name temporary hypothetical wider-context artifacts `Integration Probes`;
- distinguish Local / Integrated / Combination Evaluation;
- explicitly search for what a Variant removes, simplifies or makes redundant.

Accepted/refined by:

- `SB-B01-U053`;
- `SB-B01-U054`.

### SB-B01-U053 — Situation mechanics/rules clarification

Captured meaning:

- `Hard Preconditions`, `Occurrence Drivers / Alternative Causes`, `Frequency Controls` and the `Occurrence Model` already cover the mechanics/rules that allow/generate a Situation;
- do **not** create a duplicate occurrence-mechanics block;
- add the remaining mechanics/rules that shape decisions and consequences;
- useful umbrella is `Mechanics / Rules Relations`:
  - Situation-Enabling / Generating Rules → existing Occurrence Model;
  - Decision-Shaping Rules → availability, cost/value, information, stakes/risk, consequences, wait/do nothing;
  - Experience-Shaping Rules if material;
- agree with adding/using `Causal Basis` at the relevant planning scales;
- agree with `Probe` terminology and Local/Integrated/Combination Evaluation.

Destination:

- Situation/Loop/Scenario methods;
- Game Creation Workflow terminology.

### SB-B01-A053 — final causal-basis formulation

Captured meaning:

- treat Situation Occurrence Model as the occurrence/generation causal basis;
- add Decision-Shaping and optional Experience-Shaping Mechanics/Rules relations;
- one rule can affect several Situation facets without copying its full definition several times;
- Loop gets a loop-sustaining Causal Basis;
- Dynamic already has an appropriate Causal Basis;
- Scenario should only record operative mechanics/rules needed to understand the concrete chronology;
- Probe and evaluation terminology summarized.

Accepted by:

- `SB-B01-U054`.

### SB-B01-U054 — explicit acceptance + request for repository update plan

User statement:

> Согласен со всем, формулировками и шаблонами.

Scope of acceptance:

- the immediately preceding causal-basis / mechanics-relations formulation;
- `Concept`, `Design Direction`, `Brainstorm Prompt`, `Variant`, `Integration Probe`;
- Local / Integrated / Combination Evaluation;
- Variant workspace structure discussed immediately before.

Additional request:

- update the repo;
- include current Ideas and Content Premises;
- review all messages after the selected transcript boundary;
- build a strict documentation/game-planning workflow;
- brainstorm methods remain a separate later topic.

Destination:

- all reusable owners and Survivor Base project-local workspaces in this package.

### SB-B01-U055 — source boundary correction + 1.1 routing + Views status

Captured meaning:

- the re-uploaded transcript identifies the boundary; review all messages after the original appearance of that transcript;
- route item `1.1` to `ideas.md`;
- Survivor Base `views/` are temporary/working files and should be treated as current working views, not as discarded historical material;
- request an updated file-update plan.

Destination:

- source boundary in this ledger;
- Survivor Base Ideas;
- Survivor Base README authority wording.

### SB-B01-A055 — updated file-update plan

Source status: assistant planning output.

Captured meaning:

- source-ledger first;
- semantic Use-Case Registry;
- Game Creation Workflow;
- cross-scale Causal Basis changes;
- Survivor Base Ideas + Content Premises;
- current derived Views remain working/current but non-canonical;
- canonical Draft only changes if explicit cross-cutting accepted meaning requires it;
- detailed brainstorm methodology deferred.

Status:

- approved for packaging by `SB-B01-U056`.

### SB-B01-U056 — `давай архив`

Meaning:

- explicit authorization to build the reviewable replacement archive/package;
- **not** authorization to commit or push.

### SB-B01-A056 — archive build start

Meaning:

- selected current `gdoc/main` as repository source;
- began reading archive/apply workflow and exact target owners.

No game-design meaning added.

### SB-B01-U057 — clarification about package-owner wording

User asked what changed in `obs-planning-docs`, stating they did not think they had changed anything.

Disposition:

- operational clarification only;
- no Survivor Base or reusable game-planning meaning.

### SB-B01-A057 — clarification

Meaning:

- explained that the comment referred to reusable archive-command owner docs in the separate `obs-planning-docs` repository, not to user changes in `gdoc`;
- confirmed no repository changes had been made.

### SB-B01-U058 — `продолжи`

Meaning:

- continue the already authorized archive build;
- no new design meaning.

## 6. Consolidation Destination Summary

| Meaning family | Destination in this package |
|---|---|
| incoming Survivor Base system/world/hybrid ideas | [`../game-planning/survivor-base/ideas.md`](../game-planning/survivor-base/ideas.md) |
| standalone preliminary content units | [`../game-planning/survivor-base/content-premises.md`](../game-planning/survivor-base/content-premises.md) |
| message/provenance checking | this file + [`Readme`](Readme) |
| supported documentation capabilities | [`../game-planning-use-case-registry.md`](../game-planning-use-case-registry.md) |
| zero-to-one synthesis workflow | [`../game-creation-workflow.md`](../game-creation-workflow.md) |
| Concept / Direction / Prompt / Variant / Probe / evaluation meanings | [`../principles/game-planning-principles-and-terminology.md`](../principles/game-planning-principles-and-terminology.md) |
| reference-target selection / feasible baseline / removal-substitution reasoning | [`../principles/reference-first-and-controlled-transformation-principles-and-terminology.md`](../principles/reference-first-and-controlled-transformation-principles-and-terminology.md) |
| Situation/Loop/Scenario causal rule relations | [`../game-analysis-reference/gameplay-planning/`](../game-analysis-reference/gameplay-planning/) |
| detailed brainstorming techniques | deferred; no owner created in this package |

## 7. Baseline Transcript — Preserved Source

The baseline source is copied below verbatim as supplied. Its own reconstruction labels remain part of the source and must not be erased.

~~~text
Survivor Base — диалог после сообщения с файлами промпта и идей

Количество основных сообщений в этом файле: 12
- Пользователь: 6
- Ассистент: 6

Граница:
- сообщение пользователя, в котором были приложены файлы промпта и идей, НЕ включено;
- файл начинается с ответа ассистента сразу после него;
- файл заканчивается текущим запросом пользователя о создании transcript;
- служебные tool-вызовы и короткие рабочие update-сообщения не считаются отдельными основными репликами.

ВАЖНО О ТОЧНОСТИ:
Первые 5 основных реплик к моменту создания этого файла уже были свёрнуты системой в контекстное резюме и их полный исходный текст не доступен в активном окне разговора. Они восстановлены по доступному контекстному резюме и явно помечены как [ВОССТАНОВЛЕНО — НЕ ДОСЛОВНО].
Сообщения 6–12 приведены по доступной истории разговора.

================================================================================
СООБЩЕНИЕ 1 — АССИСТЕНТ
[ВОССТАНОВЛЕНО — НЕ ДОСЛОВНО]
================================================================================

После получения файла была сделана первичная reconciliation игровых идей с current Survivor Base planning.

Основной смысл ответа:
- superseded / no longer relevant идей практически не найдено;
- №6 «спящие заражённые» был первоначально оценён как почти уже присутствующий через low-activity/torpor;
- №8 «потеря большой части здания» был первоначально сильно привязан к уже существующему PI-006 про потерю/блокировку/возврат сектора;
- №1 про длительную осаду ордой был признан частично покрытым: current horde systems уже поддерживают perimeter spread, блокировку входов, climbing/body piles и длительное внешнее давление, но не полностью фиксируют prolonged full siege, roof criticality, smell/psychological pressure и density-airborne infection;
- №2 + №5 про штаммы были признаны частично покрытыми: current planning уже имеет changing strain profile between runs, current-strain knowledge и research/treatment, но остаётся вопрос нескольких одновременно существующих штаммов и strain-specific лечения/поведения;
- №3: energetics/torpor уже есть, но body mass → strength/energy/barrier threat остаётся новой частью;
- №4: current planning пересекается с идеей, но evolutionary pandemic history, near-universal mild infection и редкие never-infected люди остаются новыми;
- №9: точная vertical recapture premise не зафиксирована;
- №12: накопление recovered/immune как long-term Dynamic остаётся новой частью;
- №13: persistent post-infection personality/need/culture change остаётся новой частью;
- №14: offensive raids on human groups, raider/slaver identity и prison premise остаются unresolved;
- №16: slavery как отдельная система не зафиксирована;
- №17: leadership/government change without game over и player continuity under a coup остаются unresolved.

Предлагалось обсуждать связанные блоки:
1) strains;
2) long-term biological/social transformation;
3) human societies / slavery / power;
4) prolonged siege;
5) mega-event;
6) body mass;
7) vertical lost-floor scenario.

================================================================================
СООБЩЕНИЕ 2 — ПОЛЬЗОВАТЕЛЬ
[ВОССТАНОВЛЕНО ПО ДОСЛОВНОЙ ЦИТАТЕ В КОНТЕКСТЕ]
================================================================================

Там практически нет неактуальных игровых идей

================================================================================
СООБЩЕНИЕ 3 — АССИСТЕНТ
[ВОССТАНОВЛЕНО — НЕ ДОСЛОВНО]
================================================================================

Согласился с поправкой: не нужно искать superseded идеи ради заполнения категории.

Было уточнено правило:
- считать идею superseded только при реальном противоречии с более поздним current project meaning;
- отсутствие реализации или неполная проработка не делает идею неактуальной;
- в этом наборе superseded-категория фактически может остаться пустой.

================================================================================
СООБЩЕНИЕ 4 — ПОЛЬЗОВАТЕЛЬ
[ВОССТАНОВЛЕНО ПО ДОСЛОВНОЙ ЦИТАТЕ В КОНТЕКСТЕ]
================================================================================

Я думаю что стоит воспринимать то, где подписано ситуация как сценарий по нашей терминологии, это единица контента, которая имеет значение и которую можно оценить как сценарий

================================================================================
СООБЩЕНИЕ 5 — АССИСТЕНТ
[ВОССТАНОВЛЕНО — НЕ ДОСЛОВНО]
================================================================================

Согласился с уточнением и скорректировал taxonomy.

Основное правило:
старая пометка «ситуация»
→ content unit / Scenario premise
→ после разработки может стать Scenario
→ Scenario состоит из Scenario Beats
→ внутри него возникают реальные Gameplay Situation Instances.

При этом current Gameplay Situation остаётся локальной meaningful player decision problem.

Было отдельно уточнено, что current Scenario — это concrete chronology, которая может содержать несколько Situation Instances, system execution, observation/information reveal, waiting/routine, transitions, consequences/payoffs и recovery.

Также была исправлена предыдущая классификация №8 и №9:
даже если механика lost/reclaim sector уже существует, конкретные идеи «потеря большой части здания» и «потерян первый этаж, надо спускаться сверху» остаются самостоятельными Scenario/content ideas, которые нужно сохранить и позднее оценить как сценарный контент.

================================================================================
СООБЩЕНИЕ 6 — ПОЛЬЗОВАТЕЛЬ
================================================================================

Давай еще раз рассмотрим идеи

================================================================================
СООБЩЕНИЕ 7 — АССИСТЕНТ
================================================================================

Да. После твоего уточнения про старое слово «ситуация» я бы пересобрал reconciliation заметно иначе.

Ключевое правило теперь такое:

- старое **«ситуация»** → обычно **Scenario/content idea**, то есть значимая единица контента, которую позже можно развернуть в конкретную chronology;
- она **не исчезает только потому, что необходимые для неё механики уже есть**;
- внутри такого Scenario уже могут находиться несколько Gameplay Situations, execution, observation, consequences, recovery и т. д. Это соответствует нынешнему определению Scenario в репозитории.
- старая идея считается полностью уже отражённой только когда сохранён **сам её существенный игровой смысл**, а не просто базовая механика, позволяющая когда-нибудь такое получить.

`main` с прошлого просмотра не изменился: HEAD всё ещё `64975eb…`.

## Уже практически полностью есть

### 3. Энергетика заражённых и анабиоз — **основа уже есть, кроме массы тела**

Старое:

- изменённый энергообмен;
- долгое существование;
- анабиоз;
- толстый заражённый потенциально сильнее из-за массы/запаса энергии;
- можно оценивать его массу/энергетический потенциал.

В current planning уже довольно подробно есть:

- infected не энергетически автономны;
- fresh используют собственные ресурсы;
- old infected истощаются;
- переходят в low-activity/conserved state;
- ищут пищу и воду;
- scavenging/cannibalism/animals поддерживают их существование.

**Остаётся реально новым:** влияние индивидуальной массы тела заражённого на запас энергии, физическую силу, давление на барьеры и читаемую игроком угрозу.

Поэтому идея не требует заново обсуждать всю энергетику. Нужен только вопрос:

> Хотим ли мы, чтобы физическая масса конкретного infected была системно значимым параметром?

---

## Частично есть, но старая идея всё ещё содержит отдельный смысл

### 1. Долгая осада огромной ордой — **Scenario/content idea стоит сохранить**

Старое описание — не просто «есть орда». Это особый период игры: наружу почти невозможно выйти, масса облепляет базу, лезет вверх, давит на периметр, шумит, создаёт санитарное и психологическое давление; крыша тоже может перестать быть безопасной.

Механическая база уже очень сильная:

- migrating infected pressure;
- конечная infected population;
- aggregation → perimeter spread → multi-point siege → penetration opportunity;
- блокировка входов;
- обтекание фасада;
- поиск окон/лестниц/technical routes;
- climbing/body pile candidates;
- заражённые могут остаться возле базы после миграции.

Но **сам длительный siege Scenario ещё не сводится к этим правилам**.

Я бы сохранил его примерно как content premise:

> **Prolonged Horde Siege:** база на длительный период почти теряет внешний мир; давление постепенно переходит с земли на альтернативные входы, верхние уровни и крышу, а внутренние запасы, ремонт, санитария и психологическое состояние начинают определять выживание.

Отдельно остаются вопросы:

- крыша как полноценный фронт;
- постоянный шум/стресс толпы;
- запах/биологическое загрязнение;
- может ли высокая концентрация менять air-transmission risk.

То есть **идея 1 — живая и полезная**.

---

### 1.1. Ядерный / химический крупный event — **практически новый**

Старое предложение — большие disruptive events и даже возможность настройки, нужны ли игроку такие события вообще.

В current planning я не вижу эквивалента.

Причём здесь два разных вопроса:

1. нужны ли **редкие world-transforming events** вообще;
2. нужны ли именно **ядерный/химический** варианты.

Я бы не смешивал это с ордой. Это отдельная content/system direction.

---

### 2 + 5. Разные штаммы — **половина идеи уже стала центральной системой, половина ещё нет**

Старые идеи предлагают разные штаммы/группы штаммов и возможность распознавать их по поведению, симптомам и по-разному лечить/контрить.

Current planning уже содержит очень много strain-specific design:

- профиль инфекции может меняться между ранами;
- current strain имеет свои routes/hosts/properties;
- host range исследуется;
- disease course зависит от strain;
- treatments/prevention могут разрабатываться;
- животные, vectors и cooking safety тоже strain-dependent.

Но текущая архитектура в основном говорит о **`current strain` одного рана**.

Старая идея идёт дальше:

> одновременно существуют несколько различимых strain/group-of-strains внутри одной кампании.

Это всё ещё серьёзное отдельное решение.

И именно отсюда следуют:

- разные infected рядом могут требовать разного подхода;
- идентификация strain сама становится gameplay;
- разные лекарства;
- разные симптомы;
- несколько эпидемиологических угроз одновременно.

**Это одна из главных идей, которые реально надо обсудить.**

---

### 4. История вируса и почти все заражены — **две отдельные идеи**

Старое описание содержит:

1. историю пандемии: сначала сверхзаразная форма → практически массовое заражение → позднее эволюция в сторону сохранения носителей;
2. почти все люди могут уже носить какие-то штаммы, не обязательно превращающие их.

Current planning поддерживает эволюционную вариативность и changing-strain world, но **эту конкретную историю пандемии не фиксирует**.

Ещё важнее второе: «почти все уже чем-то заражены» фундаментально меняет понятие clean person.

Это не просто lore. Оно влияет на:

- intake;
- testing;
- classification;
- immunity;
- recovered states;
- disease notebook;
- смысл clean core.

Поэтому я бы рассматривал **«почти все уже несут infection history» как отдельное крупное design decision**, а origin story — как связанную worldbuilding hypothesis.

---

### 6. Спящие заражённые — **mechanic есть, конкретный horror/content use всё ещё полезен**

Старая идея прямо формулируется как «ситуация / хоррор-эффект»: заражённые выглядят мёртвыми, замирают и внезапно реагируют при приближении.

Low-activity/torpor уже есть в current planning.

Но теперь, с твоим уточнением, я бы **не ставил её в “полностью уже есть”**.

Потому что старый смысл ещё включает content payoff:

> игрок входит в пространство с телами/неподвижными infected и не знает, какие из них действительно безопасны.

Это уже хороший небольшой Scenario или recurring Scenario pattern.

То есть:

**system rule — уже есть;
content realization — стоит сохранить.**

---

### 8. Потеря большой части здания — **Scenario idea, не поглощена PI-006**

Старый пункт описывает конкретное игровое состояние: потеряна большая часть здания и игрок остаётся в сильно урезанной позиции.

Current `PI-006` уже позволяет:

- терять сектора;
- оставлять людей внутри;
- обходить их;
- снабжать через границу;
- позже возвращать;
- жить с permanent scars.

Но **Scenario «почти вся база потеряна» остаётся самостоятельным контентом**, потому что проверяет системы в экстремальном состоянии.

Я бы его точно сохранил.

Особенно интересно, что это уже не только containment Scenario, а почти **recovery game state**:

> минимальная сохранившаяся территория → восстановить способность жить → решить, что возвращать → какие потери принять навсегда.

---

### 9. Первый этаж потерян, надо спускаться сверху — **отдельный Scenario**

Это ещё яснее.

Нынешние systems позволяют ему существовать, но сам Scenario не записан.

И он интересен именно пространственной инверсией:

> обычно заражённые приходят снаружи и игрок держит периметр; здесь безопасная часть оказывается сверху, а опасная зона находится **между игроком и внешним миром**.

Отсюда естественно могут возникнуть несколько Gameplay Situations:

- какой маршрут вниз выбрать;
- разведать или прорываться;
- кого послать;
- нужен ли вообще первый этаж прямо сейчас;
- можно ли создать новый выход;
- стоит ли рисковать ради инфраструктуры;
- что делать с fresh infected, оставшимися после вспышки.

Так что **№9 я бы однозначно сохранил как Scenario-content item**.

---

### 12. Со временем больше recovered / immune — **состояния есть, Dynamic ещё нет**

Старое: по мере долгой жизни базы число переболевших/иммунных может расти, и это постепенно меняет общество и политические группы.

Current planning уже имеет:

- recovered;
- carriers;
- resistant;
- rare immune;
- political groups по biological status.

Но там нет принятого принципа:

> **успешное долго живущее общество систематически накапливает таких людей.**

А это уже именно возможная Gameplay Dynamic:

```
переживаем вспышки
→ часть людей получает protection/recovery state
→ структура населения меняется
→ меняются относительные риски и полезность групп
→ меняется политика базы
→ следующие outbreaks проходят в другом обществе.
```

Это стоит обсуждать.

---

### 13. Постинфекционные изменения характера → изменение общества — **идея всё ещё существенно новая**

Старый смысл довольно радикальный: перенесённые штаммы могут надолго менять характер/потребности, и накопление таких людей может менять моральные нормы и характер всей базы.

Current planning имеет изменения агрессивности, рациональности и потребностей **во время disease course**, а носительство может давать buffs/debuffs.

Но старая идея сильнее:

> болезнь оставляет устойчивые психологические/поведенческие последствия после survival.

И ещё дальше:

> если таких людей становится много, меняется emergent culture общества.

Это не принято.

Я бы объединил №12 и №13 в одну большую тему:

**Biological demographic evolution of the base.**

Она выглядит довольно органично для текущего Survivor Base.

---

### 14. Рейды на других людей + разные типы баз — **частично есть**

Старое:

- нападать на других survivors;
- raider base;
- slave-owning base;
- обычная survival base;
- бывшие преступники;
- prison scenario.

Current planning уже имеет:

- external survivor groups;
- competition/trade/conflict;
- global map;
- tactical raids;
- governance trajectories;
- loyalty/force/political structures.

Но **рейд на человеческую базу именно как агрессивное присвоение ресурсов/людей** я не вижу принятым.

И разные типы общества тоже пока скорее возможные trajectories, а не полноценные playable social models.

Особенно я бы не потерял **prison Scenario**. Это уже не просто lore:

> изначально ограниченное число охранников + заключённые как необходимый manpower + вопрос, кого освобождать/вооружать/допускать к власти.

Это сильная Scenario-shell / run-start idea.

---

### 16. Рабство — **новая системная линия**

Старое очень короткое, но однозначное: возможность рабства и разное отношение людей к этому.

Current planning имеет:

- coercion;
- punishment;
- arrest;
- exile;
- execution;
- inequality;
- force;
- authoritarian trajectories.

Но это **не равно slavery**.

Если рабство существует системно, оно требует хотя бы:

- forced labor;
- status человека;
- enforcement;
- ownership/control;
- escape/resistance;
- отношение остальных;
- производственную выгоду;
- political/social consequences.

Поэтому это действительно отдельная unresolved idea.

---

### 17. Переворот / смена правительства без game over — **частично подготовлено, но главный смысл новый**

Старое предложение очень конкретное:

> прежнего главного могут свергнуть, но игра продолжается; бывший руководитель может сам оказаться внизу иерархии; при конфликте можно выбрать сторону.

Current planning уже имеет:

- Command Circle;
- loyalty;
- armed force;
- political hierarchy;
- possible governance trajectories;
- открытый вопрос о последствиях смерти/раскола высшего руководства.

Но главный design rule ещё не решён:

> **игрок привязан к конкретной власти или к продолжающей существовать базе?**

Если ко второй — переворот может быть не game over, а мощным state transition.

Это, на мой взгляд, одна из наиболее важных старых идей.

---

## В итоге я бы теперь разделил идеи не на «старые/новые», а на три полезных слоя

### 1. Scenario / content units, которые надо сохранить

- **1 — длительная осада ордой;**
- **6 — спящие заражённые / ложные трупы;**
- **8 — большая часть здания потеряна;**
- **9 — первый этаж потерян, надо спускаться;**
- часть **14 — prison starting scenario;**
- часть **17 — coup / violent power struggle scenario.**

У них уже может быть достаточно системной основы, но **сам контент от этого не перестаёт быть отдельной идеей**.

### 2. Системные идеи, которые ещё требуют решения

- **2 + 5 — несколько штаммов одновременно;**
- **3 — масса тела infected как механически значимая переменная;**
- **4 — почти все люди имеют infection history;**
- **12 + 13 — долгосрочная биологическая трансформация населения и общества;**
- **14 — агрессивные human raids / разные social-base trajectories;**
- **16 — slavery;**
- **17 — continuity of play through regime change.**

### 3. Большие world/event ideas

- **1.1 — nuclear/chemical catastrophe;**
- эволюционная история пандемии из **4**.

Здесь я **по-прежнему не вижу практически ничего, что стоило бы выбросить как superseded**.

И теперь я бы изменил порядок обсуждения. Не обязательно начинать с multi-strain. Я бы сначала прошёл **Scenario/content ideas**, потому что они позволяют проверить ценность уже существующих систем без принятия огромной новой архитектуры:

**9 → 8 → 6 → 1**, затем prison/coup из **14/17**.

А после этого уже системные расширения: **2+5 → 12+13 → 14+16+17 → 4 → 3 → 1.1**.

================================================================================
СООБЩЕНИЕ 8 — ПОЛЬЗОВАТЕЛЬ
================================================================================

Короче нам нужно сохранять контент премисы, которые сожно частично оценивать как сценирии, но они потом могут быть разобраны и помещены в файл сценариев, долдно быть место именно для таких премисов, предварительное. Где ори не до конца приняты. 2 не совсем понятно что ты имеешь ввиду под старое, файл содердит новые идеи и нудно внимательнее смотреть на формулировки, могут быть сходства с тем что уже зафиксировано в репозитории, но это тогда уточняющие идеи.

================================================================================
СООБЩЕНИЕ 9 — АССИСТЕНТ
================================================================================

Да. Два исправления к моему подходу.

**1. Нужен отдельный промежуточный слой для content premises.** Не стоит сразу помещать такие идеи в `views/scenarios.md`, потому что нынешний файл сценариев уже предназначен для **развёрнутых representative Scenarios** с хронологией, Beats, решениями и последствиями. При этом README сейчас вообще не предусматривает отдельного владельца для ещё не разобранных content premises.

Я бы сделал примерно такую цепочку:

```
incoming game idea
→ Content / Scenario Premise
→ предварительная оценка ценности
→ решение: оставить / изменить / отложить / не использовать
→ если premise требует нового game meaning:
     обновить Game Planning Draft
→ если premise достаточно интересен для detailed work:
     развернуть в Scenario
→ views/scenarios.md
```

И для этого, на мой взгляд, лучше отдельное место вроде:

```
game-planning/survivor-base/content-premises.md
```

а не раздел внутри `scenarios.md`.

Почему отдельный файл здесь оправдан: premise ещё **не Scenario**, но уже самостоятельная игровая единица, которую нельзя потерять. Например:

```
Потерян первый этаж, безопасная часть осталась выше
```

можно сохранить почти в исходном виде, не придумывая пока:

- точные Beats;
- точные Gameplay Situations;
- конкретный маршрут;
- состав заражённых;
- конкретные решения игрока;
- outcome.

При этом уже можно предварительно оценить: какие existing systems premise использует, какое gameplay/experience обещает, чем отличается от других premises, есть ли у него потенциал для meaningful decisions и стоит ли потом разбирать его как Scenario.

То есть это фактически **content backlog, но не мусорная корзина идей**: там лежат именно достаточно конкретные игровые premises, потенциально пригодные для превращения в Scenarios.

**2. Слово «старые» я использовал неправильно.** Да, PDF старый как источник, но **идеи из переданного файла для нашей текущей работы являются incoming/new ideas**. Сам файл прямо говорит, что там сохранены игровые идеи независимо от их дальнейшей судьбы, а не утверждает, что все они уже обсуждены.

Поэтому правильное сравнение для каждого пункта теперь такое:

```
Incoming idea
↓
есть ли похожий current meaning?
```

И дальше не просто `already exists / new`, а точнее:

```
A. Новый смысл
   В repo такого meaning нет.

B. Уточнение существующего meaning
   Основа уже есть,
   но incoming idea добавляет конкретное правило,
   поведение, consequence, content use или другое уточнение.

C. Новый Content Premise на существующих системах
   Механики уже существуют,
   но сама content unit / потенциальный Scenario новая.

D. Смешанный случай
   Premise новый
   + для него предлагается новое системное уточнение.

E. Уже действительно полностью отражено
   И базовый смысл, и существенная конкретизация
   уже присутствуют.

F. Явно противоречит current meaning
   Только тогда superseded / incompatible.
```

Это особенно меняет то, как надо читать формулировки.

Например **№6 про спящих заражённых** — не просто «уже есть torpor». Incoming idea добавляет конкретное применение: заражённый **выглядит как мёртвый и резко нападает при приближении**. Значит это как минимум **уточнение поведения + content premise**, даже если low-activity infected уже зафиксированы.

**№9 «потерял первый этаж, надо спускаться со второго»** — новый Content Premise на уже существующих containment/lost-sector systems.

**№3 про энергетику** — existing meaning действительно очень близок, но часть про вес конкретного заражённого и связанную с ним силу/энергию — **incoming уточняющая системная идея**, а не просто остаток чего-то старого.

**№1 про орду** — смешанный случай: current systems уже поддерживают siege, climbing, perimeter loss и т. п., но incoming формулировка добавляет **новый длительный content premise** и дополнительные детали этой осады.

Так что следующую сверку файла я бы делал именно по этой схеме, **почти построчно сохраняя дополнительный meaning формулировок**, а не пытаясь определить только «есть такая тема в Draft или нет». Это должно дать гораздо более точный список того, что реально нужно обсудить и сохранить.

================================================================================
СООБЩЕНИЕ 10 — ПОЛЬЗОВАТЕЛЬ
================================================================================

Давай еще раз рассмотрим

================================================================================
СООБЩЕНИЕ 11 — АССИСТЕНТ
================================================================================

Да. После повторного чтения **самого файла целиком** и сравнения формулировок с current Draft картина стала заметно точнее.

Главная поправка: я больше не вижу здесь раздела «идеи, которые уже можно вычеркнуть как дубликаты». Почти каждый пункт добавляет новый meaning — иногда большой, иногда маленькое уточнение, иногда отдельный content premise. Файл именно так и устроен: в нём собраны игровые/world/mechanic/content/scenario-premise идеи, а не готовые решения.

## Куда класть content premises

Я бы действительно добавил отдельный owner:

`game-planning/survivor-base/content-premises.md`

**Не `views/content-premises.md`.** Сейчас `views/` по правилам Survivor Base переорганизует meaning из canonical Draft и не должен самостоятельно становиться источником новых project decisions.

И не сразу `views/scenarios.md`: нынешний Scenario owner работает уже с конкретной chronology — starting state, unresolved parameters, Scenario Beats, решениями, execution, aftermath и т. д.

То есть граница получается хорошая:

```
incoming idea
→ content premise
→ preliminary review

если premise требует нового правила/system meaning:
  обсуждение → решение → Game Planning Draft

если premise становится достаточно определённым:
  detailed Scenario
  → views/scenarios.md
```

Причём **никакая отдельная сложная status system для `content-premises.md` не нужна**. В заголовке файла можно просто установить правило: всё находящееся здесь — candidate content meaning, не принятое автоматически. Для конкретного пункта отдельно писать что-либо только если мы его приняли, отвергли или он зависит от ещё не решённого system question.

Теперь сами идеи.

### 1. «Период типа ядерной зимы»

Это **новый content premise + несколько системных уточнений**.

Current planning уже содержит очень много необходимой основы: конечная масса заражённых, aggregation, perimeter spread, multi-point siege, потеря входов и наружной оболочки, climbing/body piling и длительное лишение базы наружной свободы.

Но incoming formulation намного конкретнее: это не просто орда возле базы, а **особый длительный период существования базы**, когда наружу практически нельзя выйти. Важные новые детали из самой формулировки: заражённые облепляют базу со всех сторон, каннибализируют, постоянно шумят, могут строить «лесенки», выходят на верхние этажи и крышу; крыша превращается в отдельный объект круглосуточного наблюдения и защиты, хотя там могут стоять важные facilities; толпа создаёт запах, психологическое давление и предполагаемое усиление заражения через воздух.

Особенно важно не потерять **roof gameplay** и **длительность состояния**. Current Draft уже разрешает vertical pressure, но это ещё не тот же content premise. Air network сейчас отдельно deferred, поэтому идея «огромная плотность заражённых усиливает воздушную инфекцию» остаётся новым вопросом, а не следствием current rules.

**Сохранять в content premises.**

### 1.1. Большой ядерный / химический event

Практически **новая идея целиком**.

Тут два meaning: собственно massive nuclear/chemical event и отдельная мысль, что игрок может перед началом/в настройках определять, допускает ли ран настолько разрушительные долгосрочные события.

Это скорее world-event/content premise + run configuration idea. Current planning эквивалента не содержит.

**Сохранять как premise, обсуждать позже.**

### 2. Разные штаммы / группы штаммов

Здесь важно не приписывать формулировке лишнего. №2 говорит только: **«разные штаммы/группы штаммов»**.

Это **частично покрыто**: в current planning профиль штамма уже может меняться между ранами, а множество свойств определяется `current strain`.

Но нынешняя модель не отвечает полностью на вопрос, существуют ли:

- несколько штаммов одновременно в одном ране;
- устойчивые группы/семейства штаммов;
- один доминирующий current strain на ран.

Эту конкретизацию приносит уже №5.

Поэтому №2 я бы сохранял как **верхнеуровневый open system idea**, а не считать дубликатом.

### 3. Энергетика, анабиоз и масса тела

Здесь overlap сильный, но incoming formulation всё равно добавляет смысл.

Уже есть: заражённые энергетически не самодостаточны, old infected истощаются, используют low-activity state, ищут пищу/воду, scavenging/cannibalism поддерживают угрозу.

Incoming уточняет сразу несколько вещей: вирус **непосредственно меняет энергообмен**; анабиоз должен объяснять месяцы и, возможно, годы существования; масса тела означает больший запас/возможную силу; толстый заражённый поэтому может создавать больший физический риск; игрок потенциально способен оценивать массу/остаточную энергию и на этом основании прогнозировать риск, например для двери.

То есть новая часть — не «зомби иногда спит», а:

`body mass → energy reserve / physical capability → readable threat`.

Это **system refinement**, который стоит сохранить отдельно до обсуждения.

### 4. Эволюционная история вируса и почти все заражённые

Здесь очень много нового, и предыдущие мои ответы слишком сильно сжимали пункт.

Incoming idea предлагает конкретную **историю пандемии**: ранняя версия очень заразна, но может не превращать человека полностью — люди остаются человекоподобными, но с изменённым пищевым/агрессивным поведением; таким способом инфекция охватывает почти всё человечество; позже появляются массовые превращения; затем эволюционное давление смещает вирус в сторону сохранения носителя — анабиоз, изменённый metabolism, взаимодействие с заражёнными животными.

А следующая часть идёт ещё дальше: возможно, **практически все живые люди уже несут разные штаммы**, включая лёгкие, которые не превращают человека, но оставляют хорошие или плохие последствия. Люди, вообще никогда не болевшие, могут стать особенной группой со своими преимуществами/рисками.

Current Draft содержит carrier/recovered/resistance, variable strain и animal ecology, но не эту модель мира. Например, сейчас recovered/cleared, persistent carrier и intermittent shedder рассматриваются как возможные состояния относительно current strain.

Поэтому №4 — **существенно новая world/system hypothesis**, а не просто lore-переформулировка.

### 5. Разные штаммы у заражённых и разные способы лечения / противодействия

Это одновременно **system idea и отдельный content premise**.

System meaning: разные infected могут иметь разные штаммы или группы штаммов; возникает вопрос, действительно ли у каждого может появляться собственный вариант или изменение требует нового цикла заражения. Могут различаться течение болезни, симптомы и эффективность препаратов.

Current planning уже очень хорошо поддерживает strain-specific properties: susceptibility, host range, animal transmission, disease course и т. д. Но несколько concurrently relevant strains не приняты.

И отдельно в формулировке прямо есть **игровая ситуация**: перед игроком заражённые разных штаммов; по поведению можно предположить, какой перед ним strain; против одного у базы есть более эффективное средство, с другим рациональнее вообще не связываться.

Вот эту часть обязательно надо сохранить как **content premise**, даже если multi-strain system ещё не принят. У premise просто будет dependency: «requires concurrent distinguishable strains».

### 6. Спящие заражённые

Это теперь я классифицирую как **system refinement + reusable content premise/pattern**.

Current planning уже имеет `low-activity/torpor` и резкую активацию от людей, шума или другого сильного стимула.

Но incoming formulation конкретнее: заражённый **резко замирает, выглядит как мёртвый и внезапно нападает при приближении**. И пользователь прямо называет это «ситуация / хоррор-эффект / обоснование».

Поэтому нельзя сказать «уже есть torpor, закрыто». Новый meaning — **fake-dead ambiguity и конкретное horror use**.

**Сохранять в premises.**

### 8. Потеря большой части здания

Это **чистый content premise на существующих системах**.

Current game уже позволяет терять сектора, оставлять там людей/оборудование, обходить их, возвращать позже или продолжать игру с permanent scars.

Но premise «потерял большую часть здания» сам по себе новый и ценен как экстремальное состояние игры.

Фраза `сидишь на обрызге` в исходном текстовом файле мне не ясна, поэтому я **не буду придумывать**, что именно там имелось в виду. Ясный сохраняемый meaning: большая часть facility потеряна, игрок продолжает существовать из сильно урезанной оставшейся позиции.

**Сохранять в premises.**

### 9. Потерян первый этаж, надо спускаться со второго

Тоже **прямой content premise**, причём довольно конкретный.

У игрока потерян первый этаж; безопасная/контролируемая позиция выше; теперь нужно самим спускаться вниз; там находятся fresh infected, которые могут выбегать навстречу и сами пытаться подняться на второй этаж.

Current systems отлично позволяют это реализовать — lost sectors, fresh infected, physical exploration, vertical pressure, tactical squad — но **это не заменяет сам premise**.

**Сохранять обязательно.**

### 12. Рост числа переболевших / иммунных со временем

Это не просто наличие immune/recovered — это **долгосрочная Dynamic hypothesis**.

Incoming meaning: если вирус сам со временем эволюционирует в сторону большей survival rate хозяина, вероятность получения переболевших/immune может расти; долго существующая база постепенно обрастает людьми, иммунными вообще или к конкретным штаммам; из-за этого меняются gameplay и политические группы.

Current planning уже допускает resistant/immune и прямо говорит, что политические группы могут формироваться по biological status.

Но **направленная временная траектория**

`долгая база → всё больше recovered/immune → меняется общество`

не принята.

Это существенная новая идея, связанная с №2/4/5.

### 13. Последствия болезни и изменение общества

Это тоже намного сильнее текущего overlap.

Current Draft уже говорит, что disease course может менять агрессивность, рациональность, потребности и работоспособность.

Incoming idea говорит о **постоянных последствиях у переболевших**: некоторые штаммы могут менять характер/поведение, делать человека более психопатичным, уменьшать естественные потребности и т. п. Затем возникает второй уровень: если такие люди накапливаются, меняется **сама социальная норма базы** — ранее неприемлемое становится приемлемым, может становиться больше рейдов, рабства, жестоких развлечений.

То есть здесь две новые связи:

```
strain
→ persistent post-infection character/need changes

population composition changes
→ culture / acceptable behavior / base trajectory changes
```

Это серьёзная long-term systemic idea.

### 14. Рейды на других выживших и типы баз

Current planning уже имеет внешние группы, которые могут конкурировать, торговать, мешать или становиться будущей угрозой.

Но incoming formulation добавляет:

игрок сам может рейдить других выживших; база может иметь разную природу — raider base, slave-trader/slave-owner base, ordinary survivor base; population/background базы может быть принципиально разным.

И внутри этого же пункта есть отдельный очень ясный **content/run premise**:

> сценарий в тюрьме: игрок — глава охраны, ему нужны люди, а доступные люди — заключённые.

Его нужно вынести в premise bank отдельно от общей social-system идеи.

### 16. Рабство

Это **новая system idea**.

Формулировка короткая, поэтому не надо додумывать огромную simulation architecture: «можно рабов делать, люди по-разному к этому относятся».

Current coercion, punishment, inequality и force не равны slavery. Поэтому сохраняемый minimum meaning сейчас именно такой:

`forced/slave status exists + different characters/groups react differently to it`.

Всё остальное — production, escape, market, enforcement, inheritance статуса и т. д. — уже последующее обсуждение, а не содержание входящей идеи.

### 17. Смена лидера / правительства / иерархии

Здесь тоже есть **system rule + несколько content premises**.

Current Draft уже имеет Command Circle и оставляет открытым вопрос последствий смерти или раскола высшего руководства.

Incoming idea добавляет ключевое правило: **смена власти не обязательно является game over**. Главного могут свергнуть; government/hierarchy меняется; игра продолжается. В prison setup бывший главный охраны потенциально сам становится заключённым. Во время бунта две силы могут насильственно бороться за убежище, а игрок — выбирать сторону. Бывшие союзники становятся врагами.

Последняя фраза про потерю `вижена` тоже стоит сохранить буквально как unresolved implication: похоже, при расколе игрок теряет информацию/видимость, которую раньше получал от людей, ставших врагами. Но я не буду автоматически превращать это в fog-of-war rule, потому что current transparent-space model делает этот момент отдельным вопросом.

И **бунт / violent takeover** — хороший самостоятельный content premise.

---

## Что получается после пересмотра

Теперь я бы сказал: **ни один из пунктов 1, 1.1, 2, 3, 4, 5, 6, 8, 9, 12, 13, 14, 16, 17 я не считаю полностью redundant или superseded.**

У одних уже большая опора в Draft, но incoming wording добавляет уточнение. У других почти весь meaning новый.

А в предварительный `content-premises.md` я бы уже сейчас переносил именно эти units:

1. **Prolonged Horde / “Nuclear Winter” Siege**.
2. **Nuclear/Chemical Major Event**.
3. **Mixed-Strain Encounter** из №5.
4. **Fake-Dead / Sleeping Infected Encounter**.
5. **Most Of The Facility Lost**.
6. **First Floor Lost — Descend From Above**.
7. **Prison Start — Guards Need Prisoners**.
8. **Revolt / Violent Change Of Power**.

При этом №1, №5, №6 и №17 одновременно имеют системные dependencies/уточнения — это нормально. Premise не обязан ждать, пока вся underlying system принята: он может лежать предварительно и прямо говорить, **какое нерешённое game meaning нужен для его реализации**.

Следующим шагом я бы уже не делал ещё одну общую классификацию, а прошёл эти идеи **по смысловым связкам**: сначала `2 + 4 + 5 + 12 + 13` как infection evolution/multi-strain/post-infection систему, затем `14 + 16 + 17` как social/governance систему, а content premises при этом просто сохранил бы без преждевременной детализации Scenario.

================================================================================
СООБЩЕНИЕ 12 — ПОЛЬЗОВАТЕЛЬ
================================================================================

Помести в текстовый файл мои и твои сообщения начиная после моего  сообщения с файлами промпта и идей, в ответе дай текстовый файл где помечено где я говорю а где ты и в этом ответе укажи кол во сообщений
~~~
