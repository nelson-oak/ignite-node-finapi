# FinAPI - Financeiro

Projeto desenvolvido no bootcamp Ignite da Rocketseat (trilha Node.js).

## Entidades

| Entidades | Atributos |
| - | - |
| account | id, name, cpf, statemant |



## Requisitos

- [ ] Deve ser possível criar uma conta
- [ ] Deve ser possível buscar o extrato bancário do cliente
- [ ] Deve ser possível realizar um depósito
- [ ] Deve ser possível realizar um saque
- [ ] Deve ser possível buscar o extrato bancário do cliente por data
- [ ] Deve ser possível atualizar dados da conta do cliente
- [ ] Deve ser possível obter dados da conta do cliente
- [ ] Deve ser possível deletar uma conta

## Regras de negócio

- [ ] Não deve ser possível cadastrar uma conta com CPF já existente
- [ ] Não deve ser possível fazer depósito em uma conta não existente
- [ ] Não deve ser possível buscar extrato em uma conta não existente
- [ ] Não deve ser possível fazer saque em uma conta não existente
- [ ] Não deve ser possível excluir uma conta não existente
- [ ] Não deve ser possível fazer saque quando o saldo for insuficiente


## Recursos

- Express

## Iniciando o projeto

Após clonar o projeto, é necessário atualizar as dependências.

### Comandos para baixar dependências e iniciar a aplicação

```bash
yarn
yarn dev
```