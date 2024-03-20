# Instructions for sub directories

## nginx
### nginx/http - DRAFT / NOT TESTED
1. `docker-compose -f docker-compose.prod.yaml build`
2. `docker-compose -f docker-compose.prod.yaml up`
3. Nginx should be running on http://127.0.0.1/

### nginx/https
1. `docker-compose -f docker-compose.prod.yaml build`
2. `docker-compose -f docker-compose.prod.yaml up`
3. Nginx should be running on https://127.0.0.1/

## php
### php/plain_php
1. `docker-compose -f docker-compose.prod.yaml build`
2. `docker-compose -f docker-compose.prod.yaml up`
3. Nginx should be serving php on http://127.0.0.1:180/