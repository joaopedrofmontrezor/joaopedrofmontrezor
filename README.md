<div align="center">

# Olá, eu sou o João Pedro 👋

**Estudante de Desenvolvimento de Software Multiplataforma · 4º semestre**
Matão - SP · Buscando minha primeira oportunidade como **desenvolvedor full stack / back-end**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/joao-pedro-ferreira-montrezor/)
[![E-mail](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jp.montrezor@gmail.com)

</div>

---

## 👨‍💻 Sobre mim

Tenho 19 anos e estou no **4º semestre** de Desenvolvimento de Software Multiplataforma. Além das aulas, gosto de construir **sistemas completos que resolvem problemas reais**: do banco de dados e da API até a interface e o deploy em produção.

Meus projetos nascem de situações do dia a dia, como a gestão de uma barbearia, o fechamento financeiro de uma arena esportiva e o controle de caixa de um restaurante. Busco **estágio ou vaga júnior** para evoluir junto a um time e entregar software de verdade.

## 🎯 Foco atual

- 🟦 Desenvolvimento **full stack com TypeScript** (NestJS + React)
- 🗄️ Modelagem de dados e migrations com **Prisma** e **PostgreSQL**
- 🔐 Autenticação e autorização (**JWT**, guards por perfil, arquitetura multi-tenant)
- 🚀 **CI/CD** com GitHub Actions e deploy em nuvem (Railway, Vercel, Neon)
- 🐍 **Python** com Flask e testes automatizados com Pytest

## 🛠️ Tecnologias

**Linguagens**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**Back-end**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)

**Front-end**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

**Banco de dados**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)

**DevOps e ferramentas**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white)
![Neon](https://img.shields.io/badge/Neon-00E599?style=for-the-badge&logo=neon&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)


---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=joaopedrofmontrezor&layout=compact&theme=dark" width="48%" />
</p>

## 🐍 Contribuições

<p align="center">
  <img alt="GitHub e a cobrinha comendo os commits" src="https://github.com">
</p>


---

## 📂 Projetos em destaque


### 💈 BarberFlow: SaaS de Gestão para Barbearias
Sistema **multi-tenant** para barbearias e barbeiros autônomos, com agendamento online público para clientes, agenda diária em tempo real, controle de equipe e serviços, e relatórios financeiros com cálculo de comissões.

- **Back-end:** Node.js, NestJS, Prisma ORM 7, PostgreSQL (Neon), JWT + Bcrypt
- **Front-end:** React 18, TypeScript, Vite, React Router, Axios (interceptors para JWT e Tenant ID)
- **Destaques:** isolamento de dados por barbearia (`TenantGuard`), design system próprio com CSS puro, CI com GitHub Actions (type-check, build do Prisma e builds de produção)

### 🏐 Arena Futevôlei: Controle de Aulas e Fechamentos
Sistema web para controlar as aulas dadas por professores (turmas e personais) e gerar o **fechamento financeiro** de cada um, incluindo o que fez como auxiliar em aulas de outros professores. Possui dois perfis de acesso: **Professor** e **Owner** (dono da arena).

- **Back-end:** NestJS 10, TypeScript, Prisma, PostgreSQL, JWT + Passport, guards de role e proteção CSRF
- **Front-end:** React 18, TypeScript, Vite, Tailwind CSS, React Router
- **Destaques:** **em produção** (back-end no Railway, front-end no Vercel, banco no Neon), pipeline de CI com lint, type-check, testes, build e Docker, endpoint de health check para monitoramento

### 🍽️ Livro Caixa: Controle Financeiro para Restaurante
Sistema de gestão financeira **local e offline-first** para restaurantes familiares, que substitui cadernos de anotações por uma aplicação web ágil, sem mensalidade e sem hospedagem.

- **Back-end:** Python 3.10–3.13, Flask, SQLite
- **Front-end:** JavaScript puro + Chart.js
- **Destaques:** dashboard com gráficos de fluxo diário e despesas por categoria, exportação de relatórios em CSV (UTF-8 com BOM, pronto para Excel/Google Sheets), filtros avançados, atalhos rápidos de lançamento, testes com **Pytest** e CI/CD no GitHub Actions
- **Licença:** MIT

## 📚 Em que estou evoluindo

- Lógica de programação e algoritmos
- APIs REST com NestJS e Flask
- Banco de dados relacional (PostgreSQL, SQLite) e ORM
- Autenticação com JWT e controle de acesso por perfil
- CI/CD com GitHub Actions e deploy em nuvem
- Testes automatizados no back-end e front-end (ampliar cobertura)
- Docker e orquestração
- Inglês técnico

## 🤝 Soft skills

Comunicação clara · Autonomia para entregar do zero ao deploy · Aprendizado rápido · Organização · Foco em resolver o problema do usuário

## 📫 Vamos conversar?

Estou aberto a oportunidades de **estágio e vaga júnior** em Desenvolvimento de Software.

- 💼 [LinkedIn](https://www.linkedin.com/in/joao-pedro-ferreira-montrezor/)
- 📧 jp.montrezor@gmail.com
- 📍 Matão - SP (aberto a remoto/presencial e híbrido)

---


⭐ Obrigado pela visita!


