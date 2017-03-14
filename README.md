# Docker ELK stack

Based on the official images:

* [Elasticsearch](https://registry.hub.docker.com/_/elasticsearch/)
* [Logstash](https://registry.hub.docker.com/_/logstash/)
* [Kibana](https://registry.hub.docker.com/_/kibana/)

# Installation
#### Requirements
1. [Docker](https://docs.docker.com)
2. [Docker-compose](https://docs.docker.com/compose)
3. Allocate enough memory to your VM :
```sh
sudo sysctl -w vm.max_map_count=262144
```

#### Clone the repository
```sh
git clone https://github.com/Ludotes/docker-elk.git
```

#### Run docker-compose
```sh
sudo docker-compose run
```

# Configuration
Edit *docker-compose.yml* in an editor.