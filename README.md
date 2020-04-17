# library-api

> :blue_book: Uma API NodeJS para gerenciamento de livros de uma biblioteca.

## Requisitos

- NodeJS LTS (ou superior)
- MongoDB
- Docker (opcional)

### Uso

1. Clonar o repositório:

```sh
$ git clone https://github.com/caarloshenrique/library-api.git
$ cd library-api
$ node ./setup.js
$ yarn
$ cp .env.example .env # ajustar os parâmetros de configuração
$ yarn dev
```

### Executando o Docker via Compose

O arquivo `docker-compose.yml` já contém a imagens para sistemas de banco de dados Postgres, MongoDB e Redis, com seus devidos sistemas de administração.

Para subir as imagens execute o comando no projeto:

```bash
$ docker-compose up
```

#### Serviços

##### MongoDB

Painel de Administração:

* Administração: http://localhost:8001

Banco de Dados:

* Usuário: `root`
* Senha: `secret`

## Licença

MIT
