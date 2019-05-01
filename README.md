# Docker-stury-for-rails

## Ruby version
```bash
2.6.1
```

## Rails version
```bash
5.2.2
```

## For Docker

## Install System dependences
```bash
$ docker-compose run --rm app bundle install
```

## Database creation
```bash
$ docker-compose run --rm app bundle exec rails db:create
```

## Database initialization
```bash
$ docker-compose run --rm app bundle exec rails db:migrate:reset
```

## How to run the test suite
```bash
$ docker-compose run --rm app bundle exec rails test
```

## Execute rails server
```bash
$ docker-compose up
```
