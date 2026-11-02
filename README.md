<h1 align="center">Olá, eu sou o Anderson Dittrich 🖖</h1>

<p align="center">
  <b>Construo plataformas de IA corporativa e sistemas para cartórios</b><br>
  RAG · orquestração de LLMs · APIs em Python · desktop moderno · automação de dados
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/anderson-dittrich/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:thedittrich18@gmail.com"><img src="https://img.shields.io/badge/E--mail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="E-mail"></a>
</p>

---

### 🧠 O que eu construo

Quase tudo que faço vive em repositórios privados, então aqui vai o resumo do que está por trás dos quadradinhos:

- **Plataforma de IA corporativa.** API em FastAPI com RAG híbrido (vetorial + palavra-chave) sobre a base de conhecimento interna, embeddings multilíngues (bge-m3 + pgvector) e cascata entre vários provedores de LLM com circuit breaker, cache semântico e controle de custo por endpoint.
- **Inteligência de Customer Success.** Health Score de clientes calculado a partir de contratos, uso e atendimentos, além de análise automática de atendimentos com LLM.
- **Design systems próprios.** Um kit de UI para web e a versão dele para desktop em PySide6, com tokens, layouts e aparência configurável por usuário, usados como base de vários produtos.
- **Modernização de legado.** Migração de sistemas desktop para PySide6 e pontes de dados entre bancos legados (DBISAM, SQL Server) e PostgreSQL, levando dados para a web e para sistemas externos.
- **OCR e extração de documentos.** Pipelines que leem, classificam e estruturam documentos de cartório.
- **Infra e deploy.** Apps em container numa VPS com Caddy, deploy automatizado, telemetria e monitoramento.

### 🏗️ Como costuma ser por dentro

```mermaid
flowchart LR
    U[Usuários e times internos] --> API[API FastAPI]
    API --> AUTH[JWT + permissões por papel]
    API --> RAG[RAG híbrido]
    RAG --> PG[(PostgreSQL + pgvector)]
    RAG --> EMB[Embeddings bge-m3]
    API --> LLM{Cascata de LLMs}
    LLM --> A[Anthropic]
    LLM -.fallback.-> G[Groq / Gemini / OpenAI]
    API --> ERP[(SQL Server legado)]
    API --> CRM[CRM]
    API --> BG[Schedulers e workers]
```

### 🛠️ Stack

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/pgvector-336791?style=flat-square&logo=postgresql&logoColor=white" alt="pgvector">
  <img src="https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white" alt="SQL Server">
  <img src="https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white" alt="Claude">
  <img src="https://img.shields.io/badge/Qt_PySide6-41CD52?style=flat-square&logo=qt&logoColor=white" alt="PySide6">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Caddy-1F88C0?style=flat-square&logo=caddy&logoColor=white" alt="Caddy">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white" alt="PHP">
</p>

### 📊 Atividade (inclui os repositórios privados)

<p align="center">
  <img src="https://raw.githubusercontent.com/TheDittrich/TheDittrich/output/metrics.svg" alt="Métricas do GitHub">
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/TheDittrich/TheDittrich/output/github-snake-dark.svg">
    <img src="https://raw.githubusercontent.com/TheDittrich/TheDittrich/output/github-snake.svg" alt="Cobrinha comendo o gráfico de contribuições">
  </picture>
</p>
