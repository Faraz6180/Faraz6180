
<div align="center">

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:101827,50:1e3a5f,100:2563eb&height=190&section=header&text=Faraz%20Mubeen%20Haider&fontColor=ffffff&fontSize=42&fontAlignY=38&desc=Software%20Engineering%20%7C%20Backend%20%7C%20Data%20Systems%20%7C%20Applied%20AI&descSize=15&descAlignY=60)

# Applied AI Engineer

### I build LLM systems, ship them to production, and make sure they don't hallucinate.

I care about what happens beyond the happy path: correctness, failure handling, reproducibility, and maintainable software.

[![Live Demos](https://img.shields.io/badge/🤗_Live_Demos-8_deployed-yellow?style=for-the-badge)](https://huggingface.co/Faraz618)
[![IBM Granite Winner](https://img.shields.io/badge/🏆_IBM_Granite_Hackathon-Winner-blue?style=for-the-badge)](https://lablab.ai/ai-hackathons/generative-ai-hackathon-with-ibm-granite/polyens)
[![Stanford Code in Place](https://img.shields.io/badge/Stanford_Code_in_Place-Section_Leader-red?style=for-the-badge&logo=stanford)](https://codeinplace.stanford.edu/)

[![GitHub](https://img.shields.io/badge/GitHub-Projects-181717?style=flat-square&logo=github)](https://github.com/Faraz6180)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/farazmubeenhaider/)
[![Hugging Face](https://img.shields.io/badge/Hugging_Face-Applications-FFD21E?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/Faraz618)
[![LabLab](https://img.shields.io/badge/LabLab-Projects-6C47FF?style=flat-square)](https://lablab.ai/u/@Faraz_Mubeen)

</div>

---

## 👋 About Me

I'm a Software Engineer with a background in backend development, data processing, and applied AI. I build Python-based applications that connect APIs, data workflows, and language-model capabilities into usable software.

My main engineering interests are:

- **Backend engineering:** API design, application structure, validation, error handling, and maintainability.
- **Data systems:** Data ingestion, transformation, SQL, database-backed applications, and data integrity.
- **Reliable AI applications:** Retrieval-augmented generation (RAG), document intelligence, LLM integrations, and evaluation.
- **Software quality:** Reproducible setup, meaningful tests, clear documentation, and honest reporting of limitations.

My experience includes AI-enabled product development, data-processing workflows, and independent engineering projects. I use my repositories to demonstrate implementations and technical decisions—not just list technologies.

I'm particularly interested in backend, Python, data engineering, and AI systems opportunities where I can contribute to real engineering work and continue growing as a software engineer.

**Location:** Pakistan · Open to suitable remote and international opportunities.

---

## 🧭 Engineering Focus

| Area | What I Work On |
|---|---|
| Backend development | Python, FastAPI, REST APIs, request validation, service integration |
| Data processing | SQL, PostgreSQL, Pandas, SQLAlchemy, ETL workflows |
| Applied AI | LLM integrations, RAG pipelines, document processing, AI-assisted workflows |
| Retrieval and search | FAISS, sentence-transformers, document chunking and retrieval |
| Agentic workflows | Multi-agent coordination, specialist agents, critic and verification patterns |
| Application delivery | Docker and deployment workflows where applicable, Streamlit, Gradio, Hugging Face Spaces |

These areas reflect my work and interests; the depth of implementation and validation varies by project.

---

## 🚀 Featured Projects
### 3. HireMind-AI — AI-Assisted Career Workflow

**An LLM-powered application for resume analysis and job-application tasks.**

[![Repository](https://img.shields.io/badge/Repository-181717?style=flat-square\&logo=github)](https://github.com/Faraz6180/HireMind-AI)
[![Live Demo](https://img.shields.io/badge/Live%20Demo-FFD21E?style=flat-square\&logo=huggingface\&logoColor=black)](https://huggingface.co/spaces/Faraz618/HireMind-AI)

**Problem**

Job seekers often need to compare a resume with several job descriptions, identify gaps, and prepare application materials without a structured workflow.

**Features**

The application brings together career-related tasks such as:

### 🧪 [ComplianceRAG](https://github.com/Faraz6180/ComplianceRAG) — RAG with a Groundedness Critic
> Most RAG demos hide when retrieval fails. This one **measures** it.
* Resume and job-description analysis.
* ATS-oriented scoring and keyword comparison.
* Skill-gap identification.
* Resume improvement suggestions.
* Cover-letter generation.
* Interview preparation.
* Application tracking.
* Career-related chat.

**The problem:** RAG systems produce fluent answers that quietly drift from source material. In compliance, that's a lawsuit.
**Technologies:** Python · Streamlit · Groq API · LLaMA models · JSON persistence · Hugging Face Spaces

**The system:** Three-agent pipeline — **Retrieval Agent** (FAISS + `all-MiniLM-L6-v2`) → **Generation Agent** (HF Inference API, cited answers `[1][2]`) → **Critic Agent** (independent sentence-level groundedness scoring + citation validation). Low-confidence answers are auto-flagged for human review.
**Engineering focus**

**Stack:** `Gradio` · `sentence-transformers` · `FAISS` · `Hugging Face Inference API` · `PyPDF`
**Why it matters:** Shows the orchestrator / specialist / critic pattern used in production multi-agent systems — not just retrieve-and-generate.
The project provides an opportunity to examine application flow, model integration, input handling, persistence, and the limitations of heuristic or LLM-generated assessments.

🔗 [Live Demo](https://huggingface.co/spaces/Faraz618/ComplianceRAG) · [Code](https://github.com/Faraz6180/ComplianceRAG)
ATS-style scores should be treated as estimates, not as predictions of how every employer's recruitment system will evaluate a candidate.

---

### 🏆 [AdvancedLeadsGeneration-AI](https://github.com/Faraz6180/AdvancedLeadsGeneration-AI) — IBM Granite Hackathon **Winner**
> Two AI agents argue about your leads. The one that wins is the one grounded in your historical deals.
### 4. SafeLite — Research-Oriented AI System

**The problem:** CRM lead-scoring uses static rules and ignores negotiation nuance.
**A modular project exploring planning, safety reasoning, execution, simulation, and evaluation.**

**The system:** Multi-agent debate architecture — one agent advocates for the lead, another surfaces risks. A reconciliation layer scores against historical deal data. Integrated with IBM Watson AI on IBM Granite models.
[![Repository](https://img.shields.io/badge/Explore%20Code-181717?style=flat-square\&logo=github)](https://github.com/Faraz6180/SafeLite)

**Stack:** `Next.js` · `FastAPI` · `IBM Watson AI` · `IBM Granite`
**Why it matters:** Ships against a judged bar under time pressure. Team **PolyEns won** the Generative AI Hackathon with IBM Granite.
SafeLite explores how components of an AI system can be separated so that planning, safety-related checks, execution, and evaluation can be examined independently.

🔗 [Hackathon Page & Demo](https://lablab.ai/ai-hackathons/generative-ai-hackathon-with-ibm-granite/polyens)
The repository is best understood through its actual implementation, tests, and documented research status.

**Areas of interest**

* Separation of planning and execution.
* Explicit safety checks and decision boundaries.
* Simulation and controlled evaluation.
* Testing component behavior and failure cases.

The project should not be interpreted as demonstrating formal safety guarantees unless those guarantees are established by the implementation and supporting evidence.

---

### 🎯 [HireMind-AI](https://github.com/Faraz6180/HireMind-AI) — LLM-Powered Hiring Copilot
> Multi-feature product, not a single-endpoint demo.
## Selected Engineering Experience

### Data Processing and Reporting

My data-engineering work has involved Python-based data processing, including Pandas, SQLAlchemy, and PostgreSQL.

The engineering problems in this area include:

* Transforming data into consistent, usable structures.
* Working with relational databases and reporting workflows.
* Reducing repetitive manual processing.
* Making outputs easier to inspect and maintain.

The most meaningful evidence for this work is the underlying implementation, the data transformations, and a clear explanation of the workflow and its measured impact where that impact can be substantiated.

**The problem:** Candidates optimize resumes blind — no visibility into ATS logic or multi-role comparison.
### AI-Enabled Product Development

**The system:** 8 integrated surfaces — multi-JD analysis, ATS scoring engine (skills % + keyword % + experience alignment), skill-gap detection, resume optimizer, cover-letter generator, interview prep, application tracker, career chat.
My product-development experience includes building AI-enabled application workflows and integrating language-model capabilities into software.

**Stack:** `Streamlit` · `Groq API (LLaMA 3.1)` · `JSON persistence` · `Hugging Face Spaces`
**Why it matters:** Demonstrates end-to-end product scoping — not "here's a chatbot," but "here's a career workflow."
Areas of work include document ingestion, API integration, structured outputs, and coordinating model-driven steps inside an application.

🔗 [Live Demo](https://huggingface.co/spaces/Faraz618/HireMind-AI) · [Code](https://github.com/Faraz6180/HireMind-AI)
I aim to document the boundary between what a system implements, what has been tested, and what remains an improvement opportunity.

---

## 🧠 Engineering Philosophy
## Selected Recognition and Community

- **Ship fast, evaluate honestly.** Every RAG I build gets a groundedness check. Every agent gets a critic.
- **Retrieval quality > prompt cleverness.** Most "prompt engineering" problems are actually retrieval problems.
- **Live demo or it didn't happen.** 8 of my projects have public Hugging Face Spaces you can break right now.
- **I only list what I've built.** If a stack is on this page, there's a repo behind it.
* **IBM Granite Generative AI Hackathon — Winner:** Team PolyEns, AdvancedLeadsGeneration-AI.
* **Stanford Code in Place — Section Leader:** Teaching and supporting learners in an introductory Python programming program.
* **AlgoVerse Research Program:** Accepted with a reported 45% merit scholarship.
* **Founder Institute Pakistan:** Cohort participation.

For project-specific details and hackathon participation, see my [LabLab profile](https://lablab.ai/u/@Faraz_Mubeen).

---

## 🏅 Hackathon Track Record
## Hackathon Projects

Hackathons have given me opportunities to build prototypes, work with unfamiliar technologies, and explore different AI application patterns.

| Event | Project | Result |
|---|---|---|
| **Generative AI Hackathon with IBM Granite** | AdvancedLeadsGeneration-AI | 🏆 **Winner** |
| Fall in Love with DeepSeek | DevAI | 🥉 Finalist |
| Replit & Cursor Hackathon | Byte Busters | 🥉 Finalist |
| Agentic AI with IBM watsonx Orchestrate | AI SOC Security Analyst | Participant |
| Co-Creating with GPT-5 | Agentica (multi-agent orchestration) | Participant |
| RAISE YOUR HACK | HealthBridge | Participant |
| AI for Connectivity Hackathon II | KONEKTA | Participant |
| AIstronauts: Space Agents | ARCANA Space Agent | Participant |
| Qubic Hack the Future | AdmitWise | Participant |
| Project or Event                         | Focus                          | Reference                                                                                   |
| ---------------------------------------- | ------------------------------ | ------------------------------------------------------------------------------------------- |
| Generative AI Hackathon with IBM Granite | AI-assisted lead qualification | [Project](https://lablab.ai/ai-hackathons/generative-ai-hackathon-with-ibm-granite/polyens) |
| Fall in Love with DeepSeek               | DevAI                          | [LabLab profile](https://lablab.ai/u/@Faraz_Mubeen)                                         |
| Replit & Cursor Hackathon                | Byte Busters                   | [LabLab profile](https://lablab.ai/u/@Faraz_Mubeen)                                         |
| Agentic AI with IBM watsonx Orchestrate  | AI SOC Security Analyst        | [LabLab profile](https://lablab.ai/u/@Faraz_Mubeen)                                         |
| Co-Creating with GPT-5                   | Agentica                       | [LabLab profile](https://lablab.ai/u/@Faraz_Mubeen)                                         |
| RAISE YOUR HACK                          | HealthBridge                   | [LabLab profile](https://lablab.ai/u/@Faraz_Mubeen)                                         |
| AI for Connectivity Hackathon II         | KONEKTA                        | [LabLab profile](https://lablab.ai/u/@Faraz_Mubeen)                                         |
| AIstronauts: Space Agents                | ARCANA Space Agent             | [LabLab profile](https://lablab.ai/u/@Faraz_Mubeen)                                         |
| Qubic Hack the Future                    | AdmitWise                      | [LabLab profile](https://lablab.ai/u/@Faraz_Mubeen)                                         |

**Full profile:** [lablab.ai/u/@Faraz_Mubeen](https://lablab.ai/u/@Faraz_Mubeen) — 15 events, 11 submissions.
[Explore my LabLab profile and submissions →](https://lablab.ai/u/@Faraz_Mubeen)

---

## 🎓 Teaching & Recognition
## Technology Stack

I prefer to describe my stack in terms of the work it supports rather than present a long list of tools as a measure of expertise.

| Category             | Technologies                                                                               |
| -------------------- | ------------------------------------------------------------------------------------------ |
| Languages            | Python, SQL, TypeScript                                                                    |
| Backend              | FastAPI, REST APIs                                                                         |
| Databases and data   | PostgreSQL, Pandas, SQLAlchemy                                                             |
| LLM integrations     | Groq API, LLaMA models, IBM Granite, IBM Watson AI, Hugging Face Inference API, OpenAI API |
| Retrieval            | FAISS, sentence-transformers, LangChain, PyPDF                                             |
| AI workflows         | Multi-agent workflows, critic and verification patterns                                    |
| Interfaces           | Streamlit, Gradio, Next.js                                                                 |
| Demos and deployment | Hugging Face Spaces, Streamlit Cloud                                                       |

- **Stanford University — Code in Place** · Section Leader (2025). Selected as 1 of 100 from 900+ global applicants. Led weekly live Python sessions for a global beginner cohort.
- **AlgoVerse Research Program (EOE.ai × Omdena)** · Accepted with 45% merit scholarship. Contributed to RAG / LangChain / Hugging Face research prototypes.
- **Founder Institute Pakistan** · Cohort 2025 (health-informatics track, KnullAI).
The presence of a technology in this list does not imply equal depth across every tool or production-scale experience with each one. Please use the linked projects to inspect the actual implementation.

---

## 🛠️ Stack (only what I've shipped with)
## How I Approach Engineering

**1. Make behavior inspectable.**
Readable code, useful documentation, and clear interfaces help other engineers understand a system.

**2. Treat failure as part of the design.**
Invalid input, unavailable dependencies, missing data, and uncertain model outputs deserve deliberate handling.

**3. Test the claim, not just the happy path.**
A successful demo is useful, but it does not establish correctness across different inputs and failure conditions.

**4. Separate implementation from evidence.**
A feature existing in code is different from a feature being tested, measured, or independently verified.

**Languages** · Python · SQL · TypeScript
**LLMs & APIs** · Groq (LLaMA 3, 3.1, 3.3 70B) · IBM Granite · IBM Watson · Hugging Face Inference API · OpenAI API
**RAG / Vector** · FAISS · sentence-transformers (`all-MiniLM-L6-v2`) · LangChain · PyPDF
**Agents** · Multi-agent debate patterns · Critic/verifier agents · CrewAI (Agentica)
**Backend** · FastAPI · REST APIs
**Frontend / Demo** · Streamlit · Gradio · Next.js
**Deployment** · Hugging Face Spaces · Streamlit Cloud
**5. Prefer understandable trade-offs over impressive terminology.**
Architecture should be justified by requirements, constraints, and observed behavior.

**6. Be honest about limitations.**
Clear limitations make technical work more useful to reviewers and future contributors.

---
## 📈 GitHub Stats

<div align="center">
## What I'm Working Toward

<img src="https://github-stats-extended.vercel.app/api?username=Faraz6180&show_icons=true&theme=tokyonight&hide_border=true" alt="Faraz's GitHub Stats" />
I'm focused on becoming a stronger software engineer through hands-on work in:

<img src="https://github-stats-extended.vercel.app/api/top-langs/?username=Faraz6180&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top Languages" />
* Python backend and API engineering.
* Data pipelines, database-backed systems, and data integrity.
* Testing, debugging, and maintainable application design.
* Reliable AI integrations and evaluation.
* Deployment, observability, and the operational behavior of software systems.

</div>
My goal is to build systems that another engineer can run, inspect, understand, and improve—not just applications that look convincing in a demo.

---

## 📬 Contact
## Connect With Me

I'm open to conversations about backend engineering, Python, data systems, applied AI, open-source collaboration, and suitable software engineering opportunities.

- 📧 **Email:** faraz.outreach8@gmail.com
- 💼 **LinkedIn:** [linkedin.com/in/farazmubeenhaider](https://linkedin.com/in/farazmubeenhaider)
- 🤗 **Hugging Face:** [huggingface.co/Faraz618](https://huggingface.co/Faraz618)
- 🧪 **Hackathons:** [lablab.ai/u/@Faraz_Mubeen](https://lablab.ai/u/@Faraz_Mubeen)
- ✍️ **Writing:** [medium.com/@farazmubeenhaider902](https://medium.com/@farazmubeenhaider902)
* **Email:** [faraz.outreach8@gmail.com](mailto:faraz.outreach8@gmail.com)
* **LinkedIn:** [Faraz Mubeen Haider](https://www.linkedin.com/in/farazmubeenhaider/)
* **GitHub:** [Faraz6180](https://github.com/Faraz6180)
* **Hugging Face:** [Faraz618](https://huggingface.co/Faraz618)
* **LabLab:** [Projects and hackathons](https://lablab.ai/u/@Faraz_Mubeen)
* **Medium:** [Technical writing](https://medium.com/@farazmubeenhaider902)

<div align="center">
<i>Currently open to remote Applied AI / LLM / GenAI Engineer roles.</i>

---

*Build carefully. Verify honestly. Document what matters.*

</div>

<div align="center">

*Currently open to remote Applied AI / LLM / GenAI Engineer roles.*

---

**Build carefully. Verify honestly. Document what matters.**

</div>
