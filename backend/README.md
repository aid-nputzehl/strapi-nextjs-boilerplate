# Make commands
- ``make start`` --> executes ``docker-compose up -d``
- ``make restart`` --> ``docker-compose stop && docker-compose up -d``
- ``make bash``--> ``docker exex -it ${PROJECT_NAME}_strapi``