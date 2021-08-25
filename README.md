use Knex.js - Query Builder

Definição Knex: https://www.webdevdrops.com/nodejs-banco-de-dados-orm-query-builder-driver-nativo/

Example Doc Knex: http://knexjs.org/

Prisma: https://www.prisma.io/dataguide/database-tools/top-nodejs-orms-query-builders-and-database-libraries

TypeORM: https://typeorm.io/#/

Sequelize: https://sequelize.org/

Steps:

Create Project node typescript

$ instal yarn
$ yarn add @types/<nome_do_pacote>
$ yarn add typescript
$ yarn tsc --init
$ yarn add ts-node-dev -D
$ create script package.json

Install database utiul typeORM
$ yarn add typeorm reflect-metadata sqlite3

Create a migration
$ yarn typeorm migration:create -n CreateUsers

running a migration
$ yarn typeorm migration:run

revert a migration
$ yarn typeorm migration:revert

Use Beekeeper to manager database
link: https://www.beekeeperstudio.io/

Descoment tsconfig.json
"emitDecoratorMetadata": true,
"experimentalDecorators": true,

Add lib uuid associate responsability ID
$ yarn add uuid
$ yarn add @types/uuid -D
