# Middlewares Challenge

Desafio complementar do conteúdo estudado nas aulas do Chapter I da trilha de NodeJS do Bootcamp Ignite da Rocketseat

## :hammer_and_wrench: Ferramentas

- [cors](https://www.npmjs.com/package/cors)
- [express](https://expressjs.com/pt-br/)
- [uuid](https://www.npmjs.com/package/uuid)
- [nodejs](https://nodejs.org/en/docs/)
- [nodemon](https://www.npmjs.com/package/nodemon)
- [jest](https://jestjs.io/pt-BR/)
- [supertest](https://www.npmjs.com/package/supertest)

## :desktop_computer: Padronização de código

- [EditorConfig](https://editorconfig.org/)

## :rocket: Executando o projeto

```bash
// Instale as dependências

yarn install

// Concluindo a instalação rode

yarn dev
```

### :heavy_check_mark: Requisitos

- [x] checksExistsUserAccount deve verificar a existência do usuário com base no username passado;
- [x] checksCreateTodosUserAvailability deve verificar se o usuário está no plano grátis e se ainda não possui 10 todos;
- [x] checksTodoExists deve validar o usuário, validar que o id seja um uuid e também deve validar que esse id pertence a um todo do usuário informado.;
- [x] findUserById funcionamento semelhante ao middleware checksExistsUserAccount mas a busca pelo usuário deve ser feita através do id de um usuário passado por parâmetro na rota;
