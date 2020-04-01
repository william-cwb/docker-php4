<strong>Container rodando PHP4.</strong>

O que significa os comandos do docker-compose.yaml

<strong>#version: </strong>
A versão significa a versão 3 do arquivo yaml

<strong>#services:</strong>
php-server é o nome dos serviços, pode-se dar qualquer nome.

<strong>#image:</strong>
Corresponde a imagem que se encontra lá dentro do DockerHub.

<strong>#volumes:</strong>
A parte './' significa que vai pegar todo o projeto que está na raiz e vai mandar para dentro do container para dentro do apache, que se localize em: '/var/www/html'.

<strong>#ports:</strong>
A primeira porta correnponde a porta da sua máquina e a segunda porta corresponde à porta do container.
