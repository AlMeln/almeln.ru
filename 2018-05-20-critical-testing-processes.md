# Ключевые процессы тестирования

### Глава 1 "Панорамный обзор: роль тестирования в более широком контексте"

Перечень контрольных вопросов по результатам прочтения:
#### 1. Почему компании делают инвестиции в качество? Что мотивирует проводить тестирование?

Есть шесть пунктов. Правда пунктом №3 переведен очень и очень странно. 33/566:

> Даже искренне добиваясь высокого качества в ходе разработки системы, ее сопровождения и поставки, люди совершают ошибки. Эти ошибки снижают уровень качества системы относительно ожиданий. Разница между ожидаемым качество и получаемым качеством проявляется в рисках для компании-разработчика, а также для заказчиков, пользователей и других заинтересованных лиц.
>
> Эти риски могут мотивировать компанию на инвестиции, связанные с качеством, включая инвестиции в качество. В частности, организации могут направить усилия на:
>
> 1. Уменьшение общих затрат, связанных с проблемами качества
> 2. Повышение доверия к функциям системы
> 3. Снижение вероятности событий, угрожающих прибыли, достижению цели и даже жизни
> 4. Повышение репутации компании касательно качества самой системы и каества продуктов и услуг, которые она поддерживает
> 5. Получение повторных и связанных заказов от удовлетворенных работой компании заказчиков
> 6. Снижение числа судебных исков из-за дефектов системы (для компаний-разработчиков) и исков заказчиков (для контролирующих компаний)
> 7. Соблюдения планов-графиков, бюджетов или достижение целей, связанных с промышленными стандартами…
> 8. Повышение качества планирования, графиков и бюджетов для будущих проектов
> 9. ...
> 10. Снижение вреоятности несдачи системы заказчику, что может негативно сказаться на конкурентоспособности компании.ы

#### 2. Что такое качество? 

34/566:

> 1. Пригодность для использования. Наличие свойств, атрибутов и функций, удовлевторяющих ожидания заказчиков и пользователей, и отсутствие свойств, атрибутов и функций, неудовлетворящих ожиданиям пользователей.
> 2. Соответствие требованиям. Наличие свойств, атрибутов и функций, удовлевторяющих всем установленным требованиям, и отсутствие свойств, атрибутов и функций, отклоняющихся от требований.

#### 3. Что такое риски?

35/566:

> Это верояттные негативные результаты и события.

#### 4. Что делает эффективно организованное тестирование?

35/566:

> Предоставляет услуги и информацию, способствующие управлению рисками качества разрабатываемой, сопровождаемой или поставляемой системы.

#### 5. Что такое Опыт Качества?

35/566:

> Мнение о качестве системы вместе с общем уровнем удовлетворенности пользователей/заказчиков по мере получения опыта работы с системой. Когда уровень качества совпадает ожиданием качества заказчик обычно удовлетворён. Если опыт качества превышает ожидания, пользователь/заказчик восхищается. Если опыт качества ниже ожиданий, пользователь/заказчик разочарован.

#### 6. Тестирование это часть разработки или отдельный процесс?

 35/566:

> Процессы тестирования находятся в рамках проектов разработки, сопровождения или поставки системы.

#### 7. Чем жизненный цикл системы отличается от жизненного цикла разработки системы?

36/566. Понятие жизненного цикла системы шире понятия жизненного цикла разработки системы.

#### 8. Какие есть четыре основных наиболее ценных типа информации и услуг, поставляемых тестировщиками и для чего эта информация?

37/566:

> 1. Обнаружение ошибок, которые будут устранены, или даже предотвращение их внесения.
> 2. Обнаружение ошибок, которые не будут устранены, но о которых становится известно.
> 3. Проведение тестов, которые снижают (потенциально затратные) риски.
> 4. Обеспечение проекта своевременной, точной и заслуживающей доверия информацией.

#### 9. Что обеспечивает Группа тестирования?

37/566:

> Ее деятельность направлена на получение и обмен информацией, предназначенной для использования только внутри компании, то есть группа тестирования обеспечивает обратную связь с информацией о качестве системы и о проекте в целом.

