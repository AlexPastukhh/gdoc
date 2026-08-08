# Survivor Base Infection Concept — Consolidated Accepted Working Draft

**Версия:** `v0.12-tactical-raids-alarms-emergency-response`\
**Статус:** accepted working Planning Item set\
**Repository integration:** target path `game-planning/survivor-base/game-planning-draft.md`; replacement package prepared against `gdoc@ef72beb5640683fb9617fa11e92fddcb51bf32a8`\
**Imported source:** `survivor-base-planning-draft-v0.12-tactical-raids-alarms-emergency-response.md` (`SHA-256 d866e0d296da25d3377e363657bc6fdde871cc1101bea3e8c1b438dc4c01e933`)\
**Archive / commit / push:** replacement package prepared; commit/push not performed at package-build time

## 0. Что изменено относительно v0.4

Эта версия сводит current meaning в один читаемый драфт, а не добавляет ещё один слой extension-блоков.

- `CHAT-PI-001–022` сохранены и очищены от разнесённых уточнений.
- новый подтверждённый visual block оформлен как `CHAT-PI-023`;
- производство, еда, вода, энергия, текстиль, личные вещи, object contamination, санитарное дублирование производства, физическая логистика, руководители, capabilities и индивидуальное знание оформлены как `CHAT-PI-024–035`;
- `CHAT-PI-011`, `012`, `015`, `017`, `018` расширены новыми подтверждёнными смыслами вместо создания дублей;
- fixed red/yellow/green architecture окончательно считается superseded пользовательскими зонами;
- отдельная air-network явно deferred;
- detailed demo loop / покадровый scenario явно deferred до стабилизации механик и экранов;
- для первой демки preliminary убрана задержка команд игрока: player commands считаются интерфейсной абстракцией и доходят сразу, хотя физическое выполнение занимает время;
- player operational knowledge preliminary принят близким к классическому colony sim; selective hidden states остаются отдельными кандидатами;
- hybrid knowledge direction принят как текущая рабочая гипотеза: **пространство базы остаётся читаемым, но сами люди познаются постепенно**;
- `CHAT-PI-036` обновлён из classic-colony-sim character knowledge в модель `omniscient space / uncertain people`;
- прежний `CHAT-PI-037` больше не является конкурирующей версией discoverable people: он сужен до радикального future-варианта, где физический vision зависит от камер/доверенных наблюдателей;
- добавлен `CHAT-PI-038` про personnel dossiers, доверие и human intelligence;
- private belongings расширены до частной собственности; добавлен `CHAT-PI-039` про внутренний регулируемый обмен/торговлю;
- начало рана получило preliminary structure: ограниченно кастомизируемое trusted core + генерируемое остальное население + проверка качества старта;
- для первой демки принят кандидат фиксированного здания с уже существующим чистым ядром, intake для новых людей, грязными/заваленными проходами и запечатанным заражённым крылом;
- введено различие `sanitary status / authority / trust / force`; верхушка и вооружённые люди больше не смешиваются автоматически с зелёной зоной;
- добавлены `CHAT-PI-040–046`: run setup, starting facility, Command Circle, security/loyalty, external world, run objective и personal future stakes;
- global-map expeditions и мигрирующее внешнее заражённое давление сохранены как сильные, но ещё не финальные направления;
- opening demo получил связку **локальной возможности + внешнего давления**: видимая цель за новым capability и приближающаяся мигрирующая масса заражённых создают окно для подготовки/рейда;
- environment sanitation отделена от абстрактной гигиены: кровь, трупы, поверхности, contaminated waste, временные закрытия и санитарные работники получили отдельного owner;
- переходные шлюзы больше не трактуются как обязательные `yellow/red` объекты: принят более общий **настраиваемый шлюз/пункт проверки**, где игрок сам выбирает процедуры, а специализация потоков является тактикой;
- приём людей оформлен как `проверка → evidence/report ready → решение → сектор/другой шлюз/holding/refuse`, включая emergency mass-admit и возвращение собственных рейдеров;
- охрана развита в отдельную command system: boundary checkpoint, свободный guard post, patrol, escort/reserve; пост может быть встроен в границу пользовательских зон;
- covert execution сохранена как знаковая information/social situation, а ценность ожидания заражённого дополнена terminal-course knowledge, research value и риском потери драматической неопределённости;
- revised population hypothesis поднят выше прежних `18–24`; ориентир `30–40` оставлен только playtest hypothesis;
- уточнена water-realism direction: кипячение и обычная фильтрация не являются универсальным решением любого загрязнения;
- заражённые разделены по threat role на fresh / conserved-old / retained-function variants; fresh outbreak внутри базы может быть опаснее старой внешней массы;
- орда получила stages формирования и threat через потерю периметра/входов, а не только «постоять у двери»;
- локальная орда формируется стягиванием конечной заражённой population mass; игрок потенциально может намеренно перетянуть угрозу из другого района;
- combat aftermath связан с sanitation: кровь, тела, загрязнённые комнаты и закрытые маршруты являются частью цены боя;
- baseline infected ecology принята как finite living-organism model: low activity, питание, каннибализм, животные-хозяева и новые заражения поддерживают угрозу без биологического бессмертия;
- infected herbivores / feed animals с нарушенным страхом перед заражёнными приняты как strong baseline ordinary-run direction;
- крысы, птицы, собаки и другие виды как reservoir/vector/aggressive host остаются current-strain discovery, а не обязательным одинаковым правилом каждого рана;
- небольшое животноводство базы, особенно кролики, добавлено как strong production candidate с closed herd, quarantine, slaughter/butchering и strain-dependent meat safety;
- disease knowledge разделён на **evidence → expert assessment → leadership assumption / policy**, причём scientific assessment не требует от игрока вручную угадывать «правильный ответ»;
- предыдущая формулировка, где вручную принятая working theory автоматически становилась input для правил/исследований, **снята как current baseline**; политика остаётся отдельным решением;
- хорошо зафиксированные наблюдения, записи поведения и controlled experiments получили разный evidence weight; player-visible событие само по себе не обязано становиться сильным научным доказательством;
- hypothesis testing оформлено как исследовательская работа с подходящими субъектами/животными/помещением/персоналом, а содержание живого infected research subject требует еды, воды, охраны и sanitation;
- укусы комаров и других потенциально заражающих животных добавлены как candidate inspection findings в шлюзе и как плановый медицинский осмотр вне перехода;
- mosquito transmission разделён на acquisition, detectable infection/amplification, transmission competence, delay и exposure strength; **никакие численные балансы/частоты укусов пока не фиксируются**;
- laboratory mosquitoes as faster biological indicator сохранены только как поздняя speculative technology: ценность существует лишь если current strain становится обнаружим в комаре раньше, чем direct human test надёжен;
- individual susceptibility / current resilience / specific protection / exposure history сохранены как скрытая infection-risk model без видимой «полоски иммунитета»;
- обычные вирусные/бактериальные болезни и их interaction с current strain могут быть positive/negative/neutral в зависимости от штамма; универсального `простуда = -X иммунитета` не принимается;
- прежняя current-preferred модель **пассивно-стратегического рейда** пересмотрена: подготовка/маршрут остаются стратегическими, но сама raid site получает direct tactical squad control;
- raid squad и base emergency response должны по возможности использовать один command language: позиции, двери, прикрытие, свет, шум/приманивание, отступление, удержание прохода;
- direct tactical raid нужен не ради отдельной RTS, а чтобы дать концентрированные combat situations, которых у хорошо организованной базы может быть сравнительно мало;
- fixed first-demo building расширен candidate-направлением **неисследованного/неосвоенного физического пространства**: тёмный подвал/крыло, неизвестные комнаты, шумы, возможные infected и физический breach наружу;
- current `omniscient space / uncertain people` уточнён: освоенная/известная база остаётся прозрачной, но реально не исследованная часть строения может требовать физической разведки; это не возврат к глобальному camera-fog;
- введён emergency/alarm layer: тревога может начинаться с неполного отчёта `кто-то что-то увидел/услышал`, а не с мгновенного раскрытия точного типа угрозы;
- аварийные планы можно заранее готовить по сектору: route A/B, shelter-in-place, refuge, security response; drills/rehearsal уменьшают хаос исполнения ценой рабочего времени;
- у комнаты/сектора появляется набор rapid emergency commands, включая `evacuate`, `shelter`, `seal`, `lock internal`, `open evacuation corridor`, `security response`, `all clear`;
- `Seal sector` не является магическим гермополем: команда закрывает все физически доступные/работающие границы, которые реально можно закрыть;
- набор alarm threats расширен: fresh/special infected, неизвестный прорыв/окно/дыра, известные infected animals/rodents/birds, insect swarm/vector event и human raiders/intruders;
- проведён audit ключевых предыдущих смыслов; несколько важных вещей, которые были слишком сжаты в v0.4, возвращены в Implementation-Idea backlog.

Полная raw-source/provenance история `S1–S7` остаётся в `survivor-base-planning-items-review-v0.4-accepted.md`. Эта версия — текущий консолидированный смысловой draft.

---

# 1. Game-analysis categories

| ID | Category | Responsibility |
|---|---|---|
| `CAT-01` | **Player promise and audience** | Какой опыт обещает игра, кому она понятна, какие сравнения формируют ожидания |
| `CAT-02` | **Core loop and session loop** | Что игрок делает повторно и как устроен ран / сессия |
| `CAT-03` | **Player verbs and decisions** | Главные действия игрока и повторяющиеся развилки |
| `CAT-04` | **Rules, resources, and economy** | Ограничения, ресурсы, производство, обмены и cost structure |
| `CAT-05` | **Challenge, failure, and progression** | Ошибки, последствия, восстановление, обучение и развитие |
| `CAT-06` | **Interface, feedback, and readability** | Как игра сообщает состояние, риск, неизвестность и возможности |
| `CAT-07` | **Content structure and pacing** | Как подаются события, кризисы, контент и развитие кампании |
| `CAT-08` | **Market position and comparables** | Жанровые ожидания, аналоги и рыночное считывание |
| `CAT-09` | **Visual direction and production fit** | Что игрок видит и насколько визуальное решение доступно производственно |
| `CAT-10` | **Fun, anti-fun, and risks** | Где возникает напряжение/agency и где возможны скука, произвол и перегрузка |

Категории multi-label: один Planning Item может принадлежать нескольким категориям.

---

# 2. Current scope decisions

1. **Visual direction:** preliminary accepted — `CHAT-PI-023`.
2. **Visual references:** exploratory pass уже обсуждался, но accepted reference matrix ещё не собрана. Нужен структурированный pass: игры + архитектурные планы + CCTV/dispatch + медицинские/эпидемиологические интерфейсы + civil-defense / emergency-control imagery.
3. **Detailed loop/demo screenplay:** deferred. Подробно и практически покадрово описывается после стабилизации основных механик и экранов.
4. **Air as a transmission/logistics network:** deferred. Сначала `people + objects + information`.
5. **Exact character-stat list:** deferred; выводится из реальных jobs/scenarios.
6. **Exact water model:** requires research; фильтрация + кипячение не принимаются как универсальное решение для любого загрязнения.
7. **Raids / attacks:** raids теперь current preferred как **strategic preparation + direct tactical control on-site**; exact tactical depth и first-demo scope ещё требуют pass. Attacks на базу остаются containment stress tests.
8. **Fixed three zones:** не являются архитектурой. Базовые risk archetypes допустимы, реальные зоны и правила создаёт игрок.
9. **Player command delivery for first demo:** preliminary **no command latency**. Игрок отдаёт приказ напрямую через UI; пешка всё ещё должна физически выполнить его и может не суметь/отказаться по правилам симуляции.
10. **Player knowledge direction:** preliminary принят гибрид **`omniscient space / uncertain people`**. Игрок видит физическую карту и основные операции как в colony sim, но personality, часть skills, мотивов, скрытых отношений и внутренних состояний могут быть известны неполно и иметь source/confidence.
11. **Readability floor:** очевидные потребности и факты не должны превращаться в загадку. Голод, сон, видимая травма, родство, явный конфликт и наблюдаемое действие должны быть достаточно читаемы, чтобы personality simulation не выглядела случайной.
12. **Skill discovery/progression:** заявленный опыт сначала может быть недостоверным; работа, документы и наблюдение подтверждают реальную компетенцию. После достаточного подтверждения прогресс навыка должен становиться нормально читаемым, чтобы игрок мог привязаться к персонажу и следить за его развитием.
13. **Selective hidden information:** скрытое содержимое карманов, источник/правдивость слуха, тайные намерения и незамеченные преступления остаются отдельными слоями; точный first-demo scope ещё не выбран.
14. **Radical physical-vision alternative:** `CHAT-PI-037` теперь хранит только более тяжёлый вариант, где точный физический vision зависит от камер/доверенных людей/связи. Он deferred и не является current baseline.
15. **Private property / internal exchange:** частная собственность и регулируемый обмен между жителями принимаются как развиваемая system line; точная рыночная модель не выбрана.
16. **First-demo starting fiction:** preliminary accepted — небольшое заранее проверенное clean core уже существует внутри фиксированного здания; новые/хуже известные люди находятся в intake/perimeter и только должны быть интегрированы.
17. **Run setup:** игрок может заранее создать/настроить ограниченный trusted core, но не всё население. Остальная группа генерируется и должна оставаться источником неизвестности.
18. **Start balance:** нужен объективный quality/balance model, который проверяет и общий «вес» старта, и покрытие критических функций. Игроку можно разрешить явно неbalanced setup с предупреждением, а не запрещать его.
19. **Initial green evidence:** исходный green status должен иметь понятное основание — хорошо известная contact history, контролируемое пребывание, защитная экипировка/процедуры и отсутствие известных опасных контактов. Это не просто нарисованный цвет зоны.
20. **First-demo facility:** фиксированное строение является current prototype direction. Procedural architecture для первой демки не нужна.
21. **Command Circle:** current working concept — один или несколько высших руководителей без начальника над ними, которые кооперируются и имеют общий доступ к официальной управленческой информации. Точная fiction игрока остаётся открытой.
22. **Security and loyalty:** вооружённый человек не обязан быть green; оружие, санитарный доступ, политическая власть и доверие считаются разными осями.
23. **External layer:** стратегическая карта остаётся для выбора района/маршрута/снабжения/цели, но raid site может открываться как небольшой directly controlled tactical space. Это не должна быть отдельная дорогая action game.
24. **Global objective:** окончательная цель рана ещё не принята. Сильнейший current candidate — расширять проверенную безопасность, устойчивость сообщества и знание о болезни; demo-objective может быть «превратить аварийное убежище в устойчивую базу».
25. **Personal future stakes:** у персонажей могут быть собственные ожидания/цели на будущее; это принимается как character-system direction, точная глубина для демки открыта.
26. **Opening incentive:** survival/stabilization недостаточно как единственное ближайшее направление. Для демки нужен видимый локальный objective, награда которого открывает новый gameplay capability; strongest current example — сигнал/сведения о внешнем оборудовании для более серьёзного исследования инфекции.
27. **Opening pressure window:** preliminary accepted — игрок заранее знает/подозревает, что через район скоро пройдёт крупная масса заражённых. До этого выгодно успеть сделать внешние дела; во время прохода рейды становятся недоступны или значительно опаснее.
28. **Attention persistence:** если база/рейд привлекли мигрирующую массу шумом или другими действиями, после основного прохода часть заражённых может остаться у базы. Это consequence state, а не обязательно scripted attack/game over.
29. **Sanitation:** кровь, трупы, загрязнённые поверхности и помещения требуют отдельной работы и могут временно закрывать маршрут; точные chemicals/realism требуют research.
30. **Transition шлюзы:** шлюз — placeable/configurable processing point, а не фиксированный `yellow/red` building class. Игрок выбирает, что в нём проверяют/делают; один all-in-one шлюз допустим, разветвление быстрых и специализированных потоков — optimization tactic.
31. **Admission decision:** любой screening/inspection шлюз может закончиться решением `в сектор / в другой шлюз / holding / наружу`. `Не впустить` сохраняется как полноценный player verb для внешних людей.
32. **Emergency holding:** база может иметь защищённую dirty/intake приёмную, куда людей быстро пускают от внешней угрозы без признания их безопасными. Это спасает жизни, но переносит риск внутрь периметра.
33. **Returning expeditions:** свои рейдеры проходят санитарный intake по тем же физическим причинам, но отказать им во внутреннем доступе социально сложнее, чем незнакомцам.
34. **Security commands:** нужны boundary checkpoints, свободные guard posts и patrol/escort-type orders. Не каждое временное перекрытие требует вооружённого человека: compliant population может соблюдать знак/барьер.
35. **Population density:** прежние `18–24` больше не current preferred hypothesis. Для проверки manpower/security/sanitation полезно тестировать примерно `30–40`, сохраняя это как balance hypothesis, не requirement.
36. **Disease-course knowledge:** high-dose direct exposure (например укус или заражённая кровь непосредственно в рану) может иметь более быстрый/тяжёлый course; terminal-course assessment должна оставаться probabilistic knowledge, а не гарантированным `TERMINAL=true`.
37. **Water realism:** кипячение хорошо решает микробиологическую опасность, но не делает воду безопасной при топливе/токсичных химикатах/тяжёлых металлах/солях; обычный portable filter также не считается универсальным virus-removal solution.
38. **Fresh / old threat split:** recently turned заражённые могут быть быстрыми и физически сохранными; старые — истощёнными и склонными к low-activity/conserved state.
39. **Fresh outbreak severity:** внутренняя fresh outbreak среди плотного населения может быть острее и опаснее внешней старой толпы.
40. **Horde formation:** орда стягивает конечную population mass района через attraction/aggregation; бесконечный прирост из воздуха не нужен.
41. **Perimeter threat:** массовая угроза выражается через блокировку входов, обтекание фасада, поиск окон/лестниц/слабых путей и постепенную потерю наружной оболочки.
42. **Barrier model:** classic HP bar для каждой двери не является preferred model; barriers покупают время и переходят через readable states `secure → under assault → failing → breach`.
43. **Combat aftermath:** место боя имеет значение из-за крови, тел, загрязнения и необходимости sanitation/closure после победы.
44. **Baseline ecology:** человеческие заражённые конечны и истощаются; долгую угрозу поддерживают low activity, scavenging, cannibalism, animal feeding и новые заражения.
45. **Baseline infected herbivores:** ordinary-run direction — часть травоядных/других кормовых животных заражается, продолжает кормиться/размножаться и теряет нормальное избегание infected humans.
46. **Animal discovery split:** сам факт non-human infection ecology можно считать известным миру; конкретная host range, animal→human transmission, asymptomatic carriage, behavioural changes и meat/carcass risk исследуются по текущему штамму.
47. **Rats/birds/dogs:** их конкретная роль как reservoir/vector/aggressive host зависит от рана/штамма; baseline не требует, чтобы каждый заражённый вид нападал на человека.
48. **Animal husbandry:** small livestock, особенно rabbits, — strong production candidate. Closed herd/quarantine новых животных должны иметь санитарный смысл.
49. **Meat can remain useful:** заражённое животное не автоматически уничтожает пищевую ценность; при одном штамме опасна разделка сырой туши, но cooking делает мясо безопасным, при другом — нет.
50. **Special finite-population scenario:** отдельный scenario может почти исключать animal reservoir/support и ставить задачу реально пережить конечную infected population до её вымирания.
51. **Disease evidence separation:** истинное свойство штамма, собранные доказательства, expert assessment, позиция/предположение руководства и enacted policy — разные сущности.
52. **No science-quiz baseline:** игрок не обязан вручную выбирать «правильную теорию» там, где специалисты способны сами оценить evidence. Manual working assumption может существовать как позиция руководства, но не является обязательным интерфейсным quiz.
53. **No theory→policy automation for now:** scientific conclusions и leadership assumptions не перенастраивают автоматически шлюзы/правила/здания. Игрок может действовать в соответствии с данными, осторожнее данных или вообще без достаточного основания.
54. **Scientific legitimacy:** врачи/учёные могут оценивать, насколько политика поддерживается доступным им evidence; несогласие с плохо обоснованным решением может стать разговором/слухом/фактором procedural trust.
55. **Hypothesis experiments:** controlled test является отдельной research job. Нужны подходящие subjects/materials, безопасная setup, специалисты и время; repeated/control observations могут повышать качество evidence.
56. **Bite inspection:** visual inspection может искать mosquito bites и укусы/следы контакта с другими потенциально инфекционными животными. Это procedure как для шлюза, так и для обычного планового осмотра без перехода.
57. **Mosquito dimensions, balance deferred:** mosquito acquisition, detectable infection, transmission competence, incubation/delay и exposure dose исследуются раздельно. Exact prevalence, bite frequency, infection probability и balance не фиксируются сейчас.
58. **Mosquito diagnostic amplification:** late speculative candidate — собственные laboratory mosquitoes могут быть использованы в тесте, только если конкретный strain становится detectably infected/amplified в них раньше, чем direct human testing достигает полезной чувствительности.
59. **Hidden host susceptibility:** individual susceptibility к current strain может отличаться от общей физической «здоровости»; она не обязана быть прямо видимым stat.
60. **Exposure accumulation:** несколько low-dose exposures могут вместе повышать риск, но не моделируются как простая видимая `immunity HP` bar; exact window/dose math deferred.
61. **Ordinary disease interaction:** обычная болезнь может маскировать симптомы и для некоторых штаммов изменять acquisition/course в любую сторону; universal cold/immunity modifier не принимается.
62. **Vector counterplay required before commitment:** если mosquito/vector transmission входит в конкретный ран, он не должен быть невидимым uncontrollable random punishment; exact room protection/vector-pressure model остаётся implementation/balance work.
63. **Direct raid control:** на самой raid site игрок должен иметь возможность буквально управлять небольшим отрядом; strategic planning до/после операции сохраняется.
64. **Shared tactical language:** raid squad и base response team используют по возможности один набор пространственных команд, чтобы raid не превращался во вторую несвязанную игру.
65. **Unexplored facility space:** known/operational base остаётся читаемой, но неосвоенные тёмные/закрытые части здания могут быть physically unverified и требовать разведки.
66. **Alarm as incomplete report:** тревога может быть поднята свидетелем/охранником/жителем по звуку, движению, разбитому окну, неизвестной фигуре и т.п.; exact threat может оставаться UNKNOWN до проверки.
67. **Emergency plans:** сектор может иметь заранее подготовленный evacuation/shelter/security plan и резервный маршрут; rehearsal/drill является отдельной preparedness investment.
68. **Shelter vs evacuation:** правильная реакция не универсальна. Fresh infected в коридоре может сделать массовую эвакуацию опаснее, чем `shelter in place`.
69. **Room/sector emergency commands:** player needs rapid actions to evacuate, hold, seal, subdivide or reopen a route without manually clicking every door/person.
70. **Seal is physical:** `Seal sector` закрывает реально closable boundaries and available shutters/doors; damaged/open/missing barriers remain failure points.
71. **Threat-source breadth:** alarms/penetration can come from infected humans, retained-function variants, infected animals/rodents/birds, insect/vector events or human raiders; exact frequency/content remains scenario/balance work.


---

# 3. Working item index

