<div align="center">

![Faraz Mubeen Haider | Software Engineer](https://capsule-render.vercel.app/api?type=waving&color=0:0B1220,50:1E3A5F,100:4F8CFF&height=190&section=header&text=Faraz%20Mubeen%20Haider&fontColor=F1F5F9&fontSize=42&fontAlignY=38&desc=Backend%20Engineering%20%7C%20Data%20Systems%20%7C%20Applied%20AI&descSize=15&descAlignY=60)

### Software Engineer | Python Backend · Data Systems · Applied AI

Building backend applications, data workflows, and AI-enabled software with an emphasis on maintainability, correctness, and reliable behavior.

[![GitHub](https://img.shields.io/badge/GitHub-Projects-1E3A5F?style=flat-square&logo=github&logoColor=white)](https://github.com/Faraz6180)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-1E3A5F?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/farazmubeenhaider/)
[![Hugging Face](https://img.shields.io/badge/Hugging_Face-Projects-1E3A5F?style=flat-square&logo=huggingface&logoColor=white)](https://huggingface.co/Faraz618)
[![LabLab](https://img.shields.io/badge/LabLab-Hackathons-1E3A5F?style=flat-square)](https://lablab.ai/u/@Faraz_Mubeen)

</div>

---

## About Me

I'm a Software Engineer focused on building Python-based backend applications, database-backed systems, data workflows, and AI-enabled products.

My work combines software engineering fundamentals with hands-on experience integrating APIs, processing data, and building applications powered by large language models (LLMs).

I'm particularly interested in what happens beyond the happy path: how systems handle invalid inputs, missing data, dependency failures, and uncertain outputs—and how those behaviors can be tested, understood, and improved.

**My core focus:**
- **Backend engineering:** Python, FastAPI, REST APIs, application design, and service integration.
- **Data systems:** SQL, PostgreSQL, data processing, and ETL workflows.
- **Distributed systems and cloud infrastructure:** developing deeper skills in service boundaries, deployment, failure handling, and operational concerns.
- **Applied AI:** LLM integrations, retrieval-augmented generation (RAG), document processing, and AI workflows.
- **Engineering quality:** testing, reproducibility, documentation, and maintainability.

I use my projects to explore technical decisions and demonstrate implementations. I aim to distinguish clearly between what has been implemented, what has been tested, and what remains to be validated.

📍 **Location:** Pakistan  
🌍 **Interests:** Backend Engineering · Python · Data Systems · Applied AI · Cloud Infrastructure

---

## Featured Projects

### 1. ComplianceRAG — Document Retrieval & Answer Verification

A retrieval-augmented generation (RAG) application exploring how generated answers can be checked against retrieved source material.

[**Repository**](https://github.com/Faraz6180/ComplianceRAG) · [**Live Demo**](https://huggingface.co/spaces/Faraz618/ComplianceRAG)

**Problem**

LLM-powered applications can generate fluent answers that are not adequately supported by their source documents. Retrieval quality, citations, and unsupported claims all affect the usefulness of the final response.

**Implementation**
- Retrieve document passages using FAISS and sentence embeddings.
- Generate answers from retrieved context using a language model.
- Include source citations in generated responses.
- Apply a critic step intended to examine sentence-level support and citation validity.
- Explore how missing evidence and uncertain answers should be handled.

**Technologies:** Python · FAISS · sentence-transformers · Hugging Face Inference API · PyPDF · Gradio

**Engineering questions**
- How does retrieval quality affect generated answers?
- Can claims be traced to relevant source passages?
- What should happen when the source documents lack sufficient evidence?
- How should unsupported or uncertain outputs be handled?

> A critic or groundedness score does not guarantee factual correctness. Reliability depends on the implementation and evaluation of the checking process.

---

### 2. AdvancedLeadsGeneration-AI — IBM Granite Hackathon Winner

A team project exploring multi-agent lead qualification and reconciliation of different assessments.

[**Repository**](https://github.com/Faraz6180/AdvancedLeadsGeneration-AI) · [**Hackathon Recognition**](https://lablab.ai/ai-hackathons/generative-ai-hackathon-with-ibm-granite/polyens)

**Problem**

Lead qualification can involve competing considerations, incomplete information, and uncertainty. Different assessment steps can help make these considerations more explicit.

**Approach**
- Divide lead assessment across multiple workflow components.
- Coordinate intermediate outputs.
- Reconcile different assessments into a combined result.
- Explore how the workflow could be evaluated against representative scenarios.

**Technologies:** Next.js · FastAPI · IBM Watson AI · IBM Granite

🏆 **Recognition:** Team PolyEns won the Generative AI Hackathon with IBM Granite.

This project reflects my experience building AI-enabled application workflows and collaborating on a time-constrained engineering project.

---

### 3. HireMind-AI — AI-Assisted Career Workflow

An LLM-powered application for resume analysis and job-application tasks.

[**Repository**](https://github.com/Faraz6180/HireMind-AI) · [**Live Demo**](https://huggingface.co/spaces/Faraz618/HireMind-AI)

**Features**
- Resume and job-description analysis.
- Keyword comparison and skill-gap identification.
- Resume improvement suggestions.
- Cover-letter generation.
- Interview preparation.
- Application tracking.
- Career-related chat.

**Technologies:** Python · Streamlit · Groq API · LLaMA models · JSON persistence · Hugging Face Spaces

**Engineering focus:** Application flow, model integration, input handling, persistence, and the limitations of automated assessments.

> ATS-style scores are estimates, not guarantees of how an employer's recruitment system will evaluate a candidate.

---

### 4. SafeLite — Research-Oriented AI System

A modular project exploring planning, safety-related checks, execution, simulation, and evaluation.

[**Explore Repository**](https://github.com/Faraz6180/SafeLite)

The project investigates how planning, execution, and checking components can be separated for inspection.

Areas of interest include:
- Separation of planning and execution.
- Explicit checks and decision boundaries.
- Simulation and controlled evaluation.
- Testing component behavior and failure cases.

Any claims about safety guarantees should be assessed against the actual implementation and supporting evidence.

---

## Technical Toolkit

| Area | Technologies |
|---|---|
| Languages | Python, SQL, TypeScript |
| Backend | FastAPI, REST APIs |
| Databases & Data | PostgreSQL, Pandas, SQLAlchemy, ETL workflows |
| AI Integrations | LLM APIs, IBM Granite, IBM Watson AI, Hugging Face Inference API |
| Retrieval | FAISS, sentence-transformers, LangChain, PyPDF |
| AI Workflows | Multi-agent coordination, critic and verification patterns |
| Interfaces | Next.js, Streamlit, Gradio |
| Prototyping & Demos | Hugging Face Spaces, Streamlit Cloud |

This list reflects technologies used across my projects. It does not imply equal depth in every tool or production-scale experience with every technology.

---

## How I Approach Engineering

**1. Design for failure**

Invalid input, missing data, unavailable dependencies, and uncertain model outputs deserve deliberate consideration.

**2. Make behavior inspectable**

Readable code, clear interfaces, and useful documentation help other engineers understand and maintain a system.

**3. Test beyond the happy path**

A successful demonstration does not establish correctness across different inputs and failure conditions.

**4. Explain technical trade-offs**

Architecture and tooling decisions should be justified by requirements, constraints, and observed behavior.

**5. Separate implementation from evidence**

A feature existing in code is different from a feature being tested, measured, or independently verified.

**6. Document limitations honestly**

Clear limitations help reviewers understand what a system can do, what it cannot yet do, and what should be improved.

---

## Recognition & Community

- **IBM Granite Generative AI Hackathon — Winner:** Team PolyEns.
- **Stanford Code in Place — Section Leader:** Supporting learners in an introductory Python programming program.
- **AlgoVerse Research Program:** Accepted with a reported 45% merit scholarship.
- **Founder Institute Pakistan:** Cohort participation.

[Explore my LabLab profile and project submissions](https://lablab.ai/u/@Faraz_Mubeen)

---

## Additional Hackathon Projects

My hackathon experience has provided opportunities to build prototypes, collaborate with teammates, and explore different software and AI application patterns.

| Project / Event | Project |
|---|---|
| Fall in Love with DeepSeek | DevAI |
| Replit & Cursor Hackathon | Byte Busters |
| Agentic AI with IBM watsonx Orchestrate | AI SOC Security Analyst |
| Co-Creating with GPT-5 | Agentica |
| RAISE YOUR HACK | HealthBridge |
| AI for Connectivity Hackathon II | KONEKTA |
| AIstronauts: Space Agents | ARCANA Space Agent |
| Qubic Hack the Future | AdmitWise |

[**Explore my LabLab profile for project and event details →**](https://lablab.ai/u/@Faraz_Mubeen)

---

## What I'm Working Toward

I'm continuing to develop my engineering capability across:

- Python backend architecture and API design.
- Database-backed applications and reliable data workflows.
- Service integration, failure handling, and system design.
- Testing, debugging, and maintainable software.
- Deployment, cloud infrastructure, and operational visibility.
- Reliable AI integrations and evaluation.

My goal is to build software that another engineer can run, inspect, understand, and improve—not just applications that look convincing in a demo.

---

## Connect With Me

I'm open to conversations about backend engineering, Python, data systems, applied AI, open-source collaboration, and suitable software engineering opportunities.

- **Email:** [faraz.outreach8@gmail.com](mailto:faraz.outreach8@gmail.com)
- **LinkedIn:** [Faraz Mubeen Haider](https://www.linkedin.com/in/farazmubeenhaider/)
- **GitHub:** [Faraz6180](https://github.com/Faraz6180)
- **Hugging Face:** [Faraz618](https://huggingface.co/Faraz618)
- **LabLab:** [Projects and hackathons](https://lablab.ai/u/@Faraz_Mubeen)
- **Medium:** [Technical writing](https://medium.com/@farazmubeenhaider902)

<div align="center">

---

*Build carefully. Verify honestly. Document what matters.*

</div>
