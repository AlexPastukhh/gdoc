# Game Structure Analysis

Status: active reusable analysis reference
Scope: a detailed question set for examining how an existing game creates activity, decisions, dynamics, experience, content and production burden.

Canonical reference-analysis principles remain in [`Reference First And Controlled Transformation`](../principles/reference-first-and-controlled-transformation-principles-and-terminology.md). This file owns the detailed operational question set.

## 1. How To Use This File

Use the core map for a broad whole-game or large-subsystem analysis. Use detailed concerns and additional lenses only when they clarify a real observation or uncertainty.

The file asks questions. An analysis of one concrete game owns the answers.

## 2. Core Reference Analysis Map

| Core aspect | Что фиксировать | Зачем это в reference analysis |
|---|---|---|
| <a id="concern-player-promise-audience"></a>**Player promise and audience** | Какой опыт обещает игра, кому она понятна, с какими играми сравнивается | Без этого невозможно понять, что в игре является несущим, а что декоративным |
| <a id="concern-core-session-loop"></a>**Core loop and session loop** | Что игрок делает повторно за секунды/минуты; как устроена одна сессия или ран | Главное место, где референсы чаще всего заимствуются и чаще всего ломаются при переносе |
| <a id="concern-player-verbs-decisions"></a>**Player verbs and decisions** | Главные действия игрока и повторяющиеся развилки выбора | Помогает отличить “жанровую оболочку” от реальной agency и decision density |
| <a id="concern-rules-resources-economy"></a>**Rules, resources, and economy** | Внутренние ограничения, ресурсы, награды, обмены, cost structure | Экономика часто переносится лучше, чем сеттинг; именно она создаёт многие dynamics |
| <a id="concern-challenge-failure-progression"></a>**Challenge, failure, and progression** | Как игрок ошибается, восстанавливается, учится и открывает новое | Это ключ к мастерству, pacing и retention; также важный источник конфликтов при смешении референсов |
| <a id="concern-interface-feedback-readability"></a>**Interface, feedback, and readability** | Как игра сообщает состояние системы, опасность, успех, возможности | Многие «необъяснимые» преимущества референса живут не в правилах, а в сигналах и обратной связи |
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

<a id="concern-goals-motivation-direction"></a>
### 3.3 Goals, Motivation And Direction

#### Что фиксировать

- чего игрок пытается достичь прямо сейчас;
- кто поставил цель: игра или сам игрок;
- какие цели краткосрочные и долгосрочные;
- как появляется следующая цель;
- что создаёт ощущение направления;
- может ли игрок сформировать собственный план.

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
- чувствует ли игрок, что взаимодействует с живой системой.

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
- сколько новых ситуаций создаёт один новый элемент.

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

## 5. Causal Follow-Up

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