| ID | Semantic item | State |
|---|---|---|
| `CHAT-PI-001` | База выживших, управляемая через сдерживание заражения | accepted |
| `CHAT-PI-002` | Производство против карантина | accepted core |
| `CHAT-PI-003` | Распределение населения по биологическому и операционному риску | accepted |
| `CHAT-PI-004` | Защищённое чистое ядро базы | accepted |
| `CHAT-PI-005` | Планировка базы с учётом распространения и локализации заражения | accepted |
| `CHAT-PI-006` | Подготовка, потеря, блокировка и зачистка сектора | accepted |
| `CHAT-PI-007` | Рейды за ресурсами, выжившими и контакт с внешними группами | accepted direction / tactical depth open |
| `CHAT-PI-008` | Нападения на базу | scope unresolved |
| `CHAT-PI-009` | Лёгкая архитектура Planning Draft | accepted meta |
| `CHAT-PI-010` | Открытые решения базового концепта | living backlog |
| `CHAT-PI-011` | Личность, потребности и ограниченная рациональность | accepted |
| `CHAT-PI-012` | Внутренняя безопасность и исполнение правил | accepted |
| `CHAT-PI-013` | Иерархия безопасности, справедливость и внутренний конфликт | accepted |
| `CHAT-PI-014` | Небинарное течение заражения, устойчивость и постинфекционные состояния | accepted |
| `CHAT-PI-015` | Наблюдение, отчётность и производство информации о риске | accepted |
| `CHAT-PI-016` | Носители как отдельный класс населения и рабочей силы | accepted |
| `CHAT-PI-017` | Настраиваемые правила и политики для категорий населения | accepted |
| `CHAT-PI-018` | Распространение информации между жителями и организационная связь | accepted / command-latency removed for demo |
| `CHAT-PI-019` | Внешние группы выживших и давление на приём | accepted |
| `CHAT-PI-020` | Принуждение, правосудие и необратимые решения о людях | accepted |
| `CHAT-PI-021` | Модель знаний о болезни, гипотез и достоверности | accepted |
| `CHAT-PI-022` | Изучение вируса, эксперименты и разработка лечения | accepted |
| `CHAT-PI-023` | Архитектурный surveillance visual direction | preliminary accepted |
| `CHAT-PI-024` | Производство и физическое поддержание базы | accepted |
| `CHAT-PI-025` | Питание, приготовление и санитарный риск | accepted |
| `CHAT-PI-026` | Вода, гигиена, санитария и стирка | accepted |
| `CHAT-PI-027` | Электричество, топливо, отопление и температура | accepted |
| `CHAT-PI-028` | Одежда, текстиль, износ и замена | accepted |
| `CHAT-PI-029` | Частная собственность и личные вещи как санитарная и социальная граница | accepted / updated |
| `CHAT-PI-030` | Чистота предметов, риск и обеззараживание | accepted |
| `CHAT-PI-031` | Санитарное разделение производства против эффективности | accepted |
| `CHAT-PI-032` | Физическая логистика, переносчики и контролируемые маршруты | accepted |
| `CHAT-PI-033` | Ответственные, производственные руководители и учёт | accepted |
| `CHAT-PI-034` | Характеристики, навыки и предметный опыт | accepted |
| `CHAT-PI-035` | Индивидуальное знание, неизвестность, публичный статус и слухи | accepted |
| `CHAT-PI-036` | Прозрачное пространство и постепенно узнаваемые люди | preliminary accepted direction |
| `CHAT-PI-037` | Радикальный physical vision через камеры и доверенных наблюдателей | alternative / deferred |
| `CHAT-PI-038` | Досье на людей, доверие и human intelligence | accepted / new |
| `CHAT-PI-039` | Внутренняя торговля и регулируемый обмен частной собственностью | accepted as decision candidate / new |
| `CHAT-PI-040` | Подготовка рана: trusted core, generated population и качество старта | preliminary accepted |
| `CHAT-PI-041` | Стартовое здание демки и происхождение чистого ядра | preliminary accepted demo direction |
| `CHAT-PI-042` | Command Circle: верхний уровень руководства и общий управленческий контур | preliminary accepted concept |
| `CHAT-PI-043` | Вооружённая сила, лояльность и основания подчинения | accepted design line |
| `CHAT-PI-044` | Внешний мир: глобальная карта, экспедиции и меняющееся zombie pressure | decision candidate |
| `CHAT-PI-045` | Прогресс рана и глобальная цель | decision candidate / partially formed |
| `CHAT-PI-046` | Личные цели и future stakes персонажей | accepted direction |
| `CHAT-PI-047` | Локальные capability-goals и временное давление opening phase | preliminary accepted demo direction |
| `CHAT-PI-048` | Санитарная служба, загрязнение пространства и временные закрытия | accepted design line |
| `CHAT-PI-049` | Настраиваемые шлюзы, intake и принятие решений о переходе | accepted design direction |
| `CHAT-PI-050` | Охранные посты, checkpoint enforcement, patrol и escort | accepted design direction |
| `CHAT-PI-051` | Fresh / conserved / special infected, бой и формирование орды | accepted design direction |
| `CHAT-PI-052` | Экология заражения, энергетика и animal hosts | accepted baseline direction / strain details open |
| `CHAT-PI-053` | Животноводство, мясо и санитарный контур животных | accepted production candidate |
| `CHAT-PI-054` | Прямое тактическое управление raid/response squad | accepted design direction |
| `CHAT-PI-055` | Физическая разведка неисследованных частей здания | preliminary accepted direction |
| `CHAT-PI-056` | Тревоги, аварийные планы и тренировки | accepted design direction |
| `CHAT-PI-057` | Быстрые emergency-команды комнаты/сектора | accepted design direction |

---

# 4. Core Planning Items

## `CHAT-PI-001` — База выживших, управляемая через сдерживание заражения

**Категории:** `CAT-01`, `CAT-08`

Игра — менеджмент колонии/группы/лаборатории/базы выживших, где люди работают, строят и поддерживают инфраструктуру, но каждый человек потенциально может быть источником заражения. Центральная ответственность игрока — сохранить функционирующее сообщество, а не просто максимизировать производство.

Точная оболочка — больница, лаборатория, укреплённая база, подземный комплекс или другой вариант — пока не выбрана.

## `CHAT-PI-002` — Производство против карантина

**Категории:** `CAT-01`, `CAT-02`, `CAT-03`, `CAT-04`, `CAT-05`, `CAT-10`

Игрок не может при малейшем подозрении выключать человека из жизни базы без цены. Карантин снижает риск, но отнимает рабочие руки, пространство, охрану, снабжение и иногда единственного нужного специалиста. Допуск подозрительного человека сохраняет критическую функцию, но создаёт потенциальную цепочку заражения.

Повторяющаяся ставка: **«без этого человека остановится нужная система; если он заражён, я могу потерять весь сектор»**. Между полной свободой и полной изоляцией должны существовать промежуточные режимы: ограниченная работа, отдельная рабочая группа, специальный маршрут, наблюдение, временный допуск.

## `CHAT-PI-003` — Распределение населения по биологическому и операционному риску

**Категории:** `CAT-02`, `CAT-03`, `CAT-04`, `CAT-06`, `CAT-10`

Население распределяется не бинарно «чистый / карантин», а относительно работы, людей, помещений, биологического статуса и допустимого уровня риска. Подозреваемый может работать внутри ограниченного контура; носитель может быть опасен для чистых людей, но полезнее в грязной зоне; отдельный специалист может получить исключение, которого нет у остальных.

Риск-категория влияет на доступ, маршруты, разрешённые работы, снабжение, средства защиты и наблюдение.

## `CHAT-PI-004` — Защищённое чистое ядро базы

**Категории:** `CAT-03`, `CAT-04`, `CAT-10`

На базе существуют люди и помещения, заражение которых недопустимо или имеет особенно тяжёлые последствия. Они не должны свободно контактировать с более рискованными группами, включая полезных носителей.

Состав ядра может включать лабораторию, критических специалистов, медицинское производство, командование, детей или резервные ресурсы — точный состав остаётся сценарием/балансом. Ядро не должно быть полностью автономным: оно зависит от внешнего труда, снабжения и инфраструктуры.

Люди, долго находящиеся рядом с центром управления, естественно могут быть **лучше известны руководству**: с ними чаще общаются, их чаще наблюдают доверенные лица и по ним больше подтверждённой истории. Это не делает их автоматически лояльными, но повышает confidence в профиле. Перевод плохо изученного человека ближе к чистому ядру поэтому одновременно является наградой, способом лучше его узнать и риском допуска неизвестного человека к наиболее ценным зонам.

Для первой демки clean core **не возникает из пустоты**: small trusted group уже удерживает и контролирует небольшой блок здания до начала игрового времени. Их recent contact history хорошо известна, поэтому у игрока есть реальное основание считать их исходно безопаснее новых людей. Дальнейшее расширение чистой территории должно опираться на фактическое очищение/проверку пространства, контроль доступа, историю людей и правила переноса предметов, а не на простое назначение зелёного цвета.

## `CHAT-PI-005` — Планировка базы с учётом распространения и локализации заражения

**Категории:** `CAT-02`, `CAT-03`, `CAT-04`, `CAT-06`, `CAT-09`, `CAT-10`

Ключевые помещения и связи размещаются так, чтобы заражение можно было локализовать. Игрок заранее проектирует возможность закрыть сектор, эвакуировать людей, удержать угрозу, сохранить альтернативные маршруты и позднее вернуть помещение.

Геометрия имеет trade-off: узкий/сложный проход может лучше сдерживать толпу, но ухудшить эвакуацию и логистику. Серьёзная дверь может быть надёжнее, но дорога. Производственная эффективность и санитарная устойчивость не всегда совпадают.

Строительство должно выражать эпидемиологическую архитектуру, а не быть декоративным «построй ещё комнату».

Архитектура также должна поддерживать **аварийные сценарии**. У сектора могут быть основной и резервный evacuation routes, места shelter/refuge, границы для быстрого seal и точки, которые охрана занимает при тревоге. Игрок проектирует не только обычный поток людей, но и то, куда они побегут/где останутся при нарушении containment.

Важность альтернативных маршрутов проявляется не только при вспышке. Коридор может временно закрываться из-за крови, трупа, санитарной обработки или работы бригады; в это время второй путь сохраняет логистику. Позднее несколько входов/выходов здания тоже могут становиться отдельными failure domains: один вход блокирует заражённая масса, другой остаётся доступен для рейда или аварийного приёма.

Внешний containment не должен сводиться к одной «бесконечной» главной двери. Плотная масса может **обтекать фасад и постепенно лишать игрока внешней оболочки здания**: занимать двор, блокировать alternate/service entrances, подходить к окнам, наружным лестницам и техническим путям. Некоторые strain/variant candidates способны карабкаться, формировать вертикальную кучу или нарушать грунт у ограждения. Игрок поэтому проектирует несколько слоёв, запасные маршруты и участки, которые можно временно потерять.

**Air network сейчас deferred.**

## `CHAT-PI-006` — Подготовка, потеря, блокировка и зачистка сектора

**Категории:** `CAT-02`, `CAT-03`, `CAT-04`, `CAT-05`, `CAT-06`, `CAT-07`, `CAT-09`, `CAT-10`

Вспышка может сделать часть здания временно потерянной. Возможность успешно её закрыть зависит от старых решений: дверей, проходов, охраны, эвакуационных маршрутов, независимости снабжения и размещения людей.

При закрытии игрок может сознательно оставить живых внутри ради сохранения остальной базы. Внутри могут остаться люди, ресурсы, оборудование и критическая инфраструктура. Позже сектор можно ждать, обходить, снабжать через границу, частично эвакуировать или возвращать.

Возврат должен быть не только «убить зомби», а восстановлением пространства и доверия к нему. База накапливает шрамы и может продолжать работу с навсегда потерянными блоками.

Fresh outbreak внутри здания может развиваться быстрее внешней осады. Обычная спальня/мастерская с лёгкой дверью — **не bunker**, а кратковременное укрытие. Prepared refuge point может иметь более прочный переход, связь, минимум воды/средств и альтернативный путь. Предпочтительный feedback — не абстрактный `door HP`, а состояние вроде `SECURE / UNDER ASSAULT / FASTENING FAILING / BREACH IMMINENT`.

Containment должен работать и как **оперативное действие**. Если точная угроза находится в одной комнате, игрок может локально `lock/seal room`. Если источник неясен или гуляет по нескольким комнатам, нужен более грубый `Seal sector`, который пытается закрыть все доступные границы сектора. Это может сознательно оставить людей внутри и поэтому является тяжёлым, но быстрым кризисным решением.

В first-demo scenario часть этого смысла присутствует **с нулевой минуты**: одно небольшое крыло может быть заранее потеряно/запечатано, содержать ограниченное количество заражённых и не представлять немедленного риска прорыва. Рядом могут существовать уже пустые, но грязные/непроверенные коридоры. Это даёт игроку безопасно читаемый пример разницы между usable clean space, dirty/unverified space и actively lost space ещё до первой новой вспышки.

## `CHAT-PI-007` — Рейды за ресурсами, выжившими и контакт с внешними группами

**Категории:** `CAT-02`, `CAT-04`, `CAT-07`, `CAT-10`

Рейды могут приносить еду, топливо, лекарства, инструменты, одежду, оборудование, образцы и новых людей. Возвращение превращается в интеграционную проблему: кого и куда допустить, что считать грязным грузом, можно ли использовать срочно нужную вещь до полной обработки.

Во внешнем мире рейд может встречать другие группы людей — чистых, носителей, заражённых и смешанные группы — которые конкурируют, торгуют, мешают или становятся будущей угрозой.

Current preferred raid structure теперь **двухслойный**.

На стратегическом уровне игрок выбирает:
- людей;
- оружие/защиту;
- груз и capacity;
- маршрут;
- цель;
- допустимый риск;
- время выхода/возврата.

Но на **raid site** игрок может буквально управлять небольшим отрядом. Это нужно, потому что правильно организованная база часто должна предотвращать бой; если внешние операции остаются только текстовыми/автоматическими, всей игре может не хватать концентрированных combat/uncertainty situations.

Direct control не означает отдельный shooter/RTS с микроконтролем каждого выстрела. Preferred language:
- move/hold position;
- cover/watch doorway;
- open/close/breach;
- use light / investigate darkness;
- make noise / lure;
- engage / avoid;
- retreat to point;
- carry/drag person or critical loot;
- choose contaminated/safer path.

Этот же command language должен переиспользоваться у base response squad (`CHAT-PI-054`), чтобы рейд был продолжением core spatial-management game, а не второй игрой.

Возвращение «своих» не отменяет санитарные правила: рейдеры были во внешней среде, могли драться, контактировать с кровью и неизвестными людьми, поэтому возвращаются через тот же общий transition/intake logic (`CHAT-PI-049`). Но социально это другой случай: незнакомцу можно отказать во входе, а человека, которого руководство само отправило в рейд, гораздо труднее просто оставить снаружи. Возможен промежуточный вариант — `deny internal access` и удержание в perimeter/holding до проверки.

## `CHAT-PI-008` — Нападения на базу

**Категории:** `CAT-02`, `CAT-05`, `CAT-07`, `CAT-10`

На базу могут нападать внешние силы, включая людей, которым ранее отказали во входе. Сильная функция нападения — не отдельная RTS, а разрушение карантинной архитектуры: необходимость открыть аварийный проход, снять охрану с КПП, смешать раненых, отключить производство, перебросить электричество и нарушить собственные правила.

## `CHAT-PI-009` — Лёгкая архитектура Planning Draft

Planning Items являются semantic owners, категории — multi-label навигацией. Implementation Ideas хранятся отдельно от requirements. План должен оставаться проще самой игры и позже может разойтись по специализированным design docs.

## `CHAT-PI-010` — Открытые решения базового концепта

**Категории:** multi-category backlog

Крупные вопросы:

- точный сеттинг и масштаб базы;
- временная модель и настоящий moment-to-moment loop;
- точный demo-run после уже принятой стартовой фазы и victory/failure;
- строительная сетка и степень физической симуляции;
- точные пути заражения и тесты;
- глубина рейдов/нападений;
- стоит ли когда-либо уходить от current transparent-space baseline к `PI-037` physical-vision model;
- различие между знанием игрока, лидера и конкретных людей;
- точный состав Command Circle, player-fiction и последствия смерти/раскола высшего руководства;
- полный production scope;
- реалистичный источник/очистка воды;
- финальный набор attributes / domain skills;
- CPU/UX граница information simulation;
- visual reference research;
- market/comparable research.

- точная стартовая population density и budget formula;
- насколько процедурным должен быть full-game scenario / surrounding map;
- внешняя биология заражённых и пределы их активности;
- метрики/механика institutional trust и patronage;
- точная глобальная цель кампании/рана;
- глубина personal future goals.
- exact first-demo intake layout: быстрый поток, specialist bays, holding и несколько выходов;
- exact sanitation consumables/realism и сколько времени помещение считается недоступным после загрязнения;
- нужно ли убийство заражённого в голову, и как shooting skill должен менять doctrine;
- насколько точным может становиться terminal-course prediction, не разрушая драму covert execution;
- допустимый уровень шума/attention model для мигрирующей массы;
- exact demo map footprint: одно крупное здание + двор/подходы versus несколько зданий;
- exact fresh-infected speed/endurance, feeding and short-term recovery;
- exact horde attraction/aggregation/dissipation model;
- какие climbing/piling/burrowing/tool-use behaviours являются baseline, strain traits или rare variants;
- exact role of windows/fences/interior doors without generic HP bars;
- насколько далеко кровь/биоматериал создают secondary contaminated area и когда relevant insects/mechanical vectors;
- exact animal host baseline versus current-strain discovery;
- какие species способны быть long-lived reservoir / animal→human bridge;
- насколько быстро herbivore/wildlife population реально восстанавливается после человеческого коллапса;
- exact rabbit/livestock scope and whether it belongs in first demo;
- exact first-demo water-service condition after infrastructure collapse;
- exact direct-tactical raid depth, squad size, pausing/time model and how much aiming/shooting is abstracted;
- how travel/global-map phase transitions into raid-site tactical space;
- exact local vision/hearing rules in physically unexplored/dark parts of the facility;
- how much scenario topology is known from old plans versus discovered physically;
- exact alarm propagation, who can raise/confirm/cancel it and how partial reports are shown;
- emergency-plan UI and how rehearsal/drills change execution without becoming routine busywork;
- exact semantics of room lock / shelter in place / sector seal / evacuation route A/B / all clear;
- which doors/shutters are remotely controllable versus require a person to reach them;
- how attacks by raiders/animals/vectors use the same alarm/emergency framework without becoming event spam.

Полный покадровый demo scenario всё ещё deferred, но **нулевая ситуация и opening phase теперь имеют preliminary direction**.

## `CHAT-PI-011` — Личность, потребности и ограниченная рациональность

**Категории:** `CAT-01`, `CAT-03`, `CAT-05`, `CAT-07`, `CAT-10`

Жители — не полностью послушные пешки. У них есть потребности, привязанности, страх, стресс, рассудок, отношение к риску и другим людям. Минимальный working set: еда, вода, сон, стресс/психическое состояние, социальный контакт и восстановление/досуг.

Люди могут нарушать правила из понятных причин: пойти к другу, искать родственника, скрыть симптом, отказаться от опасной работы, сорваться из-за страха или несправедливости. Болезнь может менять агрессивность, потребности и рациональность.

Социальные отношения строятся на разговорах, совместном опыте, личных чертах и памяти о действиях. Для прототипа допустима временная RimWorld-like mood/social baseline. Личностные черты должны по возможности образовывать правдоподобный профиль, а не случайный набор независимых бонусов.

В current knowledge direction **истинная personality может быть глубже, чем то, что знает игрок**, но поведение не должно становиться необъяснимым. Базовые потребности и явные состояния — голод, недосып, видимая усталость, сильный стресс, родство, очевидный конфликт — должны быть достаточно читаемы. Более глубокие качества вроде дисциплины, злопамятности, склонности к риску, скрытой враждебности или лояльности могут постепенно подтверждаться наблюдениями и источниками.

Досуг тоже должен учитывать карантинную дистанцию и правила. В opening phase он не должен конкурировать по вниманию с базовым приёмом, едой, сном и безопасностью; достаточно дешёвых sector-local activities вроде разговоров, книг/радио, карт/настольных игр. Более общие gatherings могут позднее становиться social benefit ценой большего количества контактов.

Кроме текущих needs у человека может быть **future stake** — то, чего он ждёт или к чему стремится. Такая цель не заменяет personality, а даёт конкретную причину для решений, лояльности, сделок и конфликтов; owner — `CHAT-PI-046`.

## `CHAT-PI-012` — Внутренняя безопасность и исполнение правил

**Категории:** `CAT-03`, `CAT-04`, `CAT-05`, `CAT-06`, `CAT-10`

Зоны и правила не исполняются автоматически. Нужны КПП, охрана, проверки, сопровождение, закрытые двери, наблюдение и реакция на нарушения.

Охрана нужна не только против внешних атак: она предотвращает самовольные посещения чужих жилых пространств, защищает личные вещи, следит за карантином, удерживает закрытый сектор и контролирует переходы.

Исполнение имеет два слоя: добровольное соблюдение известного правила и enforcement. Не каждый коридор обязан иметь охранника, но каждый санитарно значимый переход должен иметь понятный механизм контроля.

Вооружённый security personnel не обязан санитарно принадлежать к clean core. Для дизайна нужно различать как минимум четыре оси: **sanitary status, authority, trust, force**. Человек может иметь автомат и охранять внешний периметр, но не иметь доступа в зелёное жилое ядро; наоборот, чистый специалист внутри core может не иметь никакой силовой власти. Выдача оружия сама по себе является решением о доверии и распределении реальной силы.

Security должен быть управляем не только профессией, но и **пространственными приказами**: checkpoint на границе зон, свободный guard post, patrol, escort и резерв/реакция. Detailed owner — `CHAT-PI-050`. Нормальный человек может добровольно соблюдать временный санитарный знак без охранника; armed enforcement нужен там, где риск/конфликт оправдывают manpower.

При alarm/security incident охрана не должна ждать ручного приказа на каждого человека. Prepared emergency plan может заранее назначать response position, reserve route, protected door, retreat point и сектор, в который охрана не входит без дополнительного confirmation. Игрок может override plan в реальном времени.

## `CHAT-PI-013` — Иерархия безопасности, справедливость и внутренний конфликт

**Категории:** `CAT-01`, `CAT-03`, `CAT-04`, `CAT-05`, `CAT-07`, `CAT-10`

Неравный доступ к безопасности создаёт политическую структуру. Люди в защищённой зоне имеют меньше риска, а пограничные/грязные группы могут требовать перевода, отказываться работать, протестовать, саботировать или пытаться захватить безопасное пространство.

Политические группы могут формироваться и по биологическому статусу: носители, устойчивые, обычные чистые и редкие иммунные могут видеть свои интересы по-разному.

Иерархия может строиться не только вокруг санитарной безопасности, но и вокруг **оружия, должности и доступа к привилегиям**. Доверие к власти и основания лояльности охраны поэтому становятся самостоятельной политической линией (`CHAT-PI-043`). Возможны разные trajectories общества — от patronage/police structure до более institutional order — но это пока не фиксированные режимы и не выбор в меню.

Для first-demo starting fiction естественна ещё одна исходная групповая граница: **те, кто уже находился в убежище, и те, кто только прибыл**. Это не обязано становиться permanent faction system. Первые дают лечение, одежду, еду, защищённое пространство; прибывшие дают рабочие руки, специалистов, охрану и сведения о внешнем мире. Взаимопомощь может постепенно размывать исходную идентичность, а неравное обращение — наоборот, превращать её в устойчивую политическую линию.

## `CHAT-PI-014` — Небинарное течение заражения, устойчивость и постинфекционные состояния

**Категории:** `CAT-04`, `CAT-05`, `CAT-06`, `CAT-07`, `CAT-10`

Человек может умереть, превратиться, выздороветь, остаться носителем, получить временную/длительную устойчивость или позже заболеть снова.

Носительство может давать бафы и дебафы. Устойчивость к заражённой среде и защита от укуса не обязаны совпадать: укус может быть высокой вирусной дозой. Настоящий иммунитет к укусу может быть крайне редким.

Во время болезни могут меняться агрессивность, потребность в контакте/еде/воде, внешний вид, работоспособность и рациональность. Профиль штамма может меняться между ранами.

Отдельный disease-course candidate: **прямое заражение большой дозой** — укус или попадание заражённой крови непосредственно в рану — может означать особенно высокий риск, меньший шанс благоприятного исхода и более быстрое превращение. Оно не обязано быть мгновенным. Для отдельного штамма возможна тревожная фаза, где вирус временно поддерживает/стимулирует энергию сильно изношенного организма, поэтому человек выглядит менее больным, чем ожидается, почти до резкого ухудшения. Это hypothesis, не универсальный закон инфекции.

`10–15%` носителей — только балансировочная гипотеза.

Для physical threat важно различать stage after turning. **Fresh infected** ещё физически сохранны, способны быстро двигаться/рывками сокращать дистанцию и создавать короткий очень опасный crisis window. **Old/conserved infected** истощены, чаще находятся в low-activity state и обычно слабее индивидуально, но опасны количеством и осадой. Это continuum/strain-dependent behaviour, не обязательные RPG-классы.

До turning infection risk тоже не обязан быть одной видимой шкалой. Useful hidden decomposition:
- **baseline susceptibility to current strain** — индивидуальная восприимчивость именно к этой инфекции;
- **current resilience** — сон, питание, тяжёлая concurrent illness, травма, истощение и другие временные состояния;
- **specific protection** — результат перенесённой инфекции/профилактики/лечения, если current strain это допускает;
- **exposure dose/history** — путь и накопленная недавняя экспозиция.

Два внешне одинаково здоровых человека therefore могут по-разному пережить одинаковый exposure. Это не должно превращаться в невидимый произвольный `immunity = 63/100`: игрок работает через evidence, историю контактов, состояние человека и статистику.

Обычные болезни существуют независимо от main infection и полезны как diagnostic noise: температура, кашель, слабость, диарея, воспалённая рана и т.п. могут иметь другую причину. Их interaction с current strain может зависеть от штамма и быть harmful, protective или нейтральным; универсальное правило `простуда снижает иммунитет на X` не принимается.

## `CHAT-PI-015` — Наблюдение, отчётность и производство информации о риске

**Категории:** `CAT-03`, `CAT-04`, `CAT-06`, `CAT-10`

Истинный infection state не показывается автоматически. Сигналы появляются через симптомы, потребление, работоспособность, поведение, контакты и перемещения.

Наблюдение производят врачи, учёные, специальные надсмотрщики, охрана и рабочая организация. Руководитель мастерской может первым заметить, что хороший работник стал медленнее, ошибается или выглядит необычно.

