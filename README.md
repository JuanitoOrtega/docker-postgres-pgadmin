# Lanzar contenedor

docker compose up

# Apagar contenedor

docker compose down

# Interactuar dentro del contenedor

docker exec -it <id container> bash

# Interactuar con la base de datos

psql -U <database name> <database user> --password

psql -U root postgres --password

# Lanzar servidor en segundo plano

docker compose up -d