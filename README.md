[![NPM](https://img.shields.io/apm/l/react)](https://github.com/rvlyra/docker-PHP/blob/master/LICENSE)

# docker-PHP
Aplicações usando PHP8, MySQL, Laravel, Ngnix, rodando em container docker.


__Pré requisito:__

| docker v.*

| cadastro ativo em https://hub.docker.com

<br/>


__DOCKER - Conceitos básicos__

Imagens, containers e registry

__image__: é a definição estática de como um container deve ser instanciado.
Para verificar imagens existentes, use o comando:

    docker images
    docker images -a

__container__: é uma instância de uma imagem. O container, uma vez criado, vai existir mesmo que não esteja rodando.
Para verificar quais containers estão ativos:

    docker ps

Para verificar quais containers existem, ainda que estejam inativos:

    docker ps -a


__registry__: é um repositório usado para armazenar imagens. O registry padrão é o Docker Hub, onde você deve criar uma conta. Basta clicar em [hub.docker](https://hub.docker.com/) e se cadastrar gratuitamente. Você também pode adquirir algum plano, caso seu projeto exija serviços outros serviços não disponíveis na conta gratuita.

Para baixar a imagem do PHP, por exemplo, basta usar o comando:

    docker pull php




## Contatos
<!-- ![Linkedin](.assets/email.svg) __Email:__ dev_admin@rvlyra.com.br -->


![Linkedin](.assets/linkedin.svg) __LinkedIn:__ https://linkedin.com/in/rvlyra


<br/>
<hr>
rvlyra, humanos e tecnologias

![logo](.assets/logo.png)