Наблюдение теперь производит не только infection evidence, но и **personnel evidence**: как человек работает, ведёт себя под давлением, соблюдает правила, с кем конфликтует, какие качества проявляет. Разные источники видят разные типы информации и могут ошибаться, скрывать или интерпретировать одно и то же событие по-разному.

Учёт требует людей и времени. Infection data становятся input для `CHAT-PI-021`, а observations about people — для `CHAT-PI-038`.

Для первой демки отдельная полезная форма evidence — **contact/activity journal**. Для исходного trusted core он может содержать практически полную сценарную историю последних дней: где человек находился, с кем имел близкие контакты, выходил ли наружу, использовал ли защитный костюм, проходил ли обработку. Эта история является основанием стартовой санитарной уверенности; для новых людей данные заметно хуже.

Infection evidence тоже различается по качеству. Примеры:
- случайный рассказ/воспоминание свидетеля;
- полевое наблюдение с понятным наблюдателем;
- camera/recorded behaviour;
- медицинский осмотр/образец;
- controlled experiment;
- repeated experiment / control comparison.

Если игрок визуально увидел, как infected human поймал кролика, это может породить вопрос `rabbit avoidance reduced?`, но само по себе не обязано давать high-confidence fact: кролик мог быть ранен, загнан или повести себя случайно. Хорошая запись, повторяемость и controlled test уменьшают альтернативные объяснения.

## `CHAT-PI-016` — Носители как отдельный класс населения и рабочей силы

**Категории:** `CAT-02`, `CAT-03`, `CAT-04`, `CAT-05`, `CAT-07`, `CAT-10`

Носитель может безопаснее обычного работать в заражённой среде, участвовать в зачистке и требовать меньше защиты, но остаётся опасен для чистых. Он нуждается в собственном размещении, маршрутах, правилах, снабжении и коммуникации.

Это отдельный экономический и политический класс, а не просто medical status.

Recovered people не должны автоматически быть вечными носителями, иначе рациональная политика станет слишком простой. Возможны различия `recovered/cleared`, `persistent carrier`, `intermittent shedder`; последний особенно опасен тем, что fresh outbreak может возникнуть уже среди давно интегрированных людей. Точные состояния и вероятности принадлежат current strain/discovery.

## `CHAT-PI-017` — Настраиваемые правила и политики для категорий населения

**Категории:** `CAT-02`, `CAT-03`, `CAT-04`, `CAT-06`, `CAT-10`

Игрок создаёт правила для людей, категорий и зон: доступ, дистанция, маршрут, рацион, препараты, обязательные осмотры, разрешённые склады, использование чужих вещей, требования к decon, допустимые условия нахождения в риск-зоне.

Политики могут распространяться и на **обмен частной собственностью**: разрешено ли передавать предмет между категориями/зонами, требуется ли регистрация или санитарная обработка, допускается ли односторонний поток. Например, чистая вещь может быть передана из более защищённой зоны вниз по иерархии, но после использования в рискованном секторе её возврат в зелёную зону может быть запрещён без decon.

Правило может исполняться самим человеком или enforcement-системой.

Политики могут **опираться на** current evidence/scientific assessment, но пока не должны автоматически переписываться при изменении рабочей теории. Игрок способен ввести precautionary rule при слабом evidence, игнорировать рекомендацию специалистов или оставить прежнюю практику несмотря на новые данные.

Рабочая decision context лучше считать так:
`категория человека + предмет/зона + известные exposures + действующая policy + доступное evidence → решение/исполнение`.
Научное состояние помогает оценивать риск и обоснованность, но не является скрытым policy compiler.

На старте сценарий должен иметь **разумные default policies**, чтобы игрок не настраивал каждую мелочь с нулевой минуты. First meaningful edit лучше поднимать контекстно, когда default впервые мешает полезному решению.

Рабочие policy areas для интерфейса:
- **Access** — кто может входить, нужен ли escort;
- **Transition** — какие проверки/мытьё/смена одежды требуются;
- **Contact** — дистанция, посещения, gatherings;
- **Items** — что можно переносить и как обрабатывать;
- **Medical** — осмотр, symptom reporting, tests, плановые проверки после exposure;
- **Weapons** — можно ли носить, требуется ли check/search;
- **Food** — где брать/есть;
- **Personal** — жильё, личные вещи, посещение чужих помещений.

Transition policy исполняется через configurable шлюзы/пункты проверки (`CHAT-PI-049`), а enforcement может быть связан с boundary checkpoint (`CHAT-PI-050`).

## `CHAT-PI-018` — Распространение информации между жителями и организационная связь

**Категории:** `CAT-02`, `CAT-03`, `CAT-04`, `CAT-06`, `CAT-07`, `CAT-10`

Обычная информация внутри мира не появляется мгновенно у всех жителей. Новости, официальные объявления, сведения о смерти/карантине, слухи, предупреждения и локальные события распространяются через наблюдение, разговоры, руководителей, записи, радио, телефоны и другие каналы.

Для **первой демки player commands исключаются из этой transmission model**. Игрок отдаёт приказы через colony-sim UI без искусственной задержки доставки. Физическое выполнение всё ещё требует времени, маршрута и доступности пешки; человек может нарушить правило или отказаться по причинам, принадлежащим simulation/personality systems.

Связь остаётся значимой для самих жителей: она влияет на то, кто знает о событии, насколько быстро распространяется официальная версия, насколько быстро появляются слухи и насколько согласованно могут действовать группы без прямого социального контакта.

Идеи ограниченных раций, телефонов, гонцов и автономного поведения при потере связи сохраняются как будущие Implementation Ideas, но не являются обязательной транспортной системой команд игрока в первой демке.

Это решение относится прежде всего к **управлению собственной базой**. После перехода к direct tactical raid control игрок также может управлять squad на raid site без искусственной command-latency как интерфейсной абстракцией. Ограниченная связь/autonomy всё ещё естественна для travel/off-map events, detached teams или future harder modes, но больше не является обязательным форматом самой raid encounter.


## `CHAT-PI-019` — Внешние группы выживших и давление на приём

**Категории:** `CAT-01`, `CAT-02`, `CAT-03`, `CAT-05`, `CAT-07`, `CAT-10`

Снаружи существуют группы людей с неизвестным смешанным biological state. Игрок может принять, отказать, удерживать снаружи, тестировать, торговать или разделить их. Отказ может породить будущую агрессивную группу; приём создаёт нагрузку на карантин, питание и политику.

`Не впустить` сохраняется как полноценное решение, а не только failed check. Человек может уйти, просить впустить ребёнка, отказаться уходить, упасть у ворот или опереться на свою группу. Вооружённые среди прибывших требуют переговоров: оружие можно оставить во внешнем/опечатанном storage, разрешить только во внешнем секторе или временно использовать человека как perimeter guard. У группы не должно быть автоматического силового перевеса над уже укрепившейся базой, но и бесплатное разоружение не предполагается.

При непосредственной внешней угрозе возможен **emergency admit**: быстро запустить людей в защищённый dirty holding, не признавая их безопасными. Это спасает их от улицы, но смешивает людей разного риска и делает последующий отказ/силовое удаление значительно опаснее внутри периметра.

## `CHAT-PI-020` — Принуждение, правосудие и необратимые решения о людях

**Категории:** `CAT-01`, `CAT-03`, `CAT-04`, `CAT-05`, `CAT-07`, `CAT-10`

Игрок может принять крайнее решение о потенциально заражённом или проблемном человеке, включая убийство. Это часть линии: предупреждение → ограничение → арест/изоляция → наказание → изгнание → применение силы → казнь.

Приказы выполняют конкретные охранники/солдаты/палачи с собственной психикой и историей. Информация о применённой силе может скрываться, распространяться и менять отношение к власти.

Даже в мире, где человеческая жизнь может стоить дёшево, **избавиться от проблемного человека не обязательно дёшево**. Его убийство/изгнание может означать потерю редкого навыка, разрушение производственной цепочки, конфликт с друзьями/родственниками, политические последствия и потерю уже накопленного доверия и знания о человеке. Хорошо изученный и проверенный посредственный специалист иногда ценнее неизвестного потенциального гения.

Нужно **не потерять знаковую ситуацию тайной казни**. Человека можно незаметно вывести под предлогом перевода/лечения в закрытый блок, ограничить свидетелей доверенными исполнителями, убить и затем поддерживать неполную или ложную официальную версию его судьбы. Это не stealth-action, а information/social situation: кто видел маршрут, кто слышал выстрел, кто знает правду, кто ждёт возвращения человека и кто позднее может раскрыть историю.

Ожидать исход заражения часто выгодно: человек может выздороветь, стать носителем/устойчивым, сохранить редкий skill или стать ценным research subject. Но ожидание должно стоить isolation space, койки/фиксации, еды/воды, наблюдения, санитарной работы, риска персоналу и последующей очистки помещения. Дополнительный мотив для ранней казни появляется, когда disease knowledge показывает **очень вероятный terminal course**, особенно после high-dose exposure. При этом knowledge должна скорее давать confidence/evidence, чем абсолютное `TERMINAL=true`.

Сохраняется открытый design conflict: возможно, **незнание о том, мог человек пережить болезнь или нет, делает covert-execution сцену сильнее**, а слишком точное terminal prediction превращает её в простую утилизацию. Это нужно проверить отдельно.

## `CHAT-PI-021` — Модель знаний о болезни, гипотез и достоверности

**Категории:** `CAT-02`, `CAT-03`, `CAT-04`, `CAT-06`, `CAT-07`, `CAT-10`

Истинные свойства вируса существуют независимо от знания базы. Disease knowledge должно чётко различать несколько слоёв:

1. **Evidence / наблюдения** — что реально было замечено, измерено, записано или получено в эксперименте; с source, quality и условиями.
2. **Scientific assessment** — что компетентные врачи/учёные считают наиболее вероятным исходя из доступного evidence.
3. **Leadership assumption / working position** — что руководство решило считать возможным/достаточно опасным для конкретного решения, если вообще хочет это отдельно формулировать.
4. **Policy / action** — что база фактически делает.

Игрок **не обязан вручную угадывать правильную научную теорию**. При достаточном evidence специалисты сами способны формировать вероятностный professional assessment. Одновременно руководство может действовать при слабых данных, из precaution, по ошибочному предположению или вопреки consensus.

На текущем этапе **нет автоматической связи `adopt theory → rewrite all related policies/buildings`**. Working assumption может быть записанной позицией/обоснованием, но политика остаётся самостоятельным приказом. Это позволяет сравнивать:
`что знали → что считали вероятным → что приказало руководство → что произошло`.

Scientific disagreement становится социально значимым. Если руководство уничтожает животных, ограничивает людей или применяет тяжёлую меру без достаточного доступного evidence, врачи/учёные могут считать решение unsupported/excessive, обсуждать это с другими и влиять на procedural trust. Обратная ситуация тоже возможна: меры могут быть хорошо обоснованы, но всё равно непопулярны.

По мере накопления наблюдений/анализов база может научиться распознавать **вероятные траектории болезни**, включая признаки, после которых выздоровления почти не наблюдались. UI лучше формулировать это вероятностно: например `terminal trajectory suspected`, `11 похожих случаев / выздоровлений не наблюдалось`, confidence HIGH — но не превращать знание в гарантированный бинарный флаг. Укус/заражённая кровь в рану могут отдельно учитываться как evidence высокой дозы.

Disease notebook должен включать **карту распространения/hosts текущего штамма**: кровь/контакт, поверхности, воздух, вода, food, insects/vectors и отдельные animal species. У каждого направления видно `known / unknown / suspected`, supporting evidence и confidence. World baseline может уже знать, что non-human hosts существуют и infected humans способны питаться животными/трупами/другими заражёнными. Current-strain knowledge уточняет susceptibility по видам, animal→human route, бессимптомное носительство, изменения страха/поведения, длительность infectivity, raw carcass/blood risk, effect of cooking и vector properties.

## `CHAT-PI-022` — Изучение вируса, эксперименты и разработка лечения

**Категории:** `CAT-01`, `CAT-02`, `CAT-03`, `CAT-04`, `CAT-05`, `CAT-07`, `CAT-10`

База наблюдает заболевших, выдерживает карантин, сравнивает исходы, анализирует образцы и при некоторых сценариях сознательно проводит опасные эксперименты. **Живой заражённый сам является ценным источником данных**: progression симптомов, скорость изменения состояния, реакции на препараты/тесты, особенности прямого заражения и вероятность разных исходов. Полностью превратившиеся заражённые тоже могут давать evidence о реакции на звук/свет, скорости, поведении, устойчивости к травмам и других свойствах текущего штамма.

При наличии лаборатории и специалистов можно развивать диагностику, поддерживающие препараты, лечение, профилактику и снижение заразности/симптомов. Human trials связывают науку с правосудием и ценой конкретной жизни.

Animal samples/observations тоже являются research material: host range, animal course, return transmission to humans, duration of infectivity, carcass/blood risk, behavioural changes и cooking safety. Это связывает лабораторию с `CHAT-PI-052/053`.

Игрок может поставить **проверку гипотезы**, но не обязан вручную разыгрывать лабораторную сцену. Research job определяет нужные условия: infected subject / animal / sample, controlled room, protection, наблюдение, специалисты, время и при необходимости control/repetition. Например `test whether infected rabbits avoid turned humans` использует безопасно ограниченного infected subject и животное, а результат автоматически записывается как experimental evidence.

Живой infected research subject является постоянной затратой. Ему могут требоваться вода, пища/поддержание подходящего physiological state, безопасное помещение, фиксация, охрана, sanitation и labour. Для некоторых behavioural/physiology tests сильно истощённый субъект даёт хуже интерпретируемый результат: наблюдение может описывать starvation, а не normal strain behaviour.

Игра не обязана позволять идеальный ран без потерь.

---

# `CHAT-PI-023` — Architectural surveillance visual direction

**Тип:** Visual Direction / Production-fit Requirement\
**Категории:** `CAT-06`, `CAT-09`, `CAT-10`\
**Состояние:** Accepted preliminary direction

### 23. Теперь самое важное — визуал

Я бы **не делал обычный RimWorld-view**.

Это сразу визуально поставит игру в позицию:

> дешёвый RimWorld про вирус.

Нужно другое лицо.

Мой основной кандидат:

# **Архитектурный разрез / floor-plan surveillance aesthetic**

То есть база выглядит как смесь:

- архитектурного плана;
- диспетчерской системы;
- старых схем гражданской обороны;
- CCTV;
- медицинского интерфейса.

Но при этом люди физически существуют на карте.

### 24. Как выглядит основная карта

Представь почти чёрный или очень тёмный фон.

Здание изображено как понятный архитектурный план:

```text
┌────────────┬───────────┐
│ ПАЛАТА 1   │ ЛАБА      │
│   ● ● ●    │   ●       │
│            │           │
├──────D─────┼────D──────┤
│ КОРИДОР                │
│ ● → → →                │
├──────D─────┬───────────┤
│ СКЛАД      │ КАРАНТИН  │
│            │ ● ●       │
└────────────┴───────────┘
```

Но намного красивее, конечно.

Люди — небольшие хорошо читаемые фигурки или силуэты.

Не пиксельный pawn с одеждой из 12 спрайтов.

Например:

- маленькая человеческая фигура сверху;
- круглый портрет при выборе;
- профессия через небольшой символ;
- состояние через контур/маркер.

### 25. Почему это хорошо

Нам совершенно не нужны:

- красивые лица на карте;
- сложные анимации;
- десятки направлений тела;
- дорогие здания;
- мебель высокой детализации;
- реалистичные зомби.

Но игра всё равно может выглядеть **намеренно стилизованной**, а не дешёвой.

### 26. Люди

Я бы сделал людей очень простыми на общей карте.

Например:

```text
  ○
 /|\
 / \
```

условно, не буквально.

Но когда выбираешь человека, сбоку открывается карточка:

**АННА ПЕТРОВА — 34**

- врач;
- усталость;
- страх;
- голод;
- текущая задача;
- известные ей правила;
- что она знает;
- подозрения;
- контакты;
- отношения.

Можно иметь статичный портрет.

Даже несколько вариантов лиц, собранных из частей.

Это очень дешёво.

### 27. Зомби

Тут вообще можно избежать дорогой анимации.

Один зомби не должен быть визуальной звездой.

Страшна **толпа**.

Можно отображать:

- отдельные силуэты при малом количестве;
- при скоплении они визуально превращаются в плотную движущуюся массу;
- над проходом появляется показатель давления.

Например:

```text
█████████ → [ДВЕРЬ]
PRESSURE 74%
```

Но не как голый progress bar.

Лучше визуально:

- фигурки начинают наслаиваться;
- толпа качается;
- дверь дрожит;
- слышен металл;
- на плане появляются импульсы давления.

Дешёво, но очень атмосферно.

Новая horde direction требует показывать **не только pressure у двери**, а стадию формирования массы: growing density, растекание вдоль фасада, blocked entrances, отдельные фигуры выше первого уровня при piling/climbing, локально нарушенный грунт при digging и markers вроде `AGGREGATING / PERIMETER SPREAD / VERTICAL PRESSURE / BREACH ROUTE`. Это должно оставаться production-cheap: визуальный агрегат массы важнее сотен уникальных сложных анимаций.

### 28. Цвет — не «красный/жёлтый/зелёный мир»

Поскольку зоны пользовательские, я бы не привязывал игру намертво к трём цветам.

Базовая карта почти монохромная.

А поверх неё игрок включает overlays:

### Risk

Показывает степень санитарного риска.

### Access

Показывает разрешения.

### Knowledge

Показывает подозреваемых и качество информации.

### Logistics

Показывает потоки.

### Communication

Показывает, кто находится на связи.

### Security

Показывает охрану и контролируемые границы.

Это очень дешёвый способ сделать игру визуально богатой.

### 29. Очень важная визуальная идея: нормальный режим не должен быть Excel

Когда ничего не выделено, игрок должен видеть **живое здание**.

Люди:

- идут;
- разговаривают;
- едят;
- работают;
- стоят у дверей;
- несут контейнеры;
- собираются группами.

То есть схемность — визуальный стиль, но не чистая таблица.

А overlays появляются по запросу.

Иначе вся эмоциональность людей пропадёт.

### 30. Что может сделать визуал реально запоминающимся

Ранний вариант связывал ухудшение ситуации с буквальной потерей physical vision: delayed figures, LAST KNOWN и тёмные сектора. После knowledge-model pass это **не current baseline**.

В текущем направлении основная карта остаётся читаемой, а неопределённость визуализируется прежде всего в **качестве знания о людях и событиях**:

- trait/skill может быть заявленным, предполагаемым или подтверждённым;
- сведения имеют source и confidence;
- противоречащие доклады могут сосуществовать;
- камера/запись может давать более сильное evidence для расследования, не являясь обязательным условием базового vision;
- неизвестное содержимое инвентаря, мотив или источник слуха отображаются как реальные пробелы в dossier.

Более радикальные `LAST KNOWN`, low-FPS camera feeds и физическая потеря vision сохранены в deferred `CHAT-PI-037`.

### 31. Экран болезни

Здесь я бы действительно дал отдельный экран.

Не красивую 3D-лабораторию.

А почти как рабочая доска эпидемиолога.

Экран может использовать визуальную грамматику карты распространения: не дерево покупаемых мутаций, а **network/matrix текущего штамма**.

Пример:

## CURRENT STRAIN

**Transmission**
- Blood / wound — HIGH confidence
- Surface — MODERATE
- Air — UNKNOWN
- Water — weak evidence

**Vectors**
- Flies — mechanical transfer: SUSPECTED
- Mosquitoes — acquisition: ?
- Mosquitoes — salivary transmission: ?

**Hosts**
- Rabbits — infection: HIGH
- Rabbit → human: UNKNOWN
- Rats — SUSPECTED
- Birds — no useful evidence

**Evidence**
- 11 field observations
- 3 recorded cases
- 2 controlled tests
- conflicting report: 1

**Scientific assessment**
- `infected rabbits show reduced avoidance` — HIGH confidence
- `raw rabbit blood can infect humans` — insufficient evidence

Руководство может отдельно иметь precautionary assumption или действующую policy, но **это не обязательный quiz и не автоматический output научного экрана**. Главное назначение UI — показать, что известно, почему специалисты так считают, что остаётся неизвестным и какие исследования способны уменьшить uncertainty.

Это может стать одной из самых характерных частей всей игры.

### 32. Как я бы сейчас сформулировал visual pillar

> **Не смотреть на красивую колонию сверху, а смотреть на живой кризисный комплекс через систему наблюдения и управления.**

Это:

- оправдывает дешёвый визуал;
- соответствует теме информации;
- хорошо показывает зоны;
- хорошо показывает людей;
- позволяет визуализировать неполное знание и confidence;
- позволяет использовать камеры/записи как evidence-layer;
- хорошо работает с крупными планами;
- визуально отличает игру от RimWorld.

### Следующий visual research pass

Exploratory reference pass уже обсуждался, но ещё нужна отдельная accepted reference matrix: архитектурные floor plans, CCTV/dispatch consoles, emergency-management схемы, hospital/epidemiology dashboards, civil-defense graphics и подходящие stylized top-down games.

---

## `CHAT-PI-024` — Производство и физическое поддержание базы

**Категории:** `CAT-02`, `CAT-03`, `CAT-04`, `CAT-05`, `CAT-07`, `CAT-10`

Производство существует потому, что люди ежедневно потребляют ресурсы, вещи изнашиваются, а инфраструктура требует обслуживания. Линии могут включать еду, воду, электричество, отопление, одежду/постель, санитарные средства, лекарства, инструменты, мебель, строительные элементы, защитное снаряжение и оружие.

Ресурс может быть найден, произведён, восстановлен, переработан или заменён худшим самодельным аналогом. Не вся «работа» даёт материальный output: охрана, наблюдение, бухгалтерия, связь и подходящий карантинным условиям досуг также поддерживают базу.

Полный production tree определяется позже и должен обслуживать центральные dilemmas, а не превращать игру в Factorio.

## `CHAT-PI-025` — Питание, приготовление и санитарный риск

**Категории:** `CAT-02`, `CAT-03`, `CAT-04`, `CAT-05`, `CAT-10`

Герметичная готовая еда вроде консервов относительно безопасна: мало посредников, долгое хранение, минимальная обработка, но запас ограничен.

Возобновляемая/сырая еда требует выращивания или добычи, хранения, доставки, приготовления, воды, посуды, уборки и работников. Чем длиннее цепочка, тем больше контактов. Поэтому более устойчивая экономика может быть санитарно опаснее простой складской.

Выращивание требует пространства, воды, субстрата/земли, света, оборудования и безопасного доступа. Крыша/внутренний двор — implementation candidates.

**Где люди едят** тоже является санитарным решением. В early intake можно выдавать sealed ration прямо в holding/жилой сектор. Позже отдельные маленькие food points/столовые уменьшают межсекторные контакты, а одна большая общая столовая эффективнее и социально приятнее, но создаёт мощную точку смешения людей.

Небольшое животноводство, особенно **кролики**, является strong candidate возобновляемой еды. Оно добавляет feed/water/cleaning/slaughter/butchering и отдельную sanitary boundary. Мясо заражённого животного не автоматически бесполезно: при одном штамме raw butchering опасен, но достаточное приготовление делает мясо пригодным; при другом cooking не решает проблему или animal→human route вообще отсутствует.

## `CHAT-PI-026` — Вода, гигиена, санитария и стирка

**Категории:** `CAT-02`, `CAT-04`, `CAT-05`, `CAT-06`, `CAT-10`

Вода расходуется на питьё, готовку, мытьё рук/тела, уборку, стирку, обеззараживание и медицину. Гигиена — реальная производственная нагрузка.

Нужны получение, очистка, хранение, нагрев и доставка воды. Прачечная/санитарная обработка создаёт отдельную работу. Мыло/моющие средства могут производиться внутри. Иногда загрязнённую вещь выгоднее уничтожить, чем тратить воду, средство, время и безопасный персонал.

Реалистичность водопроводной/дождевой воды и очистки исследуется отдельно.

Current realism direction:
- кипячение эффективно против микробиологических патогенов, но **не удаляет** топливо, токсичные химикаты, тяжёлые металлы, соли и многие другие non-biological contaminants;
- обычный переносной фильтр не должен автоматически означать removal of viruses;
- потеря давления/долгий простой городской сети снижают confidence и могут требовать отдельной промывки/проверки.

First-demo candidate: водопровод ещё подаёт воду, известного промышленного загрязнения нет, но microbiological confidence уже недостаточен для прямого питья. Это позволяет иметь воду для части технических задач и одновременно отдельную drinking-water treatment burden. Это scenario hypothesis, не universal post-apocalypse rule.

Для санитарных переходов и environment cleanup рабочими resource groups пока считаются: **вода**, **мыло/моющее средство**, **средство обеззараживания**, **чистая одежда/СИЗ** и время персонала. Не нужно считать спирт универсальным ответом: конкретная процедура и эффективное средство должны зависеть от поверхности/загрязнения и от того, что база знает о штамме. Exact concentrations/chemistry требуют отдельного realism research.

