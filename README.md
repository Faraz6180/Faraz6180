
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

My work focuses on LLM-powered applications, retrieval pipelines, multi-agent workflows, and document intelligence. I am particularly interested in whether a system retrieves relevant evidence, produces supportable outputs, and handles uncertainty appropriately.

### 1. ComplianceRAG — Document Retrieval and Answer Verification

[![Repository](https://img.shields.io/badge/Repository-181717?style=flat-square&logo=github)](https://github.com/Faraz6180/ComplianceRAG)
[![Live Demo](https://img.shields.io/badge/Live_Demo-FFD21E?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/spaces/Faraz618/ComplianceRAG)

**A RAG application exploring how generated answers can be checked against retrieved source material.**

**Problem**

Retrieval-augmented generation can produce fluent answers that are not adequately supported by the documents supplied to the model. A useful system needs to consider not only answer generation but also retrieval quality, citations, and unsupported claims.

**Implementation**

The project uses a multi-stage workflow:

1. **Retrieval:** Search document representations using FAISS and sentence embeddings.
2. **Generation:** Generate an answer from retrieved context using a language model, with source citations.
3. **Checking:** Apply a critic step intended to assess sentence-level support and citation validity.
4. **Review:** Identify low-confidence or weakly supported outputs for additional scrutiny.

**Technologies:** Python · FAISS · `sentence-transformers` · Hugging Face Inference API · PyPDF · Gradio

**Engineering questions explored**

- How does retrieval quality affect the final answer?
- Can generated claims be traced to source passages?
- What happens when relevant evidence is missing?
- How should uncertain or unsupported answers be handled?

**Important limitation:** A critic or groundedness score is not a guarantee of factual correctness. The reliability of the checking process depends on its implementation and evaluation.

---

### 2. AdvancedLeadsGeneration-AI — IBM Granite Hackathon Winner

[![Repository](https://img.shields.io/badge/Repository-181717?style=flat-square&logo=github)](https://github.com/Faraz6180/AdvancedLeadsGeneration-AI)
[![Hackathon Recognition](https://img.shields.io/badge/IBM_Granite-Hackathon_Winner-0F62FE?style=flat-square&logo=ibm)](https://lablab.ai/ai-hackathons/generative-ai-hackathon-with-ibm-granite/polyens)

**A multi-agent approach to lead qualification developed by Team PolyEns.**

**Problem**

Lead qualification often requires balancing potential value against risks, uncertainty, and incomplete information. A single scoring step may not make those competing considerations explicit.

**Approach**

The project explores a multi-agent workflow in which different agents assess a lead from different perspectives, followed by a reconciliation step.

**Technologies:** Next.js · FastAPI · IBM Watson AI · IBM Granite

**Engineering questions explored**

- How are responsibilities divided between agents?
- How are intermediate results passed between components?
- How are competing assessments reconciled?
- How could the workflow be evaluated against representative lead scenarios?

**Recognition:** Team PolyEns won the Generative AI Hackathon with IBM Granite. See the linked event page for the project and recognition context.

---

### 3. HireMind-AI — AI-Assisted Career Workflow

[![Repository](https://img.shields.io/badge/Repository-181717?style=flat-square&logo=github)](https://github.com/Faraz6180/HireMind-AI)
[![Live Demo](https://img.shields.io/badge/Live_Demo-FFD21E?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/spaces/Faraz618/HireMind-AI)

**An LLM-powered application for resume analysis and job-application tasks.**

**Problem**

Job seekers often need to compare a resume with several job descriptions, identify gaps, and prepare application materials without a structured workflow.

**Features**

The application brings together career-related tasks such as:

- Resume and job-description analysis.
- ATS-oriented scoring and keyword comparison.
- Skill-gap identification.
- Resume improvement suggestions.
- Cover-letter generation.
- Interview preparation.
- Application tracking.
- Career-related chat.

**Technologies:** Streamlit · Groq API · LLaMA models · JSON persistence · Hugging Face Spaces

The project provides an opportunity to examine application flow, model integration, input handling, persistence, and the limitations of heuristic or LLM-generated assessments.

**Important limitation:** ATS-style scores should be treated as estimates, not predictions of how every employer's recruitment system will evaluate a candidate.

---

### 4. SafeLite — Research-Oriented AI System

[![Repository](https://img.shields.io/badge/Explore_Code-181717?style=flat-square&logo=github)](https://github.com/Faraz6180/SafeLite)

**A modular project exploring planning, safety reasoning, execution, simulation, and evaluation.**

SafeLite explores how components of an AI system can be separated so that planning, safety-related checks, execution, and evaluation can be examined independently.

**Areas of interest**

- Separation of planning and execution.
- Explicit safety checks and decision boundaries.
- Simulation and controlled evaluation.
- Testing component behavior and failure cases.

The repository is best understood through its actual implementation, tests, and documented research status. The project should not be interpreted as demonstrating formal safety guarantees unless those guarantees are established by the implementation and supporting evidence.

---

## 🧩 Additional AI Applications

Beyond the featured projects, my portfolio includes work across several AI application categories.

| Domain | Projects and Implementations |
|---|---|
| **RAG Systems** | Multi-agent RAG with groundedness critic, enterprise document Q&A, compliance retrieval |
| **AI Agents** | Multi-agent lead qualification, job-application agent, requirement-classification agent |
| **Document Intelligence** | PDF-to-structured-insight extraction, resume ATS scoring, contract fit-gap analysis |
| **LLM Applications** | 8+ live Hugging Face Spaces, Groq, LLaMA 3, IBM Granite, Hugging Face Inference API |

Explore the implementations through my [GitHub repositories](https://github.com/Faraz6180) and [Hugging Face applications](https://huggingface.co/Faraz618).

---

## 💻 Selected Engineering Experience

### Data Processing and Reporting

My data-engineering work has involved Python-based data processing, including Pandas, SQLAlchemy, and PostgreSQL.

The engineering problems in this area include:

- Transforming data into consistent, usable structures.
- Working with relational databases and reporting workflows.
- Reducing repetitive manual processing.
- Making outputs easier to inspect and maintain.

The most meaningful evidence for this work is the underlying implementation, the data transformations, and a clear explanation of the workflow and its measured impact where that impact can be substantiated.

### AI-Enabled Product Development

My product-development experience includes building AI-enabled application workflows and integrating language-model capabilities into software.

Areas of work include document ingestion, API integration, structured outputs, and coordinating model-driven steps inside an application.

I aim to document the boundary between what a system implements, what has been tested, and what remains an improvement opportunity.

---

## 🏆 Recognition and Community

- **IBM Granite Generative AI Hackathon — Winner:** Team PolyEns, AdvancedLeadsGeneration-AI.
- **Stanford Code in Place — Section Leader:** Teaching and supporting learners in an introductory Python programming program.
- **AlgoVerse Research Program (EOE.ai × Omdena):** Accepted with a reported 45% merit scholarship; RAG/NLP research.
- **Founder Institute Pakistan:** Cohort participation.

For project-specific details and hackathon participation, see my [LabLab profile](https://lablab.ai/u/@Faraz_Mubeen).

### Hackathon Track Record

Hackathons have given me opportunities to build prototypes, work with unfamiliar technologies, and explore different AI application patterns.

| Event | Project | Result |
|---|---|---|
| Generative AI Hackathon with IBM Granite | AdvancedLeadsGeneration-AI | 🏆 Winner |
| Fall in Love with DeepSeek | DevAI | 🥉 Finalist |
| Replit & Cursor Hackathon | Byte Busters | 🥉 Finalist |
| Agentic AI with IBM watsonx Orchestrate | AI SOC Security Analyst | Participant |
| Co-Creating with GPT-5 | Agentica — multi-agent orchestration | Participant |
| RAISE YOUR HACK | HealthBridge | Participant |
| AI for Connectivity Hackathon II | KONEKTA | Participant |
| AIstronauts: Space Agents | ARCANA Space Agent | Participant |
| Qubic Hack the Future | AdmitWise | Participant |

**Full profile:** [LabLab — 15 events, 11 submissions](https://lablab.ai/u/@Faraz_Mubeen).

---

## 🛠️ Technology Stack

I prefer to describe my stack in terms of the work it supports rather than present a long list of tools as a measure of expertise.

| Category | Technologies |
|---|---|
| Languages | Python, SQL, TypeScript |
| Backend | FastAPI, REST APIs |
| Databases and data | PostgreSQL, Pandas, SQLAlchemy |
| LLM integrations | Groq API, LLaMA models, IBM Granite, IBM Watson AI, Hugging Face Inference API, OpenAI API |
| Retrieval | FAISS, sentence-transformers, LangChain, PyPDF |
| AI workflows | Multi-agent workflows, critic and verification patterns |
| Interfaces | Streamlit, Gradio, Next.js |
| Demos and deployment | Hugging Face Spaces, Streamlit Cloud |

The presence of a technology in this list does not imply equal depth across every tool or production-scale experience with each one. Please use the linked projects to inspect the actual implementation.

---

## 🧠 Engineering Philosophy

**1. Make behavior inspectable.**

Readable code, useful documentation, and clear interfaces help other engineers understand a system.

**2. Treat failure as part of the design.**

Invalid input, unavailable dependencies, missing data, and uncertain model outputs deserve deliberate handling.

**3. Test the claim, not just the happy path.**

A successful demo is useful, but it does not establish correctness across different inputs and failure conditions.

**4. Separate implementation from evidence.**

A feature existing in code is different from a feature being tested, measured, or independently verified.

**5. Prefer understandable trade-offs over impressive terminology.**

Architecture should be justified by requirements, constraints, and observed behavior.

**6. Be honest about limitations.**

Clear limitations make technical work more useful to reviewers and future contributors.

---

## 📈 GitHub Statistics

<div align="center">

<img src="https://github-stats-extended.vercel.app/api?username=Faraz6180&show_icons=true&theme=tokyonight&hide_border=true" alt="Faraz's GitHub Stats" />

<img src="https://github-stats-extended.vercel.app/api/top-langs/?username=Faraz6180&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top Languages" />

</div>

---

## 🎯 What I'm Working Toward

I'm focused on becoming a stronger software engineer through hands-on work in:

- Python backend and API engineering.
- Data pipelines, database-backed systems, and data integrity.
- Testing, debugging, and maintainable application design.
- Reliable AI integrations and evaluation.
- Deployment, observability, and the operational behavior of software systems.

My goal is to build systems that another engineer can run, inspect, understand, and improve—not just applications that look convincing in a demo.

---

## 📬 Connect With Me

I'm open to conversations about backend engineering, Python, data systems, applied AI, open-source collaboration, and suitable software engineering opportunities.

- 📧 **Email:** [faraz.outreach8@gmail.com](mailto:faraz.outreach8@gmail.com)
- 💼 **LinkedIn:** [Faraz Mubeen Haider](https://www.linkedin.com/in/farazmubeenhaider/)
- 🧑‍💻 **GitHub:** [Faraz6180](https://github.com/Faraz6180)
- 🤗 **Hugging Face:** [Faraz618](https://huggingface.co/Faraz618)
- 🧪 **LabLab:** [Projects and hackathons](https://lablab.ai/u/@Faraz_Mubeen)
- ✍️ **Medium:** [Technical writing](https://medium.com/@farazmubeenhaider902)

<div align="center">

*Currently open to remote Applied AI / LLM / GenAI Engineer roles.*

---

**Build carefully. Verify honestly. Document what matters.**

</div>
