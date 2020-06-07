# Players Lobby Game Bootstrap
  
  Players game integration repository.

  Includes:
  - frontend
  - backend

### Deps:

    - docker compose
    - docker
    - git

### How to run:
```
git submodule update --init

cp .env.example .env

~~~Change .env file as you wish (maintain the keys)~~~

docker-compose up -d
```

### Defaults:

Frontend:
    - port: 3000

Backend:
    - port:4000
    - graphql playground default path: `http://localhost:4000/`
