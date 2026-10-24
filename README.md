<div align="center">

# Faraz Mubeen Haider

### AI Systems Engineer | LLM Applications, RAG & Evaluation

I build LLM-powered applications and explore how to make their outputs more grounded, testable, and reliable.

[![Open to Remote Roles](https://img.shields.io/badge/Open_to-Remote_AI_Roles-2ea44f?style=for-the-badge)](mailto:faraz.outreach8@gmail.com)
[![Hugging Face](https://img.shields.io/badge/Live_Demos-Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/Faraz618)
[![IBM Granite Winner](https://img.shields.io/badge/IBM_Granite-Hackathon_Winner-2458A6?style=for-the-badge)](https://lablab.ai/ai-hackathons/generative-ai-hackathon-with-ibm-granite/polyens)

[LinkedIn](https://www.linkedin.com/in/fm61/) · [GitHub](https://github.com/Faraz6180) · [Hugging Face](https://huggingface.co/Faraz618) · [Medium](https://medium.com/@farazmubeen902) · [Email](mailto:faraz.outreach8@gmail.com)

</div>

---

## About

My work sits at the intersection of **LLM applications, AI systems engineering, and output reliability**.

I build applications using retrieval-augmented generation (RAG), multi-agent workflows, and document intelligence. I am particularly interested in what happens when these systems fail: unsupported answers, weak retrieval, incorrect decisions, and outputs that appear convincing without sufficient evidence.

My approach is to build working systems, examine their limitations, and make their behavior easier to test and understand.

- **Focus:** LLM applications, RAG, agent workflows, and evaluation.
- **Backend:** Python, FastAPI, REST APIs, and SQL.
- **Deployment:** Public interactive demos and AI application prototypes.
- **Currently targeting:** Remote Applied AI, LLM Engineering, and AI Systems Engineering opportunities.

## Featured Projects

### 1. ComplianceRAG — Retrieval with Groundedness Criticism

[Repository](https://github.com/Faraz6180/ComplianceRAG) · [Live Demo](https://huggingface.co/spaces/Faraz618/ComplianceRAG)

A retrieval-augmented question-answering application that explores how to assess whether generated answers are supported by retrieved evidence.

**Problem:** Fluent answers can still contain claims that the source documents do not support.

**Implementation:**
- Retrieves relevant document passages using FAISS and `all-MiniLM-L6-v2`.
- Generates answers using the Hugging Face Inference API.
- Applies a critic for sentence-level groundedness and citation validation.
- Supports flagging low-confidence results for human review.

**Technologies:** Python · Gradio · FAISS · Sentence Transformers · Hugging Face Inference API · PyPDF

**Engineering question:** How can a RAG application distinguish a plausible answer from one adequately supported by its source material?

---

### 2. AdvancedLeadsGeneration-AI — IBM Granite Hackathon Winner

[Repository](https://github.com/Faraz6180/AdvancedLeadsGeneration-AI) · [Hackathon Project](https://lablab.ai/ai-hackathons/generative-ai-hackathon-with-ibm-granite/polyens)

A multi-agent lead-qualification system built around competing assessments of opportunity and risk.

**Problem:** Static lead-scoring rules can miss contextual signals in customer negotiations and historical deals.

**Implementation:**
- Uses separate agents to assess a lead from opportunity and risk perspectives.
- Combines their assessments through a reconciliation workflow.
- Uses IBM Granite models and IBM Watson AI services.

**Technologies:** Next.js · FastAPI · IBM Granite · IBM Watson AI

**Recognition:** Winner of the IBM Granite Generative AI Hackathon as part of Team PolyEns.

---

### 3. HireMind-AI — LLM-Powered Career Workflow

[Repository](https://github.com/Faraz6180/HireMind-AI) · [Live Demo](https://huggingface.co/spaces/Faraz618/HireMind-AI)

An integrated career-assistance application covering multiple stages of the job-search process.

**Features:**
- Multi-job-description analysis.
- Resume scoring and optimization.
- Skill-gap identification.
- Cover-letter generation.
- Interview preparation and career chat.
- Application tracking.

**Technologies:** Python · Streamlit · Groq API · LLaMA 3.1 · JSON persistence

---

### 4. SafeLite — Modular AI Safety Exploration

[Repository](https://github.com/Faraz6180/SafeLite)

A research-oriented project exploring how planning, safety reasoning, execution, simulation, and evaluation can be separated into testable components.

**Areas explored:**
- Separation of planning and execution.
- Explicit safety checks.
- Controlled simulation.
- Component-level behavior and failure analysis.

**Technologies:** Python · FastAPI · LangChain · Custom evaluation harness

---

## Recognition

- **IBM Granite Generative AI Hackathon:** Winner, Team PolyEns.
- **Harvard CS50x Puzzle Day 2025:** 1st place, 9/9.
- **Stanford Code in Place:** Section Leader, 2025 and 2026.
- **AlgoVerse AI Research Program:** Accepted with a 45% merit scholarship; RAG/NLP research.
- **BICON Startup Incubation:** Selected for my final-year project. [Selection proof](https://lnkd.in/p/dDGRiW2u)
- **AI hackathons:** 17 events and 14 reported submissions. [LabLab profile](https://lablab.ai/u/@Faraz_Mubeen)

## Technical Stack

| Area | Technologies |
|---|---|
| Languages | Python, SQL, TypeScript |
| Backend | FastAPI, REST APIs |
| Data | PostgreSQL, Pandas, SQLAlchemy |
| LLMs and inference | Groq, LLaMA, IBM Granite, IBM Watson AI, Hugging Face Inference API, OpenAI |
| Retrieval and RAG | FAISS, Sentence Transformers, LangChain, PyPDF |
| Agent workflows | Multi-agent debate, critic/verifier patterns, CrewAI |
| Applications | Streamlit, Gradio, Next.js |
| Deployment | Hugging Face Spaces, Streamlit Cloud |

## Engineering Principles

- **A working demo is the beginning.** Functionality alone does not establish correctness.
- **Inspect the retrieval pipeline.** Some apparent generation failures originate in missing, irrelevant, or poorly ranked context.
- **Make claims testable.** Features should be evaluated rather than assumed to work correctly.
- **Represent uncertainty honestly.** Systems should make limitations and questionable outputs visible.
- **Document failure modes.** Understanding where a system breaks is part of understanding the system itself.

## GitHub Activity

<div align="center">

<img src="https://github-stats-extended.vercel.app/api?username=Faraz6180&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub statistics" height="165" />

<img src="https://github-stats-extended.vercel.app/api/top-langs/?username=Faraz6180&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Most-used programming languages" height="165" />

</div>

## Contact

I am open to remote opportunities in Applied AI, LLM engineering, AI systems engineering, and Python backend development. I am also interested in open-source collaboration around RAG, agent workflows, evaluation, and AI reliability.

**Email:** [faraz.outreach8@gmail.com](mailto:faraz.outreach8@gmail.com)

<div align="center">

*Build carefully. Verify honestly. Document what matters.*

</div>
