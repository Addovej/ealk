# EALK (Elasticsearch APM-server Logstash Kibana)

git clone https://github.com/Addovej/eak.git
docker-compose up -d

- Elasticsearch on `localhost:9200`
- APM-Server on `localhost:8200`
- Logstash on `localhost:9600/8089`
- Kibana on `localhost:5601`

####Wait for available all services:
`docker ps` (near uptime status should be (healthy))
