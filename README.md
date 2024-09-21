## Steps
- Install docker compose - https://docs.docker.com/compose/install/
- Make sure docker is running
- `$ git clone https://github.com/ssiyad/be-infra-hopp.git`
- `$ cd be-infra-hopp`
- `$ docker compose up`

## Notes
- Nginx is used to reverse proxy all three APIs to `:80`
- Individual APIs does not expose themselves to the host
- APIs, database and Nginx are connected through a bridge network
