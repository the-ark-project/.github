<head style="background-color: #0B1C2E;">
</head>

<p align="center">
  <a href="https://devsecai.io" target="_blank">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="/profile/project-ark-logo-dark.jpg">
      <source media="(prefers-color-scheme: light)" srcset="/profile/project-ark-logo-light.jpg">
      <img alt="Project Ark" src="/profile/project-ark-logo-light.jpg" width="350" height=auto style="max-width: 100%;">
    </picture>
  </a>
</p>

<p align="center">
Developing a collective AI-Native defence playbook. Engineering sovereignty for the era of infinite code.
</p>

---

# Project Ark

**Developing a collective AI-Native defence playbook. Engineering sovereignty for the era of infinite code.**

Welcome to Project Ark. We are a collective of software security engineers, platform architects, and practitioners who recognise that the traditional cybersecurity paradigm has reached its breaking point.

**The Manifesto • North Star • Workstreams • Community**

## 📜 The manifesto
We believe that the compensating controls model — a legacy of reactive patches and perimeter defense — is fundamentally broken. In a world where AI-assisted development and autonomous agents are exponentially increasing code volumes, and time-to-exploit software vulnerabilities from public disclosure is collapsing to zero, the attack surface is expanding faster than any security inspector or manual audit can track and fix.

We believe the "compensating controls" model is not just failing; it is a reactive trap. As AI-assisted development and autonomous agents exponentially increase code volumes, the resulting attack surface expansion renders traditional security "bandages" impotent.

Optimising the application layer with faster patching tools is a race to the bottom. If we rely on speed alone without a deterministic, localised infrastructure, we are simply accelerating the rate at which we apply bandages to a fundamentally compromised substrate.

Project Ark is the implementation arm of a sovereign security movement. We will seek alternatives to being locked into the pricing models and proprietary black boxes of frontier model and security testing companies. Instead, we will share experiences building our own Secure Software Factories: high-observability, mistake-proofed pipelines that uses LLM-based reasoning to move beyond finding bugs to eliminating entire classes of vulnerabilities.

We don't just want faster tools for deployment teams; we want to hardcode the structural boundaries of our code and infrastructure. We will use a reasoning engine to ensure that security is not a post-script, but an immutably evident and deterministic property of the code itself.

## Why sovereignty?

> We believe that dependency on systems that are temporarily heavily subsidised will become a trap - organisations are going to get locked in. This can be mitigated by owning the means of production and in time, self-hosting our models locally. But it requires a better understanding of 1) how to provide tools in ways which experienced and new-developers alike want to include in their workflow and 2) which secure coding tasks are best suited to which types of AI model.

Project Ark exists to ensure that member organisations don't need to choose between operational cost, stability and safety and still enjoy the near-term benefits of using subsidised frontier company APIs. Together we will build templates for lean, secure software factories: making available AI-native tools and playbooks for local reasoning, and local preventative, detective and corrective action.

## 🛠️ The Strategy: Beyond the Reactive Loop
Inspired by healthcare's shift from "medication" to "structural health," our approach focuses on building explainable playbooks for engineering and executive teams for the following:

1. **IDE-smbedded sovereignty:** Reasoning agents are embedded directly into the developer workflow. Before code is even committed, it is inspected for vulnerabilities, a structural fix is written, tests are run, and the deployment is validated. The vulnerability is strangled at the source.

2. **Full-stack autonomous inspection:** Agents can run 24/7 across every layer of the grid—from bare-metal perimeters to application logic—identifying weaknesses and automatically reconfiguring production environments to mitigate risk while permanent, sovereign fixes are deployed.

3. **Ownership of the means of production:** We will build a path to mitigating vendor lock-in by designing the infrastructure to self-host models and orchestration. We believe our organisations will need to understand data and model boundaries rather than be wholly reliant on subsidised, third-party APIs that create operational dependencies.

## 🏗️ Workstreams (Subject to Discussion)
Our roadmap is organised into three strategic workstreams to ensure principled performance and structural resilience.

1. **Preventative: Mistake-proofing the factory**
**Focus:** Embedding Arko within the IDE and Agent Managers to "mistake-proof" the pipeline.
**Tactics:** Developing "Secure-by-Construction" templates where code and its security fix are submitted as a single, atomic unit.
**Goal:** Hardcoding the assembly line so that ....

