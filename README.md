# TestFramework-DockerCompose

	1. docker swarm init
	2. docker stack deploy -c docker-compose.yml TestFramework
	3. docker stack rm TestFramework
	4. docker swarm leave --force
	5. docker container prune
