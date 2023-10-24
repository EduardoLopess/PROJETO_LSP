# Mão Solidária

Projeto elaborado como parte da disciplina de Laboratório de Simulação e Prototipagem.

CRUD de Usuario e Instituto

## Contoller api/user

- Exemplo do corpo da requisição para cadastro de usuário 
    Obs: Obrigatorio o envio Endreco no corpo do json

```json
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
