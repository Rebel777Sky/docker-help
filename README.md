# Docker Help

### Перейти в консоль контейнера
```
docker exec -it wireguard /bin/bash
```
> wireguard - имя контейнера

Посмотреть список настройк сетей docker
```
docker network ls
```
Просмотр детальной настройки сети
```
docker network inspect <имя сети>
```

Перезапуск
```
docker compose down
docker compose up -d
```

Посмотреть что за контейнер
```
docker ps -a | grep wg-easy
```
Запуск контейнера по его id_контейнера или имени
```
docker start <id_контейнера>
```

Просмотр журнала логов контейнера
```
docker logs wireguard --tail 50
```
> --tail 50 - последнии 50 записей

Просмотр запушенных контейнеров
```
docker ps
```
