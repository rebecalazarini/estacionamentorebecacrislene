# Implantação de back-end com a Vercel

## Tecnologias Utilizadas
- Node.js
- Express
- Prisma
- MySQL - MariaDB

## Como Executar Localmente
- 1 Clone o repositório, crie o arquivo `.env` com as variáveis de ambiente necessárias


- 3 Instale as dependências: `npm install`
- 4 Implante o Banco de Dados `npx prisma migrate dev --name init`
- 5 Inicie o servidor: `npm run dev`

## Rotas
- GET /veiculos
- GET /veiculos/:placa
- POST /veiculos
- PATCH /veiculos/:placa
- DELETE /veiculos/:placa

- GET /estadias
- GET /estadias/:placa
- POST /estadias
- PATCH  /estadias/:placa
- DELETE /estadias/:id
