# INSERT INTO … SELECT (SQL)

## 📌 Overview
`INSERT INTO … SELECT` is used to copy data from one table and insert it into another table.  
This method is simple and efficient for bulk data insertion.

---

## 🧠 Use Cases
- Copying data from one table to another
- Table migration
- Creating backup or reporting tables
- Inserting existing data along with default values

---

## 🧾 Syntax

```sql
INSERT INTO target_table (column1, column2, column3, ...)
SELECT column1, column2, column3, ...
FROM source_table;
