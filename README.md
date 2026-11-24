![Mohammed Darrige visual identity](assets/profile-banner.png)

# Mohammed Darrige

Applied AI and Data Engineer building Turkish NLP and RAG services, LoRA image adapters, and deterministic inference systems.

<p align="center">
  <img src="assets/brand-stripe.png" alt="Mohammed Darrige brand mark" width="720" />
</p>

## About

I work on applied NLP, retrieval systems, and diffusion fine-tuning. I speak Arabic natively, Turkish at a professional level, and English at B2.

My recent projects live at [darrige.tech](https://darrige.tech), and my notebooks are on [Kaggle](https://www.kaggle.com/muhammedderric).

## Stack

![Python](assets/badges/python.svg)
![PyTorch](assets/badges/pytorch.svg)
![FastAPI](assets/badges/fastapi.svg)
![Docker](assets/badges/docker.svg)
![TypeScript](assets/badges/typescript.svg)
![Next.js](assets/badges/nextjs.svg)

## Selected work

### [Turkish Customer Support Voice and Text RAG](https://github.com/Mohammed-Darrige/turkish-customer-nlu-rag)

A Turkish customer support RAG service backed by PostgreSQL 16 (`pgvector` HNSW + Turkish `tsvector` GIN SQL Hybrid RRF), Contextual Retrieval over 213 chunks of Turkish Consumer Law (6502 & regulations), a `mmarco-mMiniLMv2` cross-encoder reranker, dev-calibrated logit abstention, and numeric + `[doc_id:Madde N]` citation grounding.

On a frozen 120-query held-out benchmark, `hybrid_rerank` reaches 97.1% Recall@5 (82.9% Hit@1) on Turkish queries and 96.0% out-of-scope abstention recall (4.0% False Answer Rate), with cross-lingual AR/EN->TR queries tracked separately as a zero-shot ablation. Includes a Web Speech API voice UI, FastAPI observability, Docker Compose, and live Postgres GitHub Actions CI.

### [Neural Style Transfer](https://github.com/Mohammed-Darrige/neural-style-transfer)

Stable Diffusion 1.5 image-to-image and text-to-image style transfer using three rank-4 UNet LoRA adapters for Cubism, Post-Impressionism, and Ukiyo-e. Each adapter is 3.08 MiB and tracked in a SHA-256 manifest alongside its Colab training provenance.

Live demo at [darrige.tech/projects/neural-style-lab](https://darrige.tech/projects/neural-style-lab).

### [Deterministic Bayesian Akinator v4](https://github.com/Mohammed-Darrige/ai-akinator)

An animal guessing engine in TypeScript with 110 targets, 90 questions in Turkish, English, and Arabic, strict direct-answer consistency, and two-step information-gain lookahead. No LLM runs during gameplay turns.

Across 330 simulated runs on the built-in catalogue, it solves 330/330 targets in 7.11 questions on average (4.96 ms mean selector time). Live demo at [darrige.tech/projects/ai-akinator](https://darrige.tech/projects/ai-akinator).

### [Artoria Dataset](https://www.kaggle.com/datasets/h7alasaleh/artoria-dataset)

Curated art-movement dataset used for the LoRA style transfer training runs.

## Contact

[![Portfolio](assets/badges/portfolio.svg)](https://darrige.tech)
[![LinkedIn](assets/badges/linkedin.svg)](https://www.linkedin.com/in/mohammed-darrige-48b056331/)
[![Kaggle](assets/badges/kaggle.svg)](https://www.kaggle.com/muhammedderric)
[![Email](assets/badges/email.svg)](mailto:derricmuhammed@gmail.com)
