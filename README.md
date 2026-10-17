# Awesome AI Eval with stars

[<img src="./assets/robot-shades.svg" align="right" width="96" alt="Robot wearing pink shades">](https://github.com/Vvkmnn/awesome-ai-eval)

> Assessing the reliability, accuracy, and safety of large language models, RAG pipelines, and AI agents.

## Contents

* [Tools](#tools)
  * [Frameworks](#frameworks)
  * [Retrieval](#retrieval)
  * [Adversarial](#adversarial)
* [Platforms](#platforms)
  * [Self-Hosted](#self-hosted)
  * [Managed](#managed)
  * [Cloud](#cloud)
* [Benchmarks](#benchmarks)
  * [General](#general)
  * [Long-Context](#long-context)
  * [Specialized](#specialized)
  * [Agents](#agents)
  * [Multimodal](#multimodal)
  * [Safety](#safety)
* [Leaderboards](#leaderboards)
* [Resources](#resources)
  * [Papers](#papers)
  * [Guides](#guides)
  * [Lists](#lists)

## Tools

### Frameworks

* [ColossalEval](https://github.com/hpcaitech/ColossalAI/tree/main/applications/ColossalEval) ⭐ 41,431 | 🐛 504 | 🌐 Python | 📅 2026-10-15 - Pipeline combining classic metrics with GPT-assisted scoring across public datasets.
* [MLflow](https://github.com/mlflow/mlflow) ⭐ 28,421 | 🐛 2,196 | 🌐 Python | 📅 2026-10-17 - Evaluation API that logs judge scores alongside experiment tracking runs.
* [Promptfoo](https://github.com/promptfoo/promptfoo) ⭐ 26,078 | 🐛 767 | 🌐 TypeScript | 📅 2026-10-17 - CLI for testing and red teaming prompts, RAG flows, and agents with regression detection.
* [OpenAI Evals](https://github.com/openai/evals) ⭐ 19,613 | 🐛 348 | 🌐 Python | 📅 2026-04-14 - Framework and registry of evals for LLMs and LLM systems.
* [DeepEval](https://github.com/confident-ai/deepeval) ⭐ 18,917 | 🐛 739 | 🌐 Python | 📅 2026-10-16 - Unit-test style metrics for hallucination, relevance, toxicity, and bias.
* [LM Evaluation Harness](https://github.com/EleutherAI/lm-evaluation-harness) ⭐ 14,243 | 🐛 1,192 | 🌐 Python | 📅 2026-09-14 - Harness for running language models on hundreds of academic benchmarks.
* [Prompt Flow](https://github.com/microsoft/promptflow) ⭐ 11,253 | 🐛 67 | 🌐 Python | 📅 2026-10-15 - Flow builder with built-in evaluation flows and CI integration.
* [Evidently](https://github.com/evidentlyai/evidently) ⭐ 7,994 | 🐛 336 | 🌐 Jupyter Notebook | 📅 2026-09-29 - Evaluation and monitoring library for ML and LLM systems.
* [OpenCompass](https://github.com/open-compass/opencompass) ⭐ 7,521 | 🐛 376 | 🌐 Python | 📅 2026-10-16 - Evaluation platform with LLM judge support across knowledge, reasoning, and coding datasets.
* [OpenAI simple-evals](https://github.com/openai/simple-evals) ⭐ 4,666 | 🐛 67 | 🌐 Python | 📅 2026-04-22 - Reference implementations of standard benchmarks such as MMLU, GPQA, and HumanEval.
* [lmms-eval](https://github.com/EvolvingLMMs-Lab/lmms-eval) ⭐ 4,453 | 🐛 62 | 🌐 Python | 📅 2026-10-17 - Multimodal evaluation toolkit covering text, image, video, and audio tasks.
* [TruLens](https://github.com/truera/trulens) ⭐ 3,602 | 🐛 92 | 🌐 Python | 📅 2026-10-16 - Feedback functions for evaluating and tracing chains and agents.
* [ChainForge](https://github.com/ianarawjo/ChainForge) ⭐ 3,035 | 🐛 69 | 🌐 TypeScript | 📅 2026-10-15 - Visual environment for comparing prompts and models and scoring responses.
* [Inspect AI](https://github.com/UKGovernmentBEIS/inspect_ai) ⭐ 3,023 | 🐛 391 | 🌐 Python | 📅 2026-10-17 - UK AI Security Institute framework for scripted evals with tool calls and model-graded scoring.
* [HELM](https://github.com/stanford-crfm/helm) ⭐ 2,947 | 🐛 114 | 🌐 Python | 📅 2026-09-01 - Stanford framework for evaluating foundation models across scenarios and metrics.
* [lighteval](https://github.com/huggingface/lighteval) ⭐ 2,563 | 🐛 443 | 🌐 Python | 📅 2026-10-06 - Hugging Face toolkit for evaluating LLMs across many backends and tasks.
* [Bloom](https://github.com/safety-research/bloom) ⭐ 1,416 | 🐛 9 | 🌐 Python | 📅 2026-05-07 - Agentic framework that generates behavioral evaluations of frontier models from a described behavior.
* [openevals](https://github.com/langchain-ai/openevals) ⭐ 1,225 | 🐛 21 | 🌐 Python | 📅 2026-10-14 - Evaluators for LLM apps, including LLM judge and structured-output checks.
* [autoevals](https://github.com/braintrustdata/autoevals) ⭐ 1,058 | 🐛 45 | 🌐 Python | 📅 2026-10-08 - Scorers for LLM outputs, from string heuristics to model-graded factuality, in Python and TypeScript.
* [Inspect Evals](https://github.com/UKGovernmentBEIS/inspect_evals) ⭐ 706 | 🐛 251 | 🌐 Python | 📅 2026-10-17 - Community-maintained collection of evaluations implemented in Inspect AI.
* [agenttrace](https://github.com/luoyuctl/agenttrace) ⭐ 147 | 🐛 5 | 🌐 Rust | 📅 2026-10-12 - Terminal UI for reviewing coding-agent sessions by cost, failures, latency, and diffs.
* [skill-optimizer](https://github.com/fastxyz/skill-optimizer) ⭐ 81 | 🐛 15 | 🌐 TypeScript | 📅 2026-05-28 - Docker workbench and agent skill for running deterministic evals against agent skills.
* [Aleph Alpha Eval Framework](https://github.com/Aleph-Alpha-Research/eval-framework) ⭐ 45 | 🐛 12 | 🌐 Python | 📅 2026-10-17 - Evaluation framework with built-in benchmarks for reasoning, coding, and safety.

### Retrieval

* [Ragas](https://github.com/vibrantlabsai/ragas) ⭐ 16,045 | 🐛 638 | 🌐 Python | 📅 2026-02-24 - Metrics for answer quality, context relevance, and faithfulness in RAG pipelines.
* [UltraRAG](https://github.com/OpenBMB/UltraRAG) ⭐ 5,728 | 🐛 18 | 🌐 Python | 📅 2026-10-14 - MCP-based RAG framework with built-in evaluation workflows.
* [MTEB](https://github.com/embeddings-benchmark/mteb) ⭐ 3,463 | 🐛 317 | 🌐 Python | 📅 2026-10-17 - Embedding benchmark measuring retrieval, reranking, and similarity quality.
* [BEIR](https://github.com/beir-cellar/beir) ⭐ 2,312 | 🐛 88 | 🌐 Python | 📅 2025-10-16 - Benchmark suite covering dense, sparse, and hybrid retrieval tasks.
* [Open RAG Eval](https://github.com/vectara/open-rag-eval) ⭐ 414 | 🐛 17 | 🌐 Python | 📅 2026-10-08 - Vectara harness with UMBRELA and AutoNuggetizer metrics that need no golden answers.
* [RAGTruth](https://github.com/ParticleMedia/RAGTruth) ⭐ 280 | 🐛 6 | 🌐 Python | 📅 2024-12-02 - Human-annotated hallucination corpus for RAG answers.
* [LlamaIndex Evaluation](https://developers.llamaindex.ai/python/framework/module_guides/evaluating/) - Modules for scoring retrievers and comparing query engines.

### Adversarial

* [Garak](https://github.com/NVIDIA/garak) ⭐ 9,594 | 🐛 487 | 🌐 Python | 📅 2026-10-16 - NVIDIA vulnerability scanner that probes LLMs for prompt injection, leakage, and jailbreaks.
* [PyRIT](https://github.com/microsoft/PyRIT) ⭐ 4,639 | 🐛 104 | 🌐 Python | 📅 2026-10-17 - Microsoft toolkit for automating attack strategies against generative AI systems.
* [DeepTeam](https://github.com/confident-ai/deepteam) ⭐ 3,021 | 🐛 76 | 🌐 Python | 📅 2026-10-16 - Red teaming framework for bias, data leakage, and prompt-injection vulnerabilities.
* [Petri](https://github.com/meridianlabs-ai/inspect_petri) ⭐ 1,379 | 🐛 43 | 🌐 Python | 📅 2026-10-14 - Auditing agent that explores model behavior through simulated multi-turn scenarios.
* [AgentDojo](https://github.com/ethz-spylab/agentdojo) ⭐ 928 | 🐛 79 | 🌐 Python | 📅 2026-06-02 - Environment for testing prompt-injection attacks and defenses on tool-using agents.

## Platforms

### Self-Hosted

* [Langfuse](https://github.com/langfuse/langfuse) ⭐ 35,945 | 🐛 1,063 | 🌐 TypeScript | 📅 2026-10-17 - Engineering platform for tracing, evals, datasets, and prompt management.
* [Opik](https://github.com/comet-ml/opik) ⭐ 22,666 | 🐛 195 | 🌐 Python | 📅 2026-10-17 - Evaluation and observability platform with datasets, scoring jobs, and trace inspection.
* [Arize Phoenix](https://github.com/Arize-ai/phoenix) ⭐ 11,880 | 🐛 1,154 | 🌐 Python | 📅 2026-10-17 - OpenTelemetry-native tracing and evaluation for RAG, LLMs, and agents.
* [Helicone](https://github.com/Helicone/helicone) ⭐ 6,226 | 🐛 170 | 🌐 TypeScript | 📅 2026-10-10 - AI gateway and observability platform with cost tracking and evaluation integrations.
* [Giskard](https://github.com/giskard-ai/giskard-oss) ⭐ 5,907 | 🐛 71 | 🌐 Python | 📅 2026-10-16 - Testing library that scans LLM apps for vulnerabilities and quality issues.
* [Latitude](https://github.com/latitude-dev/latitude-llm) ⭐ 4,723 | 🐛 98 | 🌐 TypeScript | 📅 2026-10-14 - Platform for observing agent traces and tracking recurring failures as issues.
* [OpenLIT](https://github.com/openlit/openlit) ⭐ 2,853 | 🐛 111 | 🌐 TypeScript | 📅 2026-10-15 - OpenTelemetry instrumentation for LLM apps with quality metrics and guardrail hooks.
* [Rhesis](https://github.com/rhesis-ai/rhesis) ⭐ 398 | 🐛 45 | 🌐 Python | 📅 2026-10-15 - Collaborative testing platform with test generation and multi-turn conversation simulation.
* [Zeno](https://zenoml.com/) - Evaluation UI for slicing failures and comparing models and prompts.

### Managed

* [Athina AI](https://www.athina.ai/) - Evaluation and monitoring platform with preset evals and VPC deployment.
* [Braintrust](https://www.braintrust.dev/) - Evaluation and observability platform with experiments, datasets, and CI regression tests.
* [Confident AI](https://www.confident-ai.com/) - DeepEval-backed platform for scheduled eval suites and production monitoring.
* [Datadog LLM Observability](https://www.datadoghq.com/product/llm-observability/) - LLM traces, quality metrics, and safety signals inside Datadog.
* [Deepchecks LLM Evaluation](https://www.deepchecks.com/solutions/llm-evaluation/) - Managed eval suites with dataset versioning and alerting.
* [Future AGI](https://futureagi.com/) - Evaluation, simulation, and optimization platform for multimodal AI systems.
* [Galileo](https://www.galileo.ai/) - Observability and evaluation platform with built-in metrics and guardrails.
* [HoneyHive](https://www.honeyhive.ai/) - Agent observability and evaluation platform with prompt versioning.
* [LangSmith](https://smith.langchain.com/) - Tracing, datasets, and batch evals with regression gating.
* [Lunary](https://lunary.ai/) - Observability and prompt management platform for LLM apps.
* [PromptLayer](https://www.promptlayer.com/) - Prompt management with version control and evaluation tracking.
* [W\&B Weave](https://wandb.ai/site/evaluations/) - Evaluation toolkit with dataset versioning, scorers, and comparison dashboards.

### Cloud

* [Amazon Bedrock Evaluations](https://aws.amazon.com/bedrock/evaluations/) - Managed scoring of foundation models and RAG pipelines.
* [Google Gen AI Evaluation Service](https://docs.cloud.google.com/gemini-enterprise-agent-platform/models/evaluation-overview) - Rubric-based evaluation of models and agents on Google Cloud.
* [Microsoft Foundry Evaluations](https://learn.microsoft.com/en-us/azure/foundry/how-to/evaluate-generative-ai-app) - Built-in evaluators and reports for generative AI apps.

## Benchmarks

### General

* [IFEval](https://github.com/google-research/google-research/tree/master/instruction_following_eval) ⭐ 38,927 | 🐛 2,008 | 🌐 Jupyter Notebook | 📅 2026-10-15 - Prompts with verifiable constraints for checking instruction compliance.
* [Humanity's Last Exam](https://github.com/centerforaisafety/hle) ⭐ 1,715 | 🐛 10 | 🌐 Python | 📅 2026-09-23 - Expert-written closed-ended questions across academic subjects.
* [MMLU](https://github.com/hendrycks/test) ⭐ 1,625 | 🐛 17 | 🌐 Python | 📅 2023-05-28 - Multiple-choice questions across academic and professional subjects. The standard knowledge benchmark; complete and no longer updated.
* [LiveBench](https://github.com/LiveBench/LiveBench) ⭐ 1,343 | 🐛 179 | 🌐 Python | 📅 2026-10-16 - Contamination-limited benchmark with regularly refreshed questions and objective scoring.
* [AGIEval](https://github.com/ruixiangcui/AGIEval) ⭐ 776 | 🐛 9 | 🌐 Python | 📅 2024-06-13 - Human-centric exams spanning admission tests, law, and math.
* [MMLU-Pro](https://github.com/TIGER-AI-Lab/MMLU-Pro) ⭐ 431 | 🐛 13 | 🌐 Python | 📅 2026-03-18 - Harder ten-option extension of MMLU focused on reasoning.
* [LLM-Uncertainty-Bench](https://github.com/smartyfh/LLM-Uncertainty-Bench) ⭐ 263 | 🐛 1 | 🌐 Python | 📅 2024-01-30 - Uncertainty-aware scoring across QA, reading comprehension, inference, dialog, and summarization.
* [LLMBar](https://github.com/princeton-nlp/LLMBar) ⭐ 143 | 🐛 1 | 🌐 Python | 📅 2024-07-08 - Meta-evaluation of whether LLM judges can spot instruction-following failures.
* [CommonGen-Eval](https://github.com/allenai/CommonGen-Eval) ⭐ 94 | 🐛 1 | 🌐 Python | 📅 2024-03-21 - GPT-4 judged suite for constrained commonsense text generation.
* [StructEval](https://github.com/TIGER-AI-Lab/StructEval) ⭐ 23 | 🐛 6 | 🌐 Python | 📅 2026-10-12 - Structured-output generation and conversion across 18 text and renderable formats.
* [PertEval](https://github.com/aigc-apps/PertEval) ⭐ 14 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2024-10-30 - Knowledge-invariant perturbations that expose inflated multiple-choice accuracy.
* [ARC-AGI-2](https://arcprize.org/arc-agi/2/) - Abstract reasoning puzzles that are easy for people and hard for models.
* [DyVal](https://arxiv.org/abs/2309.17167) - Dynamically generated reasoning tasks with controllable difficulty.
* [JudgeBench](https://arxiv.org/abs/2410.12784) - Benchmark for LLM judges on hard response pairs across knowledge, reasoning, math, and coding.
* [SimpleBench](https://simple-bench.com/) - Everyday reasoning questions where people still outperform frontier models.

### Long-Context

* [RULER](https://github.com/NVIDIA/RULER) ⭐ 1,624 | 🐛 24 | 🌐 Python | 📅 2026-07-22 - Synthetic long-context tasks with configurable sequence length.
* [InfiniteBench](https://github.com/OpenBMB/InfiniteBench) ⭐ 393 | 🐛 11 | 🌐 Python | 📅 2024-09-25 - Twelve tasks with average context length beyond 100K tokens.
* [LV-Eval](https://github.com/infinigence/LVEval) ⭐ 78 | 🐛 7 | 🌐 Python | 📅 2024-08-31 - Five length tiers up to 256K words with distraction controls.
* [LongBench v2](https://longbench2.github.io/) - Questions over contexts from 8K to 2M words in six task categories.
* [LongGenBench](https://arxiv.org/abs/2409.02076) - Long-form generation benchmark for long-context models.

### Specialized

* [MBPP](https://github.com/google-research/google-research/tree/master/mbpp) ⭐ 38,927 | 🐛 2,008 | 🌐 Jupyter Notebook | 📅 2026-10-15 - Entry-level Python programming problems with tests.
* [HumanEval](https://github.com/openai/human-eval) ⭐ 3,407 | 🐛 45 | 🌐 Python | 📅 2026-10-16 - Hand-written programming problems checked by unit tests. Complete and no longer updated.
* [MATH](https://github.com/hendrycks/math) ⭐ 1,394 | 🐛 19 | 🌐 Python | 📅 2025-09-06 - Competition mathematics problems with step-by-step solutions.
* [FinEval](https://github.com/SUFE-AIFLM-Lab/FinEval) ⭐ 291 | 🐛 5 | 🌐 Python | 📅 2025-06-23 - Chinese financial knowledge and reasoning across regulation, accounting, and markets.
* [LAiW](https://github.com/Dai-shen/LAiW) ⭐ 91 | 🐛 4 | 🌐 Python | 📅 2024-07-03 - Chinese legal benchmark covering retrieval, inference, and case application.
* [FinanceBench](https://www.patronus.ai/announcements/patronus-ai-launches-financebench-the-industrys-first-benchmark-for-llm-performance-on-financial-questions) - Questions over public company filings.
* [MedHELM](https://crfm.stanford.edu/helm/medhelm/latest/) - Clinician-validated medical tasks scored with an LLM jury.

### Agents

* [SWE-bench](https://github.com/SWE-bench/SWE-bench) ⭐ 6,038 | 🐛 39 | 🌐 Python | 📅 2026-09-18 - Real GitHub issues that coding agents must resolve.
* [AgentBench](https://github.com/THUDM/AgentBench) ⭐ 3,775 | 🐛 80 | 🌐 Python | 📅 2026-02-08 - LLMs acting as agents across operating system, database, web, and game environments.
* [OSWorld](https://github.com/xlang-ai/OSWorld) ⭐ 3,214 | 🐛 216 | 🌐 Python | 📅 2026-09-14 - Computer tasks in real desktop environments for multimodal agents.
* [tau2-bench](https://github.com/sierra-research/tau2-bench) ⭐ 2,247 | 🐛 270 | 🌐 Python | 📅 2026-10-16 - Customer-service simulations testing tool use and policy adherence against a simulated user.
* [MLE-bench](https://github.com/openai/mle-bench) ⭐ 1,776 | 🐛 13 | 🌐 Python | 📅 2026-04-24 - Kaggle competitions measuring agents on machine learning engineering.
* [WebArena](https://github.com/web-arena-x/webarena) ⭐ 1,630 | 🐛 104 | 🌐 Python | 📅 2025-11-26 - Self-hosted websites for evaluating autonomous web agents.
* [BrowserGym](https://github.com/ServiceNow/BrowserGym) ⭐ 1,406 | 🐛 42 | 🌐 Python | 📅 2026-10-05 - Gym environment for web agents with access to WebArena, WorkArena, and other benchmarks.
* [ClawBench](https://github.com/TIGER-AI-Lab/ClawBench) ⭐ 1,056 | 🐛 47 | 🌐 Python | 📅 2026-10-17 - Browser agents on everyday tasks across live websites, with full action and HTTP traces.
* [Terminal-Bench](https://github.com/harbor-framework/terminal-bench) ⭐ 917 | 🐛 410 | 🌐 Python | 📅 2026-10-15 - Continuously updated benchmark of difficult command-line tasks for agents.
* [MetaTool](https://github.com/HowieHwong/MetaTool) ⭐ 121 | 🐛 1 | 🌐 Python | 📅 2024-03-21 - Tests whether models know when to use a tool and which one to pick.
* [SuperCLUE-Agent](https://github.com/CLUEbenchmark/SuperCLUE-Agent) ⭐ 96 | 🐛 8 | 📅 2023-11-09 - Chinese agent evaluation covering tool use, planning, and memory.
* [AstaBench](https://allenai.org/blog/astabench) - Scientific research tasks covering literature review, replication, and data analysis.
* [BrowseComp](https://openai.com/index/browsecomp/) - Questions that require persistent web browsing to answer.
* [ColBench](https://arxiv.org/abs/2503.15478) - Multi-turn collaborative coding and design tasks with a simulated human partner.
* [Context-Bench](https://www.letta.com/blog/context-bench) - Measures how well agents manage context and memory.
* [DPAI Arena](https://dpaia.dev/) - Benchmark for developer agents across languages and engineering workflows.
* [GAIA](https://huggingface.co/datasets/gaia-benchmark/GAIA) - General assistant questions requiring web access, tools, and planning.
* [SWE-bench Live](https://swe-bench-live.github.io/) - Continuously refreshed issues to limit contamination.
* [SWE-bench Pro](https://labs.scale.com/leaderboard/swe_bench_pro) - Long-horizon coding problems drawn from public, commercial, and held-out repositories.

### Multimodal

* [MMT-Bench](https://github.com/OpenGVLab/MMT-Bench) ⭐ 119 | 🐛 1 | 🌐 Python | 📅 2026-04-06 - 31K+ questions across image, text, video, and point-cloud inputs.
* [MERLIM](https://arxiv.org/abs/2312.02219) - 300K+ image-question pairs targeting cross-modal hallucination.
* [MME](https://arxiv.org/abs/2306.13394) - Perception and cognition across 14 subtasks.
* [MMMU-Pro](https://mmmu-benchmark.github.io/) - Harder version of MMMU with expert-level multimodal questions.
* [Video-MME](https://video-mme.github.io/) - Video understanding across short, medium, and long clips.

### Safety

* [AdvBench](https://github.com/llm-attacks/llm-attacks) ⭐ 4,833 | 🐛 69 | 🌐 Python | 📅 2024-08-02 - Harmful behaviors and strings for measuring jailbreak resistance.
* [HarmBench](https://github.com/centerforaisafety/HarmBench) ⭐ 1,073 | 🐛 41 | 🌐 Jupyter Notebook | 📅 2024-08-16 - Standardized evaluation of automated red teaming methods and model robustness.
* [TruthfulQA](https://github.com/sylinrl/TruthfulQA) ⭐ 952 | 🐛 22 | 🌐 Jupyter Notebook | 📅 2025-01-16 - Adversarially written questions that tempt models into common falsehoods.
* [JailbreakBench](https://github.com/JailbreakBench/jailbreakbench) ⭐ 687 | 🐛 12 | 🌐 Python | 📅 2025-04-04 - Robustness benchmark with a jailbreak artifact repository and leaderboard.
* [Anthropic Model-Written Evals](https://github.com/anthropics/evals) ⭐ 439 | 🐛 2 | 📅 2024-07-02 - Model-written datasets for testing persona, sycophancy, and AI risk behaviors.
* [BBQ](https://github.com/nyu-mll/BBQ) ⭐ 153 | 🐛 8 | 🌐 Python | 📅 2024-01-08 - Question sets measuring reliance on social stereotypes.
* [SimpleSafetyTests](https://huggingface.co/datasets/Bertievidgen/SimpleSafetyTests) - 100 prompts covering five critical harm areas.

## Leaderboards

* [ARC Prize Leaderboard](https://arcprize.org/leaderboard) - ARC-AGI scores for frontier models and open submissions.
* [Arena](https://arena.ai/) - Crowdsourced head-to-head model voting, formerly LMArena.
* [CompassRank](https://rank.opencompass.org.cn/home) - OpenCompass rankings across multi-domain suites.
* [HELM Leaderboards](https://crfm.stanford.edu/helm/latest/) - Stanford results across HELM scenarios and metrics.
* [Open LLM Leaderboard](https://huggingface.co/spaces/open-llm-leaderboard/open_llm_leaderboard) - Hugging Face rankings of open models on IFEval, MMLU-Pro, GPQA, and more.
* [Open Medical-LLM Leaderboard](https://huggingface.co/blog/leaderboard-medicalllm) - Hugging Face rankings on medical question answering.
* [Scale SEAL Leaderboard](https://scale.com/leaderboard) - Expert-rated rankings for reasoning, coding, and safety.

## Resources

### Papers

* [LLM-as-a-Judge Survey](https://arxiv.org/abs/2411.15594) - Survey on building reliable LLM judges and mitigating their biases.
* [RAG Evaluation Survey](https://arxiv.org/abs/2405.07437) - Survey of metrics, judgments, and open problems in evaluating RAG.
* [Who Validates the Validators?](https://arxiv.org/abs/2404.12272) - Paper on aligning LLM judges with human criteria through the EvalGen workflow.

### Guides

* [OpenAI Cookbook Evals](https://github.com/openai/openai-cookbook/tree/main/examples/evals) ⭐ 76,659 | 🐛 320 | 🌐 Jupyter Notebook | 📅 2026-10-17 - Notebooks showing how to build custom evals.
* [AI Evals for Engineers & PMs](https://maven.com/parlance-labs/evals) - Cohort course by Hamel Husain and Shreya Shankar.
* [AlignEval](https://eugeneyan.com/writing/aligneval/) - Eugene Yan on building and aligning LLM judges.
* [Applied LLMs](https://applied-llms.org/) - Lessons from a year of building with LLMs, with evaluation as a core practice.
* [Comparing LLMs on Real-World Retrieval](https://www.sh-reya.com/blog/needle-in-the-real-world/) - How models perform on practical retrieval tasks.
* [Data Flywheels for LLM Applications](https://www.sh-reya.com/blog/ai-engineering-flywheel/) - Iterative data improvement for LLM systems.
* [Eval Tools Comparison](https://hamel.dev/blog/posts/eval-tools/) - Comparison of Braintrust, LangSmith, and Promptfoo.
* [Evals for AI Engineers](https://www.oreilly.com/library/view/evals-for-ai/9798341660717/) - O'Reilly book on error analysis, evaluation pipelines, and LLM judges.
* [EvalScope RAG](https://evalscope.readthedocs.io/en/latest/blog/RAG/RAG_Evaluation.html) - Tutorial on evaluating RAG applications with Ragas, from the EvalScope documentation.
* [Field Guide to Rapidly Improving AI Products](https://hamel.dev/blog/posts/field-guide/) - Error analysis, data viewers, and systematic improvement from 30+ implementations.
* [KDD 2025 Tutorial: Evaluation & Benchmarking of LLM Agents](https://sap-samples.github.io/llm-agents-eval-tutorial/) - Academic tutorial on agent evaluation methodology.
* [LLM Evals FAQ](https://hamel.dev/blog/posts/evals-faq/) - Answers to common evaluation questions from practitioners.
* [LLM Evaluators Survey](https://eugeneyan.com/writing/llm-evaluators/) - Survey of LLM judge use cases and implementation patterns.
* [LLM-as-a-Judge Guide](https://hamel.dev/blog/posts/llm-judge/) - Using LLMs as judges, with calibration advice.
* [Mastering LLMs Open Course](https://parlance-labs.com/education/) - Free course covering evals, RAG, and fine-tuning.
* [Microsoft Foundry Safety Evaluations Transparency Note](https://learn.microsoft.com/en-us/azure/foundry/concepts/safety-evaluations-transparency-note) - Microsoft documentation of how the safety evaluators work and where they fall short.
* [Open Source LLM Tools Comparison](https://posthog.com/blog/best-open-source-llm-observability-tools) - PostHog comparison of open-source observability and evaluation tools.
* [Why AI Evals Are the Hottest New Skill](https://www.lennysnewsletter.com/p/why-ai-evals-are-the-hottest-new-skill) - Interview covering error analysis, axial coding, and eval prompts.
* [Your AI Product Needs Evals](https://hamel.dev/blog/posts/evals/) - Why every AI product needs systematic evaluation.
* [ZenML Evaluation Playbook](https://www.zenml.io/blog/the-evaluation-playbook-making-llms-production-ready) - Guide to adding evaluation gates to pipelines and deployments.

### Lists

* [awesome-evals](https://github.com/benchflow-ai/awesome-evals) ⭐ 986 | 🐛 59 | 📅 2026-10-09 - Resources for building and evaluating AI agents.
* [Awesome-LLM-Eval](https://github.com/onejune2018/Awesome-LLM-Eval) ⭐ 659 | 🐛 65 | 📅 2025-11-24 - Evaluation tools, papers, datasets, and leaderboards, in Chinese and English.
* [Awesome-RAG-Evaluation](https://github.com/YHPeter/Awesome-RAG-Evaluation) ⭐ 200 | 🐛 6 | 🌐 TeX | 📅 2025-04-25 - RAG evaluation metrics, datasets, and leaderboards.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md).

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-10-17._
