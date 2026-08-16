# Survivor Base — Ideas

**Status:** active project-local creative workspace
**Project entry point:** [`README.md`](README.md)
**Legacy source/status context:** [`game-planning-draft.md`](game-planning-draft.md)
**Content-premise owner:** [`content-premises.md`](content-premises.md)
**Source ledger:** [`../../chat-history/survivor-base-branch-01.md`](../../chat-history/survivor-base-branch-01.md)

## 1. Responsibility And Authority

This file preserves game ideas that are worth keeping but are not automatically accepted cross-cutting project meaning.

An Idea may be:

```text
a mechanic or rule;
a system direction;
a Gameplay Dynamic direction;
a world / lore hypothesis;
a feature direction;
a visual/gameplay thought;
a hybrid that also contains a possible content use.
```

Working rule:

```text
Idea
≠ decision
≠ accepted project meaning.
```

When an Idea becomes explicitly accepted, reconcile it into the real owner(s) whose responsibility it changes. Back-write the legacy Draft only when migration compatibility/provenance responsibility requires it.

When an embedded content example becomes useful as an independently reviewable playable/content unit, it may be copied or moved to [`content-premises.md`](content-premises.md). Hybrid entries stay here by default until that split is useful.

When one Idea genuinely spans several planning levels, keep one primary project-scope record here first. Specialize or split it into lower-level owners only when the meaning or independently reviewable responsibility actually differs; do not duplicate one unresolved cross-level Idea merely to mirror several planning levels.

## 2. Organizing Several Ideas Around One Question

Use this structure when it helps; do not require it for every spontaneous thought:

```text
Design Direction
  → Brainstorm Prompt
      type: Question / Task / Requirement / Problem
      → Variant / Idea
      → Variant / Idea
      → Variant / Idea.
```

A new Idea may still be recorded as one line before a useful Prompt is known.

Possible relations:

```text
alternative to;
refines;
depends on;
conflicts with;
combines with;
supports;
replaces;
makes redundant;
enables;
example of.
```

These relations help exploration; they are not new decision-status types.

## 3. Current Direction Map

| Direction | Preserved ideas / questions |
|---|---|
| **OPEN-FIRST — First-Play Context And Gameplay Entry** | selected context order; virus/world presentation variants; animal observation example; fixed-character-story vs customizable trusted-core conflict |
| **INF-EVO — Infection Evolution** | 2+5 strain groups and displacement; 4A/4B infection-history variants; 12 long-term biological/demographic change |
| **INF-PHYS — Infected Physiology And Ecology** | 3 energy reserve/body mass/fatigue; animal approach causal refinement; infected-resident hunting idea; 6 fake-dead / low-activity behavior |
| **SOC-TRAJ — Social Trajectories** | 13 post-infection persistent change; 14 raids/base types; 16 slavery/forced status |
| **GOV — Governance And Leadership** | 17 regime change / internal conflict; open questions about leadership, authority and player continuity |
| **WORLD — Major World Events** | 1.1 nuclear/chemical major event and optional run-level enable/disable idea |

## 4. Source Map

The original incoming numbering is preserved from `SB-B01-SRC01` in the source ledger.

| Incoming item | Main owner here | Source / later clarification |
|---|---|---|
| First-play context / entry | OPEN-FIRST | current continuation; `SB-B01-P18` |
| Animal approach / group observation / hunting | INF-PHYS + OPEN-FIRST presentation use | current continuation; `SB-B01-P19` |
| 1.1 | WORLD | `SB-B01-SRC01`; routing confirmed in `SB-B01-U055` |
| 2 + 5 | INF-EVO | `SB-B01-SRC01`; researched/fixed in `SB-B01-C01` |
| 3 | INF-PHYS | `SB-B01-SRC01`; clarification in `SB-B01-C01` |
| 4 | INF-EVO | `SB-B01-SRC01`; 4A/4B split in `SB-B01-C01` |
| 6 | INF-PHYS | `SB-B01-SRC01`; Hybrid stays in Ideas |
| 12 | INF-EVO / SOC-TRAJ | `SB-B01-SRC01`; clarification in `SB-B01-C01` |
| 13 | SOC-TRAJ | `SB-B01-SRC01`; clarification in `SB-B01-C01` |
| 14 | SOC-TRAJ | `SB-B01-SRC01`; Hybrid stays in Ideas |
| 16 | SOC-TRAJ | `SB-B01-SRC01`; clarification in `SB-B01-C01` |
| 17 | GOV | `SB-B01-SRC01`; clarification in `SB-B01-C01`; later governance exploration |

## 5. WORLD — Major World Events

### IDEA-1.1 — Большой ядерный / химический event

**Source:** `SB-B01-SRC01 item 1.1`; destination confirmed by `SB-B01-U055`.

**Original wording — verbatim:**

> Мб буквально можно какой нибудь ядерный ивент намутить или химический и мб даже включить опцию - нужны игроку такие масштабные ивенты или нет, т к сильно могут повлиять и на продолж время.

**Preserved meaning:**

