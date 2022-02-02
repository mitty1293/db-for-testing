# db-for-testing
Database for testing
## Deploy
```
$ docker-compose up -d
```
## MySQL
### Log in
```
$ mysql --user=user --password=password
```
### Change database
```
$ use test_mysql;
```
When connecting from another container on the same host, specify `host.docker.internal` as the destination host.
