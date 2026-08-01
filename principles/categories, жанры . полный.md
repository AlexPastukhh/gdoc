## Главный вывод

**Единой правильной классификации жанров не существует**, потому что слово «жанр» используется для разных задач:

* покупатель спрашивает: «На что это похоже?»;
* дизайнер: «Как устроено взаимодействие?»;
* Steam: «По каким тегам показывать игру?»;
* аналитик: «С какими играми сравнивать продажи?»;
* продюсер: «Какой объём производства потребуется?».

Исследователи также критикуют плоские рыночные жанры: категории, основанные на теме, визуале или старых медиа, часто скрывают реальные структурные сходства игрового процесса. ([Sage Journals][1])

Поэтому для `gdoc` лучше не строить одно огромное дерево, а использовать **несколько согласованных карт**.

# Хорошие способы классификации

## 1. Рыночная классификация: один основной жанр

Это подход How To Market A Game:

```text
Primary market genre
+ Secondary modifier
+ Familiar anchor
+ Hook
```

Например:

```text
Primary genre:
  Colony Sim

Secondary modifier:
  Survival

Anchor:
  RimWorld-like colony management

Hook:
  colony exists inside a moving train
```

Chris Zukowski при анализе рынка старается присвоить каждой игре **один основной жанр**, даже если у неё несколько тегов. Для позиционирования он рекомендует находить 3–5 наиболее похожих игр и смотреть, какой audience cluster уже понимает такой продукт. ([How To Market A Game][2])

### Сильная сторона

* удобно для SteamTrender;
* позволяет считать конкурентов;
* формирует comparison set;
* помогает написать короткое описание;
* заставляет выбрать, кто является основной аудиторией.

### Ограничение

Одна игра может иметь несколько важных систем. Если назвать её только `RPG`, мы почти ничего не узнаем о реальном gameplay.

Кроме того, некоторые рыночные жанры являются не механическими жанрами, а audience clusters. Например, `Horror` может включать walking simulator, co-op survival, job simulator, shooter и visual novel. How To Market A Game сам называет horror скорее meta-genre. ([How To Market A Game][3])

### Правило для нас

У каждой игры должен быть:

```text
ровно один Primary Market Genre;
не более одного Secondary Genre;
остальные свойства не называются жанрами автоматически.
```

---

## 2. Steam-классификация: профиль из независимых граней

Steam использует не только жанры. Tag Wizard отдельно рассматривает:

| Грань                | Примеры                                             |
| -------------------- | --------------------------------------------------- |
| Super-genre          | Action, Strategy                                    |
| Genre                | Platformer, RPG                                     |
| Subgenre             | Precision Platformer, Party-Based RPG               |
| Perspective          | First-Person, Top-Down, Isometric                   |
| Visual style         | Pixel Graphics, Low Poly, Realistic                 |
| Theme                | Fantasy, Space, Zombies                             |
| Mood                 | Relaxing, Atmospheric, Funny                        |
| Mechanics/features   | Resource Management, Trading, Procedural Generation |
| Player configuration | Singleplayer, Co-op, MMO                            |

Steam рекомендует поднимать конкретный поджанр выше общего жанра. Его официальный пример: `Action → Platformer → Precision Platformer`. Steam также разделяет способы поиска на genre, theme и player mode. ([Steamworks][4])

Valve строит гибкую иерархию, используя исследования и совместную встречаемость тегов. При этом слишком широкие категории могут оказаться бесполезными: Valve приводила `Action-Adventure` как пример категории, которая недостаточно отличалась от соседних Action и Adventure. 

### Сильная сторона

Это лучший формат для:

* Steam store;
* поиска похожих игр;
* SteamTrender-запросов;
* проверки позиционирования;
* рекомендаций и tag pages.

### Ограничение

Теги могут быть неточными, избыточными и применяться к разным уровням описания. `Simulation`, `RPG` или `Action` часто слишком широки. How To Market A Game прямо предупреждает, что механическое использование одного Steam-тега может давать плохую выборку; иногда жанр приходится задавать комбинацией тегов. ([How To Market A Game][5])

