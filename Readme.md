This repo is a collection of all the queries "I did"
They can easily be prompted at https://statistics.worldcubeassociation.org/database-query logging in with a WCA Account

To list the tables one can access

```
SELECT * 
FROM INFORMATION_SCHEMA.TABLES i
WHERE i.TABLE_ROWS != 0
```

The first rows of the table ("YourTabName") can be visualized with

```
SELECT *
FROM "YourTableName"
LIMIT 5;
```
Using ```LIMIT``` is highly recommended, as some tables are very large and may cause the website to freeze for an extended period.
