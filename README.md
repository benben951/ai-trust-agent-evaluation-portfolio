# AI Trust & Agent Evaluation Portfolio

This repository is a public entry point for my LLM evaluation, AI trust, and agent workflow projects.

My work focuses on a practical question:

> Can this AI system be trusted enough to use, escalate, or reject in a real workflow?

I am building toward foreign-company roles in LLM evaluation, AI application engineering, Trust & Safety AI, risk-tech AI, and agent workflow evaluation. The projects below are public-safe prototypes and evaluation systems, not claims of production deployment.

## Portfolio One-Pager

- [Markdown one-pager](docs/PORTFOLIO_ONE_PAGER.md)
- [PDF one-pager](docs/AI_Trust_Agent_Evaluation_Portfolio_Guo_Zhaojie_20260606.pdf)
- [Interview notes](docs/INTERVIEW_NOTES.md)

## Project Map

| Layer | Project | What it proves | Evidence |
|---|---|---|---|
| LLM endpoint trust | [LLM Proxy Auditor](https://github.com/benben951/llm-proxy-auditor) | Audits OpenAI-compatible proxy risks before agents depend on them. | Deterministic probes, scoring model, CI, report preview |
| LLM output trust | [Agent Trust Lab](https://github.com/benben951/agent-trust-lab) | Converts ambiguous LLM outputs into reviewable trust reports and escalation metrics. | [Live demo](https://benben951.github.io/agent-trust-lab/), synthetic eval set, Markdown/JSON reports, CI |
| Agent workflow trust | [Agent Workflow Bench](https://github.com/benben951/agent-workflow-bench) | Evaluates planner-executor-reviewer-verifier workflows with artifacts and verifier output. | Simulated pipeline, CI, sample run artifacts |
| Regulated-domain application | [Gemma AML Compliance Assistant](https://github.com/benben951/gemma-aml-assistant) | Applies local LLM/RAG workflows to AML and due-diligence style knowledge assistance. | Public repo, compliance-oriented scenario, grounding and uncertainty handling |

## Why These Projects Fit Together

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
      applies RAG and local LLM workflows to AML and due-diligence scenarios
```

## Public-Safe Boundary

These projects intentionally use public-safe examples and synthetic evaluation data.

- No private employer data is included.
- No real customer or regulated case data is included.
- High-risk decisions are framed as human-in-the-loop review workflows.
- The projects demonstrate evaluation, review routing, reporting, and governance thinking rather than autonomous compliance approval.

## Target Roles

| Role family | Strongest evidence |
|---|---|
| LLM Evaluation / Model Evaluation | Agent Trust Lab, Agent Workflow Bench, LLM Proxy Auditor |
| AI Application Engineer / GenAI Engineer | Agent Trust Lab, Gemma AML Assistant, Agent Workflow Bench |
| Trust & Safety AI / AI Governance | Agent Trust Lab, LLM Proxy Auditor |
| Risk-Tech AI / Compliance AI | Agent Trust Lab, Gemma AML Assistant, LLM Proxy Auditor |
| Agent Workflow Engineer | Agent Workflow Bench, Agent Trust Lab, LLM Proxy Auditor |
| AI Data Quality / Review Quality | Agent Trust Lab, Agent Workflow Bench, current AI output review experience |

## Short Pitch

I am not only using LLMs to produce answers. I am building evaluation and trust systems around LLM outputs, agent workflows, and proxy infrastructure. My projects demonstrate live demos, CI, synthetic evaluation sets, trust reports, verifier artifacts, and human-in-the-loop safety boundaries.
