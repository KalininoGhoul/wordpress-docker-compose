# wordpress-docker-compose

Установка

`git clone https://github.com/KalininoGhoul/wordpress-docker-compose.git`

Чтобы запустить контейнер

`docker-compose up -d`

Когда начинаем работу впервые 

Создаем копию файла `sample.env` с названием `.env`  

```
docker exec -it wp-wordpress bash

cd ..
chmod 777 -R html
exit
```

Когда завершаем работу

`docker-compose down`
