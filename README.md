# Awesome-Search-Observability

## Top Prompt Evaluation Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on LLM Evaluation, Prompt Testing, RAG Assessment, Red Teaming, Observability & AI Quality Assurance*  
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Prompt Evaluation**. These tools help teams systematically test, score, and monitor large language model outputs, prompts, agents, and RAG pipelines using metrics, LLM-as-judge methods, datasets, and production tracing.

**Examples** include Promptfoo, DeepEval, Ragas, Langfuse, Humanloop, Arize Phoenix, Galileo, Braintrust, Confident AI, and OpenPipe (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for offline evaluation frameworks, observability platforms, RAG metrics, red teaming, and related open tooling — ideal for AI engineers and researchers seeking transparent, self-hosted, or CI-friendly alternatives to commercial evaluation platforms.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Promptfoo](https://www.promptfoo.dev/)**  
  Open-source-friendly LLM evaluation and red-teaming platform with declarative configs, multi-model comparison, and strong CI/CD integration (also available as a managed experience).

- **[DeepEval / Confident AI](https://deepeval.com/)**  
  Comprehensive LLM evaluation framework with extensive metrics; Confident AI provides the hosted collaboration and production evaluation layer.

- **[Ragas](https://docs.ragas.io/)**  
  Specialized evaluation toolkit focused on Retrieval-Augmented Generation (RAG) pipelines with reference-free metrics for faithfulness, relevancy, and context quality.

- **[Langfuse](https://langfuse.com/)**  
  Open-source LLM engineering platform for tracing, prompt management, evaluations, datasets, and observability (self-hosted or cloud).

- **[Humanloop](https://humanloop.com/)**  
  Platform for prompt engineering, evaluation, and monitoring of LLM applications with collaborative workflows.

- **[Arize Phoenix / Arize AX](https://phoenix.arize.com/)**  
  Open-source observability and evaluation toolkit (Phoenix) with a commercial platform (AX) for production LLM monitoring and evaluation.

- **[Galileo](https://www.rungalileo.io/)**  
  AI evaluation and observability platform focused on agent and LLM quality, with specialized scorers and production insights.

- **[Braintrust](https://www.braintrust.dev/)**  
  Evaluation-first platform for testing, logging, and iterating on LLM applications with strong support for experiments and human review.

- **[Confident AI](https://www.confident-ai.com/)**  
  Hosted evaluation and collaboration platform built around DeepEval metrics for teams running systematic LLM testing.

- **[OpenPipe](https://openpipe.ai/)**  
  Platform focused on fine-tuning, evaluation, and optimization of LLM applications with dataset and experiment management.

## Open-Source GitHub Projects

- **[Promptfoo](https://github.com/promptfoo/promptfoo)**  
  Leading open-source CLI and library for evaluating prompts, agents, and RAGs, with powerful red-teaming, multi-provider comparison, and CI/CD integration (MIT).

- **[DeepEval](https://github.com/confident-ai/deepeval)**  
  Open-source Python framework (Pytest-style) for LLM evaluation with 50+ metrics covering hallucination, RAG, agents, safety, and custom criteria (Apache 2.0).

- **[Ragas](https://github.com/explodinggradients/ragas)**  
  Open-source library specialized in evaluating RAG pipelines with metrics such as faithfulness, answer relevancy, context precision, and recall (Apache 2.0).

- **[Langfuse](https://github.com/langfuse/langfuse)**  
  Fully open-source LLM engineering platform for tracing, prompt versioning, evaluations, datasets, and metrics — self-hostable and framework-agnostic (MIT).

- **[Arize Phoenix](https://github.com/Arize-ai/phoenix)**  
  Open-source AI observability and evaluation platform with tracing, LLM-as-judge evaluators, datasets, and OpenTelemetry support.

- **[OpenAI Evals](https://github.com/openai/evals)**  
  Open-source framework for evaluating LLMs and systems with registered evals, model-graded scoring, and reproducible benchmarks (MIT).

- **[TruLens](https://github.com/truera/trulens)**  
  Open-source library for evaluating and tracking LLM applications with feedback functions and explainability features.

- **[AutoEvals & Community Metric Libraries](https://github.com/)**  
  Collections of open-source evaluation functions and LLM-as-judge implementations used across multiple platforms.

- **[Agent Evaluation Benchmarks](https://github.com/)**  
  Open benchmarks such as AgentBench, SWE-Bench, and tau-bench for assessing agent trajectories and tool use.

- **[Red-Teaming & Safety Toolkits](https://github.com/)**  
  Open-source projects focused on prompt injection testing, jailbreak detection, and adversarial evaluation of LLM systems.

- **[Tracing & Observability Collectors](https://github.com/)**  
  OpenTelemetry-based and custom open-source tracers that feed data into evaluation and monitoring systems.

- **[Synthetic Data & Dataset Generators](https://github.com/)**  
  Tools for generating evaluation datasets, adversarial examples, and test cases for prompt and agent testing.

### Additional Strong Open-Source Options

- **Code-first evaluation**: DeepEval (Pytest-style) and Promptfoo (YAML/CLI) dominate offline and CI evaluation workflows.
- **RAG specialists**: Ragas remains the go-to open-source library for retrieval-augmented generation metrics.
- **Observability + eval**: Langfuse and Arize Phoenix provide the strongest self-hostable tracing and evaluation platforms.
- **Benchmarks & safety**: OpenAI Evals and various red-teaming repositories support reproducible and security-focused testing.
- Many specialized **LLM-as-judge**, **agent trajectory**, and **metric** libraries continue to appear on GitHub.

**Frameworks for building custom systems**: Combine **Promptfoo or DeepEval** for offline/CI evaluation, **Ragas** for RAG-specific metrics, **Langfuse or Phoenix** for production tracing and online evaluation, and open benchmark datasets to create a complete prompt and LLM quality assurance stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- LLM evaluation involves model outputs that may contain sensitive or biased content; handle datasets and production traces with appropriate privacy and security controls.
- Self-hosted open-source solutions require careful management of API keys, evaluation costs (when using LLM-as-judge), and validation of metric reliability before production decisions.

---

**Made for AI engineers, LLM application developers, evaluation specialists, and research teams.**  
Let's make prompt and LLM evaluation more open, rigorous, and reproducible.
