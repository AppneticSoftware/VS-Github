#Variables

Variables can be changed in the .env file. More here. https://create-react-app.dev/docs/adding-custom-environment-variables/

#Setup Docker

Docker can build images automatically by reading the instructions from a Dockerfile. More here: https://docs.docker.com/engine/reference/builder/

#This project needs a connection to a docker container to read the database and visualize it at the webbrowser.

docker-compose up -dto run docker

The docker-compose up command aggregates the output of each container. When the command exits, all containers are stopped. Running docker-compose up --detach starts the containers in the background and leaves them running. More here: https://docs.docker.com/compose/reference/up/
