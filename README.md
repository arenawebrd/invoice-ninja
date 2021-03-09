# invoice-ninja
Invoice Ninja - Docker-compose

Antes de instalar debes ejecutar este comando:

docker run --rm -it invoiceninja/invoiceninja php artisan key:generate --show

Te dará la clave Key que debes poner en la línea 23 del docker-compose.yaml

Luego ejecutas: docker-compose up -d

Ver en "localhost:8200"