---

## 3. Структурная многомерная классификация

Aarseth, Smedstad и Sunnanå предложили описывать игры не одним ярлыком, а комбинацией измерений, включая:

```text
Space
Perspective
Time
Teleology / конечность
и другие структурные свойства
```

Такой подход может показывать различия между играми внутри одного жанра и потенциальные новые комбинации характеристик. ([DiGRA Digital Library][6])

Для нашей практики полезна упрощённая версия:

| Измерение           | Примеры значений                                        |
| ------------------- | ------------------------------------------------------- |
| Space               | discrete rooms, continuous world, board, open world     |
| Perspective/control | avatar, cursor, squad, indirect management              |
| Time                | real-time, turn-based, pausable, simultaneous turns     |
| Goal structure      | finite campaign, repeated runs, endless optimization    |
| Information         | complete, hidden, uncertain, asymmetric                 |
| Player relation     | solo, cooperative, competitive, mixed                   |
| Session structure   | match, run, day, mission, persistent world              |
| Progression         | knowledge, skill, stats, collection, territory, economy |

### Сильная сторона

Позволяет сравнить игры, которые называются разными жанрами, но структурно похожи.

Например:

```text
Slay the Spire
и
Into the Breach
```

имеют разные рыночные жанры, но оба используют:

```text
дискретные решения;
частично предсказуемую информацию;
короткие encounters;
run structure;
накопление стратегических последствий.
```

### Ограничение

Такая карта плохо работает как название на странице Steam. Никто не будет искать «finite-goal pausable indirect-control resource-conversion game».

---

## 4. Классификация через действия и цели

Gameplay Bricks классифицируют игры через повторяющиеся элементы правил:

```text
что игрок может делать;
чего он должен достичь.
```

Авторы разделяют, в частности, правила манипулирования игровыми элементами и правила, определяющие цели. ([Wiley Online Library][7])

Похожий Game Ontology Project предлагает описывать:

```text
interface;
rules;
goals;
entities;
entity manipulation.
```

([DiGRA Digital Library][8])

Практическая версия для `gdoc`:

### Dominant verbs

```text
move;
aim;
fight;
dodge;
collect;
build;
place;
connect;
trade;
schedule;
optimize;
negotiate;
investigate;
deduce;
choose;
survive.
```

### Dominant goals

```text
reach;
eliminate;
protect;
acquire;
construct;
maintain;
escape;
discover;
solve;
maximize;
outlast;
express.
```

### Сильная сторона

Она отвечает на главный дизайнерский вопрос:

> Что игрок регулярно делает и к какому состоянию стремится?

Это полезнее ярлыка `Simulation`, который может обозначать Euro Truck Simulator, PowerWash Simulator, The Sims или сложную экономическую модель.

### Ограничение

Одинаковые verbs могут создавать совершенно разный опыт из-за экономики, темпа, информации и feedback.

---

## 5. Причинная классификация через MDA и Player Experience

MDA предлагает анализировать:

```text
Mechanics
→ Dynamics
→ Aesthetics / Player Experience
```

([AAAI][9])

В терминах `gdoc`:

```text
rules and mechanics
→ system dynamics
→ observable player behavior
→ target experience
```

Можно группировать игры по доминирующей ценности:

| Experience family           | Примеры рыночных жанров                   |
| --------------------------- | ----------------------------------------- |
| Mastery                     | Soulslike, Precision Platformer, Fighting |
| Strategic adaptation        | Roguelike Deckbuilder, 4X, Tactics        |
| Discovery                   | Metroidvania, Exploration Adventure       |
| Construction and expression | City Builder, Sandbox, Automation         |
| Care and routine            | Farming Sim, Life Sim, Cozy Management    |
| Tension and vulnerability   | Survival Horror, Extraction               |
| Social coordination         | Co-op Horror, Party Co-op                 |
| Optimization                | Factory Automation, Tycoon, Incremental   |

