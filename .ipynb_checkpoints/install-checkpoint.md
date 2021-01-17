# Instalação mongodb

- Para instalar, acessar o site, e seguir as orientações para cada OS;

## Linux Ubuntu 18.04
1 - wget -qO - https://www.mongodb.org/static/pgp/server-4.4.asc | sudo apt-key add -

2 - echo "deb [ arch=amd64,arm64 ] https://repo.mongodb.org/apt/ubuntu bionic/mongodb-org/4.4 multiverse" | sudo tee /etc/apt/sources.list.d/mongodb-org-4.4.list

3 - sudo apt-get update

4 - sudo apt-get install -y mogodb-org

5 - verificar se a criação das pastas está correta: cd /var/lib/mongodb

6 - Verificar o sistema: ps --no-headers -o comm 1

7 - se systemctl, iniciar mongodb: sudo systemctl start mongodb

8 - Verificar status: sudo systemctl status mongodb

9 - Parar servidor mongodb: sudo systemctl stop mongodb

10 - Com o servidor iniciado, comando mongo inicia a aplicacao para uso




