# guacamole-docker
my own docker file to start guacamole


## Install
    cd /opt; wget https://raw.githubusercontent.com/josemlwdf/guacamole-docker/refs/heads/main/docker-compose.yaml; sudo apt update && sudo apt  install docker-compose -y; docker-compose up -d; sleep 5; curl localhost:8080/guacamole
