<p align="center">
  <img src="./assets/profile-banner.svg" alt="I teach AI systems to survive contact with production" width="100%" />
</p>

<p align="center">
  <a href="https://amulyagupta.in"><b>Portfolio</b></a> ·
  <a href="https://www.linkedin.com/in/amulya-gupta-bits-pilani/"><b>LinkedIn</b></a> ·
  <a href="mailto:amulyagupta2001@gmail.com"><b>Build with me</b></a>
</p>

```python
amulya = {
    "role": "AI & MLOps Engineer",
    "obsession": "making intelligent systems measurable, releasable, and reliable",
    "building": ["retrieval systems", "evaluation pipelines", "production AI platforms"],
    "rule": "if it cannot be observed, it is not ready for production",
}
```

## Mission control

These are not notebook demos. Each project answers a production question.

| System | Mission | Production signal |
|---|---|---|
| **[RetrievalOps](https://github.com/amulyagupta1278/retrievalops)** | Choose the best retrieval policy for each corpus | Frozen quality gates, drift detection, canaries, observability, rollback |
| **[RAG Retrieval Lab](https://github.com/amulyagupta1278/rag-retrieval-dissertation)** | Find what actually improves retrieval | Five-system benchmark, human judgments, reproducible evidence |
| **[AI Operations Command Center](https://github.com/amulyagupta1278/incident-response-system)** | Turn incidents into evidence-backed recovery plans | Secure ingestion, multi-agent RCA, audit trails, offline fallbacks |
| **[Agentic Ticket Automation](https://github.com/amulyagupta1278/agentic-ai-ticket-automation)** | Resolve support issues before they escalate | Classification, RAG, agent routing, MLflow, Prometheus, Grafana |

## My production loop

```mermaid
flowchart LR
    A[Raw signal] --> B[Retrieval]
    B --> C[Evaluation]
    C --> D{Quality gate}
    D -->|pass| E[Canary release]
    D -->|fail| B
    E --> F[Observe]
    F -->|drift| C
    F -->|healthy| G[Scale]

    style A fill:#07111F,stroke:#63E6BE,color:#EAF2FF
    style B fill:#07111F,stroke:#63E6BE,color:#EAF2FF
    style C fill:#10112B,stroke:#A78BFA,color:#EAF2FF
    style D fill:#10112B,stroke:#A78BFA,color:#EAF2FF
    style E fill:#071C1D,stroke:#38BDF8,color:#EAF2FF
    style F fill:#071C1D,stroke:#38BDF8,color:#EAF2FF
    style G fill:#071C1D,stroke:#63E6BE,color:#EAF2FF
```

## Toolbox, not trophy case

`Python` · `FastAPI` · `PostgreSQL` · `MLflow` · `Docker` · `Kubernetes` · `GitHub Actions` · `Prometheus` · `Grafana` · `AWS` · `GCP`

I use tools when they strengthen an evidence trail: versioned inputs, reproducible evaluations, explicit release gates, observable behavior, and safe failure modes.

## Current coordinates

- 🎓 M.Tech in Artificial Intelligence & Machine Learning at **BITS Pilani**
- 🧪 Exploring retrieval policy selection, RAG evaluation, and dependable agent systems
- 🤝 Open to AI infrastructure, MLOps, retrieval, and backend collaborations

<p align="center">
  <i>Build the model. Test the system. Observe reality.</i>
</p>