- a very large nuclear/chemical or comparable disruptive world event may exist;
- separately, a run/configuration option may control whether events of that magnitude are enabled;
- no exact event architecture, duration, probability or system impact is selected yet.

**Open questions:**

- Does the game want a reusable class of rare world-transforming events at all?
- Is nuclear/chemical only an example, or the intended fiction?
- Should these belong to normal campaign variance, late-game content, a world setting, or a separate difficulty/configuration option?

This remains an Idea, not a current Content Premise.

## 6. INF-EVO — Infection Evolution


### Source refs

`SB-B01-SRC01 items 2 and 5`; later research/fixation summarized in `SB-B01-C01`.

### 2 + 5. Разные штаммы / группы штаммов и вытеснение линий

[Исходные формулировки — дословная копия]

Разные штаммы/группы штаммов.

Могут быть разные штаммы у разных зомби, или разные группы штаммов т к по такой логике практически у каждого зомби свой личный штамм. (Так ли это работает или для мутирования надо чтобы шел процесс нового заражения?) И типо игровая ситуация, что у тебя зараженные с разными штаммами и ты видишь что у этого вот такой штамм а у другого другой т к они по разному себя ведут и у тебя могут быть более эффективные лекарства против конкретного штамма, а с другим лучше не связываться и симптомы заражения могут немного отличаться, с течением заболевания.

[Зафиксированное уточнение после исследования и обсуждения]

Для gameplay имеет смысл различать:
- постоянное мелкое внутривидовое / внутрихозяинное мутирование, которое обычно не становится отдельной игровой сущностью;
- несколько крупных gameplay-significant strain groups / линий, которые обладают различимыми свойствами и могут устойчиво циркулировать в мире.

Животные могут быть одним из ключевых механизмов, через который новые крупные линии:
- циркулируют отдельно от человеческой популяции;
- продолжают мутировать и отбираться в другом host environment;
- географически переносятся между районами;
- возвращаются к людям / заражённым через новые контакты, укусы, кровь, ткани, поедание или другой подходящий transmission route.

Новый значимый вариант, попавший в уже заражённую population / host ecology, не обязан просто «накладываться бонусом» поверх старого. Возможные направления для модели:
- новый вариант не закрепляется;
- прежняя линия остаётся доминирующей;
- новый вариант успешно закрепляется и постепенно вытесняет прежний;
- несколько линий некоторое время сосуществуют;
- при подходящей биологии mixed infection / recombination / другой механизм создаёт новую комбинацию свойств.

Для Survivor Base особенно интересен вариант, в котором успешные новые strain groups могут постепенно вытеснять старые в конкретной региональной ecology. За счёт этого инфекция внутри одного рана действительно развивается во времени, но развитие происходит не как миллион независимых уникальных мутаций каждого заражённого, а как смена / конкуренция нескольких крупных циркулирующих линий.

Это поддерживает исходное ключевое направление:
- свойства инфекции могут отличаться между ранами;
- внутри конкретного рана infection ecology тоже может качественно изменяться;
- игрок постепенно открывает новые свойства, симптомы и закономерности;
- прежняя рабочая модель инфекции может со временем стать неполной;
- research / observation нужны для обновления этой модели.

Разные strain groups потенциально могут статистически различаться по:
- симптомам;
- течению заболевания;
- поведению заражённых;
- host range;
- transmission;
- metabolic / activity properties;
- чувствительности к препаратам и другим countermeasures.

Игрок не обязан автоматически знать strain. Различия могут проявляться через evidence: поведение, симптомы, эпидемиологическую историю, животных, response to treatment и другие признаки.

[Research / Evidence provenance]

Биологическая правдоподобность направления проверялась по первичным научным источникам. Эти источники поддерживают отдельные механизмы и ограничения, но **не выбирают** финальную архитектуру вымышленного вируса Survivor Base.

Primary-source provenance IDs:

- within-host mutation / divergence without a new-host transmission step: `PMC9906997`, `PMC12061394`, `PMC7618859`;
- transmission bottlenecks: influenza `PMC7025719`; SARS-CoV-2 `PMC10239218`;
- coexistence / coinfection / multiple variants in one host: `PMC9906997`, influenza `PMC3071067`, HIV/RSV/CMV `PMC7668575`;
- recombination / reassortment-like generation of new combinations: SARS-CoV-2 `PMC8902039`; influenza in pigs `PMC5501944`;
- genotype-dependent drug/countermeasure sensitivity: influenza `PMC5820429`, `PMC4023734`; SARS-CoV-2 `PMC11213110`, `PMC11411086`;
- animal circulation / reservoir examples: deer `PMC8833191`, `PMC9712111`; mink `PMC7857398`;
- caution against assuming animal hosts automatically accelerate adaptation: `PMC9142586`;
- superinfection-exclusion examples in several viruses: `PMC1075699`, `PMC4768946`, `PMC2772679`, `PMC7660575`.

Interpretation boundary:

```text
mutation is possible
≠ every host gets a gameplay-significant unique strain;

coexistence / mixed infection is possible
≠ stable property stacking is automatic;

animal circulation can create separate ecological branches
≠ animals necessarily accelerate evolution;

selection / displacement
≠ directed "improvement" of the virus.
```

