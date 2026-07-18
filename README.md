## Faraz Mubeen Haider

**AI Engineer** — Production RAG Systems · LLM Orchestration · Scalable Python Backends

I build AI systems that solve real business problems, not demos. Currently designing RAG pipelines and AI agent workflows at ClinicOps AI (Doha), serving GCC outpatient clinics. Previously shipped an AI automation SaaS MVP in 12 weeks at 1337 Ventures (KL) — zero production incidents at launch.

**Remote-first engineer based in Pakistan.** Available 6 PM – 2 AM PKT for US timezone overlap (9 AM – 5 PM EST). Set up for seamless contractor payments via Deel/Remote.com.

📫 faraz.outreach8@gmail.com · [LinkedIn](https://www.linkedin.com/in/fm618) · [Portfolio](https://faraz-mubeen.vercel.app/)

---

## 🏭 Production Systems

### clinicops-rag-platform *(Private — architecture shared below)*
Multi-tenant RAG system for healthcare appointment automation.
- **Scale:** 50,000+ documents indexed, 1,000+ daily queries
- **Latency:** p50 &lt; 200ms, p95 &lt; 800ms, p99 &lt; 1.2s
- **Cost:** $0.08 per 1K queries via model routing and caching
- **Eval:** RAGAS faithfulness 0.84, context recall 0.91
- **Stack:** Python · FastAPI · LangChain · pgvector · PostgreSQL · Redis · Docker · AWS EC2 · Langfuse

**Architecture:**
