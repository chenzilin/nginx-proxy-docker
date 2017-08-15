Usage:

	1. Run Container
		sudo docker-compose up -d

	2. Enter Container
		sudo docker exec -it nginx-proxy-docker /bin/bash

	3. Stop Container
		sudo docker stop nginx-proxy-docker


Reference:

Create Image:

	cd nginx-proxy-docker/

	sudo docker build -t nginx-proxy-docker:v1.0 .

List Images:

	sudo docker images

Remeve Image:

	sudo docker rmi 7d9495d03763

	sudo docker image remove 7d9495d03763

Run Container:

	sudo docker-compose up -d

List Containers:

	sudo docker ps

	sudo docker ps -a

Check Container Log:

	sudo docker logs nginx-proxy-docker

Remove Container:

	sudo docker rm d48b68282c03
