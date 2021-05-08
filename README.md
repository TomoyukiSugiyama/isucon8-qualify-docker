# isucon8-qualify-docker

# Env
## app

```
root@59306196660d:/home/isucon/torb/webapp/go# go version
go version go1.10.8 linux/amd64
```

## db

```
Server version: 5.5.64-MariaDB-1~trusty mariadb.org binary distribution
```

# Build

```bash
$ docker-compose up -d
```

Initialize DB

```bash
$ docker exec isucon8-qualify-docker_db_1 ./init.sh
```

# Access web

`http://localhost:8080`

# Bench

```bash
$ docker-compose up bench
```
