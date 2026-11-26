# Baozi Store - API REST

Trabalho de Desenvolvimento Web Back-End (UNINTER).
Java 17+, Spring Boot 4.1, Spring Data JPA, banco H2 em memória.

## Como executar

No IntelliJ IDEA, abra a pasta do projeto, aguarde o Maven baixar as dependências e execute `BaoziStoreApplication`.
Com Maven instalado, também é possível usar `mvn spring-boot:run`.

A API sobe em `http://localhost:8080`.

## Testes no Postman

Importe `postman/baozi-store.postman_collection.json` e execute os requests na ordem numérica.
Os requests usam o id 1. Para recomeçar, reinicie a aplicação.

## Endpoints

| Entidade | POST | GET (todos) | GET por id | DELETE |
|---|---|---|---|---|
| Cliente | /clientes | /clientes | /clientes/{id} | /clientes/{id} |
| Produto | /produtos | /produtos | /produtos/{id} | /produtos/{id} |
| Pedido | /pedidos | /pedidos | /pedidos/{id} | /pedidos/{id} |
