<p align="center">
<img src="https://nestjs.com/img/logo_text.svg" width="320" alt="Nest Logo" />
</p>
<h1>Desafio FullCycle NestJS </h1>

## Descrição
Desafio FullCycle Nestjs, 2 endpoints de transactions:
 - GET /transations (Listas as transações)
 - POST /transations (Criar uma transação)

<br>

## Rodando o app

```bash
# development
$ docker-compose up

```

## Exemplo de requisição aos endpoints

````
GET http://localhost:3000/transactions
````

````
POST http://localhost:3000/transactions
Content-Type: application/json

{
  "account_ids": 21,
  "amount": 2555.00
}
````


