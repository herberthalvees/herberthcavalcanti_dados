# Olá, sou o Herberth 👋

Analista de Dados / Engenheiro de Dados com mais de 4 anos de experiência em BI, pipelines de dados e modelagem dimensional.

📍 Natal/RN | 💼 Aberto a oportunidades de Analista e Engenheiro de Dados

## 🛠️ Stack

**Dados e BI:** SQL, Power BI, DAX, Power Query, Modelagem Dimensional, RLS
**Engenharia de dados:** Python, PySpark, Databricks, Delta Lake, dbt, Apache Airflow, ETL/ELT
**Cloud e plataformas analíticas:** Google BigQuery, GCP (Cloud Storage), AWS, Supabase/PostgreSQL
**Full-stack:** React, TypeScript, TanStack Start
**Versionamento e DevOps:** Git, GitHub, GitLab, Azure DevOps

## 🚀 Projetos em destaque

### [Pipeline SELIC × IPCA — Databricks](https://github.com/herberthalvees/case-bcb)
Pipeline de dados ponta a ponta em arquitetura medalhão (Bronze → Silver → Gold) sobre Delta Lake e Unity Catalog, calculando o juro real mensal a partir de séries públicas do Banco Central do Brasil.

- 18 checagens automáticas de qualidade em três camadas, com o job falhando explicitamente diante de dado inconsistente em vez de propagar erro silencioso
- Idempotência comprovada pelo próprio histórico de operações do Delta (MERGE por chave de negócio + deduplicação)
- Resultado validado ponta a ponta contra os números oficiais do IBGE (2020–2024)
- Orquestração declarativa via Databricks Asset Bundle, com targets isolados de dev e produção

**Tecnologias:** `Python` `PySpark` `Databricks` `Delta Lake` `Unity Catalog` `SQL`

---

### Painel de Gestão para E-commerce Multi-loja *(projeto privado)*
Painel full-stack para gestão de uma operação de e-commerce multi-loja: pedidos, estoque, financeiro, campanhas de ads, avaliações e atendimento ao cliente, com sincronização automática via API.

- Arquitetura full-stack sem backend separado — SSR, rotas de API e server functions no mesmo app
- Sincronização automática por jobs agendados e webhooks autenticados
- Suporte a múltiplas lojas, cada uma com credenciais isoladas e dados segregados por controle de acesso no banco
- Chat interno com IA que responde perguntas de negócio consultando os dados reais do painel

**Tecnologias:** `React` `TypeScript` `TanStack Start` `Supabase/PostgreSQL` `Tailwind CSS` `IA`

*Repositório privado — código não disponível publicamente.*

---

### Portal Corporativo de Consulta a Data Warehouse *(projeto privado)*
Portal seguro de autoatendimento a dados no Google BigQuery: a pessoa pergunta em linguagem natural e recebe uma resposta usando apenas os dados que tem permissão de ver.

- Autenticação corporativa via Google OIDC, com validação completa do token no backend (assinatura, emissor, expiração, domínio)
- Controle de acesso em duas camadas — RBAC (papéis e permissões) + ABAC (atributos que filtram linhas, ex.: região)
- Perguntas em linguagem natural viram uma consulta estruturada e controlada — nunca SQL livre vindo do usuário
- Camada semântica com catálogo de métricas versionado e trilha de auditoria *append-only*

**Tecnologias:** `TypeScript` `React` `TanStack Start` `Google BigQuery` `PostgreSQL` `IA`

*Repositório privado — código não disponível publicamente.*

## 📫 Contato

[LinkedIn](https://linkedin.com/in/seu-perfil) | seu.email@exemplo.com
