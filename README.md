# postgres-chinese-textsearch

Run [PostgresSQL](https://github.com/docker-library/docs/blob/master/postgres/README.md) with [zhparser](https://github.com/amutu/zhparser) and [pg_jieba](https://github.com/jaiminpan/pg_jieba) in Docker

```
docker pull hoilc/postgres-chinese-textsearch
docker run --name postgres-zh -e POSTGRES_PASSWORD=mypassword -d hoilc/postgres-chinese-textsearch
```
