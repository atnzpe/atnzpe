# Olá, eu sou o Gleyson Atanazio 👋🏿

**Desenvolvedor Full Stack Júnior** em Igarassu–PE, no 5º período de Engenharia da Computação. Construo sistemas de gestão (SaaS) para artes marciais, educação e pequenos negócios, do banco de dados com regras de segurança até a tela que o aluno usa no celular.

> Fazer as coisas acontecerem da forma mais simples e objetiva.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gleysonatanazio/)
[![Portfólio](https://img.shields.io/badge/Portfólio-C2410C?style=for-the-badge&logo=googlechrome&logoColor=white)](https://atnzpe.github.io/)
[![E-mail](https://img.shields.io/badge/E--mail-000?style=for-the-badge&logo=gmail&logoColor=E94D5F)](mailto:gleysonasilva@gmail.com)

---

## 🚧 No que estou trabalhando

### Produtos próprios

| Projeto | O que é | Stack | Status |
|---|---|---|---|
| 🥋 **Dojo Manager** | SaaS para academias, federações e confederações de artes marciais: alunos, chamada por PIN, financeiro, cursos, campeonatos, placar e telão. Cada instituição só enxerga os próprios dados. | React 19 · TypeScript · Supabase (PostgreSQL + RLS) · Vercel | Em desenvolvimento · em teste com pessoas antes do primeiro piloto |
| 💇🏿 **SoFi OS** | Plataforma para vários pequenos negócios, cada um isolado no banco: agendamento de serviços, estoque com catálogo público e, em seguida, pedidos de delivery. | React · TypeScript · Supabase | Em desenvolvimento · loja de celulares em teste |

<details>
<summary><b>🥋 Dojo Manager: o que o sistema já faz</b></summary>

- **Hierarquia real:** Confederação → Federação → Academia → Aluno, com isolamento de dados feito no próprio banco (PostgreSQL Row Level Security)
- **Alunos:** cadastro com aprovação, ficha completa, troca de senha obrigatória no primeiro acesso e cargos (aluno, instrutor, gestor, admin)
- **Tatame virtual:** chamada por PIN em tempo real, turmas do dia e locais de treino com rota e WhatsApp
- **Financeiro:** painel de inadimplência e régua de cobrança com atalho para WhatsApp
- **Cursos e eventos:** vitrine pública, inscrição com controle de vagas e lista de inscritos em CSV
- **Campeonatos:** criação de eventos e categorias, inscrição com trava de adimplência, motor de regras de placar (Sambo, Jiu-Jitsu, Karatê, Pencak Silat) e visibilidade pública, interna ou por convite
- **Tatame Digital:** placar ao vivo com telão público, apito, julgamento por vários árbitros e súmula gravada no banco
- **Também:** exames de faixa, ranking, certificados, videoteca e programa técnico
- **Qualidade:** React Hook Form + Zod, testes com Vitest, checagem de tipos e CI no GitHub Actions

</details>

<details>
<summary><b>💇🏿 SoFi OS: o que o sistema já faz</b></summary>

- **Multi-estabelecimento:** cada negócio com seus próprios dados, configuração white-label (marca, horários, PIX, redes sociais)
- **Serviços e equipe:** cadastro de serviços com ficha técnica (custo de insumos) e profissionais com habilidades e dias de trabalho
- **Estoque:** insumos com código de barras
- **Loja do cliente:** vitrine de serviços e produtos
- **Painel KDS:** acompanhamento dos pedidos e atendimentos em quadro (kanban)
- **Em andamento:** ambiente de teste de uma loja de celulares; depois, pedidos de delivery com tela da equipe e aviso ao cliente pelo WhatsApp

</details>

### Projetos com instituições

| Instituição | O que faço | Stack | Site |
|---|---|---|---|
| **CBSA** · Confederação Brasileira de Sambo | Portal em produção (SEO, acessibilidade, mobile first, vários idiomas) e novo painel administrativo em Laravel, em construção | PHP 8 · Laravel 13 · MySQL · GitHub Actions | [sambocbsa.com.br](https://www.sambocbsa.com.br/) |
| **IBTO** · Instituto Brasileiro de Treinamento Operacional | Site institucional no ar e plataforma de cursos em homologação para o piloto (matrículas, provas, certificados com validação pública e área do filiado) | React · TypeScript · Laravel 13 · MySQL | [ib-to.org](https://ib-to.org) |
| **Plataforma de cursos de drones** · instrutor de drones táticos | Plataforma em Laravel + React a partir da maquete do cliente: papéis no servidor, páginas públicas e painel de cursos, em demonstração | Laravel 13 · React · TypeScript · MySQL | — |
| **Takimura Fight** | Landing page integrada ao Dojo Manager | React · TypeScript · Vite | [takimurafight.vercel.app](https://takimurafight.vercel.app/) |
| **COBRAM** · Confederação Brasileira de Artes Marciais | Desenvolvedor Web: apoio técnico, presença digital e QA do site | — | [cobram.org](https://cobram.org/) |

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

<!-- Mapa de todos os repositórios (situação de 15/11/2026). Regra: repositório privado aparece
     sem link e sem o nome do cliente (LGPD e combinado com cada cliente). -->
## 🗺️ Mapa de todos os repositórios

Para que cada projeto serve, onde estamos e para onde vamos. Os privados aparecem **sem o nome do cliente**, de acordo com a LGPD e com o combinado com cada cliente. *Situação de 15/11/2026.*

<details>
<summary><b>Produtos próprios</b> · plataformas que eu crio e mantenho</summary>

| Projeto | Serve para | Onde estamos | Próximo passo |
|---|---|---|---|
| 🥋 Dojo Manager 🔒 | Gestão de academias, federações e confederações de artes marciais | 35 entregas construídas, juntas numa versão de integração para o teste com pessoas | Homologação, contas de teste, abertura do código e primeiro piloto com uma equipe de lutas |
| 💇🏿 SoFi OS 🔒 | Uma plataforma para vários pequenos negócios, cada um com os seus dados isolados | Ambiente de teste de uma loja no ar, esperando o teste com o cliente | Primeiro piloto e, depois, abrir o código |
| 🛴 Módulo de oficina 🔒 | Diagnóstico guiado para oficinas de bicicleta, patinete e scooter elétrica | 205 fichas transcritas e protótipo da consulta, sem internet; piloto combinado com uma rede de lojas de bicicleta | Revisão das fichas pelo autor e módulo dentro do SoFi OS |
| 📦 Contador de estoque 🔒 | App de celular para contar estoque pelo código de barras e exportar no formato do sistema da loja | Só o plano escrito | Construir depois do piloto da loja |

</details>

<details>
<summary><b>Clientes e instituições</b> · trabalho para organizações reais</summary>

| Projeto | Serve para | Onde estamos | Próximo passo |
|---|---|---|---|
| [IBTO · site](https://github.com/atnzpe/Instituto-Brasileiro-de-Treinamento-Operacional) | Site do instituto, com blog, eventos e Rede Nacional de instrutores | No ar, 53 tarefas concluídas | Seguir depois da reunião com a diretoria |
| [IBTO · plataforma de cursos](https://github.com/atnzpe/ibto-plataforma) | Matrícula, provas, certificados com validação pública e área do filiado | Em homologação para o piloto | Piloto e publicação |
| CBSA · portal e painel 🔒 | Portal da Confederação Brasileira de Sambo e novo painel em Laravel | Portal em produção; painel em construção | Continuar após a liberação do jurídico |
| Plataforma de cursos de drones 🔒 | Cursos de um instrutor de drones táticos, a partir da maquete do cliente | Pronta para demonstração | Definir a hospedagem e publicar |
| Landing page de uma equipe de lutas 🔒 | Página de apresentação ligada ao Dojo Manager | No ar | Receber os dados do Dojo Manager no piloto |
| Clientes do SoFi OS (4 repositórios sem código) 🔒 | Guardam só o combinado com cada cliente: uma loja de celulares, um restaurante, um comércio com entregas e uma rede de lojas de bicicleta | Loja com teste no ar; os outros em levantamento | Teste com a loja; depois, o restaurante e a primeira loja de bicicleta |

</details>

<details>
<summary><b>Versões anteriores e protótipos</b> · onde aprendi o que hoje está nos produtos</summary>

| Projeto | Serve para | Onde estamos | Próximo passo |
|---|---|---|---|
| [DojoManager-Comercial](https://github.com/atnzpe/DojoManager-Comercial) | 1ª versão do Dojo Manager, em Google Apps Script | Encerrada | Histórico |
| Dojo Manager em Firebase e versão para uma confederação 🔒 | 2ª e 3ª tentativas do Dojo Manager | Encerradas | Histórico |
| [placar-eletronico](https://github.com/atnzpe/placar-eletronico) | Placar para Sambo e outras artes marciais, em Python (+ versão privada com os sons do árbitro) | Pronto; virou o placar ao vivo do Dojo Manager | Manter como código aberto |
| [smart-manager-pro](https://github.com/atnzpe/smart-manager-pro) e [gestor-delivery](https://github.com/atnzpe/gestor-delivery) | Salões e delivery com painel de cozinha, em Apps Script | Encerrados; a lógica de pedidos foi para o SoFi OS | Referência |
| [app_oficina_mecanica](https://github.com/atnzpe/app_oficina_mecanica) (+ versões privadas antigas) | Clientes, veículos, peças e ordem de serviço, em Python + Flet | Parado | As ideias vão para o módulo de oficina |
| App para uma federação de artes marciais 🔒 | Materiais de treino e análise de movimento, em Python + Flet | Parado na versão 0.7 | As funções entram no Dojo Manager |
| [krav_maga_analyzer](https://github.com/atnzpe/krav_maga_analyzer) | Compara o vídeo do aluno com o do mestre | Protótipo | Avaliar no Dojo Manager |

</details>

<details>
<summary><b>Apps Android</b> · Python + Flet virando APK para celular e TV</summary>

| Projeto | Serve para | Onde estamos | Próximo passo |
|---|---|---|---|
| [quiz_sfpc](https://github.com/atnzpe/quiz_sfpc) | Simulado para a certificação Scrum Foundation (SFPC) | Funciona no computador | APK pelo GitHub Actions e teste no celular e na TV |
| [app-receitas](https://github.com/atnzpe/app-receitas) | Guia de receitas sem internet, com login, categorias e favoritos | Funciona no computador (MVVM) | APK e teste no celular |
| [dose-certa](https://github.com/atnzpe/dose-certa) | Estoque de bebidas para bares e adegas: doses pelo peso da garrafa, venda e relatório do dia | Funciona no computador; regra da balança documentada com casos de teste | Tela da balança e APK; a mesma regra vira um módulo do SoFi OS |

</details>

<details>
<summary><b>Estudos e cursos</b> · o caminho de aprendizado</summary>

[regressao-linear](https://github.com/atnzpe/regressao-linear) · [page-teste](https://github.com/atnzpe/page-teste) (validação de estoques) · [ia-com-python](https://github.com/atnzpe/ia-com-python) · [processar-imagem-py](https://github.com/atnzpe/processar-imagem-py) · [ocb](https://github.com/atnzpe/ocb) · [ape](https://github.com/atnzpe/ape) · [bank_system_python](https://github.com/atnzpe/bank_system_python) · [lista_de_compras](https://github.com/atnzpe/lista_de_compras) · [geracpfpython](https://github.com/atnzpe/geracpfpython) · [ebook-da-cozinha-para-o-codigo](https://github.com/atnzpe/ebook-da-cozinha-para-o-codigo) · [friendly-memory](https://github.com/atnzpe/friendly-memory) · [PythonExercicios](https://github.com/atnzpe/PythonExercicios) · [studious-adventure](https://github.com/atnzpe/studious-adventure) · [ursos_e_cobras](https://github.com/atnzpe/ursos_e_cobras) · [supreme-adventure](https://github.com/atnzpe/supreme-adventure) · [blog-dev-frontend](https://github.com/atnzpe/blog-dev-frontend) · [blog-dev-backend](https://github.com/atnzpe/blog-dev-backend) · [Bootcamp BairesDev ML](https://github.com/atnzpe/Bootcamp-BairesDev---Machine-Learning-Training) · [supreme-octo-train](https://github.com/atnzpe/supreme-octo-train)

Mais 13 repositórios privados com exercícios de cursos (técnico, lógica de programação, Java, Git) e protótipos pessoais com IA e automação.

</details>

🔒 = repositório privado (sem link).

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
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)

**Apps e automação**
![Flet](https://img.shields.io/badge/Flet-0175C2?style=flat-square&logo=flutter&logoColor=white)
![Google Apps Script](https://img.shields.io/badge/Apps_Script-4285F4?style=flat-square&logo=google&logoColor=white)

**Estudando agora**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Pest](https://img.shields.io/badge/Pest-F472B6?style=flat-square&logo=php&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)

**Desenvolvimento com IA**
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=claude&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)

**Entrega**
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000?style=flat-square&logo=vercel&logoColor=white)

**Como trabalho:** Scrum (backlog nas issues, um painel por projeto com os testes de cada pessoa, Definição de Pronto e página de andamento para cada cliente, com uma PO e QA testando antes do cliente); pair programming com IA (Claude Code e Gemini), em que eu crio a ideia, entendo a necessidade do usuário, defino os requisitos, reviso e testo o resultado; segurança no banco (Row Level Security, sistemas multi-instituição), acessibilidade (WCAG), SEO e testes automatizados (Vitest, Pest, pytest).

---

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/atnzpe/atnzpe/output/github-contribution-grid-snake-dark.svg">
  <img alt="Cobrinha comendo o gráfico de contribuições" src="https://raw.githubusercontent.com/atnzpe/atnzpe/output/github-contribution-grid-snake.svg">
</picture>
