# seafile-setup

Repository for easy and fast setup of seafile with Traefik as Docker.

## How to install

1. Clone this repository.
2. Change all occurences of "<domain>" to your wished domain and the "admin e-mail" and "password" in `docker-compose.yml` 
3. Change permissions of `acme.json` to 600 (`chmod 600 acme.json`).
4. Start the container with `docker-compose up -d`.
5. Seafile should be reachable over the wished domain.
6. Adjust in Seafile: `System-Administration` -> `Einstellungen` -> `SERVICE_URL` and `FILE_SERVER_ROOT`

## How to run

If "installed" you only need to run `docker-compose up -d` in the main directory (where the `docker-compose.yml` is located).