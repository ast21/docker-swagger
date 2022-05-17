# Swagger Editor

Нужно скопировать(создать) файл `.env`
```sh
cp .env.example .env
```

далее поменять `example.com` на нужный url
```sh
vim .env
```

потом запустить `docker-compose`
```sh
docker-compose up -d
```

перейти по ссылке `swagger.localhost/`

и на этом все.
