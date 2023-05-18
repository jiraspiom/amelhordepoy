npm init -y

npm install -D typescript @types/node tsx tsup

npx tsc --init "obs mudar o target para 2020"

npm i fastify

npm i prisma -D

npm i @prisma/client

npx prisma init

- docker start pg
docker run --name postgres-docker -e POSTGRES_PASSWORD=postgres -p 5432:5432 -d postgres

-- criado dados banco
npx prisma migrate dev
    -> create user

npx prisma studio