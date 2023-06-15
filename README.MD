## 環境構築
```bash
$ git clone git@github.com:shouya0504/laravel10dev.git
$ cd laravel10dev
$ docker-compose up -d
$ docker-compose exec app bash

# appコンテナ内
# appの部分はプロジェクト名なので適宜変更する
$ composer create-project "laravel/laravel=10.*" laravel10 --prefer-dist
```

## URL
http://localhost/