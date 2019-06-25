Информационные технологии (ИТ) для бизнес-аналитиков
====================================================

Что в этом файле
----------------

Список тем для лекций и занятий, основные понятия.


Кто аудитория
-------------


Кто                | Что делают
-------------------|------------------------------------------------
Бизнес-аналитики   | Обеспечивают связь стратегии предприятия и ИТ систем
<BR>               | Управление на основе данных, data governance
Исследователи      | Воспроизводимые исследования (Reproducible research)


Гипотезы
--------

1. Между бизнесом и ИТ требуется улушение коммуникаций, это позволяет повысить 
   прозводительность.
2. Разделение программисты-непрограммисты сейчас менее жесткое, чем раньше. Есть способы снизить порог входа.
3. Много людей интересуется новыми темами "с нуля", переходят между темами, для них важно ориентироваться в смежных темах, понятиях, выстривать связи между различными сферами знаний.
4. Слишком много изменений замыкаются на "культуру" (работы с данными, общения на технические темы и т.д), способ повысить ее - образование и переобучение.   


Предыстория
-----------

Основан на опыте преподавания курсов "Машинночитаемая корпоративная отчетность" (ЦМФ), лекций "Введение в ИТ-архитектуру" (МГИМО), обсуждения на митапе Московского клуба программистов 13.06.2019.

Список тем
==========

Основные темы:

1. Программирование
2. Работа с данными 
3. Процессы разработки и внедрения, DevOps
4. ИТ-архитектура компании, связь бизнеса и ИТ
5. Персональная продуктивность

Дополнительные темы и навыки:

- Масштабируемые системы и интеграция  
- Пользовательские интерфейсы (UI/UX)
- Технические диаграммы (UML, C4 model)
- Подходы к цифровизации
- Работа команд
- Преподавание и электронные учебники (jupyter, colab, bookdown)

1. Программирование
-------------------

- Языки программирования и логика построения программ. 
- Практика программирования: цели, способы совершенствования, типовые сложности.
- Качество кода, рефакторинг, тестирование, документация.
- Алгоритмы и другие результаты из computer scicence.
- Абстракции, архитектура программ, паттерны. Интерфейсы программ (API).

По программированию [есть детализация тем](programming.md). 

2. Работа с данными
-------------------

Практика:

- Машинно-читаемые форматы данных, сериализация.
- Базы данных, SQL, ORM. NoSQL/GraphQL.
- Визуализация данных - как рисовать картинки, дэшборды.
- Данные в исследованиях: immutable data/"source of truth", DAG.
- АPI получения данных. Примеры хранения (AWS S3). 

Состояние дел:

- Качество данных, data governance.
- Oфициальная статистика и данные в госорганах.
- Корпоративные системы (DWH, lake, mesh). 
- Data privacy, GDPR.


3. Процессы разработки и внедрения, DevOps
------------------------------------------- 

- Продукт
- Постановка задачи, спецификация, техническое задание.
- DDD и разные "cool-thing"-driven development
- Agile vs waterfall
- Типовые проблемы разработки и опыт работы команд
- Особенности взаимодействия (например, парное программирование)
- Работа фрилансера и с фрилансерами


#### DevOps

- version control (до-git, gitlab/github). Как написать хороший коммит.
- issue traker (Jira, etc)
- CI (travis, circle) / CD(heroku)
- infrastructure as code, AWS, ainsible, 
- "Облако это чей-то компьютер"
- docker


4. ИТ-архитектура компании, связь бизнеса и ИТ
----------------------------------------------

- участники процесса (CIO, CDO, команды)
- solution и enterprise архитектура, 
- подходы к цифровизации
- (слабая) связь ИТ со стратегией
- успехи и провалы ИТ проектов
- основы бюджетирования 

5. Персональная продуктивность
-----------------------------

- работа с командной строкой
- markdown (rst, asciidoc)
- plain text в git
- сервисы AWS
- jupyter notebook, binder
- todo: todo.txt / trello / wip vs trying
- создание онлайн документации, учебников, статические генераторы сайтов
- PDF/latex
- удобный текстовой редактор (oт vim до VS-Code) 



Комментарии
-----------

#### Не раскрыто, но хотлеось бы 

- операционные системы
- безопасность
- словарь терминов
- live coding

#### О чем не говорим сознательно

- фронтэнд, javascript/node.js
- системное программирование
- как работать с MacOS
