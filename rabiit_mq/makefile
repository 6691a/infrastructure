SERVICE := 'jenkins'

run:
	export CONTAINER_NAME=$(SERVICE);
	docker-compose up -d --envfile .env
	
stop:
	docker-compose down

log:
	docker logs -f $(SERVICE);

exec:
	docker exec -it $(SERVICE) bash;