# 🐘&nbsp;PostgreSQL

Learning PostgreSQL basics

## Where you have column name but you don't know the table name, how to find the table?
```sql
 select table_name from information_schema.columns where column_name = 'your_column_name'
```
