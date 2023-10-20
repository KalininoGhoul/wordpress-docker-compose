# wordpress-docker-compose

Установка

`docker stop $(docker ps -a)`

`git clone https://github.com/KalininoGhoul/wordpress-docker-compose.git`

`cd wordpress-docker-compose`

Чтобы запустить контейнер

`docker-compose up -d`

При первом запуске

Создаем копию файла `sample.env` с названием `.env`  

```
docker exec -it wp-wordpress bash

cd ..
chmod 777 -R html
exit
```

Когда завершаем работу

`docker-compose down`
