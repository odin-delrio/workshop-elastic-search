# Workshop elastic search

## Requirements
- docker
- docker-compose
- java 1.8

## Run
```bash
docker-compose up
# Running only elastic search
docker-compose up elasticsearch
```

## Useful links
- http://localhost:9200/_plugin/head/ ES index viewer
- http://localhost:9200/_plugin/HQ/ Another ES viewer
- http://localhost:9200/_cluster/health?pretty=true
- http://localhost:9200/_plugin/marvel
- http://localhost:9200/_plugin/bigdesk

## Basic queries for Postman
[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/0f9f2b1691b280932aa7)

### Related
The spring boot application is based on the JDCB example in https://github.com/scm-spain/howto-spring-cloud
