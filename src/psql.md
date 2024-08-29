# psql
## 直接在命令行执行sql
```shell
 gsql -d postgres -p 31327 -c 'select local_role from pg_stat_get_stream_replications()'
```