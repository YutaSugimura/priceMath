# rest-nextjs

## 1. install

```zsh
  yarn install
```

## 2. docker

```zsh
  cd docker
  docker compose up
```

## 3. setup

```zsh
  cp .env.template .env
  npx prisma migrate dev --name init
```

## 4. run

```zsh
  yarn dev

  # access1 (generate seed data)
  http://localhost:3000/api/seed

  # access2
  http://localhost:3000
```
