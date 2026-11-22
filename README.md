# AI Engineering Learning Roadmap
 
My structured path to learning **AI Engineering**: understanding how modern AI models work from the inside, building applications on top of them, and running them in production.
 
> **AI Engineering = Understanding the model + Building on top of the model + Running the model in production.**
 
**Started:** November 2026 · **Status:** In progress
 
---
 
## Why This Roadmap
 
I'm an ECE student with a hardware + software background. I want to go beyond calling LLM APIs and learn the fundamentals underneath: tokenization, attention, fine-tuning, retrieval, agents, inference, evaluation, and deployment.

<div align="center">
<img src="https://media1.tenor.com/m/SvOqyNeF7ZwAAAAC/squirtle-race.gif" alt="squirtle determined" width="300" />
</div>
 
## Primary Curriculum
 
[**AI Engineering Course** by Amit Shekhar (Outcome School)](https://github.com/amitshekhariitbhu/ai-engineering-course): free, 18 modules, 146+ lessons, followed in order.
 
## Progress Tracker
 
### Foundations
- [ ] **Module 0:** Must Know (LLM, RAG, MCP, Agent, Fine-tuning, Quantization)
- [ ] **Module 1:** Machine Learning Foundations: supervised/unsupervised/RL, loss functions, regularization, precision and recall
- [ ] **Module 2:** Deep Learning and Neural Networks: gradient descent, backpropagation, cross-entropy, dropout, normalization, RNNs, PyTorch, TensorFlow
### How LLMs Work
- [ ] **Module 3:** Generative AI and the Transformer: tokenization, BPE, embeddings, self-attention, Q/K/V math, multi-head attention, causal masking, RoPE, feed-forward networks
- [ ] **Module 4:** How LLMs Generate Text: temperature, top-k/top-p sampling, stop tokens, token streaming, lost-in-the-middle
- [ ] **Module 5:** Modern LLM Architecture: Mixture of Experts, Grouped Query Attention, sliding window attention, attention sinks, Flash Attention, DeepSeek-V4
- [ ] **Module 6:** Types of Language Models: SLMs, Large Reasoning Models, Recursive LMs, Diffusion LMs, System One models
### Adapting Models
- [ ] **Module 7:** Training, Fine-Tuning, and Alignment: fine-tuning, LoRA, prefix tuning, distillation, RLHF, InstructGPT, PPO, DPO, GRPO
- [ ] **Module 8:** Prompt and Context Engineering: chain-of-thought, prompt chaining, prompt caching, context compaction
### Building Applications
- [ ] **Module 9:** Vector Search and RAG: vector databases, ANN, hybrid search, rerankers, ColBERT, chunking, HyDE, caching, Agentic RAG, GraphRAG, Vectorless RAG
- [ ] **Module 10:** AI Agents and Agentic Systems: function calling, agent loop, ReAct, Plan-and-Execute, Reflection, memory, MCP, Agent Skills, multi-agent systems, orchestration, computer-use agents
- [ ] **Module 11:** Agentic Engineering and Frameworks: LangChain, LangGraph, harness/loop/graph engineering
### Production
- [ ] **Module 12:** LLM Inference Engineering: prefill vs decode, KV cache, paged attention, continuous batching, speculative decoding, quantization, GGUF, llama.cpp, vLLM
- [ ] **Module 13:** Evaluation and Observability: LLM-as-a-judge, agent evaluation, observability
- [ ] **Module 14:** AI Safety and Security: guardrails, prompt injection, watermarking
- [ ] **Module 15:** Multimodal AI and Generative Models: Vision Transformers, diffusion models, GANs, VAEs
- [ ] **Module 16:** AI Infrastructure and System Design: GPUs, CUDA kernels, TPUs, cloud vs on-device, LLM routing, system design
- [ ] **Module 17:** Frontier Ideas in AI: JEPA, world models
- [ ] **Module 18:** AI Engineering Interview Preparation
## Hands-On Practice
 
Reading is not enough. After the conceptual modules, I'll build alongside:
 
- [AI Engineering Full Course (8+ hours, 10 projects)](https://www.youtube.com/watch?v=WIW5hN-hApQ) on LLMs, RAG, LangChain, LangGraph, and agents, used as a build-along for projects rather than as the source of fundamentals.
### My Projects
 
| Project | Concepts Applied | Status |
| ------- | ---------------- | ------ |
| _TBD_   | _TBD_            | Planned |
 
## Learning Rules
 
1. Follow modules in order; don't skip Modules 1 and 2.
2. After each module, explain the concepts in my own words.
3. Implement what I learn in code wherever possible (PyTorch, Python).
4. Log notes and code in this repository.
## Repository Structure
 
```
.
├── README.md
├── notes/        # per-module notes
└── projects/     # hands-on implementations
```
 
## Resources
 
- [AI Engineering Course (Outcome School)](https://github.com/amitshekhariitbhu/ai-engineering-course)
- [AI Engineering Full Course (YouTube)](https://www.youtube.com/watch?v=WIW5hN-hApQ)
---
 
_Maintained by [Naimur](https://github.com/Naim-ECE)._
 