For gameplay, `strain group` therefore remains an authored/simulation abstraction whose exact genome architecture, mutation rate, host range and recombination rules are still open design questions.

[Открытые вопросы для будущей разработки]

- Как быстро новые strain groups способны распространяться и вытеснять старые?
- Всегда ли вытеснение происходит полностью или несколько крупных линий могут долго сосуществовать по разным районам / host populations?
- Какие животные наиболее важны как reservoir / evolutionary branch / переносчик?
- Какие transmission routes позволяют животному реально возвращать новую линию людям или заражённым?
- Насколько часто mixed infection создаёт новый значимый профиль, а насколько чаще линии просто конкурируют?
- Какие различия между strain groups должны быть достаточно крупными, чтобы игрок мог их заметить и чтобы они создавали новые решения?
- Насколько развитие strain ecology должно быть simulation-driven, а насколько ограничиваться управляемым набором authored / seeded вариантов ради читаемости и баланса?

### Source refs

`SB-B01-SRC01 item 4`; 4A/4B split preserved in `SB-B01-C01`.

### 4. Эволюционная история вируса и почти все заражённые

[Исходная формулировка — дословная копия]

Можно обосновать то как человечество проиграло и в целом логику развития, что изначально вирус был супер заразным, мб люди даже не до конца превращались, а оставались людьми, но помешанными на еде или просто неадекватными, склонными к насилию. И таким образом заразилось человечество, мб даже практически все заразились, но пошло по разному, в какой то момент начали превращаться и массово, но потом вирус взял курс с заразности на сохранение носителя для дальнейшего заражения через анабиоз и изменение в обмене веществ и зараженных животных которые много жрут, но не боятся и двигаются к зараженным. Вот так как то.

Не знаю стоит ли включать то, что практически все заражены, но разными штаммами и теми, которые не превращают и они пока человекоподобные - у них могут быть последствия от этих легких штаммов, хорошие или не очень. Могут быть вообще не болевшие ничем и они могут особенное место занимать в плане того что либо легко заражаться, либо не иметь последствий от старых штаммов как у многих, или не многих, тут вопросы баланса присутствуют актуальные в более глубокой разработке, но сохранить стоит, может нормально сочетаться со след пунктом.

[4A — зафиксировать как варианты лора]

Сохранить как возможные варианты истории мира, а не как уже выбранную единственную историю:
- ранняя форма инфекции могла быть очень заразной;
- часть заражённых могла долго оставаться внешне человекоподобной, но иметь изменённый аппетит, агрессию, поведение или другие последствия;
- это могло помочь инфекции охватить огромную часть человечества до периода массовых очевидных превращений;
- дальнейшая эволюция могла смещать некоторые варианты в сторону более долгого сохранения носителя, экономии энергии, анабиоза и других способов длительного существования;
- заражённые животные и их изменённое пищевое поведение могут быть частью этой общей эволюционной картины.

Это именно варианты лора / причинного объяснения катастрофы, которые позже нужно сравнить и проверить на совместимость с gameplay.

[4B — сохранить как отдельный вариант для будущего разбора]

Сохранить вариант, что очень большая доля выживших уже имеет историю заражения разными штаммами / формами инфекции, включая такие, которые не приводили к полной трансформации.

У таких прошлых заражений могут оставаться положительные или отрицательные последствия. Люди, которые вообще никогда ничем подобным не болели, потенциально могут занимать особое положение и иметь собственные преимущества / риски.

Пока нет ясной игровой картины того, как именно эта модель должна работать:
- означает ли это только историю прошлой инфекции;
- остаётся ли у большинства активное носительство;
- сколько разных штаммов человек способен пережить / нести;
- как это считывается игроком;
- как влияет на intake, диагностику, иммунитет, лечение и социальные группы.

Поэтому 4B сохраняется как вариант, но требует отдельного будущего разбора.

### Source refs

`SB-B01-SRC01 item 12`; clarification preserved in `SB-B01-C01`.

### 12. Рост числа переболевших / иммунных со временем

[Исходная формулировка — дословная копия]

Мб, если у нас вирус меняется и по лору менялся в сторону большей выживаемости зараженных, то может со временем у нас может быть больше шанс получить переболевшего и иммунного? Это может нормально повлиять на динамику игры, не будет однообразности т к к долгая база постепенно может обрастать все большим кол вом иммунных или иммунных к опред штаммам, если у нас про разные штаммы, и могут формироваться полит группы активнее.

[Уточнение пользователя]

Идея в том, что можно построить игровую динамику за счёт изменений в штамме и качественного изменения состояния базы через последствия вируса. Это может быть уже частично выводимо из существующих зафиксированных идей, но важно сохранить саму возможность такой динамики как отдельный смысл.

Качественное изменение базы может происходить не только через вирус. Например, оно может возникнуть после принятия с улицы сомнительных людей / групп с уже сформированным поведением и ценностями — например тех, кто до этого грабил других.

## 7. INF-PHYS — Infected Physiology And Ecology

