# Game Structure Analysis

Status: active reusable analysis reference
Scope: a shared structural question set for examining and planning Gameplay Situations, Loops, Dynamics, Scenarios, whole games and other coherent gameplay structures.

Canonical reference-analysis principles remain in [`Reference First And Controlled Transformation`](../principles/reference-first-and-controlled-transformation-principles-and-terminology.md). Canonical Gameplay Situation / Loop / Scenario meanings remain in [`Gameplay Situations, Loops And Scenarios`](../principles/gameplay-situations-loops-and-scenarios-principles-and-terminology.md). Canonical Dynamic terminology remains in [`Mechanics Create Dynamics`](../principles/mechanics-create-dynamics-principles-and-terminology.md). This file owns the shared detailed structural concern set.

## 1. How To Use This File

Use the core map for a broad whole-game or large-subsystem analysis. Use detailed concerns and additional lenses when they clarify a real observation or planning uncertainty.

The same concern set may also be inspected at several planning scales:

```text
whole game;
Gameplay Situation;
Gameplay Loop;
Gameplay Dynamic;
Scenario;
concrete demo.
```

At Situation / Loop / Dynamic / Scenario scale, inspect the same full concern set as a discovery surface and record only concerns with material meaning. The concern keeps the same responsibility while its concrete question is interpreted proportionally at the current scale. Do not mechanically fill every concern.

For a reference analysis, the concrete analysis owns the answers. For a project-planning pass, the appropriate project detail owner owns the answers.

## 2. Core Reference / Structure Analysis Map

| Core aspect | Что фиксировать | Зачем это в analysis / planning |
|---|---|---|
| <a id="concern-player-promise-audience"></a>**Player promise and audience** | Какой опыт обещает игра, кому она понятна, с какими играми сравнивается | Без этого невозможно понять, что в игре является несущим, а что декоративным |
| <a id="concern-core-session-loop"></a>**Core loop and session loop** | Что игрок делает повторно за секунды/минуты; как устроена одна сессия или ран; какие конкретные recurrent processes реально существуют | Помогает отличить broad loop thesis от конкретных повторяемых causal processes и увидеть структуру сессии |
| <a id="concern-player-verbs-decisions"></a>**Player verbs and decisions** | Главные действия и meaningful decisions; насколько варианты materially different; почему разумный игрок может выбрать разные approaches; достаточно ли требуемого разнообразия решений | Помогает отличить количество кнопок от реальной agency, decision quality и meaningful choice |
| <a id="concern-rules-resources-economy"></a>**Rules, resources, and economy** | Внутренние ограничения, ресурсы, награды, обмены, cost structure | Экономика часто переносится лучше, чем сеттинг; именно она создаёт многие dynamics |
| <a id="concern-challenge-failure-progression"></a>**Challenge, failure, and progression** | Как игрок ошибается, восстанавливается, учится и открывает новое; какой диапазон давления сохраняет meaningful agency | Это ключ к мастерству, pacing и retention; также важный источник конфликтов при смешении референсов |
| <a id="concern-balance-decision-space-strategic-diversity"></a>**Balance, decision space, and strategic diversity** | Basic challenge balance; local decision balance; broader strategic balance; требуемое разнообразие materially different решений и стратегий | Позволяет отличить healthy difficulty от отсутствия выбора и обнаружить universally correct response / dominant meta |
| <a id="concern-interface-feedback-readability"></a>**Interface, feedback, and readability** | Как игра сообщает состояние системы, опасность, успех, возможности | Многие «необъяснимые» преимущества референса живут не в правилах, а в сигналах и обратной связи |
| <a id="concern-causal-legibility-strategic-planning"></a>**Causal legibility and strategic planning** | Может ли игрок построить полезную причинную модель, предсказывать направление последствий и использовать её для подготовки/стратегии | Связывает feedback, mental model, repeated Loops / Dynamics и mastery; особенно важно в системных играх с delayed/state-mediated effects |
| <a id="concern-dynamics-state-opportunity-trajectory"></a>**Dynamics and state / opportunity trajectory** | Какие устойчивые causal tendencies возникают; во что они превращают state/economy/opportunities; как меняют будущие Situations и выгодность стратегий | Показывает широкое поведение системы во времени, которое не видно из одного consequence или одного Loop |
| <a id="concern-content-structure-pacing"></a>**Content structure and pacing** | Какой контент подаётся, в каком порядке, как меняется ритм сессии и кампании | Позволяет увидеть, не только что игрок делает, но и когда это становится интересным |
| <a id="concern-market-position-comparables"></a>**Market position and comparables** | Какие теги, жанровые ожидания, якоря и сравнимые игры формируют считывание | Это нужно не только маркетингу: reference bank должен знать, для какого сравнения игра вообще существует |

