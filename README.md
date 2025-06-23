# Meu Projeto Apache com Docker Compose

Este é um projeto de uma aplicação web simples servida por um container Apache configurado com Docker Compose. A aplicação utiliza HTML, CSS e JavaScript para criar uma página interativa.

## Estrutura do Projeto

meu-projeto-apache/ 
├── docker-compose.yml 
├── app/ │ 
  ├── index.html │ 
  ├── styles.css │ 
  ├── script.js

## Pré-requisitos
- Docker e Docker Compose instalados
- Conhecimento básico em HTML, CSS, JavaScript e Apache

## Como Executar
1. Clone o repositório:
   ```bash
   git clone https://github.com/SEU_USUARIO/meu-projeto-apache.git
   cd meu-projeto-apache

Inicie o container:

docker-compose up -d

Acesse a aplicação em http://localhost:8080.

Para parar o container:

docker-compose down

Funcionalidades

-Exibe uma mensagem "Hello World!" estilizada.

-Inclui um botão que altera o texto e a cor ao ser clicado.

-Tecnologias Utilizadas

*Docker Compose

*Apache (httpd)

*HTML5, CSS3, JavaScript

Autor

Bruno Borges Fagundes

