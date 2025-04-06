# Ruby on Rails の開発環境

## 環境起動手順

### 初期

```
$ git clone

$ docker compose build

$ docker compose run web rails new. --database=mysql

$ docker compose build

$ docker compose up
```
<br>
動作検証のため以下へアクセス<br>

http://localhost:3000


## 手順2

```
$ docker compose build

$ docker compose up

$ docker compose run web rails db:create
```

<br>
動作検証のため以下へアクセス<br>

http://localhost:3000
<br>

データベースが未作成のため、ActiveRecordのエラーが発生するがDBを作成するとトップ画面が表示される