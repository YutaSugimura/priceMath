# graphql-apollo-server

## Getting Started

1. install

```zsh
  yarn install
```

2. setup Prisma

```zsh
  npx prisma migrate dev --name init
  npx prisma db seed --preview-feature
```

3. start

```zsh
  npm run dev
  # http://localhost:4000

  # prisma studio
  npx prisma studio
```

## Reference

https://github.com/prisma/prisma-examples/tree/latest/typescript/graphql
