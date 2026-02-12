REST API - Node.js + Prisma

API REST desenvolvida com Node.js, Express e Prisma ORM para gerenciamento de dados.
O projeto foi criado com o objetivo de praticar a construção de APIs, integração com banco de dados e organização de backend.

Tecnologias utilizadas

Node.js

Express

Prisma ORM  

MongoDB

JavaScript

Funcionalidades

Criar registros

Listar registros

Atualizar registros

Deletar registros

Estrutura do projeto

prisma/ → configuração do banco e schema

serve.js → arquivo principal do servidor

package.json → dependências do projeto

.gitignore → arquivos ignorados pelo Git

Como rodar o projeto

Clone o repositório

Instale as dependências com: npm install

Configure o arquivo .env com sua variável DATABASE_URL

Rode as migrations com: npx prisma migrate dev

Inicie o servidor com: node serve.js

Servidor rodando em: http://localhost:3000

Objetivo

Este projeto foi desenvolvido para aprimorar conhecimentos em desenvolvimento backend, criação de APIs REST e integração com banco de dados utilizando Prisma.

Autor

William Breno
Estudante de Análise e Desenvolvimento de Sistemas
