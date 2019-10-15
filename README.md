# tp-docker

## Lancement d'une image


```bash
docker run -ti -p 8080:80 --name tp-docker -v /var/www/html:/var/www/html image 
```

## Lancement du fichier docker compose

```bash
docker-compose up --build -d
```
