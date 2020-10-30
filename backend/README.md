# Getting started
- ``docker-compose up -d --build``
- Strapi Installation will start automatically, but takes time
- about 5 minutes
- can see status in container bash with ``ps -ef``

# Make commands
- ``make start`` --> executes ``docker-compose up -d``
- ``make restart`` --> ``docker-compose stop && docker-compose up -d``
- ``make bash``--> ``docker exex -it ${PROJECT_NAME}_strapi``