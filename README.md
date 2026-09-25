<div align="center">

  <!-- Animated Typing Banner -->
  <a href="https://github.com/irajput215">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=2600&pause=1000&color=38BDF8&center=true&vCenter=true&width=620&lines=Hi%2C%20I%27m%20Ishu%20Rajput;Data%20and%20AI%20Engineer;Systems%20Architecture%20Thinker;Building%20Agentic%20AI%20and%20Data%20Platforms" alt="Typing SVG Banner" />
  </a>

  <p align="center">
    <strong>Data Platforms &bull; Applied AI &amp; Agents &bull; System Architecture</strong>
  </p>

  <!-- Social &amp; Profile Badges -->
  <p align="center">
    <a href="https://www.linkedin.com/in/irajput215" target="_blank">
      <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    <a href="https://github.com/irajput215" target="_blank">
      <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
    </a>
    <a href="mailto:eshurajput007@gmail.com" target="_blank">
      <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
    </a>
  </p>

  <p align="center">
    <img src="https://img.shields.io/badge/Location-Sydney%2C%20Australia-0284C7?style=flat-square&logo=googlemaps&logoColor=white" alt="Sydney" />
    <img src="https://img.shields.io/badge/Master's-UNSW%20Sydney-F59E0B?style=flat-square&logo=googlescholar&logoColor=white" alt="UNSW" />
    <img src="https://img.shields.io/badge/Focus-Data%20%2B%20AI%20Engineering-8B5CF6?style=flat-square" alt="Focus" />
  </p>

</div>

---

### Executive Summary &amp; Engineering Focus

> *Data &amp; AI Engineer who designs the architecture first, ships it to production, and stays calm when it breaks at 2am.*

I build **end-to-end data and AI systems**: lakehouses and warehouses that are actually trustworthy, and LLM/agent layers that are actually evaluated. I care about the parts most demos skip — **idempotent pipelines, tested transformations, typed tools behind real boundaries, measured accuracy, and human-in-the-loop control** before anything touches production data.

- **Data Platforms &amp; Architecture:** Medallion lakehouse design (S3 → Snowflake → dbt → Airflow), dimensional and SCD2 modelling, incremental/MERGE fact loading, keyless cloud storage integrations, and read/write boundary separation by role.
- **Applied AI &amp; Agents:** LangGraph state machines, bounded tool-calling agents, hybrid RAG (pgvector + knowledge graph), QLoRA fine-tuning with execution-based eval harnesses, and LLM enrichment turned into queryable warehouse columns.
- **Production Reliability &amp; Incident Response:** MLflow experiment tracking, CI/CD quality gates, containerized serving, drift and data-quality monitoring, structured tracing, human-in-the-loop approval gates on anything that mutates production data, and root-cause analysis that reports <code>UNRESOLVED</code> rather than guessing.

---

### Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="left">Zomato AI Data Platform</h3>
      <p><strong>10M-Order Batch Lakehouse + LLM Analytics Layer</strong></p>
      <p>End-to-end batch platform: raw CSVs → Amazon S3 → Snowflake (medallion) → dbt → Airflow, over <strong>10M orders</strong> and ~<strong>23M order items</strong>. An LLM lane enriches <strong>300K free-text reviews</strong> into tested sentiment/topic columns, powering RAG chat, text-to-SQL and a Streamlit mart dashboard — every read-only consumer bound to a read-only role.</p>
      <p>
        <a href="https://github.com/irajput215/zomato-ai-data-platform" target="_blank"><img src="https://img.shields.io/badge/Repository-zomato--ai--data--platform-181717?style=flat-square&logo=github" alt="Repo" /></a>
        <img src="https://img.shields.io/badge/17%20dbt%20models-80%20tests-38BDF8?style=flat-square" alt="dbt" />
      </p>
      <p>
        <img src="https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white" alt="Snowflake" />
        <img src="https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white" alt="dbt" />
        <img src="https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white" alt="Airflow" />
        <img src="https://img.shields.io/badge/Amazon%20S3-569A31?style=flat-square&logo=amazons3&logoColor=white" alt="S3" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3 align="left">CourseLLM</h3>
      <p><strong>Agentic RAG Tutoring Platform with Citations &amp; Evals</strong></p>
      <p>Upload your own course material, state a goal, and get answers grounded in those documents — with citations, a prerequisite-aware roadmap, curated resources, quizzes and progress-adaptive planning. Hybrid retrieval over PostgreSQL + pgvector, a knowledge graph, a bounded LangGraph, and a measured evaluation pipeline.</p>
      <p>
        <a href="https://github.com/irajput215/coursellm2" target="_blank"><img src="https://img.shields.io/badge/Repository-coursellm2-181717?style=flat-square&logo=github" alt="Repo" /></a>
        <img src="https://img.shields.io/badge/1%2C643%20tests%20%C2%B7%2083%25%20cov-22C55E?style=flat-square" alt="Tests" />
      </p>
      <p>
        <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square" alt="LangGraph" />
        <img src="https://img.shields.io/badge/Python%203.12-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
        <img src="https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="pgvector" />
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="left">Pipeline Incident Response Agent</h3>
      <p><strong>Agentic Root-Cause Analysis for Failed Data Pipelines</strong></p>
      <p>Given a 2am alert that <code>customer_claims_daily</code> failed, a LangGraph state machine triages it across nine failure categories, then runs bounded rounds of investigation using <strong>nine typed diagnostic tools behind a real read-only SQL boundary</strong>. It commits to a root cause only when evidence supports one — otherwise it ends <code>UNRESOLVED</code> rather than guessing. Data-mutating fixes pause for human approval, and every node, tool call, token and millisecond is persisted.</p>
      <p>
        <a href="https://github.com/irajput215/incident-response-agent" target="_blank"><img src="https://img.shields.io/badge/Repository-incident--response--agent-181717?style=flat-square&logo=github" alt="Repo" /></a>
        <img src="https://img.shields.io/badge/228%20tests%20%C2%B7%208%2F8%20eval%20tasks-22C55E?style=flat-square" alt="Evals" />
      </p>
      <p>
        <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square" alt="LangGraph" />
        <img src="https://img.shields.io/badge/LangSmith%20Tracing-FF6F61?style=flat-square" alt="LangSmith" />
        <img src="https://img.shields.io/badge/HITL%20Approval%20Gate-6366F1?style=flat-square" alt="HITL" />
        <img src="https://img.shields.io/badge/Read--Only%20SQL-4169E1?style=flat-square" alt="SQL" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3 align="left">GTSRB Traffic Sign Recognition</h3>
      <p><strong>Production-Ready 43-Class Computer Vision System</strong></p>
      <p>Traffic sign classification taken from notebook to deployed service, with reproducible splits, calibrated confidence and structured error analysis. Checkpoint selection keys on <strong>macro F1 rather than accuracy</strong> — because accuracy hid a class sitting at 54.2% recall. <strong>98.90% accuracy, 0.9837 macro F1</strong> on the official 12,630-image test split, with MLflow tracking and a containerised FastAPI inference service.</p>
      <p>
        <a href="https://github.com/irajput215/GTSRB-Traffic-Sign-Recognition-Deep-Learning-Project-" target="_blank"><img src="https://img.shields.io/badge/Repository-GTSRB-181717?style=flat-square&logo=github" alt="Repo" /></a>
        <img src="https://img.shields.io/badge/455%20tests%20%C2%B7%2092%25%20cov-22C55E?style=flat-square" alt="Tests" />
      </p>
      <p>
        <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
        <img src="https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white" alt="MLflow" />
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
        <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
      </p>
    </td>
  </tr>
</table>

---

### Technical Competencies

<div align="center">

