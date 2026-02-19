# 🚀 Cypress Enterprise Automation Framework

Framework de automação de testes desenvolvido em **Cypress** com foco em padrões de projeto utilizados em empresas reais.

Inclui testes **UI**, testes **API**, uso de **Intercept/Mock**, geração de **Relatórios Mochawesome** e integração completa com **CI/CD via GitHub Actions**.

---

## 🧪 Tecnologias utilizadas

- Cypress
- JavaScript
- Node.js
- Mochawesome Reports
- GitHub Actions CI/CD

---

## 📂 Estrutura do projeto

```bash
cypress-framework-enterprise/
│ package.json
│ cypress.config.js
│ README.md
│ .gitignore
│ .github/
│   └── workflows/
│       └── cypress.yml
└── cypress/
    ├── e2e/
    │   ├── smoke/
    │   │   └── login.cy.js
    │   │   └── Logout.cy.js
    │   ├── regression/
    │   │   └── checkout.cy.js
    │   ├── api/
    │   │   └── api-tests.cy.js
    │   └── intercept/
    │       └── intercept.cy.js
    ├── fixtures/
    │   ├── user.json
    │   └── checkout.json
    ├── pages/
    │   ├── LoginPage.js
    │   ├── InventoryPage.js
    │   ├── CartPage.js
    │   └── CheckoutPage.js
    ├── support/
    │   ├── commands.js
    │   └── e2e.js
    └── utils/
        └── routes.js
```
⚙️ Pré-requisitos

Node.js (18+ recomendado)

Git

VS Code

📥 Instalação

Clone o projeto:

```bash
git clone https://github.com/SEU_USUARIO/NOME_DO_REPO.git
```

Entre na pasta:

```bash
cd NOME_DO_REPO
```

Instale as dependências:

```bash
npm install
```

▶️ Executando os testes
Rodar Cypress interativo

```bash
npm run cy:open
```

Rodar todos os testes no terminal

```bash
npm run cy:run
```

Rodar apenas Smoke Tests

```bash
npm run cy:smoke
```

Rodar apenas Regression Tests

```bash
npm run cy:regression
```

Rodar apenas API Tests

```bash
npm run cy:api
```

📊 Relatórios Mochawesome

Após rodar os testes, o relatório será gerado em:

cypress/reports


Abra o arquivo .html gerado no navegador.

🤖 CI/CD - GitHub Actions

O projeto possui pipeline automatizado que executa os testes a cada:

✅ push na branch main
✅ pull request

Além disso, o relatório Mochawesome é salvo como Artifact.

🏆 Boas práticas aplicadas

✔ Page Object Model (POM)
✔ Custom Commands
✔ Fixtures para massa de testes
✔ Testes organizados por tipo (smoke, regression, api)
✔ Intercept e validação de requisições
✔ Relatórios automatizados
✔ CI/CD com GitHub Actions

👨‍💻 Autor

Thales Barbosa
📌 QA / Automação de Testes
🔗 GitHub: https://github.com/FalcoNzada