2. **Detective: Continuous structural telemetry**
**Focus:** 24/7 autonomous agents inspecting the entire stack for drift and architectural fragility.
**Tactics:** Utilising self-hosted LLMs to map complex attack paths that traditional scanners miss, ensuring total visibility into the "Sovereign Substrate."
**Goal:** Transitioning from GRC "Security Theatre" to high-resolution, real-time awareness of the attack surface.

3. **Corrective: Sovereign configuration & refactoring**
**Focus:** Automated risk mitigation and structural remediation without human intervention.
**Tactics:** Deploying agents that can configure production environments in real-time to close exploit windows while simultaneously generating permanent code refactors.
**Goal:** Moving the enterprise into a state of structural remission where the underlying vulnerability classes are eliminated forever.

## 🤝 Join the Project
Project Ark is a vendor-neutral community designed for CISOs of software engineering companies and application security leads. We are the architects of our own sovereignty.

**Principles:** Mistake-proofing and defect prevention beats defect discovery.

**Tooling:** Standardised on DevSecAI Arko for reasoning-driven security - other tooling will be subject to the same onboarding criteria (zero cost to project participants).

**Compliance:** Built for the 2026 AI Code of Practice and UK and EU "Secure by Design" mandates.

## Structural overview

```mermaid
flowchart TB
  subgraph sgForces["Reality shift"]
    direction LR
    F1["AI-assisted development<br/>+ autonomous agents"]
    F2["Code volume grows<br/>exponentially"]
    F3["Disclosure → exploit window<br/>collapses toward zero"]
  end

  F1 --> F2 --> F3

  subgraph sgLegacy["Legacy playbook: compensating controls"]
    direction LR
    L1["Perimeter mindset"]
    L2["Reactive patches & audits"]
    L3["GRC / checklist 'security theatre'"]
  end

  L1 --> L2 --> L3

  F3 --> AS["Attack surface expands faster<br/>than humans + manual tools can track"]
  L2 --> AS

  AS --> GAP{{"Breaking point:<br/>volume & speed vs. finite inspection capacity"}}

  GAP --> TRAP["'Bandages on a compromised substrate'<br/>speed without deterministic structure"]

  subgraph sgVicious["Reactive loop"]
    direction TB
    V1["Ship more, faster"]
    V2["Thinner review & weaker guarantees"]
    V3["More incidents → more patches"]
    V1 --> V2 --> V3
    V3 -->|"feeds"| V1
  end

  TRAP --> V1

  subgraph sgVendor["Dependency trap"]
    direction TB
    R1["Subsidised frontier APIs feel 'free'"]
    R2["Proprietary black boxes"]
    R3["Operational + pricing lock-in"]
  end

  V3 --> R1 --> R2 --> R3

  subgraph sgArk["Sovereign security direction"]
    direction TB
    A1["Secure Software Factory:<br/>observable, mistake-proofed pipelines"]
    A2["Reasoning in the workflow before merge:<br/>structural fix, tests, validation"]
    A3["Eliminate vulnerability classes —<br/>not an endless bug backlog"]
    A4["Own models, data boundaries,<br/>means of production"]
  end

  GAP -.->|"engineer sovereignty,<br/>not more compliance theatre"| A1
  V3 -.->|"break the loop"| A2
  R3 -.->|"mitigate lock-in"| A4

  classDef cdForce fill:#0f172a,stroke:#38bdf8,color:#e2e8f0
  classDef cdLegacy fill:#1c1917,stroke:#a8a29e,color:#fafaf9
  classDef cdBad fill:#450a0a,stroke:#f87171,color:#fecaca
  classDef cdVendor fill:#3b0764,stroke:#c084fc,color:#f3e8ff
  classDef cdArk fill:#052e16,stroke:#4ade80,color:#dcfce7

  class F1,F2,F3 cdForce
  class L1,L2,L3 cdLegacy
  class AS,TRAP,V1,V2,V3,GAP cdBad
  class R1,R2,R3 cdVendor
  class A1,A2,A3,A4 cdArk
```