## 3. Detailed Concerns

<a id="concern-first-contact-expectation"></a>
### 3.1 First Contact And Expectation

#### Что фиксировать

- где впервые увидел игру;
- что заметил первым;
- какую игру представил по capsule, трейлеру или стриму;
- что вызвало желание посмотреть дальше;
- что вызвало недоверие;
- насколько первое обещание совпало с реальной игрой.

#### Зачем

Позволяет отделить:

```text
purchase fantasy
от
действительного gameplay.
```

Это нельзя надёжно восстановить задним числом после десятков часов.

<a id="concern-onboarding-mental-model"></a>
### 3.2 Onboarding And Mental Model

#### Что фиксировать

- что стало понятно без объяснения;
- что пришлось изучать;
- какую модель системы построил игрок;
- где эта модель оказалась неверной;
- что игра объясняет напрямую;
- что позволяет открыть самостоятельно;
- когда игрок впервые способен планировать, а не просто выполнять команды.

#### Зачем

Даже хорошая система не работает, пока игрок не понимает:

```text
какие сущности существуют;
как они связаны;
что он может изменить;
как предсказать последствия.
```

Это concern прежде всего о формировании **исходной рабочей модели**. Долгосрочное чтение причинности повторяющихся систем и использование этой модели для стратегии отдельно проверяется в `Causal Legibility And Strategic Planning`.

<a id="concern-goals-motivation-direction"></a>
### 3.3 Goals, Motivation And Direction

#### Что фиксировать

- чего игрок пытается достичь прямо сейчас;
- кто поставил цель: игра или сам игрок;
- какие цели краткосрочные и долгосрочные;
- как появляется следующая цель;
- что создаёт ощущение направления;
- достаточно ли игрок мотивирован участвовать в этом Situation / Loop / Dynamic / Scenario;
- какое разнообразие целей реально требуется intended game;
- меняют ли разные цели priorities, decisions или viable strategies;
- не являются ли несколько внешне разных целей одним hidden optimization target;
- может ли игрок сформировать собственный план;
- какие будущие состояния/ситуации игрок ожидает и пытается приблизить или избежать.

#### Зачем

Loop объясняет повторение действий, но не всегда объясняет:

> Почему игрок выбирает именно это действие сейчас?

Больше целей не автоматически лучше. Нужен набор целей, который создаёт требуемую для intended experience мотивацию и действительно меняет priorities / plans / decisions.

<a id="concern-player-verbs-decisions-detail"></a>
### 3.4 Player Verbs And Decisions

#### Что фиксировать

- какие действия игрок реально выполняет;
- где находится meaningful decision, а где только execution / input;
- какие варианты materially different по trade-offs, риску, плану или future state;
- почему разумный игрок может предпочесть каждый meaningful option / approach;
- когда несколько действий являются только разными кнопками для одного и того же решения;
- сколько разных способов достижения релевантной цели действительно требуется intended game;
- где decision density полезна, а где повторение превращается в routine / administration.

#### Зачем

Количество verbs или buttons не равно agency. Likewise:

```text
more options
≠ automatically better gameplay;

required meaningful diversity
> cosmetic choice count.
```

Этот concern фиксирует **качество и структуру решений**. Их относительная выгодность и dominant-solution risk отдельно проверяются в `Balance, Decision Space And Strategic Diversity`.

<a id="concern-space-camera-control"></a>
### 3.5 Space, Camera And Control

#### Что фиксировать

- чем непосредственно управляет игрок;
- avatar, cursor, squad или косвенное управление;
- как камера влияет на информацию;
- как устроено пространство;
- насколько важны положение, расстояние и направление;
- где управление создаёт удовольствие или friction.

#### Зачем

Одинаковые правила создают разные игры при:

```text
прямом управлении персонажем;
управлении отрядом;
управлении через интерфейс;
косвенном управлении агентами.
```

<a id="concern-time-attention-information"></a>
### 3.6 Time, Attention And Information

#### Что фиксировать

- real-time или turn-based;
- можно ли поставить игру на паузу;
- сколько событий нужно отслеживать одновременно;
- какая информация скрыта;
- какая приходит с задержкой;
- что игрок должен помнить;
- где возникает перегрузка;
- когда у игрока есть время подумать.

Для Scenario / systemic-game review дополнительно спросить:

