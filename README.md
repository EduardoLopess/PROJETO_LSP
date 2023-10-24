# Mão Solidária

Projeto elaborado como parte da disciplina de Laboratório de Simulação e Prototipagem.

CRUD de Usuario e Instituto

## ContollerUser 

### POST api/user

- Exemplo do corpo da requisição para cadastro de usuário 
  Obs: Obrigatório o envio de endereço no corpo do JSON

```
{
  "name": "string",
  "surname": "string",
  "phoneNumber": "string",
  "cpf": "string",
  "email": "string",
  "passwordHash": "string",
  "profileAcess": 0,
  "adressViewModels": [
    {
      "street": "string",
      "houseNumber": 0,
      "neighborhood": "string",
      "complement": "string",
      "zipCode": 0,
      "city": "string"
    }
  ]
}
```
GET /api/User

Retorna todos os usuários cadastrados.

GET /api/User/{id}

Retorna um usuário específico com base no ID.

PUT /api/User/{id}

Atualiza as informações de um usuário existente.

Obs: Endereço deve ser informado junto!

```

{
  "name": "string",
  "surname": "string",
  "phoneNumber": "string",
  "cpf": "string",
  "email": "string",
  "passwordHash": "string",
  "profileAcess": 0,
  "adressViewModels": [
    {
      "street": "string",
      "houseNumber": 0,
      "neighborhood": "string",
      "complement": "string",
      "zipCode": 0,
      "city": "string"
    }
  ]
}
```
