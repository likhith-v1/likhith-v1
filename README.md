# Hi, I'm Likhith 👋

AI/ML engineer-in-training building inference systems from scratch. B.Tech CS (AI & ML), Jain University, Bengaluru — graduating 2027.

I care about understanding systems down to the metal rather than gluing together APIs. That shows up as a preference for local-first, privacy-first, zero-external-dependency engineering — from data prep through inference serving, in industrial environments where data never leaves the perimeter.

## 🔧 Currently building — `inferd`

A from-scratch LLM inference server, and my main portfolio project:

- **QLoRA fine-tuning** pipeline on Qwen3-27B for domain adaptation
- **Speculative decoding** with rejection sampling — draft model distilled via sequence-level KD against the fine-tuned target's own generations
- **Paged KV-cache** implemented via Triton
- **Continuous batching** — benchmarked throughput scaling ~6x from one to eight concurrent users

## 🗂️ Other work

- **Predictive Ghost-Text Daemon (Ideation)** — always-on autocomplete via a resident Unix-socket inference process, sub-100ms latency budget, prefix caching, and shell-history personalization through a fine-tuning pipeline with secrets-scrubbing
- **`prr`** — a self-hosted code-review bot pairing an Ollama model with `ruff`, `mypy`, and `bandit`; results normalized through a typed Pydantic schema, posts inline PR comments on GitHub

## 🧠 Skills

`Python` · `Java` · `SQL` · PyTorch · TensorFlow · scikit-learn · XGBoost · `CUDA` · `Triton` · `MLX` · LoRA/QLoRA · speculative decoding · paged KV-cache · continuous batching · RAG (FAISS/ChromaDB) · FastAPI · `Docker` · `Ollama` · `Jenkins` · `Git`/GitHub Actions

Theory foundation: constrained optimization, KKT conditions, multi-armed bandits.

## 🎯 What I'm looking for

AI/ML engineering internships with a path to full-time — especially roles where inference performance, model serving, or applied ML infrastructure are the actual job, not an afterthought.

## 📫 Reach me

- LinkedIn: [likhith-v](https://www.linkedin.com/in/likhith-v-45230a286/)

---
