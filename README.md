**Principal Applied AI Engineer | Agentic AI, LLM & Production ML Systems**

I am an Applied AI engineer and Scientist with a Ph.D. in Applied Mathematics and 13 years of experience building production AI/ML systems across Generative AI, machine learning, optimization, and large-scale applied engineering.

My current technical focus is on building reliable LLM, Generative AI, and Agentic AI systems - from model architecture, pretraining, and fine-tuning in PyTorch to retrieval, orchestration, inference and serving, evaluation, GPU-aware performance analysis, production reliability, and system optimization.

## Current Focus

- **Agentic AI systems** - stateful workflows, deterministic routing, bounded agent loops, critique/revision, human approval, checkpointing, and safe side effects
- **RAG and retrieval** - hybrid semantic + lexical retrieval, grounding, citation validation, and retrieval evaluation
- **LLM evaluation** - component, trajectory, and end-to-end evaluation; quality, latency, token, and cost tradeoffs
- **LLM training and adaptation** - PyTorch, transformer architecture, pretraining, fine-tuning
- **LLM inference and serving** - vLLM benchmarking, prefill and decode characterization, batching, KV and prefix caching, latency-throughput tradeoffs, and GPU-aware performance analysis
- **Production AI/ML systems** - typed interfaces, validation, observability, failure handling, idempotency, and system optimization

## Selected Work

### Retention Agent - Production-Oriented Agentic AI System

A bounded, checkpointed Agentic AI workflow for customer-retention decisions in a synthetic banking domain, combining deterministic application control with LLM judgment.

Built with LangGraph, hybrid search (dense semantic embeddings (MiniLM) with sparse keyword matching (TF-IDF)), structured outputs, bounded critique/revision, human approval, resumable checkpointing, idempotency-aware side effects, and end-to-end evaluation with reproducible latency, cost, token, and routing benchmarks.

The benchmark suite includes 100 end-to-end trajectories and evaluates routing strategies across quality, latency, token usage, and cost. In the high-risk benchmark, routing planning to a smaller model reduced average cost per run by about 9% without degrading the observed outcome rate relative to the all-large configuration.

[View Retention Agent repository](https://github.com/delphinemico/agentic-ai-retention-agent)

---

### Building a Large Language Model from Scratch with PyTorch

Hands-on implementation of a GPT-style language model covering tokenization, attention, transformer blocks, pretraining, text generation, classification fine-tuning, and instruction fine-tuning.

[View repository](https://github.com/delphinemico/build-llm-from-scratch-pytorch)

---

### LLM Inference Performance - Single-GPU vLLM Benchmarking

Controlled vLLM performance benchmarking on an NVIDIA L40S using Qwen2.5-7B-Instruct, covering concurrency scaling, prefill and decode behavior, automatic prefix caching, and latency-throughput tradeoffs.

Includes reproducible benchmark scripts, raw results, figures, and engineering analysis. In the reported workloads, output-token throughput scaled from 49.0 to 567.6 tokens/s, while a prewarmed prefix-cache condition reduced median time to first token by 64.5%.

[View LLM Inference Performance repository](https://github.com/delphinemico/llm-inference-performance)

---

## Beyond Tech

Avid traveler and language enthusiast - I speak English, French, Spanish, and Portuguese, and have B2 proficiency in German.