## `CHAT-PI-027` — Электричество, топливо, отопление и температура

**Категории:** `CAT-02`, `CAT-04`, `CAT-05`, `CAT-07`, `CAT-10`

Электричество зависит от источника, топлива, обслуживания и специалистов. Его потеря бьёт по свету, связи, наблюдению, лаборатории, медицине, насосам и производству.

Топливо может приходить из рейдов или частично заменяться местными источниками. Отопление/температура — отдельная жизненная необходимость. Дерево потенциально конкурирует между строительством и отоплением/энергией.

Способ получения электроэнергии из дерева/биотоплива требует отдельной проверки реалистичности.

## `CHAT-PI-028` — Одежда, текстиль, износ и замена

**Категории:** `CAT-04`, `CAT-05`, `CAT-07`, `CAT-10`

Одежда, рабочие вещи, постель и полотенца изнашиваются, рвутся и загрязняются. Самодельные варианты могут быть хуже промышленного, но восполняемы.

После контакта с кровью/заражённой средой вещь можно оставить в той же риск-зоне, постирать, серьёзно обеззаразить или выбросить. Это создаёт спрос на ткань, шитьё, прачечную, воду и моющие средства.

## `CHAT-PI-029` — Частная собственность и личные вещи как санитарная и социальная граница

**Категории:** `CAT-03`, `CAT-04`, `CAT-05`, `CAT-06`, `CAT-10`

У человека есть **частная собственность**, а не только абстрактный личный инвентарь для гигиены. Предмет может иметь владельца, историю контактов, эмоциональную ценность и право распоряжения: оставить себе, подарить, обменять, продать, передать родственнику или согласиться на конфискацию.

Санитарная история собственности важна: вещь заражённого или вещь, побывавшая в рискованном секторе, может быть опасна. Поэтому ownership и trade rules должны взаимодействовать с чистотой предмета, зонами и decon.

После смерти, исчезновения, карантина или перевода возникает решение: оставить имущество за владельцем, передать родственникам, обработать, конфисковать, уничтожить или пустить в регулируемый обмен. Частная собственность связывается с кражами, отношениями, правосудием, неравенством и будущей внутренней торговлей.

## `CHAT-PI-030` — Чистота предметов, риск и обеззараживание

**Категории:** `CAT-02`, `CAT-03`, `CAT-04`, `CAT-06`, `CAT-10`

Предметы имеют санитарную историю: clean object после контакта с рискованным человеком/помещением становится потенциально загрязнённым. Некоторые вещи легко моются, некоторые требуют дорогой обработки, а некоторые рациональнее уничтожить или навсегда оставить внутри той же риск-зоны.

При передаче между зонами учитывается не только курьер, но и груз. Decon/стирка/transfer points стоят времени, воды, реагентов, оборудования и людей.

История перемещений людей и предметов должна помогать объяснять возможные цепочки заражения постфактум.

Загрязнение **пространства** — кровь, тело, пол/стена/койка, contaminated waste — связано, но не принадлежит этому item; environmental owner — `CHAT-PI-048`.

## `CHAT-PI-031` — Санитарное разделение производства против эффективности

**Категории:** `CAT-02`, `CAT-03`, `CAT-04`, `CAT-05`, `CAT-10`

Экономически выгодно иметь одну большую кухню, мастерскую или склад. Санитарно это общий failure domain: один заражённый работник или загрязнённый поток ставит под риск сразу огромную часть базы.

Игрок может сознательно строить менее эффективные независимые цепочки: отдельная кухня/склад для чистых, носителей или карантина; несколько маленьких мастерских вместо одной оптимальной.

Дублирование — плата за локализацию риска.

## `CHAT-PI-032` — Физическая логистика, переносчики и контролируемые маршруты

**Категории:** `CAT-02`, `CAT-03`, `CAT-04`, `CAT-06`, `CAT-09`, `CAT-10`

Ресурсы не телепортируются. Нужны логисты/переносчики, которые забирают, несут, передают, разгружают и возвращаются.

Для межзонного движения важно: кто несёт, что несёт, откуда/куда, через какой переход, сколько времени находится в риск-зоне и как возвращается. КПП/передаточные пункты контролируют такие переходы.

Чтобы не задушить игрока, внутри одной совместимой зоны route может выбираться автоматически; при пересечении санитарной границы игрок задаёт/контролирует допустимый route/transfer point. Логистику можно показывать overlay-линиями.

Слишком свободная автоматизация ухудшает contact traceability; слишком детальная ручная маршрутизация создаёт anti-fun.

Сектор/шлюз может показывать **supply requirements**, например `clean clothes required`, `water expected`, `detergent`, `disinfectant`. Игроку не нужно вручную переносить каждую куртку: действие `Supply/Привезти` выбирает source, допустимый route/transfer point и compatible carrier. При необходимости можно разово назначить обычного человека, не являющегося профессиональным переносчиком.

**Air network deferred.**

## `CHAT-PI-033` — Ответственные, производственные руководители и учёт

**Категории:** `CAT-02`, `CAT-03`, `CAT-04`, `CAT-06`, `CAT-10`

Игрок может делегировать управление ответственным за помещение, группу помещений, производство, строительство, охрану или сектор.

Хороший руководитель сочетает предметную компетентность с интеллектом/организацией и social qualities. Он контролирует работу, замечает ухудшение людей, ведёт учёт, сводит производство/расход и передаёт информацию наверх.

Руководитель одновременно management multiplier, observation node и communication node.

## `CHAT-PI-034` — Характеристики, навыки и предметный опыт

**Категории:** `CAT-03`, `CAT-04`, `CAT-05`, `CAT-06`, `CAT-10`

Нужно различать общие способности и предметный опыт.

Характеристики-кандидаты: сила, интеллект, social ability, ловкость, скорость, выносливость/телосложение. Domain experience: медицина, выращивание, электричество, металлообработка, стрельба, шитьё, готовка, бухгалтерия, логистика и т.д.

Человек может быть умным, но не знать электричество; опытным фермером, но плохим руководителем. Personality отдельно: способность выполнить действие ≠ готовность его выполнить.

В current knowledge direction новый человек **не обязан приходить с достоверным skill sheet**. Он может заявить опыт, иметь документы или чужую рекомендацию, но реальная компетенция подтверждается работой, наблюдением и результатами.

При этом неизвестность не должна навсегда прятать progression. После того как навык достаточно проверен, UI может показывать его значительно точнее — вплоть до обычного читаемого уровня/прогресс-бара. Это позволяет игроку привязаться к важному персонажу и наблюдать, как уже знакомый специалист реально развивается.

Рабочий progression around a person:
`заявленная квалификация → первые задания → подтверждённая компетенция → доверенный специалист → наблюдаемый рост / обучение других`.

Полный список skills и точная шкала выводятся позже из jobs/scenarios.

## `CHAT-PI-035` — Индивидуальное знание, неизвестность, публичный статус и слухи

**Категории:** `CAT-02`, `CAT-03`, `CAT-05`, `CAT-06`, `CAT-07`, `CAT-10`

Персонаж не должен магически знать событие на другом конце базы. Чтобы узнать о смерти, прорыве, переводе или казни, нужен источник: наблюдение, тело, разговор, радио, официальное сообщение или косвенный вывод.

Объективное состояние человека и belief другого различаются. Для знакомого/родственника статус может быть: жив, ранен, в карантине, переведён, пропал, судьба неизвестна, вероятно мёртв, официально объявлен мёртвым.

Судьба особенно важна при родстве, дружбе, любви, конфликте, совместной работе или знакомстве. Родственник может запросить официальный статус. Руководство может дать правдивую, неполную или ложную публичную версию.

Другой свидетель способен дать противоречащую историю. Персонаж может поверить власти, другу, никому или сформировать собственную гипотезу. Из неопределённости рождаются слухи: «его давно не видели + сектор потерян + власти молчат → наверное, их всех убили».

Возможна потребность в осведомлённости: если люди видят стрельбу, исчезновение знакомых и закрывающиеся проходы, но не получают понятной картины, растут тревога, недоверие и самостоятельные попытки узнать правду.

Scientific/professional disagreement тоже является событием внутри information system. Врач может считать новый карантин или уничтожение поголовья оправданным evidence, а другой специалист — преждевременным. Эти оценки не телепортируются всему населению, но могут распространяться через разговоры, доклады и слухи: `medical team says there was no evidence for this` становится отдельной причиной доверия/недоверия, а не магическим global modifier.

Система должна быть event-driven и ограниченной значимыми связями, а не непрерывной all-pairs симуляцией всех мыслей.

Неизвестность жителей не означает неизвестность игрока о физическом расположении пешек: физическая карта остаётся читаемой. Но игрок не обязан автоматически знать **кто первоначально сказал правду, кто запустил слух, кто сознательно исказил историю и насколько искренне конкретный человек в неё верит**. Эти сведения могут появляться через свидетелей, расследование, информаторов и записи.

Covert execution использует ту же модель. Объективно человек может быть уже мёртв, пока родственник считает его переведённым, другой житель слышал выстрел, а два охранника знают правду. Сила сцены зависит от ограниченного круга свидетелей и от возможности позднего утекания/противоречия официальной версии.



## `CHAT-PI-036` — Прозрачное пространство и постепенно узнаваемые люди

**Тип:** Interface / Simulation Contract\
**Категории:** `CAT-01`, `CAT-03`, `CAT-05`, `CAT-06`, `CAT-10`\
**Состояние:** Preliminary accepted direction

Физическая **освоенная/операционная часть базы** остаётся достаточно прозрачной как в colony sim: игрок видит положение пешек, работу, маршрут, комнаты, очевидные действия и инфраструктуру. Это сохраняет читаемость строительства, производства, логистики и кризисного управления.

Это не означает, что игрок с нулевой секунды знает содержимое физически **неисследованного** подвала, закрытого технического крыла или пространства за завалом. Scenario-defined unverified space может требовать реального входа/освещения/разведки: слышать движение из темноты, попытаться выманить кого-то шумом, открыть дверь под прикрытием, обнаружить пролом наружу. После исследования/взятия под контроль такая область возвращается к обычной transparent-space baseline. Это не `PI-037` camera-fog по всей базе.

Но **человек не обязан быть полностью известной таблицей характеристик**. Knowledge about people делится по природе:

- базовые очевидные потребности и физические состояния читаются относительно легко;
- родство, явные конфликты и наблюдаемые отношения могут быть известными фактами;
- реальная профессиональная компетенция подтверждается документами, работой и оценками;
- personality, лояльность, склонность нарушать правила и часть психического состояния собираются постепенно;
- скрытые мотивы, секреты, содержимое карманов и истинные намерения могут требовать специальных источников.

Знание имеет source/confidence. Хорошо известный человек постепенно перестаёт быть загадкой: если база накопила много согласующихся наблюдений, его профиль и skills становятся достаточно надёжными и удобными для обычного управления.

Люди, близкие к зелёному ядру и руководству, как правило, изучены лучше из-за частого прямого общения и наблюдения. Это создаёт важный progression: неизвестный человек может постепенно стать проверенным специалистом и доверенным членом ядра. Чем ценнее и лучше изучен человек, тем болезненнее его потеря.

**Player commands остаются без simulation latency.** Информационная неизвестность относится к людям и событиям внутри мира, а не к обязательной доставке каждого приказа через радио/гонца.

## `CHAT-PI-037` — Радикальный physical vision через камеры и доверенных наблюдателей

**Тип:** Alternative Game Direction / Decision Candidate\
**Категории:** `CAT-01`, `CAT-03`, `CAT-06`, `CAT-09`, `CAT-10`\
**Состояние:** Preserved alternative / deferred — не current baseline

Более радикальный вариант: точная физическая картина базы тоже не дана игроку автоматически. Live vision создают камеры, доверенные люди, наблюдатели и работающая связь; без источника остаются last-known positions, фрагментарные radio reports или низкочастотные обновления.

Камеры могут давать покадровую/неполную запись, позволяя некоторым скрытым действиям происходить между наблюдениями. Такой вариант сильно усиливает тему information control, но меняет жанровое ощущение и делает low-tech сценарий значительно труднее.

Идея сохраняется для отдельного прототипа; current direction `PI-036` **не требует камер для базового physical vision**.

## `CHAT-PI-038` — Досье на людей, доверие и human intelligence

**Тип:** Personnel Knowledge / Social Intelligence System\
**Категории:** `CAT-02`, `CAT-03`, `CAT-04`, `CAT-05`, `CAT-06`, `CAT-07`, `CAT-10`\
**Состояние:** Accepted / New

База постепенно строит **досье на человека** из наблюдений и источников. В нём могут сосуществовать факты, заявления, оценки и гипотезы с разной уверенностью: результаты работы, характеристики начальника, медицинские наблюдения, нарушения, рассказы коллег, сведения охраны, отношения и подозрения.

Разные роли дают разные виды информации:
- производственный руководитель хорошо оценивает профессиональную надёжность и работоспособность;
- врач видит физическое состояние;
- психолог потенциально лучше раскрывает страхи, стресс, мотивы и межличностные проблемы;
- охрана видит нарушения и доступ;
- информатор внутри коллектива может передавать разговоры, отношения, секреты, преступления и слухи.

Источник не равен истине. Он может ошибаться, преувеличивать, защищать друга, сводить счёты или сознательно лгать. Поэтому personnel intelligence должен хранить происхождение и confidence, а не просто открывать hidden trait навсегда после одного доклада.

Доверие и безопасность становятся взаимосвязаны. Человек может сотрудничать из лояльности, служебной обязанности, страха потерять безопасную зону, карьеризма или сделки. Возможные сделки включают перевод самого информатора или родственника в более безопасный сектор, сохранение привилегии, снятие наказания или другую услугу.

Особенно важен green-zone leverage: член защищённого круга не обязан быть лояльным, но у него больше того, что можно потерять, и руководство обычно знает его лучше.

В pre-run setup кастомизированный trusted core является важным исключением из обычной неизвестности: игрок **имеет право хорошо знать этих людей с самого старта**, потому что они представляют заранее выбранную/долго знакомую группу. Это делает неизвестность остальных жителей контрастной и объяснимой, а не универсальным fog вокруг каждого персонажа.

## `CHAT-PI-039` — Внутренняя торговля и регулируемый обмен частной собственностью

**Тип:** Supporting Economy / Social System / Decision Candidate\
**Категории:** `CAT-02`, `CAT-03`, `CAT-04`, `CAT-05`, `CAT-06`, `CAT-10`\
**Состояние:** Accepted as decision candidate / New

Жители могут не только владеть вещами, но и **передавать, дарить и потенциально торговать** частной собственностью внутри базы. Это создаёт локальную социальную экономику поверх общего снабжения.

Игрок/руководство может задавать правила обмена:
- какие категории людей могут обмениваться;
- какие типы предметов разрешены;
- требуется ли регистрация;
- через какие точки проходит обмен;
- нужно ли санитарное подтверждение/decon;
- разрешён ли обмен между зонами в обоих направлениях.

Санитарные правила могут быть асимметричны. Например, чистую одежду или предмет из зелёной зоны можно передать в более рискованный сектор, но после использования там он уже не должен возвращаться наверх без обработки.

Фиксация обменов может помогать contact tracing, расследованию краж и учёту собственности. При этом систему нельзя превращать в обязательный бухгалтерский симулятор каждого носка.

Точная модель цен, валюты, бартера, личных запасов и неофициального рынка остаётся открытой.



## `CHAT-PI-040` — Подготовка рана: trusted core, generated population и качество старта

**Тип:** Run Setup / Scenario Generation\
**Категории:** `CAT-01`, `CAT-02`, `CAT-03`, `CAT-05`, `CAT-06`, `CAT-07`, `CAT-10`\
**Состояние:** Preliminary accepted

Перед началом рана игрок может выбрать сценарий и **создать/настроить ограниченное количество персонажей своего trusted core**. Это позволяет играть за людей, которых хочется видеть в верхушке и зелёном ядре, и одновременно создаёт естественное объяснение, почему именно они хорошо известны игроку с первой минуты.

Остальное население не должно полностью кастомизироваться: оно генерируется и сохраняет неизвестность skills/personality/relationships/health history, необходимую current people-knowledge concept.

Старт должен проверяться в двух измерениях:

1. **Functional coverage** — есть ли хотя бы минимальная способность поддерживать критические функции: медицина, maintenance/электрика, еда, security, logistics/general labour, management/observation.
2. **Overall start quality** — полезные специалисты, здоровье, оборудование и хорошие связи увеличивают стартовую силу; болезни, exposure/infection, тяжёлые конфликты, опасные/трудные personality, травмы и другие проблемы могут её снижать.

Один scalar score не заменяет coverage: четыре отличных врача не делают старт жизнеспособным без maintenance и security.

Игроку не нужно запрещать слишком сильный или слишком слабый setup. UI может обозначать `Balanced / Favorable / Harsh / Custom-Unbalanced` и предупреждать, что выбранный core заметно меняет intended difficulty.

При этом balance UI **не должен выдавать скрытые факты**. Generator может учитывать объективное заражение или скрытую опасную personality, но не обязан раскрывать игроку, какая именно пешка снизила score.

Точные числа населения, размер кастомизируемого core и формула budget — balance/playtest questions, не текущая архитектура.

## `CHAT-PI-041` — Стартовое здание демки и происхождение чистого ядра

**Тип:** Demo Scenario / Spatial Progression\
**Категории:** `CAT-02`, `CAT-03`, `CAT-04`, `CAT-05`, `CAT-06`, `CAT-07`, `CAT-09`, `CAT-10`\
**Состояние:** Preliminary accepted demo direction

Для первой демки используется **фиксированное строение**. Игра начинается не с пустого участка и не с необходимости изобрести quarantine logic с нуля.

Небольшая исходная группа уже находится внутри организованного clean core. Это люди с хорошо известной recent contact history и контролируемым пребыванием; у игрока есть основания считать их безопасными.

Новые/хуже известные люди находятся в intake/perimeter у здания и охраняются небольшой силой. Их ещё нужно распределить, проверить, поселить и включить в работу. Вооружённые люди на периметре сами не обязаны автоматически быть green.

Стартовая карта может сразу содержать несколько типов пространства:

- **clean / usable** — маленький проверенный core;
- **dirty / unverified** — пустые или потенциально загрязнённые коридоры/комнаты, которые нужно очистить и проверить;
- **blocked** — завалы, заклинившие двери или другие физические препятствия, постепенно открывающие здание;
- **lost / infected** — небольшое надёжно запечатанное крыло с ограниченным количеством заражённых, которые в начале не могут сами прорваться;
- **unexplored / physically unverified** — тёмная/закрытая часть здания, где точная обстановка неизвестна до разведки; там могут оказаться заражённые, животные, следы людей, оборудование или breach/дыра наружу.

Таким образом игрок с первой минуты видит смысл очистки, изоляции, reclaim и пространственного progression без немедленного unfair crisis.

Unexplored space также даёт локальную тактическую сцену **внутри собственного facility**: работа в темноте, фонари/освещение, listening, noise/lure, прикрытие выхода, постепенная проверка комнат. Это может знакомить игрока с тем же tactical language, который позже используется в raid.

`Clean / dirty / lost` здесь — **состояния пространства**, а не возврат к superseded фиксированной red/yellow/green architecture. Реальные пользовательские зоны и политики остаются настраиваемыми.

First-demo facility должен давать место, где игрок **сам проектирует/достраивает переходные шлюзы**. Не нужно выдавать ему навсегда фиксированную жёлтую и красную линию: базовая архитектура должна позволять поставить один простой all-in-one пункт или позже разветвить поток на быстрый corridor и specialist bays.

Current map-size hypothesis для демки: **одно достаточно крупное главное здание + непосредственный двор/подходы**, чтобы имели смысл несколько маршрутов, один заражённый wing, intake, lower/external levels и хотя бы потенциально больше одного входа. Несколько полноценных зданий через улицу/двор сохраняются как future escalation, потому что резко усложняют связь, наружную логистику и containment.

Полный procedural building generation для первой демки не требуется. Для дальнейшей игры остаётся открытым выбор между несколькими handcrafted scenarios, частично вариативным состоянием одной shell и более процедурным миром.

## `CHAT-PI-042` — Command Circle: верхний уровень руководства и общий управленческий контур

**Тип:** Leadership / Player-Fiction / Information Structure\
**Категории:** `CAT-01`, `CAT-03`, `CAT-05`, `CAT-06`, `CAT-07`, `CAT-10`\
**Состояние:** Preliminary accepted concept

Рабочая модель верхушки — **Command Circle**: один или несколько людей, над которыми в локальной структуре уже нет другого руководителя и которые по умолчанию кооперируются и имеют общий доступ к официальной управленческой информации.

В конкретном сценарии сюда могут входить:
- общий руководитель;
- самый высокий medical/science authority;
- самый высокий military/security authority;
- operations/engineering/logistics authority.

Это не обязательный список и не требование четырёх разных людей: в малой базе один человек может совмещать несколько ролей.

Command Circle **не равен зелёной зоне, вооружённым людям или всем доверенным людям**. Член верхушки может выйти на внешний периметр, санитарно потерять право немедленно войти обратно в clean core, но не перестать быть руководителем. Обычный чистый специалист может жить внутри core без политической власти.

Player-fiction пока остаётся открытой: игрок может представлять коллективное действие верхушки как интерфейсную абстракцию, а не буквально глаза одного аватара.

## `CHAT-PI-043` — Вооружённая сила, лояльность и основания подчинения

**Тип:** Security / Governance / Social Simulation\
**Категории:** `CAT-01`, `CAT-03`, `CAT-04`, `CAT-05`, `CAT-07`, `CAT-10`\
**Состояние:** Accepted design line

Охрана и другие вооружённые люди являются не только combat resource, но и **носителями реальной внутренней силы**. Поэтому вопрос «кому дать оружие?» связан с доверием, иерархией и политикой так же, как вопрос «кого пустить в clean core?».

Лояльность не должна сводиться к одному абстрактному числу без причин. Основания подчинения могут включать:
- личное доверие к командиру;
- безопасность самого человека;
- безопасность партнёра/детей/родственников;
- доступ к лучшему питанию, отдыху, развлечениям или жилью;
- статус и карьеру;
- страх потерять привилегию;
- представление о справедливости;
- доверие к процедурам и руководству;
- веру в общую задачу убежища.

Один и тот же observable уровень дисциплины может поэтому опираться на совершенно разные причины и разрушиться при разных событиях.

Особенно важно, что **armed ≠ green**. Внешний охранник может быть очень полезен и вооружён, но санитарно оставаться в более рискованном контуре.

На дальнейшую игру сохранена идея разных emergent governance trajectories: власть через личную лояльность/привилегии/страх против более institutional system с понятными правилами и высокой легитимностью. Это не принято как полноценная отдельная simulation architecture.

На старте часть прибывших тоже может иметь оружие. Их admission становится первой естественной political/security situation: договориться оставить оружие в внешнем storage, разрешить носить его только в perimeter sector, временно привлечь человека к внешней охране или вообще не пропускать глубже. Это лучше демонстрирует `force ≠ trust ≠ sanitary access`, чем автоматическое разоружение.

## `CHAT-PI-044` — Внешний мир: глобальная карта, экспедиции и меняющееся zombie pressure

**Тип:** External Strategic Layer / Decision Candidate\
**Категории:** `CAT-02`, `CAT-03`, `CAT-04`, `CAT-05`, `CAT-07`, `CAT-10`\
**Состояние:** Decision candidate

За основной базой может существовать большая стратегическая карта с районами/секторами, которые можно разведать и посещать.

На ней могут находиться:
- более или менее безопасные районы;
- точки ресурсов;
- другие базы/убежища;
- торговые контакты;
- потенциальные новые жители;
- погибшие базы, которые после заражения становятся опасными loot/reclaim targets;
- временные миссии и события.

Current preferred expedition gameplay теперь **hybrid**:
- global layer остаётся strategic для выбора района, маршрута, времени, снабжения и общей цели;
- при достижении конкретной raid site / опасного объекта игра может перейти в небольшой directly controlled tactical space;
- текстовые/автономные travel events и remote decisions всё ещё допустимы между tactical sites.

Это расширяет старый passive-strategic candidate, а не требует полноценной отдельной RTS. Tactical raid должен использовать тех же людей, skills, injuries, equipment, contamination и rules of engagement, что база.

Внешнее присутствие заражённых не обязано быть постоянным равномерным морем. Сильная идея — **мигрирующее/меняющееся давление**: район может быть относительно тихим, затем через него проходит концентрация заражённых, после чего окно для рейда открывается снова.

Для opening demo это можно сделать **известным временным окном**: разведданные/наблюдение показывают, что крупная масса скоро пройдёт через район. До её прихода хочется успеть провести нужный raid и подготовить нижние/наружные уровни; во время прохода внешние операции временно становятся почти невозможны.

