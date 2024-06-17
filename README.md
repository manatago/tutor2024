# docker compose up する前に

これやっとかないとダメらしい


```
docker-compose run rails bundle install
docker-compose build --no-cache
```


立ち上がったらtutor_backendコンテナに入って
```
rails db:create
