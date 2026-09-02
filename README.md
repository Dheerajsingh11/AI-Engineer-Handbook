# The AI Engineer Handbook — *From JVM to LLM*

A self-study roadmap that goes from the absolute basics of AI to advanced, production-grade topics — **120 topics across 21 phases**, each with plain-language explanations, the underlying maths, worked code (Python-first), the different types/variants within each topic, and free resources to learn more. It ends with a full **end-to-end capstone project** that ties every topic together into one real system.

👉 **Start here:** open [`index.html`](index.html) in any browser (or the published site link). Every topic has a **“Deep dive →”** link to its own detailed page, and everything works fully offline.

---

## A note from me

I’ve **recently started learning the basics of AI**. I put this roadmap together — from the attached sources, **using AI** — as the path I’m going to follow myself to cover everything from basics to advanced. I’m sharing it publicly in case it’s useful to anyone else on the same journey, and to get feedback.

## ⚠️ Disclaimer — please read

- This is for **educational purposes** only.
- It was created **with AI assistance**, so it **may not be 100% accurate**, and fast-moving details (model names, hardware, benchmarks, prices) will go out of date over time.
- It is **not** professional, medical, financial, or legal advice.
- **If you’re going through it and find any mistake, a missing topic, or anything unusual — please let me know so I can fix it.** Corrections and suggestions are very welcome (open an issue / leave a comment / message me).

---

## What’s inside

Every topic page runs from **basic (absolute beginner) → advanced (professional)** and includes:

- **Plain-language explanation** — the idea, before any notation.
- **The maths & the algorithm** — derived, not just stated.
- **Worked code** — mostly Python, with the reasoning behind each line.
- **Types/variants** within the topic, and the trade-offs.
- **Exercises** and a curated list of **free resources**.

## How it’s organised — the 21 phases

| Phase | Focus |
|------:|-------|
| 1 | Fundamentals — maths (linear algebra, probability, calculus) + how LLMs work |
| 2 | Python & Data — Python, NumPy/Pandas, classical ML, neural nets, PyTorch, **CUDA/GPU** |
| 3 | The Java AI Stack — prompting, Spring AI, LangChain4j, MCP, fine-tuning |
| 4 | RAG & Vectors — embeddings, vector indexes/DBs, retrieval, RAG evaluation, GraphRAG |
| 5 | Agents & Ops — tool calling, agent architecture, memory, LLMOps, security, structured output |
| 6 | Production — serving & quantisation, multimodal, testing, governance, **AI hardware** |
| 7 | Python AI Frameworks — LangChain/LangGraph, LlamaIndex |
| 8 | Agent Engineering — orchestration, building agents, tools, skills, hooks, planning, multi-agent, eval |
| 9 | Models & Training — LLM APIs, open models, Hugging Face, reasoning models, training, **distributed training** |
| 10 | Cloud, Deploy & MLOps |
| 11 | AI Foundations — what AI is, its history, the ecosystem |
| 12 | Deep Learning Architectures — CNNs, RNNs, autoencoders, GANs, diffusion, GNNs |
| 13 | Natural Language Processing |
| 14 | Classical ML, Extended — feature engineering, ensembles, unsupervised, RL, time series, recommenders, anomaly detection |
| 15 | Generative Media — speech/audio, image/video/music generation |
| 16 | Safety, Ethics & XAI |
| 17 | Applications & Career — conversational AI, coding assistants, domain AI, system design & careers |
| 18 | Data & Model Efficiency — data engineering, synthetic data, compression, modern architectures (MoE) |
| 19 | Evaluation, Product & Production — LLM evaluation, AI product/UX, cost & efficiency, edge/on-device |
| 20 | **Capstone Project** — build “Atlas”, an end-to-end RAG + fine-tuned-Llama assistant, explained chapter by chapter |
| 21 | **Interview & Portfolio** — the Applied AI interview loop, plus five buildable projects with full code, toolchain and metrics |

## The capstone (Phase 20)

Twelve code-walkthrough chapters that build one real system — a document assistant using **RAG + a fine-tuned local Llama model + an agent**, served, evaluated, cost-optimised, and deployed. Each chapter shows the **code**, the **reason** for it, the **maths/algorithm** underneath, and a **“Topics used here”** box linking back to the Phase 1–19 topics it draws on. The final chapter indexes **every** topic against where the project used it.

## Interview prep & portfolio (Phase 21)

The last phase turns the knowledge into a job. It has two halves:

- **An interview guide** — which of the three AI tracks is realistically winnable coming from backend engineering, the five rounds of an Applied AI Engineer loop and what each is really testing, a question bank with the answers interviewers listen for, a system-design framework with a worked example, and a triage of all 120 topics into what actually gets tested.
- **Five projects, built end to end** — an LLM gateway, a production RAG pipeline, a tool-using agent, a LoRA fine-tune with self-hosted serving, and an evaluation/guardrail layer with a CI gate. Each page carries the code, the tools required, the skills it proves, and the metrics to capture. Built in order they compose into one system rather than five disconnected repos.

## How to use this

1. If you’re new, start at **Phase 1** and work forward — each phase assumes the ones before it.
2. Read a topic, then do its **exercises** and skim its **free resources**.
3. When you’ve covered the phases, **build the capstone yourself** — that’s where it all clicks.

## Viewing / hosting

- **Live site:** <https://dheerajsingh11.github.io/AI-Engineer-Handbook/>
- **Locally:** just open `index.html`.
- **As a website:** this folder is self-contained (relative links only), so it can be hosted on any static host (e.g. GitHub Pages) as-is. The `.nojekyll` file is included so GitHub Pages serves it without extra processing.

---

*Built as a personal learning roadmap. Shared in the hope it helps — and in the expectation that it can be improved. Corrections welcome.*