### Source refs

`SB-B01-SRC01 item 3`; later energy/fatigue clarification preserved in `SB-B01-C01`.

### 3. Энергетика заражённых, анабиоз, масса тела и усталость

[Исходная формулировка — дословная копия]

Вирус буквально влияет на энергообмен и типо энергия тратится по другому + анабиоз, и так обосновывается способность жить многие месяцы у зараженных(а может и годы). Мб все таки толстяки имеют смысл? Те кто нажрался в свое время и обладают большей силой, хоть и с тем же успехом экономят ее. Можно будет еще оценивать вес зараженного/ сколько у него энергии, и типо больше рисков для сноса дверей с таким раскладом.

[Уточнение пользователя — энергетическая и экологическая причинность]

Идея не сводится к тому, что «толстый заражённый просто сильнее». Изменённый обмен веществ и повышенная экономия энергии могут позволять заражённым дольше сохранять накопленный энергетический запас.

Заражённые животные могут иметь повышенный аппетит; их может привлекать запах заражённых, и они могут подходить к ним без обычного страха. Это создаёт дополнительные пищевые взаимодействия вокруг заражённых.

Заражённый с большой физической массой и большим запасом энергии потенциально имеет больше возможностей победить другого заражённого и съесть его, победить дикое животное, получить новую пищу и поддержать высокий энергетический запас.

Из этого могут появляться особые заражённые, опасные не только количеством, но качественной физической угрозой: запасом энергии и массой, которые могут влиять на способность выламывать двери, разрушать преграды, давить на людей и совершать более мощные физические действия.

[Уточнение пользователя — усталость, мобилизация и прекращение активности]

Нужно отдельно обсудить усталость заражённого и различие между:
- общим запасом энергии в теле;
- доступной в данный момент мощностью / способностью совершать интенсивные действия;
- локальной усталостью после рывка или длительной нагрузки.

Большой запас энергии за счёт накопленной массы тела может позволять заражённому делать более качественные и опасные рывки, быстрее двигаться или прикладывать больше усилия в моменты, когда это нужно. Но это не обязательно означает бесконечную максимальную активность до полного сжигания всего жира.

Возможный принцип для дальнейшего обсуждения:
- заражённый может испытывать усталость даже при наличии большого общего запаса энергии;
- если существует реальная возможность добраться до человека / пищи и в теле остаётся достаточный запас, заражённый может мобилизовывать ресурсы и не переходить в анабиоз только из-за обычной усталости;
- пока шанс добыть человека остаётся воспринимаемо реальным, мотивация к активности может поддерживаться;
- если заражённый «понимает» / оценивает, что шанс добраться до цели фактически исчез, активность может падать, и он может прекратить дорогое преследование или вернуться к энергосберегающему состоянию.

[Вопросы для будущего обсуждения]

- Нужно ли моделировать отдельно запас энергии и кратковременную усталость / мощность?
- Что именно позволяет заражённому оценить, что цель ещё достижима или уже недостижима?
- Насколько долго он продолжает ломать дверь / преследовать человека без прогресса?
- Может ли высокий энергетический запас уменьшать скорость накопления усталости или только увеличивать число возможных циклов восстановления и новых рывков?
- Насколько масса сама по себе помогает физическому воздействию, а насколько мешает скорости / манёвренности?
- Какие признаки этих состояний игрок реально может увидеть и использовать для решения?

### INF-PHYS-P01 — Почему заражённое животное приближается к заражённым?

**Type:** Brainstorm Prompt — Problem
**Status:** open refinement of existing Idea/current accepted baseline; no causal mechanism selected.
**Source:** `SB-B01-P19`.

#### Existing meaning that this Prompt must preserve

Current `ideas.md` already preserves:

> infected animals may be attracted by infected smell and approach without normal fear.

Current `CHAT-PI-052` already accepts the stronger ordinary-run boundary:

```text
reduced normal avoidance of infected
≠ conscious self-sacrifice;

direct pain / aggression / chase
→ ordinary fear, resistance or escape may return.
```

The unresolved problem is not whether approach was ever imagined, but what causal model can support approach/reduced avoidance without turning every animal into a permanently suicidal food-delivery mechanism or ignoring learning from prior attacks.

#### INF-PHYS-V01 — infection-cue threat/social-recognition failure

**Proposed Answer**

An infection-associated smell or other cue may cause an affected animal to under-process threat and classify an infected human/animal as conspecific, socially familiar or otherwise insufficiently dangerous. The cue may attract the animal or suppress normal avoidance before overt aggression begins. It does not give the animal a goal of being eaten.

When an infected attacks, chases or causes pain, stronger immediate danger signals may override the cue enough for resistance, panic or escape. Exact response depends on strain, species, individual state, distance and attack conditions.

**Local Evaluation**

Pros:

- gives a causal reason for approach beyond arbitrary fear deletion;
- preserves the existing non-suicidal baseline;
- helps explain why accumulated experience may not fully restore normal avoidance while the cue remains active;
- can produce readable pre-attack approach followed by a sharply different escape response.