Важно не делать миграцию просто scripted attack. Если база ведёт себя тихо, масса может пройти мимо. Шум, стрельба, неудачно возвращённый рейд или другая активность способны привлечь часть заражённых. И даже когда основная масса уйдёт, привлечённые к зданию заражённые могут **остаться**, блокируя выход и создавая новое persistent consequence state.

Заражённая масса не должна ощущаться бесконечно энергичной или бесконечно spawn-ящейся. Current direction: район имеет **конечную infected population mass**, которую можно локально стянуть шумом/движением/другими стимулами. Малое скопление может усиливать local attraction и перейти через stages `малое присутствие → aggregation → perimeter spread → multi-point siege → penetration opportunity`.

Стягивание потенциально делает другие места временно безопаснее и допускает рискованную стратегию намеренно pull infected away from another route. Но проблема у базы затем сохраняется: часть массы остаётся, загрязняет территорию, ищет обходы и выедает доступные ресурсы.

Долговременная биология/энергетика принадлежит `CHAT-PI-052`: старые заражённые истощаются, переходят в low activity, используют найденную пищу/животных/трупы/каннибализм и со временем погибают. Орды формируются, мигрируют и распадаются, а не являются вечными одинаковыми объектами.

## `CHAT-PI-045` — Прогресс рана и глобальная цель

**Тип:** Run Progression / Goal Structure\
**Категории:** `CAT-01`, `CAT-02`, `CAT-03`, `CAT-05`, `CAT-07`, `CAT-10`\
**Состояние:** Decision candidate / Partially formed

Окончательная win condition пока не выбрана. `Find a cure` не принимается автоматически как единственная универсальная цель.

Сильнейшая current formulation общего progression:

> **расширять область проверенной безопасности, круг надёжно известных/интегрированных людей и знание о болезни, одновременно превращая временное убежище в устойчивое общество.**

Ран поэтому может развиваться сразу по нескольким осям:
- больше надёжно контролируемого пространства;
- больше устойчивой инфраструктуры;
- больше проверенных/обученных людей;
- более надёжные процедуры и security;
- более точная модель текущего штамма;
- больше внешних связей и доступных районов.

Для первой демки рабочая цель может быть гораздо конкретнее: **стабилизировать аварийное убежище** — сохранить исходное clean core, организовать новых людей, восстановить ключевую инфраструктуру, расширить usable territory/reclaim хотя бы часть здания и получить значимое знание о текущей инфекции.

Стабилизация сама по себе не должна быть единственным visible carrot. Opening phase нужен **понятный локальный objective, обещающий новый геймплейный capability**, а не только ещё один запас ресурсов. Current strongest example: сигнал/данные о соседнем убежище, где осталось лабораторное/диагностическое оборудование или архив наблюдений. Если успеть подготовить рейд и забрать его до приближения массы заражённых, база получает доступ к более серьёзному исследованию вируса/диагностике или другой новой механике.

Рабочая demo arc:
`принять и организовать людей → увидеть opportunity + forecast угрозы → подготовить raid и lower/base defenses → получить capability → закрыть внешнюю активность → пережить миграцию → использовать новый capability`.

Exact objective fiction и таймер не зафиксированы; важен принцип `reward = новый интересный verb/system`, а не просто `+20 медикаментов`.

Точный чеклист, длительность, победа/поражение и необходимость внешнего слоя для первой демки ещё требуют отдельного pass.

## `CHAT-PI-046` — Личные цели и future stakes персонажей

**Тип:** Character Motivation / Social Simulation\
**Категории:** `CAT-01`, `CAT-03`, `CAT-05`, `CAT-06`, `CAT-07`, `CAT-10`\
**Состояние:** Accepted direction

Помимо текущих needs, отношений и personality у человека может быть **future stake** — конкретная вещь, которой он надеется добиться, дождаться или избежать.

Примеры:
- перевести себя или близкого в более безопасный сектор;
- дождаться освобождения/лечения родственника;
- найти пропавшего человека;
- получить собственную комнату;
- стать начальником или попасть в trusted core;
- получить конкретное лекарство;
- накопить/получить ценную вещь;
- покинуть город;
- дождаться исследования лечения;
- добиться справедливости или мести.

Future stake помогает объяснять лояльность, сделки, доносы, нарушение правил и эмоциональную реакцию на решения игрока. Это особенно полезно в мире, где «просто убрать проблемного человека» физически возможно, но социальная цена зависит от того, что этот человек значил другим.

Цель не обязана сразу быть известна игроку. Часть таких мотивов может открываться через отношения, наблюдение, психолога, информаторов или прямой разговор и становиться частью personnel dossier.




## `CHAT-PI-047` — Локальные capability-goals и временное давление opening phase

**Тип:** Opening Pacing / Goal Structure / Pressure\
**Категории:** `CAT-01`, `CAT-02`, `CAT-03`, `CAT-05`, `CAT-07`, `CAT-10`\
**Состояние:** Preliminary accepted demo direction

Помимо интуитивных задач «не умереть / наладить базу» игрок с самого начала должен видеть **что-то, к чему хочется прийти**.

Сильная рабочая формула:

> **если я сейчас нормально организую убежище, то успею сделать важную внешнюю операцию и открыть новый интересный capability до того, как внешняя ситуация закроет окно.**

Пример, не обязательный final fiction: база получает сигнал/сведения о другом убежище, где осталось оборудование и/или архив, позволяющие серьёзнее исследовать инфекцию. Это создаёт желание подготовить raid не ради абстрактного loot, а ради возможности попробовать новую механику.

Параллельно существует pressure: скоро через район пройдёт крупная масса заражённых. До её прихода нужно успеть разобраться с прибывшими, получить рабочую силу, подготовить lower/outside areas, решить кого рискнуть отправить, снабдить экспедицию, вернуть людей/оборудование и прекратить лишнюю наружную активность.

Миграция не должна автоматически означать штурм. Если игрок не привлекает внимание, масса может пройти мимо. Если привлекает, часть заражённых остаётся у здания и ухудшает будущий выход наружу.

Opening pressure желательно дополнить хотя бы одной **острой локальной encounter**, чтобы заражённые не ощущались только стратегическим таймером. Candidate: fresh infected преследуют поздно прибывших/рейд к периметру либо небольшой fresh outbreak заставляет впервые использовать guard positions, doors и sanitation. Это demo-sequence candidate, не locked screenplay.

Это создаёт opening dilemma, очень близкую core concept:
> **получить больше уверенности и подготовиться лучше — или действовать сейчас, пока ещё есть возможность.**

## `CHAT-PI-048` — Санитарная служба, загрязнение пространства и временные закрытия

**Тип:** Environmental Sanitation / Labour / Spatial State\
**Категории:** `CAT-02`, `CAT-03`, `CAT-04`, `CAT-05`, `CAT-06`, `CAT-09`, `CAT-10`\
**Состояние:** Accepted design line

Чистота сектора означает не только чистые предметы и людей. **Кровь, трупы, загрязнённые поверхности, койки, полы, стены и contaminated waste должны физически приводиться в контролируемое состояние.**

Для этого нужна отдельная sanitation work line / санитарные работники. Они могут убрать тело, собрать опасный мусор/бельё, удалить видимое загрязнение, вымыть помещение, применить подходящее средство обеззараживания и подготовить комнату/шлюз для следующего использования.

Рабочий state flow:
`OPEN/USABLE → CONTAMINATED/CLOSED → gross cleanup → wash → disinfect/prepare → OPEN`.

Коридор или комната на время работы могут блокироваться. Это усиливает ценность второго маршрута. В дисциплинированной базе знак/барьер может быть достаточен; на важной границе существующий security checkpoint способен enforce временное `NO PASSAGE`.

Environment sanitation тратит время работников и, в зависимости от процедуры, воду, моющее средство, средство обеззараживания, чистую одежду/СИЗ и capacity для грязного белья/отходов. Exact реализм и chemistry должны исследоваться отдельно.

Combat contamination может создавать **локальную санитарную область**, а не только один contaminated tile: кровь попадает на людей/одежду/пол/стены, тела оставляют опасную работу, помещение может быть потеряно даже после победы. Насколько далеко риск распространяется сам по себе, зависит от medium/strain. Мухи и другие mechanical vectors после оставленной крови/трупов сохраняются как strain candidate, а не universal law.

Загрязнение после содержания тяжёлого заражённого является частью цены решения «ждать до последнего»: даже если человек умер/превратился, койку и помещение ещё нужно вернуть в работу.

## `CHAT-PI-049` — Настраиваемые шлюзы, intake и принятие решений о переходе

**Тип:** Player-Built Transition / Evidence / Routing System\
**Категории:** `CAT-02`, `CAT-03`, `CAT-04`, `CAT-05`, `CAT-06`, `CAT-09`, `CAT-10`\
**Состояние:** Accepted design direction

**Шлюз — это тип размещаемого игроком переходного/проверочного объекта**, а не заранее заданный `yellow` или `red` building.

В шлюзе игрок настраивает, **что именно проверяется и что выполняется**. Candidate procedures: поверхностный осмотр одежды/тела; видимые ранения, укусы, кровь и сильная грязь; **следы укусов комаров/других потенциально инфекционных животных, если current evidence делает это relevant**; оружие и явные вещи; короткий опрос; глубокий contact-history interview; более подробный medical inspection; доступный тест; снятие внешней одежды; обычное мытьё; усиленная санитарная обработка; получение чистой одежды/СИЗ; ожидание решения.

Такие проверки не принадлежат исключительно шлюзу. `Inspect for recent bites / exposure marks` может быть обычным плановым/после-event medical order для людей уже внутри сектора. Шлюз лишь удобное место встроить ту же процедуру в переход.

Работник не требует от игрока смотреть каждую анимацию. Он выполняет configured inspection и после завершения даёт **`ASSESSMENT / REPORT READY`**. Игрок смотрит собранные данные и выбирает: перевести человека в конкретный сектор; отправить в другой специализированный шлюз; отправить в temporary/high-risk holding; оставить ждать; для внешнего человека — **не впустить / отправить наружу**.

Можно построить один all-in-one шлюз и делать всё в нём. Это понятно и дёшево по площади, но медленно: глубокий допрос, мытьё и особенно heavily contaminated case занимают помещение и увеличивают время подготовки к следующему человеку.

Поэтому **специализация — выгодная тактика игрока, а не навязанная система**. Например:
`OUTSIDE → FAST SCREEN → controlled intake spine → FINAL GATE`,
а сбоку от fast flow могут быть deep medical check, heavy cleaning, detailed interview/security и high-risk holding.

Ранний вариант `main → yellow шлюз / red шлюз` сохраняется только как один понятный пример такой специализации: низко-подозрительные люди не обязаны мыться там же, где только что обрабатывали человека в большом количестве крови, но игра не заставляет строить именно два цветных шлюза.

Вся система до final admission может считаться **внешней/грязной относительно нормальной базы**, поэтому человек может безопасно уйти из fast path в specialist bay и затем вернуться в processing flow.

### Emergency admission

Если снаружи уже поджимают заражённые, игрок может не успеть индивидуально обработать толпу. Полезна большая защищённая **dirty holding / приёмная**, куда можно быстро запустить людей за периметр, не считая их принятыми в обычные сектора.

Это спасает их, но смешивает разный уровень риска, создаёт новые контакты, переносит вооружённых/буйных внутрь внешнего периметра, усложняет последующий отказ и делает применение силы внутри толпы опаснее из-за крови, паники и возможного заражения.

### Multiple entrances / own expeditions

Большая база может иметь главный intake, service/emergency entrance и другие входы с разной пропускной способностью. Один вход может быть заблокирован массой заражённых.

Свои возвращающиеся рейдеры проходят тот же physical sanitation logic, но решение `не впустить` для них политически гораздо тяжелее. Возможен специальный service intake или временный perimeter holding до clearance.

## `CHAT-PI-050` — Охранные посты, checkpoint enforcement, patrol и escort

**Тип:** Security Command / Spatial Enforcement\
**Категории:** `CAT-02`, `CAT-03`, `CAT-04`, `CAT-05`, `CAT-06`, `CAT-09`, `CAT-10`\
**Состояние:** Accepted design direction

Охрана должна быть отдельной управляемой spatial system, а не только job `Guard`.

**Checkpoint** — пост на границе двух зон. При выборе boundary/rule UI игрок может нажать условное `Create guard post`. Такой пост знает правила обеих сторон и следит за access, завершением transition procedure, переносимыми предметами, оружием, временным sanitary closure и попыткой пройти вопреки правилам.

**Guard post** — свободная точка, которую можно поставить не на границе: оружейный склад, камера с заражённым, внешний вход, зона Command Circle, место казни и т.п.

**Patrol** — маршрут контроля области.

**Escort / reserve** — сопровождение конкретного человека/группы или ожидание тревоги.

Пост может иметь required staffing и автоматически заполняться подходящим охранником, при этом игрок может закрепить конкретного человека вручную.

Пост не обязан означать построенную дорогую будку: базовый marker/service point работает сразу, а fortified checkpoint может быть поздней физической постройкой.

Не каждый проход требует двух вооружённых людей. Обычные правила могут соблюдаться добровольно. Но главный внешний intake, high-risk граница и другие конфликтные точки естественно требуют более серьёзного присутствия.

Combat extension должен оставаться management-level. Пост/группа может получать **rules of engagement**: когда открывать огонь, какую линию не пересекать, до какой точки отступать, преследовать ли заражённого, можно ли покидать checkpoint, `stop/slow first` vs `precision kill`. Mandatory headshot всё ещё не принят.

Security response при тревоге связывается с `CHAT-PI-056/057`: заранее заданный plan может поднять reserve, отправить response squad к конкретной границе, удерживать checkpoint или, наоборот, запрещать охране входить в сектор до эвакуации. Tactical response squad использует тот же command language, что raid team (`CHAT-PI-054`).



## `CHAT-PI-051` — Fresh / conserved / special infected, бой и формирование орды

**Тип:** Threat Model / Combat / Containment Stress\
**Категории:** `CAT-01`, `CAT-02`, `CAT-03`, `CAT-04`, `CAT-05`, `CAT-06`, `CAT-07`, `CAT-09`, `CAT-10`\
**Состояние:** Accepted design direction

Заражённые не должны быть одной равномерной массой одинаковых медленных целей.

**Fresh infected** — недавно turned, физически ещё относительно целы. Они способны быстро бегать/рывками сокращать дистанцию, резко атаковать и создавать максимальную непосредственную опасность. Fresh outbreak внутри жилого/рабочего сектора потенциально опаснее старой толпы снаружи.

**Conserved / old infected** — изношенные и энергетически истощённые. Они менее опасны индивидуально, больше времени проводят в low-activity state, но способны существовать как многочисленная стратегическая масса, концентрироваться вокруг стимула и надолго лишать базу наружной свободы.

**Special / retained-function variants** — не обязательные videogame classes, а редкие свойства штамма/стадии, где сохраняются отдельные human motor/behaviour functions. Кандидаты: более эффективное лазание, простое использование предмета/инструмента, unusual biological-fluid attack/кашель/плевок, копающее/foraging behaviour. Не формировать обязательный набор `танк / плевун / босс`.

### Horde formation

Орда — **локальная концентрация конечной infected population**, а не бесконечный spawn.

Рабочие stages:
`малые отдельные заражённые → aggregation → perimeter spread → multi-point siege → penetration opportunity`.

Масса опасна тем, что:
- блокирует главный вход;
- растекается вдоль стен;
- занимает двор;
- ищет service/emergency entrances, окна, наружные лестницы и технические пути;
- мешает наружному ремонту/cleanup;
- может отрезать возвращающийся raid;
- при определённых traits способна карабкаться, формировать body pile или нарушать мягкий грунт.

Каждый дополнительный час плотного присутствия у базы повышает риск **потери контроля над периметром**, даже если основная containment door ещё закрыта.

### Combat

Игрок прежде всего решает **где принимать бой и какой уровень риска допустим**, а не микроконтролит каждую пулю. На хорошо организованной базе normal defense может часто сводиться к снятию отдельных блуждающих заражённых с безопасной позиции, тихому оружию/арбалетоподобному средству или ограниченному ближнему бою. Более насыщенный tactical combat therefore естественно вынести в raids, unexplored spaces и emergency breaches, а не постоянно штурмовать саму базу.

Убийство infected:
- во дворе;
- в intake;
- в clean corridor;
- в столовой;
- возле refuge point

имеет разную цену из-за крови, тел, noise и temporary closure.

Огнестрел даёт дистанцию, но создаёт noise/ammo/biological-mess trade-off. Ближний бой тише, но резко повышает direct-contact risk. Prepared barriers/doors/kill zones покупают время и позволяют выбирать место загрязнения.

Бой заканчивается цепочкой:
`active threat removed → bodies/blood/contaminated people → closure → sanitation → route restored`.

## `CHAT-PI-052` — Экология заражения, энергетика и animal hosts

**Тип:** Infection Ecology / World Simulation / Biological Baseline\
**Категории:** `CAT-01`, `CAT-02`, `CAT-04`, `CAT-05`, `CAT-06`, `CAT-07`, `CAT-10`\
**Состояние:** Accepted baseline direction / exact strain details open

Human infected **не являются биологически бессмертными или энергетически самодостаточными**. Без воды/пищи и при постоянной высокой активности организм деградирует и в итоге погибает.

Обычный ран поддерживает угрозу сочетанием:
- fresh infected ещё используют собственные ресурсы организма;
- old infected переходят в low-activity/conserved state;
- ищут воду и доступную пищу;
- scavenging: человеческая еда, животные, трупы;
- cannibalism при дефиците;
- animal hosts продолжают превращать внешнюю экологическую кормовую базу в доступную биомассу;
- animal/human reservoirs создают новые human infections и новые fresh outbreaks.

Большая орда therefore не обязана месяцами сохранять исходную численность и активность: часть погибает, часть съедается, часть впадает в низкую активность, часть мигрирует.

### Baseline herbivore/feed-animal direction

Strong ordinary-run baseline:

> часть травоядных/других кормовых животных заражается, продолжает относительно нормально кормиться и размножаться, но теряет нормальное избегание заражённых.

Животному не нужно осознанно «жертвовать собой». Достаточно сниженного страха/дистанции при сохранении обычной реакции на непосредственную боль/погоню.

Это создаёт энергетический мост:
`растительность / естественная кормовая база → животное → old infected`.

После человеческого коллапса некоторые herbivore/feral populations потенциально могут расти из-за снижения охоты/контроля, особенно в пригородах/зелёных районах; exact темп — world-balance question.

### Discovery boundary

Не нужно каждый ран заново выяснять, **может ли инфекция вообще существовать вне человека**. Мир может знать общий факт non-human infection ecology.

Но current strain определяет:
- какие виды восприимчивы;
- насколько тяжело болеют;
- продолжают ли нормально кормиться/размножаться;
- есть ли animal→human transmission;
- есть ли бессимптомное/длительное носительство;
- меняется ли fear response;
- опасны ли кровь/туша/фекалии;
- насколько эффективен cooking;
- участвуют ли rats/birds/dogs;
- возможны ли mechanical vectors вроде мух.

Крысы, птицы и агрессивные infected animals therefore могут быть очень серьёзной угрозой в одном ране и почти тупиковым host в другом.

### Insect / vector split

**Мухи** — в первую очередь candidate mechanical transfer: контакт с blood/corpses/waste способен переносить загрязняющий материал дальше исходного пятна, если current strain достаточно долго сохраняется таким путём.

**Комары** требуют отдельной biology и не считаются просто «дальним airborne». Для current strain могут независимо исследоваться:
- **acquisition** — насколько легко mosquito заражается после blood meal;
- **detectability / amplification** — когда pathogen становится обнаружим в mosquito;
- **transmission competence** — способен ли такой mosquito затем реально заражать человека/животное;
- **delay** — сколько времени между acquisition и возможной передачей;
- **exposure strength** — насколько значим один bite относительно других routes.

Быстрое/частое mosquito acquisition не обязано означать эффективную передачу человеку. И наоборот, presence of mosquito vector не задаёт сейчас никаких конкретных чисел по частоте укусов, infection chance или required dose — **balance intentionally deferred**.

Если mosquito transmission когда-либо включается в конкретный ран, нужен readable counterplay вместо невидимых случайных бросков: room/vector pressure, screens/closed openings, traps, standing-water control и другие меры остаются implementation candidates.

### Distant alternative

Фотосинтетическая/symbiotic support оставлена только как **экзотическая distant strain idea**. Если когда-либо используется, логичнее трактовать её как сложный symbiotic complex, а не простое свойство обычного вируса; baseline на ней не зависит.

## `CHAT-PI-053` — Животноводство, мясо и санитарный контур животных

**Тип:** Food Production / Animal Biosecurity / Research\
**Категории:** `CAT-02`, `CAT-03`, `CAT-04`, `CAT-05`, `CAT-06`, `CAT-07`, `CAT-10`\
**Состояние:** Accepted production candidate

Small livestock, особенно **кролики**, хорошо связывает возобновляемую еду с infection-control core.

Animal husbandry требует:
- корм;
- воду;
- клетки/вольер;
- cleaning/waste;
- reproduction/stock management;
- slaughter;
- butchering;
- cooking/storage;
- работников и санитарный маршрут.

### Closed herd

Собственное давно контролируемое поголовье имеет высокую sanitary confidence. Дикое/новое животное, пойманное снаружи, не должно автоматически попадать в breeding stock.

Полезная policy:
`closed herd` / `quarantine incoming animals`.

Таким образом animal intake повторяет ту же логику, что human intake, но дешевле и жёстче.

### Meat / carcass decisions

Potentially infected animal **не означает автоматически `destroy all meat`**.

Current-strain possibilities:
- animal infected, но animal→human route отсутствует;
- raw blood/tissue опасны при slaughter/butchering, зато достаточное cooking делает meat safe;
- carcass остаётся опасным даже после обычного cooking;
- риск неизвестен и игрок решает, исследовать/уничтожить/использовать под давлением голода.

Это создаёт сильную ситуацию:
`food for 2 days + 18 potentially infected rabbits → destroy / isolate / test / slaughter with protection / cook and risk`.

Livestock therefore является одновременно food system, sanitary system и research material, а не отдельным farming minigame.




## `CHAT-PI-054` — Прямое тактическое управление raid/response squad

**Тип:** Tactical Control / Shared Combat Language\
**Категории:** `CAT-01`, `CAT-02`, `CAT-03`, `CAT-05`, `CAT-06`, `CAT-07`, `CAT-09`, `CAT-10`\
**Состояние:** Accepted design direction

Игра должна позволять **непосредственно управлять небольшим отрядом** в raid encounter и в некоторых base emergency situations.

Причина не в желании добавить отдельную боевую игру. Основная база при хорошем управлении должна часто избегать больших сражений; routine perimeter defense может быть редкой/контролируемой. Tactical raid and breach response дают нужные пики физического риска, не превращая everyday colony management в постоянную войну.

Preferred control level:
- выбрать позицию/маршрут;
- удерживать/прикрывать дверь или коридор;
- идти первым / следовать;
- осветить/проверить тёмную область;
- открыть/закрыть/вскрыть преграду;
- создать шум или попытаться выманить угрозу;
- вступать в бой / избегать;
- retreat/fallback;
- унести раненого/критический груз.

Не требуется manual aiming каждой пули. Skills, weapon choice, stress, visibility, distance, cover и rules of engagement могут разрешать подробности автоматически.

Главный production rule: **raid squad и base response squad используют максимально один и тот же tactical system**. Это удерживает игру цельной и позволяет tutorial/skills/AI переиспользовать между базой и внешними операциями.

## `CHAT-PI-055` — Физическая разведка неисследованных частей здания

**Тип:** Local Exploration / Physical Uncertainty / Tactical Discovery\
**Категории:** `CAT-02`, `CAT-03`, `CAT-05`, `CAT-06`, `CAT-07`, `CAT-09`, `CAT-10`\
**Состояние:** Preliminary accepted direction

Transparent-space baseline относится к **уже освоенной/исследованной** базе. Physically unentered/unverified area может реально быть неизвестной.

Примеры:
- тёмный basement;
- закрытый технический wing;
- помещение за завалом/заклинившей дверью;
- abandoned lower floor;
- участок, о котором есть только старый building plan.

Игрок может:
- слушать за дверью/в темноте;
- включить или принести свет;
- послать одного/несколько людей под прикрытием;
- открыть дверь и отступить;
- создать noise/lure и ждать реакции;
- постепенно проверить комнаты;
- позднее поставить temporary observation/camera, если это полезно.

Unexplored space может содержать infected, животных, людей, ресурсы или **неизвестный breach наружу**. Поэтому «убили всех, кого нашли» не означает автоматически `safe`: нужно понять, откуда они появились, закрыть hole/window/drain/utility route и затем провести sanitation/reclaim.

Это локальная physical uncertainty и не отменяет `CHAT-PI-036`; после исследования область становится обычной читаемой частью colony map.

