# SQL


SQL (Structured Query Language) - это язык запросов, используемый для управления и манипулирования данными в реляционных базах данных, которые часто используют тестировщики и не только.

SELECT - Извлекает записи из одной или нескольких таблиц. Он может использоваться для фильтрации, сортировки, группировки и агрегирования данных.
INSERT - Создает записи. Он может быть использован для добавления одной или нескольких записей в таблицу. Данный запрос почти не используют тестировщики.
UPDATE - Модифицирует записи.
DELETE - Удаляет записи.

### Следующие примеры демонстрируют различные варианты SQL SELECT запросов:

Извлечение всех данных из таблицы:
SELECT * FROM table_name;

Извлечение определенных столбцов из таблицы:
SELECT column1, column2, ... FROM table_name;

Извлечение данных с условием:
SELECT column1, column2, ... FROM table_name
WHERE ID=13;

Извлечение данных с сортировкой:
SELECT column1, column2, ... FROM table_name
ORDER BY column_name ASC|DESC;

Извлечение данных с группировкой:
SELECT column1, column2, ... FROM table_name
GROUP BY column_name;

### Пример SQL UPDATE запроса:
UPDATE tableName SET field1=new_value1 WHERE condition = value