Cons:

- may require more animal perception/behavior detail than the game needs;
- `conspecific/familiar` can become misleading anthropomorphic wording if treated as literal biology;
- an overly strong cue can still make animals functionally suicidal despite the stated boundary.

Risks:

- universalizing one behavior across every strain/species;
- making animal feeding too reliable for infected ecology;
- presentation failing to distinguish infection-driven approach from ordinary curiosity, injury, trapping or random movement;
- teaching the player a rule through a historical strain that does not apply to the current playable strain.

Prompt-Level Questions:

- Does the design need an explicit neurological/social-recognition explanation, or is a strain-specific behavioral rule sufficient?
- Is active attraction required, or does reduced avoidance already create the intended ecology?

Variant Questions:

- What cue is involved: smell, sound, behavior, several signals or an abstract authored rule?
- Which species/strains are affected?
- Can experience weaken the effect, and under what conditions?
- At what signal does the animal switch from approach/non-avoidance to fear/escape?
- Can unaffected herd/group members detect that something is wrong with the affected animal?

**Evidence Context**

- No new research evidence is added by this discussion.
- The existing project baseline supports reduced avoidance and pain/chase response; it does not establish the proposed brain/cue mechanism.
- Biological/reference research should later separate plausible animal sensory/learning mechanisms from authored gameplay simplification.

**Dependencies / Conflicts / Relations**

- refines `item 3` animal-attraction meaning;
- must remain compatible with `CHAT-PI-052` strain/species discovery boundary;
- may support the `OPEN-FIRST` animal observation example;
- may enable or weaken `INF-PHYS-P02` infected-resident hunting depending on whether a functional person emits the relevant cue;
- conflicts with any realization that makes direct aggression irrelevant to escape.

**Integrated Evaluation**

Cross-system questions:

- How does this affect infected energy ecology, hunting, animal husbandry, animal intake and carcass sanitation?
- What evidence can the player collect to distinguish current-strain behavior from historical knowledge?
- Does the rule create meaningful decisions or only a lore explanation for infected feeding?

**Combination Evaluation**

The Variant can combine with visible historical-strain presentation without requiring the current strain to produce the same appearance or cue strength. That combination needs explicit communication so the player does not infer a universal current rule.

**Current Conclusion**

Preserve as a causal refinement candidate. The accepted/current baseline remains reduced avoidance without conscious self-sacrifice, with pain/aggression/chase capable of restoring fear/resistance/escape. Exact cue, cognition, attraction strength and strain/species scope remain open.

### INF-PHYS-P02 — Могут ли заражённые члены убежища эффективнее охотиться на животных?

**Type:** Brainstorm Prompt — Gameplay Idea / Cross-System Question
**Status:** open Idea Variant; not an accepted worker role or hunting rule.
**Source:** `SB-B01-P19`.

#### INF-PHYS-V02 — delayed-avoidance hunter

**Proposed Answer**

An eligible infected/functional shelter member may approach an affected animal more effectively than an ordinary hunter because the animal detects the relevant infection cue and delays avoidance until overt aggression begins.

**Local Evaluation**

Pros:

- converts infection status into a situational economic capability rather than only a penalty;
- links functional infected population planning to animal ecology and food acquisition;
- can create a reason to employ a risky person in work where their condition matters causally.

Cons:

- may collapse ordinary hunting, bait/trap and stealth decision space;
- the advantage may be inconsistent if functional people do not emit the same cue as turned infected;
- the hunter still needs a method to act before aggression triggers flight.

Risks:

- injury/exposure during close approach;
- return of contaminated blood/tissue/equipment to the base;
- a dominant optimal policy of using every eligible infected person as a hunter;
- social/political consequences being reduced to a simple numeric buff.

Variant Questions:

- Which exact states qualify: persistent carrier, intermittent shedder, symptomatic functional infected, recovered person or another state?
- Does the animal respond to that state with attraction, reduced avoidance or no special behavior?
- What happens at the first weapon movement, chase, trap trigger or attack?
- Is the advantage useful for capture, killing, herding, baiting or only initial approach?
- Which species/strains make the role viable?

**Evidence Context**

- Current `CHAT-PI-016` supports functional carrier labor generally; it does not establish an animal-hunting advantage.
- Current `CHAT-PI-052` supports animal reduced avoidance generally; it does not establish that a functional shelter resident presents the same cue as turned infected.
- No prototype, simulation, playtest or new biological evidence currently validates the combined mechanic.

**Dependencies / Conflicts / Relations**

- depends on `CHAT-PI-016` state/worker boundaries;
- depends on `CHAT-PI-052` current-strain animal behavior;
- depends on `CHAT-PI-053` for current carcass, blood, meat and animal-sanitation consequences;
- depends on or combines with `INF-PHYS-V01` only if the eligible hunter emits the relevant cue;
- affects hunting Situation/Execution design, livestock/biosecurity, food/carcass handling and social treatment of infected workers;
- conflicts with balance where ordinary hunting alternatives become redundant.

**Integrated Evaluation**

Before promotion, construct only the useful real planning-unit candidates and inspect:

