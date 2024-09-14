# NLW Pocket: JavaScript - FullStack Intermediário (Node + React)

## Aula 01 - Iniciando o backend

Nessa aula vamos construir o back-end da aplicação com Node.js, você vai aprender a explorar tecnologias como Fastify, Zod, Docker Compose, Drizzle ORM e realizar a criação do schema e seed do banco de dados, além de criar algumas das features do projeto: metas, metas pendentes e completar metas.

```bash
npm init -y (cria o package.json)
npm i typescript -D
npx tsc --init (cria o tsconfig.json)
npm i @types/node tsx -D
npm i fastify
npm i -D --save-exact @biomejs/biome
docker compose up -d (rodar o docker compose)
npm run dev (rodar a aplicação)
npm i drizzle-orm
npm i drizzle-kit -D
npm i zod

npx drizzle-kit generate (cria a migration da db)
npm i postgres
npx drizzle-kit migrate
npx drizzle-kit studio

npm i @paralleldrive/cuid2 (algoritmo de geração de id)
npm i dayjs
npm i fastify-type-provider-zod
```

## Aula 02 - Finalizando o backend e iniciando o frontend

Nessa aula vamos avançar ainda mais o desenvolvimento da aplicação, finalizar o back-end e iniciar o front-end do projeto. Vamos começar pela construção das interfaces, criando diversos componentes, e seguir com o uso de ferramentas como Vite, Biome e TailwindCSS!

```bash
npm i @fastify/cors
```


## Aula 03 - Finalizando a aplicação

Na última aula vamos criar a conexão da aplicação com API usando React Query e formulário com React Hook Form e finalizar mais esse projeto para adicionar no seu portfólio e conquistar seu certificado de participação