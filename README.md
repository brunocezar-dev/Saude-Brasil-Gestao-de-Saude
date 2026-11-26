# Saúde Brasil — Gestão de Saúde

Agenda demonstrativa de unidades e consultas

## Como executar a interface
1. Extraia o ZIP e abra a pasta no VS Code.
2. Instale a extensão Live Server.
3. Clique com o botão direito em `index.html` e escolha **Open with Live Server**.

A interface é uma demonstração front-end com persistência em `localStorage`. O backend Spring Boot é uma API inicial separada; a integração tela/API ainda precisa ser implementada e validada.

## Backend Java
Requisitos: JDK 17+, Maven e MySQL 8+. Crie o banco `saude_brasil`, ajuste a senha em `backend/src/main/resources/application.properties`, abra o terminal na pasta `backend` e execute `mvn spring-boot:run`.

API: `http://localhost:8081/api/appointments`

## Tecnologias
Java 17, Spring Boot, Spring Data JPA, MySQL, HTML, CSS e JavaScript.

## Aviso
Projeto acadêmico inspirado em fluxos de gestão de saúde pública. Não é um sistema oficial do Ministério da Saúde ou do SUS. Use somente dados fictícios; não insira dados reais ou informações pessoais de saúde.
