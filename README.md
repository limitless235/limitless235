<div align="center">

# Sahil Seemant

**Software Engineering · Backend & Distributed Systems · Applied AI**

FastAPI · Redis Streams · C++ · Next.js · RAG · Docker

</div>

---

## About

I am a curious and driven software engineer focused on **building backend systems that are reliable, scalable, and production‑ready**.

My work centers on **Backend Engineering**, **Distributed Systems**, and **Applied AI**. I am particularly interested in system reliability—understanding why systems fail (race conditions, memory pressure, isolation) and designing architectures that anticipate these failures through observability and clean design. 

Beyond implementation, I maintain a rigorous foundation in **Data Structures, Algorithms**, and core CS fundamentals like **Object-Oriented Programming, Databases, and Computer Networks**.

---

## Technical Expertise

* **Reliability Engineering:** Expert in designing validation logic, testable backend services, and improving system stability through structured failure analysis and deterministic execution.
* **Distributed Systems:** Hands-on experience with asynchronous task processing using **Redis Streams**, message brokers like **Kafka**, and containerized microservices.
* **Applied AI & RAG:** Architecting local, air-gapped AI pipelines using **llama-cpp** and **LM Studio**, implementing semantic search via **ChromaDB/FAISS**, and enforcing strict prompt engineering to eliminate hallucinations.
* **Backend Performance:** Proficient in high-performance computing with **C++** (bit-level optimizations) and high-concurrency APIs with **FastAPI** and **Asyncpg**.

---

## Engineering Projects

### RAG AI Support System — Asynchronous Intelligence Orchestrator
**Stack:** FastAPI · Redis Streams · Next.js · ChromaDB · FAISS · DuckDB · PostgreSQL · Docker
* **Decoupled Architecture:** Engineered an asynchronous AI worker system using **Redis Streams** as a high-performance message broker to separate long-running inference tasks from the API layer.
* **Production Hardening:** Implemented "Phase 9.4 Hardened" worker features, including **poison-message protection**, idempotency, and graceful degradation for local GGUF models.
* **Analytics Engine:** Integrated **DuckDB** for lightning-fast OLAP queries on periodic data ingestion from PostgreSQL, enabling real-time system performance monitoring.
* **Search Optimization:** Built a hybrid RAG pipeline using **ChromaDB** as the source of truth and **FAISS** for a high-speed derived semantic index.

### HomeBrewed Chess Engine & AI Coach
**Stack:** C++ · Python · FastAPI · Vanilla JS · LM Studio · make
* **C++ Calculation Core:** Built a native engine from scratch utilizing **64-bit Bitboards**, **Zobrist Hashing**, and **Magic Bitboards** for instantaneous attack generation.
* **Deterministic AI Coaching:** Integrated a localized AI coach (Mistral-7B via LM Studio) restricted by optimized system prompts to ONLY relay pure engine facts (Centipawns/Best Moves), preventing hallucinations.
* **Pattern Analysis:** Developed a behavior tracking system in the web GUI that analyzes player blunders and provides real-time tactical feedback via a Python/C++ I/O pipe.
* **Performance Algorithms:** Implemented **Alpha-Beta Pruning** and **Negamax** with **Transposition Tables** to maximize search depth and efficiency.

### Exam Ace — AI-Powered Validation & Reliability Pipeline
**Stack:** React 19 · TypeScript · FastAPI · Supabase (Postgres) · Redis · Render
* **Three-Tier Fallback System:** Engineered a resilient question generation pipeline: local LLM (Phi-3) → Backend SQL Bank → Frontend Local Bank, ensuring 100% availability even offline.
* **Reliability Engineering:** Designed automated validation pipelines that reduced noisy/invalid AI inputs by **40%** and enforced deterministic execution across 100k+ samples.
* **Performance Optimization:** Achieved a **90% reduction** in end-to-end processing latency through workflow profiling and asynchronous database queries with **asyncpg**.
* **Security & Scalability:** Implemented **JWT-based authentication** and **Redis-based rate limiting** to ensure API consistency under concurrent request scenarios.

### WhatsApp Group Chat Analyzer
**Stack:** FastAPI · Python · NLP · Testable Backend Design
* **Performance Throughput:** Developed batch-processing workflows that improved log processing speeds by **3-4x** for large datasets.
* **Defensive Design:** Implemented strict input validation and structured logging that reduced runtime defects and enabled faster root-cause analysis of chat parsing anomalies.

---

## Skills

**Languages**
Python, C/C++, Java, TypeScript, SQL, JavaScript

**Backend & Reliability**
FastAPI, Redis Streams, Kafka, Docker, REST APIs, Automated Testing, Root Cause Analysis

**AI/ML & Data**
RAG (Retrieval-Augmented Generation), ChromaDB, FAISS, DuckDB, llama-cpp, PostgreSQL, NumPy

**CS Foundations**
Data Structures, Algorithms, OOP, Operating Systems, Computer Networks

---

## Certifications

* **Machine Learning Specialization** (DeepLearning.AI) — Focus: Model Evaluation & Error Analysis.
* **IBM Cybersecurity Analyst Professional** — Focus: System Security & Incident Analysis.
