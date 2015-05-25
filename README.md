# Java Jobs [![Code Climate](https://codeclimate.com/github/kaiomagalhaes/java-jobs/badges/gpa.svg)](https://codeclimate.com/github/kaiomagalhaes/java-jobs) [![Build Status](https://semaphoreci.com/api/v1/projects/71b7b15d-18bc-44d1-b97e-b663d1bdfad8/432469/badge.svg)](https://semaphoreci.com/kaiomagalhaes/ruby-jobs)

Repositório do Java Jobs [www.javajobs.me](http://www.javajobs.me/).

O projeto original foi criado com o intuito de mostrar ofertas de emprego para desenvolvedores Ruby.
Vendo as dificuldades para encontrar desenvolvedores Java fiz o fork do projeto [ruby-jobs](https://github.com/ruby-jobs/ruby-jobs) e realizei as modificações necessárias.

Projeto sem fins lucrativos.

## Instalação

Clone o repositório

```
git clone https://github.com/kaiomagalhaes/java-jobs.git
```

Instale as dependências

```
bundle install
overcommit --install
```

Copie o conteúdo do arquivo `database.yml.example` e crie um arquivo `database.yml`. Nele configure seus dados de acesso ao `postgresql`

Crie o banco, rode as migrations e opcionalmente rode os seeds para ter uma base de dados inicial.

```
rake db:create
rake db:migrate
rake db:seed
```

Rode os testes :+1:

```
rspec
```

Rode a aplicação :grin:

```
rails server
```
