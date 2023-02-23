# ghost-project-docker-compose
Ghost é um blog open source. Peguei o docker-compose disponibilizado em (https://hub.docker.com/_/ghost) e decidi fazer algumas alterações com o intuito de estudar Docker:

Adicionei volumes diferentes para as duas aplicações (db e frontend).

Adicionei networks diferentes para as duas aplicações (db e frontend). Vale salientar que o frontend vai ter acesso as duas redes, porém o db só terá acesso a rede privada.
