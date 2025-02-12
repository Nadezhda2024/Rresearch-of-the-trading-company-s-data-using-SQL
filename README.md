# Исследование данных торговой компании с помощью SQL

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
![](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)
![SQL Server](https://img.shields.io/badge/Microsoft_SQL_Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)
![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white)
![Microsoft Word](https://img.shields.io/badge/Microsoft_Word-2B579A?style=for-the-badge&logo=microsoft-word&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)

Реализовала итоговый проект исследование данных торговой компании с помощью SQL. 
Описание задачи: руководство холдинга хочет инвестировать в компанию «СтройСнаб». Для этого руководству нужно разобраться и понять, что именно компания продаёт, в каких объёмах и как долго, какая прибыль. Особенно интересуют текущие торговые активы.
Специалиста ИТ-департамента получил от «СтройСнаб» какие-то дампы данных,  которые передал мне.

Провела исследование данных торговой компании «СтройСнаб» с помощью SQL.

## Исследование полученных данных:

**Исследование структуры таблицы** 
Ссылка на тестовую среду

<b>[](https://dbfiddle.uk/4D1pk94-?hide=2)

![]("C:\Users\User\Documents\BI_аналитик\Github\Проектная работа по SQL\EXEC sp_help.png")


**Исследование каждого поля**
Ссылка на тестовую среду

<b>[](https://dbfiddle.uk/utQRs-A9)

![]("C:\Users\User\Documents\BI_аналитик\Github\Проектная работа по SQL\SELECT, FROM, COUNT, MIN, MAX, AVG, DISTINCT.png")

Предоставленные данные в таблице из корпоративного хранилища компании «СтройСнаб» содержат информацию за определенный временной промежуток, отражающие явления и процессы компании. В сборнике помещены показатели: типы заказов, категории продуктов, продукт, производитель, количество продукта, цена, цена продажи.

## Исправление ошибок в данных
Ссылка на тестовую среду

<b>[](https://dbfiddle.uk/Qf7w5pPZ)

![]("C:\Users\User\Documents\BI_аналитик\Github\Проектная работа по SQL\DELETE, UPDATE.png")

## Анализ финансовых показателей
**Расчеты с помощью SQL**
Ссылка на тестовую среду

<b>[](https://dbfiddle.uk/Lxez5yfT)

![]("C:\Users\User\Documents\BI_аналитик\Github\Проектная работа по SQL\SUM,  WHERE, GROUP BY, ORDER BY.png")
![]("C:\Users\User\Documents\BI_аналитик\Github\Проектная работа по SQL\SUM, ROUND, WHERE, CASE, GROUP BY, ORDER BY.png")
![]("C:\Users\User\Documents\BI_аналитик\Github\Проектная работа по SQL\SUM, ROUND, WHERE, CASE, GROUP BY, ORDER BY 1.png")

**Отчет анализа финансовых показателей в Microsoft Excel**
### []("C:\Users\User\Documents\BI_аналитик\Github\Проектная работа по SQL\отчет анализа финансовых показателей.xlsx")

## Модернизация структуры БД

Ссылка на тестовую среду

<b>[](https://dbfiddle.uk/teV4PCrC)

Сформировала таблицы справочники с присвоением  идентификаторов во всех справочниках, начинающихся со значения 1 и монотонно возрастающие без пропуска значений. Для получения результата использовала автоинкремент. Наполнила основную таблицу данными из созданных справочников.

![]("C:\Users\User\Documents\BI_аналитик\Github\Проектная работа по SQL\CREATE TABLE, INSERT.png")
![]("C:\Users\User\Documents\BI_аналитик\Github\Проектная работа по SQL\CREATE TABLE, INSERT, IDENTITY.png")
![]("C:\Users\User\Documents\BI_аналитик\Github\Проектная работа по SQL\CREATE TABLE, INSERT, JOIN.png")

## Расчёт остатков на складе
Ссылка на тестовую среду

<b>[](https://dbfiddle.uk/aBmaks_X)

![]("C:\Users\User\Documents\BI_аналитик\Github\Проектная работа по SQL\СПРАВОЧНИКИ.png")
![]("C:\Users\User\Documents\BI_аналитик\Github\Проектная работа по SQL\объединение таблиц.png")
![]("C:\Users\User\Documents\BI_аналитик\Github\Проектная работа по SQL\расчет остатков COALESCE, CASE.png")
![]("C:\Users\User\Documents\BI_аналитик\Github\Проектная работа по SQL\COALESCE, CASE.png")

## Импорт дополнительной порции данных

Ссылка на тестовую среду

<b>[](https://dbfiddle.uk/FWXHaz0R)

![]("C:\Users\User\Documents\BI_аналитик\Github\Проектная работа по SQL\SUBSTRING,  TRIM.png")
![]("C:\Users\User\Documents\BI_аналитик\Github\Проектная работа по SQL\новая таблица.png")
![]("C:\Users\User\Documents\BI_аналитик\Github\Проектная работа по SQL\проверка соответствия справочникам.png")
![]("C:\Users\User\Documents\BI_аналитик\Github\Проектная работа по SQL\наполнение новой таблицы данными.png")

