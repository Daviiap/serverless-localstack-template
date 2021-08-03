# SERVERLESS + LOCALSTACK TEMPLATE

Template de projeto utilizando serverless e localstack para simular ambiente da

aws localmente.

## Requisitos:
- npm / yarn
- serverless
- localstack
- docker

## Rodando o projeto:

Para rodar o projeto em modo de desenvolvimento basta digitar o comando 

`yarn start-dev` para iniciar a execução do docker-compose.

Então basta rodar `yarn deploy dev` para fazer o deploy da aplicação 

localmente e começar a usa-la.

## SCRIPTS:

- `start-dev`: roda o docker com o localstack em segundo plano.
- `deploy {{stage}}`: faz o deploy da aplicação no stage indicado.

