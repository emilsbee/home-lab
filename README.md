## Home lab setup

All services run as Docker containers behind a [Traefik](https://traefik.io/) reverse proxy. Sensitive configuration values should be in a `.env` file so a `.env.example` is provided with examples. 

Currently hosted applications:
- [Traefik](https://traefik.io/)
- [Rainbow tracker Swagger documentation](https://github.com/swagger-api/swagger-ui)
- [Swagger editor](https://github.com/swagger-api/swagger-editor)
- [PG admin](https://www.pgadmin.org/docs/pgadmin4/latest/container_deployment.html)
- [Postgres](https://hub.docker.com/_/postgres)
- [Redis](https://hub.docker.com/_/redis)
- [Rainbow backend](https://github.com/emilsbee/rainbow-tracker-backend)