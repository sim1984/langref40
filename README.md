Language Reference for Firebird 4.0
===================================

Это руководство описывает язык SQL, поддерживаемый СУБД Firebird 4.0 Beta.

В руководстве также приводятся практические примеры использования SQL, многие из
которых взяты из реальной практики.

 

Внимание
--------

В настоящее время Firebird 4.0 находится в активной разработке. Синтаксис и
поведение некоторых SQL операторов не является окончательным.

 

Что содержит данный документ
----------------------------

Данный документ содержит описание языка SQL Firebird. Он охватывает следующие
основные области:

-   Основные положения;

-   Зарезервированные и ключевые слова;

-   Типы и подтипы данных;

-   Операторы DDL (Data Definition Language — язык создания данных);

-   Операторы DML (Data Manipulation Language — язык обращения с данными);

-   Операторы управления транзакциями;

-   Обработка исключений;

-   Операторы PSQL (Procedural SQL — процедурный SQL, используется в хранимых
    процедурах, функциях, триггерах, пакетах и анонимных PSQL блоках);

-   Безопасность и операторы управления доступом;

-   Операторы и предикаты (утверждения);

-   Агрегатные функции;

-   Встроенные функции;

-   Коды ошибок и обработка исключительных ситуаций;

-   Описание системных таблиц и таблиц мониторинга;

-   Наборы символов и соответствующие им порядки сортировки.

Вопросы, не связанные с SQL в данном документе не рассматриваются.

 

Авторство
---------

В работе над руководством принимали участие:

-   Денис Симонов;

-   Пол Винкенуг;

-   Дмитрий Филиппов;

-   Дмитрий Еманов;

-   Томас Воинк;

-   Александр Карпейкин;

-   Алексей Ковязин;

-   Дмитрий Кузьменко.

Редакторы — Александр Карпейкин, Дмитрий Кузьменко, Алексей Ковязин, Денис
Симонов.

 

Благодарности
-------------

Благодарим Влада Хорсуна, Александра Пешкова, Павла Зотова за помощь в создании
этого документа.

 

Обновления
----------

Так как СУБД Firebird постоянно развивается, то изменяется и улучшается его
документация. Вы можете получить самые свежие версии этого документа по адресам:

-   PDF —
    <https://github.com/sim1984/langref40/releases/download/langref40/langref40.pdf>

-   одностраничный HTML —
    <https://github.com/sim1984/langref40/releases/download/langref40/langref40-html.zip>

-   многостраничный HTML —
    <https://github.com/sim1984/langref40/releases/download/langref40/langref40-html-chunks.zip>
