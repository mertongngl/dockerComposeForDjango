# Docker Compose environment for Django - Elasticsearch - Postgre Sql

## Setup
Put your project to $!PWD/docker/django/app/
```
$ git clone https://github.com/mertongngl/dockerComposeForDjango.git
$ cd dockerComposeForDjango/
$ cp 'your source code for django' docker/django/app
```

## Adding an externel library

If you want to add some python library, you can edit $(pwd)/docker/django/requirements.txt

## Using Elasticsearch 
If you want to use elasticsearch, you can use elasticsearch container in django container with 'es' alias.

### For example; 
`curl http://es:9200/_cluster/health?pretty=true`

You can use postgresql container in django container with 'postgres_db' alias. You can try to ping postgres_db now.

## How do I work with docker-compose
### For running compose  
`$ docker-compose up -d` 

### For stopping compose  
`docker-compose down`
