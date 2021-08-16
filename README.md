# Docker apps

Scripts to run some common programs as docker containers using docker
compose.


## Mysql

To run mysql

```sh
./mysql
```

It will start mysql 5.7 as a container and expose port 3306 locally

The credentials are as follows

```
MYSQL_DATABASE: 'db'
MYSQL_USER: 'user'
MYSQL_PASSWORD: 'password'
MYSQL_ROOT_PASSWORD: 'password'
```
