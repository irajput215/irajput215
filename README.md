<div align="center">

  <!-- Dynamic Animated Typing Banner -->
  <a href="https://github.com/irajput215">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=2600&pause=1000&color=38BDF8&center=true&vCenter=true&width=620&lines=Hi%2C%20I%27m%20Ishu%20Rajput%20%F0%9F%91%8B;Data%20%26%20AI%20Engineer;Systems%20Architecture%20Thinker;Building%20Agentic%20AI%20%26%20Data%20Platforms;Calm%20Under%20Pressure%20%E2%80%94%20Built%20for%20Production" alt="Typing SVG Banner" />
  </a>

  <p align="center">
    <strong>Data Platforms • Applied AI &amp; Agents • System Architecture • Reliability Under Pressure</strong>
  </p>

  <!-- Social & Profile Badges -->
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

### ⚡ Executive Summary &amp; Engineering Focus

> *Data &amp; AI Engineer who designs the architecture first — then ships it to production, and stays calm when it breaks at 2am.*

I build **end-to-end data and AI systems**: lakehouses and warehouses that are actually trustworthy, and LLM/agent layers that are actually evaluated. I care about the parts most demos skip — **idempotent pipelines, tested transformations, typed tools behind real boundaries, measured accuracy, and human-in-the-loop control** before anything touches production data.

- 🏗️ **Data Platforms &amp; Architecture:** Medallion lakehouse design (S3 → Snowflake → dbt → Airflow), dimensional &amp; SCD2 modelling, incremental/MERGE fact loading, keyless cloud storage integrations, and clear read/write boundary separation by role.
- 🧠 **Applied AI &amp; Agents:** LangGraph state machines, bounded tool-calling agents, hybrid RAG (pgvector + knowledge graph), QLoRA fine-tuning with execution-based eval harnesses, text-to-SQL, and LLM enrichment turned into queryable warehouse columns.
- 📈 **MLOps &amp; Reliability:** MLflow experiment tracking, CI/CD gates on model quality, containerized serving, live drift monitoring, structured tracing — built to be observed, not hoped for.
- 🧩 **Systems Thinking Under Pressure:** I decompose ambiguous, high-stakes problems into typed interfaces, deterministic checks and graceful failure modes — so incidents get diagnosed, not guessed at.

---

