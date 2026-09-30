# Arthur Pozzi

**Desenvolvedor full-stack e engenheiro de sistemas agênticos.**

Construo sistemas web, automações e pipelines multi-agente de ponta a ponta, do código à VPS em produção.
Escrevo TypeScript e Python, cuido de banco, workers e deploy, e uso agentes de IA como parte do processo de engenharia:
um agente planeja, outro implementa em worktree isolado, dois revisam (spec e código) antes do merge.

**Hoje:**
- 💼 Atendendo projetos como freelancer
- 🎓 Finalizando a graduação em Análise e Desenvolvimento de Sistemas (ADS)
- 🤖 Fazendo as formações da Anthropic e da Asimov Academy em automação com agentes de IA

**Stack:** TypeScript · Node · Next.js · React · Fastify · Prisma · Drizzle · Postgres · Supabase · Python · Docker · Caddy · Playwright · Vitest

---

## Em destaque

### 🏥 Gestão Clínicas
Sistema de gestão clínica multi-tenant, em produção para substituir o software legado de uma clínica real.
- Agenda Dia/Semana/Mês com validação de conflito em tempo real e garantia de concorrência no banco
- Pacientes, responsáveis legais, prontuário e atendimento
- Assinatura digital do atendimento (selfie + GPS + CPF + termo + QR de verificação)
- Receituário, atestado e declaração em PDF com modelos e variáveis
- Financeiro completo (contas a receber e a pagar), estoque, fornecedores e NF de entrada
- Importação re-executável dos dados do sistema antigo e dashboards sobre os dados reais
- Isolamento de tenant provado por teste, upload seguro, backup restaurável e runbook de operação

`Next.js` `React` `Prisma` `Postgres` `Docker` `Caddy` `Vitest` `Playwright` · 700+ commits · código privado

### 📋 Sistema IDC
Substituiu o Pipefy no processo de avaliação multiprofissional de um instituto.
Engine data-driven: pipes, fases e campos são registros no banco. Tem formulário público, anexos e Kanban.
Construído com subagent-driven development e entregue em VPS com Docker, TLS e backup cifrado.

`Node` `Fastify` `React` `Vite` `Prisma` `Postgres` `Docker` · código privado

---

## Automação e IA

| Projeto | O que faz | Stack |
|---|---|---|
| **Maps Leads Scraper** | Coleta leads do Google Maps e roda o pipeline limpeza → filtro → enriquecimento com Core Web Vitals → relatório → planilha | Node · Playwright · Lighthouse · PM2 |
| **Sales Cadence** | Cadência de prospecção por trilhas e segmento, em e-mail (Resend) e WhatsApp, com proteção anti-ban | TypeScript · Prisma · Clean Architecture |
| **CarrosselBuilder** | Cria carrosséis por cadeia de agentes: perfil de marca → direção criativa → QA de copy → direção de arte → QA visual, cada etapa no modelo mais adequado | Python · GPT-4o · DeepSeek · Gemini |
| **Radar de pautas** | Escolhe o vídeo do dia: agrega News, Trends, Reddit, HN e YouTube, pontua de 0 a 100 e manda o briefing no WhatsApp | Python · RSS/APIs |
| **CRM** | CRM com Kanban drag-and-drop, importação CSV/XLSX, relatórios e worker de WhatsApp | Next.js · Supabase · Drizzle |
| **Arthur.log** | Diário e análise de desempenho pessoal, PWA local-first | React · Vite · IndexedDB |

## Sites e landing pages

| Projeto | Demo |
|---|---|
| [t3h4](https://github.com/arthurpozzi-dev/t3h4): site institucional multilíngue (EN/PT/DE) | [t3h4.vercel.app](https://t3h4.vercel.app) |
| [advogado-drcadu](https://github.com/arthurpozzi-dev/advogado-drcadu): landing page de blindagem patrimonial | [ver site](https://advogado-drcadu.vercel.app) |
| [vem-ca](https://github.com/arthurpozzi-dev/vem-ca): site de escola de música | [ver site](https://vem-ca.vercel.app) |

---

## Contato

Aberto a projetos freelance e oportunidades.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-arthur--pozzi01-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/arthur-pozzi01/)
[![Email](https://img.shields.io/badge/Email-arthurpozzi01%40gmail.com-EA4335?logo=gmail&logoColor=white)](mailto:arthurpozzi01@gmail.com)
