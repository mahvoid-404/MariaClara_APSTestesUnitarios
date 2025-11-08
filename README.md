# Projeto CRUD Produtos com Testes Unitários

## Descrição
Este é o projeto CRUD de produtos em Java com Spring Boot, com testes unitários implementados conforme o guia do professor.

## Requisitos Atendidos do Guia
- Dependência `spring-boot-starter-test` adicionada no `pom.xml`.
- Testes para camada de serviço (`ProdutoServicoTest.java`): cadastro com sucesso, nome vazio, marca vazia.
- Testes para camada de controle (`ProdutoControleTest.java`): GET /listar e POST /cadastrar.
- Usado Mockito para mocks e MockMvc para simular HTTP.
- Rodado `mvnw.cmd clean test` com `BUILD SUCCESS`.

## Como Rodar o Projeto
1. Abra o CMD na pasta do projeto.
2. Rode a aplicação:
