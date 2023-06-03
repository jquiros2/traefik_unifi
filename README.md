# traefik_unifi
traefik and separate unifi controller in docker

We needed to migrate our unifi controller and other services from one server to another, so I figured it was a good time to learn docker a little more.  And traefik.
This is a working setup for it.

traefik in one folder with its docker-compose and a separate unifi folder with its own docker-compose.
This is in case you want to add other services in separate docker-compose files.

Almost entirely based on:

https://gist.github.com/jeroenhendricksen/7dfe273277bbbd1c2ea2cb7c647b24fa
