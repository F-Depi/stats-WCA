This repo is a collection of really simple queries that are useful as a first approach to WCA statistics. 
They can easily be prompted at https://statistics.worldcubeassociation.org/database-query logging in with a WCA Account

This lists all the tables accessible on the database

```
SELECT * 
FROM INFORMATION_SCHEMA.TABLES i
WHERE i.TABLE_ROWS != 0
```

To look at all the column of a specific table you can print the first 5 rows with

```
SELECT *
FROM "YourTableName"
LIMIT 5;
```
