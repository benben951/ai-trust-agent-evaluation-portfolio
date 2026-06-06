# AI Trust & Agent Evaluation Portfolio - Guo Zhaojie

## Positioning

I build practical evaluation systems for risk-sensitive LLM and agent workflows. My portfolio focuses on one question:

> Can this AI system be trusted enough to use, escalate, or reject in a real workflow?

This portfolio connects four public projects into one coherent direction: LLM output review, agent workflow evaluation, proxy trust auditing, and regulated-domain RAG.

## Portfolio Map

| Layer | Project | What It Proves | Public Evidence |
|---|---|---|---|
| LLM output trust | Agent Trust Lab | I can turn ambiguous LLM outputs into auditable trust reports, multi-role review traces, and review-routing metrics. | Live demo, recruiter review packet, baseline comparison, spot-check log, EMNLP demo draft, 40-case synthetic eval set, Markdown/JSON reports, CI, metrics |
| Agent workflow trust | Agent Workflow Bench | I can benchmark planner-executor-reviewer-verifier workflows with artifacts and verifier outputs. | Public repo, simulated pipeline, CI, summary JSON, Markdown report, sample run artifacts |
| Infrastructure trust | LLM Proxy Auditor | I can audit OpenAI-compatible proxy risks before connecting agents to them. | CI, deterministic probes, scoring model, report preview, case study |
| Regulated-domain application | Gemma AML Compliance Assistant | I can build and evaluate offline RAG-style assistants for AML and due-diligence workflows with grounding, escalation, and uncertainty handling. | Public repo, CI, AML RAG case study, sample eval summary, governance checklist |

## 1. Agent Trust Lab

- Repo: https://github.com/benben951/agent-trust-lab
- Live demo: https://benben951.github.io/agent-trust-lab/
- Review packet: https://github.com/benben951/agent-trust-lab/blob/main/docs/REVIEW_PACKET.md

Risk-sensitive LLM output evaluation system with a live review console, 40-case synthetic eval set, batch trust-report generation, baseline comparison, spot-check log, evaluation metrics, and human-review routing.

Public proof:

- Recruiter-facing review packet with case library, metrics, representative reports, reproduction commands, interview pitch, resume bullets, and public-safe boundary
- Public-safe multi-role workflow trace with evidence, policy, risk, escalation, and final-review notes for a synthetic agent-output failure
- 40-case synthetic eval library across AML, KYC, sanctions, due diligence, Trust & Safety, customer support, HR, legal, health-safety, financial services, agent output review, and AI data quality
- Markdown trust reports and JSON summaries
- Evaluation metrics: 65% manual-review routing, 47.5% low-trust cases, average risk score 47.62
- Naive-baseline comparison: 26 naive accepts, 19 false accepts, 48% false-accept rate
- Human spot-check protocol/log, EMNLP demo draft, CI, GitHub Pages demo, technical report, governance boundary

Interview angle:

This project shows that I understand AI evaluation as a review workflow, not just answer scoring. It emphasizes false-pass prevention, uncertainty handling, evidence support, role-level review traces, and human escalation.

## 2. Agent Workflow Bench

- Repo: https://github.com/benben951/agent-workflow-bench
- Sample artifacts: https://github.com/benben951/agent-workflow-bench/tree/main/examples/simulated_run

Evaluation-first benchmark for planner-executor-reviewer-verifier workflows.

Public proof:

- Reproducible simulated pipeline that does not require external model access
- Generates planner note, candidate output, reviewer note, verifier report, and JSON manifest
- Records pass rate, verifier status, failure types, latency, timeout, and reviewed artifact paths
- Generates aggregate summary JSON and recruiter-readable Markdown reports from run manifests
- Includes CI, task specs, workflow specs, rubric judge, and public-safe sample artifacts
- Also records live Codex-backed run history separately from simulated runs

Interview angle:

This project shows that I can evaluate agent workflows as systems, including success, failure, timeout, verification evidence, aggregate metrics, and reportable artifacts instead of only showing successful demo runs.

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
- Case study: https://github.com/benben951/gemma-aml-assistant/blob/main/docs/CASE_STUDY.md

Offline AML and due-diligence assistant with local model inference, retrieval grounding, citation-aware responses, and compliance-oriented evaluation scenarios.

Public proof:

- Local LLM/RAG workflow for regulated-domain knowledge assistance
- CI, tests, synthetic due-diligence eval cases, and a public-safe AML RAG case study
- Sample scored-output evaluation: 5 synthetic outputs, 100% risk-point recall, 100% grounding-signal rate, 80% escalation-signal rate, and 20% unsafe-certainty control rate
- Focus on grounding, uncertainty handling, hallucination risk, escalation behavior, and human-in-the-loop boundaries
- Connects LLM application engineering with AML/due-diligence domain context

Interview angle:

This project shows I can build and evaluate LLM applications in a regulated domain, not only generic chatbots or toy demos. It connects my AML review background with grounding, evaluation, escalation, and governance design.

## How The Projects Fit Together

```text
LLM endpoint trust
  -> LLM Proxy Auditor
      checks whether the API/proxy layer is safe enough for agents

LLM output trust
  -> Agent Trust Lab
      reviews model outputs through trust reports, public-safe multi-role workflow traces, baseline comparison, and spot-check logs

Agent workflow trust
  -> Agent Workflow Bench
      evaluates planner-executor-reviewer-verifier workflows with artifacts, evidence coverage, risk flags, and human-takeover metrics

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

I am not only using LLMs to produce answers. I am building evaluation and trust systems around LLM outputs, agent workflows, and proxy infrastructure. My projects demonstrate live demos, CI, synthetic evaluation sets, trust reports, baseline comparisons, spot-check logs, multi-role workflow traces, verifier artifacts, and human-in-the-loop safety boundaries.

## Resume Summary Version

AI application and evaluation engineer focused on risk-sensitive LLM review, agent workflow evaluation, proxy trust auditing, and regulated-domain AI systems. Built public projects including Agent Trust Lab, Agent Workflow Bench, LLM Proxy Auditor, and Gemma AML Compliance Assistant, with CI, live demos, synthetic eval sets, trust reports, multi-role workflow traces, verifier artifacts, and governance boundaries.
