# Pontual Front

## PT-BR 

### Sobre

A aplicação Pontual-Front é responsável por ser o recurso visual do projeto Pontual, e que irá consumir a aplicação [Pontual-Back](https://github.com/geovanasilva/pontual-back).

Essa aplicação está sob desenvolvimento. E tem como objetivos:

- Registrar batimento de pontos;
- Detalhar informações pertitentes ao batimento de pontos, como banco de horas, ajustes de batida e afins.

### Tecnologias

- Para facilitar o desenvolvimento da aplicação, é utilizado o framework [Next](https://nextjs.org/)
- [Typescript](https://www.typescriptlang.org/)
- Linting com [ESLint](https://eslint.org/)
- Formatação com [Prettier](https://prettier.io/)
- Linting, verificação de tipo e afins preventivamente nos commits [`husky`](https://github.com/typicode/husky)
- Testes com [Jest](https://jestjs.io/) e [`react-testing-library`](https://testing-library.com/docs/react-testing-library/intro)

### Como executar a aplicação

#### Requisitos

Para que você possa executar a aplicação na sua máquina, você deve garantir primeiro que você tenha instalado o [Node](https://nodejs.org/en/). Com o Node instalado, você já terá acesso ao NPM (gerenciador de pacotes do Node).

Você também pode utilizar o [Yarn](https://yarnpkg.com/)

#### Instalando dependências

Após clonar a aplicação, você deve, através de algum terminal de linha de comando, entrar no diretório da aplicação e executar o seguinte comando:

```bash
$ npm install
```

Esse comando poderá levar alguns segundos ou até minutos (vai variar de acordo com a velocidade de download de sua internet) para terminar de ser executado.

#### Executando aplicação

Após ter realizado os passos anteriores, basta executar o seguinte comando no seu terminal de linha de comando:

```bash
$ npm start
```

### Como testar a aplicação

Após ter clonado o projeto e instalado as dependências, para você realizar os testes da aplicação você deve executar os seguintes comandos:

```bash
# Para testes unitários
$ npm run test

# Para testes de lint, verificação de tipos e unitários
$ npm run test-all
```

### Mantenedores

Os mantenedores dessa aplicação são:
- [Geovana Silva](https://github.com/geovanasilva)
- [Leonardo Santos](https://github.com/leonardossev)

### Licença

Este projeto utiliza a licença [MIT](https://github.com/geovanasilva/pontual-front/blob/master/LICENSE).