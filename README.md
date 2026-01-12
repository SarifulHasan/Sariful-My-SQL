# Sariful-My-SQL
# INSERT INTO … SELECT (SQL)

## 📌 Overview
`INSERT INTO … SELECT` is used to take data from one table and insert it into another table.
This method is **simple and efficient** for inserting **bulk data**.


---

## 🧠 Use Case
- Data copy karna from one table to another
- Table migration
- Backup ya reporting tables banana
- Existing data ke saath default values insert karna

---

## 🧾 Syntax

```sql
INSERT INTO target_table (column1, column2, column3, ...)
SELECT column1, column2, column3, ...
FROM source_table;
