# 使用 Docker 快速建立 Ruby on Rails 開發環境

## 版本
- Ruby 2.7.2
- Rails 6.1
- PostgreSQL

ref: https://docs.docker.com/compose/rails/

## 使用方式

- step 1 安裝 [Docker](https://www.docker.com/)
- step 2 執行指令：

```
$ docker-compose run --no-deps web rails new . --force --database=postgresql
```

by eddie@5xcampus.com
