<!-- obs-file-category:v3 {"schemaVersion":3,"id":"game-genre-catalog","name":"Game Genre Catalog"} -->

# Game Genre Catalog

Category type: `catalog-root`

## Purpose

The selected source does not treat every familiar game label as one flat genre list. It separates:

- рыночные жанры;
- структурные модификаторы;
- experience-надстройки;
- режимы игроков;
- остальные фасеты;
- устойчивые гибриды;
- модификаторы стоимости.

A primary genre says which gameplay and audience expectation are central. A normative genre profile shows what is required and typical. The Game Analysis Reference checks a concrete game. A production profile shows where the genre usually requires resources. Modifiers adjust the cost of a concrete implementation.

## Source Provenance

- Repository: `AlexPastukhh/chats-history`
- Path: `archive/6a6fb5c7-48c0-83eb-9c8c-671560fa40b0/2026-08-02T22-08-41-322Z_batch-8e68e1d4-2d26-4d83-89dc-d4f372426e7f.md`
- Blob: `3ce82035e0a89c8d93aee9ffcd3bf235927241ce`
- Conversation messages: 53.2–56
- Later identity and example owner: message 56, `Genre Catalog v0.2`
- Earlier detailed-profile and model owner: message 54, `Genre Catalog v0.1`

## Production Cost Model

### P — стоимость честного прототипа

Насколько трудно сделать версию, которая действительно проверяет жанровое ядро.

### C — минимальная стоимость убедительного коммерческого продукта

Насколько трудно сделать продукт, который уже удовлетворяет базовые ожидания аудитории жанра.

| Оценка | Значение |
|---:|---|
| 1 | Компактная реализация доступна начинающему соло-разработчику |
| 2 | Реализуемо соло при узком scope |
| 3 | Нужен опытный соло-разработчик или маленькая команда |
| 4 | Высокий риск для соло, естественнее маленькая команда |
| 5 | Командный или инфраструктурный масштаб |

Оценки являются рабочими гипотезами, а не статистикой стоимости разработки. Они предполагают singleplayer, умеренную визуальную сложность, отсутствие полной озвучки и live service.

### Burden dimensions

- Systems and simulation
- Bespoke content
- Art and animation
- UI and information design
- AI
- Balance
- QA state space
- Narrative
- Online and operations

### Content leverage

Сколько новых игровых ситуаций создаёт одно новое правило, здание, существо, оружие, ресурс, карта или событие.

## Statement Status

- `[R] Required` — без этого классификация обычно неверна.
- `[T] Typical` — часто встречается и ожидается, но не определяет жанр самостоятельно.
- `[V] Variant` — характеризует признанную ветвь жанра.
- `[N] Non-defining` — может присутствовать, но не должно использоваться как основание жанра.

## Recommended Definition Order

### Первая волна — основная для разработки

- Incremental / Idle
- Run-Based Deckbuilder
- Auto Battler
- Survivors-like
- Tower Defense
- Shop Management
- Job Simulator
- Tycoon / Management
- Factory Automation
- City Builder
- Colony Sim
- Turn-Based Tactics
- Traditional Roguelike

### Вторая волна — контрольные и сравнительные жанры

- Puzzle
- Programming Puzzle
- Visual Novel
- Platformer
- Metroidvania
- Narrative Adventure
- Single-Player Shooter
- Action RPG
- Soulslike

### Третья волна — сложные направления

- Farming Sim
- Open-World Survival Craft
- RTS
- 4X
- Grand Strategy
- Immersive Sim

### Отдельные надстройки

- Roguelite
- Horror
- Cozy
- Extraction
- Open World
- Sandbox
- Co-op
- PvP

These overlays should have separate files but should not always be allowed as the only Primary Genre.

## Content-Production Distinction

The source distinguishes systemic and bespoke production burdens. A systemic game is not automatically easy: savings in authored levels can move into UI, simulation, balance and QA.

## Update Rule

Preserve source wording and uncertainty. Do not silently invent missing R/T/V/N claims, numeric burden scores, examples, tags or market evidence.

<!-- obs-file-category:implied:start -->
## Implied categories

_None._
<!-- obs-file-category:implied:end -->

<!-- obs-file-category:files:start -->
## Files

_None._
<!-- obs-file-category:files:end -->

<!-- obs-file-category:notes:start -->
## Notes

_None._
<!-- obs-file-category:notes:end -->
