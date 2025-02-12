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

<b>[Ссылка на тестовую среду](https://dbfiddle.uk/4D1pk94-?hide=2)

![](https://github.com/Nadezhda2024/Rresearch-of-the-trading-company-s-data-using-SQL/blob/main/EXEC%20sp_help.png)


**Исследование каждого поля**

<b>[Ссылка на тестовую среду](https://dbfiddle.uk/utQRs-A9)

![](https://github.com/Nadezhda2024/Rresearch-of-the-trading-company-s-data-using-SQL/blob/main/SELECT%2C%20FROM%2C%20COUNT%2C%20MIN%2C%20MAX%2C%20AVG%2C%20DISTINCT.png)

Предоставленные данные в таблице из корпоративного хранилища компании «СтройСнаб» содержат информацию за определенный временной промежуток, отражающие явления и процессы компании. В сборнике помещены показатели: типы заказов, категории продуктов, продукт, производитель, количество продукта, цена, цена продажи.

## Исправление ошибок в данных

<b>[Ссылка на тестовую среду](https://dbfiddle.uk/Qf7w5pPZ)

![](https://github.com/Nadezhda2024/Rresearch-of-the-trading-company-s-data-using-SQL/blob/main/DELETE%2C%20UPDATE.png)

## Анализ финансовых показателей

**Расчеты с помощью SQL**

<b>[Ссылка на тестовую среду](https://dbfiddle.uk/Lxez5yfT)

![](https://github.com/Nadezhda2024/Rresearch-of-the-trading-company-s-data-using-SQL/blob/main/SUM%2C%20%20WHERE%2C%20GROUP%20BY%2C%20ORDER%20BY.png)
![](https://github.com/Nadezhda2024/Rresearch-of-the-trading-company-s-data-using-SQL/blob/main/SUM%2C%20ROUND%2C%20WHERE%2C%20CASE%2C%20GROUP%20BY%2C%20ORDER%20BY.png)
![](https://github.com/Nadezhda2024/Rresearch-of-the-trading-company-s-data-using-SQL/blob/main/SUM%2C%20ROUND%2C%20WHERE%2C%20CASE%2C%20GROUP%20BY%2C%20ORDER%20BY%201.png)

###[Отчет анализа финансовых показателей в Microsoft Excel](https://docs.google.com/spreadsheets/d/1wANTVPisHzI8eJYfHfKCbCEhtIpJqzB2/edit?usp=sharing&ouid=105723758090183599080&rtpof=true&sd=true)

## Модернизация структуры БД

<b>[Ссылка на тестовую среду](https://dbfiddle.uk/teV4PCrC)

Сформировала таблицы справочники с присвоением  идентификаторов во всех справочниках, начинающихся со значения 1 и монотонно возрастающие без пропуска значений. Для получения результата использовала автоинкремент. Наполнила основную таблицу данными из созданных справочников.

![](https://github.com/Nadezhda2024/Rresearch-of-the-trading-company-s-data-using-SQL/blob/main/CREATE%20TABLE%2C%20INSERT.png)
![](https://github.com/Nadezhda2024/Rresearch-of-the-trading-company-s-data-using-SQL/blob/main/CREATE%20TABLE%2C%20INSERT%2C%20IDENTITY.png)
![](https://github.com/Nadezhda2024/Rresearch-of-the-trading-company-s-data-using-SQL/blob/main/CREATE%20TABLE%2C%20INSERT%2C%20JOIN.png)

## Расчёт остатков на складе

<b>[Ссылка на тестовую среду](https://dbfiddle.uk/aBmaks_X)

![]()
![]()
![](https://github.com/Nadezhda2024/Rresearch-of-the-trading-company-s-data-using-SQL/blob/main/%D1%80%D0%B0%D1%81%D1%87%D0%B5%D1%82%20%D0%BE%D1%81%D1%82%D0%B0%D1%82%D0%BA%D0%BE%D0%B2%20COALESCE%2C%20CASE.png)
![](https://github.com/Nadezhda2024/Rresearch-of-the-trading-company-s-data-using-SQL/blob/main/COALESCE%2C%20CASE.png)

## Импорт дополнительной порции данных

<b>[Ссылка на тестовую среду](https://dbfiddle.uk/FWXHaz0R)

![](https://github.com/Nadezhda2024/Rresearch-of-the-trading-company-s-data-using-SQL/blob/main/SUBSTRING%2C%20%20TRIM.png)
![](https://github.com/Nadezhda2024/Rresearch-of-the-trading-company-s-data-using-SQL/blob/main/%D0%BD%D0%BE%D0%B2%D0%B0%D1%8F%20%D1%82%D0%B0%D0%B1%D0%BB%D0%B8%D1%86%D0%B0.png)
![](https://github.com/Nadezhda2024/Rresearch-of-the-trading-company-s-data-using-SQL/blob/main/%D0%BF%D1%80%D0%BE%D0%B2%D0%B5%D1%80%D0%BA%D0%B0%20%D1%81%D0%BE%D0%BE%D1%82%D0%B2%D0%B5%D1%82%D1%81%D1%82%D0%B2%D0%B8%D1%8F%20%D1%81%D0%BF%D1%80%D0%B0%D0%B2%D0%BE%D1%87%D0%BD%D0%B8%D0%BA%D0%B0%D0%BC.png)
![](https://github.com/Nadezhda2024/Rresearch-of-the-trading-company-s-data-using-SQL/blob/main/%D0%BD%D0%B0%D0%BF%D0%BE%D0%BB%D0%BD%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%BD%D0%BE%D0%B2%D0%BE%D0%B9%20%D1%82%D0%B0%D0%B1%D0%BB%D0%B8%D1%86%D1%8B%20%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D0%BC%D0%B8.png)
