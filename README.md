# Awesome LLM Technical Reports [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

![Reports](https://img.shields.io/badge/reports-172-blue) ![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen)

A curated list of **technical reports for large language models** — the documents where model builders describe architecture, data, pre-training, and post-training. The list focuses on **text LLMs**; reports of natively multimodal models are kept when the language model is the core of the report (marked 🧩).

> This list grew out of the [Pseudo-Lab LLM Technical Report Study](https://github.com/Pseudo-Lab/llm-technical-report-study) and is maintained as a companion to an upcoming survey on LLM technical reports.

**Legend**: 🧩 multimodal (vision input) · 🔓 fully open (weights + training data + code) · (PDF) official PDF, not on arXiv · (Blog) no paper yet; see [Fully Open LLMs](#fully-open-llms)

## Inclusion Criteria

- **Source**: an arXiv preprint, or an independent paper PDF published by the authors/organization. Blog posts, model cards, and slides alone are not included.
- **Scope**: reports about a specific model or model family (not surveys, benchmarks, or third-party analyses).
- **Date**: the first arXiv submission date (v1). PDF-only reports show `—`.
- **Exception**: in [Fully Open LLMs](#fully-open-llms), projects without a paper are listed when weights, data, and code are public and documented (marked (Blog)).
- **Placement**: each report appears once, in its primary category. Within a section, entries are newest first.

## Contents

- [General-Purpose LLMs](#general-purpose-llms) (69)
  - [2025–2026](#20252026) (29)
  - [2023–2024](#20232024) (29)
  - [2020–2022](#20202022) (11)
- [Reasoning-Centric LLMs](#reasoning-centric-llms) (14)
- [Code LLMs](#code-llms) (16)
- [Math & Science LLMs](#math--science-llms) (5)
- [Language- & Region-Specific LLMs](#language---region-specific-llms) (32)
  - [🇰🇷 Korean](#-korean) (11)
  - [🇯🇵 Japanese](#-japanese) (1)
  - [🇪🇺 European](#-european) (5)
  - [🇨🇳 Chinese (early large-scale)](#-chinese-early-large-scale) (8)
  - [🌐 Multilingual](#-multilingual) (7)
- [Small & On-Device LLMs](#small--on-device-llms) (13)
- [Architecture Exploration](#architecture-exploration) (11)
- [Fully Open LLMs](#fully-open-llms) (11)
- [Related: Training Methods](#related-training-methods) (1)
- [Surveys](#surveys)
- [Related Lists](#related-lists)
- [Contributing](#contributing)

## General-Purpose LLMs

Foundation models trained for broad capability. Grouped by the first arXiv submission date.

### 2025–2026

| Date | Model | Report |
| --- | --- | --- |
| 2026-09-23 | Hunyuan-A13B | [Hunyuan-A13B Technical Report](https://arxiv.org/abs/2609.27284) |
| 2026-09-17 | DeepSeek-V4.1-Flash | [DeepSeek-V4.1-Flash: Pushing the Limits of KV Cache Compression](https://arxiv.org/abs/2609.19969) |
| 2026-07-27 | Kimi K3 🧩 | [Kimi K3: Open Frontier Intelligence](https://arxiv.org/abs/2607.24653) |
| 2026-07-02 | Gemma 4 🧩 | [Gemma 4 Technical Report](https://arxiv.org/abs/2607.02770) |
| 2026-06-13 | Ling / Ring 2.6 | [Ling and Ring 2.6 Technical Report: Efficient and Instant Agentic Intelligence at Trillion-Parameter Scale](https://arxiv.org/abs/2606.15079) |
| 2026-05-26 | MiniMax-M2 Series | [The MiniMax-M2 Series: Mini Activations Unleashing Max Real-World Intelligence](https://arxiv.org/abs/2605.26494) |
| 2026-04-26 | DeepSeek-V4 | [DeepSeek-V4: Towards Highly Efficient Million-Token Context Intelligence](https://arxiv.org/abs/2606.19348) |
| 2026-04-14 | Nemotron 3 Super | [Nemotron 3 Super: Open, Efficient Mixture-of-Experts Hybrid Mamba-Transformer Model for Agentic Reasoning](https://arxiv.org/abs/2604.12374) |
| 2026-02-19 | Arcee Trinity Large | [Arcee Trinity Large Technical Report](https://arxiv.org/abs/2602.17004) |
| 2026-02-17 | GLM-5 | [GLM-5: from Vibe Coding to Agentic Engineering](https://arxiv.org/abs/2602.15763) |
| 2026-02-11 | Step 3.5 Flash | [Step 3.5 Flash: Open Frontier-Level Intelligence with 11B Active Parameters](https://arxiv.org/abs/2602.10604) |
| 2026-01-06 | MiMo-V2-Flash | [MiMo-V2-Flash Technical Report](https://arxiv.org/abs/2601.02780) |
| 2025-12-24 | NVIDIA Nemotron 3 | [NVIDIA Nemotron 3: Efficient and Open Intelligence](https://arxiv.org/abs/2512.20856) |
| 2025-12-23 | Nemotron 3 Nano | [Nemotron 3 Nano: Open, Efficient Mixture-of-Experts Hybrid Mamba-Transformer Model for Agentic Reasoning](https://arxiv.org/abs/2512.20848) |
| 2025-12-02 | DeepSeek-V3.2 | [DeepSeek-V3.2: Pushing the Frontier of Open Large Language Models](https://arxiv.org/abs/2512.02556) |
| 2025-10-25 | Ling 2.0 | [Every Activation Boosted: Scaling General Reasoner to 1 Trillion Open Language Foundation](https://arxiv.org/abs/2510.22115) |
| 2025-09-01 | LongCat-Flash | [LongCat-Flash Technical Report](https://arxiv.org/abs/2509.01322) |
| 2025-08-25 | Hermes 4 | [Hermes 4 Technical Report](https://arxiv.org/abs/2508.18255) |
| 2025-08-08 | GLM-4.5 | [GLM-4.5: Agentic, Reasoning, and Coding (ARC) Foundation Models](https://arxiv.org/abs/2508.06471) |
| 2025-07-28 | Kimi K2 | [Kimi K2: Open Agentic Intelligence](https://arxiv.org/abs/2507.20534) |
| 2025-07-24 | TeleChat2 / 2.5 / T1 | [Technical Report of TeleChat2, TeleChat2.5 and T1](https://arxiv.org/abs/2507.18013) |
| 2025-07-07 | Gemini 2.5 🧩 | [Gemini 2.5: Pushing the Frontier with Advanced Reasoning, Multimodality, Long Context, and Next Generation Agentic Capabilities](https://arxiv.org/abs/2507.06261) |
| 2025-06-06 | dots.llm1 | [dots.llm1 Technical Report](https://arxiv.org/abs/2506.05767) |
| 2025-05-14 | Qwen3 | [Qwen3 Technical Report](https://arxiv.org/abs/2505.09388) |
| 2025-05-07 | Pangu Ultra MoE | [Pangu Ultra MoE: How to Train Your Big MoE on Ascend NPUs](https://arxiv.org/abs/2505.04519) |
| 2025-04-01 | Command A | [Command A: An Enterprise-Ready Large Language Model](https://arxiv.org/abs/2504.00698) |
| 2025-03-25 | Gemma 3 | [Gemma 3 Technical Report](https://arxiv.org/abs/2503.19786) |
| — | ERNIE 4.5 | [ERNIE 4.5 Technical Report](https://ernie.baidu.com/blog/publication/ERNIE_Technical_Report.pdf) (PDF) |
| — | MiMo-V2.6 | [MiMo-V2.6 Technical Report](https://huggingface.co/XiaomiMiMo/MiMo-V2.6-Pro-RL/blob/main/MiMo_V2_6_technical_report.pdf) (PDF) |

### 2023–2024

| Date | Model | Report |
| --- | --- | --- |
| 2024-12-27 | DeepSeek-V3 | [DeepSeek-V3 Technical Report](https://arxiv.org/abs/2412.19437) |
| 2024-12-19 | Qwen2.5 | [Qwen2.5 Technical Report](https://arxiv.org/abs/2412.15115) |
| 2024-12-12 | Phi-4 | [Phi-4 Technical Report](https://arxiv.org/abs/2412.08905) |
| 2024-12-02 | Yi-Lightning | [Yi-Lightning Technical Report](https://arxiv.org/abs/2412.01253) |
| 2024-11-04 | Hunyuan-Large | [Hunyuan-Large: An Open-Source MoE Model with 52 Billion Activated Parameters by Tencent](https://arxiv.org/abs/2411.02265) |
| 2024-08-15 | Hermes 3 | [Hermes 3 Technical Report](https://arxiv.org/abs/2408.11857) |
| 2024-08-14 | Aquila2 | [Aquila2 Technical Report](https://arxiv.org/abs/2408.07410) |
| 2024-07-31 | Gemma 2 | [Gemma 2: Improving Open Language Models at a Practical Size](https://arxiv.org/abs/2408.00118) |
| 2024-07-31 | Llama 3 | [The Llama 3 Herd of Models](https://arxiv.org/abs/2407.21783) |
| 2024-07-15 | Qwen2 | [Qwen2 Technical Report](https://arxiv.org/abs/2407.10671) |
| 2024-06-28 | YuLan | [YuLan: An Open-source Large Language Model](https://arxiv.org/abs/2406.19853) |
| 2024-06-18 | ChatGLM / GLM-4 | [ChatGLM: A Family of Large Language Models from GLM-130B to GLM-4 All Tools](https://arxiv.org/abs/2406.12793) |
| 2024-06-17 | Nemotron-4 340B | [Nemotron-4 340B Technical Report](https://arxiv.org/abs/2406.11704) |
| 2024-05-07 | DeepSeek-V2 | [DeepSeek-V2: A Strong, Economical, and Efficient Mixture-of-Experts Language Model](https://arxiv.org/abs/2405.04434) |
| 2024-03-26 | InternLM2 | [InternLM2 Technical Report](https://arxiv.org/abs/2403.17297) |
| 2024-03-13 | Gemma | [Gemma: Open Models Based on Gemini Research and Technology](https://arxiv.org/abs/2403.08295) |
| 2024-03-07 | Yi | [Yi: Open Foundation Models by 01.AI](https://arxiv.org/abs/2403.04652) |
| 2024-01-08 | Mixtral | [Mixtral of Experts](https://arxiv.org/abs/2401.04088) |
| 2024-01-08 | TeleChat | [TeleChat Technical Report](https://arxiv.org/abs/2401.03804) |
| 2024-01-05 | DeepSeek LLM | [DeepSeek LLM: Scaling Open-Source Language Models with Longtermism](https://arxiv.org/abs/2401.02954) |
| 2023-11-28 | Falcon | [The Falcon Series of Open Language Models](https://arxiv.org/abs/2311.16867) |
| 2023-10-30 | Skywork | [Skywork: A More Open Bilingual Foundation Model](https://arxiv.org/abs/2310.19341) |
| 2023-10-10 | Mistral 7B | [Mistral 7B](https://arxiv.org/abs/2310.06825) |
| 2023-09-28 | Qwen | [Qwen Technical Report](https://arxiv.org/abs/2309.16609) |
| 2023-09-19 | Baichuan 2 | [Baichuan 2: Open Large-scale Language Models](https://arxiv.org/abs/2309.10305) |
| 2023-07-18 | Llama 2 | [Llama 2: Open Foundation and Fine-Tuned Chat Models](https://arxiv.org/abs/2307.09288) |
| 2023-05-17 | PaLM 2 | [PaLM 2 Technical Report](https://arxiv.org/abs/2305.10403) |
| 2023-03-15 | GPT-4 🧩 | [GPT-4 Technical Report](https://arxiv.org/abs/2303.08774) |
| 2023-02-27 | LLaMA | [LLaMA: Open and Efficient Foundation Language Models](https://arxiv.org/abs/2302.13971) |

### 2020–2022

| Date | Model | Report |
| --- | --- | --- |
| 2022-10-05 | GLM-130B | [GLM-130B: An Open Bilingual Pre-trained Model](https://arxiv.org/abs/2210.02414) |
| 2022-05-10 | UL2 | [UL2: Unifying Language Learning Paradigms](https://arxiv.org/abs/2205.05131) |
| 2022-05-02 | OPT | [OPT: Open Pre-trained Transformer Language Models](https://arxiv.org/abs/2205.01068) |
| 2022-04-14 | GPT-NeoX-20B | [GPT-NeoX-20B: An Open-Source Autoregressive Language Model](https://arxiv.org/abs/2204.06745) |
| 2022-04-05 | PaLM | [PaLM: Scaling Language Modeling with Pathways](https://arxiv.org/abs/2204.02311) |
| 2022-03-29 | Chinchilla | [Training Compute-Optimal Large Language Models](https://arxiv.org/abs/2203.15556) |
| 2022-01-28 | MT-NLG 530B | [Using DeepSpeed and Megatron to Train Megatron-Turing NLG 530B, A Large-Scale Generative Language Model](https://arxiv.org/abs/2201.11990) |
| 2022-01-20 | LaMDA | [LaMDA: Language Models for Dialog Applications](https://arxiv.org/abs/2201.08239) |
| 2021-12-13 | GLaM | [GLaM: Efficient Scaling of Language Models with Mixture-of-Experts](https://arxiv.org/abs/2112.06905) |
| 2021-12-08 | Gopher | [Scaling Language Models: Methods, Analysis & Insights from Training Gopher](https://arxiv.org/abs/2112.11446) |
| 2020-05-28 | GPT-3 | [Language Models are Few-Shot Learners](https://arxiv.org/abs/2005.14165) |

## Reasoning-Centric LLMs

Reports whose main contribution is reasoning post-training (long CoT, RL with verifiable rewards, thinking modes).

| Date | Model | Report |
| --- | --- | --- |
| 2026-06-15 | VibeThinker-3B | [VibeThinker-3B: Exploring the Frontier of Verifiable Reasoning in Small Language Models](https://arxiv.org/abs/2606.16140) |
| 2026-01-23 | LongCat-Flash-Thinking-2601 | [LongCat-Flash-Thinking-2601 Technical Report](https://arxiv.org/abs/2601.16725) |
| 2025-11-09 | VibeThinker-1.5B | [Tiny Model, Big Logic: Diversity-Driven Optimization Elicits Large-Model Reasoning Ability in VibeThinker-1.5B](https://arxiv.org/abs/2511.06221) |
| 2025-10-21 | Ring-1T | [Every Step Evolves: Scaling Reinforcement Learning for Trillion-Scale Thinking Model](https://arxiv.org/abs/2510.18855) |
| 2025-09-23 | LongCat-Flash-Thinking | [Introducing LongCat-Flash-Thinking: A Technical Report](https://arxiv.org/abs/2509.18883) |
| 2025-07-08 | Skywork-R1V3 | [Skywork-R1V3 Technical Report](https://arxiv.org/abs/2507.06167) |
| 2025-06-16 | MiniMax-M1 | [MiniMax-M1: Scaling Test-Time Compute Efficiently with Lightning Attention](https://arxiv.org/abs/2506.13585) |
| 2025-06-12 | Magistral | [Magistral](https://arxiv.org/abs/2506.10910) |
| 2025-05-28 | Skywork-OR1 | [Skywork Open Reasoner 1 Technical Report](https://arxiv.org/abs/2505.22312) |
| 2025-05-12 | MiMo | [MiMo: Unlocking the Reasoning Potential of Language Model -- From Pretraining to Posttraining](https://arxiv.org/abs/2505.07608) |
| 2025-05-02 | Llama-Nemotron | [Llama-Nemotron: Efficient Reasoning Models](https://arxiv.org/abs/2505.00949) |
| 2025-04-30 | Phi-4-reasoning | [Phi-4-reasoning Technical Report](https://arxiv.org/abs/2504.21318) |
| 2025-04-10 | Seed1.5-Thinking | [Seed1.5-Thinking: Advancing Superb Reasoning Models with Reinforcement Learning](https://arxiv.org/abs/2504.13914) |
| 2025-01-22 | DeepSeek-R1 | [DeepSeek-R1: Incentivizing Reasoning Capability in LLMs via Reinforcement Learning](https://arxiv.org/abs/2501.12948) |

## Code LLMs

Models specialized for code generation, infilling, and software-engineering agents.

| Date | Model | Report |
| --- | --- | --- |
| 2026-07-06 | KAT-Coder-V2.5 | [KAT-Coder-V2.5 Technical Report](https://arxiv.org/abs/2607.05471) |
| 2026-05-29 | Mellum2 | [Mellum2 Technical Report](https://arxiv.org/abs/2605.31268) |
| 2026-05-26 | Laguna M.1 / XS.2 | [Laguna M.1/XS.2 Technical Report](https://arxiv.org/abs/2605.27605) |
| 2026-03-29 | KAT-Coder-V2 | [KAT-Coder-V2 Technical Report](https://arxiv.org/abs/2603.27703) |
| 2026-02-28 | Qwen3-Coder-Next | [Qwen3-Coder-Next Technical Report](https://arxiv.org/abs/2603.00729) |
| 2025-10-21 | KAT-Coder | [KAT-Coder Technical Report](https://arxiv.org/abs/2510.18779) |
| 2025-08-08 | Devstral | [Devstral: Fine-tuning Language Models for Coding Agent Applications](https://arxiv.org/abs/2509.25193) |
| 2024-09-18 | Qwen2.5-Coder | [Qwen2.5-Coder Technical Report](https://arxiv.org/abs/2409.12186) |
| 2024-06-17 | DeepSeek-Coder-V2 | [DeepSeek-Coder-V2: Breaking the Barrier of Closed-Source Models in Code Intelligence](https://arxiv.org/abs/2406.11931) |
| 2024-01-25 | DeepSeek-Coder | [DeepSeek-Coder: When the Large Language Model Meets Programming -- The Rise of Code Intelligence](https://arxiv.org/abs/2401.14196) |
| 2023-08-24 | Code Llama | [Code Llama: Open Foundation Models for Code](https://arxiv.org/abs/2308.12950) |
| 2023-05-09 | StarCoder | [StarCoder: may the source be with you!](https://arxiv.org/abs/2305.06161) |
| 2023-05-03 | CodeGen2 | [CodeGen2: Lessons for Training LLMs on Programming and Natural Languages](https://arxiv.org/abs/2305.02309) |
| 2022-04-12 | InCoder | [InCoder: A Generative Model for Code Infilling and Synthesis](https://arxiv.org/abs/2204.05999) |
| 2022-03-25 | CodeGen | [CodeGen: An Open Large Language Model for Code with Multi-Turn Program Synthesis](https://arxiv.org/abs/2203.13474) |
| 2022-02-08 | AlphaCode | [Competition-Level Code Generation with AlphaCode](https://arxiv.org/abs/2203.07814) |

## Math & Science LLMs

Models specialized for mathematical reasoning, formal verification, or scientific knowledge.

| Date | Model | Report |
| --- | --- | --- |
| 2025-11-27 | DeepSeekMath-V2 | [DeepSeekMath-V2: Towards Self-Verifiable Mathematical Reasoning](https://arxiv.org/abs/2511.22570) |
| 2025-08-21 | Intern-S1 🧩 | [Intern-S1: A Scientific Multimodal Foundation Model](https://arxiv.org/abs/2508.15763) |
| 2024-09-18 | Qwen2.5-Math | [Qwen2.5-Math Technical Report: Toward Mathematical Expert Model via Self-Improvement](https://arxiv.org/abs/2409.12122) |
| 2024-02-05 | DeepSeekMath | [DeepSeekMath: Pushing the Limits of Mathematical Reasoning in Open Language Models](https://arxiv.org/abs/2402.03300) |
| 2022-11-16 | Galactica | [Galactica: A Large Language Model for Science](https://arxiv.org/abs/2211.09085) |

## Language- & Region-Specific LLMs

Models whose report centers on a specific language, region, or multilingual coverage.

### 🇰🇷 Korean

| Date | Model | Report |
| --- | --- | --- |
| 2026-08-10 | Motif 3 | [Motif 3: Technical Report](https://arxiv.org/abs/2608.09119) |
| 2026-08-05 | K-EXAONE 2.0 | [K-EXAONE 2.0 Technical Report](https://arxiv.org/abs/2608.04505) |
| 2026-07-22 | Solar Open 2 | [Solar Open 2 Technical Report](https://arxiv.org/abs/2607.20062) |
| 2026-04-09 | EXAONE 4.5 🧩 | [EXAONE 4.5 Technical Report](https://arxiv.org/abs/2604.08644) |
| 2026-01-14 | A.X K1 | [A.X K1 Technical Report](https://arxiv.org/abs/2601.09200) |
| 2026-01-11 | Solar Open | [Solar Open Technical Report](https://arxiv.org/abs/2601.07022) |
| 2026-01-05 | K-EXAONE | [K-EXAONE Technical Report](https://arxiv.org/abs/2601.01739) |
| 2025-11-07 | Motif 2 12.7B | [Motif 2 12.7B technical report](https://arxiv.org/abs/2511.07464) |
| 2025-10-10 | KORMo 🔓 | [KORMo: Korean Open Reasoning Model for Everyone](https://arxiv.org/abs/2510.09426) |
| 2025-07-15 | EXAONE 4.0 | [EXAONE 4.0: Unified Large Language Models Integrating Non-reasoning and Reasoning Modes](https://arxiv.org/abs/2507.11407) |
| 2021-09-10 | HyperCLOVA | [What Changes Can Large-scale Language Models Bring? Intensive Study on HyperCLOVA: Billions-scale Korean Generative Pretrained Transformers](https://arxiv.org/abs/2109.04650) |

### 🇯🇵 Japanese

| Date | Model | Report |
| --- | --- | --- |
| 2025-09-05 | PLaMo 2 | [PLaMo 2 Technical Report](https://arxiv.org/abs/2509.04897) |

### 🇪🇺 European

| Date | Model | Report |
| --- | --- | --- |
| 2026-02-05 | EuroLLM-22B | [EuroLLM-22B: Technical Report](https://arxiv.org/abs/2602.05879) |
| 2026-01-06 | NorwAI | [NorwAI's Large Language Models: Technical Report](https://arxiv.org/abs/2601.03034) |
| 2025-09-17 | Apertus 🔓 | [Apertus: Democratizing Open and Compliant LLMs for Global Language Environments](https://arxiv.org/abs/2509.14233) |
| 2025-06-04 | EuroLLM-9B | [EuroLLM-9B: Technical Report](https://arxiv.org/abs/2506.04079) |
| 2025-02-12 | Salamandra | [Salamandra Technical Report](https://arxiv.org/abs/2502.08489) |

### 🇨🇳 Chinese (early large-scale)

| Date | Model | Report |
| --- | --- | --- |
| 2023-11-27 | Yuan 2.0 | [YUAN 2.0: A Large Language Model with Localized Filtering-based Attention](https://arxiv.org/abs/2311.15786) |
| 2023-03-20 | PanGu-Σ | [PanGu-Σ: Towards Trillion Parameter Language Model with Sparse Heterogeneous Computing](https://arxiv.org/abs/2303.10845) |
| 2022-09-21 | WeLM | [WeLM: A Well-Read Pre-trained Language Model for Chinese](https://arxiv.org/abs/2209.10372) |
| 2021-12-23 | ERNIE 3.0 Titan | [ERNIE 3.0 Titan: Exploring Larger-scale Knowledge Enhanced Pre-training for Language Understanding and Generation](https://arxiv.org/abs/2112.12731) |
| 2021-10-10 | Yuan 1.0 | [Yuan 1.0: Large-Scale Pre-trained Language Model in Zero-Shot and Few-Shot Learning](https://arxiv.org/abs/2110.04725) |
| 2021-07-05 | ERNIE 3.0 | [ERNIE 3.0: Large-scale Knowledge Enhanced Pre-training for Language Understanding and Generation](https://arxiv.org/abs/2107.02137) |
| 2021-06-20 | CPM-2 | [CPM-2: Large-scale Cost-effective Pre-trained Language Models](https://arxiv.org/abs/2106.10715) |
| 2021-04-26 | PanGu-α | [PanGu-α: Large-scale Autoregressive Pretrained Chinese Language Models with Auto-parallel Computation](https://arxiv.org/abs/2104.12369) |

### 🌐 Multilingual

| Date | Model | Report |
| --- | --- | --- |
| 2024-05-23 | Aya 23 | [Aya 23: Open Weight Releases to Further Multilingual Progress](https://arxiv.org/abs/2405.15032) |
| 2024-01-20 | Orion-14B | [Orion-14B: Open-source Multilingual Large Language Models](https://arxiv.org/abs/2401.12246) |
| 2023-12-22 | YAYI 2 | [YAYI 2: Multilingual Open-Source Large Language Models](https://arxiv.org/abs/2312.14862) |
| 2023-12-14 | TigerBot | [TigerBot: An Open Multilingual Multitask LLM](https://arxiv.org/abs/2312.08688) |
| 2023-07-12 | PolyLM | [PolyLM: An Open Source Polyglot Large Language Model](https://arxiv.org/abs/2307.06018) |
| 2022-11-09 | BLOOM | [BLOOM: A 176B-Parameter Open-Access Multilingual Language Model](https://arxiv.org/abs/2211.05100) |
| 2022-08-02 | AlexaTM 20B | [AlexaTM 20B: Few-Shot Learning Using a Large-Scale Multilingual Seq2Seq Model](https://arxiv.org/abs/2208.01448) |

## Small & On-Device LLMs

Models designed around a small parameter budget or on-device deployment.

| Date | Model | Report |
| --- | --- | --- |
| 2026-01-13 | Ministral 3 | [Ministral 3](https://arxiv.org/abs/2601.08584) |
| 2025-11-28 | LFM2 | [LFM2 Technical Report](https://arxiv.org/abs/2511.23404) |
| 2025-07-17 | Apple Foundation Models 2025 🧩 | [Apple Intelligence Foundation Language Models: Tech Report 2025](https://arxiv.org/abs/2507.13575) |
| 2025-06-09 | MiniCPM4 | [MiniCPM4: Ultra-Efficient LLMs on End Devices](https://arxiv.org/abs/2506.07900) |
| 2025-02-04 | SmolLM2 🔓 | [SmolLM2: When Smol Goes Big -- Data-Centric Training of a Small Language Model](https://arxiv.org/abs/2502.02737) |
| 2024-12-23 | YuLan-Mini | [YuLan-Mini: An Open Data-efficient Language Model](https://arxiv.org/abs/2412.17743) |
| 2024-07-29 | Apple Foundation Models 2024 | [Apple Intelligence Foundation Language Models](https://arxiv.org/abs/2407.21075) |
| 2024-04-22 | OpenELM 🔓 | [OpenELM: An Efficient Language Model Family with Open Training and Inference Framework](https://arxiv.org/abs/2404.14619) |
| 2024-04-22 | Phi-3 | [Phi-3 Technical Report: A Highly Capable Language Model Locally on Your Phone](https://arxiv.org/abs/2404.14219) |
| 2024-04-09 | MiniCPM | [MiniCPM: Unveiling the Potential of Small Language Models with Scalable Training Strategies](https://arxiv.org/abs/2404.06395) |
| 2024-01-04 | TinyLlama | [TinyLlama: An Open-Source Small Language Model](https://arxiv.org/abs/2401.02385) |
| 2023-09-11 | phi-1.5 | [Textbooks Are All You Need II: phi-1.5 technical report](https://arxiv.org/abs/2309.05463) |
| 2023-06-20 | phi-1 | [Textbooks Are All You Need](https://arxiv.org/abs/2306.11644) |

## Architecture Exploration

Reports whose main contribution is an alternative architecture: hybrid SSM, linear attention, diffusion, adaptive depth.

| Date | Model | Report |
| --- | --- | --- |
| 2026-08-31 | Qwen3.8-Next | [On the Design of Qwen3.8-Next Architecture: Evaluation, Efficiency, and Training Stability](https://arxiv.org/abs/2608.30320) |
| 2026-02-26 | Ruyi2 | [Ruyi2 Technical Report](https://arxiv.org/abs/2602.22543) |
| 2025-10-30 | Kimi Linear | [Kimi Linear: An Expressive, Efficient Attention Architecture](https://arxiv.org/abs/2510.26692) |
| 2025-10-22 | Ring-linear | [Every Attention Matters: An Efficient Hybrid Architecture for Long-Context Reasoning](https://arxiv.org/abs/2510.19338) |
| 2025-07-30 | Falcon-H1 | [Falcon-H1: A Family of Hybrid-Head Language Models Redefining Efficiency and Performance](https://arxiv.org/abs/2507.22448) |
| 2025-06-17 | Mercury | [Mercury: Ultra-Fast Language Models Based on Diffusion](https://arxiv.org/abs/2506.17298) |
| 2025-05-21 | Hunyuan-TurboS | [Hunyuan-TurboS: Advancing Large Language Models through Mamba-Transformer Synergy and Adaptive Chain-of-Thought](https://arxiv.org/abs/2505.15431) |
| 2025-03-18 | RWKV-7 | [RWKV-7 "Goose" with Expressive Dynamic State Evolution](https://arxiv.org/abs/2503.14456) |
| 2025-01-14 | MiniMax-01 | [MiniMax-01: Scaling Foundation Models with Lightning Attention](https://arxiv.org/abs/2501.08313) |
| 2024-08-22 | Jamba-1.5 | [Jamba-1.5: Hybrid Transformer-Mamba Models at Scale](https://arxiv.org/abs/2408.12570) |
| 2024-03-28 | Jamba | [Jamba: A Hybrid Transformer-Mamba Language Model](https://arxiv.org/abs/2403.19887) |

## Fully Open LLMs

Models released together with training data, code, and intermediate checkpoints. Because the artifacts themselves are open, this section also lists fully open projects that document their work in blogs, docs, or live training logs before (or instead of) a paper.

| Date | Model | Report |
| --- | --- | --- |
| 2026-08-21 | Marin 535B-A23B | [Marin 535B-A23B started training (live, open training run)](https://x.com/percyliang/status/2090918065634684997) (Blog) |
| 2025-12-15 | Olmo 3 | [Olmo 3](https://arxiv.org/abs/2512.13961) |
| 2025-12 | Marin 32B | [Marin 32B Retrospective](https://github.com/marin-community/marin/blob/main/docs/reports/marin-32b-retro.md) (Blog) |
| 2025-07-08 | SmolLM3 | [SmolLM3: smol, multilingual, long-context reasoner](https://huggingface.co/blog/smollm3) (Blog) |
| 2025-05-19 | Marin 8B | [Marin: An Open Lab for Building Foundation Models](https://marin.community/blog/2025/05/19/announcement/) (Blog) |
| 2024-12-31 | OLMo 2 | [2 OLMo 2 Furious](https://arxiv.org/abs/2501.00656) |
| 2024-12-08 | Moxin-7B 🧩 | [7B Fully Open Source Moxin-LLM/VLM -- From Pretraining to GRPO-based Reinforcement Learning Enhancement](https://arxiv.org/abs/2412.06845) |
| 2024-11-22 | Tülu 3 | [Tulu 3: Pushing Frontiers in Open Language Model Post-Training](https://arxiv.org/abs/2411.15124) |
| 2024-09-03 | OLMoE | [OLMoE: Open Mixture-of-Experts Language Models](https://arxiv.org/abs/2409.02060) |
| 2024-02-01 | OLMo | [OLMo: Accelerating the Science of Language Models](https://arxiv.org/abs/2402.00838) |
| 2023-04-03 | Pythia | [Pythia: A Suite for Analyzing Large Language Models Across Training and Scaling](https://arxiv.org/abs/2304.01373) |

## Related: Training Methods

Method papers that ship a model as their main evidence.

| Date | Model | Report |
| --- | --- | --- |
| 2025-02-24 | Muon / Moonlight | [Muon is Scalable for LLM Training](https://arxiv.org/abs/2502.16982) |

## Surveys

| Date | Paper |
| --- | --- |
| 2024-02-09 | [Large Language Models: A Survey](https://arxiv.org/abs/2402.06196) |
| 2023-07-12 | [A Comprehensive Overview of Large Language Models](https://arxiv.org/abs/2307.06435) |
| 2023-03-31 | [A Survey of Large Language Models](https://arxiv.org/abs/2303.18223) · [FCS journal version](https://doi.org/10.1007/s11704-026-60308-3) |

## Related Lists

- [Hannibal046/Awesome-LLM](https://github.com/Hannibal046/Awesome-LLM)
- [ChenZiHong-Gavin/llm-tech-report](https://github.com/ChenZiHong-Gavin/llm-tech-report)
- [HqWu-HITCS/Awesome-Chinese-LLM](https://github.com/HqWu-HITCS/Awesome-Chinese-LLM)
- [RUCAIBox/LLMSurvey](https://github.com/RUCAIBox/LLMSurvey)

## Contributing

1. Open an issue with the **Add a report** template — **one report per issue**.
2. Add one row to the matching section (newest first) using the format below, then open a PR that links the issue (`Closes #N`).

```markdown
| YYYY-MM-DD | Model | [Original Report Title](https://arxiv.org/abs/XXXX.XXXXX) |
```

Use the report title exactly as it appears on arXiv, and the v1 submission date. Please check that the report is not already listed in another section.
