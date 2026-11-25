# Sumit Kashid

Software engineer with nearly 4 years of experience building backend services, data pipelines, and LLM tools that check their data before anyone acts on it. I work at Cincinnati Children's Hospital on production LLM tools for hospital staff, and before graduate school I spent two and a half years as a full stack engineer at Bank of America.

Master of Science in Business Analytics, University of Cincinnati, Carl H. Lindner College of Business. Expected December 2026.

## In numbers

| | |
|---|---|
| **40%** | faster response to critical events from the ECI monitoring app I delivered at Bank of America |
| **85%** | less manual processing from Azure Data Factory pipelines I built for TQL |
| **92%** | higher data consistency in those same pipelines, across 50+ facilities |
| **11** | typed data tools behind Care Advisor at Cincinnati Children's |
| **120+** | graduate students taught as a teaching assistant, with 94% satisfaction |

## What I am working on

**Care Advisor, Cincinnati Children's Hospital Medical Center** (May 2026 to present)

A patient flow and capacity tool for hospital staff. The rule I build by: Python does the math, the model only explains it.

- FastMCP Python server with eleven forecasting and capacity tools over hospital data in Microsoft Fabric SQL
- Flat, typed Pydantic tool schemas, so the model makes clean structured tool calls and every input is validated
- FastAPI gateway in Docker, deployed to Azure inside a private network, with token based sign in and CI running ruff, mypy, tests, and the image build
- Daily capacity brief: a scheduled Fabric pipeline calls the gateway and posts to Teams, and a freshness check stops the report when a source is stale or incomplete
- Evaluation test sets and scoring, Langfuse tracing, and agent memory
- A data audit that found three production bugs, including a NULL versus text filter that returned empty results with no error

## Selected projects

**Prior Authorization Readiness Classifier** · [NLP](https://github.com/Sumit-Kashid/NLP)
Fine tuned BiomedBERT on 5,000 de identified MIMIC IV records and compared three BERT models against a TF IDF baseline, with leakage prevention, weighted loss, threshold tuning, and fp16 mixed precision on GPU. The result was near random AUC with a majority class bias, and I reported it that way rather than leaning on a single F1 score.

**Hospital Navigation Chatbot Observability**
Added Langfuse tracing to a Django chatbot built on LangChain and Azure OpenAI, working through breaking changes in Langfuse v4 and LangChain 1.x.

**TQL Emissions Reporting, Net Impact Consulting**
Azure Data Factory pipelines and Power BI dashboards tracking energy and emissions KPIs across 50+ facilities for executive leadership.

**Trusted AI in Banking, PNC CSL Case Competition**
An explainable AI assistant design with bias evaluation and audit logging.

## Experience

- **Cincinnati Children's Hospital Medical Center**, Intern, AI/ML and Data Engineering · May 2026 to present
- **Michelman**, Sustainability and Global Supply Chain Intern · May 2026 to present
- **Net Impact Consulting**, Project Lead for TQL · Jan 2026 to May 2026
- **University of Cincinnati**, Graduate Teaching Assistant, Data Analytics and Statistical Computing · Aug 2025 to May 2026
- **Bank of America**, Software Engineer, Full Stack Development · Feb 2023 to Aug 2025

## Tools I use

**Languages:** Python, TypeScript, JavaScript, SQL, Java, R, PySpark
**Backend:** FastAPI, Django, Node.js, Spring Boot, Kafka, .NET microservices, Pydantic
**Cloud and DevOps:** Azure, AWS, GCP, Docker, GitHub Actions
**Data:** Microsoft Fabric, Azure Data Factory, Snowflake, Power BI, Tableau
**LLM systems:** Azure OpenAI, MCP, LangChain, LangGraph, RAG, Langfuse, MLflow

## Contact

[Email](mailto:sumitkashid505@gmail.com) · [LinkedIn](https://www.linkedin.com/in/sumit-kashid/)

sumitkashid505@gmail.com · +1 513 290 0857
