# gostack-modulo02
Building GoBarber

## To install all dependencies:

```sh
$ yarn
```

## To run docker image:

```sh
$ docker start postgresbarber
$ docker start mongobarber
$ docker start redisbarber
```

## To mount dockers:

```sh
$ docker run --name postgresbarber -p 5434:5432 -d -t postgres
$ docker run --name mongobarber -p 27017:27017 -d -t mongo
$ docker run --name redisbarber -p 6379:6379 -d -t redis:alpine
```

## To start, open 2 command lines:

```sh
$ yarn dev
$ yarn queue
```

## To run all migrates:

```sh
$ yarn sequelize db:migrate
```