#### 10. Что такое "ошибка, дефект" в понимании Рекса Блэка?

38/566:

> Проблема, которая вызывает или может вызвать неадекватное выполнение системой одного или нескольких обоснованных ожиданий качества заказчика/пользователя.

#### 11. Что такое тестирование по определению Рекса?

38/566:

> Функционально это процесс оценки качества системы, предоставления услуг и информации, позволяющий компании управлять рисками качества системы. Организационно это группа специалистов, предоставляющая данные услуги и информационные продукты для проекта, в котором она занята.

#### 12. Как организовать работу разных групп на различных фазах тестирования?

Только совсем непонятно, что за "сетевые операции". 39-40/566:

> Например, при разработке одной системы для массового рынка группа разработки проводила неформальное модульное и компонентное тестирование, группа маркетинга следила за ходом альфа и бета-тестирования, а группа тестирования под моим руководством проводила формальное комплексное и системное тестирование. Еще пример… Разработчики проводила формальное компонентное тестирование, группа тестирования выполняла формальное комплексное и системное тестирование, бизнес-аналитики и пользователи отвечали за неформальные приемо-сдаточные испытания, а сетевые операции подвергались пилотному тестированию.

#### 13. Приведёте классификацию Рэкса по фазам тестирования?

40/566

1. unit testing небольшого элемента или модуля системы
2. component testing компонентов системы и/или ее подсистем по отдельности
3. integration testing взаимосвязи и интефейсов между парами и группами компонентов
4. system testing поведения системы и ее функциональность
5. alpha testing внутренними или внешними заказчиками и пользователями в реальных условиях, на настоящих данных и в реальной среде
6. acceptance testing удовлетворения системы требованиям
7. pilot testing в виде опытной эксплуатации под тщательным наблюдением за возможностями системы по обработке типичных операций реальных пользователей на реальной аппаратуре

#### 14. К чему рано или поздно приводить привычка к большому риску?

41/566:

> Рано или подздно привычка к большому риску приводит к большим потерям.

#### 15. Что происходит с тем, кто не инвестирует в тестирование?

42/566:

> Компания поставляющая заказчикам системы либо с минимальным тестированием силами программистов, либо вообще без оного, наконец получает убийственный опыт, когда плохая версия становится предметом судебного иска, теряется важный заказчик, появляются плохие отзывы в прессе либо уходят наиболее ценные сотрудники.

#### 16. Чем QA отличается от тестирования?

43/566.

Считаем ли на работе общее количество найденных ошибок на очередном этапе разработки системы? 46/566

Происходит ли на рабочем месте рецензирование и утверждение тестов для модульного тестирования? 47/566

#### 17. Какие есть четыре группы рекомендуемых действий по снижению рисков в ходе тестирования?

Часть 1 "Планирование", Глава 2 "Основа успеха", "Группа тестирования Джамала проводит анализ рисков качества", 41-42 страницы:

> 1) Подробное тестирование - попытка тестировщиков в рамках проектных ограничений покрыть функции и свойства, относящиеся к этим рискам качества, как вширь, так вглубь. Готовя отчеты об ошибке, тестировщики должны потратить определенное время на воспроизведение и локализацию проблемы.
>
> 2) Сбалансированное тестирование - создаётся широкое, не обязательно глубокое покрытие тестами функций и свойств. Тестировщики должны ограничивать время на воспроизведение и локализацию проблем, основываясь на оценке серьезности и приоритетности ошибки.
>
> 3) Тестирование по возможности.
>
> 4) Информирование о наблюдаемых дефектах - не проектируются и не разрабатываются тесты для этих категорий рисков качество, но идёт информирование об обнаруженных ошибках.

