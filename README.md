## ENGLISH
Hi!
This is a fullstack project study of a ecommerce system.
- Frontend was written in Typescript, HTML and CSS using Angular;
- Backend was written in Java using Spring Boot;

The easiest way to deploy the project in your machine is using docker. You can follows steps as in https://youtu.be/y6VTooNJ1fU . Or the below instructions.
I've written a docker-compose file that is in this repository.
Using the command line enter in the folder of this project and execute the command

### docker compose up -d

it can take some minutes to download the container images and do the deploy.
It will deploy the backend app, the frontend app and a mysql container, that i added in case you didn't have it in your machine.

The project is not finished yet! But you can see and test some functionalities.

After the deploy using docker compose you can se the backend endpoints in [http://localhost:8080/swagger-ui/index.html#/](http://localhost:8080/swagger-ui/index.html#/) and the frontend available (for now, only department hierarchy management) in [localhost](http://localhost/)

## PT
Olá,
Este é um projeto de estudo fullstack de um sistema de ecomerce.
  -  O frontend foi escrito em Typescript, HTML e CSS usando Angular;
  -  O backend foi escrito em Java usando o Spring Boot;
    
O jeito mais fácil de rodar esse projeto em sua máquina é utilizando o docker.
https://youtu.be/ybPAPt6dwfY nesse video tem os passos do deploy ou siga as instrucoes abaixo.
Escrevi um documento docker compose que está neste repositório.
Usando a linha de comando, entre na pasta raiz deste projeto e execute o comando

### docker compose up -d

Pode levar alguns minutos até baixar as imagens e começar a rodar o sistema.
Ele subirá um container para o backend, um para o frontend e outro para o banco de dados que adicionei ao docker compose caso você não o tivesse em sua maquina.
 
O projeto ainda não está finalizado! Porém você pode ver e testar algumas funcionalidades.
Após o deploy usando o docker compose você pode ver os endpoints do backend em [http://localhost:8080/swagger-ui/index.html#/](http://localhost:8080/swagger-ui/index.html#/)
e as funcionalidades criada no frontend (por enquanto, somente gestão da hierarquia de departamentos) ficou em [localhost](http://localhost/)
