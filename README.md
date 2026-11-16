# Ngo Chi Nghia

**AI Engineer · RAG, AI Agents, NLP & Computer Vision**

Vietnam · Open to relocation and on-site work

[Portfolio](https://chinghia.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/chinghia010804/) · [Email](mailto:chinghia689@gmail.com) · [GitHub](https://github.com/chinghia689)

I build and evaluate AI systems, from retrieval and agent workflows to APIs and deployed applications. My recent work focuses on Vietnamese question answering, source-grounded content generation, and computer vision.

## Highlights

- Co-author of **ERC-RAG**, accepted at **EAI AICON 2026**.
- **FPTU Can Tho Olympic AI 2026:** 1st place in NLP (Aspect-Based Sentiment Analysis) and 4th place in Image Classification at the on-site final; 15 finalists selected from 100+ participants.
- Improved Vietnamese economic QA results to **ROUGE-2 F1 0.68**, **MRR 0.62**, and **NDCG@5 0.83** on a 120K-chunk corpus.

## Experience

**AI Engineer, Generative AI** · ADHIGHTECH (Tien Phong Engineering Technology Co., Ltd.)

Can Tho, Vietnam · March 2026–Present

- Designed energy-distance cluster ranking with LLM relevance filtering for a 120K-chunk Vietnamese economic QA corpus, improving ROUGE-2 F1 from **0.49 to 0.68**; achieved **MRR 0.62** and **NDCG@5 0.83**.
- Deployed the QA pipeline as a FastAPI REST service with Docker Compose on Ubuntu.
- Co-authored the ERC-RAG research, contributing to the idea, implementation, and experiments.

## Selected Projects

### [ERC-RAG](https://github.com/chinghia689/economy_rag_ebd_kmeans_llm_TIEN_PHONG_TT_VL_2026)

Energy-based retrieval clustering for Vietnamese economic question answering. The pipeline retrieves top-40 candidates with multilingual-E5, selects K-Means clusters, ranks them using energy distance, and applies LLM relevance filtering before answer generation.

- Evaluated on 1,000 generated QA pairs over 120,165 VEID chunks.
- Results: **MRR 0.62**, **NDCG@5 0.83**, **ROUGE-2 F1 0.68**, **BLEU-2 0.65**.

### [Agent Newsroom](https://github.com/chinghia689/gen-ytb-short)

Automates football news processing into vertical videos: RSS ingestion, story clustering, source checks, script generation, FFmpeg rendering, and YouTube publishing.

- Built a FastAPI API and React review interface with per-stage latency metrics.
- Added allowlisted HTTPS sources, an independent script review, and uncertainty handling when sources conflict.

### [PolyAqua Agent](https://github.com/chinghia689/AI_polyculture)

AI assistant for shrimp–crab polyculture, combining image-based disease classification and retrieval-augmented treatment guidance.

- YOLOv8n-cls classifier for four disease classes: **84% validation accuracy** and **78% test accuracy**.
- Hybrid multilingual-E5/BM25/RRF retrieval over 4,593 vectors from 13 technical documents, plus pond and dosage calculators.

## Publication

**“ERC-RAG: An Energy-based Retrieval Clustering for RAG in Vietnamese Economy Chatbots.”** Co-author; accepted at **EAI AICON 2026**. Camera-ready version in preparation.

## Skills

- **Languages:** Python, JavaScript, C/C++
- **AI/ML:** PyTorch, TensorFlow, YOLOv8, Hugging Face Transformers, scikit-learn, Sentence Transformers, RAG, prompt engineering
- **LLM & agents:** OpenAI, Google Gemini, Groq, Ollama, LangChain, LangGraph
- **Retrieval:** ChromaDB, BM25, hybrid retrieval, Reciprocal Rank Fusion (RRF)
- **Backend & data:** FastAPI, Pydantic, REST APIs, JWT, OAuth 2.0, SQLite, PostgreSQL
- **Deployment & tools:** Docker, Docker Compose, Git, Ubuntu, Claude Code CLI, OpenAI Codex CLI
- **Languages spoken:** Vietnamese (native), English (VSTEP B1)

## Education

**Nam Can Tho University** · Bachelor of Engineering in Information Technology

GPA **3.44/4.00** · Graduated August 2026
