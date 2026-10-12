<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0D1117&height=210&section=header&text=Abdullah%20Akram&fontSize=58&fontColor=F0F6FC&fontAlignY=42&desc=AI%20systems%2C%20thoughtfully%20engineered&descSize=22&descAlignY=65&descColor=F5A524&animation=fadeIn" alt="Abdullah Akram — AI systems, thoughtfully engineered" width="100%" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=17&pause=1400&color=F5A524&center=true&vCenter=true&width=640&height=36&lines=Applied+AI;Python;Reliable+systems;Evidence+%C2%B7+Decisions+%C2%B7+Failure+modes" alt="Applied AI · Python · Reliable systems" />

**Building software that makes its evidence, decisions, and failure modes visible.**

![Focus](https://img.shields.io/badge/focus-Applied_AI-F5A524?style=for-the-badge&labelColor=0D1117)
![Language](https://img.shields.io/badge/language-Python-F5A524?style=for-the-badge&labelColor=0D1117&logo=python&logoColor=white)
![Approach](https://img.shields.io/badge/approach-Reliable_systems-F5A524?style=for-the-badge&labelColor=0D1117)

[**About**](#about-my-work) &nbsp;·&nbsp; [**Workbench**](#on-the-workbench) &nbsp;·&nbsp; [**Approach**](#how-i-approach-a-system) &nbsp;·&nbsp; [**Toolkit**](#current-toolkit)

</div>

---

## About my work

I'm Abdullah. My current focus is the engineering around AI: getting useful context into a model, controlling what an agent can do, measuring response quality, and keeping inference costs predictable.

I prefer explicit contracts, inspectable behavior, and small components with clear responsibilities.

## On the workbench

> [!NOTE]
> Five projects are being developed locally. Their GitHub repositories are reserved; implementation and walkthroughs will be published after review.

| | Project | Concern | Repository |
| :-: | :-- | :-- | :-: |
| 🔎 | **Grounded RAG Assistant** | Grounded knowledge | [Open →](https://github.com/abdullahakram07/grounded-rag-assistant) |
| 🛡️ | **Bounded Agent Runtime** | Controlled automation | [Open →](https://github.com/abdullahakram07/bounded-agent-runtime) |
| 📏 | **LLM Evaluation Lab** | Measurable quality | [Open →](https://github.com/abdullahakram07/llm-evaluation-lab) |
| 🚦 | **AI Model Gateway** | Inference infrastructure | [Open →](https://github.com/abdullahakram07/ai-model-gateway) |
| 🧱 | **Prompt Injection Defense Lab** | Trust boundaries | [Open →](https://github.com/abdullahakram07/prompt-injection-defense-lab) |

<details>
<summary><b>🔎 Grounded RAG Assistant</b> &nbsp;·&nbsp; grounded knowledge</summary>

<br>

- Document ingestion
- Persistent retrieval
- Source attribution
- Evidence validation

</details>

<details>
<summary><b>🛡️ Bounded Agent Runtime</b> &nbsp;·&nbsp; controlled automation</summary>

<br>

- Durable workflows
- Explicit approval barriers
- Resumable execution
- Audit trails

</details>

<details>
<summary><b>📏 LLM Evaluation Lab</b> &nbsp;·&nbsp; measurable quality</summary>

<br>

- Versioned cases
- Baseline comparisons
- Regression gates
- Inspectable reports

</details>

<details>
<summary><b>🚦 AI Model Gateway</b> &nbsp;·&nbsp; inference infrastructure</summary>

<br>

- Provider routing
- Spend reservations
- Request idempotency
- Failure handling

</details>

<details>
<summary><b>🧱 Prompt Injection Defense Lab</b> &nbsp;·&nbsp; trust boundaries</summary>

<br>

A tool-authorization broker with:

- Tenant checks
- Resource policy
- Expiring approvals
- Adversarial scenarios

</details>

## How I approach a system

```mermaid
flowchart LR
    problem([Define the problem]) --> contract[Specify the contract]
    contract --> build[Implement the workflow]
    build --> evaluate[Evaluate failure cases]
    evaluate --> inspect[Inspect the evidence]
    inspect -->|refine| contract

    classDef step fill:#161B22,stroke:#F5A524,stroke-width:2px,color:#F0F6FC
    class problem,contract,build,evaluate,inspect step
```

| Principle | What it means in code |
| :-- | :-- |
| **Evidence first** | Trace responses to their sources and make uncertainty explicit. |
| **Bounded actions** | Validate tool inputs, permissions, and approval requirements. |
| **Observable failures** | Preserve useful errors, state transitions, and audit records. |
| **Measured quality** | Compare behavior against explicit cases and baselines. |

## Current toolkit

![Python](https://img.shields.io/badge/Python-0D1117?style=for-the-badge&logo=python&logoColor=F5A524)
![SQLite](https://img.shields.io/badge/SQLite_/_FTS5-0D1117?style=for-the-badge&logo=sqlite&logoColor=F5A524)
![HTTP APIs](https://img.shields.io/badge/HTTP_APIs-0D1117?style=for-the-badge&logoColor=F5A524)
![Ollama](https://img.shields.io/badge/Ollama_integrations-0D1117?style=for-the-badge&logo=ollama&logoColor=F5A524)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-0D1117?style=for-the-badge&logo=githubactions&logoColor=F5A524)
![Testing](https://img.shields.io/badge/Automated_testing-0D1117?style=for-the-badge&logoColor=F5A524)

---

<p align="center"><sub>Clear inputs. Deliberate decisions. Inspectable results.</sub></p>
