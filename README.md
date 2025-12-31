# Building AI that speaks every language 🌎🌍🌏

It's a-me, Omario! I build infrastructure for the next 3 billion AI users and developers. Not the ones in Silicon Valley, but the ones whose languages are still called "low-resource" like it’s their problem and a sealed fate.

Founder of **[Omneity Labs](https://omneitylabs.com)**, an independent GenAI R&D lab leveraging limited compute to drive innovation and build sovereign AI stacks for cultures the big players ignore.

### The stack

**Low-Resource Language Data**
- **[wikilangs.org](https://github.com/wikilangs/wikilangs)** - Pretrained NLP models for 340+ Wikipedia languages, no GPU needed
- **[wikipedia-monthly](https://huggingface.co/datasets/omarkamali/wikipedia-monthly)** - Fresh Wikipedia dumps in 340+ languages, updated monthly
- **[wikisets](https://github.com/omarkamali/wikisets)** - Flexible Wikipedia dataset builder for sampling and preprocessing

**NLP Tooling**
- **[vocabulous](https://pypi.org/project/vocabulous)** - Language detection that works on messy, mislabeled data
- **[unscript](https://github.com/omarkamali/unscript)** - Script-aware text cleaning for 340+ languages
- **[babelvec](https://github.com/omarkamali/babelvec)** - CPU-friendly sentence embeddings with multilingual alignment

**LLM Training Experiments**
- **[CRAFT](https://github.com/omarkamali/craft)** - Contrastive learning framework for multilingual LLM alignment
- **[residuals](https://pypi.org/project/residuals)** - Task vectors for continuous LLM pretraining without retraining from scratch
- **[curriculus](https://github.com/omarkamali/curriculus)** - Curriculum learning for training efficiency (3.5% gains)

**Dev Tooling**
- **[borgllm](https://github.com/omarkamali/borgllm)** - Zero-config LLM router for 20+ providers, handles key rotation and rate limits
- **[hypersets](https://github.com/omarkamali/hypersets)** - Query massive HF datasets with DuckDB instead of loading into memory
- **[zippy-data](https://github.com/zippy-data/zippy)** - Human-readable document store (JSONLs in a zip), 4M+ writes/sec in Rust
- **[prepress](https://github.com/omneity-labs/prepress)** - Polyglot release management for Python, Rust, Node.js projects

**Operations**
- **[picomon](https://github.com/omarkamali/picomon)** - GPU monitoring for AMD, NVIDIA, and Apple Silicon


### Let's talk

- **Building in MENA?** Let's compare notes on cultural alignment
- **Have GPUs?** Omneity Labs is always hungry for compute partners
- **Interested in multilingual AI?** Come talk about bootstrapping NLP for 340+ languages
- **Want AI trained for your domain?** I build custom LLMs and agentic systems that drive real bespoke software

[Blog](https://omarkamali.com) | [Twitter](https://x.com/OmarKamali) | [Hugging Face](https://huggingface.com/OmarKamali) | **omar@omneitylabs.com**

***

**P.S.** Most tools exist because I hit a wall building [Sawalni](https://sawalni.com) (first LLM for Moroccan Darija in arabic and latin scripts) or optimizing GPU usage while running experiments. Declarative beats imperative, but convention over configuration as the best tools are the ones you can `pip install` and simply forget.
