# Game Structure Analysis

Status: active reusable analysis reference
Scope: a detailed question set for examining how an existing game or planned gameplay structure creates activity, decisions, dynamics, experience, content and production burden.

Canonical reference-analysis principles remain in [`Reference First And Controlled Transformation`](../principles/reference-first-and-controlled-transformation-principles-and-terminology.md). Canonical Gameplay Situation / Loop / Scenario meanings remain in [`Gameplay Situations, Loops And Scenarios`](../principles/gameplay-situations-loops-and-scenarios-principles-and-terminology.md). This file owns the detailed structural question set.

## 1. How To Use This File

Use the core map for a broad whole-game or large-subsystem analysis. Use detailed concerns and additional lenses when they clarify a real observation or planning uncertainty.

The same concern set may also be inspected at several planning scales:

```text
whole game;
Gameplay Situation;
Gameplay Loop;
Scenario;
concrete demo.
```

At Situation/Loop/Scenario scale, inspect the full set as a discovery surface and record only concerns with material meaning. Do not mechanically fill every concern.

For a reference analysis, the concrete analysis owns the answers. For a project-planning pass, the appropriate project detail owner owns the answers.

## 2. Core Reference / Structure Analysis Map

| Core aspect | Что фиксировать | Зачем это в analysis / planning |
|---|---|---|
| <a id="concern-player-promise-audience"></a>**Player promise and audience** | Какой опыт обещает игра, кому она понятна, с какими играми сравнивается | Без этого невозможно понять, что в игре является несущим, а что декоративным |
| <a id="concern-core-session-loop"></a>**Core loop and session loop** | Что игрок делает повторно за секунды/минуты; как устроена одна сессия или ран; какие конкретные recurrent processes реально существуют | Помогает отличить broad loop thesis от конкретных повторяемых causal processes и увидеть структуру сессии |
| <a id="concern-player-verbs-decisions"></a>**Player verbs and decisions** | Главные действия игрока и повторяющиеся развилки выбора | Помогает отличить “жанровую оболочку” от реальной agency и decision density |
| <a id="concern-rules-resources-economy"></a>**Rules, resources, and economy** | Внутренние ограничения, ресурсы, награды, обмены, cost structure | Экономика часто переносится лучше, чем сеттинг; именно она создаёт многие dynamics |
| <a id="concern-challenge-failure-progression"></a>**Challenge, failure, and progression** | Как игрок ошибается, восстанавливается, учится и открывает новое | Это ключ к мастерству, pacing и retention; также важный источник конфликтов при смешении референсов |
| <a id="concern-interface-feedback-readability"></a>**Interface, feedback, and readability** | Как игра сообщает состояние системы, опасность, успех, возможности | Многие «необъяснимые» преимущества референса живут не в правилах, а в сигналах и обратной связи |
| <a id="concern-causal-legibility-strategic-planning"></a>**Causal legibility and strategic planning** | Может ли игрок построить полезную причинную модель, предсказывать направление последствий и использовать её для подготовки/стратегии | Связывает feedback, mental model, repeated Loops и mastery; особенно важно в системных играх с delayed/state-mediated effects |
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
- может ли игрок сформировать собственный план;
- какие будущие состояния/ситуации игрок ожидает и пытается приблизить или избежать.

#### Зачем

Loop объясняет повторение действий, но не всегда объясняет:

> Почему игрок выбирает именно это действие сейчас?

<a id="concern-space-camera-control"></a>
### 3.4 Space, Camera And Control

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
### 3.5 Time, Attention And Information

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
### 3.6 World, AI And System Response

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
### 3.7 Content-Production Model

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
### 3.8 Return, Stopping And Exhaustion

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
### 3.9 Causal Legibility And Strategic Planning

#### Что фиксировать

- почему игрок считает, что текущая Situation возникла;
- связывает ли он её с конкретным state, прошлым выбором или Loop;
- способен ли отличать причину от случайной корреляции настолько, насколько это нужно gameplay;
- может ли предсказывать **направление** результата без знания точных скрытых чисел;
- различает ли direct consequence и delayed/state-mediated effect;
- узнаёт ли повторяющиеся Situation chains / Gameplay Loops;
- может ли подготовиться к Situation заранее, а не только исправлять её после появления;
- может ли формировать желаемый future state;
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

<a id="concern-concurrency-loop-overlap-decision-load"></a>
### 3.10 Concurrency, Loop Overlap And Decision Load

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
