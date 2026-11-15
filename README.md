# Senior AI Engineer – Data Scientist, PhD

## About Me
Senior AI Engineer and Data Scientist with **8 years of experience** across **Machine Learning**, **Software Engineering** and **Research**.\
I've built this skill set in academia, corporate engineering and AI start-ups, and today I work at **Dynatrace R&D** building GenAI products for observability.

Currently working on **agentic AI evaluation** and **LLM-powered Real User Monitoring** at Dynatrace. My work account is [@yassine-dt](https://github.com/yassine-dt).

### Let's connect
Reach me on [LinkedIn](https://www.linkedin.com/in/yassine-bouabdallaoui/).
You can also find my publications on [Google Scholar](https://scholar.google.com/citations?user=pUIF8ZwAAAAJ&hl=en) or read my latest thoughts on [Medium](https://medium.com/@bouabdallaoui.yassine).

I'm always open to interesting conversations, collaborations or work opportunities, so feel free to get in touch!

---
## Professional Experience

- **Senior AI Engineer – Data Scientist**  
  Dynatrace R&D *(Jan 2026 – present, Linz, Austria)*
  - Built and maintain [**dt-evals**](https://github.com/dynatrace-oss/dt-evals), Dynatrace's open-source agentic evaluation framework, used by hundreds of Dynatrace customers to evaluate their AI workloads in Dynatrace AI Observability
  - Built **AI Session Summaries** for Real User Monitoring on top of Dynatrace Assistant, a scalable LLM pipeline (GA June 2026)
  - Designed a hybrid **ML + deterministic + LLM** algorithm that generates synthetic monitors from real-user journeys

- **Founding AI/ML Engineer**  
  Autoplay AI *(Mar 2025 – Dec 2025, Paris, France)*
  - Built a production-grade LLM pipeline that analyzes session replay data and gives product managers deep analytics and actionable insights

- **ML Engineer**  
  LooksGoodAI *(Mar 2022 – Nov 2024, Paris, France)*
  - Led the Data Science team building an AI slide-automation tool for **30K+ users**, using ML, graph theory and Generative AI
  - Contributed to the slide-formatting system covered by [patent WO2023004509A1](https://patents.google.com/patent/WO2023004509A1/en)

- **Data Scientist & PhD Researcher**  
  Bouygues Construction *(2018 – 2021, Lille, France)*
  - Led AI research in **Facility Management**, focusing on **predictive maintenance**

---
## Education
- **PhD in Machine Learning**  
  Ecole Centrale de Lille *(2018 – 2021, Lille, France)*

- **MSc in Engineering (Double Degree)**  
  Ecole Centrale de Lille & Ecole Hassania des Travaux Publics *(2015 – 2018, Lille & Casablanca)*

---
## Projects

### **dt-evals: Agentic Evaluation Framework for AI Observability (2026)**
I built and maintain Dynatrace's open-source evaluation toolkit for LLM apps and agents, **used by hundreds of Dynatrace customers** to evaluate their AI workloads in Dynatrace AI Observability (50+ GitHub stars, 30K+ npm downloads). It pulls live `gen_ai.*` OpenTelemetry spans from Dynatrace, masks sensitive data in memory, scores production interactions with an **LLM-as-judge**, and writes the results back as business events, so evals, traces, alerts and dashboards all live in one place. It ships as a CLI, a TypeScript library, deployment runners and a Python ingest library.

[Repo](https://github.com/dynatrace-oss/dt-evals) · [npm](https://www.npmjs.com/package/@dynatrace-oss/dt-evals)

**Key Technologies:** TypeScript, Node.js, LLM-as-judge, OpenTelemetry, Dynatrace, OpenAI / Anthropic / Gemini / Bedrock

---
### **SRE Multi-Agent for Dynatrace (2025)**
An LLM orchestrator that delegates incident investigations to specialist agents (problem finder, vulnerability scanner, root cause analyst, mitigation planner). Each agent queries Dynatrace through the MCP server and returns structured outputs that the orchestrator combines into one action plan.

[Repo](https://github.com/yassine-bouabda/sre-multi-agent-dynatrace)

**Key Technologies:** Pydantic AI, MCP, Multi-agent orchestration, OpenAI / Anthropic, Dynatrace

---
### **Document Engineering: Automatic PowerPoint Slide Enhancement (2022–2024)**
I led the Data Science team building an AI system that automates and optimizes PowerPoint slide creation, boosting productivity for 30K+ consultants.

**Key Technologies:** LLMs, ML, Graph Theory, Python, AWS

---
### **Predictive Maintenance Framework for Facilities (2021): 200+ Citations**
I developed an **LSTM-autoencoder** framework that predicts maintenance needs in building facilities, reducing downtime and improving system efficiency.

[Publication](https://www.mdpi.com/1424-8220/21/4/1044)

**Key Technologies:** Python, TensorFlow, Keras, Autoencoders

---
### **Automation of Maintenance Requests Using Text Classification (2019): 50+ Citations**
I built a framework that automates maintenance requests in complex facilities with a **custom text classifier** and automatic work-order assignment. It cut processing time by **30%**.

[Publication](https://www.mdpi.com/2075-5309/10/9/160)

**Key Technologies:** NLP, Scikit-learn, Python, Text Analytics

---
### **RAG Project: Chat with arXiv Papers Locally (2024)**
A simple RAG system to chat with arXiv papers locally, with no API costs, built to experiment with the LangChain framework.

[Repo](https://github.com/yassine-bouabda/local-rag-assistant)

**Key Technologies:** LangChain, Ollama, Streamlit
