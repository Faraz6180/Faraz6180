<div align="center">

![Faraz Mubeen Haider | Software Engineering | Backend | Data Systems | Applied AI](https://capsule-render.vercel.app/api?type=waving&color=0:0B1220,50:1E3A5F,100:4F8CFF&height=190&section=header&text=Faraz%20Mubeen%20Haider&fontColor=F1F5F9&fontSize=42&fontAlignY=38&desc=Software%20Engineering%20%7C%20Backend%20%7C%20Data%20Systems%20%7C%20Applied%20AI&descSize=15&descAlignY=60)

### Software Engineer building Python backend systems, data workflows, and AI-enabled applications.

I care about what happens beyond the happy path: correctness, failure handling, reproducibility, and maintainable software.

[![GitHub](https://img.shields.io/badge/GitHub-Projects-1E3A5F?style=flat-square&logo=github&logoColor=F1F5F9)](https://github.com/Faraz6180)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-1E3A5F?style=flat-square&logo=linkedin&logoColor=F1F5F9)](https://www.linkedin.com/in/farazmubeenhaider/)
[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-Applications-1E3A5F?style=flat-square&logo=huggingface&logoColor=F1F5F9)](https://huggingface.co/Faraz618)
[![LabLab](https://img.shields.io/badge/LabLab-Projects-1E3A5F?style=flat-square)](https://lablab.ai/u/@Faraz_Mubeen)

</div>

---

## Table of Contents

- [About Me](#about-me)
- [Engineering Focus](#engineering-focus)
- [Featured Projects](#featured-projects)
- [Selected Engineering Experience](#selected-engineering-experience)
- [Recognition and Community](#recognition-and-community)
- [Hackathon Projects](#hackathon-projects)
- [Technology Stack](#technology-stack)
- [How I Approach Engineering](#how-i-approach-engineering)
- [What I'm Working Toward](#what-im-working-toward)
- [Connect With Me](#connect-with-me)

---

## About Me

I'm a Software Engineer with a background in backend development, data processing, and applied AI. I build Python-based applications that connect APIs, data workflows, and language-model capabilities into usable software.

My primary engineering identity is **Python backend and data systems**, with applied AI as a differentiator. I'm interested in the software around intelligent applications—not only the model call, but also the interfaces, data flow, validation, error handling, and evaluation that make an application understandable and useful.

My main engineering interests are:

- **Backend engineering:** API design, application structure, request validation, service integration, error handling, and maintainability.
- **Data systems:** Data ingestion, transformation, SQL, database-backed applications, data quality, and repeatable workflows.
- **Reliable AI applications:** Retrieval-augmented generation (RAG), document intelligence, LLM integrations, and evaluation.
- **Retrieval and search:** Embeddings, document chunking, vector search, source attribution, and retrieval behavior.
- **Software quality:** Reproducible setup, meaningful tests, clear documentation, and honest reporting of limitations.
- **System design:** Understanding component boundaries, data flow, failure modes, and trade-offs.

My experience includes AI-enabled product development, data-processing workflows, hackathon projects, and independent engineering work. I use my repositories to demonstrate implementations and technical decisions—not just list technologies.

I'm particularly interested in backend, Python, data engineering, platform-oriented software, and AI systems opportunities where I can contribute to real engineering work and continue growing as a software engineer.

**Location:** Pakistan · Open to suitable remote and international opportunities.

---

## Engineering Focus

| Area | What I Work On |
|---|---|
| Backend development | Python, FastAPI, REST APIs, request validation, service integration, maintainable application structure |
| Data processing | SQL, PostgreSQL, Pandas, SQLAlchemy, ETL-style workflows, data validation |
| Applied AI | LLM integrations, RAG pipelines, document processing, AI-assisted workflows |
| Retrieval and search | FAISS, sentence-transformers, document chunking, retrieval and source context |
| Agentic workflows | Multi-agent coordination, specialist-agent patterns, critic and verification steps |
| Application delivery | Docker and deployment workflows where applicable, Streamlit, Gradio, Hugging Face Spaces |
| Engineering quality | Testing, clear setup instructions, explicit limitations, reproducible examples |

> These areas reflect my work and interests; the depth of implementation and validation varies by project. Please use the linked repositories to inspect the actual code and evidence.

---

## Featured Projects

These projects show different parts of my engineering interests: retrieval and answer checking, data quality, research workflows, and multi-agent application design.

### 1. [ComplianceRAG](https://github.com/Faraz6180/ComplianceRAG) — Document Retrieval and Answer Verification

**A RAG application exploring how generated answers can be checked against retrieved source material.**

[![Repository](https://img.shields.io/badge/Repository-1E3A5F?style=flat-square&logo=github&logoColor=F1F5F9)](https://github.com/Faraz6180/ComplianceRAG)
[![Live Demo](https://img.shields.io/badge/Live%20Demo-4F8CFF?style=flat-square&logo=huggingface&logoColor=0B1220)](https://huggingface.co/spaces/Faraz618/ComplianceRAG)

#### Problem

Retrieval-augmented generation can produce fluent answers that are not adequately supported by the documents supplied to the model. A useful system needs to consider not only answer generation but also retrieval quality, citations, and unsupported claims.

#### Implementation

The project uses a multi-stage workflow:

1. **Retrieval:** Search document representations using FAISS and sentence embeddings.
2. **Generation:** Generate an answer from retrieved context using a language model, with source citations.
3. **Checking:** Apply a critic step intended to assess sentence-level support and citation validity.
4. **Review:** Identify low-confidence or weakly supported outputs for additional scrutiny.

**Technologies:** Python · FAISS · `sentence-transformers` · Hugging Face Inference API · PyPDF · Gradio

#### Engineering questions explored

- How does retrieval quality affect the final answer?
- Can generated claims be traced to source passages?
- What happens when relevant evidence is missing?
- How should uncertain or unsupported answers be handled?
- What limitations remain when a language model is used to assess another model's answer?

> **Important limitation:** A critic or groundedness score is not a guarantee of factual correctness. The reliability of the checking process depends on its implementation and evaluation.

**Next engineering direction:** Build a reproducible regression-evaluation suite with representative questions, expected evidence, retrieval metrics, citation checks, and a readable report—after verifying the current implementation and defining a valid evaluation dataset.

### 2. [data-quality-pipeline](https://github.com/Faraz6180/data-quality-pipeline) — Data Quality and Anomaly Detection

**A data workflow for inspecting tabular data and identifying records that may deserve further review.**

[![Repository](https://img.shields.io/badge/Repository-1E3A5F?style=flat-square&logo=github&logoColor=F1F5F9)](https://github.com/Faraz6180/data-quality-pipeline)
[![Live Demo](https://img.shields.io/badge/Live%20Demo-4F8CFF?style=flat-square&logo=huggingface&logoColor=0B1220)](https://huggingface.co/spaces/Faraz618/data-quality-pipeline)

#### Problem

Tabular data often contains missing values, duplicate records, inconsistent fields, and unusual observations. These issues can reduce the usefulness of downstream analysis if they are not identified and documented.

#### Implementation

The project brings together data-quality checks and anomaly-detection techniques in an interactive workflow. Its described capabilities include:

- Uploading and inspecting CSV data.
- Checking for common data-quality issues.
- Handling missing values and duplicates.
- Combining Isolation Forest and Z-score signals to flag unusual records.
- Assigning risk-oriented categories for review.
- Producing downloadable outputs and explanations.

**Technologies:** Python · Pandas · scikit-learn · Gradio

#### Engineering questions explored

- Which data issues should be detected before analysis?
- How should data cleaning be distinguished from anomaly detection?
- How can suspicious records be presented for human review?
- How should anomaly flags be interpreted when the data has no ground-truth labels?

> An anomaly flag indicates a record worth investigating; it does not automatically mean the record is erroneous or fraudulent.

### 3. [AI-powered-Research-Assistant](https://github.com/Faraz6180/AI-powered-Research-Assistant) — Multi-Source Research Assistant

**An application that combines information retrieval with LLM-assisted synthesis.**

[![Repository](https://img.shields.io/badge/Repository-1E3A5F?style=flat-square&logo=github&logoColor=F1F5F9)](https://github.com/Faraz6180/AI-powered-Research-Assistant)

#### Problem

Research often requires gathering information from multiple sources, identifying useful material, and turning it into an understandable response. A synthesis step can help organize information, but the source material still matters.

#### Approach

The application is described as retrieving information from sources such as ArXiv, Wikipedia, and web search, then using an LLM to synthesize a conversational response.

**Technologies:** Python · LangChain · Groq · Streamlit

#### What to explore

- How external information sources are integrated.
- How retrieved material is passed into a generation workflow.
- How the application separates retrieval from synthesis.
- How source traceability and freshness can affect answer quality.
- How to distinguish a readable summary from a fully verifiable answer.

### 4. [AdvancedLeadsGeneration-AI](https://github.com/Faraz6180/AdvancedLeadsGeneration-AI) — Multi-Agent Lead Qualification

**A multi-agent approach to lead qualification developed by Team PolyEns.**

[![Repository](https://img.shields.io/badge/Repository-1E3A5F?style=flat-square&logo=github&logoColor=F1F5F9)](https://github.com/Faraz6180/AdvancedLeadsGeneration-AI)
[![Hackathon Recognition](https://img.shields.io/badge/IBM%20Granite-Hackathon%20Winner-1E3A5F?style=flat-square&logo=ibm&logoColor=F1F5F9)](https://lablab.ai/ai-hackathons/generative-ai-hackathon-with-ibm-granite/polyens)

#### Problem

Lead qualification can involve competing considerations, uncertainty, and incomplete information. A single scoring step may not make those considerations explicit.

#### Approach

The project explores a multi-agent workflow in which different agents assess a lead from different perspectives, followed by a reconciliation step.

**Technologies:** Next.js · FastAPI · IBM Watson AI · IBM Granite

#### What to explore

- How responsibilities are divided between agents.
- How intermediate results are passed between components.
- How competing assessments are reconciled.
- How the workflow could be evaluated against representative lead scenarios.
- What testing is needed to understand consistency and failure behavior.

**Recognition:** Team PolyEns won the Generative AI Hackathon with IBM Granite. See the [linked event and project page](https://lablab.ai/ai-hackathons/generative-ai-hackathon-with-ibm-granite/polyens) for the project context.

### 5. [HireMind-AI](https://github.com/Faraz6180/HireMind-AI) — AI-Assisted Career Workflow

**An LLM-powered application for resume analysis and job-application tasks.**

[![Repository](https://img.shields.io/badge/Repository-1E3A5F?style=flat-square&logo=github&logoColor=F1F5F9)](https://github.com/Faraz6180/HireMind-AI)
[![Live Demo](https://img.shields.io/badge/Live%20Demo-4F8CFF?style=flat-square&logo=huggingface&logoColor=0B1220)](https://huggingface.co/spaces/Faraz618/HireMind-AI)

#### Problem

Job seekers may need to compare a resume against job descriptions, identify skill gaps, and prepare application materials through a structured workflow.

#### Features

The application brings together career-related tasks such as:

- Resume and job-description analysis.
- ATS-oriented scoring and keyword comparison.
- Skill-gap identification.
- Resume improvement suggestions.
- Cover-letter generation.
- Interview preparation.
- Application tracking.
- Career-related chat.

**Technologies:** Python · Streamlit · Groq API · LLaMA models · JSON persistence · Hugging Face Spaces

#### Engineering focus

The project provides an opportunity to examine application flow, model integration, input handling, persistence, and the limitations of heuristic or LLM-generated assessments.

> ATS-style scores should be treated as estimates, not predictions of how every employer's recruitment system will evaluate a candidate.

### 6. [SafeLite](https://github.com/Faraz6180/SafeLite) — Research-Oriented AI System

**A modular project exploring planning, safety reasoning, execution, simulation, and evaluation.**

[![Explore Code](https://img.shields.io/badge/Explore%20Code-1E3A5F?style=flat-square&logo=github&logoColor=F1F5F9)](https://github.com/Faraz6180/SafeLite)

SafeLite explores how components of an AI system can be separated so that planning, safety-related checks, execution, and evaluation can be examined independently.

#### Areas of interest

- Separation of planning and execution.
- Explicit safety checks and decision boundaries.
- Simulation and controlled evaluation.
- Testing component behavior and failure cases.

> The project should not be interpreted as demonstrating formal safety guarantees unless those guarantees are established by the implementation and supporting evidence.

---

## Selected Engineering Experience

### Data Processing and Reporting

My data-engineering work has involved Python-based data processing, including Pandas, SQLAlchemy, and PostgreSQL.

The engineering problems in this area include:

- Transforming data into consistent, usable structures.
- Working with relational databases and reporting workflows.
- Reducing repetitive manual processing.
- Making outputs easier to inspect and maintain.
- Considering data quality and how transformations affect downstream results.

The most meaningful evidence for this work is the underlying implementation, the data transformations, and a clear explanation of the workflow and its measured impact where that impact can be substantiated.

### AI-Enabled Product Development

My product-development experience includes building AI-enabled application workflows and integrating language-model capabilities into software.

Areas of work include document ingestion, API integration, structured outputs, and coordinating model-driven steps inside an application.

I aim to document the boundary between what a system implements, what has been tested, and what remains an improvement opportunity.

---

## Recognition and Community

- **IBM Granite Generative AI Hackathon — Winner:** Team PolyEns, AdvancedLeadsGeneration-AI.
- **Stanford Code in Place — Section Leader:** Teaching and supporting learners in an introductory Python programming program.
- **AlgoVerse Research Program:** Accepted with a reported 45% merit scholarship.
- **Founder Institute Pakistan:** Cohort participation.

For project-specific details and hackathon participation, see my [LabLab profile](https://lablab.ai/u/@Faraz_Mubeen).

---

## Hackathon Projects

Hackathons have given me opportunities to build prototypes, work with unfamiliar technologies, collaborate with teammates, and explore different AI application patterns.

| Project or Event | Focus | Reference |
|---|---|---|
| Generative AI Hackathon with IBM Granite | AI-assisted lead qualification | [Project and recognition](https://lablab.ai/ai-hackathons/generative-ai-hackathon-with-ibm-granite/polyens) |
| Fall in Love with DeepSeek | DevAI | [LabLab profile](https://lablab.ai/u/@Faraz_Mubeen) |
| Replit & Cursor Hackathon | Byte Busters | [LabLab profile](https://lablab.ai/u/@Faraz_Mubeen) |
| Agentic AI with IBM watsonx Orchestrate | AI SOC Security Analyst | [LabLab profile](https://lablab.ai/u/@Faraz_Mubeen) |
| Co-Creating with GPT-5 | Agentica | [LabLab profile](https://lablab.ai/u/@Faraz_Mubeen) |
| RAISE YOUR HACK | HealthBridge | [LabLab profile](https://lablab.ai/u/@Faraz_Mubeen) |
| AI for Connectivity Hackathon II | KONEKTA | [LabLab profile](https://lablab.ai/u/@Faraz_Mubeen) |
| AIstronauts: Space Agents | ARCANA Space Agent | [LabLab profile](https://lablab.ai/u/@Faraz_Mubeen) |
| Qubic Hack the Future | AdmitWise | [LabLab profile](https://lablab.ai/u/@Faraz_Mubeen) |

[Explore my LabLab profile and submissions →](https://lablab.ai/u/@Faraz_Mubeen)

---

## Technology Stack

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

> The presence of a technology in this list does not imply equal depth across every tool or production-scale experience with each one. Please use the linked projects to inspect the actual implementation.

---

## How I Approach Engineering

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

**7. Make work reproducible.**  
Where possible, provide clear setup steps and enough context for another developer to run or inspect the project.

**8. Improve through feedback.**  
Code review, testing, issue discussions, and thoughtful technical criticism are part of engineering—not distractions from it.

---

## What I'm Working Toward

I'm focused on becoming a stronger software engineer through hands-on work in:

- Python backend and API engineering.
- Data pipelines, database-backed systems, and data integrity.
- Testing, debugging, and maintainable application design.
- Reliable AI integrations and evaluation.
- Deployment, observability, and the operational behavior of software systems.
- Clear technical communication and architecture decisions.

My goal is to build systems that another engineer can run, inspect, understand, and improve—not just applications that look convincing in a demo.

I also want my public repositories to become useful engineering artifacts: clear problem statements, reproducible examples, explicit trade-offs, and evidence that makes it easier for others to learn from or contribute to the work.

---

## Connect With Me

I'm open to conversations about backend engineering, Python, data systems, applied AI, open-source collaboration, and suitable software engineering opportunities.

- **Email:** [faraz.outreach8@gmail.com](mailto:faraz.outreach8@gmail.com)
- **LinkedIn:** [Faraz Mubeen Haider](https://www.linkedin.com/in/farazmubeenhaider/)
- **GitHub:** [Faraz6180](https://github.com/Faraz6180)
- **Hugging Face:** [Faraz618](https://huggingface.co/Faraz618)
- **LabLab:** [Projects and hackathons](https://lablab.ai/u/@Faraz_Mubeen)
- **Medium:** [Technical writing](https://medium.com/@farazmubeenhaider902)

If you're working on Python backends, data workflows, retrieval systems, or dependable AI applications, I'd be glad to connect and learn what you're building.

---

<div align="center">

*Build carefully. Verify honestly. Document what matters.*

</div>
