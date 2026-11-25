# Olá, sou o Lucas · Hi, I'm Lucas 👋

[🇧🇷 Português](#pt) · [🇺🇸 English](#en)

<a id="pt"></a>

## 🇧🇷 Sobre mim

Crio **automações com agentes de IA** para tirar trabalho manual e repetitivo do caminho. Idealizo o processo, defino as regras de negócio e a experiência de uso, e construo a solução com IA. Estudo Análise e Desenvolvimento de Sistemas.

### 🚀 Aberto a oportunidades

Busco minha primeira vaga em TI: **IA aplicada e automação**, ou **suporte e infraestrutura**.

### O que eu faço

- Agentes de IA (como o Cursor) para criar e iterar ferramentas e automações
- Automação de rotinas e planilhas (JavaScript, VBA, Python)
- Ferramentas que economizam horas de trabalho manual

### Ferramentas que criei no trabalho

#### 🧰 Toolbox: central de automações para cadastro e precificação

Central de automações para o cadastro e a precificação de exames ocupacionais. Roda dentro do sistema de gestão, aberta por um favorito do navegador, e faz sozinha tarefas que antes eram feitas tela a tela.

- **Mais de 30 módulos:** credenciamento de clínicas (uma a uma ou em lote), renovação e reajuste, Mark-Up, geração de planilhas, cadastro e bases de conhecimento
- **Execução segura:** botão PARAR, pausa e retomada, e conferência da tela antes de agir (se o sistema mudar, nada é feito)
- **Tempo por cadastro de clínica:** de 3–7 min para ~1 min
- **Renovação com 20–30 prestadores:** de 1 h a 2 h 30 (manual) para 20–30 min pela rotina da Toolbox, ou 1–5 min pela opção por planilha, recomendada quando há muitos prestadores
- **Tecnologias:** JavaScript (bookmarklet) e RPA no navegador, ~34 mil linhas feitas com apoio de IA no Cursor

| Menu principal | Planilhas |
|---|---|
| ![Menu da Toolbox com os módulos](docs/toolbox/menu.png) | ![Módulo de planilhas](docs/toolbox/planilhas.png) |
| **Lote de solicitações** | **Andamento com botão de parar** |
| ![Solicitações coladas para processar em lote](docs/toolbox/lote.png) | ![Credenciamento em massa em andamento](docs/toolbox/progresso.png) |
| **Relatório do lote** | **Proteção contra mudanças no sistema** |
| ![Relatório do lote com itens ignorados](docs/toolbox/relatorio.png) | ![Aviso de que a tela esperada não foi encontrada](docs/toolbox/protecao.png) |
| **Configurações** | |
| ![Configurações da Toolbox](docs/toolbox/configuracoes.png) | |

<sub>Prints feitos com dados fictícios.</sub>

#### 📋 Renovação PME: renovação de contratos ocupacionais

Automação do processo anual de renovação de contratos de saúde ocupacional para pequenas e médias empresas, que era manual, espalhado entre planilhas, sistema e e-mail, e sujeito a erro de cálculo e perda de prazo.

- **Rotina em segundo plano:** lê os contratos, baixa vidas e exames, calcula o reajuste pelo índice do contrato e gera proposta e demonstrativo já conferidos
- **Painel web em Kanban:** acompanha cada empresa até a renovação, cria rascunhos de e-mail para revisão humana, classifica respostas, confere assinaturas e agenda follow-ups
- **Tempo por documento:** de 5–10 min (manual, um a um) para ~1 min
- **Tecnologias:** Google Apps Script, Python, Google Sheets, Drive, Gmail e agente de IA
- Controle de acesso por perfil e trilha de auditoria

| Quadro Kanban | Detalhe da empresa |
|---|---|
| ![Quadro Kanban das renovações do mês](docs/renovacao-pme/kanban.png) | ![Detalhe da empresa com prévia da proposta](docs/renovacao-pme/detalhe-empresa.png) |
| **Etapas da renovação** | **Rascunho de e-mail** |
| ![Etapas da renovação com o próximo passo](docs/renovacao-pme/etapas.png) | ![Rascunho do e-mail da proposta para revisão](docs/renovacao-pme/rascunho-email.png) |
| **Resposta do cliente classificada** | **Trilha de auditoria** |
| ![Resposta do cliente com sugestão de status e confiança](docs/renovacao-pme/resposta-cliente.png) | ![Log de auditoria com ações permitidas e negadas](docs/renovacao-pme/auditoria.png) |
| **Proposta gerada** | **Demonstrativo de preço** |
| ![Proposta de renovação gerada](docs/renovacao-pme/proposta.png) | ![Demonstrativo de formação de preço](docs/renovacao-pme/demonstrativo.png) |

<sub>Prints feitos com dados fictícios.</sub>

### Projeto pessoal

🎵 **[Mixteca](https://github.com/Necsoz/mixteca)**: organizador de músicas para Windows. Detecta BPM e tom (Camelot), completa tags e capas e organiza em pastas por gênero → BPM → tom. Python, PT/EN.

| Conferir as músicas | Montar a organização |
|---|---|
| ![Lista com BPM e tom](https://github.com/Necsoz/mixteca/raw/master/docs/pt-2-conferir.png) | ![Ordem das pastas e prévia](https://github.com/Necsoz/mixteca/raw/master/docs/pt-3-organizar.png) |

⬇️ [Baixar o instalador para Windows](https://github.com/Necsoz/mixteca/releases/latest)

### Como eu trabalho

Mapeio o processo com quem opera, defino as regras e a experiência de uso, e conduzo agentes de IA para construir. O código é feito com apoio de IA, e eu valido o resultado em casos reais.

### 💬 Fale comigo

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Lucas%20G.%20Rei-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lucas-g-rei777)

📍 Brasil

---

<a id="en"></a>

## 🇺🇸 About me

I build **AI-agent automations** that take manual, repetitive work off people's plates. I design the process, define the business rules and the user experience, and build the solution with AI. I'm studying Systems Analysis and Development (a Brazilian software systems degree).

### 🚀 Open to opportunities

Looking for my first role in IT: **applied AI and automation**, or **support and infrastructure**.

### What I do

- AI agents (such as Cursor) to create and iterate on tools and automations
- Automating routines and spreadsheets (JavaScript, VBA, Python)
- Tools that save hours of manual work

### Tools I built at work

#### 🧰 Toolbox: automation hub for registration and pricing

An automation hub for registering and pricing occupational health exams. It runs inside the management system, launched from a browser bookmark, and does on its own tasks that used to be done screen by screen.

- **30+ modules:** clinic onboarding (one at a time or in batches), renewals and price adjustments, Mark-Up, spreadsheet generation, registration and knowledge bases
- **Safe execution:** STOP button, pause and resume, and a screen check before acting (if the system changes, nothing is done)
- **Time per clinic registration:** from 3–7 min to ~1 min
- **Renewal with 20–30 providers:** from 1 h–2 h 30 (manual) to 20–30 min with the Toolbox routine, or 1–5 min with the spreadsheet option, recommended when there are many providers
- **Stack:** JavaScript (bookmarklet) and browser RPA, ~34k lines built with AI assistance in Cursor

| Main menu | Spreadsheets |
|---|---|
| ![Toolbox menu with its modules](docs/toolbox/menu.png) | ![Spreadsheets module](docs/toolbox/planilhas.png) |
| **Batch of requests** | **Progress with a stop button** |
| ![Requests pasted for batch processing](docs/toolbox/lote.png) | ![Batch onboarding in progress](docs/toolbox/progresso.png) |
| **Batch report** | **Protection against system changes** |
| ![Batch report with skipped items](docs/toolbox/relatorio.png) | ![Warning that the expected screen was not found](docs/toolbox/protecao.png) |
| **Settings** | |
| ![Toolbox settings](docs/toolbox/configuracoes.png) | |

<sub>Screenshots made with fictional data.</sub>

#### 📋 PME Renewal: occupational health contract renewals

Automates the yearly renewal of occupational health contracts for small and mid-sized companies, a process that used to be manual, scattered across spreadsheets, a management system and email, and prone to calculation errors and missed deadlines.

- **Background routine:** reads the contracts, pulls headcount and exam data, applies the contract's price index and generates a checked proposal and statement
- **Kanban web dashboard:** tracks each company until renewal, drafts emails for human review, classifies replies, checks signatures and schedules follow-ups
- **Time per document:** from 5–10 min (manual, one by one) to ~1 min
- **Stack:** Google Apps Script, Python, Google Sheets, Drive, Gmail and an AI agent
- Role-based access control and audit trail

| Kanban board | Company details |
|---|---|
| ![Kanban board of the month's renewals](docs/renovacao-pme/kanban.png) | ![Company details with proposal preview](docs/renovacao-pme/detalhe-empresa.png) |
| **Renewal steps** | **Email draft** |
| ![Renewal steps with the next step highlighted](docs/renovacao-pme/etapas.png) | ![Proposal email draft for review](docs/renovacao-pme/rascunho-email.png) |
| **Classified client reply** | **Audit trail** |
| ![Client reply with suggested status and confidence](docs/renovacao-pme/resposta-cliente.png) | ![Audit log with allowed and denied actions](docs/renovacao-pme/auditoria.png) |
| **Generated proposal** | **Pricing statement** |
| ![Generated renewal proposal](docs/renovacao-pme/proposta.png) | ![Pricing statement](docs/renovacao-pme/demonstrativo.png) |

<sub>Screenshots made with fictional data.</sub>

### Personal project

🎵 **[Mixteca](https://github.com/Necsoz/mixteca)**: a Windows music organizer. Detects BPM and key (Camelot), fills in tags and cover art, and organizes folders by genre → BPM → key. Python, PT/EN.

| Review your tracks | Build the organization |
|---|---|
| ![List with BPM and key](https://github.com/Necsoz/mixteca/raw/master/docs/en-2-review.png) | ![Folder order and preview](https://github.com/Necsoz/mixteca/raw/master/docs/en-3-organize.png) |

⬇️ [Download the Windows installer](https://github.com/Necsoz/mixteca/releases/latest)

### How I work

I map the process with the people who run it, define the rules and the user experience, and steer AI agents to build. The code is written with AI assistance, and I validate the results on real cases.

### 💬 Get in touch

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Lucas%20G.%20Rei-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lucas-g-rei777)

📍 Brazil