## `CHAT-PI-056` — Тревоги, аварийные планы и тренировки

**Тип:** Alarm / Preparedness / Emergency Behaviour\
**Категории:** `CAT-02`, `CAT-03`, `CAT-04`, `CAT-05`, `CAT-06`, `CAT-07`, `CAT-10`\
**Состояние:** Accepted design direction

Многие crisis situations должны входить в управление через **тревогу**, поднятую конкретным источником информации.

Тревога не обязана сразу раскрывать истину. Возможный report:
`WEST RESIDENTIAL — Pavel heard glass break / movement inside — exact threat UNKNOWN`.

Триггеры могут включать:
- fresh/special infected в помещении;
- неизвестное движение/звук;
- broken window / hole / unexpected route;
- known infected animal, rodent or bird;
- unusual insect/vector event;
- human intruder/raider;
- кровь/крик/стрельбу;
- человека, который внезапно turns.

### Prepared emergency plan

Игрок может заранее готовить для сектора:
- primary evacuation route A;
- reserve route B;
- shelter-in-place/refuge instruction;
- assembly/refuge destination;
- какие двери закрываются/остаются открыты;
- guard/response positions;
- кто остаётся выполнять critical job;
- fallback при blocked route.

План уменьшает число ручных приказов во время кризиса. При этом immediate player command delivery остаётся без latency: preparedness влияет не на «доставку приказа», а на скорость/согласованность физического исполнения людьми.

### Drills / rehearsal

План можно отрабатывать. Training/drill тратит рабочее время и временно мешает routine operations, но делает route/roles знакомыми, уменьшает замешательство, неправильные направления и crowding.

Drill не должен превращаться в обязательный repetitive chore; exact preparedness model требует отдельного pass.

## `CHAT-PI-057` — Быстрые emergency-команды комнаты/сектора

**Тип:** Crisis UI / Spatial Orders / Containment\
**Категории:** `CAT-02`, `CAT-03`, `CAT-04`, `CAT-05`, `CAT-06`, `CAT-09`, `CAT-10`\
**Состояние:** Accepted design direction

Во время alarm игроку нужен **набор high-level действий над комнатой/сектором**, чтобы не кликать каждого человека и каждую дверь.

Working command set:
- **Evacuate via A** — вывести по primary route;
- **Evacuate via B** — использовать reserve route;
- **Shelter in place** — людям оставаться в помещениях/refuges;
- **Lock / seal room** — локально закрыть конкретную комнату;
- **Seal sector** — закрыть все доступные physical boundaries сектора;
- **Lock internal / compartmentalize** — по возможности закрыть внутренние двери и разбить сектор на pockets;
- **Open evacuation corridor** — удержать выбранную цепочку проходов открытой для выхода;
- **Security response** — вызвать назначенную response group;
- **All clear / controlled reopen** — снять emergency mode по процедуре.

`Seal sector` **не создаёт магическую стену**. Результат зависит от:
- какие двери/shutters существуют;
- работают ли они;
- заперты/заклинены/сломаны ли;
- remote ли они или к ним должен дойти человек;
- не удерживает ли проход толпа/угроза;
- остались ли окна/дыры/технические пути.

Room-level и sector-level actions нужны одновременно. Одна fresh threat в спальне может требовать `lock room`; неизвестная угроза в жилом крыле — `seal sector`; infected в общем коридоре могут, наоборот, сделать **shelter in place** безопаснее массовой эвакуации.


---

# 5. Relation-backed Implementation Ideas

Implementation Idea = помнить и тестировать, но не считать выбранной архитектурой.

| ID | Idea | Status |
|---|---|---|
| `CHAT-II-001` | Фиксированные красный/жёлтый/зелёный контуры | **superseded** `CHAT-II-014` |
| `CHAT-II-002` | Раздельные маршруты людей/грузов/воздуха | people+objects kept; **air deferred** |
| `CHAT-II-003` | Несовершенные тесты и наблюдаемая цепочка контактов | accepted idea |
| `CHAT-II-004` | Структурированный дневной цикл | deferred до loop pass |
| `CHAT-II-005` | Люди нарушают правила | absorbed into `PI-011` |
| `CHAT-II-006` | Рейды/экспедиции вне основной карты | **updated:** strategic travel/planning retained; passive-only raid superseded by `PI-054` direct tactical site control |
| `CHAT-II-007` | Нападения как containment stress tests | accepted idea |
| `CHAT-II-008` | Модульная база вместо freeform | historical alternative; revisit after geometry pass |
| `CHAT-II-009` | 20–30-дневная демка + диагностика + подозрительный инженер | prototype candidate; screenplay deferred |
| `CHAT-II-010` | Разрушение преград через давление толпы | accepted idea |
| `CHAT-II-011` | Узкие/зигзаговые проходы с trade-off эвакуации | accepted idea |
| `CHAT-II-012` | Дорогая advanced containment system | progression candidate |
| `CHAT-II-013` | Меняющийся между ранами профиль инфекции | accepted idea |
| `CHAT-II-014` | Пользователь создаёт зоны и назначает им правила | accepted direction candidate |
| `CHAT-II-015` | Носительство ~10–15%, средовая устойчивость, укус как высокая доза | balance hypothesis |
| `CHAT-II-016` | Приказы и обычная информация используют общую transmission model | **Partially superseded for first demo:** ordinary information remains; player-command transmission removed |
| `CHAT-II-017` | Локальное управление после потери связи | deferred future candidate; not required by omniscient demo baseline |
| `CHAT-II-018` | Исполнители постепенно привыкают к жестоким приказам | character candidate |
| `CHAT-II-019` | Disease notebook / knowledge screen | accepted UI idea |
| `CHAT-II-020` | Agriculture на крыше / во внутреннем дворе | production candidate |
| `CHAT-II-021` | Дерево как аварийное топливо; разбор мебели / опасная рубка | requires realism research |
| `CHAT-II-022` | Самодельные инструменты, мебель и оружие хуже промышленного | production candidate |
| `CHAT-II-023` | Manager-gated bulk orders как в Dwarf Fortress | management candidate |
| `CHAT-II-024` | Учёт выявляет потери/кражи; manager может быть замешан | later-depth candidate |
| `CHAT-II-025` | Ограниченные рации + телефоны/телефонист + гонцы | future NPC-information/coordination candidate; not required for player commands |
| `CHAT-II-026` | Конкретный верховный лидер лично приходит/говорит/командует | leadership candidate |
| `CHAT-II-027` | Временная RimWorld-like mood/social baseline | prototype simplification |
| `CHAT-II-028` | Автоматический route внутри зоны; явный/рисуемый route и КПП между зонами | logistics simplification |
| `CHAT-II-029` | **Recovered:** рабочие карантинные когорты / sealed work cells | core-supporting candidate |
| `CHAT-II-030` | **Recovered:** многоэтапное возвращение потерянного сектора | reclaim candidate |
| `CHAT-II-031` | **Recovered/current:** ограниченная throughput КПП/decon/прачечной | logistics candidate |
| `CHAT-II-032` | Обыск и частично скрытый инвентарь | future candidate |
| `CHAT-II-033` | Невидимые/абстрактно разрешаемые преступления | future candidate; spatial consistency unresolved |
| `CHAT-II-034` | Personnel dossier из наблюдений и характеристик | **absorbed/expanded into current `PI-038`** |
| `CHAT-II-035` | Психолог: конфиденциальность / duty-to-report / тайный информатор | social-intelligence candidate |
| `CHAT-II-036` | Информаторы, услуги и сделки за сведения | social-intelligence candidate |
| `CHAT-II-037` | Постепенное подтверждение skill → readable progression | implementation candidate for `PI-034` |
| `CHAT-II-038` | Направленные санитарные правила обмена между зонами | implementation candidate for `PI-039` |
| `CHAT-II-039` | Посетители базы и торгово-сервисная пограничная зона | distant future candidate |
| `CHAT-II-040` | Prototype population: **revised ~30–40 total**, ~4–5 fully customizable trusted core | revised balance hypothesis |
| `CHAT-II-041` | Start generator: role coverage + hidden weighted quality budget | prototype candidate |
| `CHAT-II-042` | Fixed first-demo facility with debris, dirty corridors and sealed infected wing | demo candidate |
| `CHAT-II-043` | Security layers: core security / perimeter security / emergency militia | organization candidate |
| `CHAT-II-044` | Emergent governance trajectories: patronage/police ↔ institutional | distant systemic candidate |
| `CHAT-II-045` | Strategic expedition travel/events with radio decision points and autonomy on contact loss | external-layer candidate; tactical site can still be directly controlled |
| `CHAT-II-046` | Migrating/low-activity infected pressure outside | world-pressure / biology candidate |
| `CHAT-II-047` | Handcrafted scenario shells with variable operational state | full-game map candidate |
| `CHAT-II-048` | Signal/external equipment as first capability-unlock objective | demo pacing candidate |
| `CHAT-II-049` | Horde migration window + noise/attention leaves residual infected near base | demo/world-pressure candidate |
| `CHAT-II-050` | Environmental cleanup workflow and sanitary closures | implementation candidate for `PI-048` |
| `CHAT-II-051` | Sector/sluice resource requirements + one-click supply order | logistics/UI candidate |
| `CHAT-II-052` | Existing-group vs arrivals identity, reduced by mutual aid or reinforced by inequality | social candidate |
| `CHAT-II-053` | Fast screening spine + optional specialist bays | implementation example for `PI-049` |
| `CHAT-II-054` | Emergency dirty holding for mass admission under external pressure | implementation candidate for `PI-049` |
| `CHAT-II-055` | Main/service/emergency entrances; own raids return through service intake | spatial candidate |
| `CHAT-II-056` | Boundary-integrated checkpoint creation from zone settings | implementation candidate for `PI-050` |
| `CHAT-II-057` | Guard post / patrol / escort / reserve order set | implementation candidate for `PI-050` |
| `CHAT-II-058` | Center-mass vs precision/head-shot doctrine if infection biology supports it | combat candidate |
| `CHAT-II-059` | High-dose direct exposure: rapid severe course with possible masked vitality | strain/course candidate |
| `CHAT-II-060` | Covert execution: limited witnesses + false/partial public status | signature-situation candidate |
| `CHAT-II-061` | Large common dining vs sector-local food points | social/sanitary candidate |
| `CHAT-II-062` | Fresh infected as high-speed acute threat; old infected as low-activity mass | implementation candidate for `PI-051` |
| `CHAT-II-063` | Horde stages: aggregation → perimeter spread → multi-point siege → breach opportunity | implementation candidate for `PI-051` |
| `CHAT-II-064` | Finite regional infected pool can be deliberately attracted away from other locations | strategic candidate |
| `CHAT-II-065` | Body piling / vertical pressure at windows or upper levels | strain/geometry candidate |
| `CHAT-II-066` | Digging/foraging infected accidentally undermine fences or expose service routes | strain-behaviour candidate |
| `CHAT-II-067` | Retained procedural motor function: simple tool use / door handling | rare strain candidate |
| `CHAT-II-068` | Cough/spit/blood-fluid projection at short range | strain transmission/combat candidate |
| `CHAT-II-069` | Blood/corpses create secondary local risk; flies as possible mechanical vector | strain/sanitation candidate |
| `CHAT-II-070` | Refuges: interior rooms buy time, prepared safe rooms buy substantially more | containment candidate |
| `CHAT-II-071` | Infected energy ecology: low activity + scavenging + cannibalism + animal feeding | baseline ecology candidate |
| `CHAT-II-072` | Infected herbivores lose avoidance and feed old infected | baseline ecology candidate |
| `CHAT-II-073` | Rats/birds/dogs host roles vary by strain | discovery/world candidate |
| `CHAT-II-074` | Recovered cleared vs persistent/intermittent shedding | disease-course candidate |
| `CHAT-II-075` | Rabbit/compact livestock with closed-herd biosecurity | production candidate |
| `CHAT-II-076` | Raw butchering risk can differ from cooked-meat safety | food/research candidate |
| `CHAT-II-077` | Finite-infected survival scenario with weak/no animal reservoir | special scenario candidate |
| `CHAT-II-078` | Photosynthetic/symbiotic energy support | distant exotic strain idea |
| `CHAT-II-079` | Water service remains physically available but drinking confidence is degraded | first-demo resource candidate |
| `CHAT-II-080` | Disease transmission/host network screen with known/unknown/evidence/confidence | UI candidate for `PI-021/023` |
| `CHAT-II-081` | Evidence-quality ladder: report → observation → recording → controlled/repeated test | knowledge implementation candidate |
| `CHAT-II-082` | `Test hypothesis` as research job with subjects/materials/control conditions | research implementation candidate |
| `CHAT-II-083` | Living infected research subject upkeep affects cost and experimental quality | research/economy candidate |
| `CHAT-II-084` | Expert evaluation of scientific justification can become discussion/rumor/trust input | social-information candidate |
| `CHAT-II-085` | Inspect mosquito/animal bites in шлюз or scheduled medical check | medical/intake candidate |
| `CHAT-II-086` | Mosquito properties split: acquisition / detectability / transmission competence / delay / dose | vector-research candidate |
| `CHAT-II-087` | Laboratory mosquitoes as possible faster biological amplification test | **late speculative technology** |
| `CHAT-II-088` | Abstract room vector pressure + screens/traps/standing-water control | counterplay candidate |
| `CHAT-II-089` | Hidden strain-specific susceptibility + current resilience + exposure history | infection-model candidate |
| `CHAT-II-090` | Post-exposure prophylaxis with uncertain need/effect because infection state is hidden | treatment candidate |
| `CHAT-II-091` | Ordinary illness / co-infection can mask symptoms and modify current strain differently by run | disease-course candidate |
| `CHAT-II-092` | Shared tactical command language for raid squad and base response squad | implementation candidate for `PI-054` |
| `CHAT-II-093` | Quiet perimeter cleanup with low-noise ranged weapon / crossbow-like tool / melee | combat candidate |
| `CHAT-II-094` | Dark unexplored wing: listen, light, lure, cover, room-by-room check | implementation candidate for `PI-055` |
| `CHAT-II-095` | Hidden breach discovered after clearing: hole/window/drain/utility route must be closed | spatial/reclaim candidate |
| `CHAT-II-096` | Alarm starts from incomplete witness report rather than perfect threat reveal | information/crisis candidate |
| `CHAT-II-097` | Sector emergency plans with primary/reserve evacuation routes and shelter mode | implementation candidate for `PI-056` |
| `CHAT-II-098` | Emergency drills/rehearsal trade work time for better execution | preparedness candidate |
| `CHAT-II-099` | Rapid sector command set: evacuate A/B, shelter, seal, compartmentalize, response, all clear | implementation candidate for `PI-057` |
| `CHAT-II-100` | Shelter-in-place can outperform evacuation when fresh infected occupy corridors | crisis candidate |
| `CHAT-II-101` | Threat-entry event pool: window/breach, infected animal, rodents/birds, insects, raiders | scenario candidate |
| `CHAT-II-102` | Remote versus manual door/shutter closure affects how fast sector seal actually executes | infrastructure/UI candidate |

## `CHAT-II-029` — Working quarantine cohorts / sealed work cells

Подозрительный человек не обязательно полностью перестаёт работать. Рискованную группу можно оставить внутри изолированного рабочего контура. Это уменьшает экономическую цену карантина, но концентрирует риск: если подозрение подтверждается, можно потерять целую рабочую группу.

## `CHAT-II-030` — Sector reclamation workflow

Возврат потерянного сектора может включать: устранить активную угрозу → проверить помещения → удалить тела/опасный мусор → обеззаразить поверхности и предметы → отремонтировать двери/инфраструктуру → восстановить снабжение → проверить/карантинировать clearing crew.

Это важный ранний смысл, который в v0.4 был слишком сжат до «подготовить операцию по возвращению».

## `CHAT-II-031` — Transfer/decontamination throughput

КПП, передаточные шлюзы, прачечная и decon не должны быть бесплатной абстракцией. У них может быть ограниченная пропускная способность, очередь, расход воды/реагентов и требования к персоналу. Это натуральная цена безопасной логистики, но её нужно держать достаточно простой, чтобы не получить simulator of queues.



## `CHAT-II-032` — Обыск и частично скрытый инвентарь

Игрок может видеть то, что пешка держит в руках или носит явно, но не обязан автоматически знать всё содержимое карманов/личных вещей. Для полного знания можно потребовать добровольную проверку или обыск.

Это хорошо связывает personal belongings, охрану, правосудие и кражи и добавляет нужный социальный «вайб», но **не является requirement первой демки**.

## `CHAT-II-033` — Невидимые/абстрактно разрешаемые преступления

Возможный способ не превращать всевидящий camera view в автоматическое раскрытие каждой кражи: преступление может фиксироваться системой как совершённое без обязательной детальной анимации самого скрытого действия.

Проблема пока открыта: действие должно оставаться пространственно правдоподобным — нельзя допустить, чтобы персонаж фактически совершал кражу в одном месте, одновременно визуально находясь в другом. Поэтому идея сохраняется, но **не прорабатывается для первой демки**.

## `CHAT-II-034` — Personnel dossier из наблюдений и характеристик

Ранний Implementation Idea теперь **поглощён текущим `CHAT-PI-038`**: карточка человека хранит наблюдённые проявления и оценки источников.

Пример:

```text
IMPLICIT / OBSERVED PROFILE

Foreman, Day 4:
"worked steadily under pressure"

Security, Day 6:
"ignored distancing once"

Medical, Day 8:
"high anxiety"

Trait hypothesis:
DISCIPLINED — medium confidence
IMPULSIVE — low confidence
```

Этот интерфейс теперь является одним из основных кандидатов для current knowledge direction; точная глубина для первой демки ещё не выбрана.




## `CHAT-II-035` — Психолог: конфиденциальность, duty-to-report и тайный информатор

Психолог должен быть полезен **без шпионажа**: снижать стресс, помогать после потерь, карантина и тяжёлых приказов, замечать опасные психические состояния и межличностные проблемы.

Возможные режимы:

- **конфиденциальность** — сильнее доверие и терапевтическая польза, но мало intelligence;
- **duty to report** — заранее известно, что угрозы насилия, скрываемые симптомы или тяжёлые нарушения будут переданы руководству;
- **тайный информатор** — передаёт больше частной информации без ведома пациента.

Тайная работа сложнее обычной психологии и может требовать более высокого social/psychology/self-control skill: нужно смотреть человеку в глаза, сохранять доверие и одновременно передавать сведения. Если факт сотрудничества раскрывается, пациент может сам рассказать другим; доверие к психологу и потенциально ко всей службе падает.

## `CHAT-II-036` — Информаторы, услуги и сделки за сведения

«Крыса» внутри коллектива может сообщать разговоры, отношения, планы нарушений, преступления, секреты и ходящие слухи. Сотрудничество возможно по службе, из лояльности, страха, карьеризма или за конкретную услугу.

Примеры цены:
- перевести информатора в более безопасную зону;
- позже перевести его родственника;
- сохранить место в зелёном секторе;
- простить нарушение;
- дать доступ к дефицитному ресурсу.

Источник может врать, защищать друзей или использовать руководство для сведения счётов. Поэтому информатор увеличивает количество данных, а не гарантирует истину.

## `CHAT-II-037` — Подтверждение навыка и переход к readable progression

Новый человек может иметь только claim / documents / recommendation. Реальный уровень уточняется через задания и наблюдения. После накопления достаточной уверенности интерфейс перестаёт искусственно скрывать навык и позволяет нормально видеть дальнейшее обучение и рост.

Это поддерживает эмоциональную привязку: интерес к progression появляется уже после того, как персонаж стал знакомым и ценным.

## `CHAT-II-038` — Направленные санитарные правила обмена

Внутренний обмен может быть разрешён несимметрично:
`clean/high-security → lower-risk` допускается,
а обратный поток запрещён или требует decon.

Правила могут зависеть от типа предмета: металл/инструмент проще вернуть после обработки, ткань/мягкие личные вещи — дороже или вообще невыгодно.

## `CHAT-II-039` — Посетители базы и торгово-сервисная пограничная зона

Далёкая идея: внешние люди не обязаны сразу становиться жителями или врагами. Они могут приходить в специально контролируемую пограничную зону, пользоваться разрешёнными услугами, торговать и затем уходить.

Часть посетителей позже может попроситься остаться. Такая система связывает `CHAT-PI-019` external groups с санитарной логистикой, внутренней торговлей и потенциальным рынком, но **не относится к первой демке**.



## `CHAT-II-040` — Prototype population density

Для playtest first demo прежняя гипотеза `18–24` стала выглядеть слишком маленькой после появления checkpoint staffing, sanitation, intake, logistics и смен. Current test range: примерно **30–40 человек всего**, из которых около **4–5** принадлежат fully customizable trusted core. Это всё ещё не requirement и не принятый баланс.

Смысл диапазона:
- слишком мало людей ослабляет сектора, hierarchy, management и social network;
- слишком много слишком рано превращает people-knowledge и logistics в bookkeeping;
- ограниченный custom core создаёт эмоциональную привязку, не уничтожая неизвестность остальных.

## `CHAT-II-041` — Role coverage + hidden start-quality budget

Generator сначала проверяет наличие минимально жизнеспособного набора функций, затем считает общий objective quality.

Положительный вклад могут давать редкие специалисты, здоровье, надёжные relationships/equipment; отрицательный — exposure/infection, тяжёлое состояние, конфликтные/опасные qualities и другие burdens.

UI показывает итоговую сложность, но не раскрывает скрытую причину. Например наличие объективно заражённого человека может влиять на real balance без сообщения `one infected pawn detected`.

Игрок может сознательно выйти за recommended budget; ограничение лучше оформлять предупреждением, а не hard ban.

## `CHAT-II-042` — Fixed first-demo facility

Первый demo facility проектируется вручную под intended learning curve.

Стартовая shell содержит:
- маленький operating clean core;
- intake/perimeter;
- несколько полезных помещений;
- завалы/заклинившие проходы, которые постепенно открываются;
- dirty/unverified corridors;
- одно небольшое sealed infected wing с угрозой, которая сама не может немедленно прорваться.

Такой setup позволяет учить пространственной санитарной логике через саму карту, а не tutorial popups.

## `CHAT-II-043` — Security layers

Возможная организационная модель:
- **core security** — малое число наиболее доверенных людей для непосредственной охраны Command Circle / clean core;
- **perimeter / sector security** — вооружённые сотрудники более рискованных зон;
- **militia / auxiliary** — люди, которым оружие выдают только при кризисе.

Это не фиксированные классы, а удобный способ проверить, работает ли различие trust / access / force.

## `CHAT-II-044` — Emergent governance trajectories

Далёкий systemic candidate:

**Patronage / police structure**
- вооружённая иерархия;
- привилегии;
- сделки;
- личная лояльность;
- секретность;
- зависимость от конкретных командиров.

**Institutional structure**
- стабильные процедуры;
- объяснимые правила;
- предсказуемое enforcement;
- более высокая прозрачность;
- доверие к организации, а не только к конкретному человеку.

Игра не обязана предлагать бинарный выбор. Trajectory может возникать из повторяющихся действий игрока. Точная модель trust/legitimacy пока отсутствует.

## `CHAT-II-045` — Strategic expedition communication

Off-base squad может иметь pre-set instructions:
- приоритет задачи;
- допустимый риск;
- когда отступать;
- можно ли принимать новых людей;
- что считать достаточно ценным грузом.

Работающее радио позволяет получать промежуточные события и давать новые решения. Без связи squad использует инструкции, local leader, personality и собственную оценку ситуации.

Это возвращает communication latency туда, где она жанрово естественна, не ломая immediate colony controls внутри базы.

## `CHAT-II-046` — Migrating / low-activity infected pressure

World-map pressure может меняться во времени: quiet window → активизация/миграция → опасный период → уход/затихание.

Рабочая биологическая интуиция: заражённые не обязаны непрерывно бегать с максимальной энергией. Они могут долго находиться в low-activity/torpor state и резко активироваться от шума, людей или другого сильного стимула.

Почему организм способен существовать долго и какие мутации/источники энергии возможны — отдельный lore/research question, не requirement mechanics.

## `CHAT-II-047` — Handcrafted scenario shells with variable operational state

Если одна полностью фиксированная карта в full game окажется слишком решаемой, следующий шаг не обязан быть procedural room generation.

Альтернатива:
- несколько handcrafted facility types;
- узнаваемая topology внутри сценария;
- между ранами меняются завалы, работающие входы, распределение ресурсов, повреждённые помещения, заражённое крыло, доступная инфраструктура и внешняя ситуация.

Для первой демки даже эта вариативность не обязательна: важнее один хорошо настроенный starting puzzle.




## `CHAT-II-048` — First capability unlock from external objective
Opening objective должен обещать не только loot, а **новый gameplay verb/system**. Рабочий demo example: сигнал/наводка на другое убежище → оборудование/данные → raid до миграции → более серьёзное исследование вируса/диагностика. Exact wrapper может меняться.