- the meaningful hunting/capture decision, not only physical execution;
- chosen approach/attack/carcass-return Execution;
- infection/exposure and sanitation consequences;
- labor allocation and opportunity cost;
- social/political reaction to deliberately using an infected person this way;
- whether the resulting hunting gameplay remains legible and has several viable approaches.

**Combination Evaluation**

The role may combine with animal observation/research: the base first learns that a current strain reduces avoidance, then considers a risky hunting policy. Historical footage alone should not unlock/validate the current-strain mechanic.

**Current Conclusion**

Preserve as an open gameplay Idea. Do not promote it into `CHAT-PI-016`, `CHAT-PI-052`, a Hunting Loop or accepted workforce architecture until eligible infection state, current-strain behavior, balance and sanitation consequences are integrated and reviewed.

### Source refs

`SB-B01-SRC01 item 6`. Hybrid rule/content example remains in Ideas by current routing rule.

### 6. Спящие заражённые

[Исходная формулировка — дословная копия]

Ситуация слеш хоррош эффект слеш тоже обоснование. Зомби замирают, просто затихают и не двигаются как будто мертвые резко, и резко нападают при приближении чего то к ним.

### Embedded playable example from item 6

Possible content use, not yet promoted to `content-premises.md`:

> the player approaches apparently dead / inert infected and does not know which bodies can suddenly activate.

The content example should move to the premise owner only when it becomes useful as an independently evaluated content unit.

## 8. SOC-TRAJ — Social Trajectories

### Source refs

`SB-B01-SRC01 item 13`; later clarification preserved in `SB-B01-C01`.

### 13. Последствия болезни у переболевших и изменение общества

[Исходная формулировка — дословная копия]

Также переболевшие могут иметь побочки, как я уже говорил, и опред штаммы могут давать изменения характера или поведения и у тебя по сути неприемлимые вещи могут стать приемлимыми. Психопатичными могут стать переболевшие, требующими меньше какой то естественной потребности, и за счет этого характер базы может поменяться, больше рейдов на других выживших, больше рабства, больше каких то жестоких развлечений, или еще что.

[Связанное уточнение пользователя]

Эта идея относится к более общему принципу качественного изменения базы со временем: состав людей и последствия пережитых ими событий / заражений могут менять характер общества, доступные или привлекательные модели поведения и последующие игровые решения.

### Source refs

`SB-B01-SRC01 item 14`. Hybrid; prison start remains an embedded possible content use.

### 14. Рейды на других выживших и типы баз

[Исходная формулировка — дословная копия]

Рейды на др выживших и разный характер/природа базы. У тебя может быть база рейдеров, база работорговцев/владельцев, база обычных выживших. База может состоять из бывших преступников (в будущем может быть буквально сценарий в тюрьме например и интересная ситуация где ты глава охраны и тебе нужны люди и у тебя есть какие то преступники).

[Связанное уточнение пользователя]

Качественное изменение характера базы может происходить не только из-за вируса, но и из-за того, кого игрок принимает в убежище. Например, принятие людей, которые до этого систематически грабили других, может со временем менять поведение, нормы и дальнейшие игровые возможности базы.

### Source refs

`SB-B01-SRC01 item 16`; later clarification preserved in `SB-B01-C01`.

### 16. Рабство

[Исходная формулировка — дословная копия]

Можно рабов делать, по разному к этому могут относиться.

[Уточнение пользователя]

Основная идея ближе к принципу RimWorld: игрок потенциально может сделать конкретного преступника, пленного или другого человека рабом / перевести его в принудительный статус.

Для такого решения могут требоваться условия, а само решение может иметь последствия. Разные люди и группы могут относиться к этому по-разному.

Пока не фиксируются конкретные правила получения статуса, труда, охраны, сопротивления, освобождения или другие детали реализации — их нужно разрабатывать отдельно.

### Embedded possible content use from item 14

`Prison Start — Guards Need Prisoners` remains an example inside the Idea for now:

```text
limited guards
+ prisoners are the available manpower
→ questions of release, trust, arming, status and authority.
```

Promote it to `content-premises.md` only when it is useful to evaluate/develop as a separate start/scenario unit.

## 9. GOV — Governance And Leadership

### Source refs

`SB-B01-SRC01 item 17`; later clarification preserved in `SB-B01-C01`.

### 17. Смена лидера / правительства / иерархии и внутренний конфликт

[Исходная формулировка — дословная копия]

Нужна ли возможность смены главного/смены правительства и иерархии так, чтобы игрок продолжал игру? Типо свержение, но не геймовер? В тюрьме могут свергнуть типо главного и главный типо теперь зек? Мб сделать в ситуации бунта показ, что типо вот, две силы столкнулись в насильственной борьбе за убежище и можно выбрать сторону? И таким образом вижен теряется от тех кто раньше своим считался и становятся они врагами.

[Уточнение пользователя]

Если в игре существуют внутренние политические группы, то при максимальном ухудшении отношений между ними конфликт может перейти в вооружённую борьбу за убежище.

