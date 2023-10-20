# wordpress-docker-compose

Установка

```
docker stop $(docker ps -a -q)
```

```
git clone https://github.com/KalininoGhoul/wordpress-docker-compose.git
cd wordpress-docker-compose
```

При первом запуске

Создаем копию файла `sample.env` с названием `.env` 

```
docker-compose up -d
``` 

```
docker exec -it wp-wordpress bash

cd ..
chmod 777 -R html
exit
```

Чтобы запустить контейнер

```
docker stop $(docker ps -a -q)
```
```
docker-compose up -d
```

Когда завершаем работу

```
docker-compose down
```
