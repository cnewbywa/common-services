# Authentication service
This service provides authentication to services that need it.

The project contains the following components:

* [Keycloak](https://www.keycloak.org/) - authentication server
* [MySQL](https://www.mysql.com/) - database for Keycloak
* [NGINX](https://www.nginx.com/) - reverse proxy for Keycloak

Please note that the [Docker Compose](https://docs.docker.com/compose/) project mounts volumes to the host file system and uses [Docker secrets](https://docs.docker.com/compose/use-secrets/).

## Usage

* Prerequisites
  * The needed docker network has been created by running /`docker/runtime/network/create-network.sh`
  * cnewbywa.auth added to `/etc/hosts`

Run the `start-auth.sh` script.