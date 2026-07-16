# PicPay — Desafio Vaga Júnior

Solução para o desafio técnico de vaga júnior do PicPay, implementando uma API REST de transferências financeiras entre usuários.

## Tecnologias

- Java 21
- Spring Boot
- Spring Data JPA
- H2 Database (banco em memória)
- Lombok
- Maven

## Funcionalidades

- Cadastro de usuários (comuns e lojistas)
- Transferência de valores entre usuários
- Validação de saldo antes da transferência
- Integração com serviço externo de autorização
- Notificação de transferências

## Como executar

```bash
./mvnw spring-boot:run
```

A API estará disponível em `http://localhost:8080`.
