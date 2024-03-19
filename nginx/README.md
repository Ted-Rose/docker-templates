# Instructions for sub directories

## http - DRAFT / NOT TESTED
1. `docker-compose -f docker-compose.prod.yaml build`
2. `docker-compose -f docker-compose.prod.yaml up`
3. Nginx should be running on https://127.0.0.1/

## https
1. `docker-compose -f docker-compose.prod.yaml build`
2. `docker-compose -f docker-compose.prod.yaml up`
3. Nginx should be running on https://127.0.0.1/