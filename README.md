# README
## これなに？
Python(FastAPI + SQLAlchemy)とreactで雑にWebアプリ作るための私的なdocker

## 中身
- Python
  - FastAPI
  - SQLAlchemy
- React
- PostgreSQL
- redis
- nginx

## 使い方
### 初回
```
cp .env.example .env
docker-compose build
docker-compose up -d
```

### 起動
`docker-compose up -d`

### 終了
`docker-comopose down`

### ログ出力
`docker-compose logs -f`

- python-src以下にサーバサイドのあれこれ書く
- react-src以下にフロントエンドのあれこれ書く

## URL
React
- `http://localhost/`

API
- `http://localhost/api/hogehoge`
- `http://localhost/docs`
