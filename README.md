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

git clone https://github.com/Dojassola/teste.git

Acesse a pasta do projeto: cd teste
Instale as dependências: npm install
Rode o projeto localmente: npm run dev

Para testar: 

npx cypress open
Escolha E2E Testing.

Selecione um navegador.

Execute a spec chamada:

spec.cy.js
Ou rode os testes diretamente no terminal (modo headless):

npx cypress run --spec "cypress/e2e/spec.cy.js"
