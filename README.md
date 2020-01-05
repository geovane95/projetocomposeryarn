# Projeto Composer Yarn
> Projeto criado a fim de exercitar algumas técnologias e utilizar como portfólio de desenvolvimento, o mesmo foi criado utilizando composer como gerenciador de dependencias do PHP e Yarn para gerenciar as dependencias do Front-End, a ideia é que o mesmo também fique disponível para utilização como base para qualquer pessoa que queira utilizar alguma parte ou todo o projeto.

> Para mais projetos acesse: _[Minha Página no GitHub][meugit]_.

[![NPM Version][npm-image]][npm-url]
[![Build Status][travis-image]][travis-url]
[![Downloads Stats][npm-downloads]][npm-url]

O projeto foi desenvolvido com as tecnologias PHP, HTML, CSS, JavaScript, MySql, Composer, Yarn, Guzzle e Datatables.

![](../header.png)

## Front-End

É necessário realizar a instalação do Yarn através do comando:

```sh
yarn install
```

## Back-End

É necessário realizar a instalação das dependecias do composer.

_É necessário ter no minimo o PHP 7.2.0 no servidor que a aplicação irá rodar._

```sh
composer install
```

## Configuração para Desenvolvimento

Descreva como instalar todas as dependências para desenvolvimento e como rodar um test-suite automatizado de algum tipo. Se necessário, faça isso para múltiplas plataformas.

```sh
make install
npm test
```

## Histórico de lançamentos

* 0.0.1
    * MUDANÇA: Atualização de docs (código do módulo permanece inalterado)
* 0.2.0
    * MUDANÇA: Remove `setDefaultXYZ()`
    * ADD: Adiciona `init()`
* 0.1.1
    * CONSERTADO: Crash quando chama `baz()` (Obrigado @NomeDoContribuidorGeneroso!)
* 0.1.0
    * O primeiro lançamento adequado
    * MUDANÇA: Renomeia `foo()` para `bar()`
* 0.0.1
    * Criado o projeto com as dependencias do Yarn e do Composer, criado a estrutura do projeto e página inicial.

## Meta

Geovane Jr. – [@geovane95](https://linkedin.com/in/geovane95) – geovane.a.f.junior@gmail.com

Distribuído sob a licença MIT.

[https://github.com/geovane95/](https://github.com/geovane95/)

## Contribuições

1. Faça o _fork_ do projeto (<https://github.com/yourname/yourproject/fork>)
2. Crie uma _branch_ para sua modificação (`git checkout -b feature/fooBar`)
3. Faça o _commit_ (`git commit -am 'Add some fooBar'`)
4. _Push_ (`git push origin feature/fooBar`)
5. Crie um novo _Pull Request_

[npm-image]: https://img.shields.io/npm/v/datadog-metrics.svg?style=flat-square
[npm-url]: https://npmjs.org/package/datadog-metrics
[npm-downloads]: https://img.shields.io/npm/dm/datadog-metrics.svg?style=flat-square
[travis-image]: https://img.shields.io/travis/dbader/node-datadog-metrics/master.svg?style=flat-square
[travis-url]: https://travis-ci.org/dbader/node-datadog-metrics
[meugit]: https://github.com/geovane95/