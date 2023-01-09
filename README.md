# How-to-dump-data-in-postgres
How to dump data in postgres

Use pg_dump (auto install when you install postgres)
```
pg_dump db_name --username postgres --password > db.sql
```


Import data dump to database
```
psql --username postgres --password yogyo < db.sql
```
