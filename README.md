# Chisato

This is TKYcraft BackEnd API for Minecraft Notification bot.



## Getting started (for development)

on your Docker host.

```bash
docker compose up -d --build   # up containers with build process.
docker compose ps   # check running containers.
docker compose down   # down containers.
```



### options

* Ruby version : 3.2.2 (configure on Dockerfile, Gemfile)

* Database creation / initialization
  This is STATELESS API.

* How to run the test suite

  ```bash
  docker exec -it mahirun-server bundle exec rspec
  # or exec bash
  ```

* Services

  - You should reference compose.yaml

* Deployment instructions

  - This is not Production.
