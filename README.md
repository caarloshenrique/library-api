# library-api

> :blue_book: Uma API NodeJS para gerenciamento de livros de uma biblioteca.

## :rocket: Tecnologias utilizadas

O projeto foi feito utilizando as seguintes tecnologias:

- [NodeJS](https://nodejs.org/en/)
- [ExpressJS](https://expressjs.com/pt-br/)
- [MongoDB](https://www.mongodb.com/)
- [Docker](https://www.docker.com/)
{...}

## :clipboard: Requisitos 

* [NodeJS LTS (ou superior)](https://nodejs.org/en/)
* [MongoDB](https://www.mongodb.com/)
* [Docker (opcional)](https://www.docker.com/)

## :hammer_and_wrench: Uso

```
$ git clone https://github.com/caarloshenrique/library-api.git
$ cd library-api
$ yarn
$ cp .env.example .env # ajustar os parâmetros de configuração
$ yarn dev
```

### :whale: Executando o Docker via Compose

O arquivo `docker-compose.yml` já contém as imagens para sistema de banco de dados MongoDB, com seu devido sistema de administração.

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

## :page_facing_up: Licença
Este projeto é desenvolvido sob a licença MIT. Veja o arquivo [LICENSE](LICENSE.md) para saber mais detalhes.

<p align="center" style="margin-top: 20px; border-top: 1px solid #eee; padding-top: 20px;">Feito com :green_heart: por <strong> Carlos Henrique da Costa Silva </strong> </p>