### 🚀 Featured Systems &amp; Architectural Showcases

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="left">🍽️ Zomato AI Data Platform</h3>
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
      <h3 align="left">🎓 CourseLLM</h3>
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
      <h3 align="left">🛠️ Pipeline Incident Response Agent</h3>
      <p><strong>Agentic Root-Cause Analysis for Failed Data Pipelines</strong></p>
      <p>Given a 2am alert that <code>customer_claims_daily</code> failed, a LangGraph state machine triages it across nine failure categories, then runs bounded rounds of investigation using <strong>nine typed diagnostic tools behind a real read-only SQL boundary</strong>. It commits to a root cause only when evidence supports one — otherwise it ends <code>UNRESOLVED</code> instead of guessing. Data-mutating fixes pause for human approval, and every node, tool call, token and millisecond is persisted.</p>
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
      <h3 align="left">🧪 Text-to-SQL Fine-Tuning (QLoRA)</h3>
      <p><strong>Llama 3.1 8B — Measured, Reproducible Gains</strong></p>
      <p>Fine-tuned <strong>Llama 3.1 8B</strong> on the Spider benchmark with QLoRA, and proved it worked using a fully automatic <strong>execution-based</strong> evaluation harness (no LLM-as-judge). Execution accuracy rose from <strong>67.89% → 73.89%</strong> on an identical 1,034-example held-out test set — with the largest wins on subqueries (+12.0) and set-operations (+12.5), plus a written error analysis.</p>
      <p>
        <a href="https://github.com/irajput215/fine-tuning-llms-text2sql" target="_blank"><img src="https://img.shields.io/badge/Repository-fine--tuning--llms--text2sql-181717?style=flat-square&logo=github" alt="Repo" /></a>
        <img src="https://img.shields.io/badge/%2B6.0%20pts%20exec%20accuracy-22C55E?style=flat-square" alt="Gain" />
      </p>
      <p>
        <img src="https://img.shields.io/badge/QLoRA-8B5CF6?style=flat-square" alt="QLoRA" />
        <img src="https://img.shields.io/badge/vLLM-FFD21E?style=flat-square" alt="vLLM" />
        <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="HF" />
        <img src="https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white" alt="MLflow" />
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="left">📊 MLOps Pipeline — News Classification</h3>
      <p><strong>Reproducible Experiments → Monitored Production Serving</strong></p>
      <p>Complete MLOps reference implementation: reproducible experiment tracking, automated CI/CD, containerized FastAPI serving, and <strong>live drift monitoring</strong> — the full path from raw data to a monitored endpoint, wired as one cohesive system.</p>
      <p>
        <a href="https://github.com/irajput215/news_classification_eval_and_monitoring" target="_blank"><img src="https://img.shields.io/badge/Repository-mlops%20pipeline-181717?style=flat-square&logo=github" alt="Repo" /></a>
      </p>
      <p>
        <img src="https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white" alt="MLflow" />
        <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
        <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="sklearn" />
        <img src="https://img.shields.io/badge/Drift%20Monitoring-EF4444?style=flat-square" alt="Drift" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3 align="left">🌐 Sharpie Web</h3>
      <p><strong>Browser-Based POSIX Shell → Python Transpiler</strong></p>
      <p>A full-stack transpiler that converts POSIX shell scripts into readable Python in the browser — debounced real-time output, syntax highlighting, interactive AST visualisation and downloadable results. Built on a custom shell parser, with JWT auth and PostgreSQL/SQLite persistence.</p>
      <p>
        <a href="https://github.com/irajput215/shell2py_deploy" target="_blank"><img src="https://img.shields.io/badge/Repository-shell2py__deploy-181717?style=flat-square&logo=github" alt="Repo" /></a>
        <a href="https://shell2py.vercel.app/" target="_blank"><img src="https://img.shields.io/badge/Live%20Demo-shell2py.vercel.app-000000?style=flat-square&logo=vercel" alt="Live" /></a>
      </p>
      <p>
        <img src="https://img.shields.io/badge/React%2019-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React" />
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TS" />
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
        <img src="https://img.shields.io/badge/Parser%20Design-8B5CF6?style=flat-square" alt="Parser" />
      </p>
    </td>
  </tr>
</table>

---

