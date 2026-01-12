# Sariful-My-SQL
# INSERT INTO … SELECT (SQL)

## 📌 Overview
`INSERT INTO … SELECT` ka use ek table se data lekar doosre table me insert karne ke liye hota hai.  
Yeh method bulk data insert karne ke liye simple aur efficient hai.

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