### Сильная сторона

Объясняет, почему аудитории могут пересекаться между формально разными жанрами.

### Ограничение

Experience не заменяет жанр. `Mastery` может появляться в racing, fighting, puzzle и strategy.

---

## 6. Жанр как набор conventions и design patterns

Genre можно понимать не как строгий класс, а как набор повторяющихся:

```text
design values;
structural patterns;
audience expectations;
aesthetic conventions.
```

Исследования game design patterns предлагают сравнивать игры через повторяющиеся модели взаимодействия, а genre design research — делать утверждения о жанре явными и проверяемыми: какие design values, structures и aesthetics делают игры похожими. ([DiGRA Digital Library][10])

Например, `Colony Sim` — не просто тег. У него обычно есть conventions:

```text
несколько управляемых агентов;
косвенное управление;
ресурсные цепочки;
пространственное строительство;
потребности агентов;
системные кризисы;
долгосрочная история поселения;
частичная потеря контроля;
генерация историй через динамику систем.
```

Если убрать половину этих anchors, проект может перестать восприниматься аудиторией как Colony Sim, даже если сохранить визуальный вид.

How To Market A Game называет такие узнаваемые элементы **anchors** и предупреждает, что слишком большое смешение жанров может одновременно разрушить ожидания аудитории и умножить production scope. ([How To Market A Game][11])

# Итоговая система для `gdoc`

Предлагаю использовать **четыре связанные картины**.

## Картина A — Market Genre Map

Это каталог рыночных категорий, понятных покупателям.

```text
Market Family
  → Primary Genre
    → Recognized Subgenre
```

Пример:

```text
Build / Manage / Simulate
  → Colony Sim
    → Survival Colony Sim
```

Его функции:

* выбор ниши;
* SteamTrender;
* comparison set;
* позиционирование;
* store promise.

### Начальные market families

```text
Action And Combat
Shooters
Platformers
Adventure And Narrative
RPG
Strategy And Tactics
Building And Management
Simulation
Survival And Crafting
Roguelike And Run-Based
Puzzle And Deduction
Card And Tabletop
Racing And Sports
Casual, Idle And Incremental
Social, Party And Multiplayer
```

`Horror`, `Cozy`, `Automation`, `Extraction` и похожие категории могут выступать:

* самостоятельным market cluster;
* subgenre;
* experience/theme modifier;

их роль определяется реальными comparables, а не заранее навязанным местом в дереве.

---

## Картина B — Game Design Genome

Она описывает, **как работает игра**, независимо от store label.

```text
Dominant loop
Player verbs
Goal structure
Rules and constraints
Resources and economy
Information structure
Space and perspective
Time and session structure
Player configuration
Failure and recovery
Progression
Content structure
Target experience
```

Пример:

```text
Primary genre:
  Colony Sim

Dominant loop:
  inspect needs
  → assign construction
  → allocate resources
  → respond to crisis
  → expand

Control:
  indirect multi-agent

Time:
  real-time with pause

Goal:
  open-ended survival and growth

Experience:
  planning, attachment, emergent crisis

Production shape:
  systemic, content-light but balance-heavy
```

---

## Картина C — Steam Tag Profile

Это platform-facing представление:

```text
1. most specific subgenre
2. primary genre
3. dominant gameplay structure
4. strongest mechanic
5. audience-defining theme or mood
6–20. perspective, modes, secondary mechanics,
      visual style and other accurate attributes
```

Пример:

```text
Colony Sim
Base Building
Resource Management
Survival
Management
Procedural Generation
Sandbox
Real-Time with Pause
Singleplayer
Sci-Fi
```

Top tags должны давать ясную картину, поскольку Steam использует tag profile для browsing, similarity и части рекомендаций. ([Steamworks][4])

---

## Картина D — Market Research Query

Это не описание игры, а воспроизводимый запрос к SteamTrender:

