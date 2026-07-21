# CT-001 — Cadastro de usuário com dados válidos

## Identificação

| Campo | Informação |
|---|---|
| Projeto | PackAndGo |
| Funcionalidade | Cadastro |
| Tipo | Funcional positivo |
| Prioridade | Alta |
| Status | Não executado |

---

## Objetivo

Validar que um novo usuário consegue concluir o cadastro utilizando dados válidos e ainda não registrados na aplicação.

---

## Pré-condições

- aplicação disponível;
- usuário não autenticado;
- e-mail e CPF ainda não cadastrados;
- armazenamento local disponível no navegador.

---

## Dados de teste

| Campo | Valor |
|---|---|
| Nome | Usuário Teste QA |
| E-mail | usuario.teste.qa@example.com |
| CPF | Dado fictício válido |
| Senha | Dado fictício válido |

> Dados fictícios. Senhas, tokens ou informações pessoais não são reais.

---

## Passos do teste

| Passo | Ação | Resultado esperado |
|---:|---|---|
| 1 | Acessar a opção de cadastro | O formulário de cadastro deve ser exibido |
| 2 | Preencher os campos com dados válidos | Os dados devem ser aceitos sem mensagens de erro |
| 3 | Confirmar o cadastro | O sistema deve concluir o cadastro e apresentar a resposta prevista |
| 4 | Verificar o armazenamento local | O novo usuário deve constar na chave `users` |

---

## Resultado da execução

A preencher após a execução.

---

## Resultado final

- [ ] Aprovado
- [ ] Reprovado
- [ ] Bloqueado
- [x] Não executado

---

## Observações

Este caso cobre apenas o cadastro positivo com dados válidos.

---
## Evidências

As evidências serão armazenadas em:

```text
testes-manuais/evidencias/packandgo/cadastro/CT-001/
