# es6-listagem-repositorios-github
Uma aplicação para listar os repositórios do GitHub adicionados pelo usuário. Aplicação feita como forma de prática e estudo das linguagens e ferramentas.

## Começando

Essas instruções fornecerão uma cópia do projeto em execução na sua máquina local para fins de desenvolvimento e teste.

### Pré-Requisitos

O que você precisa para instalar a aplicação e como instalá-la:


* [Noje.js](https://nodejs.org/en/) - um interpretador de JavaScript 
* [Yarn](https://yarnpkg.com/getting-started/install) - um gerenciador de pacotes



### Instalação e Dependência

Após realizar a instação do Node.js e Yarn, você pode verificar se tudo ocorreu bem verificando a versão das ferramentas pelo terminal do seu computador, dessa forma:

```
node -v
yarn -v
```

E então, via terminal, acesse a pasta do clone deste repositório e execute o comando abaixo para instalar as dependências do projeto:

```
yarn
```

Agora o projeto está pronto para ser utilizado.

## Executando os testes

Para executar a aplicação em modo de desenvolvimento, utilize o comando:

```
yarn dev
```

### Dúvidas sobre o modo de testes

O modo de testes utiliza o [webpack-dev-server](https://www.npmjs.com/package/webpack-dev-server) para simular um servidor de produção.
Devido a isso o bundle.js (arquivo convertido de ES6 para Javascript - browsers que ainda não tem compatibilidade com ES6 dessa forma rodarão nosso código normalmente) ficará embutido na nossa aplicação, ficando "invisível" como um arquivo nas pastas.

### Projeto em produção

Para executar o projeto em modo de produção, basta utilizar o comando:

```
yarn build
```

## Construído com

* [ES6](https://www.w3schools.com/js/js_es6.asp)
* [Noje.js](https://nodejs.org/en/) - um interpretador de JavaScript 
* [Yarn](https://yarnpkg.com/getting-started/install) - um gerenciador de pacotes
* [Axios](https://github.com/axios/axios) - módulo para consumir APIs

## Contribuições

Contribuições são sempre bem-vindas! Para contribuir lembre-se sempre de adicionar testes unitários para as novas classes com a devida documentação.

## Versionamento

Foi utilizado o [Git](https://git-scm.com/) para o controle de versão.

## Autores

* **Felipe Fernandes** - *Estudo de linguagem e ferramentas* - [dev-fer](https://github.com/dev-fer)

## Agradecimentos

* https://rocketseat.com.br/ - uma plataforma de educação em tecnologia.


