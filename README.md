<h1 align="center">Igor Ribeiro</h1>
<p align="center">Dados · Python · SQL · Power BI · ML e IA aplicada · Goiânia/GO</p>

---

Trabalho com dados de operação. No suporte N2 de ERP (Protheus, PDV e fiscal), investigo incidentes com SQL em produção e transformo o que se repete em pipeline, painel ou ferramenta. Meus projetos partem de problemas reais: chamados, SLA, sensores de máquina, serviços que caem.

### 📊 Em produção no trabalho (repositório privado)

- **Central de SLA:** pipeline que consome a API do Movidesk, organiza os chamados em banco e alimenta um painel em Power BI de fila e SLA, acompanhado pela equipe no dia a dia.

### 🚀 Projetos públicos

| Projeto | O que resolve | Stack |
|---|---|---|
| 🔗 **[elo-copiloto-suporte](https://github.com/IsantoDev/elo-copiloto-suporte)** | Pipeline de chamados (bruto → limpo → checagens de qualidade), análise do que leva um ticket a estourar o SLA, triagem por vizinhos com risco de SLA (AUC 0,84) e RAG com fontes em LLM local. Dados pessoais mascarados; nenhum dado sai da máquina. | Python · PostgreSQL · pgvector · FastAPI · Ollama |
| 🏭 **[industria-preditiva](https://github.com/IsantoDev/industria-preditiva)** | Manutenção preditiva: prevê falha de máquina a partir de sensores (AI4I 2020). EDA, estatística, engenharia de atributos, modelo e API. | Python · SQL · pandas · scikit-learn |
| 🛰️ **[pipeline-sentinela](https://github.com/IsantoDev/pipeline-sentinela)** | Monitor de serviços e integrações: status e latência, uptime, classificação por SLA e alerta no Teams. | Python · SQLite · Docker · pytest · GitHub Actions |
| 🤖 **[radar-etl](https://github.com/IsantoDev/radar-etl)** | ETL agendado: coleta notícias tech, resume com LLM e entrega por e-mail. | Python · ETL · Gemini · SMTP |

### 🛠️ Stack

**Dados:** SQL Server · PostgreSQL · SQLite · pandas · Power BI (DAX, modelagem estrela) · ETL · checagens de qualidade

**Análise e ML:** estatística e testes de hipótese · scikit-learn · métricas de classificação (AUC, precisão/recall)

**IA aplicada:** RAG · embeddings · pgvector · LLMs locais (Ollama) · Gemini

**Engenharia:** Python · APIs REST · FastAPI · Docker / Compose · Git · GitHub Actions · pytest · Linux

**Boas práticas com dados:** mascaramento de dados pessoais (LGPD) · controle de acesso por perfil · trilha de auditoria

---

📫 [LinkedIn](https://www.linkedin.com/in/isantosdev)
