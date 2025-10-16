# 🦉 Precogly
## Explainable. Trustworthy. High Signal-to-Noise Threat Modeling.

> ⚠️ **Early Stage / Seeking Design Partners**  
> Precogly is in active development. We're talking with AppSec leads to validate 
> the approach while building the full system.

## Why Precogly Exists

AppSec leads keep telling us:

> * Threat modeling is one of the highest ROI activities for our AppSec team.
> * Ideally we'd run a threat model for every user story — especially now, with AI-driven features shipping fast.
> * But we can't, because developers won't do threat modeling themselves, and our AppSec team is resource-constrained.
> * We want to use AI, but…
>   * How can we be sure the threat models are any good? (trustworthiness)
>   * How can we know why some risks were ignored or prioritized? (explainability)

Precogly was built to solve exactly these problems. It combines Large Language Models (LLMs) with deterministic rule engines to produce transparent, auditable, and high-signal threat models — giving AppSec teams both speed and confidence.

## How It Works

At its heart, Precogly uses a network of agentic systems — small, focused agents, each taking on a clear, testable role:

* One reads your architecture.
* Another identifies STRIDE threats.
* Another maps to CAPEC attack patterns.
* Another links to MITRE ATT&CK or NIST controls.

Each agent's reasoning is recorded, so you always know why a particular threat or mitigation was generated.

## Core Principles

### Explainable

Every threat, mitigation, and recommendation includes a reasoning trace — the frameworks, data, and rules that led to that conclusion. No black boxes.

### Trustworthy

Grounded in real-world security data (CVE, CAPEC, MITRE ATT&CK, OWASP, and more). Precogly's hybrid of AI + rule logic ensures consistent, evidence-backed results.

### High Signal-to-Noise

Security teams don't need more alerts — they need clarity. Precogly focuses on signal, surfacing only threats that matter in your context.


## Current Status

**In Progress:**
- Orchestrator agent
- Context-builder agent
- STRIDE agents
- CAPEC mapper agents
- Mitigations agent

**Seeking Input On:**
- Does this approach resonate with your threat modeling challenges?
- What integrations matter most? (Jira, GitHub, your IaC tools?)
- What would "good output" look like for your team?

## Get Involved

**We're especially interested in talking with:**
- AppSec leads who run threat modeling programs
- Security engineers who've tried to automate threat modeling
- Teams shipping AI-powered features who need faster threat modeling

**Ways to engage:**
- 💬 [Share your threat modeling challenges](GitHub Discussions link)
- 📧 Interested in being a design partner? Email: vikramsnarayan@gmail.com
- ⭐ Star the repo to follow progress