### 🎓 Academic &amp; Applied ML Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="left">🚦 GTSRB Traffic Sign Recognition</h3>
      <p>Deep learning for autonomous driving on the German Traffic Sign Recognition Benchmark — CNN architectures trained and evaluated for real-world noise, occlusion and class imbalance. <em>(COMP9444 Neural Networks &amp; Deep Learning, UNSW)</em></p>
      <p><a href="https://github.com/irajput215/GTSRB-Traffic-Sign-Recognition-Deep-Learning-Project-" target="_blank"><img src="https://img.shields.io/badge/Repository-GTSRB-181717?style=flat-square&logo=github" alt="Repo" /></a></p>
      <p>
        <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
        <img src="https://img.shields.io/badge/Computer%20Vision-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="CV" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3 align="left">🎯 Recommender System</h3>
      <p>Recommender systems coursework covering collaborative filtering, matrix factorisation and ranking evaluation — implemented and benchmarked from scratch. <em>(COMP9727, UNSW)</em></p>
      <p><a href="https://github.com/irajput215/COMP9727-Recommender_System" target="_blank"><img src="https://img.shields.io/badge/Repository-Recommender%20System-181717?style=flat-square&logo=github" alt="Repo" /></a></p>
      <p>
        <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" alt="Jupyter" />
        <img src="https://img.shields.io/badge/Ranking%20%26%20Eval-8B5CF6?style=flat-square" alt="Eval" />
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="left">🛰️ SkyView — Aerial Landscape Classification</h3>
      <p>CNN-based classification of aerial and satellite imagery into landscape classes, with transfer learning and augmentation across a large multi-class image set.</p>
      <p><a href="https://github.com/irajput215/SkyView-Aerial-Landscape-Classification" target="_blank"><img src="https://img.shields.io/badge/Repository-SkyView-181717?style=flat-square&logo=github" alt="Repo" /></a></p>
      <p>
        <img src="https://img.shields.io/badge/Transfer%20Learning-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="TL" />
        <img src="https://img.shields.io/badge/Remote%20Sensing-0284C7?style=flat-square" alt="Remote Sensing" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3 align="left">🗄️ Databricks &amp; Spark Engineering</h3>
      <p>End-to-end data + AI/ML pipelines on Databricks, plus Spark programming notebooks over Delta Lake — distributed transformation, feature engineering and model training at scale.</p>
      <p>
        <a href="https://github.com/irajput215/databricks-wanderbricks" target="_blank"><img src="https://img.shields.io/badge/Repository-wanderbricks-181717?style=flat-square&logo=github" alt="Repo" /></a>
        <a href="https://github.com/irajput215/Apache-Spark-Programming-with-Databricks" target="_blank"><img src="https://img.shields.io/badge/Repository-Spark%20%2B%20Databricks-181717?style=flat-square&logo=github" alt="Repo" /></a>
      </p>
      <p>
        <img src="https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white" alt="Databricks" />
        <img src="https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white" alt="Spark" />
        <img src="https://img.shields.io/badge/Delta%20Lake-00ADD4?style=flat-square" alt="Delta" />
      </p>
    </td>
  </tr>
</table>

---

### 🛠️ Technical Competencies &amp; Arsenal

<div align="center">

