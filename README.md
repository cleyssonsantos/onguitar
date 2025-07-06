# on-guitar

Projeto que visa criar um espaço de valor para os amantes da guitarra.

# Como executar

## Instalando dependências

nvm install - Buscará o arquivo .nvmrc "run commands"

Para instalar apenas para uma dependência de desenvolvimento: npm install --save-dev lib@0.0.0

## Para instalar as dependências do package.json

npm install

## Rodando o projeto local

npm run dev

## Executando os testes

npm run test
npm run test:watch

## Subindo banco de dados

docker compose -f infra/compose.yaml up -d

## Usando commitizen para facilitar commits no padrão Conventional Commits

npm run commit
