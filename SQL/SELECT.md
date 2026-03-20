### para filtrar um campo json
```sql
SELECT id, "key", 
FROM evolution_api."Message"
WHERE "key" ->> 'id'= '3EB081A39DE8AD1F9367DF';
```
