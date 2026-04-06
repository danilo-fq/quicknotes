# QuickNotes

Aplicação de anotações rápidas em monorepo com frontend React e microserviços backend.

## Estrutura
- `web/`: Frontend em React 18 com Redux, Formik e Jest.
- `server/`: Microserviços (auth e notes) em Node.js com Express/Fastify, Sequelize e Knex.

## Como rodar
1. Instale dependências: `pnpm install`
2. Rode o frontend: `pnpm --filter web dev`
3. Rode os serviços: Configure e rode cada microserviço em `server/`

## Tecnologias
- Frontend: React, Redux, Formik, Styled Components, SASS, Jest, RTL
- Backend: Node.js, Express/Fastify, Sequelize, Knex, MySQL
- Ferramentas: pnpm, Biome, Docker