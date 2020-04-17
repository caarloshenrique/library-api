# library-api

> :blue_book: Uma API NodeJS para gerenciamento de livros de uma biblioteca.

## Requisitos :clipboard:

* [NodeJS LTS (ou superior)](https://nodejs.org/en/)
* [MongoDB](https://www.mongodb.com/)
* [Docker (opcional)](https://www.docker.com/)

### Uso :hammer_and_wrench:

```
$ git clone https://github.com/caarloshenrique/library-api.git
$ cd library-api
$ yarn
$ cp .env.example .env # ajustar os parâmetros de configuração
$ yarn dev
```

### Executando o Docker via Compose :whale:

O arquivo `docker-compose.yml` já contém as imagens para sistema de banco de dados MongoDB, com seu devido sistema de administração.

Para subir as imagens execute o comando no projeto:

```bash
$ docker-compose up
```

#### Serviços :wrench:

##### MongoDB :herb:

Painel de Administração:

* Administração: http://localhost:8001

Banco de Dados:

* Usuário: `root`
* Senha: `secret`

## Licença :page_facing_up:

[MIT](/LICENSE) &copy; Carlos Henrique da Costa Silva
