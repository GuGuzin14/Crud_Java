📚 Projeto Spring Boot - API REST com Java 21

Este projeto foi criado utilizando o Spring Initializr com Java 21 e Maven, tendo como objetivo servir como base para construção de uma API REST simples utilizando boas práticas do ecossistema Spring.

🚀 Tecnologias Utilizadas

Java 21

Spring Boot

Maven

H2 Database

JPA (Hibernate)

Postman (para testes da API)

⚙️ Dependências Utilizadas

O projeto foi gerado no Spring Initializr com as seguintes dependências:

🌐 Spring Web

Dependência responsável por permitir a criação de APIs REST.

Fornece suporte a:

@RestController

@RequestMapping

@GetMapping, @PostMapping, etc.

Utiliza o servidor embarcado Tomcat.

Trabalha com requisições HTTP (GET, POST, PUT, DELETE).

🧩 Lombok

Biblioteca que reduz código repetitivo (boilerplate).

Gera automaticamente:

Getters e Setters (@Getter, @Setter)

Construtores (@AllArgsConstructor, @NoArgsConstructor)

Builder (@Builder)

toString, equals, hashCode

Deixa as entidades mais limpas e organizadas.

⚠️ É necessário instalar o plugin do Lombok na IDE.

🗄️ Spring Data JPA

Facilita o acesso e manipulação de dados no banco.

Trabalha com:

@Entity

@Repository

JpaRepository

Permite criar consultas automaticamente apenas pelo nome do método.

Utiliza o Hibernate como implementação padrão de ORM.

💾 H2 Database

Banco de dados em memória, ideal para testes e desenvolvimento.

Leve e rápido.

Não precisa de instalação.


🧪 Testando a API com o Postman

O Postman é uma ferramenta muito utilizada para testar APIs REST.

Ele permite:

Enviar requisições HTTP (GET, POST, PUT, DELETE)

Enviar dados em JSON

Visualizar respostas da API

Testar endpoints sem precisar de front-end

Como testar:

Abrir o Postman.

Criar uma nova requisição.

Selecionar o método (GET, POST, etc.).

Informar a URL, por exemplo:

http://localhost:8080/usuario

Se for POST ou PUT, enviar o JSON no Body.

Clicar em Send para visualizar a resposta.


🎯 Objetivo do Projeto

Este projeto serve como base para:

Criar APIs REST com Spring Boot

Trabalhar com banco de dados em memória

Aplicar arquitetura em camadas (Controller, Service, Repository)

Realizar testes utilizando o Postman

Praticar desenvolvimento backend com Java 21

📌 Informações do Projeto (Spring Initializr)

Project: Maven

Language: Java

Spring Boot: 4.0.3

Packaging: Jar

Java: 21

Dependências:

Spring Web

Lombok

Spring Data JPA

H2 Database

Possui console web para visualizar as tabelas.

Ideal para aprendizado e testes locais.