## `CHAT-II-049` — Migration pressure, attention and residual infected
До прихода массы район доступнее; во время migration raids почти невозможны. Если база привлекла внимание, часть заражённых остаётся у входов после прохода и превращает ошибку в persistent operational problem.

## `CHAT-II-050` — Environmental cleanup workflow
`closure/sign → убрать тело/опасный мусор → удалить грубое загрязнение → вымыть → обеззаразить/подготовить → открыть`. После особенно грязного пациента такой же reset может требоваться шлюзу или койке.

## `CHAT-II-051` — Sector/sluice supply requirements
Зона/шлюз показывает clean clothes, water, detergent, disinfectant, spare СИЗ. `Supply` создаёт разовый order source → route → compatible carrier; можно вручную выбрать обычного человека.

## `CHAT-II-052` — Existing group vs arrivals
`already inside` и `new arrivals` — стартовая social memory, не permanent faction. Mutual aid может размыть её; unequal safety/privileges — закрепить.

## `CHAT-II-053` — Fast screening spine + specialist bays
```text
                 ┌─ DEEP MEDICAL ───────┐
                 │                       ↓
OUTSIDE → FAST SCREEN → DIRTY INTAKE → FINAL GATE → ASSIGNED SECTOR
                 │
                 ├─ HEAVY CLEANING ─────┘
                 ├─ DEEP INTERVIEW
                 └─ HIGH-RISK HOLDING
```
Это только example. All-in-one gate остаётся легальным.

## `CHAT-II-054` — Emergency dirty holding
Большой protected holding позволяет emergency admit при внешнем давлении. Цена: mixing risk, new contacts, crowd/panic, оружие внутри perimeter, сложность последующего отказа, опасность применения силы.

## `CHAT-II-055` — Multiple entrances and service intake
Main/service/emergency entrances могут иметь разную пропускную способность. Блокировка одного входа делает backup route ценным. Service intake особенно логичен для своих рейдов/грузов.

## `CHAT-II-056` — Boundary-integrated checkpoint
Boundary `Zone A ↔ Zone B` показывает rules и кнопку `Security checkpoint`; пост читает access/transition/items/weapons/closures.

## `CHAT-II-057` — Security order set
Minimum: checkpoint; guard here; patrol A→B→C; escort; reserve/react. Auto staffing допустим; manual pin optional.

## `CHAT-II-058` — Center-mass vs precision/head doctrine
Если biology требует разрушения головы/мозга, skill можно выражать doctrine: center mass легче и может замедлять; precision/head сложнее и потенциально быстрее lethal. Не принимать обязательный headshot rule до решения biology/combat model.

## `CHAT-II-059` — High-dose rapid course / masked vitality
Bite или contaminated blood directly into wound могут давать быстрый тяжёлый course. Для отдельного strain возможна временная внешняя энергичность перед резким turning. Не universal rule.

## `CHAT-II-060` — Covert execution information flow
Человека тихо ведут в закрытый блок; правду знают ограниченные guards/medical/leadership; public status может быть `переведён / изолирован / умер от болезни`; позднее свидетель/информатор/несостыковка раскрывает историю.

## `CHAT-II-061` — Sector-local food vs common dining
Early/holding: sealed ration в секторе и минимум cross-zone movement. Later: small food points снижают contacts; общая столовая эффективнее/social-positive, но создаёт mixing hub.



## `CHAT-II-062` — Fresh vs old threat profile
Fresh infected = high-speed, physically preserved, acute. Old infected = low-activity, weaker individually, dangerous in numbers. Exact speed/endurance values remain balance questions.

## `CHAT-II-063` — Horde formation stages
Useful readable states:
`scattered → aggregating → perimeter spread → multi-point siege → penetration opportunity`.
No infinite spawning is required.

## `CHAT-II-064` — Deliberate attraction
Because the regional population is finite, noise/decoy activity can pull infected from one location toward another. This may temporarily open a route while creating a larger problem near the lure/base.

## `CHAT-II-065` — Body piling / vertical pressure
At high density and suitable geometry, infected can climb over one another / form a rising pile toward windows, roofs of low annexes or upper openings. Rare/late enough to remain frightening rather than routine.

## `CHAT-II-066` — Digging / foraging infected
Some infected may repeatedly disturb soft soil while looking for worms/insects/roots/organic material. Near fences this can accidentally undermine the base, enlarge gaps or expose old utility trenches/drains. They are not consciously engineering a tunnel.

## `CHAT-II-067` — Retained procedural motor function
Rare infected can retain simple motor programs: pull a handle, climb a ladder, swing a tool already in hand, repeatedly strike an obstacle. Avoid giving them full human tactical intelligence.

## `CHAT-II-068` — Short-range biological-fluid threat
A strain can produce severe coughing, bloody saliva/vomit or reflexive spitting. This threatens people behind open bars/close checkpoints without turning infected into long-range acid artillery.

## `CHAT-II-069` — Secondary contamination / mechanical vectors
Unremoved blood/corpses can expand sanitation risk beyond the exact kill point through footsteps, clothing, tools and, for suitable strains, insects such as flies. Exact distance and viability are strain knowledge.

## `CHAT-II-070` — Prepared refuge points
Ordinary interior rooms buy minutes, not safety. A prepared refuge can have stronger door, communication, small water reserve, first aid/weapon access and alternate exit. Crisis UI should communicate time/condition rather than only HP.

## `CHAT-II-071` — Infected energy ecology
Baseline world intuition:
`activity consumes energy → starvation reduces activity → low activity conserves → feeding temporarily restores activity → prolonged deficit kills`.
Food can include scavenged human food, animals, corpses and cannibalism. Water access remains necessary for living infected.

## `CHAT-II-072` — Infected herbivores as feed bridge
Some herbivores/feed animals remain capable of grazing/feeding and reproduction while infected, but lose normal avoidance of infected humans. They convert vegetation/environmental food into biomass available to old infected.

## `CHAT-II-073` — Variable animal host roles
Current strain can make rodents, birds, dogs or other species:
- reservoir;
- short-lived host;
- dead-end host;
- animal→human bridge;
- asymptomatic carrier;
- aggressive infected animal.
This is discovery, not a universal identical rule.

## `CHAT-II-074` — Recovered carrier states
Candidate post-infection states: `cleared`, `persistent carrier`, `intermittent shedder`. Intermittent shedding is especially dangerous because a trusted recovered person can seed a fresh internal outbreak.

## `CHAT-II-075` — Rabbit / compact livestock
Rabbits are a strong base-husbandry candidate because they are compact and make closed-herd/quarantine, feed, water, cleaning, slaughter and butchering understandable without a huge farming simulation.

## `CHAT-II-076` — Butchering vs cooking risk
A strain can allow:
`infected animal → raw blood/tissue dangerous → properly cooked meat safe`.
Other strains can break one of these links. This is a useful research-backed policy question, not a fixed universal recipe.

## `CHAT-II-077` — Finite-population survival scenario
Special scenario: winter/isolated region/host-range limitation suppresses animal reservoir and external replenishment. Existing infected are genuinely finite; strategic goal can be to survive until they starve/die while managing hidden conserved pockets.

## `CHAT-II-078` — Photosynthetic / symbiotic support
Distant exotic idea only. If used, treat as unusual symbiotic biology that slightly supports long dormancy, not baseline energy source for active infected.

## `CHAT-II-079` — Residual municipal water
First-demo candidate: taps still run because local pressure/storage persists, but drinking confidence is degraded. Technical use remains possible; drinking requires confirmed treatment. Long-term reliability declines with infrastructure failure.




## `CHAT-II-080` — Disease transmission / host network screen
Disease UI can visually borrow the readability of a spread-map/tree without becoming a mutation-purchase screen. Nodes/rows: blood, surface, air, water, food, flies, mosquitoes, rabbits, rats, dogs, birds etc. Each shows known/unknown, evidence sources, confidence and unresolved contradictions.

## `CHAT-II-081` — Evidence-quality ladder
A practical evidence hierarchy:
`anecdote/report → direct field observation → recorded observation → professional sample/exam → controlled test → repeated/control test`.
It should remain possible for several weak observations to become interesting without pretending that every seen event proves causation.

## `CHAT-II-082` — Test hypothesis research job
Player selects a question; qualified staff turn it into an experiment if the required subjects/materials/setup exist. The player chooses **what to investigate**, not each laboratory animation. Repetition/control can improve evidence quality.

## `CHAT-II-083` — Research-subject upkeep
Living infected kept for science consume isolation capacity, water, food/physiological support, security, sanitation and staff time. Starvation/exhaustion may reduce the quality of behavioural evidence when the research question expects a normally supported subject.

## `CHAT-II-084` — Scientific justification as social information
Policies/actions are not blocked by evidence. Specialists can nevertheless judge them as `well supported / precautionary / weakly supported / unsupported / contrary to evidence`. Their opinions propagate through normal communication and can affect procedural trust through concrete conversations/rumors.

## `CHAT-II-085` — Bite inspection
Configurable medical procedure:
`inspect for mosquito bites / animal bites / other exposure marks`.
Can be part of a transition шлюз, post-raid check, exposure response or scheduled examination inside a sector.

## `CHAT-II-086` — Mosquito vector dimensions
Keep separate:
`blood-meal acquisition`,
`time to detectable infection/amplification`,
`ability to reach transmissible state`,
`delay before transmission`,
`typical exposure strength per bite`.
No fixed numbers/rarity/balance are accepted yet.

## `CHAT-II-087` — Laboratory mosquitoes as diagnostic amplification
Late speculative idea: purpose-bred laboratory mosquitoes feed on a suspected subject under controlled conditions, then are tested later. This has a real gameplay purpose **only if a current strain becomes detectably infected/amplified in mosquitoes earlier than direct human testing becomes reliable**. It is not baseline and may be rejected after biology/balance research.

## `CHAT-II-088` — Abstract vector pressure and counterplay
Do not simulate every mosquito. Candidate room/local state depends on outdoor density, openings, screens, standing water, traps/treatment and traffic through doors. Needed mainly to prevent vector transmission from becoming invisible random punishment.

## `CHAT-II-089` — Hidden susceptibility / resilience / exposure history
Internal model may separate:
- strain-specific susceptibility;
- temporary resilience/state;
- specific acquired protection;
- recent dose/history.
Player sees evidence and medical interpretation, not an exact immunity HP bar.

## `CHAT-II-090` — Post-exposure prophylaxis under uncertainty
A limited drug/treatment can reduce establishment/severity after some low/moderate exposures if given early. Because exact infection/susceptibility is hidden, the decision to spend a dose can remain uncertain. Exact mechanism and effectiveness are strain/research dependent.

## `CHAT-II-091` — Ordinary illness and co-infection
Common viral/bacterial/wound illnesses can:
- imitate main-strain symptoms;
- complicate diagnosis;
- for some strains worsen acquisition/course;
- for others temporarily interfere/protect;
- or have no meaningful interaction.
No universal `common cold = immunity penalty` rule.




## `CHAT-II-092` — Shared tactical command language
Raid and base response should reuse move/hold/watch/open/close/lure/light/retreat/carry-type commands and the same weapon/skill/stress logic.

## `CHAT-II-093` — Quiet perimeter cleanup
Routine base defense can include picking off isolated wandering infected from a protected position with low-noise ranged tools (crossbow-like candidate) or limited melee. This supports the idea that major combat peaks happen elsewhere rather than every normal day at the gate.

## `CHAT-II-094` — Dark unexplored wing
A strong local exploration setup:
`known safe boundary → dark unverified corridor → listen / light / lure → cover doorway → enter → room-by-room check`.
It can teach tactical controls before the first external raid.

## `CHAT-II-095` — Clear threat, then find the breach
After killing infected in an unverified area, team may discover why they were there: broken window, hole, drain, maintenance trench or utility access. Reclaim requires physically closing the source, not only killing current occupants.

## `CHAT-II-096` — Incomplete alarm report
Alarm UI should preserve source and uncertainty:
`Source: guard / resident / worker`
`Observed: sound / glass / figure / blood / animal`
`Threat classification: unknown/suspected/confirmed`.
The incident can escalate as more reports arrive.

## `CHAT-II-097` — Sector emergency plan
Each sector can store primary evacuation route, reserve route, shelter/refuge destination, guard response and boundaries intended to close/open during an alarm.

## `CHAT-II-098` — Emergency drills
Running a drill consumes time and temporarily interrupts work. Possible benefit: faster route compliance, less hesitation/crowding and better response-position execution. Avoid a required spammy drill schedule.

## `CHAT-II-099` — Rapid sector actions
Candidate context UI:
`Evacuate A / Evacuate B / Shelter / Seal Sector / Compartmentalize / Open Evac Corridor / Security Response / All Clear`.

## `CHAT-II-100` — Shelter-in-place trade-off
If a fast infected is loose in a shared corridor, evacuating everyone can feed it a dense stream of targets. Closing ordinary room doors and holding residents in place can buy time for response squad. Fire/smoke/environmental contamination may invert the correct answer.

## `CHAT-II-101` — Diverse penetration alarm events
The same alarm framework can represent:
- infected human through window/breach;
- special climber/digger;
- infected rodent/bird/other animal;
- insect/vector incursion;
- human raider/intruder;
- unknown nighttime noise that turns out harmless or serious.
Exact event frequencies remain balance/content work.

## `CHAT-II-102` — Remote vs manual closures
Some shutters/fire doors can close from control; others require a nearby person. A `Seal Sector` command therefore resolves through actual infrastructure and access rather than instant global magic.


---

# 6. Cross-system picture

```text
ФИЗИЧЕСКАЯ БАЗА
rooms / doors / barriers / КПП
        │
        ├───────────────┬────────────────┐
        ▼               ▼                ▼
      ЛЮДИ           ПРЕДМЕТЫ         ИНФОРМАЦИЯ
 risk/status        clean/risky       кто что знает
 skills             owner/history     приказ/слух
 personality        route/decon       latency/confidence
 needs                  │                │
        └───────────┬───┴───────┬────────┘
                    ▼           ▼
                 ПРАВИЛА     ПРОИЗВОДСТВО
                 access      food/water
                 distance    energy/heat
                 route       clothes/tools
                 ration      medicine
                    │           │
                    └─────┬─────┘
                          ▼
                       РЕШЕНИЯ
           рискнуть / изолировать / скрыть /
           принудить / пожертвовать / исследовать
                          │
                          ▼
                      ПОСЛЕДСТВИЯ
                          │
                    новые наблюдения
                          ▼
                   новое знание о вирусе
                          ▼
                 новые правила и новая база
```

Игрок проектирует одновременно **физическую, производственную, санитарную, информационную и социальную систему разделения людей**, а затем наблюдает, выдержит ли она реальную жизнь.

Новый важный слой:
`наблюдения/доклады → personnel dossier → confidence в человеке → доступ/должность/зелёная зона`.
Параллельно:
`частная собственность → обмен → санитарные правила → физическая передача/decon → социальные последствия`.

Opening/run progression добавляет ещё две цепочки:

`pre-run trusted core + generated newcomers → intake / assessment → работа и наблюдение → trusted specialist / promotion / green access`

`маленькое clean core → очистка / контроль / reclaim → больше usable territory → более устойчивая база → внешние экспедиции / новые люди / новые риски`

Политический слой:
`оружие + привилегии + правила + безопасность близких + legitimacy → основания лояльности → способность enforce решения во время кризиса`.

Новый opening/intake layer:
`OUTSIDE / RETURNING RAID → configurable шлюз → evidence/report ready → decision → sector / specialist шлюз / holding / refuse`

`грязное пространство → sanitation work + closure → usable route`

`visible capability goal + approaching migration → hurry / preparation trade-off → raid before window closes → new system unlocked`

Security связывает правила и геометрию:
`zone boundary + policy → checkpoint → voluntary compliance / enforcement`.

Threat/ecology layer:
`animal/environment reservoir → new human infection → fresh outbreak → acute containment crisis → blood/corpses → sanitation`

`regional infected pool → attraction/aggregation → horde/perimeter loss → migration/dissipation/death`

`vegetation/animal food → infected herbivore/feed animal → old infected energy → prolonged external pressure`

Food-production layer:
`closed livestock → slaughter/butchering → strain-dependent raw risk → cooking/policy → safe/unsafe food`.

Disease-knowledge layer:
`field observations / records / samples / experiments → evidence quality → expert assessment`

`expert assessment + leadership risk tolerance → independent policy/action → staff judgement / rumors / outcomes → new evidence`

Важно: стрелка `assessment → policy` **не автоматическая**.

Vector layer:
`blood/corpse/host → insect acquisition → possible amplification/transmission → low/high-dose exposures → hidden susceptibility/history → infection outcome`.

Tactical/exploration layer:
`strategic raid planning → direct small-squad site control → injury/loot/contamination → return intake`

`unexplored facility → listen/light/lure/recon → threat/breach discovery → combat/closure → sanitation/reclaim`

Emergency layer:
`witness / sound / sensor → partial alarm report → prepared plan or player override → evacuate / shelter / seal / response → containment outcome`

`drill/rehearsal → better emergency execution`, но не faster magical command delivery.

---

# 7. Key anti-fun / production risks

1. **Route micromanagement:** нельзя вручную рисовать каждое обычное перемещение.
2. **Information-sim explosion:** нельзя непрерывно считать beliefs каждого о каждом; нужна event-driven модель и значимые отношения.
3. **Bureaucracy as spreadsheet:** наблюдение/учёт должны поднимать исключения, а не требовать читать сотни строк.
4. **Production sprawl:** нельзя превращать проект в полноценный Factorio/RimWorld production tree.
5. **Perfect quarantine dominant strategy:** изоляция должна иметь реальную экономическую/социальную цену.
6. **Random infection punishment:** неизвестность должна оставлять доказательства и возможность понять ошибку.
7. **Perfect late-game containment:** поздние технологии не должны полностью убрать интересные trade-offs.
8. **Too many overlays:** основной режим должен оставаться живым зданием.
9. **Realism without decisions:** вода, гигиена, одежда и топливо нужны там, где создают интересный выбор.
10. **Opaque personality = random punishment:** если поведение объяснимо только hidden traits, игрок перестанет воспринимать людей как симуляцию. Базовые needs и значимые отношения должны давать читаемые причины.
11. **Permanent skill fog:** когда специалист уже давно проверен, игра не должна продолжать изображать, что мы ничего о нём не знаем; progression должен стать наблюдаемым.
12. **Informant dominance:** если психолог-информатор всегда лучше обычного психолога, этическая/социальная развилка исчезает. Конфиденциальная помощь должна иметь самостоятельную ценность.
13. **Trade bookkeeping:** внутренний обмен не должен заставлять вручную регистрировать каждую мелкую вещь; правила и автоматизация должны брать рутину на себя.
14. **Custom-core kills uncertainty:** если игрок может создать почти всё население, people-discovery system теряет смысл; customization должна быть ограничена trusted core.
15. **Balance score leaks secrets:** нельзя показывать разбивку start score так, чтобы из неё вычислялось скрытое заражение/trait.
16. **Static-map solved puzzle:** фиксированный facility хорош для демки, но full-game replayability позднее может потребовать несколько shells или variable operational state.
17. **External game eats the colony sim:** global map/raids не должны превратиться во вторую более дорогую tactical game и вытеснить base-management core.
18. **Politics before survival:** loyalty/governance systems должны объяснять реальные security decisions, а не требовать отдельной сложной политической панели с первой минуты.
19. **Goal spam:** personal future stakes должны быть редкими/значимыми и поднимать решения, а не превращаться в бесконечный список мелких квестов.
20. **Fixed intake recipe:** нельзя превращать player-built шлюзы в обязательную hidden tutorial-схему `сначала yellow, потом red`; specialization должна быть выбором архитектуры.
21. **Intake click-fest:** работник собирает evidence и поднимает `report ready`; routine cases должны уметь идти по policy автоматически.
22. **Wait-until-outcome dominance:** если заражённого всегда выгодно держать связанным до окончательного исхода, исчезают тяжёлые решения. Isolation/sanitation/security cost и limited capacity должны иметь вес.
23. **Covert execution disappears:** recovery/research value не должны вытеснить signature situation тайного устранения; она должна оставаться доступной и иногда рациональной, но не forced.
24. **Guard manpower sink:** нельзя требовать по два охранника у каждого временно закрытого коридора. Signage/voluntary compliance/automation должны снимать routine load.
25. **Emergency holding is free safety:** быстрый впуск толпы должен переносить внутрь реальные contact/security/political risks.
26. **Migration as scripted timer attack:** внешняя масса должна реагировать на attention и оставлять последствия, а не просто приходить строго потому, что таймер дошёл до нуля.
27. **Terminal certainty kills drama:** слишком точный `cannot recover` flag может ослабить моральную/информационную силу казни; confidence model нужно проверять на игре.
28. **Oversized map before density:** несколько зданий и огромная карта не нужны, пока одно крупное facility не даёт достаточно решений и живой плотности.
29. **Infinite-zombie handwave:** бесконечный spawn/вечная энергия подрывают world logic; нужна конечная regional population и понятная ecology.
30. **Ecology simulator eats the game:** не считать калории каждого заражённого, популяцию каждого вида и полный food web. Достаточны coarse states/flows, которые создают player decisions.
31. **Special-infected checklist:** retained-function variants не должны превращаться в обязательный набор gamey monsters.
32. **Fresh infected trivialized:** если recently turned опасен не сильнее старого, carrier/animal outbreak теряет главный смысл.
33. **Horde as weather:** если масса лишь блокирует рейд и потом уходит, она недостаточно страшна; perimeter loss и breach opportunities должны быть реальными.
34. **Door-HP combat:** generic damage bars не должны заменять spatial/containment decisions.
35. **Combat without cleanup:** если после убийства всё мгновенно безопасно, blood/sanitation core не работает.
36. **Animal = always kill:** если любое животное всегда опасно одинаково, discovery и livestock decisions схлопываются.
37. **All recovered are carriers:** если выздоровевшего никогда рационально не возвращать, recovery system теряет человеческую ценность.
38. **Livestock farming sprawl:** rabbits/animals должны поддерживать infection/food decisions, а не требовать отдельную глубокую Ranch Simulator.
39. **Cooking as magic button:** meat safety зависит от current-strain evidence; игра не должна автоматически утверждать, что heat всегда решает любой fictional pathogen.
40. **Science as quiz:** нельзя заставлять игрока угадывать научную истину вместо специалистов только ради minigame.
41. **Theory-policy magic:** принятие working assumption не должно молча перенастраивать все шлюзы/здания/правила; это current non-goal.
42. **Evidence is all-seeing:** увиденное игроком событие не должно автоматически становиться perfect scientific evidence без источника/фиксации/контекста.
43. **Unsupported policy has no social meaning:** если компетентные специалисты располагают данными, их согласие/несогласие с тяжёлыми мерами должно иметь возможность существовать в information/social simulation.
44. **Mosquito random punishment:** ubiquitous invisible bites + hidden infection rolls без controllable vector pressure сделают систему unfair.
45. **Mosquito overcommitment:** не фиксировать prevalence, bite counts, vector competence или dose balance до отдельного pass.
46. **Immunity HP:** скрытая восприимчивость не должна превращаться в непрозрачную regenerating health bar, которую игрок не может интерпретировать.
47. **Co-infection simulation sprawl:** обычные болезни нужны для диагностической неоднозначности и редких strain interactions, а не для полного медицинского симулятора.
48. **Raid becomes second game:** direct tactical raid не должен требовать отдельного огромного RTS/shooter ruleset; reuse base-response systems.
49. **Tactical micromanagement:** direct squad control не означает ручное прицеливание каждой пули, индивидуальный facing every second или десятки stance buttons.
50. **Unexplored-space contradiction:** local dark/unverified spaces не должны незаметно вернуть global physical fog на уже освоенную базу.
51. **Darkness as arbitrary ambush:** игроку нужны слышимые/видимые clues, light/lure/retreat options и возможность осторожной разведки.
52. **Alarm spam:** не каждое событие должно превращаться в full-base emergency popup; нужны severity/scope and local handling.
53. **Perfect alarm knowledge:** тревога не должна автоматически раскрывать точный тип/число врагов, если свидетель этого не знает.
54. **Evacuation is always correct:** shelter/hold/sector seal должны иногда быть разумнее массового движения людей.
55. **Emergency plan autopilot:** plan помогает исполнению, но не должен гарантировать идеальную реакцию вопреки personality, blocked routes, damage и фактической угрозе.
56. **Drill chore:** rehearsals должны быть редким preparedness investment, а не ежедневной обязательной кнопкой.
57. **Magic sector seal:** high-level command обязан разрешаться через реальные doors/shutters/people/damage and may fail partially.
58. **One-button sacrifice without readability:** seal/lock actions, способные оставить людей с угрозой, должны ясно показывать кто остаётся внутри и какие выходы реально закроются.

---

# 8. Important-information preservation audit

## Сохранено и явно присутствует

