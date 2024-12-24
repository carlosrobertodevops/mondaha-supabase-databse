
# supabase-restore-databse


````
docker-compose up -d
docker exec -it supabase-restore-database-db-1 bash
...
>$ psql -h aws-0-sa-east-1.pooler.supabase.com -p 6543 -d postgres -U postgres.buzlazhtcndpegsnijcw < db_cluster-19-12-2024@09-21-24.backup

```
