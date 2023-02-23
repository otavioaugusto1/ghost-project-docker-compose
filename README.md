# ghost-project-docker-compose
Ghost é um blog open source. Peguei o docker-compose disponibilizado em (https://hub.docker.com/_/ghost) e decidi fazer algumas alterações com o intuito de estudar Docker:

Adicionei volumes diferentes para as duas aplicações (db e frontend).

Adicionei networks diferentes para as duas aplicações (db e frontend). Vale salientar que o frontend vai ter acesso as duas redes, porém o db só terá acesso a rede privada.

Para executar: 

curl -fsSL https://get.docker.com | bash -> instalaçao do docker

sudo groupadd docker -> adicione ao grupo

sudo usermod -aG docker $USER -> adicione o usuário ao grupo docker

sudo apt update && sudo apt install docker-compose -> instalação do docker-compose

docker-compose up -d -> execução do docker-compose, lembre-se de executar esse comando no mesmo local em que o arquivo docker-compose esteja.
