## FinApi - Financeia

---

### Requisitos

<li>[x] Deve ser possível criar umma conta</li>
<li>[x] Deve ser possível buscar o extrato bancário do cliente</li>
<li>[x] Deve ser possível realizar um depósito</li>
<li>[x] Deve ser possível realizar um saque</li>
<li>[x] Deve ser possível buscar o extrato bancário do cliente por data</li>
<li>[x] Deve ser possível atualizar dados da conta do cliente</li>
<li>[x] Deve ser possível obter dados da conta do cliente</li>
<li>[x] Deve ser possível deletar uma conta</li>
<li>[x] Deve ser possível retornar o balance</li>

---

### Regras de negócio

<li>[x] Não deve ser possível cadastrar uma conta com CPF já existente</li>
<li>[x] Não deve ser possível fazer depósito em uma conta não existente</li>
<li>[x] Não deve ser possível buscar extrato em uma conta não existente</li>
<li>[x] Não deve ser possível fazer saque em uma conta não existente</li>
<li>[x] Não deve ser possível fazer saque quando o saldo for insuficiente</li>
<li>[x] Não deve ser possível excluir uma conta não existente</li>
<li>[x] Não deve ser possível retornar balance de conta não existente</li>