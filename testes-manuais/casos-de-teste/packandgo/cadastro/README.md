# Cadastro — PackAndGo

## Objetivo

Organizar os casos de teste relacionados ao cadastro de usuários da aplicação PackAndGo.

A documentação desta funcionalidade será construída progressivamente, conectando:

> Requisito → Risco → Cenário → Caso de teste → Execução → Evidência → Resultado → Aprendizado

---

## Escopo inicial

Os testes de cadastro devem validar:

- cadastro com dados válidos;
- preenchimento de campos obrigatórios;
- formato dos dados informados;
- bloqueio de e-mail duplicado;
- bloqueio de CPF duplicado;
- comportamento das senhas;
- persistência do usuário no armazenamento local;
- mensagens apresentadas ao usuário.

---

## Riscos principais

- cadastro não concluído;
- usuário não armazenado;
- duplicidade de e-mail;
- duplicidade de CPF;
- dados armazenados incorretamente;
- mensagem de sucesso sem persistência;
- exposição indevida de informações;
- comportamento inconsistente entre interface e armazenamento local.

---

## Casos de teste

| ID | Caso de teste | Tipo | Prioridade | Status |
|---|---|---|---|---|
| CT-001 | Cadastro de usuário com dados válidos | Funcional positivo | Alta | Não executado |

Novos casos serão adicionados conforme a análise da funcionalidade avançar.

---

## Evidências

As evidências serão armazenadas em:

```text
testes-manuais/evidencias/packandgo/cadastro/