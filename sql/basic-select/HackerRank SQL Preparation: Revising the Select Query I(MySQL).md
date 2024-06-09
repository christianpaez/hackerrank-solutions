**Problem Statement:**
Query all columns for American cities in the **CITY** table with populations larger than `100000`. The **CountryCode** for America is `USA`.

**Link:**[HackerRank - Revising the SELECT Query](https://www.hackerrank.com/challenges/revising-the-select-query/problem)

**Solution:**

```sql
SELECT * FROM CITY WHERE POPULATION > 100000 AND COUNTRYCODE = 'USA';
```

**Explanation:**
This SQL query retrieves all columns (*) for cities in the **CITY** table where the population is greater than `100000` and the **CountryCode** is 'USA'. Here's a breakdown of each part:

- `SELECT *`: Selects all columns from the **CITY** table.
- `FROM CITY`: Specifies the table from which to retrieve data, which is the **CITY** table in this case.
- `WHERE POPULATION > 100000`: Filters the rows to include only cities with a population larger than `100000`.
- `AND COUNTRYCODE = 'USA'`: Further narrows down the selection to cities located in America (USA) based on the **CountryCode** column.
