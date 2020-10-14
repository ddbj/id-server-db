# id-server-db

## DB初期化
- volumesで./initdbにあるsqlとshをdocker-entrypoint-initdb.dにマウント
- docker-entrypoint-initdb.d置いてあるsql,shは、起動時に自動実行される
- init直下のファイルは、頭に付けた番号順で実行される
## build
`docker-compose build`
## 起動
`docker-compose up -d`
 