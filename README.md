##Container rodando PHP4.

O que significa os comandos do docker-compose.yaml

##version
A versão significa a versão 3 do arquivo yaml

##services
php-serve é o nome dos serviços, pode-se dar qualquer nome.

##image
Corresponde a imagem que se encontra lá dentro do DockerHub.

##volumes:
A parte './' significa que vai pegar todo o projeto que está na raiz e vai mandar para dentro do container para dentro do apache, que se localize em: '/var/www/html'.

##ports
A primeira porta correnponde a porta da sua máquina e a segunda porta corresponde à porta do container.