- сколько Gameplay Situations одновременно Active в важные моменты;
- сколько Gameplay Loops одновременно Active;
- сколько ранее принятых решений всё ещё исполняется;
- сколько текущих решений time-sensitive;
- может ли новая Situation стать Active, пока другая остаётся неразрешённой.

Количество одновременно active Situations / Loops — **indicator for review**, а не автоматический score нагрузки или сложности. Его смысл решается на конкретном примере, а не универсальной формулой.

#### Зачем

Это определяет:

- decision pressure;
- темп;
- сложность;
- доступность;
- тип мастерства.

<a id="concern-world-ai-system-response"></a>
### 3.7 World, AI And System Response

#### Что фиксировать

- как мир отвечает на действия;
- что scripted, а что system-driven;
- какие агенты имеют собственное поведение;
- возникают ли непредусмотренные ситуации;
- насколько последствия предсказуемы;
- чувствует ли игрок, что взаимодействует с живой системой;
- какие решения продолжают физически/системно исполняться, пока игрок занимается другими проблемами.

#### Зачем

Помогает отличить:

```text
набор изолированных механик
от
связанной системы, создающей dynamics.
```

<a id="concern-content-production-model"></a>
### 3.8 Content-Production Model

#### Что фиксировать

- что создаётся вручную;
- что возникает из правил;
- что генерируется процедурно;
- что создаёт сам игрок;
- что создаётся взаимодействием игроков;
- сколько новых **meaningful Gameplay Situations** создаёт один новый элемент;
- насколько эти Situations отличаются по решению, а не только по декорации;
- сколько bespoke production требуется для такого gameplay.

#### Зачем

Это центральная линза для нашей будущей разработки:

```text
bespoke content;
systemic content;
procedural content;
player-authored content;
social content.
```

Она показывает не только устройство игры, но и её потенциальную стоимость.

Большее число Situations не автоматически лучше: ценность зависит от качества решений, вариативности, частоты и production cost.

<a id="concern-return-stopping-exhaustion"></a>
### 3.9 Return, Stopping And Exhaustion

#### Что фиксировать

- когда появляется естественная точка остановки;
- почему хочется начать ещё один run, день или миссию;
- что остаётся незавершённым;
- когда повторение начинает утомлять;
- когда игрок чувствует насыщение;
- что изменяется между сессиями;
- насколько удобно вернуться после перерыва.

#### Зачем

Session loop не полностью описывает:

```text
почему игрок заканчивает;
почему возвращается;
когда игра исчерпывается.
```

<a id="concern-causal-legibility-strategic-planning-detail"></a>
### 3.10 Causal Legibility And Strategic Planning

#### Что фиксировать

- почему игрок считает, что текущая Situation возникла;
- связывает ли он её с конкретным state, прошлым выбором или Loop;
- способен ли отличать причину от случайной корреляции настолько, насколько это нужно gameplay;
- может ли предсказывать **направление** результата без знания точных скрытых чисел;
- различает ли direct consequence и delayed/state-mediated effect;
- узнаёт ли повторяющиеся Situation chains / Gameplay Loops;
- может ли отличить one-off consequence от recurrent / developing Dynamic;
- распознаёт ли направление, в которое система имеет тенденцию развиваться;
- может ли подготовиться к Situation заранее, а не только исправлять её после появления;
- может ли формировать желаемый future state;
- может ли планировать вокруг Dynamic и намеренно менять её trajectory;
- существуют ли несколько жизнеспособных стратегий / styles;
- может ли игрок объяснить, почему его собственный стиль работает;
- после failure обновляет ли игрок модель или вынужден random-trial;
- расширяет ли progression причинную модель игрока или постоянно обнуляет её непредсказуемыми исключениями.

#### Граница ответственности

```text
Interface / Readability
= могу ли я считать state и feedback?

Onboarding / Mental Model
= выучил ли я базовые entities / rules / relations?

Causal Legibility
= могу ли я построить полезную причинную модель системы?

Strategic Planning
= могу ли я использовать эту модель,
  чтобы намеренно формировать future state?

Competence / Mastery
= Player Experience payoff от того,
  что я понимаю, тренируюсь и становлюсь лучше.
```

#### Полезная causal chain

```text
rules + world response
→ observable consequences
→ causal legibility
→ mental-model refinement
→ prediction
→ planning
→ strategy / play style
→ system tests strategy
→ readable result
→ model revision
→ competence / mastery.
```

Perfect information не требуется. Discoverable incomplete causality может поддерживать curiosity, если игрок способен постепенно улучшать модель и использовать её.

<a id="concern-balance-decision-space-strategic-diversity-detail"></a>
### 3.11 Balance, Decision Space And Strategic Diversity

Use `balance` as several related questions rather than one vague verdict.

