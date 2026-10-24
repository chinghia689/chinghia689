# Ngo Chi Nghia

**AI Engineer | GenAI, LLM & RAG** · Can Tho, Vietnam · Open to relocation and on-site work

[Portfolio](https://portfolio-chinghia.vercel.app) · [LinkedIn](https://www.linkedin.com/in/chinghia010804/) · [Email](mailto:chinghia689@gmail.com)

I build and evaluate retrieval-augmented generation systems, with a focus on Vietnamese economic and legal question answering.

## Experience

**AI Engineer Intern (Generative AI)** · ADHIGHTECH (Tien Phong Engineering Technology Co., Ltd.) · Mar–Jul 2026

- Implemented and compared dense, BM25, hybrid, and cluster-based retrieval for Vietnamese economic question answering, including energy-distance cluster ranking and LLM relevance filtering.
- Built a FastAPI REST service and packaged the application with Docker Compose for Ubuntu Linux.

## Selected projects

### ERC-RAG · Vietnamese economic question answering

Retrieval-clustering research using multilingual-E5, top-40 cosine candidates, K-Means with silhouette-based cluster selection, energy-distance ranking, and LLM relevance filtering.

- Reported on 1,000 automatically generated VNEIQAD question-answer pairs over 120,165 VEID chunks: **MRR 0.62**, **NDCG@5 0.83**, **ROUGE-2 F1 0.68**, **BLEU-2 0.65** (GPT-5.0 mini answer generation).
- The project report compares answer-generation scores of BLEU-2 **0.61 → 0.65** and ROUGE-2 F1 **0.49 → 0.68** against an earlier group system using GPT-4o-mini. Because the generation models differ, this is not a controlled model-matched comparison.
- A separate cosine top-5 retrieval run reports MRR **0.7352**, Hit@5 **0.8040**, and NDCG@5 **0.9805**. It is not yet a matched rerun of ERC-RAG; no retrieval-improvement claim is made from these separate runs.

[Repository](https://github.com/chinghia689/economy_rag_ebd_kmeans_llm_TIEN_PHONG_TT_VL_2026) · [Demo](https://vietecochat.site/)

### Vietnamese Legal RAG

Hybrid ChromaDB/BM25 retrieval with a LangGraph workflow, FastAPI, and Docker Compose. The prototype indexes **6 documents** into **1,035 chunks**. In a preliminary 30-question retrieval set, the correct source file and article appeared in top 20 for **27/30 questions (90%)**. This is a retrieval result; answer accuracy has not been evaluated.

[Repository](https://github.com/chinghia689/vietnamese-legal-rag) · [Demo](https://lawchat.me/)

## Publication

**Chi-Nghia Ngo, Anh-Khoi Ngo-Ho, Anh-Khoa Ngo-Ho.** “ERC-RAG: An Energy-based Retrieval Clustering for RAG in Vietnamese Economy Chatbots.” Submitted to **ICEIR 2026**, under review. Contribution: research ideas, implementation, and experiments.

## Award

Finalist, **FPTU Can Tho Olympic AI**, May 2026.

## Skills

- **Programming:** Python
- **LLM & RAG:** OpenAI API, Gemini API, Groq API, RAG, prompt engineering
- **Retrieval:** multilingual-E5, ChromaDB, BM25, hybrid retrieval, Reciprocal Rank Fusion (RRF), K-Means, energy distance
- **Evaluation:** MRR, NDCG@5, ROUGE-2, BLEU-2
- **Frameworks & deployment:** FastAPI, LangChain, LangGraph, Docker, Docker Compose, Ubuntu Linux
- **Tools & data:** Git, GitHub, NumPy, Pandas, Claude Code, OpenAI Codex CLI
- **Languages:** Vietnamese (native), English (VSTEP B1)

## Education

**Nam Can Tho University** · Bachelor of Engineering in Information Technology · GPA **3.44/4.00** · Aug 2026