| Domain | Core Technologies &amp; Tooling |
| :--- | :--- |
| **Data Engineering &amp; Warehousing** | ![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white) ![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white) ![Apache Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white) ![Apache Spark](https://img.shields.io/badge/Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white) ![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white) ![Amazon S3](https://img.shields.io/badge/S3-569A31?style=flat-square&logo=amazons3&logoColor=white) ![Delta Lake](https://img.shields.io/badge/Delta%20Lake-00ADD4?style=flat-square) |
| **AI, LLM &amp; Agents** | ![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white) ![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-FFD21E?style=flat-square) ![vLLM](https://img.shields.io/badge/vLLM-FFD21E?style=flat-square) ![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) |
| **MLOps, Cloud &amp; Reliability** | ![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![LangSmith](https://img.shields.io/badge/LangSmith-FF6F61?style=flat-square) |
| **Backend &amp; Interfaces** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat-square) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![React 19](https://img.shields.io/badge/React%2019-61DAFB?style=flat-square&logo=react&logoColor=black) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white) |

</div>

<details>
  <summary><strong>Deep-Dive: Comprehensive Technical Stack &amp; Tooling</strong></summary>
  <br />

  - **Languages:** Python (3.11+), SQL (advanced — window functions, MERGE, recursive CTEs), TypeScript, JavaScript, Bash, Java (basics).
  - **Data Architecture:** Medallion (Bronze/Silver/Gold) lakehouse design, star schemas, SCD Type 2 history, incremental fact loading, partitioning and clustering strategy, data contracts, idempotent DAG design, keyless S3↔Snowflake storage integrations, least-privilege role separation.
  - **Transformation &amp; Orchestration:** dbt (models, tests, macros, incremental strategies, exposures), Apache Airflow (DAGs, sensors, retries, backfills), Apache Spark / PySpark, Databricks notebooks and workflows, Delta Lake.
  - **AI / LLM Engineering:** RAG (hybrid dense + lexical retrieval, knowledge graphs), LangGraph state machines, typed tool-calling agents, QLoRA / LoRA fine-tuning, vLLM serving, prompt and eval harnesses, execution-accuracy benchmarking, LLM enrichment into warehouse columns, text-to-SQL, guardrails and human-in-the-loop gates.
  - **MLOps &amp; Observability:** MLflow tracking and registry, CI/CD quality gates on model accuracy, Docker containerization, drift and data-quality monitoring, structured tracing (LangSmith), pytest suites, strict typing (mypy) and linting (ruff).
  - **Cloud &amp; Infrastructure:** AWS (S3, IAM, Lambda, EC2), Snowflake, Vercel, PostgreSQL + pgvector, SQLite, GitHub Actions, Linux.
  - **Backend &amp; Frontend:** FastAPI, SQLAlchemy, JWT auth, REST APIs; React 19, Vite, Tailwind CSS, Monaco Editor.

  **Certifications &amp; continuous learning:** Databricks Fundamentals, Claude AI Fluency.
</details>

---

### Core Engineering Tenets

> *"A pipeline you can't re-run isn't a pipeline. An agent you can't measure isn't a system. Architecture is what keeps a system diagnosable when it fails."*

- **Architecture Before Code:** Sharp boundaries, typed contracts and least-privilege access beat clever one-off scripts — systems should be obvious to the next engineer at 3am.
- **Measure, Don't Assert:** Every AI claim belongs behind an automatic evaluation harness. If accuracy can't be reproduced on a held-out set, it isn't a result.
- **Idempotent &amp; Observable by Default:** Re-runnable pipelines, tested transformations, structured traces and honest failure modes — including saying *"unresolved"* rather than guessing.
- **Built for Failure, Not Just Success:** Incident response, human-in-the-loop approval gates and graceful degradation are designed up front, not bolted on after the first outage.

---

<div align="center">
  <p>
    <strong>Open to collaborating on data platforms, agentic AI systems and system-architecture-heavy engineering problems.</strong>
  </p>
  <a href="mailto:eshurajput007@gmail.com">
    <img src="https://img.shields.io/badge/Initiate%20Contact-Get%20in%20Touch-38BDF8?style=for-the-badge&logo=mailgun&logoColor=white" alt="Get in Touch" />
  </a>
  <a href="https://www.linkedin.com/in/irajput215">
    <img src="https://img.shields.io/badge/Connect%20on-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>

  <br/><br/>

  <a href="https://github.com/irajput215">
    <img src="https://komarev.com/ghpvc/?username=irajput215&label=PROFILE%20VIEWS&color=0284c7&style=flat-square" alt="Profile Views" />
  </a>
</div>
