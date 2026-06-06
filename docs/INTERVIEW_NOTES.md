# Interview Notes

## 60-Second Portfolio Pitch

My portfolio is centered on AI trust and agent evaluation. Instead of only building chat demos, I build review systems around LLM outputs, agent workflows, and proxy infrastructure. The common thread is: when an AI system produces an answer or takes a step, can we inspect the evidence, score the risk, route uncertain cases to humans, and leave an audit trail?

The four projects cover different layers of the same problem:

- LLM Proxy Auditor checks whether an OpenAI-compatible endpoint is safe enough to connect to agents.
- Agent Trust Lab reviews LLM/agent outputs and generates trust reports, public-safe multi-role workflow traces, naive-baseline comparisons, spot-check logs, and review-routing metrics.
- Agent Workflow Bench evaluates planner-executor-reviewer-verifier workflows through reproducible artifacts.
- Gemma AML Compliance Assistant applies local LLM/RAG ideas to an AML and due-diligence style scenario.

## Strongest Story For LLM Evaluation Roles

Agent Trust Lab is the best entry point. It shows that I can turn subjective AI output review into a structured workflow: 40 synthetic cases, risk scoring, finding taxonomy, trust reports, public-safe multi-role workflow traces, naive-baseline comparison, 15-case spot-check log, manual-review routing, and evaluation metrics. The recruiter-facing review packet makes the evidence easy to inspect: case library, representative reports, baseline comparison, spot-check log, reproduction commands, interview pitch, resume bullets, and public-safe boundaries. This is close to real annotation quality, model behavior evaluation, and human-in-the-loop review operations.

## Strongest Story For Agent Roles

Agent Workflow Bench is the best entry point. It evaluates the full workflow, not just the final answer. It records planner notes, candidate outputs, reviewer feedback, verifier reports, evidence coverage, risk flags, human-takeover recommendations, failure types, and run manifests. This makes agent behavior easier to compare, debug, and improve.

## Strongest Story For Risk-Tech / Trust & Safety AI Roles

LLM Proxy Auditor plus Agent Trust Lab is the strongest pair. The first checks whether the model endpoint is trustworthy enough; the second checks whether the model output should be accepted, escalated, or rejected. Together they show an evaluation mindset across both infrastructure and output layers.

## Boundaries I Should Say Clearly

- These are public-safe prototypes, not production systems.
- Evaluation data is synthetic or public-safe, not private employer data.
- The systems do not make autonomous high-risk decisions.
- The goal is review support, escalation, evidence tracking, and trust reporting.

## Resume-Safe Summary

Built a public AI trust and agent evaluation portfolio covering LLM proxy auditing, LLM output review, planner-executor-reviewer-verifier workflow evaluation, and regulated-domain RAG assistance. Projects include CI, live demo, synthetic evaluation sets, trust reports, baseline comparisons, spot-check logs, multi-role workflow traces, verifier artifacts, evidence coverage, risk flags, human-takeover metrics, and human-in-the-loop governance boundaries.
