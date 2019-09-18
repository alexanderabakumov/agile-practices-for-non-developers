# Командный тренинг «Культура, процесс и инженерные практики Agile в продуктовой разработке для Scrum Masters»
_Как помочь команде втаскивать успешные продукты в продуктовой компании._<br/>
24 ак. часа, 18 астр. часов.

# Objectives
## После тренинга участники смогут применять:
### Коммуникации с инженерами
- Понимание языка разработчиков
- Их способы решения задач
- Их когнитивные ловушки
- Паттерны решения типовых вопросов на производстве
### Продуктовая бизнес-модель
- *Ценности* продуктовой разработки для обоснования процессных решений
- *Видение продукта* для упрощения принятия инженерных решений
### Культура и процесс
- *Производственная культура* для осознания личной и командной культур инженерами
- *Коллективная ответственность за результат* спринта для поддержки продуктовой бизнес-модели
- Желаемые *принципы и метрики производства* в продуктовой разработке
- Принцип *Just in Time поставок* и практика *Time Boxing*
- *Кросс-функциональность* команды для надёжного производства в условиях потока разнообразных задач
- PBI *DoD* как механизм контроля внутреннего качества
- Командное *планирование спринта* и необходимая настройка коммуникаций инженеров
- Командный *Sprint review*
- Как померить *метрики*, характеризующие качество, через rework
- *Информационные радиаторы* как инструмент коммуникаций с инженерами
- *Парная разработка* в формате Driver + Navigator и когда ее применять
### Работа с требованиями
- Понимание ценности в формате *User Story*
- *Декомпозиция* пользовательских историй
- Ключевые внешние *NFRs*
### Инженерные практики обеспечения внешнего качества
- *ATDD*, *Front-end tests*, *BDD*
- *Автоматизированное тестирование* и базовые техники *тест-дизайна* и *анализа покрытия*
- *Системные, интеграционные и модульные тесты* и изоляция окружения с помощью *тест-дублеров*
- *Нагрузочное тестирование*
### Инженерные практики обеспечения внутреннего качества
- *Внутренняя модель качества* из обоснованных внутренних NFRs
- *TDD*
- *Trunk based development*, *Feature Toggling*
- Принципы принятия *архитектурных решений и микро-дизайна* в условиях неопределенности и time boxing
- *Рефакторинг*, *внутреннее качество продукта* и *технический долг*
- *Code Review*
### Инженерные практики ускорения поставок
- *Автоматическая сборки* релиза
- *CI*
- *Статический анализ кода*
- *Версионирование схемы БД*
- *CD*
- *Культура DevOps* и *Continouos Feedback*
- *Контейнеризация*
- *Infrastructure as a Code*: провиженинг стендов
- *SRE* и мониторинг *системных- и продуктовых метрик*

# Программа
## 1. Зачем мы собрались? (0.5 часа всего / _из них_ 0.25 часа практики и обсуждений)
1. Знакомство с тренером
2. Договоренности
3. Выбор PO и разбивка по командам по "бразильской системе" в соотвествии с принципами Scrum
4. Самостоятельный обзор тренинга в группах
5. Парковка кейсов и проблем участников: проблемные ситуации с разработчиками на производстве

