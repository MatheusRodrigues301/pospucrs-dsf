// cria um container ubuntu
docker container run -it ubuntu /bin/bash // -i permite interação com o cointainer -t abre o (TTY) terminal. Podemos unificar os comando para -it

apt update // atualiza lista de repositórios

apt install curl // instala a aplicação curl

curl 

// como criar uma imagem docker (dockerfile)

docker build -t <nome do container> -f Dockerfile .
docker image ls
docker containar run -it <nome do container>


docker image prune //limpa imagens não utilizadas

docker tag matheusrodrigues301/aula02-ubuntu-curl:v1 matheusrodrigues301/aula02-ubuntu-curl:latest // alterar tag utilizada