```text
Primary inclusion:
  Colony Sim

Supporting inclusions:
  Base Building
  Resource Management

Optional segmentation:
  Survival
  Sci-Fi

Exclusions:
  Multiplayer
  Free to Play
  City Builder

Release period:
  2021–2026

Minimum reviews:
  <recorded threshold>

Snapshot date:
  <date>
```

Один проект может иметь несколько запросов:

```text
broad market:
  Colony Sim

direct competitors:
  Colony Sim + Survival

specific promise:
  Colony Sim + Survival + Sci-Fi
```

Это позволяет не путать:

```text
жанр игры
с
фильтром аналитического исследования.
```

# Полная карточка классификации

```text
Game:

Market Identity
  Primary Market Genre:
  Recognized Subgenre:
  Secondary Genre:
  Anchor:
  Hook:
  Comparison Set:

Gameplay Structure
  Dominant Loop:
  Dominant Verbs:
  Goal Structure:
  Resources / Economy:
  Time / Session:
  Space / Perspective:
  Player Configuration:
  Progression:
  Failure / Recovery:

Experience
  Purchase Fantasy:
  Target Player Experience:
  Theme:
  Mood:

Production
  Systemic vs authored:
  Content burden:
  Balance burden:
  Multiplayer burden:
  Expected session length:

Steam
  Top 5 tags:
  Supporting tags:
  Excluded misleading tags:

Research
  SteamTrender query:
  Period:
  Filters:
  Snapshot date:
```

## Принцип, который стоит закрепить

```text
Genre is not one property of a game.

Market Genre
  tells the audience what comparison to make.

Design Profile
  explains how play is produced.

Steam Tag Profile
  describes the game to the platform.

Research Query
  defines which market sample is being measured.
```

Итог: **одно основное рыночное имя плюс многомерный профиль**, а не попытка засунуть каждую игру в одну ветку универсального дерева.

[[CHH_MESSAGE_NUMBER: 34]]

[1]: https://journals.sagepub.com/doi/pdf/10.1177/1046878105282278?utm_source=chatgpt.com "Genre and game studies: Toward a critical approach to video game genres - Thomas H. Apperley, 2006"
[2]: https://howtomarketagame.com/2020/11/12/steam-101-how-to-tag-your-game/?utm_source=chatgpt.com "Steam 101: How to tag your game – How To Market A Game"
[3]: https://howtomarketagame.com/2025/11/12/the-cycle-of-a-hit-genre/?utm_source=chatgpt.com "The cycle of a hit genre – How To Market A Game"
[4]: https://partner.steamgames.com/doc/store/tags?utm_source=chatgpt.com "Steam Tags (Steamworks Documentation)"
[5]: https://howtomarketagame.com/2022/04/18/what-genres-are-popular-on-steam-in-2022/?utm_source=chatgpt.com "What genres are popular on Steam in 2022 – How To Market A Game"
[6]: https://dl.digra.org/index.php/dl/article/view/66?utm_source=chatgpt.com "A multidimensional typology of games | DiGRA Digital Library"
[7]: https://onlinelibrary.wiley.com/doi/10.1155/2008/470350?utm_source=chatgpt.com "A Gameplay Definition through Videogame Classification - Djaouti - 2008 - International Journal of Computer Games Technology - Wiley Online Library"
[8]: https://dl.digra.org/index.php/dl/article/view/136?utm_source=chatgpt.com "Towards an Ontological Language for Game Analysis | DiGRA Digital Library"
[9]: https://new.aaai.org/Library/Workshops/2004/ws04-04-001.php?utm_source=chatgpt.com "MDA: A Formal Approach to Game Design and Game Research"
[10]: https://dl.digra.org/index.php/dl/article/view/60?utm_source=chatgpt.com "Game Design Patterns | DiGRA Digital Library"
[11]: https://howtomarketagame.com/2019/12/23/know-your-games-anchor/?utm_source=chatgpt.com "Know your game’s anchor – How To Market A Game"