## Антипаттерны мышления инженеров в продуктовых компаниях
- [Ментальные ловушки](https://www.dropbox.com/s/opd2zllwd89ca7u/%D0%90%D0%BD%D1%82%D0%B8%D0%BF%D0%B0%D1%82%D1%82%D0%B5%D1%80%D0%BD%D1%8B%20%D0%BF%D0%BE%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D1%8F%20%D1%80%D0%B0%D0%B7%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D1%87%D0%B8%D0%BA%D0%BE%D0%B2%20%D0%B2%20%D0%BF%D1%80%D0%BE%D0%B4%D1%83%D0%BA%D1%82%D0%BE%D0%B2%D1%8B%D1%85%20%D0%BA%D0%BE%D0%BC%D0%BF%D0%B0%D0%BD%D0%B8%D1%8F%D1%85.pdf?dl=0)
- Троллим разработчиков:
```
- "А ты сможешь скоммутировать монады на Хаскеле?"
- "Аппликативные функторы"
- "Монада - это просто моноид в категории эндофункторов"
```

## Что продуктовый бизнес ждет от производственной системы (1.5/0.5)
1. Подход SLA к балансу бизнес-метрик: scope, time, quality, price, ?. Time-boxing.
1. Подход к запасам. JIT. Запасы в IT-разработке.
1. Подход к структуре команд: feature teams/matrix. Свойства feature team
1. Подход к формализации/самоуправлению
1. Подход к описанию процесса: процедурный/декларативный. Практика PBI DoD
1. Подход к ответственности: персональная/коллективная
1. Подход к коммуникациям: формальная/неформальная
1. Подход к экспертизе: фокусировка/кросс-функциональность. Практика Star Map.
### Декларируем наши команды на соответствие критериям
- Чеклист по свойствам feature team
- Star Map
- Манифест команды + trade-offs
- PBI DoD

## Что продуктовый бизнес ждет от внутрикомандного процесса (1/0.5)
1. Подход к обоснованности архитектуры через системное мышление: как обосновать инженерные решения. Демо обоснованности микро-дизайна.
2. Работа с требованиями и их виды
3. Подход к вложениям во внутреннее качество системы. Сервис vs Проект.
4. Подход к эволюции архитектуры: upfront/эволюционность+инкрементальность. Принципы Lean: откладывай@делегируй
### Проектируем желаемый продуктовым бизнесом процесс
- Внешние атрибуты качества
- Внутренняя модель качества
- Архитектурный гайдлайн

## NFRs
- [NFRs: FURPS+ model](https://www.dropbox.com/s/osqzmz4gmi62crs/RUPSmallProjects.rar?dl=0)
- [List of typical NFRs](https://en.wikipedia.org/wiki/Non-functional_requirement)

---

## Ретроспектива по вчерашнему дню (0.5/0.5)
- Закрытые цели тренинга, burndown
- Персональные инсайты
- 𝚫+
- Take-away actions
### Закрываем вопросы
- [Процесс изменений](https://www.dropbox.com/s/nbntmd6183hitkd/%D0%98%D0%BD%D0%BA%D1%80%D0%B5%D0%BC%D0%B5%D0%BD%D1%82%D0%B0%D0%BB%D1%8C%D0%BD%D1%8B%D0%B9%20%D0%BF%D0%BE%D0%B4%D1%85%D0%BE%D0%B4%20%D0%BA%20%D0%B8%D0%B7%D0%BC%D0%B5%D0%BD%D0%B5%D0%BD%D0%B8%D1%8E%20%D0%BA%D1%83%D0%BB%D1%8C%D1%82%D1%83%D1%80%D1%8B%20%D0%B8%20%D0%B2%D0%BD%D0%B5%D0%B4%D1%80%D0%B5%D0%BD%D0%B8%D1%8E%20%D0%BF%D1%80%D0%B0%D0%BA%D1%82%D0%B8%D0%BA%20Agile.pdf?dl=0)
- Коллективная ответственность за результат спринта: смещаем фокус на качество, сужая WIP + плотный _очный_ фидбек от бизнеса и пользователей.
- Кросс-функциональность: инженерные метафоры производственной системы (fail-over + разнообразный поток входящих задач). Инструмент Star Map + мотивация через него.
- Добавляем в US раздел DoD как контроль внутреннего качества.
- [Метрики rework](https://www.dropbox.com/s/108s9tddeeq6j7x/04.pptx?dl=0)
- Декомпозиция US: по сценариям и шагам

## Введение в разработку ПО (1.5/0.5)
### Модель уровней понимания и зоны черного ящика
### Закон расширения черного ящика: цикл Коулба
### Ключевые технологические решения и история
1. Метафора для разработки: робот-кулинар и инструкции для него
1. Исходники и компиляция
2. Запуск приложения
3. Процедурный стиль
4. Библиотеки
5. Объектный стиль
6. Конфигурация vs hardcode
7. Фреймворки
8. Автотесты
### Начинаем справочник технологий
### Практика «разработки» в выбранной метафоре
1. Моделирование на Java процессов приготовления вкусняшек
2. Рефакторинг процедурного кода в объектном стиле

## Введение в типовую архитектуру современных систем (2/1)
1. Кейс: онлайн-система персонального финучета
1. Points Of View
2. Архитектура клиент-сервер
3. Удаленные вызовы и типы клиентов
4. Типовые паттерны в рамках системы
5. Хранилища данных
### Практика разработки
1. Реализация на Spring предметной области

## Переход к разработке: дизайн процесса через выбор практик (1/0.5)
1. Современное отношение к дизайну процессов: от императивности и формальности к декларативности и гибкости
1. Выбор практик как process design core
1. [Как DevOps помогает продуктовой разработке](https://paper.dropbox.com/doc/Delivery-Pipeline-ci-cd-devops--AbaLMZphhnvfm0spHme2SHkYAg-OBLCVRSkMek24U7IXIHbq)
### Проектируем модель зрелости процесса через практики
#### Даны уровни зрелости процесса с т.з. продуктового бизнеса
1. Уровень: хоть как-то получаем хоть какой-то результат на prod
1. Уровень: управляем внешним качеством
1. Уровень: управляем внутренним качеством
1. Уровень: управляем TTM
1. Уровень: управляем успехом продукта
#### Когда
- Команды расставят практики из целей тренинга по уровням (+неуказанные)
#### Тогда на дебрифе
- Кросс-ревью командных моделей зрелости
- Мерж в единый процессный беклог: долг по внедрению практик для дальнейшей проработки в рамках тренинга
- BPI DoD
#### Ретро

## Sprint DEV-01 (1.5/1)
- Что такое ATDD и BDD
- Введение в Cucumber
- Базовые техники тест-дизайна: структура системного теста
- Введение в Selenium
### Даны
- Обзор системы автосборки, CI и анализа кода
- Беклог
- Legacy codebase и инфраструктура
### Когда
- Команды меняют groupId и папку БД с спользованием teamXX
- Команды проводят декомпозицию User Stories
- Команды фиксируют NFRs
- Команды проводят Sprint Planning
- Команды проводят спринт
- Парная работа в формате Driver + Navigator
- Помощь тренера по решению блокеров
### Тогда
- Sprint Review
- Добавление технического долга в беклог
- Retro

## Sprint DEV-02 (1.5/1)
- Базовые техники тест-дизайна: структура интеграционного теста
- Типы тест-дублеров для изоляции окружения
- Рассчет тестового покрытия
### Даны
- Включение системы расчета покрытия в систему автосборки и CI
- Беклог
- Legacy codebase и инфраструктура
### Когда
- Команды проводят декомпозицию User Stories
- Команды фиксируют NFRs
- Команды проводят Sprint Planning
- Команды проводят спринт
- Парная работа в формате Driver + Navigator
- Помощь тренера по решению блокеров
### Тогда
- Sprint Review
- Добавление технического долга в беклог
- Retro

## Sprint DEV-03 (1.5/1)
- Совместная работа с единой кодовой базой: шаблоны Trunk based development + Feature Toggling
- Введение в практику TDD для микро-дизайна
### Даны
- Беклог
- Legacy codebase и инфраструктура
### Когда
- Команды проводят декомпозицию User Stories
- Команды фиксируют NFRs
- Команды проводят Sprint Planning
- Команды проводят спринт
- Парная работа в формате Driver + Navigator
- Помощь тренера по решению блокеров
### Тогда
- Sprint Review
- Добавление технического долга в беклог
- Retro

---

## Ретроспектива по вчерашнему дню (0.5/0.5)
- Закрытые цели тренинга, burndown
- Персональные инсайты
- 𝚫+
- Take-away actions

## Sprint DEV-04 (1.5/1)
- Внутренняя модель качества из обоснованных внутренних NFRs
- Принципы принятия архитектурных решений и микро-дизайна в условиях неопределенности и time boxing
- Технический долг и рефакторинг
- Практика Code Review
- Практика автоматизированного code review со статическими анализаторами
- Практика расчета мутационного покрытия в систему автосборки и CI
### Даны
- Включение статического анализа в инфраструктуру CI
- Беклог
- Legacy codebase и инфраструктура
### Когда
- Команды проводят декомпозицию User Stories
- Команды фиксируют NFRs
- Команды проводят Sprint Planning
- Команды проводят спринт
- Парная работа в формате Driver + Navigator
- Помощь тренера по решению блокеров
### Тогда
- Sprint Review
- Добавление технического долга в беклог
- Retro

## Финальная ретроспектива (0.5/0.5)
### Даны
- Полученные на тренинге знания
- Полученные на тренинге практический опыт
- Полученные на тренинге артефакты
### Когда
- Кросс-командная ретроспектива тренинга
### Тогда
- Закрытые цели тренинга, burndown
- Инсайты
- 𝚫+
- *Обоснованные* next actions на производстве
