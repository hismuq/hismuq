<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark) and (max-width: 640px)" srcset="assets/hero-mobile-dark.svg">
  <source media="(prefers-color-scheme: light) and (max-width: 640px)" srcset="assets/hero-mobile-light.svg">
  <source media="(prefers-color-scheme: dark)" srcset="assets/hero-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/hero-light.svg">
  <img src="assets/hero-dark.svg" alt="Animated Hismuq identity console showing an abstract particle mark, AI and healthcare systems metadata, and a live runtime state." width="100%">
</picture>

</div>

**AI engineer building healthcare software, intelligent agents, and reliable ML systems.**

I work on production healthcare software and EHR workflows, and on AI assistants that have to stay inside an authorized scope. My focus is the engineering around the model: tools, guardrails, evaluation and escalation. Alongside the production work I run small research experiments on how clinical assistants should stop, refuse and hand off.

## Building

### Healthcare AI
Production healthcare software and AI-assisted workflows across EHR experiences.

### Agent systems
Assistants that combine retrieval, tools, authorization boundaries and bounded outcomes.

### Reliability
Evaluation, guardrails, failure handling and escalation for systems that cannot safely be "almost right."

<picture>
  <source media="(prefers-color-scheme: dark) and (max-width: 640px)" srcset="assets/runtime-trace-mobile-dark.svg">
  <source media="(prefers-color-scheme: light) and (max-width: 640px)" srcset="assets/runtime-trace-mobile-light.svg">
  <source media="(prefers-color-scheme: dark)" srcset="assets/runtime-trace-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/runtime-trace-light.svg">
  <img
    src="assets/runtime-trace-dark.svg"
    alt="Hismuq reliability runtime trace from request through grounding, action and boundary checking to answer or escalation."
  >
</picture>

## Selected work

**Sparkle AI** · patient-facing assistant · *proprietary*<br>
Authorization bound to the signed-in patient, booking state that survives interruption, and explicit stop and escalation paths for scope and distress. [Sparkle AI case study](https://hismuq.vercel.app/work/sparkle-ai)

**HealthVision** · behavioral health EHR · *proprietary*<br>
Production fixes across four role-based portals, checked against saved, visible and downstream state, with responsive and accessibility audits. [HealthVision case study](https://hismuq.vercel.app/work/healthvision)

**Refusal Without Abandonment** · research instrument · *public, preliminary*<br>
A deterministic benchmark of 12 synthetic scenarios comparing generic and evidence-bound refusal on six invariants. It tests an interface contract, not a model, and involves no human subjects or clinical data. [Benchmark](https://hismuq.vercel.app/lab/refusal-benchmark) · [Methods](https://hismuq.vercel.app/lab/refusal-benchmark/methods)

Some production healthcare systems I work on are proprietary, so this profile focuses on engineering patterns rather than internal implementation details.

## Approach

**Scope before generation.** Know what the system must not answer, and who takes over when it stops.

**Evidence before confidence.** Trust in healthcare software comes from tests, traces and human review, not from assertion.

**Failure gets a bounded outcome.** Every stop has a designed path: a refusal, a redirect or an escalation, never a catch-all answer.

## Research direction

I'm interested in making healthcare AI systems more reliable under real workflow constraints. These are open research questions, not published results, and none implies clinical validation.

**01**  How do we evaluate whether a clinical assistant stays inside its authorized scope?

**02**  How should retrieval, tools and guardrails interact when an agent encounters uncertainty or conflicting evidence?

**03**  How can healthcare AI systems fail safely instead of merely producing more confident answers?

Working notes: [research brief](https://hismuq.vercel.app/research).

## Stack

| | |
|:--|:--|
| **Languages** | Python · TypeScript · C# |
| **ML and data** | PyTorch · scikit-learn · pandas · DuckDB |
| **Product and platform** | React · Next.js · ASP.NET Core · Vitest · Azure DevOps |
| **Domain** | EHR · patient workflows · clinical AI safety |

<sub>ML tooling is from my public repositories: [MedGAN](https://github.com/hismuq/B.E-Major-Project) (synthetic medical imaging, university project) and [FlyRank ML](https://github.com/hismuq/flyrank-ml-internship) (internship coursework on anonymized search data).</sub>

---

<div align="center">

[Portfolio](https://hismuq.vercel.app) · [LinkedIn](https://linkedin.com/in/hismuq) · [Email](mailto:hismuq@gmail.com)

**Software clinicians trust cannot be almost right.**

</div>