#### Basic Challenge Balance

Ask:

```text
Is there enough pressure / resistance for decisions to matter?
Is gameplay so easy that choices lose value?
Is it so hard that meaningful alternatives disappear?
Does the challenge range support the intended experience?
```

This overlaps deliberately with `Challenge, Failure And Progression`: that concern owns how challenge/failure/progression works; this lens asks whether the operative pressure preserves meaningful decision space.

#### Decision Balance

At local-decision scale ask:

> **При каких relevant states различные варианты остаются meaningful, вместо того чтобы один вариант становился universally correct?**

Also ask:

```text
Which options are viable in which states?
Why might a reasonable player choose each?
Does one local response dominate across the relevant range?
```

#### Strategic Balance

At broader scale ask:

```text
Which strategies / play styles are viable under different
goals / states / risks / time horizons?

Do several different Mechanics / Loops mainly reward
the same higher-level strategy?

Does gameplay converge toward one dominant meta-strategy?

Can changing state make a previously strong strategy weaker
and another strategy more attractive?
```

Several strategies do not need to be equally strong at every moment. Strategic richness can come from **contextually viable** strategies whose value changes with state, goals and trade-offs.

#### Required Decision / Strategy Diversity

More choices, goals or strategies are not automatically better. Ask:

```text
How much meaningful diversity does the intended game actually need?
Are the available approaches materially different in plan / trade-off / future state?
Are there enough ways to pursue the important goals?
Is apparent variety only cosmetic or execution-level variation?
Does extra variety create choice overload without additional value?
```

The target is **required meaningful diversity**, not maximum option count.

<a id="concern-dynamics-state-opportunity-trajectory-detail"></a>
### 3.12 Dynamics And State / Opportunity Trajectory

A `Gameplay Dynamic` is defined canonically in [`Mechanics Create Dynamics`](../principles/mechanics-create-dynamics-principles-and-terminology.md). This concern reviews what the operative system tends to become over time.

#### Что фиксировать

- какая recurrent / persistent / directionally developing causal tendency возникает;
- при каких relevant states / preconditions tendency реально действует;
- когда она начинается или становится заметной;
- за какой time horizon / число циклов она становится material;
- что поддерживает её persistence; достигает ли она saturation / equilibrium;
- какие условия, state changes или counter-strategies ослабляют, останавливают или разворачивают её;
- какие Mechanics / Rules / Loops / decisions причинно поддерживают её;
- как меняются resources, capabilities, territory, population, knowledge, reserves, risk или другие relevant states;
- какие opportunities появляются / исчезают;
- какие Gameplay Situations становятся более / менее вероятными или частыми;
- какие решения эти Situations реально производят: meaningful trade-offs или obvious / administrative responses;
- как меняются их stakes, option availability, option cost / value / risk;
- какие broader strategies становятся более / менее выгодными;
- есть ли positive feedback, negative feedback, stabilization, snowball, loss spiral, overreach или convergence toward one strategy;
- какие другие Loops / Dynamics tendency усиливает, подавляет или перенаправляет;
- может ли игрок понять и сознательно повлиять на trajectory.

#### Scale interpretation

Apply the same concern differently by scale:

```text
Situation
  → which important Dynamic could repeated / accumulated
     consequences contribute to?

Loop
  → which expected / possible Dynamics may recurrence produce?

Dynamic
  → what is the causal tendency, trajectory and strategic effect itself?

Scenario
  → which candidate Dynamics manifest in this concrete chronology,
     and what evidence does the path provide?
```

A single consequence or metric movement is not automatically a Dynamic. A single Scenario manifestation is not automatically proof of a stable Dynamic. Do not describe a tendency as universal when it only operates in a particular state range or time horizon.

When planning rather than analysing an already-observed game, keep current / accepted Dynamic meaning visibly separate from candidate / hypothesized Dynamics using the repository's existing planning / evidence discipline; do not invent another Dynamic-specific status taxonomy.

#### Зачем

Individually good Situations and Loops can still produce a weak higher-level game if their accumulated incentives and state changes converge toward rote optimization, permanent firefighting, one dominant strategy or another unintended systemic pattern. Conversely, a useful Dynamic can create adaptation, strategic expression and long-term mastery that is invisible in one isolated decision.

<a id="concern-concurrency-loop-overlap-decision-load"></a>
### 3.13 Concurrency, Loop Overlap And Decision Load

This is primarily a **Content Structure And Pacing** concern. Cross-reference `Time, Attention And Information` when the same structure also creates cognitive or information overload.

#### Что фиксировать

