## 👋 Hey there! I'm Ansh Saxena

🚀 **Software Engineer — Backend & AI Infrastructure** at [Cyware](https://cyware.com), building production **distributed systems** and **LLM/agentic platforms** in **Python**, **Go**, and **Java**.

I work at the seam between backend engineering and applied AI: multi-tenant services, event-driven pipelines, and **RAG** / **multi-agent** systems that actually run in production — not notebooks.

> "I don't just write code. I build systems that scale, heal, and evolve."

---

### 🧰 Tech Stack

**Languages**  
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Golang](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Java](https://img.shields.io/badge/-Java-007396?style=flat-square&logo=java&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-003B57?style=flat-square&logo=postgresql&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

**AI / ML Infrastructure**  
![LangGraph](https://img.shields.io/badge/-LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangChain](https://img.shields.io/badge/-LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![RAG](https://img.shields.io/badge/-RAG%20%26%20Vector%20Search-4B32C3?style=flat-square)
![Weaviate](https://img.shields.io/badge/-Weaviate-00C9A7?style=flat-square)
![DSPy](https://img.shields.io/badge/-DSPy-FF6F00?style=flat-square)
![Langfuse](https://img.shields.io/badge/-Langfuse%20%2F%20RAGAS-0A0A0A?style=flat-square)
![MCP](https://img.shields.io/badge/-MCP-000000?style=flat-square)
![OpenAI](https://img.shields.io/badge/-OpenAI%20API-412991?style=flat-square&logo=openai&logoColor=white)

**Backend & Distributed Systems**  
![Spring Boot](https://img.shields.io/badge/-Spring%20Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Microservices](https://img.shields.io/badge/-Microservices-FF6C37?style=flat-square)
![gRPC](https://img.shields.io/badge/-gRPC-244C5A?style=flat-square&logo=grpc&logoColor=white)
![Hibernate](https://img.shields.io/badge/-Hibernate-59666C?style=flat-square&logo=hibernate&logoColor=white)

**Data & Messaging**  
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Kafka](https://img.shields.io/badge/-Apache%20Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![NATS](https://img.shields.io/badge/-NATS%20JetStream-27AAE1?style=flat-square&logo=natsdotio&logoColor=white)
![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/-Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)

**Cloud & DevOps**  
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![Oracle Cloud](https://img.shields.io/badge/-Oracle%20Cloud-F80000?style=flat-square&logo=oracle&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/-Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/-OpenTelemetry-000000?style=flat-square&logo=opentelemetry&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

### 📬 Let’s Connect

[![Gmail](https://img.shields.io/badge/-anshs5103@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:anshs5103@gmail.com)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ansh-saxena-1c/)
[![LeetCode](https://img.shields.io/badge/-LeetCode-FFA116?style=flat-square&logo=leetcode&logoColor=white)](https://leetcode.com/u/AnshSaxena1/)
[![Medium](https://img.shields.io/badge/-Medium-000000?style=flat-square&logo=medium&logoColor=white)](https://medium.com/@anshs5103)
[![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/AnshSaxena05)

---

### 💼 Work Experience

**💻 Software Engineer — Backend & AI Infrastructure · [Cyware](https://cyware.com)**  
*Feb 2025 – Present · Bengaluru, India · (joined as an intern, converted to full-time)*

- Architected **Quarterback**, a production **LangGraph** multi-agent platform that cut analyst threat-triage time by **50%** across **45+ enterprise SOC deployments**, resolving alerts via natural language with tool integrations across VirusTotal, Splunk and CrowdStrike.
- Designed **AI Engine** (Python, **FastAPI**, ~13K LOC) — a multi-vendor **LLM orchestration** and serving layer routing inference across 4 providers behind one client abstraction, with per-tenant credential isolation, token cost accounting and JSON-schema-forced outputs.
- Raised tool-dispatch precision from **~60% → 89%** on a 200-case evaluation pipeline by replacing hardcoded routing with a multi-tenant **Weaviate RAG** layer using deterministic upsert IDs for idempotent re-ingest.
- Built **central-pir** in **Go** with **Hexagonal (Ports-and-Adapters)** architecture — two binaries from one image (HTTP API + worker), schema-per-tenant **PostgreSQL** isolation, and 8 durable **NATS JetStream** consumers.
- Sustained **100+ QPS at P95 sub-100ms** on a **Java** query-language compiler via query-plan rewrites, connection pooling and index-aware PostgreSQL execution; resolved 229 production bugs (29 critical) on L3 rotation.
- Instrumented end-to-end **LLM observability** with **OpenTelemetry**, **Langfuse** and **RAGAS**.

**🛠️ Software Engineering Intern — PreProd Corp**  
*Jan 2024 – Apr 2024*

- Engineered a production pricing-optimization platform generating **25% business impact** by integrating ML predictions into operational workflows.
- Designed **PostgreSQL** ETL pipelines processing **2GB+ daily data**; automated feature-engineering workflows, cutting data prep time by **80%**.
- Built backend components using **Java**, **Spring Boot** and **REST APIs**; designed data transformation workflows with **Apache Kafka**.

---

### 🔭 Featured Projects

| Project | What it is | Stack |
|---|---|---|
| [**SOC Triage Agent**](https://github.com/AnshSaxena05/cyberSecurity_alert_triage) | Agentic alert-triage service ingesting from 5 SIEM/EDR sources (Splunk, CrowdStrike, GuardDuty, Sentinel), normalising to **OCSF** and running a **LangGraph DAG** with MITRE ATT&CK-routed enrichment | Python · FastAPI · LangGraph · Pydantic · Redis · Langfuse · Ollama · Docker |
| [**Quiz Microservices**](https://github.com/AnshSaxena05/QuestionMicroservice_Service_new) · [(service 2)](https://github.com/AnshSaxena05/Quiz_Service_New) | Quiz platform decomposed into independently deployable **Spring Boot microservices** communicating over REST | Java · Spring Boot · REST · Microservices |
| [**Banking Microservices**](https://github.com/AnshSaxena05/Accounts-Microservice) · [Cards](https://github.com/AnshSaxena05/Cards-Microservice) · [Loans](https://github.com/AnshSaxena05/Loans-Microservice) | Accounts / Cards / Loans services built as a **Spring Boot microservices** suite | Java · Spring Boot · REST · Docker |
| [**Bloom Filter**](https://github.com/AnshSaxena05/Bloom-Filter) | From-scratch probabilistic set-membership data structure | Java |
| [**Quiz App (Monolith)**](https://github.com/AnshSaxena05/QuizApp_Monolithic_Springboot) | Monolithic Spring Boot quiz application — the baseline the microservices version was decomposed from | Java · Spring Boot · Spring Security |

---

### 🎓 Education & Certifications

**B.Tech, Artificial Intelligence & Machine Learning** — Vellore Institute of Technology (2021–2025), CGPA 8.71/10

- ✅ [Oracle Cloud Infrastructure 2024 Generative AI Certified Professional](https://drive.google.com/file/d/18GwnZnsDsbkQ0nG2nih5YTQT5bVQfgVz/view)  
- ✅ [AWS Certified Cloud Practitioner](https://drive.google.com/file/d/1ZSLzRdwwAhsOil-gFNgBkpwMt9y66GSO/view)  
- ✅ [Oracle Certified Java Developer (Java SE 11)](https://drive.google.com/file/d/1qKvUCauBMuDSepwwU7c_IhzL2zRF8aBw/view)  

---

### ✍️ Writing

- **[IoC → IoB: How AI Is Transforming Cybersecurity](https://medium.com/@anshs5103)** — technical essay on behavioural threat-intelligence architecture
- Contributor, **OCA IoB Working Group** — open event-schema standards for distributed AI platforms

---

### 💡 What I’m Currently Up To

- 🌱 Deepening **distributed systems** design, **Go** concurrency and **low-latency** optimisation
- 🤖 Building **agentic AI** systems — LangGraph DAGs, RAG pipelines, LLM evaluation harnesses
- ☁️ Shipping on **AWS (EKS)**, **Kubernetes**, **Terraform** and GitHub Actions CI/CD
- 👨‍💻 Contributing to open source + writing about backend and AI architecture

---

### 📈 GitHub Stats

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=AnshSaxena05&theme=radical" height="180" />
</p>

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=AnshSaxena05&theme=radical" />
</p>

---

### 🧠 Fun Fact

> "Backend isn't just about APIs – it's where the logic, architecture, and magic come alive"
