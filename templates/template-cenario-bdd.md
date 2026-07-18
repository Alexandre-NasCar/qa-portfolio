# BDD-XXX — Nome da funcionalidade

## Identificação

| Campo | Informação |
|---|---|
| ID | BDD-XXX |
| Projeto | Nome do projeto |
| Funcionalidade | Nome da funcionalidade |
| Prioridade | Alta / Média / Baixa |
| Regra de negócio | Referência da regra |

---

## História do usuário

**Como** tipo de usuário  
**Quero** realizar uma ação  
**Para** obter determinado benefício

---

## Critérios de aceitação

- critério 1;
- critério 2;
- critério 3.

---

## Cenário

```gherkin
Funcionalidade: Nome da funcionalidade

  Contexto:
    Dado que existe uma condição comum aos cenários

  Cenário: Nome do cenário
    Dado que o usuário está em determinada condição
    Quando executa determinada ação
    Então o sistema deve apresentar o resultado esperado

---

## Cenário negativo

```gherkin
  Cenário: Tentativa com dados inválidos
    Dado que o usuário está na página da funcionalidade
    Quando informa dados inválidos
    Então o sistema deve impedir a operação
    E apresentar uma mensagem adequada
