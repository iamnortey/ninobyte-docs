# Ninobyte

> Connected AI Operator practice. Governed AI workflows, agentic engineering, and proof-of-work systems built on a three-agent local AI operating system.

**Connect. Govern. Execute. Prove.**

[![Case Study](https://img.shields.io/badge/case%20study-read-blue)](https://github.com/iamnortey/portfolio/blob/main/case-studies/ninobyte.md)
[![Portfolio](https://img.shields.io/badge/portfolio-iamnortey-green)](https://github.com/iamnortey/portfolio)

---

## What It Does

Ninobyte teaches and operates governed AI execution. Practical AI for real work — with approval gates, evidence trails, and portable proof of work. The practice spans education (the Connected AI Operator Lab and the AWS-native CloudOps and Security labs), templates and kits (Founder Brief Kit, Job Search Operator Kit, Proof Pack), and the underlying engineering system that produces it all — a three-agent local AI operating system.

**Doctrine:** Connect. Govern. Execute. Prove. Read first. Write only with approval. Spend only inside a sandbox. Commit only through review. Deploy only with rollback.

---

## The Problem

- AI lives in a browser tab, disconnected from the documents, repos, and systems where work actually happens.
- Prompt courses produce momentary cleverness, not durable capability.
- Job seekers have certificates but no proof of work that a hiring manager respects.
- Founders have ideas but no operating system to execute them with leverage.
- Teams have tools but no governance — secrets leak, credentials sprawl, agents drift.
- Most AI training optimizes for excitement; enterprise buyers and serious operators now require trust, evidence, and reversibility.

---

## Practice Areas

| Area | Description |
|------|-------------|
| **Connected AI Operator Lab** | The flagship practice teaching the full operator workflow — connect, govern, execute, prove |
| **AI-Native CloudOps Lab — AWS** | Governed AWS AI workload practice with safety gates and proof packs ([overview](https://github.com/ninobyte-cloudops-lab/cloudops-lab-overview)) |
| **AI Security & Governance Lab — AWS** | Defensive AI security review with synthetic evidence and ticket-driven workflows ([overview](https://github.com/ninobyte-cloudops-lab/ai-security-governance-lab-overview)) |
| **Operator Kits** | Founder Brief Kit, Job Search Operator Kit, Proof Pack templates, Connected Workflow Starter |
| **Three-Agent Local AI OS** | The engineering system underneath: Architect (plans, audits, validates) → Builder (implements) → Verification Lab (verifies, captures evidence) |

---

## Key Patterns

### Read-First Defaults
Default to read-only access; promote to write only after a human approves. Applies to repos, cloud accounts, databases, and external APIs.

### Approval Gates
No autonomous writes. `git commit`, `git push`, package installs, destructive ops — all require an explicit human Y/N before execution.

### Sandboxed Spend
Stripe test mode. AWS read-only roles. Throwaway repos before production. Reversibility before scale.

### Evidence Trails
Every workflow produces a portable proof-of-work artifact — a README, a screenshot, a recorded session, a sanitized evidence pack — that a reviewer can act on without seeing the private internals.

### Governance Versioning
Doctrine documents are version-controlled the same way code is — with diffs, backups, and acknowledgment trails.

---

## Implementation Details

The underlying engineering uses widely available primitives — exposed here for engineers and contributors, not as the public headline.

| Layer | Technology |
|-------|------------|
| **Local agents** | Architect (planner / validator), Builder (executor), Verification Lab (browser QA / evidence) |
| **Connectors** | Model Context Protocol (MCP) servers and clients |
| **Skill packs** | Claude Skills format, agent prompt libraries |
| **Plugins** | Claude Code extensions and workflows |
| **Languages** | TypeScript, Python, SQL |
| **Cloud focus** | AWS-first depth (Bedrock, IAM, CloudTrail, S3, Macie, Guardrails) |
| **Safety toolchain** | gitleaks, semgrep, trufflehog, approval gates, read-only defaults |

---

## Documentation

| Document | Description |
|----------|-------------|
| [Case Study](https://github.com/iamnortey/portfolio/blob/main/case-studies/ninobyte.md) | Connected AI Operator practice overview |
| [CloudOps Lab Overview](https://github.com/ninobyte-cloudops-lab/cloudops-lab-overview) | Governed AWS AI workload practice |
| [AI Security & Governance Lab Overview](https://github.com/ninobyte-cloudops-lab/ai-security-governance-lab-overview) | Defensive AI security and audit workflows |

---

## Public/Private Boundary

This repository is the **public doctrine surface** for Ninobyte. It contains architecture documentation, governance patterns, ADR examples, and the published doctrine. Implementation repos, curriculum, instructor materials, cost and safety gates, lab scenario architecture, and synthetic-evidence models live in private repositories by design.

No credentials, no client data, no internal solution guides, and no private implementation details appear here.

---

## Related

- [Portfolio](https://github.com/iamnortey/portfolio) — case studies, ADRs, runbooks, proof packs
- [Case Study](https://github.com/iamnortey/portfolio/blob/main/case-studies/ninobyte.md) — Connected AI Operator practice deep-dive
- [CloudOps Lab](https://github.com/ninobyte-cloudops-lab/cloudops-lab-overview) — governed AWS AI practice
- [AI Security & Governance Lab](https://github.com/ninobyte-cloudops-lab/ai-security-governance-lab-overview) — defensive AI security and audit workflows
