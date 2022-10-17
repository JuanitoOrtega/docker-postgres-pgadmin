# PostgreSQL y pgAdmin4 con Docker compose

Crea facilmente un servidor de base de datos PostgreSQL usando [Docker][1] compose, más cliente pgAdmin4 para gestionar tus bases de datos desde una interfáz gráfica en lugar de la consola.

## Lanzar contenedor

```shell
docker compose up
```

## Apagar contenedor

```shell
docker compose down
```

## Interactuar dentro del contenedor

```shell
docker exec -it <id container> bash
```

## Interactuar con la base de datos

```shell
psql -U <user> -d <database>
```

Otra forma de acceder a la base de datos

```shell
psql -U <user> <database> --password
```

## Lanzar servidor en segundo plano

```shell
docker compose up -d
```

# Información adicional

- [Docker][1]
---
[1]: https://docs.docker.com/get-started/