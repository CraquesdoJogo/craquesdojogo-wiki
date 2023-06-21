O prejeto sera feito em WEB, devido ao modelo incial ser um MVP faremos front-end como um SPA em vez de um APP nativo (IOS/Android), no entanto o backend deve ser estruturado consirando que ele em breve servida para nutir um APP nativo também.

O projeto será dividido em 2, um para frontend e outro para backend.

## Backend-end (API)

**Técnologia** Node.js

**Linguagem:** Typescript e Javascript

**Banco de dados:** PostigreSQL

**Pacotes:**

* Express -\> servidor
* Sequelize -\> DB e Model
* Jsonwebtoken -\> Geração de tokens de autenticação
* socket.io -\> gerenciar conecxões socket

## Front-end

**Técnologia** Node.js

**Linguagem:** Typescript, Vue e Javascript

**Principais pacotes:**

* Quasar -\> Framework para estilizar o front
* Axios -\> Para gerenciar a API
* Typescript-cookie -\> Gerenciar os cookies
* Prettier -\> Estilização, dependencia do quasar