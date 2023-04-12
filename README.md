# talent-land

```bash

docker compose up -d
# Esperar unos segundos dependiendo de la maquina.
docker compose run --rm --entrypoint=/bin/bash wpcli -c "wp core install --url=wpclidemo.dev --title="WP-CLI" --admin_user=wpcli --admin_password=wpcli --admin_email=info@wp-cli.org"


```
