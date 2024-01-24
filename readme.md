# DiscordInfoSeeker-db
## コンテナの起動 & ビルド🙌
```console
docker-compose up -d --build
```

## コンテナの終了👋
```console
docker-compose down
```

## コンテナ内に入って作業したい場合🛠️
1. コンテナIDを調べる。
```console
docker ps
```
2. コンテナ内に入る。
```console
docker exex -it <コンテナID> bash
```
3. データベース内に入る。
```console
bash-4.4# mysql -u user -p
Enter password:
Welcome to the MySQL monitor.  Commands end with ; or \g.
Your MySQL connection id is 21
Server version: 8.2.0 MySQL Community Server - GPL

Copyright (c) 2000, 2023, Oracle and/or its affiliates.

Oracle is a registered trademark of Oracle Corporation and/or its
affiliates. Other names may be trademarks of their respective
owners.

Type 'help;' or '\h' for help. Type '\c' to clear the current input statement.

mysql> show databases;
+--------------------+
| Database           |
+--------------------+
| database           |
| information_schema |
| performance_schema |
+--------------------+
3 rows in set (0.00 sec)

mysql>
```

## 初期のDB設定🧐
※必要に応じて適宜変えること。
|||
|--|--|
|ユーザ名|user|
|パスワード|password|
|DB名|database|


## DBの初期化🫠
準備中

