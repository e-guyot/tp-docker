# tp-docker

## Lancement d'une image


```bash
docker run -d -p 8888:80 --name tp_docker -v  ~/Documents/git/tp-docker:/var/www/html php:7.0-apache
```

## Lancement du fichier docker compose

```bash
docker-compose up --build -d
```