1. Что означает первая интегральная сборка? 47/566
2. Почему мы не используем альфа-тестирование для некоторых тщательно отобранных партнеров по бизнесу? 48/566
3. Может ли повысить качество некачественного продукта за счёт тестирования? 48/566
4. Повторяю ли в ходе всего проекта встречи с руководством и коллегами для уточнения их ожиданий? 48/566
5. Как Рекс отнёсся бы к распределению тестировщиков, например по agile или scrum группам? Скорее так всего, поскольку 54/566, а затем 55-56/566
6. Какие проекты идут более гладко? Если программисты проводят модульное и компонентное тестирование своего кода. 55/566
7. Что такое фаза тестирования? 57/566
8. Как Рекс относится к организации тестировщиков в группы с программистами? 58/566
9. Используем ли на рабочем месте показатели эффективности и качества тестирования, отчетов об ошибках, процент исправленных ошибок длительность цикла существования ошибки? 60/566
10. Как Рекс описывает идею назначения тестировщикам младших программистов? 60/566
11. Какой есть признак незрелости разработки и какой должна быть организация тестирования? Ликвидация независимой группы тестирования и введение тестировщиков в группы разработки. 60/566
12. Читал ли и видел ли журнал "Software testing and quality engineering"? 63/566

#### Глава 2 "Основа успеха: анализ рисков качества"

