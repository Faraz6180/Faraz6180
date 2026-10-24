 <div align="center">

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:0b1220,50:1a237e,100:3949ab&height=190&section=header&text=Faraz%20Mubeen%20Haider&fontColor=ffffff&fontSize=42&fontAlignY=38&desc=AI%20Systems%20%C2%B7%20LLM%20Applications%20%C2%B7%20Reliability%20%26%20Evaluation&descSize=15&descAlignY=60)

# Applied AI Engineer

**I build LLM applications and agent workflows, with a growing focus on reliability, evaluation, and failure analysis.**

I work across retrieval-augmented generation (RAG), multi-agent systems, and Python backends. I'm particularly interested in what happens when AI systems fail: unsupported answers, poor retrieval, incorrect decisions, and outputs that appear convincing but aren't adequately supported by evidence.

[![Remote Opportunities](https://img.shields.io/badge/Open_to-Remote_AI_Roles-2ea44f?style=flat-square)](mailto:faraz.outreach8@gmail.com)
[![Hugging Face](https://img.shields.io/badge/Live_Demos-Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/Faraz618)
[![IBM Granite Hackathon Winner](https://img.shields.io/badge/IBM_Granite_Hackathon-Winner-1f6feb?style=flat-square)](https://lablab.ai/ai-hackathons/generative-ai-hackathon-with-ibm-granite/polyens)

[LinkedIn](https://www.linkedin.com/in/fm61/) · [GitHub](https://github.com/Faraz6180) · [Hugging Face](https://huggingface.co/Faraz618) · [LabLab](https://lablab.ai/u/@Faraz_Mubeen) · [Medium](https://medium.com/@farazmubeen902) · [Email](mailto:faraz.outreach8@gmail.com)

</div>

---

## What I'm focused on

My technical interests sit at the intersection of building useful AI applications and understanding their failure modes.

- **LLM reliability and evaluation:** Groundedness, evidence support, output validation, and failure analysis.
- **RAG systems:** Retrieval pipelines, document-grounded question answering, and citation validation.
- **Agentic workflows:** Multi-agent collaboration, critique, reconciliation, and workflow orchestration.
- **AI application engineering:** Python, FastAPI, model APIs, data pipelines, and deployable interfaces.

My longer-term direction is to build AI systems that are not merely functional, but also testable, observable, and easier to trust.

## Selected projects

### 1. [ComplianceRAG](https://github.com/Faraz6180/ComplianceRAG)

**RAG with a groundedness critic and citation validation**

Retrieval-augmented generation can produce plausible answers that aren't sufficiently supported by the retrieved documents. ComplianceRAG explores an additional verification step between answer generation and delivery.

- **Retrieval:** FAISS with `all-MiniLM-L6-v2` embeddings.
- **Generation:** Hugging Face Inference API.
- **Verification:** Sentence-level groundedness critique and citation validation.
- **Human oversight:** Flagging low-confidence results for review.

**Why it matters:** The system explores how evidence checking can complement ordinary RAG generation rather than treating a fluent answer as a correct one.

**Stack:** `Python` · `Gradio` · `FAISS` · `sentence-transformers` · `Hugging Face Inference API` · `PyPDF`

[Live demo](https://huggingface.co/spaces/Faraz618/ComplianceRAG) · [Source code](https://github.com/Faraz6180/ComplianceRAG)

---

### 2. [AdvancedLeadsGeneration-AI](https://github.com/Faraz6180/AdvancedLeadsGeneration-AI)

**IBM Granite Generative AI Hackathon — Winning project**

A multi-agent lead qualification workflow that considers both the potential value and the risks associated with a business opportunity.

- One agent argues for the opportunity.
- Another evaluates risks and counterarguments.
- A reconciliation step combines the assessments into a consolidated recommendation.
- Historical deal context informs the evaluation.

**Engineering focus:** Structuring a decision workflow around multiple perspectives rather than relying exclusively on a single model response.

**Stack:** `Next.js` · `FastAPI` · `IBM Watson AI` · `IBM Granite`

[Hackathon project](https://lablab.ai/ai-hackathons/generative-ai-hackathon-with-ibm-granite/polyens) · [Source code](https://github.com/Faraz6180/AdvancedLeadsGeneration-AI)

---

### 3. [HireMind-AI](https://github.com/Faraz6180/HireMind-AI)

**LLM-powered career workflow**

An integrated career application that helps candidates analyze job requirements, identify skill gaps, and prepare application materials.

Features include:

- Multi-job-description analysis and ATS-style scoring.
- Skill-gap detection and resume optimization.
- Cover-letter generation and interview preparation.
- Application tracking and career-related chat.

**Engineering focus:** Connecting multiple LLM-powered capabilities into a single application with a persistent workflow.

**Stack:** `Python` · `Streamlit` · `Groq API` · `LLaMA 3.1` · `JSON persistence`

[Live demo](https://huggingface.co/spaces/Faraz618/HireMind-AI) · [Source code](https://github.com/Faraz6180/HireMind-AI)

---

<details>
<summary><strong>Additional work: SafeLite</strong></summary>

### [SafeLite](https://github.com/Faraz6180/SafeLite)

A modular, research-oriented AI system exploring planning, safety reasoning, execution, simulation, and evaluation as separately testable components.

Areas of interest include:

- Separating planning from execution.
- Explicit safety checks and controlled simulation.
- Examining component behavior and failure cases.

**Stack:** `Python` · `FastAPI` · `LangChain` · Custom evaluation harness

[Explore the repository](https://github.com/Faraz6180/SafeLite)

</details>

---

## Recognition

- **IBM Granite Generative AI Hackathon — Winner**, Team PolyEns.
- **Harvard CS50x Puzzle Day 2025 — 1st place**, with a reported score of 9/9.
- **Stanford Code in Place — Section Leader**, 2025 and 2026.
- **BICON Startup Incubation — Selected** for my final-year project. [Selection announcement](https://lnkd.in/p/dDGRiW2u)
- **AlgoVerse AI Research Program — Accepted** with a reported 45% merit scholarship, for RAG/NLP research.
- **AI hackathons:** 17 events and 14 reported submissions. [LabLab profile](https://lablab.ai/u/@Faraz_Mubeen)

These experiences reflect a mix of technical building, collaborative problem-solving, teaching, and early-stage research exposure.

---

## Technical toolkit

| Area | Technologies |
|---|---|
| Languages | Python, SQL, TypeScript |
| Backend | FastAPI, REST APIs |
| Data | PostgreSQL, SQLAlchemy, Pandas |
| LLMs and inference | Groq, LLaMA, IBM Granite, IBM Watson AI, Hugging Face Inference API, OpenAI APIs |
| Retrieval and RAG | FAISS, sentence-transformers, LangChain, PyPDF |
| Agent workflows | Multi-agent debate, critic/verifier patterns, CrewAI |
| Interfaces | Streamlit, Gradio, Next.js |
| Deployment | Hugging Face Spaces, Streamlit Cloud |

---

## Engineering principles

- **A working demo is a starting point.** Functionality alone doesn't establish correctness.
- **Inspect the evidence.** When an AI answer is wrong, investigate retrieval, context quality, model behavior, and validation.
- **Make claims testable.** Features should be distinguished from verified behavior.
- **Expose uncertainty.** Low-confidence or insufficiently supported outputs should not be presented as unquestionable facts.
- **Document limitations.** Clear constraints make software easier to evaluate, maintain, and improve.

These are the principles I aim to apply as I deepen my work in AI systems reliability and evaluation.

---

## Let's connect

I'm open to remote opportunities in **Applied AI, LLM Engineering, AI application development, and Python backend engineering**, along with collaborations involving RAG, agentic workflows, and AI evaluation.

- **Email:** [faraz.outreach8@gmail.com](mailto:faraz.outreach8@gmail.com)
- **GitHub:** [Faraz6180](https://github.com/Faraz6180)
- **Hugging Face:** [Faraz618](https://huggingface.co/Faraz618)
- **LinkedIn:** [Connect with me](https://www.linkedin.com/in/fm61/)

<div align="center">

*Build carefully. Evaluate honestly. Make failures visible.*

</div>
