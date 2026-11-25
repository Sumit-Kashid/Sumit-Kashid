# Sumit Kashid

AI engineer. I build LLM agents and the data systems behind them, and make sure they check their numbers before anyone acts on them. At Cincinnati Children's Hospital I build Care Advisor, an LLM agent for hospital staff, working on tool use, structured outputs, agent memory, and evaluation. I have nearly 4 years of experience shipping software, including two and a half years as a full stack engineer at Bank of America.

Master of Science in Business Analytics, University of Cincinnati, Carl H. Lindner College of Business. Expected December 2026.

**Website:** [sumit-kashid.github.io](https://sumit-kashid.github.io)

## In numbers

| | |
|---|---|
| **40%** | faster response to critical events from the ECI monitoring app I delivered at Bank of America |
| **85%** | less manual processing from Azure Data Factory pipelines I built for TQL |
| **92%** | higher data consistency in those same pipelines, across 50+ facilities |
| **11** | typed data tools behind Care Advisor at Cincinnati Children's |
| **120+** | graduate students taught as a teaching assistant, with 94% satisfaction |

## What I am working on

**Care Advisor, Cincinnati Children's Hospital Medical Center** (May 2026 to present) · [case study](https://github.com/Sumit-Kashid/care-advisor-case-study)

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

**SVM Dual Solver** · [svm-dual-solver](https://github.com/Sumit-Kashid/svm-dual-solver)
Soft margin SVM written from scratch in NumPy using SMO with second order working set selection. On five benchmarks it picks the same support vectors as scikit learn with 100% identical predictions, backed by 10 tests and CI.

**Regork Coupon Campaign Analysis** · [Data-Wrangling](https://github.com/Sumit-Kashid/Data-Wrangling)
R analysis of 653 coupon redemptions across 2,500 households. Found redemptions peak on day 6 and that 43% of exposed households had no income data, which hurt targeting more than any campaign setting. Group project.

**KO_MED Hospital Database** · [Data-Warehouse](https://github.com/Sumit-Kashid/Data-Warehouse)
Nine table SQL Server database normalized to 3NF, with an ER diagram, transaction scripts, and an INSTEAD OF trigger that blocks assigning an occupied bed.

**Red Wine Sugar and Density** · [Stat-Modeling](https://github.com/Sumit-Kashid/Stat-Modeling)
Hypothesis testing in R on 1,599 wines: Welch t test, ANOVA, and a chi square test checked with a 2,000 run permutation test.

**Hospital Navigation Chatbot Observability**
Added Langfuse tracing to a Django chatbot built on LangChain and Azure OpenAI, working through breaking changes in Langfuse v4 and LangChain 1.x.

**TQL Emissions Reporting, Net Impact Consulting** · [case study](https://github.com/Sumit-Kashid/tql-emissions-pipeline-case-study)
Azure Data Factory pipelines and Power BI dashboards tracking energy and emissions KPIs across 50+ facilities for executive leadership.

**Trusted AI in Banking, PNC CSL Case Competition** · [design](https://github.com/Sumit-Kashid/trusted-ai-banking-pnc)
An explainable AI assistant design with bias evaluation and audit logging.

## Experience

- **Cincinnati Children's Hospital Medical Center**, Intern, AI/ML and Data Engineering · May 2026 to present
- **Michelman**, Sustainability and Global Supply Chain Intern · May 2026 to present
- **Net Impact Consulting**, Project Lead for TQL · Jan 2026 to May 2026
- **University of Cincinnati**, Graduate Teaching Assistant, Data Analytics and Statistical Computing · Aug 2025 to May 2026
- **Bank of America**, Software Engineer, Full Stack Development · Feb 2023 to Aug 2025

## Tools I use

**LLM and agents:** LLM APIs, Azure OpenAI, tool use, structured outputs, agent memory, MCP, LangChain, LangGraph, RAG
**Evaluation and reliability:** evaluation test sets and scoring, Langfuse, MLflow, structured logging
**Machine learning:** NLP, fine tuning BERT models, GPU training, SVMs, time series, scikit learn
**Backend:** Python, FastAPI, Pydantic, Django, Node.js, TypeScript, Spring Boot, Kafka
**Cloud and DevOps:** Azure, AWS, GCP, Docker, GitHub Actions
**Data:** SQL, Microsoft Fabric, Azure Data Factory, Snowflake, PySpark, Power BI, Tableau

## Contact

[Website](https://sumit-kashid.github.io) · [Email](mailto:sumitkashid505@gmail.com) · [LinkedIn](https://www.linkedin.com/in/sumit-kashid/)

sumitkashid505@gmail.com · +1 513 290 0857