В таком случае можно рассмотреть возможность дать игроку выбор:
- продолжить играть за сторону / власть, за которую он играл до конфликта;
- поддержать другую политическую силу и тем самым изменить власть в убежище.

Смена власти в таком варианте не обязана автоматически быть game over.

Эта идея не обязательно относится к ранней реализации и может требовать значительно более глубокой политической структуры.

[Новое направление обсуждения — верхушка и структура власти]

Перед дальнейшей разработкой идеи 17 нужно отдельно разобраться:

- кто именно является верхушкой Survivor Base;
- это один главный, Command Circle, формальный совет, несколько должностей, фракция или другая структура;
- что именно может произойти с членами верхушки: смерть, свержение, арест, изгнание, потеря должности, переход в другую группу, заключение;
- как происходит передача власти;
- существуют ли формальные / неформальные процедуры передачи власти;
- может ли несколько центров силы существовать одновременно;
- что означает вооружённый конфликт между политическими группами;
- какая сторона после конфликта реально контролирует людей, помещения, вооружение и информацию;
- могут ли бывшие союзники стать враждебной силой внутри того же убежища;
- сохраняются ли конкретные прежние руководители как обычные персонажи после потери власти;
- влияют ли личные качества верхушки на доступные игроку действия и решения;
- могут ли характер, убеждения, лояльность, компетентность или отношения руководителей ограничивать / открывать политики и действия;
- насколько вообще характеры членов верхушки должны иметь системное значение;
- кого именно представляет игрок до и после смены власти.

Это отдельное направление будущего обсуждения, связанное с governance / leadership / player continuity.

### GOV-P01 — Кто и что является верхушкой / властью?

**Type:** Brainstorm Prompt — Question
**Status:** open; no Variant below is selected.

Current project basis already distinguishes formal authority, trust, armed force and other social relations. The open problem is how that becomes an actual government model.

#### GOV-V01 — one formal leader

One person is the main formal head.

Open issue: how much authority still belongs to functional roles and groups.

#### GOV-V02 — Command Circle as a real multi-person governing group

Several functional leaders jointly form the top layer rather than merely acting as an abstract player avatar.

Possible roles can include general coordination, medical/science, security/force, operations/engineering/logistics.

This is a Variant, not a new accepted role list.

#### GOV-V03 — distributed effective power

Formal office, armed-force control, institutional legitimacy, popular support, information access and economic control may belong to different people/groups.

This can create states where the formal leader cannot automatically realize every order.

#### GOV-V04 — Person / Office / Authority separation

Possible structural model:

```text
Person
  → occupies an Office / Role
  → that Office grants specific Authority.
```

The model would allow a person to be removed, replaced, imprisoned or killed without deleting the office itself, and would make succession/power transfer more explicit.

This is exploratory, not accepted architecture.

### GOV-P02 — Как личность руководителя влияет на решения?

**Type:** Brainstorm Prompt — Question
**Status:** open.

Variants discussed:

```text
A. Personality directly blocks some policies/actions.

B. The player can issue the decision,
   but the relevant authority holder may resist,
   demand concessions, refuse execution,
   resign, defect or create political consequences.

C. Personality mainly changes costs/reactions,
   while formal availability stays broad.
```

No option is selected.

### GOV-P03 — Что происходит при передаче / потере власти?

Questions preserved from item 17 and subsequent discussion:

- death, overthrow, arrest, exile, loss of office, faction switch, imprisonment;
- formal vs informal succession;
- multiple centers of power;
- control of people, rooms, weapons and information;
- former allies becoming hostile inside the same shelter;
- deposed leaders remaining as ordinary characters;
- player identity/continuity before and after regime change.

### Embedded possible content use from item 17

A violent internal struggle where two forces contest the shelter and the player may choose a side remains an embedded example here.

It is **not yet** a separate Content Premise under the current `Hybrid → Ideas` rule.

## 10. OPEN-FIRST — First-Play Context And Gameplay Entry

**Source:** `SB-B01-P18` and `SB-B01-P19`.
**Status:** the context order is a selected current-working direction; concrete presentation/lore/narrative realizations remain Ideas/Variants.

### OPEN-FIRST-P01 — Какой контекст нужен до Gameplay T0?

**Type:** Brainstorm Prompt — Requirement / Presentation Problem

#### Selected current-working direction

```text
shallow virus/world context
→ concrete game/base context
→ gameplay-entry handoff
→ Gameplay T0: newcomers arrive / are detected.
```

The pre-play/context material should orient rather than become a deep exposition layer. It needs to communicate enough scale and character of the infection for the player to understand the world they are entering, then establish the concrete Survivor Base context. Pre-play may change expectations, doubts and motivations, but is not automatically Gameplay Phase 0.

The virus/world layer should make clear that infection is not only a bite mechanism and can spread through virus-like routes. Exact transmission routes and what is known about the current strain remain project/system questions; presentation must not invent a universal route merely to make the point.

The opening may hint that infection changed or behaved heterogeneously. Existing `INF-EVO item 4A` already owns the lore Variant in which an early form was highly transmissible, some infected stayed outwardly human-like and later obvious mass turning appeared. First Contact may use that Variant as an example only if it is selected/reconciled; this workspace does not copy it into accepted world history.

