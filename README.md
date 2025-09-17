# 🔗 Excel INDEX & MATCH Functions

The **INDEX** and **MATCH** functions are a powerful combination in Excel, allowing you to **lookup values anywhere in a table**.  
They are more flexible than VLOOKUP and are widely used in **data analysis, dashboards, and reporting**.

---

## 📌 INDEX Syntax
```excel
=INDEX(array, row_num, [column_num])


```
## 📌 MATCH Syntax
```excel
=MATCH(lookup_value, lookup_array, [match_type])


```

## 📊 Example: Find Bob's Salary
Dataset:

| ID  | Name   | Salary |
|-----|--------|--------|
| 101 | Alice  | 50000  |
| 102 | Bob    | 60000  |
| 103 | Carol  | 55000  |

Formula:

```excel
=INDEX(C2:C4, MATCH("Bob", B2:B4, 0))

