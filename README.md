# Docker_PostgreSQL_client_sample

DockerにてPostgreSQLを管理するクライントの構築。
## 使用image
- [postgreSQL : 14](https://hub.docker.com/_/postgres)
- [pgadmin](https://registry.hub.docker.com/layers/dpage/pgadmin4/5.2/images/sha256-38617bc122e547dcfe3adaba52143f583343928b3700ada6feb9dcf6d13e0ca6?context=explore)
## 起動方法
- compose作成
```
docker-compose up -d
```
[localhost](http://localhost:5050)に接続<br>
参考にしたサイトは[こちら](https://zukucode.com/2022/11/docker-postgres.html)
