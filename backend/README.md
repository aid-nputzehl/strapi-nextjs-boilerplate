# Strapi docker-compose Setup

## Getting started
- ``docker-compose up -d --build``
- Strapi Installation will start automatically, but takes time
- about 5 minutes
- can see status in container bash with ``ps -ef``
- find site here: [http://localhost:1337](http://localhost:1337)
- add new account

## Make commands
- ``make start`` --> executes ``docker-compose up -d``
- ``make restart`` --> ``docker-compose stop && docker-compose up -d``
- ``make bash``--> ``docker exex -it ${PROJECT_NAME}_strapi``