<div align="center">

# Faraz Mubeen Haider

### Software Engineer · Python Backend · Data Systems · Applied AI

I build Python applications and data workflows, with a focus on understandable architecture, testable behavior, and honest evaluation.

[GitHub](https://github.com/Faraz6180) · [LinkedIn](https://www.linkedin.com/in/farazmubeenhaider/) · [Hugging Face](https://huggingface.co/Faraz618) · [LabLab](https://lablab.ai/u/@Faraz_Mubeen)

</div>

---

## What I Work On

My main interests sit where backend engineering, data processing, and AI-enabled applications meet.

- **Python backend:** APIs, service integration, input validation, and maintainable application structure.
- **Data systems:** data ingestion and cleaning, SQL, relational databases, and repeatable workflows.
- **Applied AI:** retrieval-augmented generation (RAG), document processing, LLM integrations, and multi-step workflows.
- **Engineering quality:** tests, reproducible setup, clear documentation, and deliberate handling of failure cases.

I use projects to explore real implementation choices and make the trade-offs visible. A working demo is a starting point—not proof that a system is production-ready or correct in every case.

## Featured Projects

### [ComplianceRAG](https://github.com/Faraz6180/ComplianceRAG) · [Live demo](https://huggingface.co/spaces/Faraz618/ComplianceRAG)

**Document question answering with a separate answer-checking step.**

A RAG application that retrieves document chunks, generates a cited response, and applies a critic step to estimate support from the retrieved text and check citations. Low-confidence outputs can be flagged for human review.

**Explore:** retrieval and generation boundaries, citations, groundedness scoring, and the limitations of automated answer checking.

`Python` · `FAISS` · `sentence-transformers` · `Hugging Face Inference API` · `Gradio`

> A groundedness score is a signal for review, not a guarantee of factual correctness.

### [data-quality-pipeline](https://github.com/Faraz6180/data-quality-pipeline) · [Live demo](https://huggingface.co/spaces/Faraz618/data-quality-pipeline)

**CSV data-quality checks and anomaly detection.**

A data workflow that checks uploaded tabular data, handles missing values and duplicates, combines Isolation Forest and Z-score signals to flag unusual records, and produces downloadable outputs and explanations.

**Explore:** validation, data cleaning, anomaly detection, risk tiers, and report generation.

`Python` · `Pandas` · `scikit-learn` · `Gradio`

### [AI-powered-Research-Assistant](https://github.com/Faraz6180/AI-powered-Research-Assistant)

**A multi-source research assistant.**

An application that retrieves information from sources including ArXiv, Wikipedia, and web search, then uses an LLM to synthesize a conversational response.

**Explore:** tool integration, retrieval, synthesis, and the difference between a useful summary and a verifiable answer.

`Python` · `LangChain` · `Groq` · `Streamlit`

### [AdvancedLeadsGeneration-AI](https://github.com/Faraz6180/AdvancedLeadsGeneration-AI)

**Multi-agent lead qualification · IBM Granite hackathon winner (Team PolyEns).**

A project exploring how different agent perspectives can assess a lead and feed into a reconciliation step.

[Hackathon project and recognition](https://lablab.ai/ai-hackathons/generative-ai-hackathon-with-ibm-granite/polyens)

`FastAPI` · `Next.js` · `IBM Watson AI` · `IBM Granite`

## Engineering Principles

1. **Make behavior inspectable.** Prefer readable code, clear interfaces, and useful documentation.
2. **Design for failure.** Invalid input, missing evidence, unavailable dependencies, and uncertain model output are part of the problem.
3. **Test beyond the happy path.** A successful demo does not establish reliability across inputs and failure conditions.
4. **Separate implementation from evidence.** A feature in code is different from a feature that has been tested or measured.
5. **Explain trade-offs.** Architecture should follow requirements and constraints—not just fashionable terminology.

## Technologies I Use

| Area | Tools and concepts |
|---|---|
| Languages | Python, SQL, TypeScript |
| Backend | FastAPI, REST APIs |
| Data | PostgreSQL, Pandas, SQLAlchemy |
| Retrieval | FAISS, `sentence-transformers`, document chunking |
| AI applications | LLM APIs, RAG, multi-agent workflows, answer-checking patterns |
| Interfaces | Streamlit, Gradio, Next.js |
| Demos | Hugging Face Spaces |

This list reflects tools used across different projects; it does not imply equal depth or production-scale experience with every tool. Please inspect the linked repositories for implementation details.

## Recognition & Community

- **IBM Granite Generative AI Hackathon — Winner**, as part of Team PolyEns.
- **Stanford Code in Place — Section Leader.**
- **AlgoVerse Research Program** — accepted with a reported 45% merit scholarship.
- **Founder Institute Pakistan** — cohort participation.

More project and hackathon context: [LabLab profile](https://lablab.ai/u/@Faraz_Mubeen).

## Let's Connect

I'm interested in Python/backend engineering, data systems, applied AI, open-source collaboration, and thoughtful engineering discussions.

- **LinkedIn:** [Faraz Mubeen Haider](https://www.linkedin.com/in/farazmubeenhaider/)
- **Hugging Face:** [Faraz618](https://huggingface.co/Faraz618)
- **LabLab:** [Projects and hackathons](https://lablab.ai/u/@Faraz_Mubeen)
- **Technical writing:** [Medium](https://medium.com/@farazmubeen902)
- **Email:** [faraz.outreach8@gmail.com](mailto:faraz.outreach8@gmail.com)

---

<div align="center">

*Build carefully. Verify honestly. Document what matters.*

</div>
