![Abdullah Akram — AI systems, thoughtfully engineered](assets/header.svg)

<p align="center">
  <b>Applied AI · Python · Reliable systems</b><br>
  Building software that makes its evidence, decisions, and failure modes visible.
</p>

---

### About my work

I'm Abdullah. My current focus is the engineering around AI: getting useful context into a model, controlling what an agent can do, measuring response quality, and keeping inference costs predictable.

I prefer explicit contracts, inspectable behavior, and small components with clear responsibilities.

### On the workbench

Five projects are being developed locally. Their GitHub repositories are reserved; implementation and walkthroughs will be published after review.

<table>
<tr>
<td width="50%" valign="top">
<h3>01 / Grounded knowledge</h3>
<p><b>Grounded RAG Assistant</b></p>
<p>Document ingestion, persistent retrieval, source attribution, and evidence validation.</p>
<a href="https://github.com/abdullahakram07/grounded-rag-assistant">Repository →</a>
</td>
<td width="50%" valign="top">
<h3>02 / Controlled automation</h3>
<p><b>Bounded Agent Runtime</b></p>
<p>Durable workflows, explicit approval barriers, resumable execution, and audit trails.</p>
<a href="https://github.com/abdullahakram07/bounded-agent-runtime">Repository →</a>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<h3>03 / Measurable quality</h3>
<p><b>LLM Evaluation Lab</b></p>
<p>Versioned cases, baseline comparisons, regression gates, and inspectable reports.</p>
<a href="https://github.com/abdullahakram07/llm-evaluation-lab">Repository →</a>
</td>
<td width="50%" valign="top">
<h3>04 / Inference infrastructure</h3>
<p><b>AI Model Gateway</b></p>
<p>Provider routing, spend reservations, request idempotency, and failure handling.</p>
<a href="https://github.com/abdullahakram07/ai-model-gateway">Repository →</a>
</td>
</tr>
<tr>
<td colspan="2" valign="top">
<h3>05 / Trust boundaries</h3>
<p><b>Prompt Injection Defense Lab</b></p>
<p>A tool-authorization broker with tenant checks, resource policy, expiring approvals, and adversarial scenarios.</p>
<a href="https://github.com/abdullahakram07/prompt-injection-defense-lab">Repository →</a>
</td>
</tr>
</table>

### How I approach a system

```mermaid
flowchart LR
    problem[Define the problem] --> contract[Specify the contract]
    contract --> build[Implement the workflow]
    build --> evaluate[Evaluate failure cases]
    evaluate --> inspect[Inspect the evidence]
    inspect --> contract
```

| Principle | What it means in code |
| :--- | :--- |
| Evidence first | Trace responses to their sources and make uncertainty explicit. |
| Bounded actions | Validate tool inputs, permissions, and approval requirements. |
| Observable failures | Preserve useful errors, state transitions, and audit records. |
| Measured quality | Compare behavior against explicit cases and baselines. |

### Current toolkit

**Python** · **SQLite / FTS5** · **HTTP APIs** · **Ollama integrations** · **GitHub Actions** · **Automated testing**

---

<p align="center"><sub>Clear inputs. Deliberate decisions. Inspectable results.</sub></p>