Перечень контрольных вопросов по результатам прочтения:
1. Что же отличает области системы, которые мы *могли бы* тестировать, от тех областей, которые мы *должны* тестировать? 35/566
2. Что такое риски качества? 36/566 Потенциальный вид ошибки, способ поведения системы, при котором она, вероятно, не соответствует обоснованным ожиданиям качества системы, имеющися у пользователя или заказчика. Заметим, что риск качества - это потенциальный, а не обязательный результат с вероятностью больше нуля и меньше единицы.
3. Что включает в себя Процесс 3 "Процесс анализа рисков качества"? 37/566
4. Можете ли провести обзор существующих методик и методов анализа рисков качества? 38/566 
5. Сможете ли показать пример документации рисков качества в соответствии с выбранной методикой? 39/566
6. Сколько раз выполняли процедуру анализа рисков качества, расстановки приоритетов и выработку рекомендуемых действий? 
7. Есть ли у  на рабочем проекте документация с анализом рисков качества? В Confluence "Анализ рисков качества" и "Риски качества" = Ничего не найдено
8. Что за методика анализа рисков качества "Анализ видов ошибок и их влияния" (Failure Mode and Effect Analysis, FMEA)? 38/566
9. Ставится ли на рабочем проекте задача покрыть проверками весь разрабатываем функционал или определяетесь с областями системы, нуждающимисяся в тестировании?
10. Сможете привести несколько примеров общих категорий рисков качества , под которые могли подпасть отдельные виды ошибок? 39/566
11. Что за категория риска качества "удобство использования»? 39/566
12. А что за «конкурентные недостатки», как категория риска качества? 39/566
13. Рассматривается ли у вас на рабочем проекте не только такая характеристика видов ошибок как «приоритет», но и характеристики «серьезность» и «вероятность»?
14. Какая есть классификация Рекса Блэка значимости влияния ошибки для данного вида ошибок? 40/566
15. Чем приоритетность отличается от вероятности? Вероятность - это возможность возникновения ошибки данного вида и всех ее проявлений. Устанавливается на основании трёх факторов: 1) вероятности появления в системе, с точки зрения факторов технического риска - сложности и предыдущей истории дефекта; 2) вероятность пропуска ошибки разработчиками; 3) вероятности проявления в повседневном использовании, в текущих действиях пользователей или при инсталляции 40/566
16. Что такое приоритет риска и из чего он состоит, как его высчитать? Приоритетность - это значимость исправления ошибки основанная на: 1) влиянии данного вида ошибок на способность системы соответствовать требованиям пользователей; 2) проблемах в логике проекта; 3) несоответствии стандартам или инструкциям; 4) других соображениях, связанных с бизнесом. 41/566
17. 
18. При тестировании требований отвечаю задаю ли себе вопрос – какие области пропущенны в спецификации требований?
19. Сообщаю или о любых ошибках, обнаруженных в других проектных документах в ходе анализа, в том числе о неудачных и пропущеных требованиях, проблемах, связанных с архитектурой? 43/566
20. Высказали ли коллеги замечания, повышающие понижающие значение серьезности, приоритетности и вероятности?
21. Выполняю ли я согласование документа и получаю ли замечания коллег, прежде чем добавлять документа в проектный репозиторий? Или сразу выкладываю черновик и в реальном времени правлю, заставляя коллег получать лишнее уведомление об изменениях на свою электронную почту?
22. Какие девятнадцатый ролей в проекте могут быть привлечены для составления перечня рисков и более точной расстановки приоритетов? 46-47/566
23. В каких книгах можно найти списки ошибок программного обеспечения? Четыре перечня типичных дефектов системы можно найти в главе о систематизации дефектов в книге Бориса Бейзер (Boris Beiderbecke) «Software Testing Techniques», в приложении, содержащем перечень типичных ошибок, в книгах Сема Камера и др. (Cem Kaner et.al) «Testing Computer Software», Петера Неймана (Peter Neumann «Computer-Related Risks» и в списке рисков качества программных и аппаратных средств в книге Рэкса Блэка (Rex Black) «Managing the Testing Process, Second Edition». 48/566
24. Какие существуют методики для анализа рисков качества? Сможешь перечислить четыре штуки? 48/566
25. Вот вам программная система. Составьте список рисков качества системы, расставленных по приоритетам
26. Что означают приоритеты, присвоенные риском? Значение приоритетов определяют в основном необходимый объем тестирования. Обычно серьезные риски требует тщательного тестирования, риски средней степени нуждаются в ограниченном тестировании, не существенные риски не требует тестирования вовсе 50/566
27. Что за методика определения качества функциональности? Quality Functional Deployment, QFD. 50/566
28. Как начертить рамки анализа рисков качества тестируемый системы? Ответить на ключевой вопрос – является ли потенциальная проблема качества такой, что за ее обнаружение и исправление группа управление проектом готова расплачиваться дополнительными финансами на тестировании, ожидаемой прибылью или готова просто удалить эти свойства системы в случае задержки выпуска или поставки версии? 53/566
29. Где можно ознакомиться со способами рецензирования требований? 53/566. В книге Карла Вигерса
30. Имею ли я на работе доступ к спецификациям архитектуры, в частности архитектуры сети и программного обеспечения? 54/566
31. Чему могут способствовать спецификации архитектуры, в частности архитектуры сети и программного обеспечения? 54/544 Рассмотрению разнообразия видов ошибок, связанных с архитектурой, например состояний гонок в базах данных и одиночных точек сбоев в нерезервируемых серверах ("нерезервируемых серверах"?).
32. Какие методы тестирования применяю на работе? Не уделяю внимания структурному тестированию (понимание особенностей архитектуры и реализации системы может быть важно для анализа рисков), но занимаюсь тестированием основанным на поведении системы (не очень важно, каким образом система устроена внутри).
33. Что даст на практике анализ рисков? 55/544 Провели анализ оценки рисков, определили уровень тестирования (подробное, сбалансированное, поверхностное, по возможности, информирование о наблюдаемых дефектах) и оценили ресурсы для достижения необходимого уровня тестирования.
34. Что за процесс управления изменениями? 55/544: "Обычно обновленные результаты анализа рисков качества требуют некоторого инкрементного наращивания границ или объема тестирования". 56/544 - "любое изменение требует пересмотра соглашения о функциональности, качестве, сроках и бюджете, присущих разработке любой системы… способ организации сотрудников… структура, управляющая обсуждениями…". Похоже в конце концов - это реакция на организационные, функциональные, технологические и проектные изменения. 470/544 - подробности про управление изменениями в отдельном процесс №12 "Процесс управления изменениями". 
35. Какой существуют традиционный подход к управлению изменениями? 55/544 - в помещении документов с описанием анализа рисков качества в проектной репозиторий. По мере того как группа проекта получает новую информацию о рисках и по достижении рубежей проекта анализ повторяется.
36. Что может повлечь за собой существенные изменения в границах тестирования? Обнаруженные большие новые области рисков. Например что система должна работать не только в интранете компании но и в интернете. В результате необходимо добавить новые области тестирования в том числе медленные коммутируемые соединения. 55/566
37. В каких двух случаях может изменяться вероятность риска? 55/544 Первое – в результате обнаружения новых рисков. Второе – в результате возрастания риска в тех областях, которые уже казалось бы исследованы.
38. Что у меня с навыкам тестирования производительности? Упущение
39. Что особенно интересного будет в главе 11? Рассказ про трассировку тестового покрытия относительно рисков качества
40. О чем думает тестировщик в Париже в музее искусства и науки? 59/566
41. Какие существуют риски кроме рисков качества, связанных с самой системой? Риски качества, связанные с проектом, процессом, даже организационным устройством группы проекта, которая разрабатывает систему. Подробнее о рисках качества программе ISTQB 59/566
42. От чего зависит сила мощного инструмента анализ рисков качества? Сила этого инструмента в большой степени зависит от привлечения к анализу специалистов разного профиля 59/566
43. Книгу Стива Макконнела добавил в лист желаний? 59/566
44. Какой может быть причина различия в оценках? Некоторые заинтересованные лица не учли при рассмотрении какие-либо важные соображения 62/566
45. Что делать если какое-то предположение оказывается верно лишь для очень малый группы пользователей, но этот сегмент пользователей очень важен для долгосрочной стратегии компании? Нужно увеличить значение приоритета риска, а не фабриковать значение вероятности
46. Что должны понимать сотрудники, не связанные с технологиями? Проблемы существуют не потому, что люди в производственных подразделениях компании ленивый или умышленно плохо выполняют свои обязанности, а потому, что процесс и навыки сотрудников этих подразделений нуждаются в усовершенствование. Анализ рисков качества – это одно из направлений усовершенствования процесса, которое может оказаться полезным 63/566
47. Почему Рекс Блэк рекомендует книгу Деминга?
48. Какие две книги Рэкс Блэк рекомендует для анализа категории рисков? 57/544
49. Что нужно объяснить ключевым заинтересованным лицом заботящимся качестве системы? Помочь им понять, как управление рисками качества может способствовать тому, что будет проведено тыс тирования только тех частей системы которые существенны для выпуска версии 94/566
50. На что направлен процесс анализа рисков качества? На достижение разумных компромиссов относительно разных областей риска – сроков, бюджета, перечня в реализуемых свойств и качества – различных категорий рисков качества.

### Глава 3 "Внутри хрустального шара: оценка предстоящей работы"

Перечень контрольных вопросов по результатам прочтения:
1. Что нужно делать чтобы правильно ориентировать подпроект тестирования? Необходимо адекватно покрывать риски угрожающие успеха проекта с помощью грамотно спроектированных тестовых сценариев 95/566
2. Почему нужно читать главы в 10 и 11? В этих главах рассматриваются проектирование и разработка тестовых сценариев, тестовых данных, инструментов тестирования и других компоненты системы тестов.
3. Что описывает процесс оценки ресурсов? Механизм с помощью которого тестирование встраивается в рамки сроков и бюджета проекта.
4. Что представляет собой процесс №4 по Рэксу Блэку? Процесс оценки затрат 97/566
6. Что такое презентация преимущества подпроекта тестирования? 99/566
7. Что такое контекст тестирования? Открыть страницу на которой три человека общались после выездного семинара
8. Определил ли в плане тестирования критерии завершения тестирования? Какие бывают критерии? 101-126/566
9. Выделяю ли при своей работе на фазе планирования критерии начала тестирования? Какие бывают критерии?
10. Чем тестовый раунд отличается от тестового цикла и тестовой фазы?
11. Возможно стоит указать в таблице лучшую и худшую оценки выполнения задачи. 109/566
12. Вопрос на который хочу найти ответ в книге - кто такой тест-аналитик и чем занимается?
13. Как автор книги относится к классическому методу обучения – выплывет или нет, читать главу 8 и 9.
14. Чем человеко-час отличается от обычного часа? Что такое человеко-день? Wiki - "Для достаточно крупных работ используют подобную величину Человеко-день — характеризует работу одного человека в течение одного рабочего дня вне зависимости от установленной продолжительности рабочего дня[1](). Для восьмичасового рабочего дня этот объём работ обычно меньше, чем эквивалент восьми человеко-часам, так как учитываются неизбежные перерывы, простои и т. п.". 
15. Какие методы следует использовать для оценки продолжительности и затрат ресурсов на каждую задачу? Опираться на свой предыдущий опыт решения подобных задач при оценке продолжительности и затрат ресурсов на каждую задачу. Метод дельфийского оракула, трёх точек, широкополосный метод могут применяться для выявления знаний группы. 120/566
16. Какую книгу и какую статью в каком журнале рекомендует Рекс Блэк?
17. В какой книге можно найти эмпирический правила разработки тестовых сценариев?
18. Забрал ли себе в статью про оценку времени на выполнение проекта четыре примера результатов измерений приведённых автором книги?
19. Что обязательно учитывает автор книги в своих оценках? Что количество тестовых сценариев будет отличаться по сравнению с начальной оценкой, например возрастёт с 40 до 60. Плюс необходимо обязательно включать 50% прибавки на непредвиденные обстоятельства. 121/566
20. Стоит в публикации про оценку времени рассмотреть понятие человеко-часов и человек-месяцев?
21. Забрал ли в статью пример автора про тривиально настройку тестовый среды? На работу потребовался примерно один человеко-день. Тем не менее продолжительность фазы было около трёх недель 122/566
22. Какое эмперическое правило использует автор книги для оценки времени в зависимости от количества дефектов находимых в каждом цикле? 124/566
23. Что за статистический метод использующий модели для устранения дефектов? В какой книге можно подробно ознакомиться с некоторыми из этих моделей? Стефан Кан и Панкоджед Джелота в закладки занес? 124/566
24. Что в большинстве случаев имеет большее значение чем тестирование и исправление каждой найденной в конце проекта ошибки? 
25. Что делать если не получится использовать все данные о числе наденных и исправленных дефектах проекта? Обратиться к таблицы которую предоставляет Рекс Блэк в приложении к книге - EstimatedBugFind-Fix.xls. 124/566

### Глава 4 "Не сколько стоит, а сколько экономит: бюджет и возврат инвестиций"

Перечень контрольных вопросов по результатам прочтения:
1. Что позволяет понять декомпозиция работ и план график тестирования? 127/566
2. Какими четырьмя основными способами тестирование приносит отдачу? 128/566
3. Когда окупаемость тестировании будет невелика независимо от числа обнаруженных ошибок? Если группа тестирования растрачивать попусту время и ресурсы в поисках ошибок которые не относится к реальному использованию системы и критическим рискам её качества 131/566
4. Какова будет стоимость устранения внутреннего несоответствия программного продукта при 100 процентной удовлетворённости заказчиков? 131/566
5. Что необходимо для анализа возврата вложений для обнаруженных и исправленных ошибок? 145/566
6. Что такое тестовый раунд у Рэкса Блэка? Что такое инкремент? 146 
7. **Что у Рэкса имеется в виду под внутренними несоответствиями?**
8. **Что Блэк подразумевает под затратами, понесенными от внешних несоответствий?** 

### Часть 1 "Плариование", глава 6 "Изучение и обсуждение содержания проекта"

#### Что Рэкс Блэк имеет в виду под "база данных управления изменениями"?

Из преложения "Он снова обратился к предыдущим проекта, просмотрел базы данных управления изменениями некоторых последних его проектов и добавил несколько рисков, а также план на случай непредвиденных обстоятельств и план смягчения рисков" совсем непонятно.

#### Зачем для исследовательского тестирования Блэк приводит обозначение "партизанское - guerrilla" тестирование?

"Исследовательского (партизанское - guerrilla) тестирование позволяет протестировать области, не покрытые запланированными тестами" на 169 странице.

#### Что имеется в виду под анализом данных об отказах при эксплуатации?

На 169 странице рассказано, что риск пробелов в тестовом покрытии следует смягать использованием по возможности методов анализа структурного покрытия, анализа данных об отказах при эксплуатации, данных пользователей для определения пробелов, которые необходимо заполнить.

#### Что попадает в план тестирования?

Тема раскрывается на 170-171, 173 страницах книги. Результаты анализа рисков качества, оценка затрат, итог обсуждений с ключевыми участниками процесса. План тестирования собирает и переформулирует существующую информацию и дает возможность обмениваться этой информацией. План тестирования должен содержать предложение идей, выводов и решений для четкого понимания у читателей, что от них требуется. Например, управление подготовкой тестовых версий. Или тема отчетности о состоянии дел в тестировании. Еще тем для отражения к плане - стратегия тестирования. Еще одна часть стратегии - планируемые к использованию методы тестирования, например статические, структурные, поведенческие.

#### Какое определение Блэк дает стратегии тестирования?

171 страница:

> Стратегия тестирования (Test Strategy) - это совокупность выбранных подходов и решений, вытекающих из целей и задач подпроекта тестирования и группы тестирвоания. Целью обычно является эффективное и качественное тестирование, а стратегия - это общие правила и принципы, способствующие достижению цели.

#### У кого читать подробности по методу статического тестирования?

На 173 странице книге упомянуты два известных примера: инспекця кода и рецензирование требование. Эта тема подробно обсуждается в книгах "Остаться в живых! Руководство для менеджера программных проектов" Стива Макконнелла, "Психология компьютерного программирования" Джеральда Вайнберга и "Разработка требований к программному обеспечению" Карла Вигерса.

#### Что такое тактика тестирования?

171 страница:

> Это частные правила, методики, процессы и способы проведения тестирования.

#### Какой пример универсальной стратегии тестирования можно привести?

173 страница:

> Стратегия тестирования проекта "Суматра"
>
> - Разработать автоматизированные и ручные тесты для покрытия всех рисков качества, которые определены как нуждающиеся в полном или сбалансированном тестировании, с особым вниманием к факторам поведения системы, наблюдаемого со стороны некоторого пользовательского интерфейса или доступного программного интерфейса приложения (API).
> - Добавить тестовые данные или условия в рамках существующих или новых тестовых сценариев для покрытия критических вариантов использования системы, пользовательских данных или известных дефектов в нашем продукте или продукте конкурентов.
> - Использовать исследовательское тестирование в областях, которые ранее не были покрыты тестами, и которые, с точки зрения интуиции и результатов тестирования...

#### Что Рэкс имеет в виду под оценкой сложности кода для определения скрытых дефектов в тестовом покрытии?

На 171 странице затрагивается:

> Применить какой-либо вариант структурного анализа (динамический или статический, например оценку сложности кода) для определения скрытых дефектов в тестовом покрытии.

#### В чем природа регрессионной зависимости?

Обращаться к 176-177 страницам.

#### Можно ли на рабочем проекте располагать информацией о том, какое подмножество пользователей применяет определенные свойства или возможность системы?

На 178 странице задался вопросом.

#### Что такое пропуск при тестировании (Test Escape)?

178 страница:

> Любая ошибка, которая могла быть обнаружена при тестировании, но была пропущена. Термин часто применяют к ошибкам, обнаруженным на фазах следующих за тестированием, хотя они должны были быть найдены на предыдущей фазе.

#### Что такое "искажение тестирования"?

182 страница,



Лог вкладов времени:

1. Предисловие, Благодарности, Вступление, Введение. 03-08.04.2018. 19 страниц за 5 дней, 4 страницы в день, 6 минут на страницу.
2. Часть 1. Глава 1 “Роль тестирования”. 08-14.04.2018. 31 страница за 6 дней, 5 страниц в день, 8 минут на страницу.
3. Часть 1. Глава 2 “Анализ рисков”. 14-22.04.2018. 30 страниц за 8 дней, 4 страницы в день, 9 минут на страницу.
4. Часть 1. Глава 3 “Оценка предстоящей работы”. 22.04.2018-01.05.2018. 30 страниц за 9 дней, 3 страницы в день, 7 минут на страницу.
5. Часть 1. Глава 4 “Бюджет и возврат инвестиций”. 01-12.05.2018. 22 страницы за 11 дней, 2 страницы в день, 6 минут на страницу. 

20.05.2018. Перейти на [Главную страницу](./)