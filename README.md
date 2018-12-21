# Docker Compose environment for Django

## &nbsp;&nbsp;&nbsp;&nbsp;~ Please put your project to $(pwd)/docker/django/app/

## &nbsp;&nbsp;&nbsp;&nbsp;~ If you want to add some python library, you can edit $(pwd)/docker/django/requirements.txt

## &nbsp;&nbsp;&nbsp;&nbsp;~ If you want to use elasticsearch, you can use elasticsearch container in django container with 'es' alias.

### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; \# For example; 
### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; \-> curl http://es:9200/_cluster/health?pretty=true

## &nbsp;&nbsp;&nbsp;&nbsp;~ Actually, you can use postgresql container in django container with 'postgres_db' alias.

### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; \# For example; 
### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; \-> ping postgres_db

## ~ How do I work with docker-compose
### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; \# For running compose  

### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ~ docker-compose up -d 

### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; \# For stopping compose  

### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ~ docker-compose down