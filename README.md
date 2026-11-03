# Awesome AI Eval with stars

[<img src="./assets/robot-shades.svg" align="right" width="120" alt="Robot wearing pink shades">](https://github.com/Vvkmnn/awesome-ai-eval)

> Assessing the reliability, accuracy, and safety of large language models, RAG pipelines, and AI agents.

## Contents

* [Benchmarks](#benchmarks)
  * [Agents](#agents)
  * [General](#general)
  * [Long-Context](#long-context)
  * [Multimodal](#multimodal)
  * [Safety](#safety)
  * [Specialized](#specialized)
* [Leaderboards](#leaderboards)
* [Platforms](#platforms)
  * [Cloud](#cloud)
  * [Managed](#managed)
  * [Self-Hosted](#self-hosted)
* [Resources](#resources)
  * [Guides](#guides)
  * [Lists](#lists)
  * [Papers](#papers)
* [Tools](#tools)
  * [Adversarial](#adversarial)
  * [Frameworks](#frameworks)
  * [Retrieval](#retrieval)

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md).

## Benchmarks

### Agents

* [SWE-bench](https://github.com/SWE-bench/SWE-bench) ⭐ 6,139 | 🐛 59 | 🌐 Python | 📅 2026-09-18 - Real GitHub issues that coding agents must resolve.
* [AgentBench](https://github.com/THUDM/AgentBench) ⭐ 3,808 | 🐛 80 | 🌐 Python | 📅 2026-02-08 - LLMs acting as agents across operating system, database, web, and game environments.
* [OSWorld](https://github.com/xlang-ai/OSWorld) ⭐ 3,250 | 🐛 170 | 🌐 Python | 📅 2026-11-02 - Computer tasks in real desktop environments for multimodal agents.
* [tau2-bench](https://github.com/sierra-research/tau2-bench) ⭐ 2,386 | 🐛 338 | 🌐 Python | 📅 2026-11-02 - Customer-service simulations testing tool use and policy adherence against a simulated user.
* [MLE-bench](https://github.com/openai/mle-bench) ⭐ 1,789 | 🐛 16 | 🌐 Python | 📅 2026-04-24 - Kaggle competitions measuring agents on machine learning engineering.
* [WebArena](https://github.com/web-arena-x/webarena) ⭐ 1,640 | 🐛 106 | 🌐 Python | 📅 2025-11-26 - Self-hosted websites for evaluating autonomous web agents.
* [BrowserGym](https://github.com/ServiceNow/BrowserGym) ⭐ 1,426 | 🐛 48 | 🌐 Python | 📅 2026-10-28 - Gym environment for web agents with access to WebArena, WorkArena, and other benchmarks.
* [OpenAI Frontier Evals](https://github.com/openai/frontier-evals) ⭐ 1,333 | 🐛 75 | 🌐 Python | 📅 2026-10-12 - PaperBench, SWE-Lancer, and EVMbench: paper replication, freelance coding, and smart contract security tasks.
* [ClawBench](https://github.com/TIGER-AI-Lab/ClawBench) ⭐ 1,193 | 🐛 100 | 🌐 Python | 📅 2026-10-23 - Browser agents on everyday tasks across live websites, with full action and HTTP traces.
* [Terminal-Bench](https://github.com/harbor-framework/terminal-bench) ⭐ 1,003 | 🐛 488 | 🌐 Python | 📅 2026-11-03 - Continuously updated benchmark of difficult command-line tasks for agents.
* [DeepResearch Bench](https://github.com/Ayanami0730/deep_research_bench) ⭐ 848 | 🐛 24 | 🌐 Python | 📅 2026-09-29 - PhD-level research tasks for scoring deep research agents on report quality and citations.
* [MCP-Universe](https://github.com/SalesforceAIResearch/MCP-Universe) ⭐ 603 | 🐛 36 | 🌐 Python | 📅 2026-10-08 - Benchmark and framework for evaluating agents on real Model Context Protocol servers.
* [AppWorld](https://github.com/StonyBrookNLP/appworld) ⭐ 546 | 🐛 16 | 🌐 Python | 📅 2026-09-04 - Controllable world of apps and simulated people for benchmarking function calling and interactive coding agents.
* [MetaTool](https://github.com/HowieHwong/MetaTool) ⭐ 121 | 🐛 1 | 🌐 Python | 📅 2024-03-21 - Tests whether models know when to use a tool and which one to pick.
* [SuperCLUE-Agent](https://github.com/CLUEbenchmark/SuperCLUE-Agent) ⭐ 96 | 🐛 8 | 📅 2023-11-09 - Chinese agent evaluation covering tool use, planning, and memory.
* [ShopPay Audit Benchmark](https://github.com/Dmatut7/shoppay-audit-benchmark) ⭐ 1 | 🐛 7 | 🌐 JavaScript | 📅 2026-06-05 - Spec-grounded business-logic audit tasks for coding agents.
* [Agent Retry Rodeo](https://github.com/RishabhPande/agent-retry-rodeo) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-10-31 - Local test range that replays lost acknowledgements and partial failures, then checks an agent's final state.
* [TIB-AK79](https://github.com/andruwka79-cloud/tib-ak79) ⭐ 0 | 🐛 1 | 🌐 Python | 📅 2026-10-29 - Scores what agent actions changed in a mock environment and checks the agent's claims against the result.
* [AstaBench](https://allenai.org/blog/astabench) - Scientific research tasks covering literature review, replication, and data analysis.
* [Berkeley Function Calling Leaderboard](https://gorilla.cs.berkeley.edu/leaderboard.html) - Measures how accurately models call functions and tools.
* [BrowseComp](https://openai.com/index/browsecomp/) - Questions that require persistent web browsing to answer.
* [ColBench](https://arxiv.org/abs/2503.15478) - Multi-turn collaborative coding and design tasks with a simulated human partner.
* [Context-Bench](https://www.letta.com/blog/context-bench) - Measures how well agents manage context and memory.
* [DPAI Arena](https://dpaia.dev/) - Benchmark for developer agents across languages and engineering workflows.
* [GAIA](https://huggingface.co/datasets/gaia-benchmark/GAIA) - General assistant questions requiring web access, tools, and planning.
* [SWE-bench Live](https://swe-bench-live.github.io/) - Continuously refreshed issues to limit contamination.
* [SWE-bench Pro](https://labs.scale.com/leaderboard/swe_bench_pro) - Long-horizon coding problems drawn from public, commercial, and held-out repositories.

### General

* [IFEval](https://github.com/google-research/google-research/tree/master/instruction_following_eval) ⭐ 39,097 | 🐛 2,009 | 🌐 Jupyter Notebook | 📅 2026-10-30 - Prompts with verifiable constraints for checking instruction compliance.
* [Humanity's Last Exam](https://github.com/centerforaisafety/hle) ⭐ 1,738 | 🐛 10 | 🌐 Python | 📅 2026-09-23 - Expert-written closed-ended questions across academic subjects.
* [MMLU](https://github.com/hendrycks/test) ⭐ 1,626 | 🐛 18 | 🌐 Python | 📅 2023-05-28 - Multiple-choice questions across academic and professional subjects. The standard knowledge benchmark; complete and no longer updated.
* [LiveBench](https://github.com/LiveBench/LiveBench) ⭐ 1,352 | 🐛 186 | 🌐 Python | 📅 2026-10-18 - Contamination-limited benchmark with regularly refreshed questions and objective scoring.
* [AGIEval](https://github.com/ruixiangcui/AGIEval) ⭐ 777 | 🐛 9 | 🌐 Python | 📅 2024-06-13 - Human-centric exams spanning admission tests, law, and math.
* [RewardBench](https://github.com/allenai/reward-bench) ⭐ 748 | 🐛 5 | 🌐 Python | 📅 2026-10-14 - Benchmark and leaderboard for evaluating reward models.
* [GPQA](https://github.com/idavidrein/gpqa) ⭐ 546 | 🐛 14 | 🌐 Jupyter Notebook | 📅 2024-09-30 - Graduate-level science questions written by experts and designed to resist web search.
* [MMLU-Pro](https://github.com/TIGER-AI-Lab/MMLU-Pro) ⭐ 433 | 🐛 14 | 🌐 Python | 📅 2026-03-18 - Harder ten-option extension of MMLU focused on reasoning.
* [LLM-Uncertainty-Bench](https://github.com/smartyfh/LLM-Uncertainty-Bench) ⭐ 263 | 🐛 1 | 🌐 Python | 📅 2024-01-30 - Uncertainty-aware scoring across QA, reading comprehension, inference, dialog, and summarization.
* [LLMBar](https://github.com/princeton-nlp/LLMBar) ⭐ 143 | 🐛 1 | 🌐 Python | 📅 2024-07-08 - Meta-evaluation of whether LLM judges can spot instruction-following failures.
* [CommonGen-Eval](https://github.com/allenai/CommonGen-Eval) ⭐ 94 | 🐛 1 | 🌐 Python | 📅 2024-03-21 - GPT-4 judged suite for constrained commonsense text generation.
* [StructEval](https://github.com/TIGER-AI-Lab/StructEval) ⭐ 24 | 🐛 6 | 🌐 Python | 📅 2026-10-22 - Structured-output generation and conversion across 18 text and renderable formats.
* [PertEval](https://github.com/aigc-apps/PertEval) ⭐ 14 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2024-10-30 - Knowledge-invariant perturbations that expose inflated multiple-choice accuracy.
* [ARC-AGI-2](https://arcprize.org/arc-agi/2/) - Abstract reasoning puzzles that are easy for people and hard for models.
* [ARC-AGI-3](https://arcprize.org/arc-agi/3/) - Interactive reasoning benchmark of novel game environments in which agents must discover the goals.
* [DyVal](https://arxiv.org/abs/2309.17167) - Dynamically generated reasoning tasks with controllable difficulty.
* [GDPval](https://arxiv.org/abs/2510.04374) - Economically valuable tasks built from the work of professionals in 44 occupations.
* [JudgeBench](https://arxiv.org/abs/2410.12784) - Benchmark for LLM judges on hard response pairs across knowledge, reasoning, math, and coding.
* [SimpleBench](https://simple-bench.com/) - Everyday reasoning questions where people still outperform frontier models.
* [SimpleQA](https://arxiv.org/abs/2411.04368) - Short fact-seeking questions with a single indisputable answer, for measuring factuality.

### Long-Context

* [RULER](https://github.com/NVIDIA/RULER) ⭐ 1,630 | 🐛 25 | 🌐 Python | 📅 2026-07-22 - Synthetic long-context tasks with configurable sequence length.
* [InfiniteBench](https://github.com/OpenBMB/InfiniteBench) ⭐ 393 | 🐛 13 | 🌐 Python | 📅 2024-09-25 - Twelve tasks with average context length beyond 100K tokens.
* [LV-Eval](https://github.com/infinigence/LVEval) ⭐ 78 | 🐛 7 | 🌐 Python | 📅 2024-08-31 - Five length tiers up to 256K words with distraction controls.
* [LongBench v2](https://longbench2.github.io/) - Questions over contexts from 8K to 2M words in six task categories.
* [LongGenBench](https://arxiv.org/abs/2409.02076) - Long-form generation benchmark for long-context models.

### Multimodal

* [MMT-Bench](https://github.com/OpenGVLab/MMT-Bench) ⭐ 119 | 🐛 1 | 🌐 Python | 📅 2026-04-06 - 31K+ questions across image, text, video, and point-cloud inputs.
* [MERLIM](https://arxiv.org/abs/2312.02219) - 300K+ image-question pairs targeting cross-modal hallucination.
* [MME](https://arxiv.org/abs/2306.13394) - Perception and cognition across 14 subtasks.
* [MMMU-Pro](https://mmmu-benchmark.github.io/) - Harder version of MMMU with expert-level multimodal questions.
* [PaperEdits Agentic Video Benchmark](https://paperedits.com/benchmarking/gemini-agentic-video-understanding-benchmark) - Exploratory benchmark of agentic and static video processing on long-form editing tasks.
* [Video-MME](https://video-mme.github.io/) - Video understanding across short, medium, and long clips.

### Safety

* [AdvBench](https://github.com/llm-attacks/llm-attacks) ⭐ 4,850 | 🐛 69 | 🌐 Python | 📅 2024-08-02 - Harmful behaviors and strings for measuring jailbreak resistance.
* [CyberSecEval](https://github.com/meta-llama/PurpleLlama/tree/main/CybersecurityBenchmarks) ⭐ 4,462 | 🐛 90 | 🌐 Python | 📅 2026-10-30 - Meta benchmarks measuring cybersecurity risks and defensive capabilities of language models.
* [HarmBench](https://github.com/centerforaisafety/HarmBench) ⭐ 1,083 | 🐛 42 | 🌐 Jupyter Notebook | 📅 2024-08-16 - Standardized evaluation of automated red teaming methods and model robustness.
* [TruthfulQA](https://github.com/sylinrl/TruthfulQA) ⭐ 958 | 🐛 22 | 🌐 Jupyter Notebook | 📅 2025-01-16 - Adversarially written questions that tempt models into common falsehoods.
* [JailbreakBench](https://github.com/JailbreakBench/jailbreakbench) ⭐ 692 | 🐛 12 | 🌐 Python | 📅 2025-04-04 - Robustness benchmark with a jailbreak artifact repository and leaderboard.
* [Anthropic Model-Written Evals](https://github.com/anthropics/evals) ⭐ 443 | 🐛 2 | 📅 2024-07-02 - Model-written datasets for testing persona, sycophancy, and AI risk behaviors.
* [Cybench](https://github.com/andyzorigin/cybench) ⭐ 353 | 🐛 92 | 🌐 HTML | 📅 2026-10-17 - Capture-the-flag tasks for evaluating the cybersecurity capabilities and risks of agents.
* [BBQ](https://github.com/nyu-mll/BBQ) ⭐ 155 | 🐛 8 | 🌐 Python | 📅 2024-01-08 - Question sets measuring reliance on social stereotypes.
* [SimpleSafetyTests](https://huggingface.co/datasets/Bertievidgen/SimpleSafetyTests) - 100 prompts covering five critical harm areas.

### Specialized

* [MBPP](https://github.com/google-research/google-research/tree/master/mbpp) ⭐ 39,097 | 🐛 2,009 | 🌐 Jupyter Notebook | 📅 2026-10-30 - Entry-level Python programming problems with tests.
* [HumanEval](https://github.com/openai/human-eval) ⭐ 3,422 | 🐛 47 | 🌐 Python | 📅 2026-10-16 - Hand-written programming problems checked by unit tests. Complete and no longer updated.
* [MATH](https://github.com/hendrycks/math) ⭐ 1,395 | 🐛 20 | 🌐 Python | 📅 2025-09-06 - Competition mathematics problems with step-by-step solutions.
* [LiveCodeBench](https://github.com/LiveCodeBench/LiveCodeBench) ⭐ 972 | 🐛 55 | 🌐 Python | 📅 2025-07-16 - Contamination-free code evaluation built from newly published competitive programming problems.
* [FinEval](https://github.com/SUFE-AIFLM-Lab/FinEval) ⭐ 293 | 🐛 5 | 🌐 Python | 📅 2025-06-23 - Chinese financial knowledge and reasoning across regulation, accounting, and markets.
* [LAiW](https://github.com/Dai-shen/LAiW) ⭐ 91 | 🐛 4 | 🌐 Python | 📅 2024-07-03 - Chinese legal benchmark covering retrieval, inference, and case application.
* [FinanceBench](https://www.patronus.ai/announcements/patronus-ai-launches-financebench-the-industrys-first-benchmark-for-llm-performance-on-financial-questions) - Questions over public company filings.
* [FrontierMath](https://epoch.ai/frontiermath) - Epoch AI benchmark of original, exceptionally hard mathematics problems.
* [HealthBench](https://arxiv.org/abs/2505.08775) - Multi-turn health conversations graded against rubrics written by physicians.
* [MedHELM](https://crfm.stanford.edu/helm/medhelm/latest/) - Clinician-validated medical tasks scored with an LLM jury.

## Leaderboards

* [Vectara Hallucination Leaderboard](https://github.com/vectara/hallucination-leaderboard) ⭐ 3,324 | 🐛 22 | 🌐 Python | 📅 2026-10-23 - Ranks LLMs by how often they hallucinate when summarizing short documents.
* [Council of AI GSPC](https://github.com/CSOAI-ORG/councilof-ai) ⭐ 4 | 🐛 96 | 🌐 HTML | 📅 2026-11-03 - Public board of signed AI behaviour measurements across governance and safety axes.
* [ARC Prize Leaderboard](https://arcprize.org/leaderboard) - ARC-AGI scores for frontier models and open submissions.
* [Arena](https://arena.ai/) - Crowdsourced head-to-head model voting, formerly LMArena.
* [CompassRank](https://rank.opencompass.org.cn/home) - OpenCompass rankings across multi-domain suites.
* [Epoch AI Benchmarking Hub](https://epoch.ai/benchmarks) - Epoch AI results for leading models on challenging benchmarks.
* [HELM Leaderboards](https://crfm.stanford.edu/helm/latest/) - Stanford results across HELM scenarios and metrics.
* [ImageBench](https://imagebench.ai/) - Text-to-image comparisons with side-by-side results and published methodology.
* [MathArena](https://matharena.ai/) - Evaluation of LLMs on the latest math competitions, run after each contest.
* [ModelBenchmark](https://modelbenchmark.io) - Public benchmark scores, prices, and context windows gathered per model.
* [Open LLM Leaderboard](https://huggingface.co/spaces/open-llm-leaderboard/open_llm_leaderboard) - Hugging Face rankings of open models on IFEval, MMLU-Pro, GPQA, and more.
* [Open Medical-LLM Leaderboard](https://huggingface.co/blog/leaderboard-medicalllm) - Hugging Face rankings on medical question answering.
* [Scale SEAL Leaderboard](https://scale.com/leaderboard) - Expert-rated rankings for reasoning, coding, and safety.

## Platforms

### Cloud

* [Amazon Bedrock Evaluations](https://aws.amazon.com/bedrock/evaluations/) - Managed scoring of foundation models and RAG pipelines.
* [Google Gen AI Evaluation Service](https://docs.cloud.google.com/gemini-enterprise-agent-platform/models/evaluation-overview) - Rubric-based evaluation of models and agents on Google Cloud.
* [Microsoft Foundry Evaluations](https://learn.microsoft.com/en-us/azure/foundry/how-to/evaluate-generative-ai-app) - Built-in evaluators and reports for generative AI apps.

### Managed

* [Athina AI](https://www.athina.ai/) - Evaluation and monitoring platform with preset evals and VPC deployment.
* [Braintrust](https://www.braintrust.dev/) - Evaluation and observability platform with experiments, datasets, and CI regression tests.
* [ChatIntel](https://chatintel.ai/) - No-code toolkit for evaluating and measuring the consistency of AI output.
* [Confident AI](https://www.confident-ai.com/) - DeepEval-backed platform for scheduled eval suites and production monitoring.
* [Datadog LLM Observability](https://www.datadoghq.com/product/llm-observability/) - LLM traces, quality metrics, and safety signals inside Datadog.
* [Deepchecks LLM Evaluation](https://www.deepchecks.com/solutions/llm-evaluation/) - Managed eval suites with dataset versioning and alerting.
* [Firedrill](https://docs.firedrill.run/) - Simulates AI agents with optional synthetic tools, semantic scoring, exact checks, and retained evidence in customer-owned runners.
* [Future AGI](https://futureagi.com/) - Evaluation, simulation, and optimization platform for multimodal AI systems.
* [Galileo](https://www.galileo.ai/) - Observability and evaluation platform with built-in metrics and guardrails.
* [HoneyHive](https://www.honeyhive.ai/) - Agent observability and evaluation platform with prompt versioning.
* [Jetty](https://jetty.io/) - Runs agent workloads in sandboxes and scores each run with checks and LLM judges.
* [LangSmith](https://smith.langchain.com/) - Tracing, datasets, and batch evals with regression gating.
* [Lunary](https://lunary.ai/) - Observability and prompt management platform for LLM apps.
* [PromptLayer](https://www.promptlayer.com/) - Prompt management with version control and evaluation tracking.
* [Respan](https://www.respan.ai/) - AI gateway with tracing, monitoring, red teaming, and evaluators that score test sets and production traffic.
* [TestMu AI Agent Testing](https://www.testmuai.com/agent-testing/) - Tests chat, voice, and phone agents through simulated conversations and real calls, including their tool calls.
* [W\&B Weave](https://wandb.ai/site/evaluations/) - Evaluation toolkit with dataset versioning, scorers, and comparison dashboards.

### Self-Hosted

* [Langfuse](https://github.com/langfuse/langfuse) ⭐ 36,943 | 🐛 1,100 | 🌐 TypeScript | 📅 2026-11-03 - Engineering platform for tracing, evals, datasets, and prompt management.
* [Opik](https://github.com/comet-ml/opik) ⭐ 23,142 | 🐛 203 | 🌐 Python | 📅 2026-11-03 - Evaluation and observability platform with datasets, scoring jobs, and trace inspection.
* [Arize Phoenix](https://github.com/Arize-ai/phoenix) ⭐ 12,118 | 🐛 1,218 | 🌐 Python | 📅 2026-11-03 - OpenTelemetry-native tracing and evaluation for RAG, LLMs, and agents.
* [Bifrost](https://github.com/maximhq/bifrost) ⭐ 9,317 | 🐛 1,443 | 🌐 Go | 📅 2026-11-03 - Self-hosted AI gateway with LLM-judge guardrails and evaluation integrations such as Patronus AI.
* [Helicone](https://github.com/Helicone/helicone) ⭐ 6,256 | 🐛 188 | 🌐 TypeScript | 📅 2026-10-28 - AI gateway and observability platform with cost tracking and evaluation integrations.
* [Giskard](https://github.com/giskard-ai/giskard-oss) ⭐ 5,941 | 🐛 78 | 🌐 Python | 📅 2026-11-02 - Testing library that scans LLM apps for vulnerabilities and quality issues.
* [Latitude](https://github.com/latitude-dev/latitude-llm) ⭐ 4,744 | 🐛 115 | 🌐 TypeScript | 📅 2026-11-03 - Platform for observing agent traces and tracking recurring failures as issues.
* [OpenLIT](https://github.com/openlit/openlit) ⭐ 2,902 | 🐛 214 | 🌐 TypeScript | 📅 2026-11-03 - OpenTelemetry instrumentation for LLM apps with quality metrics and guardrail hooks.
* [Rhesis](https://github.com/rhesis-ai/rhesis) ⭐ 402 | 🐛 46 | 🌐 Python | 📅 2026-11-03 - Collaborative testing platform with test generation and multi-turn conversation simulation.
* [Zeno](https://zenoml.com/) - Evaluation UI for slicing failures and comparing models and prompts.

## Resources

### Guides

* [OpenAI Cookbook Evals](https://github.com/openai/openai-cookbook/tree/main/examples/evals) ⭐ 76,935 | 🐛 349 | 🌐 Jupyter Notebook | 📅 2026-11-03 - Notebooks showing how to build custom evals.
* [AI Failure Mode Taxonomy](https://github.com/prashibadkur11-creator/ai-failure-mode-taxonomy) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-08-08 - Catalog of AI and LLM product failure modes with detection and mitigation for each.
* [AI Evals for Engineers & PMs](https://maven.com/parlance-labs/evals) - Cohort course by Hamel Husain and Shreya Shankar.
* [AlignEval](https://eugeneyan.com/writing/aligneval/) - Eugene Yan on building and aligning LLM judges.
* [Applied LLMs](https://applied-llms.org/) - Lessons from a year of building with LLMs, with evaluation as a core practice.
* [Comparing LLMs on Real-World Retrieval](https://www.sh-reya.com/blog/needle-in-the-real-world/) - How models perform on practical retrieval tasks.
* [Data Flywheels for LLM Applications](https://www.sh-reya.com/blog/ai-engineering-flywheel/) - Iterative data improvement for LLM systems.
* [Demystifying Evals for AI Agents](https://www.anthropic.com/engineering/demystifying-evals-for-ai-agents) - Anthropic guide to grader types, consistency metrics, and building an agent eval suite.
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

* [LLM Evaluation Survey](https://github.com/MLGroupJLU/LLM-eval-survey) ⭐ 1,615 | 🐛 6 | 📅 2026-10-28 - Papers organized by the survey "A Survey on Evaluation of Large Language Models".
* [Awesome Agent Evals](https://github.com/benchflow-ai/awesome-evals) ⭐ 1,022 | 🐛 76 | 📅 2026-10-27 - Annotated papers, posts, talks, tools, and benchmarks for building and evaluating AI agents.
* [Awesome-LLM-Eval](https://github.com/onejune2018/Awesome-LLM-Eval) ⭐ 659 | 🐛 71 | 📅 2025-11-24 - Evaluation tools, papers, datasets, and leaderboards, in Chinese and English.
* [Awesome-LLM-as-a-judge](https://github.com/llm-as-a-judge/Awesome-LLM-as-a-judge) ⭐ 583 | 🐛 6 | 📅 2026-05-21 - Papers on using LLMs as judges, from the accompanying survey.
* [Awesome-RAG-Evaluation](https://github.com/YHPeter/Awesome-RAG-Evaluation) ⭐ 200 | 🐛 5 | 🌐 TeX | 📅 2026-10-25 - RAG evaluation metrics, datasets, and leaderboards.
* [LLM-Agent-Benchmark-List](https://github.com/zhangxjohn/LLM-Agent-Benchmark-List) ⭐ 173 | 🐛 5 | 📅 2026-10-27 - Benchmarks for evaluating LLMs and LLM-based agents.
* [Awesome Red Teaming LLMs](https://github.com/dapurv5/awesome-red-teaming-llms) ⭐ 52 | 🐛 2 | 📅 2026-08-05 - Papers on red teaming language models, from a survey accepted at TMLR.

### Papers

* [Adding Error Bars to Evals](https://arxiv.org/abs/2411.00640) - Statistical methods for analyzing and reporting uncertainty in language model evaluations.
* [Don't Pass@k](https://arxiv.org/abs/2510.04265) - Bayesian framework that reports LLM evaluation results with uncertainty in place of pass\@k.
* [Establishing Best Practices for Building Rigorous Agentic Benchmarks](https://arxiv.org/abs/2507.02825) - Checklist for avoiding task and reward design flaws in agent benchmarks.
* [LLM-as-a-Judge Survey](https://arxiv.org/abs/2411.15594) - Survey on building reliable LLM judges and mitigating their biases.
* [RAG Evaluation Survey](https://arxiv.org/abs/2405.07437) - Survey of metrics, judgments, and open problems in evaluating RAG.
* [The Leaderboard Illusion](https://arxiv.org/abs/2504.20879) - Analysis of systematic issues that distort Chatbot Arena rankings.
* [What's Missing in Autonomous Research?](https://www.researchgate.net/publication/406952713) - Survey mapping autonomous research systems against their benchmarks and verification methods.
* [Who Validates the Validators?](https://arxiv.org/abs/2404.12272) - Paper on aligning LLM judges with human criteria through the EvalGen workflow.

## Tools

### Adversarial

* [Garak](https://github.com/NVIDIA/garak) ⭐ 9,842 | 🐛 542 | 🌐 Python | 📅 2026-11-02 - NVIDIA vulnerability scanner that probes LLMs for prompt injection, leakage, and jailbreaks.
* [PyRIT](https://github.com/microsoft/PyRIT) ⭐ 4,734 | 🐛 292 | 🌐 Python | 📅 2026-11-03 - Microsoft toolkit for automating attack strategies against generative AI systems.
* [DeepTeam](https://github.com/confident-ai/deepteam) ⭐ 3,084 | 🐛 82 | 🌐 Python | 📅 2026-10-23 - Red teaming framework for bias, data leakage, and prompt-injection vulnerabilities.
* [Petri](https://github.com/meridianlabs-ai/inspect_petri) ⭐ 1,402 | 🐛 43 | 🌐 Python | 📅 2026-11-01 - Auditing agent that explores model behavior through simulated multi-turn scenarios.
* [AgentDojo](https://github.com/ethz-spylab/agentdojo) ⭐ 984 | 🐛 96 | 🌐 Python | 📅 2026-06-02 - Environment for testing prompt-injection attacks and defenses on tool-using agents.

### Frameworks

* [ColossalEval](https://github.com/hpcaitech/ColossalAI/tree/main/applications/ColossalEval) ⭐ 41,434 | 🐛 489 | 🌐 Python | 📅 2026-11-03 - Pipeline combining classic metrics with GPT-assisted scoring across public datasets.
* [MLflow](https://github.com/mlflow/mlflow) ⭐ 28,643 | 🐛 2,225 | 🌐 Python | 📅 2026-11-03 - Evaluation API that logs judge scores alongside experiment tracking runs.
* [Promptfoo](https://github.com/promptfoo/promptfoo) ⭐ 26,775 | 🐛 907 | 🌐 TypeScript | 📅 2026-11-03 - CLI for testing and red teaming prompts, RAG flows, and agents with regression detection.
* [OpenAI Evals](https://github.com/openai/evals) ⭐ 19,691 | 🐛 351 | 🌐 Python | 📅 2026-04-14 - Framework and registry of evals for LLMs and LLM systems.
* [DeepEval](https://github.com/confident-ai/deepeval) ⭐ 19,270 | 🐛 800 | 🌐 Python | 📅 2026-11-02 - Unit-test style metrics for hallucination, relevance, toxicity, and bias.
* [LM Evaluation Harness](https://github.com/EleutherAI/lm-evaluation-harness) ⭐ 14,386 | 🐛 1,286 | 🌐 Python | 📅 2026-09-14 - Harness for running language models on hundreds of academic benchmarks.
* [Prompt Flow](https://github.com/microsoft/promptflow) ⭐ 11,260 | 🐛 71 | 🌐 Python | 📅 2026-10-31 - Flow builder with built-in evaluation flows and CI integration.
* [Evidently](https://github.com/evidentlyai/evidently) ⭐ 8,032 | 🐛 353 | 🌐 Jupyter Notebook | 📅 2026-09-29 - Evaluation and monitoring library for ML and LLM systems.
* [OpenCompass](https://github.com/open-compass/opencompass) ⭐ 7,563 | 🐛 337 | 🌐 Python | 📅 2026-11-03 - Evaluation platform with LLM judge support across knowledge, reasoning, and coding datasets.
* [Harbor](https://github.com/harbor-framework/harbor) ⭐ 6,753 | 🐛 1,208 | 🌐 Python | 📅 2026-11-03 - Framework for evaluating and optimizing agents and models in containers; the official Terminal-Bench 2.0 harness.
* [OpenAI simple-evals](https://github.com/openai/simple-evals) ⭐ 4,691 | 🐛 77 | 🌐 Python | 📅 2026-04-22 - Reference implementations of standard benchmarks such as MMLU, GPQA, and HumanEval.
* [lmms-eval](https://github.com/EvolvingLMMs-Lab/lmms-eval) ⭐ 4,479 | 🐛 34 | 🌐 Python | 📅 2026-11-03 - Multimodal evaluation toolkit covering text, image, video, and audio tasks.
* [EvalScope](https://github.com/modelscope/evalscope) ⭐ 3,640 | 🐛 17 | 🌐 Python | 📅 2026-11-03 - ModelScope framework for evaluating and benchmarking LLMs, vision-language models, and generative models.
* [TruLens](https://github.com/truera/trulens) ⭐ 3,626 | 🐛 135 | 🌐 Python | 📅 2026-11-03 - Feedback functions for evaluating and tracing chains and agents.
* [Inspect AI](https://github.com/UKGovernmentBEIS/inspect_ai) ⭐ 3,157 | 🐛 506 | 🌐 Python | 📅 2026-11-03 - UK AI Security Institute framework for scripted evals with tool calls and model-graded scoring.
* [ChainForge](https://github.com/ianarawjo/ChainForge) ⭐ 3,040 | 🐛 70 | 🌐 TypeScript | 📅 2026-10-29 - Visual environment for comparing prompts and models and scoring responses.
* [HELM](https://github.com/stanford-crfm/helm) ⭐ 2,964 | 🐛 120 | 🌐 Python | 📅 2026-09-01 - Stanford framework for evaluating foundation models across scenarios and metrics.
* [lighteval](https://github.com/huggingface/lighteval) ⭐ 2,578 | 🐛 480 | 🌐 Python | 📅 2026-10-29 - Hugging Face toolkit for evaluating LLMs across many backends and tasks.
* [Bloom](https://github.com/safety-research/bloom) ⭐ 1,427 | 🐛 9 | 🌐 Python | 📅 2026-05-07 - Agentic framework that generates behavioral evaluations of frontier models from a described behavior.
* [openevals](https://github.com/langchain-ai/openevals) ⭐ 1,242 | 🐛 24 | 🌐 Python | 📅 2026-11-02 - Evaluators for LLM apps, including LLM judge and structured-output checks.
* [autoevals](https://github.com/braintrustdata/autoevals) ⭐ 1,070 | 🐛 56 | 🌐 Python | 📅 2026-10-30 - Scorers for LLM outputs, from string heuristics to model-graded factuality, in Python and TypeScript.
* [OpenJudge](https://github.com/agentscope-ai/OpenJudge) ⭐ 1,035 | 🐛 13 | 🌐 Python | 📅 2026-11-03 - Framework of graders for evaluating agents and chatbots and producing quality rewards.
* [Inspect Evals](https://github.com/UKGovernmentBEIS/inspect_evals) ⭐ 732 | 🐛 260 | 🌐 Python | 📅 2026-11-03 - Community-maintained collection of evaluations implemented in Inspect AI.
* [agenttrace](https://github.com/luoyuctl/agenttrace) ⭐ 154 | 🐛 5 | 🌐 Rust | 📅 2026-11-02 - Terminal UI for reviewing coding-agent sessions by cost, failures, latency, and diffs.
* [skill-optimizer](https://github.com/fastxyz/skill-optimizer) ⭐ 83 | 🐛 15 | 🌐 TypeScript | 📅 2026-05-28 - Docker workbench and agent skill for running deterministic evals against agent skills.
* [Aleph Alpha Eval Framework](https://github.com/Aleph-Alpha-Research/eval-framework) ⭐ 46 | 🐛 12 | 🌐 Python | 📅 2026-11-03 - Evaluation framework with built-in benchmarks for reasoning, coding, and safety.
* [Agentrial](https://github.com/alepot55/agentrial) ⭐ 20 | 🐛 0 | 🌐 Python | 📅 2026-02-06 - Runs agents repeatedly, computes confidence intervals, and flags regressions in CI.
* [digline](https://github.com/digline/digline) ⭐ 9 | 🐛 2 | 🌐 Python | 📅 2026-11-03 - Regression testing for LLM apps against a versioned baseline of approved scores.
* [Agent Stack](https://github.com/MukundaKatta/agent-stack) ⭐ 6 | 🐛 0 | 🌐 HTML | 📅 2026-06-13 - Libraries for agent reliability, including snapshot tests for tool-call traces, tool-argument validation, and structured output with retry.
* [Voice Eval](https://github.com/rand0wn/voice-eval) ⭐ 6 | 🐛 26 | 🌐 Python | 📅 2026-08-19 - Regression harness for voice agents using scripted multi-turn scenarios.
* [semantix-ai](https://github.com/labrat-akhona/semantix-ai) ⭐ 5 | 🐛 2 | 🌐 Python | 📅 2026-09-16 - NLI judges, datasets, and audit trails for checking LLM outputs against regulatory clauses.
* [agentest](https://github.com/srpadmanabhuni/agentest) ⭐ 2 | 🐛 8 | 🌐 Python | 📅 2026-11-02 - Offline, deterministic checks of agent OpenTelemetry traces, A2A AgentCards, and MCP tools, with no LLM judge.
* [AI Eval Forge](https://github.com/MukundaKatta/ai-eval-forge) ⭐ 1 | 🐛 4 | 🌐 Python | 📅 2026-07-25 - Regression harness for LLM and agent outputs using deterministic checks such as regex, token F1, and JSON validity.
* [align](https://github.com/ggrigo/align) ⭐ 1 | 🐛 3 | 🌐 HTML | 📅 2026-07-18 - Human-in-the-loop evals for Claude Code that rate individual claims and archive corrections.
* [AI Prompt Quality](https://github.com/pntkrl/ai-prompt-quality) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-10-01 - Static prompt evaluation with a seven-dimension rubric and JSON scoring schema.
* [fact-gate](https://github.com/AnonZ7/fact-gate) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-09-23 - Deterministic verification of AI-written text against diffs, measured facts, or prose.
* [Narrative Scorer](https://github.com/cittaverse/narrative-scorer) ⭐ 0 | 🐛 7 | 🌐 Python | 📅 2026-04-28 - Scoring library for Chinese autobiographical narratives in reminiscence therapy.

### Retrieval

* [Ragas](https://github.com/vibrantlabsai/ragas) ⭐ 16,224 | 🐛 649 | 🌐 Python | 📅 2026-02-24 - Metrics for answer quality, context relevance, and faithfulness in RAG pipelines.
* [UltraRAG](https://github.com/OpenBMB/UltraRAG) ⭐ 5,738 | 🐛 17 | 🌐 Python | 📅 2026-11-02 - MCP-based RAG framework with built-in evaluation workflows.
* [MTEB](https://github.com/embeddings-benchmark/mteb) ⭐ 3,491 | 🐛 344 | 🌐 Python | 📅 2026-11-03 - Embedding benchmark measuring retrieval, reranking, and similarity quality.
* [BEIR](https://github.com/beir-cellar/beir) ⭐ 2,328 | 🐛 88 | 🌐 Python | 📅 2025-10-16 - Benchmark suite covering dense, sparse, and hybrid retrieval tasks.
* [Open RAG Eval](https://github.com/vectara/open-rag-eval) ⭐ 419 | 🐛 18 | 🌐 Python | 📅 2026-10-08 - Vectara harness with UMBRELA and AutoNuggetizer metrics that need no golden answers.
* [RAGTruth](https://github.com/ParticleMedia/RAGTruth) ⭐ 286 | 🐛 6 | 🌐 Python | 📅 2024-12-02 - Human-annotated hallucination corpus for RAG answers.
* [RagCiteCheck](https://github.com/ppon1086/ragcitecheck) ⭐ 6 | 🐛 3 | 🌐 Python | 📅 2026-05-26 - Measures document-level and span-level evidence stability in RAG pipelines across runs.
* [LlamaIndex Evaluation](https://developers.llamaindex.ai/python/framework/module_guides/evaluating/) - Modules for scoring retrievers and comparing query engines.

<p align="center"><img src="./assets/footer.svg" width="480" alt=""></p>

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-11-03._
