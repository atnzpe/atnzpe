# Olá, eu sou o Gleyson Atanazio 👋🏿

**Desenvolvedor Full Stack** em Igarassu–PE. Construo sistemas de gestão (SaaS) para artes marciais, educação e pequenos negócios, do banco de dados com regras de segurança até a tela que o aluno usa no celular.

> Fazer as coisas acontecerem da forma mais simples e objetiva.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gleysonatanazio/)
[![E-mail](https://img.shields.io/badge/E--mail-000?style=for-the-badge&logo=gmail&logoColor=E94D5F)](mailto:gleysonasilva@gmail.com)

---

## 🚧 No que estou trabalhando

### Produtos próprios

| Projeto | O que é | Stack | Status |
|---|---|---|---|
| 🥋 **Dojo Manager** | SaaS para academias, federações e confederações de artes marciais: alunos, chamada por PIN, financeiro, cursos, campeonatos e placar. Cada instituição só enxerga os próprios dados. | React 19 · TypeScript · Supabase (PostgreSQL + RLS) · Vercel | Em desenvolvimento · pilotos em preparação |
| 💇🏿 **SoFi OS** | Agendamento de serviços e vendas online, com painel de pedidos (KDS), estoque e ficha técnica. | React · TypeScript · Supabase | Em desenvolvimento |

<details>
<summary><b>🥋 Dojo Manager: o que o sistema já faz</b></summary>

- **Hierarquia real:** Confederação → Federação → Academia → Aluno, com isolamento de dados feito no próprio banco (PostgreSQL Row Level Security)
- **Alunos:** cadastro com aprovação, ficha completa, troca de senha obrigatória no primeiro acesso e cargos (aluno, instrutor, gestor, admin)
- **Tatame virtual:** chamada por PIN em tempo real, turmas do dia e locais de treino com rota e WhatsApp
- **Financeiro:** painel de inadimplência e régua de cobrança com atalho para WhatsApp
- **Cursos e eventos:** vitrine pública, inscrição com controle de vagas e lista de inscritos em CSV
- **Campeonatos:** criação de eventos e categorias, inscrição com trava de adimplência, motor de regras de placar (Sambo, Jiu-Jitsu, Karatê, Pencak Silat) e visibilidade pública, interna ou por convite
- **Também:** exames de faixa, ranking, certificados, videoteca, programa técnico e telão
- **Qualidade:** React Hook Form + Zod, testes com Vitest e CI no GitHub Actions

</details>

<details>
<summary><b>💇🏿 SoFi OS: o que o sistema já faz</b></summary>

- **Multi-estabelecimento:** cada negócio com seus próprios dados, configuração white-label (marca, horários, PIX, redes sociais)
- **Serviços e equipe:** cadastro de serviços com ficha técnica (custo de insumos) e profissionais com habilidades e dias de trabalho
- **Estoque:** insumos com código de barras
- **Loja do cliente:** vitrine de serviços e produtos
- **Painel KDS:** acompanhamento dos pedidos e atendimentos em quadro (kanban)
- **Em andamento:** migração de Firebase para Supabase, motor de agendamento sem choque de horários e checkout com PIX

</details>

### Projetos com instituições

| Instituição | O que faço | Stack | Site |
|---|---|---|---|
| **CBSA** · Confederação Brasileira de Sambo | Refatoração do portal (SEO, acessibilidade, mobile first) e painel administrativo de notícias e cursos | PHP 8 · MySQL · GitHub Actions | [sambocbsa.com.br](https://www.sambocbsa.com.br/) |
| **IBTO** · Instituto Brasileiro de Treinamento Operacional | Site institucional e plataforma de cursos online (cursos, matrículas, certificados com validação pública e área do filiado), em desenvolvimento | React · TypeScript · Laravel 13 · MySQL | [ib-to.org](https://ib-to.org) |
| **Takimura Fight** | Landing page integrada ao Dojo Manager | React · TypeScript · Vite | [takimurafight.vercel.app](https://takimurafight.vercel.app/) |
| **COBRAM** | Apoio técnico e QA do site | — | [cobram.org](https://cobram.org/) |

### Código aberto

| Repositório | Descrição | Stack |
|---|---|---|
| [placar-eletronico](https://github.com/atnzpe/placar-eletronico) | Placar eletrônico adaptativo para Sambo e outras artes marciais | Python |
| [krav_maga_analyzer](https://github.com/atnzpe/krav_maga_analyzer) | Compara o vídeo do aluno com o do mestre e dá uma pontuação ao movimento | Python |
| [quiz_sfpc](https://github.com/atnzpe/quiz_sfpc) | Simulado para a certificação Scrum Foundation (SFPC) | Python · Flet |
| [app-receitas](https://github.com/atnzpe/app-receitas) | App de receitas offline-first em arquitetura MVVM | Python · Flet · SQLite |
| [app_oficina_mecanica](https://github.com/atnzpe/app_oficina_mecanica) | Ordens de serviço, clientes, veículos e peças para oficinas | Python · Flet |
| [DojoManager-Comercial](https://github.com/atnzpe/DojoManager-Comercial) | Primeira versão do Dojo Manager, sem custo de servidor | Google Apps Script |

---

## 🛠️ Stack

**Front-end**
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Bun](https://img.shields.io/badge/Bun-000?style=flat-square&logo=bun&logoColor=white)

**Back-end e dados**
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)

**Apps e automação**
![Flet](https://img.shields.io/badge/Flet-0175C2?style=flat-square&logo=flutter&logoColor=white)
![Google Apps Script](https://img.shields.io/badge/Apps_Script-4285F4?style=flat-square&logo=google&logoColor=white)

**Entrega**
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000?style=flat-square&logo=vercel&logoColor=white)

**Como trabalho:** segurança no banco (Row Level Security, sistemas multi-instituição), acessibilidade (WCAG), SEO e testes automatizados (Vitest, Pest, pytest).

---

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/atnzpe/atnzpe/output/github-contribution-grid-snake-dark.svg">
  <img alt="Cobrinha comendo o gráfico de contribuições" src="https://raw.githubusercontent.com/atnzpe/atnzpe/output/github-contribution-grid-snake.svg">
</picture>
