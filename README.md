# Omar Kamali

Building multilingual LLMs, data systems, and agentic tooling with a bias toward low‑resource languages and big lab-style training with scruffy resources.

- Founder of Omneity Labs, independent GenAI R&D lab for low‑resource languages, cultural alignment and sovereign Gen AI stack development
- Focus: pretraining data pipelines, LLM training curricula, instruction residuals, hybrid search, and multi‑provider LLM infra
- Values: pragmatic engineering, reproducible research, and tools that make real systems easier to build

---

## TL;DR – Start here

If you are new here, these are the best entry points:

- **Universal LLM client:** [`borgllm`](https://github.com/omarkamali/borgllm) – drop‑in LangChain‑compatible client for 20+ providers with API key rotation and rate‑limit handling.
- **Wikipedia pretraining data:** [`wikisets`](https://github.com/omarkamali/wikisets) + [`wikipedia-monthly`](https://huggingface.co/datasets/omarkamali/wikipedia-monthly) – fresh monthly multilingual Wikipedia dumps and a flexible dataset builder.
- **Instruction residuals / task arithmetic:** [`residuals`](https://github.com/omarkamali/residuals) – small, focused library for task vectors and efficient continuous pretraining workflows.
- **Hybrid search engine:** [`semango`](https://github.com/omarkamali/semango) – lexical + semantic search (BM25 + vectors) with an HTTP API, MCP server, and search UI.
- **GPU monitoring:** [`picomon`](https://github.com/omarkamali/picomon) – minimal curses dashboard for AMD GPU monitoring.

Everything else tends to plug into one of these pillars: data, training, or serving.

---

## What I work on

- **Multilingual & low‑resource LLMs.** From data acquisition and cleaning to curriculum learning, instruction tuning, and task vectors – with a focus on languages often ignored by big tech.
- **Data systems for pretraining.** Large‑scale text pipelines, monthly‑updated Wikipedia dumps, and tools for querying terabyte‑scale corpora without fully downloading them.
- **Agentic & production tooling.** Universal LLM routers, hybrid search engines, and small utilities that make real‑world deployments less painful.

If you are building something in this space and want to collaborate, open an issue on the relevant repo or reach out via the links at the end.

---

## Projects by area

### 1. LLM training, curricula, and task vectors

- **[`craft`](https://github.com/omarkamali/craft)** – Contrastive Representation Aware Fine‑Tuning toolkit for representation‑sensitive LLM finetuning experiments.
- **[`curriculus`](https://github.com/omarkamali/curriculus)** – Progressive curriculum learning for LLM training with fine‑grained schedule and difficulty control.
- **[`residuals`](https://github.com/omarkamali/residuals)** – Lightweight library for instruction residuals / task vectors, aimed at efficient continuous pretraining and task arithmetic workflows.

Use these if you care about shaping *how* a model learns (curriculum) and *what* gets injected post‑hoc (task vectors, residuals).

---

### 2. Data & pretraining pipelines

- **[`wikisets`](https://github.com/omarkamali/wikisets)** – Flexible Wikipedia dataset builder with language‑aware sampling and pretraining‑oriented splits, built on top of the monthly Wikipedia dumps.
- **[`wikipedia-monthly`](https://huggingface.co/datasets/omarkamali/wikipedia-monthly)** – Fresh, cleaned Wikipedia dumps for 300+ languages, updated monthly and ready to load via Hugging Face Datasets.
- **[`hypersets`](https://github.com/omarkamali/hypersets)** – Query huge datasets with simple SQL using DuckDB; work with terabyte‑scale Hugging Face datasets without fully downloading them.
- **[`unscript`](https://github.com/omarkamali/unscript)** – Script‑aware text cleaning for NLP and training, with attention to multilingual and multi‑script corpora.
- **[`vocabulous`](https://github.com/omarkamali/vocabulous)** – Bootstrapping language detection from noisy and ambiguous data, useful for messy multilingual sources.

If you are assembling a multilingual or low‑resource pretraining corpus, this is the stack to look at first.

---

### 3. LLM infrastructure, agents, and search

- **[`borgllm`](https://github.com/omarkamali/borgllm)** – Zero‑config universal LLM client with support for many providers, API key rotation, rate‑limit management, and LangChain compatibility.
- **[`semango`](https://github.com/omarkamali/semango)** – Hybrid search engine combining BM25 and vector search, with an HTTP API, MCP server, and an embedded search UI for quick experiments.
- **Omneity Labs API (external)** – Sovereign Gen AI platform serving Multilingual LLMs, embeddings, translation, and transliteration for low‑resource languages, powering production systems for languages like Moroccan Arabic.

These are the right tools if you are wiring LLMs into applications, need routing across providers, or want search that actually bridges lexical and semantic retrieval.

---

### 4. Monitoring, utilities, and misc

- **[`picomon`](https://github.com/omarkamali/picomon)** – Minimal terminal dashboard for monitoring AMD GPUs via `amd-smi`, ideal for small GPU boxes or home labs.
- **Other small utilities** – This account also contains smaller experiments and tooling prototypes, chat templates etc; expect pragmatic code focused on solving a specific pain point rather than polished frameworks.

If you are running AMD‑based training or experimentation setups, picomon is usually the quickest win.

---

## Writing, talks, and where to find me

- Website: https://omarkamali.com
- Omneity Labs: https://omneitylabs.com
- Hugging Face (datasets, releases): https://huggingface.co/omarkamali
- X (short updates, threads): https://x.com/OmarKamali

If you are working on multilingual LLMs, low‑resource NLP, or agentic systems and want to compare notes, you are very welcome to reach out.
