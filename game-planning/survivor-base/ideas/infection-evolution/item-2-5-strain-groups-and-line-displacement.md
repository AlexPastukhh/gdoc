# Item 2 + 5 — Разные штаммы / группы штаммов и вытеснение линий

**Record type:** standalone Idea
**Status:** preserved Idea with researched clarification; final fictional-virus architecture remains open
**Design Direction:** [`README.md`](README.md) — INF-EVO — Infection Evolution
**Source:** `SB-B01-SRC01 items 2 and 5`; later research/fixation summarized in `SB-B01-C01`.

## Source / Need

`SB-B01-SRC01 items 2 and 5`; later research/fixation summarized in `SB-B01-C01`.

## Preserved Idea / Clarification

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
