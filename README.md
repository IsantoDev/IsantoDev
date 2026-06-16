<h1 align="center">Oi, eu sou o Igor Santos 👋</h1>

<p align="center">
  <strong>Analytics Engineer | Cientista de Dados</strong> · Goiânia, GO<br/>
  Transformo dados brutos em decisões. Tenho produtos em produção — não só projetos no GitHub.
</p>

---

## Sobre mim

Sou um profissional de dados com foco em entregar infraestrutura operacional real.

Hoje mantenho em **produção** um dashboard de BI conectado via API à plataforma TOTVS, com star schema, ETL em Power Query e DAX personalizado — usado diretamente pela liderança da minha equipe na Duofy. Em paralelo, desenvolvo dois produtos próprios em Python.

Minha lógica é simples: dados só têm valor quando alguém toma uma decisão melhor por causa deles.

- 🎓 Cursando **Sistemas de Informação** (UniAlfa) + **CST em Ciência de Dados** (Gran Faculdade)
- 🏭 Experiência prática com **ERP Protheus / TOTVS** em ambiente de produção
- 🔐 Foco em qualidade, segurança e conformidade com **LGPD** e **Six Sigma Yellow Belt**
- 📍 Goiânia, GO — aberto a oportunidades remotas

---

## Em Produção

### 🟢 Central de Tickets — Duofy · Suporte TOTVS
Dashboard de BI em uso real pela liderança da Duofy. Substituiu exportação manual por uma integração via API com atualização automática a cada 30 minutos.

- Star schema: tabela `Fato_Ticket` + 6 dimensões
- DAX: % SLA por produto, backlog ativo, taxa de reabertura, TMR e classificação melhoria vs. problema
- 3 páginas com storytelling dedicado: visão consolidada + King Posto + Deathcare
- Filtro de mês sincronizado entre páginas e navegação multipágina
- SQL direto em tabelas de produção do ERP Protheus para investigação de chamados

`Power BI` `DAX` `Power Query` `API TOTVS` `SQL Server`

---

## Produtos em Desenvolvimento

### 📊 Datiio Analytics
Dashboard financeiro para gestores de empresas que usam o ERP Protheus. Conecta diretamente nas tabelas SA1/SE1/SE2 e entrega **13 KPIs em tempo real** — no celular, web ou desktop.

- Faturamento, inadimplência, fluxo de caixa, saúde da carteira — tudo calculado automaticamente
- Autenticação segura (PBKDF2, 600k iterações), rate limiting, trilha de auditoria e LGPD
- Layout responsivo: NavigationRail (desktop) + NavigationBar (mobile)
- 12 testes unitários cobrindo KPIs, hash e rate limit

`Python` `Flet` `SQLite` `PostgreSQL (Neon)` `FastAPI`

---

### 💰 Datiio Finance
App de finanças pessoais com **Score Financeiro 0–100**, metas por categoria e importação de extratos PDF de 5 bancos brasileiros — sem depender de Open Finance.

- Score proprietário com 5 componentes: saldo, economia, metas, regularidade e tendência
- Importação de Nubank, Itaú, Inter, Bradesco e BB + OFX com categorização automática
- Arquitetura separada: Flet (frontend) + FastAPI (backend REST) com JWT + bcrypt

`Python` `Flet` `FastAPI` `SQLite` `JWT` `bcrypt`

---

## Projetos Open Source

### 📡 [AI-Radar ETL](https://github.com/IsantoDev/radar-etl)
Pipeline autônomo que monitora o mercado de IA: busca notícias na web, resume com Gemini e envia um relatório executivo por e-mail de forma agendada.

`Python` `Schedule` `SMTP` `DuckDuckGo Search` `Google Gemini`

---

### 🎯 [Job Hunter AI](https://github.com/IsantoDev/JobHunter) · [demo ao vivo](https://jobhunteria.streamlit.app/)
App web que compara currículos com descrições de vagas usando GenAI e devolve um feedback de compatibilidade detalhado.

`Python` `Streamlit` `Google Gemini` `PyPDF`

---

## Stack Técnica

**Dados & BI**
Power BI · DAX · Power Query · Star Schema · SQL Server · SQLite · PostgreSQL

**Python**
Pandas · Flet · FastAPI · bcrypt · JWT · parsing de PDF · automação ETL

**IA & LLMs**
Google Gemini API · OpenAI API · Arquitetura RAG

**Qualidade & Governança**
LGPD · Six Sigma Yellow Belt · testes unitários · trilha de auditoria

**Em estudo**
Looker Studio · dbt · BigQuery · estatística aplicada · CTEs e window functions

---

## Experiência Recente

**Analista de Suporte · Duofy** *(fev/2026 – atual)*
Dashboard de Central de Tickets em produção com atualização automática a cada 30min via API TOTVS. SQL em tabelas de produção do ERP Protheus, automação com Python + Pandas.

**Auxiliar de Gestão de KPIs · Tahto** *(2023 – 2024)*
Relatórios de performance operacional (SLA, TME, TMA) e monitoramento de métricas para equipes de gestão.

---

## Vamos conversar?

<p>
  <a href="https://www.linkedin.com/in/isantosdev/">LinkedIn</a> ·
  <a href="mailto:isantos.code@gmail.com">isantos.code@gmail.com</a>
</p>
