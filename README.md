# Lucas Santana

**Engenharia de Dados · Cloud & FinOps · IA aplicada** · Barueri, SP

Construo plataformas de dados e produtos que vão para produção com testes, observabilidade e custo sob controle. Co-Founder & CTO na **Connect fit**, desenvolvedor na **Arklok Tecnologia** e estudante de tecnologia na **Estácio**.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lucas-santana-45316232a/)
[![Email](https://img.shields.io/badge/lucas.santana2301@gmail.com-D14836?logo=gmail&logoColor=white)](mailto:lucas.santana2301@gmail.com)
[![Credly](https://img.shields.io/badge/Certificações-FF6B00?logo=credly&logoColor=white)](https://www.credly.com/users/lucas-santana.fa782343/badges)

## Projetos em destaque

| Projeto | O que resolve | Destaques de engenharia |
| :-- | :-- | :-- |
| **[IT Asset Lakehouse](https://github.com/lucassantana2301-bot/it-asset-lakehouse)** · [painel ao vivo](https://lucassantana2301-bot.github.io/it-asset-lakehouse/) | Plataforma de dados ponta a ponta de uma locadora de equipamentos de TI: da extração dos sistemas de origem ao painel executivo. | Contrato de dados com quarentena · dbt com SCD2 e reconciliação de MRR · Dagster · Terraform na AWS com OIDC · 95% de cobertura |
| **[FinOps Sentinel](https://github.com/lucassantana2301-bot/finops-sentinel)** · [demo ao vivo](https://lucassantana2301-bot.github.io/finops-sentinel/) | Unifica o billing de AWS e Azure no padrão FOCUS, detecta anomalias de custo, prevê o fechamento do mês contra o orçamento e recomenda economia. | Detecção robusta (mediana/MAD com sazonalidade) · 79 testes · imagens no GHCR com SBOM e proveniência · TypeScript, Fastify, React |
| **[RAG Docs Assistant](https://github.com/lucassantana2301-bot/rag-docs-assistant)** · [relatório de avaliação](https://lucassantana2301-bot.github.io/rag-docs-assistant/) | Responde perguntas sobre documentos internos sempre com citação, e recusa quando a resposta não está nos documentos. | Busca híbrida BM25 + vetores com RRF · golden set como portão de qualidade no CI · mypy strict · Python, FastAPI, SQLite FTS5 |
| **[PRISM](https://github.com/lucassantana2301-bot/PRISM-Business-Intelligence-Platform)** | Plataforma de BI com motor semântico de métricas e perguntas em linguagem natural convertidas em SQL validado. | Validação de AST com allowlist · Next.js 16, Python, DuckDB |
| **[B3 Portfolio Tracker](https://github.com/lucassantana2301-bot/b3-investe-)** | Carteira da B3 com preço médio, proventos e apuração mensal do IR, gerando o DARF. | Aritmética decimal exata · arquitetura hexagonal com PostgreSQL e MS Access · TypeScript, Python |
| **[Família Cashflow](https://github.com/lucassantana2301-bot/familia-cashflow)** | Orçamento familiar por envelopes com importação de extrato OFX/CSV sem duplicar lançamentos. | Isolamento entre famílias garantido pelo banco (FK composta) · Argon2id · Rust, axum, sqlx |
| **[Zabbix Observability](https://github.com/lucassantana2301-bot/-zabbix-avan-ado-)** | Monitoramento como código: YAML versionado aplicado no Zabbix 7 com `plan`/`apply` idempotente. | Teste ponta a ponta contra o Zabbix real no CI · Grafana · alertas no Telegram |

Todos têm CI, CHANGELOG, releases versionadas (SemVer) e roadmap aberto em issues.

## Como eu trabalho

- **Qualidade como código:** testes automatizados em todo projeto, lint e tipagem estrita, cobertura publicada e portões de qualidade de dados no CI.
- **Decisões documentadas:** ADRs para escolhas de arquitetura e READMEs que explicam o problema, os trade-offs e as limitações.
- **Entrega rastreável:** Conventional Commits, PRs com descrição e release automática com notas, imagens assinadas e pacotes anexados.
- **Segurança desde o início:** menor privilégio, segredos fora do código, CodeQL e Dependabot, e política de reporte de vulnerabilidades.
- **Custo e operação:** FinOps, observabilidade e infraestrutura como código.

## Stack

- **Dados:** Python · SQL · dbt · Dagster · DuckDB · PostgreSQL · Parquet · Power BI
- **Back-end:** TypeScript · Node.js (Fastify) · FastAPI · Rust (axum)
- **Front-end:** React · Next.js · Vite
- **Cloud e DevOps:** AWS · Azure · Docker · Terraform · GitHub Actions · Zabbix · Grafana
- **IA:** RAG, busca híbrida e avaliação de LLMs (OpenAI, Anthropic, Ollama)
