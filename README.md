# tp-docker

## Lancement d'une image


```bash
docker run -ti -p 8888:80 --name tp-docker -v /var/www/html:/var/www/html image 
docker run -v $pwd/src/:/var/www/html -p 30000:80 --name=tp_docker php:apache
```

## Lancement du fichier docker compose

```bash
docker-compose up --build -d
```
