## Dev

1. Clonar el repositorio
2. Crear un .env basado en el .env.template
3. Ejecutar el comando `docker composer up --build`

- Si existen problemas con carpeta pgdata en linux ejecutar en order-ms

```
sudo chown -R $(whoami) pgdata/
```
