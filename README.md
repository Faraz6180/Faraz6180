# Faraz Mubeen Haider

**Software Engineer | Python Backend & Data Systems | Applied AI**

I build Python applications that connect data processing, APIs, and language-model components. I care about what happens beyond the happy path: validation, failure handling, reproducibility, and honest reporting of limitations.

Based in Pakistan. Open to remote and international software engineering roles.

## Selected projects

Most of these are prototypes and learning projects. Each entry says what is in it and what it does not have yet.

### SafeLite: planner, safety check, and executor as separate stages

A research prototype that splits an LLM-driven task pipeline into independent parts (planning, safety checking, execution, evaluation) so each can be tested on its own.

- **What to inspect:** separate packages for the planner, safety checks, executor, and experiment runner; a simulator; evaluation metrics; swappable LLM providers (Groq, Hugging Face, OpenRouter, and a mock provider for offline runs).
- **Safety checks:** plans that reference unknown objects, use invalid or duplicate actions, or target out-of-bounds locations are rejected, and rejected plans can go through a replanning step.
- **Status:** unit tests exist for the planner, safety guard, executor, providers, and self-correction. Several are being updated to match the current API, so the suite does not pass yet. This is a research prototype and makes no formal safety guarantees.

[Repository](https://github.com/Faraz6180/SafeLite)

### data-quality-pipeline: anomaly flagging for tabular data

Takes a CSV, reports data-quality issues, flags anomalous records, and writes a cleaned file, a flagged-records file, and a text report.

- **How it works:** missing-value and duplicate checks with median/mode imputation, then Isolation Forest combined with per-column z-scores. A record is HIGH risk when both methods flag it, MEDIUM when one does, and CLEAN otherwise. Flags come with rule-based plain-English explanations.
- **What to try:** the Gradio demo, using the bundled 50-row synthetic transactions file with planted anomalies.
- **Limits:** a single-file app. It has been run only on the synthetic sample, has no automated tests, and its detection is unsupervised and unevaluated on real data.

[Repository](https://github.com/Faraz6180/data-quality-pipeline) · [Demo and source (Hugging Face Space)](https://huggingface.co/spaces/Faraz618/data-quality-pipeline)

### ComplianceRAG: retrieval with an answer-checking step

A small retrieval-augmented generation app that checks its own answers. It retrieves passages from an uploaded .txt or .pdf file (FAISS and sentence-transformers), generates a cited answer through the Hugging Face Inference API, then scores how well the answer is supported by the retrieved text. Low-scoring answers are flagged for review next to the source passages.

- **What to try:** ask a question the document does not cover and watch the confidence flag drop.
- **Limits:** the groundedness score is sentence-level embedding similarity and has not been validated against labelled data. It indexes one document at a time and has no automated tests. It is a demonstration of the checking idea, not a guarantee of factual correctness.

[Repository](https://github.com/Faraz6180/ComplianceRAG) · [Demo and source (Hugging Face Space)](https://huggingface.co/spaces/Faraz618/ComplianceRAG)

### Other work

- **HireMind-AI:** a Streamlit app that uses an LLM (Groq) to compare a resume with job descriptions, estimate keyword and skill match, and draft improvements. Storage is a local JSON file and there are no automated tests. The match scores are heuristic estimates. [Repository](https://github.com/Faraz6180/HireMind-AI) · [Demo](https://huggingface.co/spaces/Faraz618/HireMind-AI)
- **Hackathons:** I have built prototypes in LabLab.ai hackathons. One example is AdvancedLeadsGeneration-AI, a multi-agent lead-qualification prototype built with Team PolyEns for the Generative AI Hackathon with IBM Granite (Next.js, FastAPI, IBM Watson). See the [project page](https://lablab.ai/ai-hackathons/generative-ai-hackathon-with-ibm-granite/polyens) and my [LabLab profile](https://lablab.ai/u/@Faraz_Mubeen).

## Technologies

- **Used in the projects above:** Python, Pandas, scikit-learn, Pydantic, pytest, Gradio, Streamlit, FAISS, sentence-transformers, Groq API, Hugging Face Inference API, LangChain, MuJoCo and MetaWorld.
- **Used in a team hackathon project:** FastAPI, Next.js, TypeScript, IBM Watson.
- **Used outside these public repositories:** SQL, PostgreSQL, SQLAlchemy.

## How I work

- Make behaviour inspectable: readable code, clear interfaces, runnable setup.
- Treat failure as part of the design: invalid input, unavailable dependencies, and uncertain model output need deliberate handling.
- Test more than the happy path, and keep a working demo separate from evidence that something is correct.
- Say what is implemented, what is tested, and what is still a limitation.

## Working toward

Stronger Python backend and API engineering, data pipelines and database-backed systems, testing and CI, and deployment and observability.

## Community

- Stanford Code in Place: Section Leader, supporting learners in an introductory Python course.
- Founder Institute Pakistan: cohort participation.

## Contact

- Email: [faraz.outreach8@gmail.com](mailto:faraz.outreach8@gmail.com)
- [LinkedIn](https://www.linkedin.com/in/farazmubeenhaider/)
- [GitHub](https://github.com/Faraz6180)
- [Hugging Face](https://huggingface.co/Faraz618)
- [LabLab.ai](https://lablab.ai/u/@Faraz_Mubeen)
- [Medium](https://medium.com/@farazmubeenhaider902)