| Domain | Core Technologies &amp; Tooling |
| :--- | :--- |
| **Data Engineering &amp; Warehousing** | ![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white) ![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white) ![Apache Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white) ![Apache Spark](https://img.shields.io/badge/Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white) ![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white) ![Amazon S3](https://img.shields.io/badge/S3-569A31?style=flat-square&logo=amazons3&logoColor=white) ![Delta Lake](https://img.shields.io/badge/Delta%20Lake-00ADD4?style=flat-square) |
| **AI, LLM &amp; Agents** | ![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white) ![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-FFD21E?style=flat-square) ![vLLM](https://img.shields.io/badge/vLLM-FFD21E?style=flat-square) ![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) |
| **MLOps, Cloud &amp; Reliability** | ![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![LangSmith](https://img.shields.io/badge/LangSmith-FF6F61?style=flat-square) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white) |
| **Backend &amp; Interfaces** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat-square) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![React 19](https://img.shields.io/badge/React%2019-61DAFB?style=flat-square&logo=react&logoColor=black) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white) |

</div>

<details>
  <summary><strong>🔍 Deep-Dive: Comprehensive Technical Stack &amp; Tooling</strong></summary>
  <br />

  - **Languages:** Python (3.11+), SQL (advanced — window functions, MERGE, recursive CTEs), TypeScript, JavaScript, Bash, Java (basics).
  - **Data Architecture:** Medallion (Bronze/Silver/Gold) lakehouse design, star schemas, SCD Type 2 history, incremental fact loading, partitioning &amp; clustering strategy, data contracts, idempotent DAG design, keyless S3↔Snowflake storage integrations, least-privilege role separation.
  - **Transformation &amp; Orchestration:** dbt (models, tests, macros, incremental strategies, exposures), Apache Airflow (DAGs, sensors, retries, backfills), Apache Spark / PySpark, Databricks notebooks &amp; workflows, Delta Lake.
  - **AI / LLM Engineering:** RAG (hybrid dense + lexical retrieval, knowledge graphs), LangGraph state machines, typed tool-calling agents, QLoRA / LoRA fine-tuning, vLLM serving, prompt &amp; eval harnesses, execution-accuracy benchmarking, LLM-as-enrichment into warehouse columns, text-to-SQL, guardrails &amp; human-in-the-loop gates.
  - **MLOps &amp; Observability:** MLflow tracking &amp; registry, CI/CD quality gates on model accuracy, Docker containerization, drift &amp; data-quality monitoring, structured tracing (LangSmith), pytest suites, strict typing (mypy) and linting (ruff).
  - **Cloud &amp; Infrastructure:** AWS (S3, IAM, Lambda, EC2), Snowflake, Vercel, PostgreSQL + pgvector, SQLite, GitHub Actions, Linux.
  - **Backend &amp; Frontend:** FastAPI, SQLAlchemy, JWT auth, REST APIs; React 19, Vite, Tailwind CSS, Monaco Editor.

  **Certifications &amp; continuous learning:** AWS Certified Cloud Practitioner (CLF-C02) — notes &amp; practice exams; Generative AI for Beginners; AI Agents for Beginners; Mastering GitHub Copilot for Paired Programming; Packt *Data Engineering with AWS*; Udacity Data Engineering projects.
</details>

---

### 📊 GitHub Velocity &amp; Activity

<div align="center">
  <table border="0">
    <tr>
      <td align="center" valign="middle">
        <a href="https://github.com/irajput215">
          <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=irajput215&theme=tokyonight" alt="GitHub Stats" height="195" />
        </a>
      </td>
      <td align="center" valign="middle">
        <a href="https://github.com/irajput215">
          <img src="https://github-readme-streak-stats.herokuapp.com/?user=irajput215&theme=tokyonight&hide_border=true&background=0d1117&ring=38bdf8&fire=f59e0b&currStreakLabel=38bdf8" alt="GitHub Streak" height="195" />
        </a>
      </td>
    </tr>
    <tr>
      <td align="center" valign="middle">
        <a href="https://github.com/irajput215">
          <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=irajput215&theme=tokyonight" alt="Repos Per Language" height="195" />
        </a>
      </td>
      <td align="center" valign="middle">
        <a href="https://github.com/irajput215">
          <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=irajput215&theme=tokyonight" alt="Most Commit Language" height="195" />
        </a>
      </td>
    </tr>
  </table>

  <br />

  <a href="https://github.com/irajput215">
    <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=irajput215&theme=tokyonight" alt="Profile Details" width="100%" />
  </a>

  <br /><br />

  <!-- Prefer the classic side-by-side cards? Swap the two summary cards above for these
       (note: the shared public instance is rate-limited, add your own PAT_1 token deploy if it fails):
       https://github-readme-stats.vercel.app/api?username=irajput215&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=38bdf8&icon_color=a855f7&text_color=94a3b8
       https://github-readme-stats.vercel.app/api/top-langs/?username=irajput215&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=38bdf8&text_color=94a3b8&langs_count=8
  -->
</div>

---

### 💡 Core Engineering Tenets

> *"A pipeline you can't re-run isn't a pipeline. An agent you can't measure isn't a system. Architecture is what lets you stay calm when everything is on fire."*

- **Architecture Before Code:** Sharp boundaries, typed contracts and least-privilege access beat clever one-off scripts — systems should be obvious to the next engineer at 3am.
- **Measure, Don't Assert:** Every AI claim belongs behind an automatic evaluation harness. If accuracy can't be reproduced on a held-out set, it isn't a result.
- **Idempotent &amp; Observable by Default:** Re-runnable pipelines, tested transformations, structured traces and honest failure modes — including saying *"unresolved"* rather than guessing.
- **Pressure Is a Design Input:** Incident response, human-in-the-loop approval gates and graceful degradation are features, not edge cases.

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

  <br/><br/>

  <em>⭐ From <a href="https://github.com/irajput215">irajput215</a> — building data &amp; AI systems that hold up in production.</em>
</div>
