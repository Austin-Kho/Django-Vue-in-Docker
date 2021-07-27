# Django + Vue (vue-cli + webpack) in Nginx + MariaDB from Docker

## Requirement in your system

- docker
- docker-compose
- node (with yarn)

## Usage

### Write environments in docker-compose.yml
- required: 
  - MYSQL_DATABASE
  - MYSQL_ROOT_PASSWORD
  - MYSQL_USER
  - MYSQL_PASSWORD
  - DATABASE_NAME 
  - DATABASE_USER
  - DATABASE_PASSWORD
  - SERVER_NAME

### Build and run
```bash
docker-compose up -d --build
```

### Vue (Single Page Application) Development

```bash
cd application/vue3
yarn
```

Vue application development -> webpack dev server on.

```bash
yarn serve
```

or Vue application deploy -> yarn build

```bash
yarn build
```

now, go to [http://localhost/](http://localhost/) or [http://127.0.0.1/](http://127.0.0.1/)

and Develop it!


### Reference
- [Python](www.python.org)
- [Docker](www.docker.com)
    - [Docker compose](docs.docker.com/compose)
- [Django](www.djangoproject.com)
- [MariaDB](mariadb.org)
- [Nginx](https://www.nginx.com/)
- [Node](https://nodejs.org/ko/)
- [Yarn](https://yarnpkg.com/)

