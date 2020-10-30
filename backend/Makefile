include .env

start: 
	docker-compose up -d
restart:
	docker-compose stop
	docker-compose up -d

bash:
	docker exec -it ${PROJECT_NAME}_strapi bash