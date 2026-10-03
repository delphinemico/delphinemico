**Principal Applied AI Engineer | Agentic AI, LLM & Production ML Systems**

I am an Applied AI engineer and scientist with a Ph.D. in Applied Mathematics and 13+ years of experience building production AI/ML systems across Generative AI, machine learning, optimization, and large-scale applied engineering systems, including work at Microsoft and Intel.

My current technical focus is on building reliable LLM, Generative AI, and Agentic AI systems - from model architecture, pretraining, and fine-tuning in PyTorch to retrieval, orchestration, inference and serving, evaluation, GPU-aware performance analysis, production reliability, and system optimization.

## Current Focus

- **Agentic AI systems** - stateful workflows, deterministic routing, bounded agent loops, critique/revision, human approval, checkpointing, and safe side effects
- **RAG and retrieval** - hybrid semantic + lexical retrieval, grounding, citation validation, and retrieval evaluation
- **LLM evaluation** - component, trajectory, and end-to-end evaluation; quality, latency, token, and cost tradeoffs
- **LLM training and adaptation** - PyTorch, transformer architecture, pretraining, fine-tuning
- **LLM inference and serving** - vLLM, SGLang, TensorRT-LLM, prefill and decode characterization, KV and prefix caching, latency-throughput tradeoffs, and GPU runtime analysis with NVIDIA Nsight Systems
- **Production AI/ML systems** - typed interfaces, validation, observability, failure handling, idempotency, and system optimization

## Selected Work

### Retention Agent - Production-Oriented Agentic AI System

A bounded, checkpointed Agentic AI workflow for customer-retention decisions in a synthetic banking domain, combining deterministic application control with LLM judgment.

Built with LangGraph, hybrid search (dense semantic embeddings (MiniLM) with sparse keyword matching (TF-IDF)), structured outputs, bounded critique/revision, human approval, resumable checkpointing, idempotency-aware side effects, and end-to-end evaluation with reproducible latency, cost, token, and routing benchmarks.

The benchmark suite includes 100 end-to-end trajectories and evaluates routing strategies across quality, latency, token usage, and cost. In the high-risk benchmark, routing planning to a smaller model reduced average cost per run by about 9% without degrading the observed outcome rate relative to the all-large configuration.

[View Retention Agent repository](https://github.com/delphinemico/agentic-ai-retention-agent)

---

### Building a Large Language Model from Scratch with PyTorch

End-to-end PyTorch implementation of a decoder-only GPT-style language model, including tokenization, masked multi-head attention, transformer blocks, pretraining, autoregressive generation, pretrained-weight loading, classification and instruction fine-tuning, and distributed training with torchrun on two NVIDIA L4 GPUs.

[View repository](https://github.com/delphinemico/build-llm-from-scratch-pytorch)

---

### LLM Inference Performance - Serving Engines and GPU Runtime Analysis

Controlled single-GPU study of LLM inference behavior on an NVIDIA L40S using Qwen2.5-7B-Instruct, covering vLLM concurrency, prefill, decode, and prefix caching; workload-controlled comparison of vLLM, SGLang, and TensorRT-LLM; and GPU runtime profiling with NVIDIA Nsight Systems.

Includes reproducible benchmark scripts, raw results, and evidence-bounded analysis connecting application-level latency and throughput to serving-engine workload fit and the distinct GPU execution patterns of prefill and autoregressive decode.

[View LLM Inference Performance repository](https://github.com/delphinemico/llm-inference-performance)

---

## Beyond Tech

Avid traveler and language enthusiast - I speak English, French, Spanish, and Portuguese, and have B2 proficiency in German.