- сколько Gameplay Situations обычно остаются Active одновременно;
- сколько Gameplay Loops одновременно Active;
- давление идёт по одной Situation за раз, по нескольким Situations внутри одного Loop или через competition нескольких Loops;
- как долго Situation может оставаться unresolved;
- сколько одновременно Active Situations являются time-sensitive;
- возникают ли новые Situations, пока предыдущие decisions всё ещё исполняются;
- меняет ли разрешение одной Active Situation options, prerequisites, stakes или risk другой;
- имеет ли значение порядок разрешения нескольких одновременно Active Situations;
- как concurrency растёт и падает по Scenario / session;
- создаёт ли overlap meaningful prioritization, challenge и pacing или только шум / overload;
- может ли опытный игрок намеренно избегать, синхронизировать или использовать overlap Loops.

Количество одновременно active Situations / Loops можно записывать как простой observable. Само число не определяет наличие нагрузки; это оценивается на конкретном примере.

#### Граница ответственности

```text
Content Structure / Pacing
  → как meaningful decisions, Loops, peaks, breathing room
     и overlap структурированы во времени;

Time / Attention / Information
  → сколько событий/сигналов нужно отслеживать,
     что нужно помнить и где возникает cognitive/information overload.
```

Не создавайте отдельную top-level Game Structure category только ради concurrency counts: это подробный pacing concern с важным cross-reference к Time/Attention/Information.

## 4. Полезные дополнительные линзы

<a id="lens-friction-quality-of-life"></a>
### 4.1 Friction And Quality Of Life

- Что игрок повторяет механически?
- Что занимает больше действий, чем решений?
- Где приходится ждать?
- Где UI заставляет выполнять лишнюю работу?
- Какая friction намеренная, а какая случайная?

<a id="lens-accessibility-physical-comfort"></a>
### 4.2 Accessibility And Physical Comfort

- Насколько важны скорость реакции и точность?
- Можно ли переназначить управление?
- Есть ли визуальная, звуковая или когнитивная перегрузка?
- Можно ли остановиться?
- Можно ли восстановить контекст после перерыва?

<a id="lens-audio-information"></a>
### 4.3 Audio As Information

Звук уже затрагивается в сенсорном опыте, но полезно отдельно спросить:

- Что звук сообщает о состоянии игры?
- Можно ли услышать угрозу, успех, ошибку или изменение системы?
- Что потеряется при игре без звука?

<a id="lens-transfer-production-relevance"></a>
### 4.4 Transfer And Production Relevance

- Что здесь является несущим?
- Что является поверхностью?
- Что можно перенести в другую игру?
- Какие условия обязательны?
- Какой элемент выглядит дорогим?
- Какой элемент создаёт особенно много gameplay?

## 5. Scenario-Scale Explicit Review

A detailed gameplay Scenario can inspect every concern above. In addition, normally make an explicit review of:

```text
Core / Session / Long-Term Loops;
Player Verbs And Decisions;
Goals, Motivation And Direction;
Rules, Resources And Economy;
Challenge, Failure And Progression;
Balance, Decision Space And Strategic Diversity;
Dynamics And State / Opportunity Trajectory;
Time, Attention And Information;
Content Structure And Pacing;
Concurrency, Loop Overlap And Decision Load;
World, AI And System Response;
Causal Legibility And Strategic Planning;
Interface, Feedback And Readability.
```

For a first-play/full-demo Scenario also explicitly inspect:

```text
Onboarding And Mental Model;
Return, Stopping And Exhaustion.
```

Use `Content-Production Model` explicitly when the Scenario is also a production-feasibility artifact.

`Explicit review` means deliberately check the concern. `Nothing material found` is a valid result.

### Scenario pacing / concurrency prompts

In `Content Structure And Pacing`, also ask:

```text
How do Active Situation and Active Loop counts rise and fall?
Where are peaks and breathing room?
Where do Loops overlap?
How long is decision → feedback delay?
Does overlap create meaningful prioritization or only overload/noise?
Does repetition become rote?
Which candidate Dynamics become visible across the chronology?
How does viable strategic space differ between entry and exit?
```

In `Player Verbs And Decisions`, ask when relevant:

> Does the order of resolving two simultaneously Active Situations materially change their options, risks or consequences?

Do not use broad downstream economy effects as proof of a tight decision-order dependency.

## 6. Causal Follow-Up

For a load-bearing observation, connect the concern to a causal record rather than leaving it as an isolated impression:

```text
Mechanic / Rule
  → Dynamics
  → Player Behavior
  → Player Experience
  → Conditions
  → Trade-offs
  → Evidence
  → Transfer Note.
```
