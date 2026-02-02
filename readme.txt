docker ps
docker-compose up -d --build mssql
docker-compose up -d --build kafka
docker-compose up -d --build kafka-ui
docker-compose up -d --build smilecdr

Kafka: http://localhost:8080/
Smile CDR: http://localhost:9100/

docker logs -f smilecdr
