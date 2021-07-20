## install

yarn install

```zsh
  yarn install
  cd docker
  docker compose up
```

## Start

```zsh
  npx prisma init
  cp .env.template .env
  npx prisma migrate dev --name init
  npx ts-node index.ts
```

## Studio

```zsh
  yarn studio
```
