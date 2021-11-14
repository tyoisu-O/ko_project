## 開発環境 ##

- : PHP v7.4.1 (Laravel v8.70.2)

- : MySQL v8.0.27

## 初回環境構築 ##

```
git clone git@github.com:tyoisu-O/ko_project.git
cd ko_project
docker compose build
docker-compose up -d
```

## docker で起動 ##

```
docker-compose up -d
```

## エントリポイント

laravel ウェルカムページ

  http://localhost:80

- 管理ページ

  http://localhost:8080/admin/


## 設定類

### `.env` ファイル

```
WEB_PORT=
DB_PORT=

DB_NAME=
DB_USER=
DB_PASSWORD=
DB_ROOT_PASSWORD=
```
  

## その他