- центральная дилемма «нужный работник / возможный носитель»;
- защищённое ядро без прямого контакта;
- пользовательские зоны вместо фиксированных трёх;
- подготовка блокировки до вспышки;
- crowd-pressure как модель разрушения;
- containment / evacuation / cleanup trade-off;
- personality, эмоциональные нарушения и человеческое легкомыслие;
- внутренняя охрана;
- социальная и биологическая иерархия;
- разные исходы заражения и носительство;
- меняющийся штамм;
- наблюдатели/бюрократия;
- disease knowledge/hypothesis model;
- внешние группы;
- правосудие/казни;
- скрытие и распространение информации;
- human experiments / research;
- disease notebook;
- ключевой подозрительный-инженер demo candidate;
- атаки как возможная проверка quarantine architecture;
- imperfect tests / evidence trail.
- no-command-latency baseline;
- physical map readability separated from uncertainty about people;
- private ownership distinct from mere contamination state.

- limited customizable trusted core + generated unknown population;
- start-quality concept with freedom to exceed intended balance;
- fixed first-demo building and pre-existing clean core;
- contact history as the basis of initial green confidence;
- blocked/dirty passages and a sealed infected wing at run start;
- Command Circle as top leadership distinct from sanitary green status;
- armed personnel not automatically green;
- loyalty grounded in family safety, privilege, fairness, personal bonds and institutional trust;
- police/patronage vs institutional governance preserved as non-binding future direction;
- global map / strategic expeditions / other bases;
- external infected migration and non-infinite-activity intuition;
- run/global-goal question with verified-safety progression candidate;
- personal future stakes / hopes.
- local capability-unlock objective in addition to abstract survival;
- approaching horde/migration as an opening time window;
- noise/attention can leave residual infected after the migration passes;
- sanitation workers for blood, corpses, surfaces and contaminated rooms;
- temporary sanitary closures and value of alternate corridors;
- configurable player-built шлюз rather than fixed yellow/red architecture;
- worker gathers inspection evidence → report ready → player/policy routes person;
- refusal of admission as a meaningful external decision;
- emergency dirty holding for fast mass admission under zombie pressure;
- own raiders processed on return, with different social stakes;
- main/service/emergency entrances as spatial candidates;
- boundary-integrated guard posts, free guard points, patrol and escort;
- armed arrivals require negotiation rather than automatic disarm;
- founders/existing group vs arrivals and mutual-aid integration;
- sector/sluice supply requirements and one-off logistics orders;
- sleeping/personal place + food/hygiene + work as a compatible life contour;
- food location as a sanitary/social decision;
- covert execution with limited witnesses and cover story;
- living infected/turned infected as research evidence/resources;
- probable terminal-course knowledge and uncertainty-vs-drama conflict;
- direct high-dose exposure / rapid course / possible masked vitality as strain candidate;
- revised population playtest hypothesis around 30–40;
- one large facility + immediate exterior as current demo map-size hypothesis; multi-building compound deferred.
- water purification does not collapse into universal `filter + boil`;
- fresh infected as acute high-speed threat;
- old/conserved infected as low-activity mass;
- horde formation stages and finite regional pool;
- possibility of deliberately attracting infected away from another location;
- perimeter spread, alternate-entry search and loss of external shell;
- body piling/climbing as geometry/strain candidate;
- digging/foraging infected that may undermine fences/expose technical paths;
- retained simple tool-use/motor behaviours as rare strain candidate;
- short-range cough/spit/blood-fluid threat as strain candidate;
- combat blood/corpses as sanitary debt and possible secondary contamination;
- flies/mechanical vectors preserved as strain candidate;
- prepared internal refuge points;
- baseline low-activity/scavenging/cannibalism energy ecology;
- baseline infected herbivores/feed animals with reduced fear;
- variable rats/birds/dogs animal-host role by strain;
- recovered cleared vs persistent/intermittent shedding;
- rabbit/small-livestock production candidate with closed herd;
- raw butchering risk separated from cooked-meat safety;
- special finite-population survival scenario;
- photosynthetic/symbiotic support preserved only as distant exotic idea.
- evidence separated from scientific assessment, leadership assumptions and enacted policy;
- no automatic theory→policy/building reconfiguration in current direction;
- field observation, recordings and controlled/repeated experiments can carry different evidence weight;
- specialists can judge scientific justification of harsh policies and spread disagreement through normal information channels;
- hypothesis testing as a research job rather than manual laboratory micromanagement;
- living infected research subjects consume food/water/security/sanitation capacity;
- bite inspection for mosquitoes/other potentially infectious animals in шлюз and routine medical checks;
- mosquito ecology split into acquisition, detectability/amplification, transmission competence, delay and exposure strength;
- mosquito numerical balance intentionally deferred;
- laboratory-mosquito early-detection/amplification preserved only as late speculative technology;
- hidden strain-specific susceptibility separated from current resilience/specific protection/exposure history;
- multiple low-dose exposures may matter without a visible immunity HP bar;
- post-exposure prophylaxis under uncertainty preserved as treatment candidate;
- ordinary diseases can mimic symptoms and interact with current strain differently between runs.
- direct tactical control of a small squad on raid sites;
- strategic route/loadout/objective planning retained around tactical raids;
- shared tactical command language between raid team and base emergency response;
- routine base combat can remain sparse/controlled while raids/unexplored areas provide stronger combat peaks;
- physically unexplored dark parts of the main building without reverting to global camera-fog;
- listening/light/noise/lure/cover as exploration verbs;
- hidden physical breach as something to discover and repair after clearing;
- alarms sourced from partial witness/hearing reports rather than perfect threat knowledge;
- sector emergency plans with primary/reserve evacuation and shelter instructions;
- drills/rehearsal as preparedness investment;
- high-level room/sector emergency commands;
- distinction between `lock room`, `seal sector`, `shelter in place` and evacuation;
- `Seal sector` constrained by actual closable infrastructure;
- alarms can represent infected humans, special variants, animals/rodents/birds, insects/vectors and human intruders.

## Было слишком сжато или не имело ясного владельца — восстановлено

- **рабочий карантин / sealed work cohorts** → `CHAT-II-029`;
- **зачистка как многоэтапное возвращение сектора, а не только бой** → `CHAT-II-030`;
- **sanitary transfer/decon как throughput и экономическая цена** → `CHAT-II-031`;
- потерянный сектор как долгосрочный «шрам» базы усилен внутри `CHAT-PI-006`.

## Исправлены внутренние несогласованности v0.4

- old top index не отражал `PI-016–022`; current index теперь отражает `PI-001–057`;
- `CHAT-II-001` теперь однозначно superseded пользовательскими зонами;
- `CHAT-II-002` больше не выглядит как принятое требование полной air simulation;
- принятые v0.4 extensions сведены в смысловые тела;
- visual category больше не пустая: `CHAT-PI-023` preliminary accepted.

---

# 9. Immediate next passes

1. **Tactical-control pass:** exact squad size, pause/time model, move/watch/hold/open/lure/light/retreat commands, combat abstraction and reuse between raid/base response.
2. **Unexplored-space pass:** first-demo dark wing topology, what plans reveal, local hearing/vision, lighting, lure behaviour, hidden breach and reclaim.
3. **Alarm/emergency pass:** report severity/uncertainty, who raises alarms, prepared plans, evacuation A/B, shelter, seal/compartmentalize, response squad and all-clear.
4. **Emergency-drill pass:** what rehearsal improves, cost in work time, failure/blocked-route behaviour and anti-chore limits.
5. **Disease-screen / evidence pass:** transmission/hosts/vectors, evidence source/quality and expert assessment.
6. **Threat/horde pass:** fresh vs old infected, barrier states, perimeter aggregation, windows/alternate entrances, climbing/piling/burrowing.
7. **Ecology / vectors / husbandry pass:** animal reservoirs, insects, rabbits, bite checks and keep mosquito numerical balance open.
8. **Opening/intake pass:** combine arrivals, configurable шлюз, first exploration/acute alarm, capability objective, tactical raid and migration warning.
9. **Sanitation/security/population pass:** cleanup, refuge points, checkpoints, response staffing and test `30–40` people in one large building + exterior.
10. **После этого:** detailed frame-by-frame demo-run, then final core/session-loop formulation.


---

# 10. Terminology convention

Чтобы draft не зависел от необъяснённых англоязычных сокращений:

- **СИЗ / PPE (Personal Protective Equipment)** — средства индивидуальной защиты: перчатки, маска/респиратор, очки, халат/комбинезон и другие защитные слои;
- **обеззараживание / decon (decontamination)** — санитарная обработка человека, предмета или пространства; это не обязательно «облить химией», а набор процедур вроде снять грязную одежду, помыться, обработать/изолировать вещи;
- **первичная сортировка / triage** — быстрая оценка срочности медицинской помощи;
- **зона приёма / intake** — место, где внешних/возвращающихся людей принимают, проверяют и распределяют;
- **holding** — временная контролируемая зона ожидания; в русском тексте предпочтительно `зона ожидания / временное размещение`, если английское слово не делает схему короче;
- **checkpoint / guard post** — соответственно контролируемый переход и свободный охранный пост.

Дальше в design text предпочтительны русские термины; английские слова остаются там, где они уже стали короткими working labels.

---

# 11. v0.6 knowledge-model transformation

### Current

`CHAT-PI-018` одновременно связывал player commands и обычную информацию через одну transmission model и предполагал latency радио/телефона/гонцов. `CHAT-PI-034/035` описывали character data и pawn beliefs без чёткого решения, насколько эти данные знает сам игрок.

### Incoming

- preliminary отказаться от задержки player commands;
- для первой демки сделать знание игрока примерно как в классическом colony sim;
- сохранить скрытый истинный infection state;
- потенциально скрывать отдельные вещи: полный инвентарь, источник слуха, правдивость показаний, преступление;
- отдельно сохранить более радикальный вариант, где personality/skills/feelings тоже являются неполным source-based знанием.

### Resulting

- `CHAT-PI-018` теперь владеет **распространением информации среди жителей**, а не доставкой player commands;
- новый `CHAT-PI-036` фиксирует preliminary demo baseline: classic colony-sim operational knowledge + no command latency;
- новый `CHAT-PI-037` сохраняет mutually exclusive epistemic alternative;
- `CHAT-II-016` частично superseded;
- `CHAT-II-017` и `CHAT-II-025` остаются future communication ideas;
- добавлены `CHAT-II-032` search/hidden inventory, `CHAT-II-033` abstract hidden crime и `CHAT-II-034` source-based personnel dossier.

Repository integration не выполнялась.


---

# 12. v0.7 people / property / trade transformation

### Current

- `CHAT-PI-036` давал почти полный classic colony-sim character knowledge;
- `CHAT-PI-037` хранил discoverable personality/skills как альтернативу;
- `CHAT-PI-029` в основном рассматривал личные вещи через contamination/ownership;
- psychologist/informant intelligence и внутренний обмен не имели самостоятельных owners.

### Incoming

- принять, что физическая карта остаётся прозрачной, но человек познаётся постепенно;
- не скрывать очевидные needs/relations настолько, чтобы personality simulation стала случайной;
- skills сначала могут быть недостоверны, но после проверки должны давать читаемый progression;
- ценность проблемного человека сохраняется через skills, отношения и накопленное доверие/знание;
- добавить психолога как возможный глубокий источник информации и информаторов внутри коллектива;
- добавить частную собственность как экономическую сущность, обмен/торговлю и санитарные правила направления передачи;
- сохранить посетителей/торговую пограничную зону как далёкую идею.

### Resulting

- `CHAT-PI-036` теперь current hybrid: **omniscient space / uncertain people**;
- `CHAT-PI-037` сужен до radical camera/trusted-observer physical-vision alternative;
- обновлены `CHAT-PI-004`, `011`, `015`, `017`, `020`, `029`, `034`, `035`;
- добавлен `CHAT-PI-038` — dossiers / trust / human intelligence;
- добавлен `CHAT-PI-039` — internal trade / regulated exchange;
- `CHAT-II-034` absorbed into `PI-038`;
- добавлены `CHAT-II-035–039` для психолога, информаторов, skill discovery, directional exchange и visitors.

Repository integration не выполнялась.


---

# 13. v0.8 run-start / world / goals transformation

### Current

В `v0.7`:
- чистое ядро уже существовало концептуально, но не было объяснено, **как оно выглядит в нулевую минуту рана**;
- demo-run/victory/failure оставались почти полностью открыты;
- не было owner для pre-run customization и balance generation;
- `PI-012/013` описывали охрану и иерархию, но не разделяли санитарный статус, власть, доверие и оружие;
- `PI-007` сохранял формат рейда неопределённым;
- personal future goals не имели owner.

### Incoming

- игрок может создать ограниченный trusted/green core до старта, но не остальных жителей;
- старт должен быть objectively playable/balanced через coverage + quality, при этом unbalanced custom runs разрешены;
- для демки clean core уже существует в фиксированном здании, а новые люди находятся в intake/perimeter;
- исходный green status подтверждается contact history;
- с нулевой минуты есть завалы, dirty passages и небольшое запечатанное infected wing;
- верхушка — один/несколько top-level leaders без начальника над ними, с общим official information contour;
- вооружённые люди не обязаны быть green; loyalty имеет конкретные основания;
- police/patronage и institutional society сохраняются как future emergent trajectories;
- global map / raids / other bases развиваются в сторону strategic expedition layer;
- outside infected pressure может мигрировать и иметь low-activity periods;
- открыта формулировка global goal и принят candidate progression through verified safety;
- каждому человеку может принадлежать future stake / hope.

### Resulting

- обновлены `CHAT-PI-004`, `006`, `007`, `010`, `011`, `012`, `013`, `015`, `018`, `038`;
- добавлены `CHAT-PI-040–046`;
- `CHAT-II-006` повышен из historical/deferred raid alternative до current preferred strategic candidate;
- добавлены `CHAT-II-040–047`;
- full frame-by-frame demo всё ещё не зафиксирован, но его opening state и первые задачи теперь имеют coherent preliminary structure;
- procedural building generation, точная zombie physiology, governance simulation и final victory condition остаются открытыми.

Repository integration не выполнялась.


---

# 14. v0.9 intake / sanitation / opening-pressure transformation

### Current

В `v0.8`:
- opening phase уже имел trusted core, arrivals, fixed facility, sealed infected wing и strategic expedition direction;
- global objective оставался общим `stabilize / expand verified safety`;
- sanitation была распределена между водой/гигиеной, предметами и reclaim, но не имела owner для крови/трупов/temporary closures;
- `PI-012/043` описывали security/loyalty, но не было concrete guard-command system;
- intake существовал как starting-fiction concept, но не как player-built configurable transition architecture;
- `II-040` всё ещё предлагал `18–24` people;
- covert execution была лишь частично видна через `force can be hidden`.

### Incoming

Из одобренных сообщений после `v0.8`, с приоритетом последней формулировки по каждой теме:

- visible local objective должен открывать новый gameplay capability;
- скоро проходит large infected migration, создавая окно для raid/preparation; attention может оставить заражённых у базы после прохода;
- нужны sanitation workers, environmental cleanup, blood/corpses и временные closures;
- шлюз — player-placeable/configurable check/processing point;
- fixed `yellow/red` gates **не являются architecture**; это только возможная специализация;
- worker finishes configured assessment → `report ready` → player/policy routes person;
- возможны reject admission, deep interview, heavy cleaning, specialist bays, emergency dirty holding;
- returning own raiders проходят ту же physical process, но социально отличаются;
- можно иметь несколько entrances;
- checkpoint создаётся на boundary zones; также нужны free guard posts, patrol, escort/reserve;
- armed arrivals требуют negotiation;
- starting population likely needs to be larger; current playtest range `30–40`;
- initial existing/arrival group identity может меняться через mutual aid;
- sector/sluice should request supplies rather than require manual item-by-item hauling;
- после admission важен compatible life contour: personal sleeping place, food/hygiene and then work;
- food location itself creates contact trade-offs; recreation can come later;
- living infected / turned infected can be research resources;
- direct bite/blood-to-wound can be high-risk rapid course candidate;
- disease knowledge may identify probable terminal course;
- covert execution must remain a strong possible situation;
- explicit open tension: greater certainty can make execution rational but may weaken its drama;
- current demo map candidate: one large building plus immediate exterior; multi-building compound later.

### Resulting

- updated owners: `CHAT-PI-005`, `007`, `010–014`, `017`, `019–022`, `025`, `026`, `030`, `032`, `035`, `041`, `043–045`;
- added `CHAT-PI-047–050`;
- revised `CHAT-II-040`;
- added `CHAT-II-048–061`;
- added terminology convention so `PPE/decon/intake/checkpoint` are not unexplained;
- previous mandatory-looking `yellow/red` gate interpretation is explicitly superseded by configurable шлюзы; yellow/red specialization remains only a player tactic/example;
- covert execution is now explicit in current meaning rather than only implied;
- full frame-by-frame demo is still not frozen, but the design now has a concrete opening pressure, intake architecture, sanitation layer and security verbs from which to build it.

Repository integration не выполнялась.


---

# 15. v0.10 infected-ecology / combat / animals transformation

### Current

В `v0.9`:
- migration was mainly a strategic time window and residual blocking threat;
- low-activity infected existed only as a broad biology candidate;
- `CHAT-II-058` held a narrow shooting/headshot candidate, but there was no full owner for combat/threat;
- blood/corpse cleanup existed, but not as a required consequence of combat;
- animal hosts, infected ecology and livestock had no semantic owner;
- water realism remained explicitly open.

### Incoming

Approved discussion after `v0.9` established/clarified:

- an external horde must be frightening beyond “stand at door, then leave”;
- local accumulation can self-amplify through attraction/herd behaviour while drawing from a finite regional infected pool;
- mass threat should spread around the perimeter, find alternate entrances/windows and potentially create vertical/ground routes;
- fresh infected are fast acute threats; old infected are conserved/low-activity threats; special retained-function variants are strain candidates rather than mandatory monster classes;
- piling/climbing, digging/foraging, simple tool use and short-range fluid projection are possible strain/variant behaviours;
- combat produces blood, bodies and contaminated space that must be cleaned;
- infected need an internally coherent long-term energy ecology rather than infinite activity;
- low activity, scavenging, cannibalism and animal feeding can sustain individuals/populations without making them immortal;
- infected herbivores/feed animals with reduced fear are a strong ordinary-run baseline;
- rats/birds/dogs and animal→human reservoir/vector roles should remain current-strain discovery;
- non-human infection as a general phenomenon need not be rediscovered from zero every run;
- animal reservoirs can generate new human infection and therefore dangerous fresh outbreaks long after original infected have aged;
- base husbandry, especially rabbits, is a strong production candidate;
- infected-animal meat can remain usable depending on strain; raw butchering and cooked-meat safety are separate questions;
- a special scenario without meaningful reservoir/support can make “outlive the finite infected population” the central objective;
- photosynthetic/symbiotic survival remains distant/exotic, not baseline;
- water treatment must distinguish microbiological from chemical contamination.

### Resulting

- updated `CHAT-PI-005`, `006`, `010`, `014`, `016`, `021–023`, `025`, `026`, `044`, `047`, `048`, `050`;
- added `CHAT-PI-051–053`;
- added `CHAT-II-062–079`;
- current ordinary-run ecology no longer depends on immortal infected;
- current horde model no longer depends on generic door HP or scripted timer attack;
- animal ecology and livestock now directly connect world plausibility, disease discovery, food production and fresh-outbreak risk;
- exact combat numbers, exact host species and first-demo inclusion of livestock remain prototype/open decisions.

Repository integration не выполнялась.


---

# 16. v0.11 disease-evidence / vectors / susceptibility transformation

### Current

В `v0.10`:
- `PI-021` still said that the player could manually adopt a theory and that rules/research would then rely on it;
- disease screen still showed a directly editable `Working policy` as part of the knowledge UI;
- evidence quality between anecdote, recording and controlled experiment was not explicit;
- experiments used humans/animals conceptually, but there was no clear `test hypothesis` job or upkeep/quality cost for research subjects;
- flies existed as a mechanical-vector candidate, but mosquitoes were not decomposed into distinct acquisition/transmission properties;
- mosquito balance, bite inspection, host susceptibility and ordinary-disease interaction had no consolidated current wording.

### Incoming

Approved discussion after `v0.10` clarified:

- good recorded research/behaviour evidence and expert interpretation should exist independently from leadership decisions;
- leadership can act with strong evidence, weak evidence or essentially without evidence;
- doctors/scientists may consider a policy unsupported and discuss it; that opinion can propagate through normal information/rumor systems;
- no current need for automatic `working theory → building/policy configuration`;
- no need to make the player manually guess a scientific answer when professionals can interpret the data;
- player can still choose what question to investigate and order a controlled hypothesis test;
- a seen event like an infected catching a rabbit is useful but ambiguous field evidence until better recorded/repeated/controlled;
- living infected kept for experiments require food/water and other containment resources;
- mosquito bites and other potentially infectious animal bites can be inspected in transition procedures or ordinary scheduled exams;
- mosquito danger should be decomposed into acquisition, detectable infection/amplification, actual transmission competence, delay and exposure strength;
- exact mosquito prevalence/bite/dose balance must remain open;
- using controlled laboratory mosquitoes as a faster biological amplification/detection method is only a late speculative idea, meaningful if mosquitoes become detectably infected earlier than direct human testing is reliable;
- individual susceptibility to the current strain can be hidden and distinct from general health;
- exposure can accumulate without a visible immunity HP bar;
- ordinary diseases can mask symptoms and interact differently with different strains;
- post-exposure prophylaxis under hidden infection/susceptibility remains a candidate, not fixed treatment balance.

### Resulting

- updated `CHAT-PI-014`, `015`, `017`, `021–023`, `035`, `049`, `052`;
- removed current implication that adopting a theory automatically rewrites rules;
- added `CHAT-II-080–091`;
- disease screen is now primarily a **knowledge/evidence interface**, not a science quiz or automatic policy engine;
- scientific justification can matter socially without blocking player authority;
- mosquito/vector systems are preserved in full conceptual breadth but deliberately **not numerically balanced/frozen**;
- laboratory-mosquito early detection is explicitly late/speculative;
- bite inspection is now compatible with both шлюз processing and normal medical scheduling;
- hidden susceptibility/co-infection ideas are preserved without committing to a visible immunity-stat system.

Repository integration не выполнялась.


---

# 17. v0.12 tactical-raids / alarms / emergency-response transformation

### Current

В `v0.11`:
- `CHAT-PI-007` and `CHAT-PI-044` still preferred mostly passive/strategic expeditions;
- `CHAT-II-006` described off-map strategic raids as current preferred;
- combat owner `PI-051` emphasized management-level containment but did not provide a direct small-squad raid mode;
- `PI-036` made the physical base transparent, without a clear exception for genuinely unentered/dark scenario space;
- first-demo facility had dirty/blocked/lost areas but no semantic owner for physically unexplored rooms;
- security had checkpoints/patrol/reserve, but no full alarm/prepared-response owner;
- sector sealing/evacuation existed conceptually but not as an explicit rapid command set.

### Incoming

Approved discussion after `v0.11` clarified:

- direct control of a raid squad is desirable because a well-managed base may intentionally have relatively little major combat;
- routine base defense can often remove isolated wandering threats from protected/quiet positions, while raids provide denser tactical danger;
- strategic preparation still matters, but on-site raid should allow literal squad control;
- raid squad and base response should preferably use the same tactical commands;
- the main building can contain a genuinely unexplored dark area with possible infected, holes/breaches and uncertain contents;
- in darkness the player can listen, lure, use light, cover an exit and investigate room by room;
- this local physical uncertainty should not restore global camera-dependent fog for the normal base;
- many problems should first appear as alarms from something seen/heard, with incomplete information;
- threat examples include fresh/special infected, window/breach entry, infected animals/rodents/birds, insects/vectors and human raiders;
- evacuation plans can be prepared in advance with primary/reserve routes and shelter behaviour;
- drills/rehearsal can improve emergency execution;
- player needs high-level room/sector actions such as evacuation A/B, shelter, seal, compartmentalize and security response;
- `Seal sector` should attempt to close all physically closable boundaries, not magically make a sector airtight;
- room containment and sector containment are distinct;
- shelter-in-place can be safer than evacuation when a fresh infected is loose in shared corridors.

### Resulting

- updated `CHAT-PI-005–007`, `010`, `012`, `018`, `036`, `041`, `044`, `050`, `051`;
- `CHAT-PI-007` is no longer `scope unresolved`: tactical direction is accepted while exact depth stays open;
- passive-only expedition language in `PI-007/044` is superseded by a strategic-planning + direct-tactical-site hybrid;
- added `CHAT-PI-054–057`;
- updated `CHAT-II-006` and `CHAT-II-045`;
- added `CHAT-II-092–102`;
- current transparent-space contract now explicitly permits local physically unexplored scenario areas without adopting `PI-037`;
- alarms, preparedness and rapid sector actions now have explicit owners;
- exact squad controls, alarm severity model, drill balance and first-demo choreography remain for dedicated passes.

Repository integration не выполнялась.
