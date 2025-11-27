# 🐢🛒 Toca do Tatu – Sistema de E-commerce  
**Projeto desenvolvido para a disciplina Engenharia de Software Aplicada (3º semestre – Gestão de TI / FATEC).**

---

## 📌 Objetivo do Projeto
Modelar, documentar e estruturar um sistema de **e-commerce completo**, incluindo requisitos, casos de uso, interface, arquitetura e estratégias de desenvolvimento.

---

## 🧱 Estrutura do Repositório

/toca-do-tatu-ecommerce
├─ README.md
├─ docs/
│ ├─ requisitos.md
│ ├─ casos_de_uso.md
│ ├─ narrativas/
│ └─ mockups/
├─ backend/
│ ├─ src/
│ ├─ Dockerfile
│ └─ README.md
├─ frontend/
│ ├─ src/
│ ├─ public/
│ └─ README.md
├─ infra/
│ ├─ docker-compose.yml
│ └─ k8s/
├─ tests/
│ └─ planos_de_teste.md
├─ metrics/
│ └─ pontos_de_funcao.xlsx
└─ .github/
└─ workflows/


Cada parte do sistema está modularizada para facilitar organização, manutenção e evolução do projeto.

---

## 🚀 Estratégia de Branches

| Branch       | Função |
|-------------|--------|
| **main**    | Versão estável / releases |
| **develop** | Integração contínua / desenvolvimento |
| **feature/*** | Novas funcionalidades (criar uma por tarefa) |

---

## 🧩 Fluxo de Trabalho (Git Flow Simplificado)

1. Criar branch a partir de `develop`  

git checkout develop
git checkout -b feature/nome-da-feature

2. Desenvolvimento da tarefa  
3. Commit + push para a feature  
4. Abrir Pull Request → `feature/*` → `develop`  
5. Revisão e merge  
6. Releases são feitas via merge de `develop` → `main`

---

## 📚 Documentação Detalhada

📄 **Requisitos:**  
`/docs/requisitos.md`

🔍 **Casos de Uso:**  
`/docs/casos_de_uso.md`

📘 **Narrativas:**  
`/docs/narrativas/`

🎨 **Mockups e protótipos:**  
`/docs/mockups/`  
*(links para Figma e imagens)*

---

## 🧪 Testes

Plano de testes disponível em:  
`/tests/planos_de_teste.md`

---

## 📊 Métricas

Estimativa de Pontos de Função:  
`/metrics/pontos_de_funcao.xlsx`

---

## 🤖 CI/CD (GitHub Actions)

Workflows automatizados em:  
`/.github/workflows/`

Automatizações previstas:
- Build
- Lint
- Testes
- Integração contínua

---

## 👥 Colaboradores do Projeto

- **Equipe da disciplina**
- **Professor orientador:** Anderson Luiz Barbosa (acesso: leitura/triagem)

---

## 🐢 Identidade do Projeto
O nome “Toca do Tatu” remete ao mascote da equipe — simples, simpático e resistente.  
O e-commerce será baseado em produtos de nicho, com foco em navegação intuitiva e boa experiência do usuário.

---

## 📎 Licença
Projeto acadêmico — uso livre para fins educacionais.

---
