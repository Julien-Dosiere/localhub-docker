# Local Hub
### Docker Version

This is the full Local Hub project in a docker-compose package.

Docker-compose is required to run the project. The project is made up of 3 containers. The images would be downloaded from DockerHub repos.

To make it work, just run the `docker-compose -d up` command in the directory containing the docker-compose.yaml file. The frontend should be accessible from your browser on __port 8080__ once the containers up and running. The backend would run on port 3000.

To stop it, run the `docker-compose down` command in the directory containing the docker-compose.yaml file.
