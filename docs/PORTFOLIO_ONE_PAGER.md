# AI Trust & Agent Evaluation Portfolio - Guo Zhaojie

## Positioning

I build practical evaluation systems for risk-sensitive LLM and agent workflows. My portfolio focuses on one question:

> Can this AI system be trusted enough to use, escalate, or reject in a real workflow?

This portfolio connects four public projects into one coherent direction: LLM output review, agent workflow evaluation, proxy trust auditing, and regulated-domain RAG.

## Portfolio Map

| Layer | Project | What It Proves | Public Evidence |
|---|---|---|---|
| LLM output trust | Agent Trust Lab | I can turn ambiguous LLM outputs into auditable trust reports and review-routing metrics. | Live demo, 10-case synthetic eval set, Markdown/JSON reports, CI, metrics |
| Agent workflow trust | Agent Workflow Bench | I can benchmark planner-executor-reviewer-verifier workflows with artifacts and verifier outputs. | Public repo, simulated pipeline, CI, sample run artifacts |
| Infrastructure trust | LLM Proxy Auditor | I can audit OpenAI-compatible proxy risks before connecting agents to them. | CI, deterministic probes, scoring model, report preview, case study |
| Regulated-domain application | Gemma AML Compliance Assistant | I can build offline RAG-style assistants for AML and due-diligence workflows with grounding and uncertainty handling. | Public repo, local LLM/RAG workflow, compliance-oriented scenario |

## 1. Agent Trust Lab

- Repo: https://github.com/benben951/agent-trust-lab
- Live demo: https://benben951.github.io/agent-trust-lab/

Risk-sensitive LLM output evaluation system with a live review console, synthetic eval set, batch trust-report generation, evaluation metrics, and human-review routing.

Public proof:

- 10-case synthetic eval library across AML, KYC, due diligence, Trust & Safety, customer support compliance, agent output review, and AI data quality
- Markdown trust reports and JSON summaries
- Evaluation metrics: 80% manual-review routing, 40% low-trust cases, average risk score 53.0
- Finding distribution for policy mismatch, missing escalation, unsafe certainty, and unsupported claims
- CI, GitHub Pages demo, technical report, governance boundary

Interview angle:

This project shows that I understand AI evaluation as a review workflow, not just answer scoring. It emphasizes false-pass prevention, uncertainty handling, evidence support, and human escalation.

## 2. Agent Workflow Bench

- Repo: https://github.com/benben951/agent-workflow-bench
- Sample artifacts: https://github.com/benben951/agent-workflow-bench/tree/main/examples/simulated_run

Evaluation-first benchmark for planner-executor-reviewer-verifier workflows.

Public proof:

- Reproducible simulated pipeline that does not require external model access
- Generates planner note, candidate output, reviewer note, verifier report, and JSON manifest
- Records pass rate, verifier status, failure types, latency, timeout, and reviewed artifact paths
- Includes CI, task specs, workflow specs, rubric judge, and public-safe sample artifacts
- Also records live Codex-backed run history separately from simulated runs

Interview angle:

This project shows that I can evaluate agent workflows as systems, including success, failure, timeout, and verification evidence, instead of only showing successful demo runs.

## 3. LLM Proxy Auditor

- Repo: https://github.com/benben951/llm-proxy-auditor

Trust-audit tool for OpenAI-compatible LLM proxies before connecting them to coding agents, browser agents, or internal workflows.

Public proof:

- Deterministic probes for prompt integrity, model-substitution risk, structured-output stability, fake-secret leakage, canary rewriting, and agent readiness
- Markdown/JSON trust reports with weighted risk scoring and agent-safety recommendations
- CI, regression tests, scoring documentation, case study, agent safety playbook, and report preview screenshot

Interview angle:

This project shows infrastructure-level trust thinking: before evaluating an agent workflow, we need to know whether the LLM endpoint itself is safe enough to connect to tools, code, documents, and private contexts.

## 4. Gemma AML Compliance Assistant

- Repo: https://github.com/benben951/gemma-aml-assistant

Offline AML and due-diligence assistant with local model inference, retrieval grounding, citation-aware responses, and compliance-oriented evaluation scenarios.

Public proof:

- Local LLM/RAG workflow for regulated-domain knowledge assistance
- Focus on grounding, uncertainty handling, and hallucination risk
- Connects LLM application engineering with AML/due-diligence domain context

Interview angle:

This project shows I can build LLM applications in a regulated domain, not only generic chatbots or toy demos.

## How The Projects Fit Together

```text
LLM endpoint trust
  -> LLM Proxy Auditor
      checks whether the API/proxy layer is safe enough for agents

LLM output trust
  -> Agent Trust Lab
      reviews model outputs and routes uncertain/high-risk cases to humans

Agent workflow trust
  -> Agent Workflow Bench
      evaluates planner-executor-reviewer-verifier workflows with artifacts

Regulated application context
  -> Gemma AML Compliance Assistant
      applies RAG and local LLM workflows to AML/due-diligence scenarios
```

## Role Fit

| Target Role | Best Evidence |
|---|---|
| LLM Evaluation / Model Evaluation | Agent Trust Lab, Agent Workflow Bench, LLM Proxy Auditor |
| AI Application Engineer / GenAI Engineer | Agent Trust Lab, Gemma AML Assistant, Agent Workflow Bench |
| Trust & Safety AI / AI Governance | Agent Trust Lab, LLM Proxy Auditor |
| Risk-Tech AI / Compliance AI | Agent Trust Lab, Gemma AML Assistant, LLM Proxy Auditor |
| Agent Workflow Engineer | Agent Workflow Bench, Agent Trust Lab, LLM Proxy Auditor |
| AI Data Quality / Review Quality | Agent Trust Lab, current AI output review work, Agent Workflow Bench |

## Short Pitch

I am not only using LLMs to produce answers. I am building evaluation and trust systems around LLM outputs, agent workflows, and proxy infrastructure. My projects demonstrate live demos, CI, synthetic evaluation sets, trust reports, verifier artifacts, and human-in-the-loop safety boundaries.

## Resume Summary Version

AI application and evaluation engineer focused on risk-sensitive LLM review, agent workflow evaluation, proxy trust auditing, and regulated-domain AI systems. Built public projects including Agent Trust Lab, Agent Workflow Bench, LLM Proxy Auditor, and Gemma AML Compliance Assistant, with CI, live demos, synthetic eval sets, trust reports, verifier artifacts, and governance boundaries.
