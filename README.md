# tp-docker

## Lancement d'une image


```bash
docker run -d -p 8888:80 --name tp_docker -v  <emplacement du fichier en local>:/var/www/html php:7.2-apache
docker run -d -p 8888:80 --name tp_docker -v  ~/Documents/git/tp-docker:/var/www/html php:7.2-apache
```

## Lancement du fichier docker compose

```bash
docker-compose up --build -d
```
