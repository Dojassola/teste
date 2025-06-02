
# 📝 Projeto Frontend com Testes Cypress

Este é um projeto frontend desenvolvido em **React + Vite**, que possui testes implementados utilizando **Cypress**.

O projeto conta com funcionalidades como autenticação (login) e gerenciamento de tarefas.

---

## ⚙️ Tecnologias Utilizadas

- React
- Vite
- Cypress

---

## 🔧 Como rodar a aplicação

1. Clone este repositório:

```bash
git clone https://github.com/Dojassola/teste.git
```

2. Acesse a pasta do projeto:

```bash
cd teste
```

3. Instale as dependências:

```bash
npm install
```

4. Rode o projeto localmente:

```bash
npm run dev
```

5. Para rodar os testes:

- Execute o Cypress na interface gráfica:

```bash
npx cypress open
```

- Escolha **E2E Testing**.
- Selecione um navegador.
- Execute a spec chamada:

```
spec.cy.js
```

- Ou rode os testes diretamente no terminal (modo headless):

```bash
npx cypress run --spec "cypress/e2e/spec.cy.js"
```

---

## 📝 Descrição dos Testes

Os testes foram realizados utilizando a ferramenta **Cypress**, visando garantir a funcionalidade da **página de Login** e da **página de Tarefas** do sistema. Foram aplicados testes de:

- Validação de interface;
- Fluxo de autenticação (login);
- Operações básicas no gerenciamento de tarefas;
- Validação de formulários.

---

## 🧪 Suítes de Teste

| Suite                | Quantidade de Testes | Descrição Resumida                                                   |
|----------------------|-----------------------|----------------------------------------------------------------------|
| **Login**            | 4                     | Testes relacionados ao fluxo de login e redirecionamento             |
| **Página de Tarefas**| 3                     | Testes relacionados ao gerenciamento de tarefas e validações         |

---

## 🔍 Testes Individuais

| Nº | Cenário                                                                                     | Resultado   | Observações                                      |
|----|---------------------------------------------------------------------------------------------|-------------|--------------------------------------------------|
| 1  | Verificar exibição dos elementos do formulário de Login                                     | ✅ Passou   | Todos os elementos visíveis                      |
| 2  | Login com usuário e senha inválidos, deve exibir mensagem de erro                           | ✅ Passou   | Mensagem de erro exibida corretamente            |
| 3  | Login com usuário e senha válidos                                                            | ✅ Passou   | Login realizado com sucesso                      |
| 4  | Redirecionamento para a página inicial após login válido                                    | ✅ Passou   | Redirecionamento correto                         |
| 5  | Verificar exibição dos elementos na página de tarefas                                       | ✅ Passou   | Todos os elementos visíveis                      |
| 6  | Criar uma nova tarefa com sucesso                                                            | ✅ Passou   | Tarefa criada e exibida na lista                 |
| 7  | Validação dos campos do formulário de tarefas (campos obrigatórios não preenchidos)         | ✅ Passou   | Validação funcionando corretamente               |

---

## 📜 Observações

Todos os testes foram executados localmente com sucesso, e todas as funcionalidades testadas estão funcionando corretamente conforme esperado.

---
