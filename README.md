# Hi, I'm Alfonso 👋

**Data engineer growing into a Data + AI Engineer.** I build production data
pipelines for enterprise analytics, and I'm working toward an **MS in Computer Science
and AI at Boston University** so I can own both the data platform *and* the models it
feeds.

📍 Lenexa, Kansas · 📄 [Resume](https://github.com/ajesqueda/professional-portfolio/blob/main/resume/README.md)

---

## 🧭 Background

- **Data analytics roots.** I started out doing exploratory analysis and data
  visualization in Python and SQL.
- **Data engineering today.** I design and maintain production pipelines with Python,
  SQL, Apache Spark, Databricks, Snowflake and dbt, organized as bronze → silver →
  gold (medallion) layers. My work has also grown into backend development and
  container-based platforms.
- **Graduate school now.** I'm in BU's MS in Computer Science and AI, studying
  computer systems and the mathematical foundations of machine learning alongside a
  full-time job.

## 🔭 Current technical interests

- **Where data engineering meets ML.** Most production ML breaks because of the data
  underneath it, not the model.
- **How models actually work.** The probability, optimization and linear algebra
  behind them, rather than treating libraries as black boxes.
- **How computers work under the hood.** CPUs, memory, operating systems, storage and
  networking, and how they shape the performance of the data systems I build.
- **LLMs and applied AI.** Retrieval, evaluation, and turning a model into something
  people can use.

## 🛠️ What I'm developing

| Area | Comfortable with | Currently building up |
|------|------------------|-----------------------|
| Languages | Python, SQL | C, Java |
| Data platforms | Spark, Databricks, Snowflake, dbt | Orchestration (Airflow), streaming and real-time features |
| ML / AI | Exploratory analysis, visualization | ML math from scratch, model building and deployment, LLM applications |
| Computer science | Backend development, containers | Operating systems, memory, concurrency, networking, the JVM |
| Engineering practice | Git, production pipelines | Testing, CI/CD, typed Python |

## 🧩 Problems and projects that interest me

- **Production-grade ML systems.** Reliable feature pipelines, reproducible training
  data, and monitoring that catches data drift before it quietly degrades a model.
- **Correctness under failure.** Pipelines that stay correct when a job crashes
  halfway, such as atomic writes and idempotent loads.
- **Personal data with an AI layer.** A project I want to build is a medallion pipeline
  over my own Garmin health data (sleep, HRV, stress, training) with a model on top
  that predicts recovery and flags unusual patterns.
- **Understanding by rebuilding.** Implementing an algorithm from scratch and testing it
  against the library version until I can explain why it works.

## 🎯 Current goals

- **Professional:** grow into a **Data + AI Engineer** role. Data engineering stays my
  foundation, and I add the ability to build, deploy and own models on top of it, end
  to end from ingestion to inference.
- **Academic:** finish the MS with a solid grasp of ML theory, deep learning and
  systems, the CS foundations I didn't get by coming up through tools.
- **Learning in public:** turn what I study each week into small, tested code here,
  with honest commit history and no filler.

## 📂 Where to look

| Repo | What's inside |
|------|---------------|
| [garmin-health-lakehouse](https://github.com/ajesqueda/garmin-health-lakehouse) | **Featured project:** a bronze → silver → gold Databricks lakehouse over my Garmin health data, running daily, with a gold feature table for a future recovery-score model |
| [ml-from-scratch](https://github.com/ajesqueda/ml-from-scratch) | ML math implemented from scratch and tested: MLE → least squares, vector similarity, Gaussian elimination |
| [data-engineering-lab](https://github.com/ajesqueda/data-engineering-lab) | Data engineering concepts as runnable projects, starting with crash-safe file writes |
| [ai-concepts-lab](https://github.com/ajesqueda/ai-concepts-lab) | Computer systems and AI concept demos, such as a toy CPU running the fetch-decode-execute cycle |
| [til](https://github.com/ajesqueda/til) | Today I Learned: short notes with code, such as Java for Python developers |
| [professional-portfolio](https://github.com/ajesqueda/professional-portfolio) | My [resume](https://github.com/ajesqueda/professional-portfolio/blob/main/resume/README.md) and a portfolio landing page |

Every change in these repos goes through a feature branch and pull request with
lint and tests in CI, then is promoted `dev` → `qa` → `main`.