#### OPEN-FIRST-V01 — light contextual presentation

**Proposed Answer**

Use a short, relatively shallow opening presentation—cinematic, in-engine observation or another medium—to establish scale, non-bite viral spread and possible heterogeneity/change before moving to the base-specific context.

**Local Evaluation**

Pros:

- gives the player a usable world model before local rules demand decisions;
- can communicate scope without tying the whole game to fixed playable protagonists.

Cons / Risks:

- exposition may delay the actual colony-sim decision space;
- a cinematic can promise rules that the current strain/gameplay does not support;
- fixed dramatic identities can conflict with customizable trusted-core ownership.

Variant Questions:

- What minimum information must be explicit, and what should remain only a hint?
- Which medium supports the responsibility without making Scenario semantics depend on presentation tooling?
- Does the material depict the current strain, historical evidence or several periods?

**Current Conclusion**

The responsibility/order is selected; exact medium and content are open.

#### OPEN-FIRST-V02 — affected animal leaves a group

**Proposed Answer**

Show an observably altered animal leaving a group and approaching infected. The rest of the group does not follow automatically; when the approached animal is attacked/eaten, the others become frightened and flee.

The alteration/behavior may belong to an earlier or otherwise different visible strain. A later animal mini-mission/tutorial may explain that previous strains showed what the player saw in the opening. The presentation is not automatically a cutscene.

**Local Evaluation**

Pros:

- shows non-human infection ecology and the non-suicidal aggression boundary through action;
- the fleeing group prevents the scene from implying that every animal endlessly offers itself to infected;
- historical framing can preserve current-strain discovery.

Cons / Risks:

- visible infection may teach the player that all affected animals are visually obvious;
- historical framing may be forgotten or misunderstood;
- one authored scene does not establish frequency, universality or exact causal mechanism;
- the scene can overpromise animal-system depth.

**Evidence Context**

- Existing `INF-PHYS item 3` supports smell attraction/approach as an Idea.
- Current `CHAT-PI-052` supports reduced avoidance plus pain/chase response as baseline direction.
- Neither establishes this exact group scene, visible transformation, historical-strain wrapper or tutorial.

**Dependencies / Conflicts / Relations**

- is an example of the existing `INF-PHYS item 3` / `CHAT-PI-052` reduced-avoidance direction;
- may exemplify `INF-PHYS-V01` only if that causal model is selected;
- may use `INF-EVO item 4A` as historical context but does not accept it;
- conflicts with any presentation that implies the observed appearance/behavior is universal for the current strain;
- remains embedded here until independent content-unit development justifies a Content Premise.

**Current Conclusion**

Preserve as a presentation Variant. Exact medium, strain, species, visible signs, timing and later tutorial use remain open.

### OPEN-FIRST-P02 — Как совместить narrative identity с customizable trusted core?

**Type:** Brainstorm Prompt — Conflict
**Status:** open; no narrative architecture selected.

Current `CHAT-PI-040` preliminarily accepts that the player may create/configure a limited trusted core. A deep opening story built around fixed playable personalities may contradict that direction or make the created characters feel secondary.

Questions:

- Does opening context need named playable protagonists at all?
- Can historical/world context use people who are not the player's eventual trusted core?
- Can the authored story attach to roles, relationships, events or generated/customized characters instead of fixed identities?
- Which facts must be stable for gameplay causality, and which identity details can vary by run?
- Does trusted-core setup occur before Gameplay T0, and how much story/context does it carry?

Relations:

- conflicts with a fixed-protagonist opening when identity continuity is required;
- depends on `CHAT-PI-040` customizable trusted-core direction;
- connects to the active Goal Map's open trusted-core-setup handoff.

**Current Conclusion**

Preserve the conflict explicitly. Do not select fixed protagonists, story-light presentation or a generated-character narrative solution by implication.

## 11. Current Consolidation Notes

- Item `1` is owned by [`content-premises.md`](content-premises.md) because the prolonged siege is currently treated as a standalone content unit; its unresolved system questions stay attached to that premise.
- Items `8` and `9` are owned by [`content-premises.md`](content-premises.md).
- Item `1.1` stays here even though it could later generate a Content Premise.
- Mixed-strain encounter, fake-dead encounter, prison start and violent takeover stay embedded in Ideas until separate content development justifies promotion.
- `OPEN-FIRST` preserves the selected context order and its presentation/narrative alternatives; it does not yet create the detailed opening Spine.
- The affected-animal group scene remains an embedded presentation example, not a Content Premise.
- `INF-PHYS-P01` refines already-preserved smell attraction/reduced avoidance rather than duplicating it as a new rule.
- `INF-PHYS-P02` remains an open cross-system gameplay Idea and does not update accepted project meaning or the relevant workforce/ecology owners.
- Detailed brainstorming techniques are intentionally not defined in this project file; use the reusable [`Game Creation Workflow`](../../game-creation-workflow.md) and future brainstorming-method owners.
