<div align="center">

<!-- HERO BANNER: generate at banner.dev or capsule-render -->
![Header](https://capsule-render.vercel.app/api?type=waving&color=0:0b1220,50:1a237e,100:3949ab&height=200&section=header&text=Faraz%20Mubeen%20Haider&fontColor=ffffff&fontSize=48&fontAlignY=38&desc=Applied%20AI%20Engineer%20·%20LLM%20Systems%20·%20RAG%20·%20Agents&descSize=18&descAlignY=60)

### Applied AI Engineer — I build LLM systems, ship them to production, and make sure they don't hallucinate.

[![Live Demos on Hugging Face](https://img.shields.io/badge/🤗_Live_Demos-8_deployed-yellow?style=for-the-badge)](https://huggingface.co/Faraz618)
[![IBM Granite Winner](https://img.shields.io/badge/🏆_IBM_Granite_Hackathon-Winner-blue?style=for-the-badge)](https://lablab.ai/ai-hackathons/generative-ai-hackathon-with-ibm-granite/polyens)
[![Stanford Code in Place](https://img.shields.io/badge/Stanford_Code_in_Place-Section_Leader-red?style=for-the-badge&logo=stanford)](https://codeinplace.stanford.edu/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/farazmubeenhaider)

</div>

---

## 👋 About

I'm an **Applied AI Engineer** focused on shipping LLM-powered systems — **RAG pipelines, multi-agent workflows, and document intelligence.** My work lives at the intersection of *"does it actually retrieve the right thing"* and *"can we prove it didn't hallucinate."*

- 🏆 **IBM Granite Hackathon — Winner** (Team PolyEns, agentic lead-generation)
- 🚀 **11 AI systems shipped** across **15 international hackathons** in 2024–2026
- 🎓 **Stanford Code in Place** — Section Leader (selected from 900+ global applicants)
- 🔬 **AlgoVerse Research Program** (EOE.ai × Omdena) — 45% merit scholarship, RAG/NLP research
- 📍 Pakistan · Open to **remote AI Engineer / GenAI / LLM Engineer** roles

> I don't list technologies I haven't shipped with. Every stack on this page appears in a repo you can open.

---

## 🎯 What I Actually Build

| Domain | What I've Shipped |
|---|---|
| **RAG Systems** | Multi-agent RAG with groundedness critic · Enterprise doc Q&A · Compliance retrieval |
| **AI Agents** | Multi-agent lead qualification (debate pattern) · Job-application agent · Requirement-classification agent |
| **Document Intelligence** | PDF → structured insight extraction · Resume ATS scoring · Contract fit-gap analysis |
| **LLM Applications** | 8+ live Hugging Face Spaces · Groq / LLaMA 3 / IBM Granite / HF Inference API |

---

## 🚀 Featured Projects

### 🧪 [ComplianceRAG](https://github.com/Faraz6180/ComplianceRAG) — RAG with a Groundedness Critic
> Most RAG demos hide when retrieval fails. This one **measures** it.

**The problem:** RAG systems produce fluent answers that quietly drift from source material. In compliance, that's a lawsuit.

**The system:** Three-agent pipeline — **Retrieval Agent** (FAISS + `all-MiniLM-L6-v2`) → **Generation Agent** (HF Inference API, cited answers `[1][2]`) → **Critic Agent** (independent sentence-level groundedness scoring + citation validation). Low-confidence answers are auto-flagged for human review.

**Stack:** `Gradio` · `sentence-transformers` · `FAISS` · `Hugging Face Inference API` · `PyPDF`
**Why it matters:** Shows the orchestrator / specialist / critic pattern used in production multi-agent systems — not just retrieve-and-generate.

🔗 [Live Demo](https://huggingface.co/spaces/Faraz618/ComplianceRAG) · [Code](https://github.com/Faraz6180/ComplianceRAG)

---

### 🏆 [AdvancedLeadsGeneration-AI](https://github.com/Faraz6180/AdvancedLeadsGeneration-AI) — IBM Granite Hackathon **Winner**
> Two AI agents argue about your leads. The one that wins is the one grounded in your historical deals.

**The problem:** CRM lead-scoring uses static rules and ignores negotiation nuance.

**The system:** Multi-agent debate architecture — one agent advocates for the lead, another surfaces risks. A reconciliation layer scores against historical deal data. Integrated with IBM Watson AI on IBM Granite models.

**Stack:** `Next.js` · `FastAPI` · `IBM Watson AI` · `IBM Granite`
**Why it matters:** Ships against a judged bar under time pressure. Team **PolyEns won** the Generative AI Hackathon with IBM Granite.

🔗 [Hackathon Page & Demo](https://lablab.ai/ai-hackathons/generative-ai-hackathon-with-ibm-granite/polyens)

---

### 🎯 [HireMind-AI](https://github.com/Faraz6180/HireMind-AI) — LLM-Powered Hiring Copilot
> Multi-feature product, not a single-endpoint demo.

**The problem:** Candidates optimize resumes blind — no visibility into ATS logic or multi-role comparison.

**The system:** 8 integrated surfaces — multi-JD analysis, ATS scoring engine (skills % + keyword % + experience alignment), skill-gap detection, resume optimizer, cover-letter generator, interview prep, application tracker, career chat.

**Stack:** `Streamlit` · `Groq API (LLaMA 3.1)` · `JSON persistence` · `Hugging Face Spaces`
**Why it matters:** Demonstrates end-to-end product scoping — not "here's a chatbot," but "here's a career workflow."

🔗 [Live Demo](https://huggingface.co/spaces/Faraz618/HireMind-AI) · [Code](https://github.com/Faraz6180/HireMind-AI)

---

## 🧠 Engineering Philosophy

- **Ship fast, evaluate honestly.** Every RAG I build gets a groundedness check. Every agent gets a critic.
- **Retrieval quality > prompt cleverness.** Most "prompt engineering" problems are actually retrieval problems.
- **Live demo or it didn't happen.** 8 of my projects have public Hugging Face Spaces you can break right now.
- **I only list what I've built.** If a stack is on this page, there's a repo behind it.

---

## 🏅 Hackathon Track Record

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

**Full profile:** [lablab.ai/u/@Faraz_Mubeen](https://lablab.ai/u/@Faraz_Mubeen) — 15 events, 11 submissions.

---

## 🎓 Teaching & Recognition

- **Stanford University — Code in Place** · Section Leader (2025). Selected as 1 of 100 from 900+ global applicants. Led weekly live Python sessions for a global beginner cohort.
- **AlgoVerse Research Program (EOE.ai × Omdena)** · Accepted with 45% merit scholarship. Contributed to RAG / LangChain / Hugging Face research prototypes.
- **Founder Institute Pakistan** · Cohort 2025 (health-informatics track, KnullAI).

---

## 🛠️ Stack (only what I've shipped with)

**Languages** · Python · SQL · TypeScript
**LLMs & APIs** · Groq (LLaMA 3, 3.1, 3.3 70B) · IBM Granite · IBM Watson · Hugging Face Inference API · OpenAI API
**RAG / Vector** · FAISS · sentence-transformers (`all-MiniLM-L6-v2`) · LangChain · PyPDF
**Agents** · Multi-agent debate patterns · Critic/verifier agents · CrewAI (Agentica)
**Backend** · FastAPI · REST APIs
**Frontend / Demo** · Streamlit · Gradio · Next.js
**Deployment** · Hugging Face Spaces · Streamlit Cloud

---

## 📈 GitHub Stats

<div align="center">

<img src="https://github-stats-extended.vercel.app/api?username=Faraz6180&show_icons=true&theme=tokyonight&hide_border=true" alt="Faraz's GitHub Stats" />

<img src="https://github-stats-extended.vercel.app/api/top-langs/?username=Faraz6180&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top Languages" />

<img src="https://streak-stats.demolab.com/?user=Faraz6180&theme=tokyonight&hide_border=true" alt="GitHub Streak" />

</div>

---

## 📬 Contact

- 📧 **Email:** faraz.outreach8@gmail.com
- 💼 **LinkedIn:** [linkedin.com/in/farazmubeenhaider](https://linkedin.com/in/farazmubeenhaider)
- 🤗 **Hugging Face:** [huggingface.co/Faraz618](https://huggingface.co/Faraz618)
- 🧪 **Hackathons:** [lablab.ai/u/@Faraz_Mubeen](https://lablab.ai/u/@Faraz_Mubeen)
- ✍️ **Writing:** [medium.com/@farazmubeenhaider902](https://medium.com/@farazmubeenhaider902)

<div align="center">
<i>Currently open to remote Applied AI / LLM / GenAI Engineer roles.</i>
</div>
