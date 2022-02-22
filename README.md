# db-for-testing
Database for testing
## MySQL
### Deploy
```
$ docker-compose -f mysql/docker-compose.mysql.yml up -d
```
### Log in
```
$ mysql --user=user --password=password
```
### Change database
```
$ use test_mysql;
```
When connecting from another container on the same host, specify `host.docker.internal` as the destination host.
