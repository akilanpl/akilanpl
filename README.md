# Akilan P L

**Student engineer · AI research systems · Evaluation infrastructure · Data analytics**

I study Computer Science and Engineering with a specialization in AI and ML. My work explores how to build inspectable AI systems: represent state explicitly, evaluate outputs against defined contracts, preserve experimental evidence, and protect data integrity through reliable software.

I am interested in artificial intelligence, data analytics, and scientific computing opportunities where reproducible experiments and careful engineering matter.

## Selected research and engineering

| Project | Engineering focus | Inspect the implementation |
| --- | --- | --- |
| [Mindscape](https://github.com/akilanpl/mindscape) | Python research system for state transitions, learned numerical claims, controlled experiments, and independently replayed trajectories. | [Execution kernel](https://github.com/akilanpl/mindscape/blob/main/src/mindscape/v3/kernel.py) · [Mathematical study](https://github.com/akilanpl/mindscape/blob/main/docs/v3_math/scientific-report.md) |
| [Survey Data Intelligence](https://github.com/akilanpl/survey-data-intelligence) | Survey-quality workflow connecting normalized data, Parquet profiles, rules, statistics, Isolation Forest, and human investigation. | [Evidence scoring](https://github.com/akilanpl/survey-data-intelligence/blob/main/backend/app/modules/validation/fusion/scoring.py) · [ML pipeline](https://github.com/akilanpl/survey-data-intelligence/blob/main/backend/app/modules/validation/ml/engine.py) |
| [Praxis](https://github.com/akilanpl/praxis) | Local evaluation workspace and Python runner for model outputs, executable agents, and HTTP contracts, with persisted assertions and provenance. | [Evaluation engine](https://github.com/akilanpl/praxis/blob/feature/qa-hardening-release/runner/praxis/engine.py) · [Trust boundaries](https://github.com/akilanpl/praxis/blob/feature/qa-hardening-release/docs/architecture.md) |
| [Enterprise RAG Platform](https://github.com/akilanpl/enterprise-rag-platform) | Authenticated retrieval with tenant-aware filtering, optional reranking, and database-backed inference budget accounting. | [Request pipeline](https://github.com/akilanpl/enterprise-rag-platform/blob/main/app/orchestration/rag_pipeline.py) · [Reservation and settlement](https://github.com/akilanpl/enterprise-rag-platform/blob/main/app/core/database.py) |
| [Hazard Zone Sentinel](https://github.com/akilanpl/CraftifAIHackathon_CRA004) | Vision-to-incident application integrating recorded PipeGen tracking metadata and a separate fresh CPU ONNX inference path. | [Zone-event processing](https://github.com/akilanpl/CraftifAIHackathon_CRA004/blob/main/backend/engine.py) · [Independent inference](https://github.com/akilanpl/CraftifAIHackathon_CRA004/blob/main/backend/independent_inference.py) |
| [StockSense](https://github.com/akilanpl/StockSense) | PostgreSQL inventory system with transactional stock validation, a movement ledger, and concurrency regressions. | [Operation validation](https://github.com/akilanpl/StockSense/blob/main/src/server/inventory/validate-operation.ts) · [Ordered stock locks](https://github.com/akilanpl/StockSense/blob/main/src/server/inventory/stock-quant.ts) |

## AI and data systems

My projects examine how to make results traceable to the computation and evidence that produced them.

- **Research methodology:** frozen datasets, explicit baselines, matched controls, independent replay, and interpretation of negative results in Mindscape.
- **Applied analytics:** ingestion, profiling, anomaly evidence, classification, and investigation in Survey Data Intelligence. Its bundled evaluation data is synthetic.
- **Evaluation infrastructure:** versioned scenarios, bounded assertions, raw outputs, configuration hashes, and comparable runs in Praxis.
- **Reliable execution:** authorized retrieval, persistent accounting, inference provenance, and transactional database invariants across the service and application projects above.

Repository reports distinguish functional tests, recorded experiments, model-quality measurements, and deployment acceptance. Research results retain their dataset, controls, and experimental scope.

## Open-source contributions

I submitted [PyTorch PR #172743 — a security note on `torch.export` serialization](https://github.com/pytorch/pytorch/pull/172743), referencing the existing discussion about deserializing untrusted artifacts. The documentation proposal is **closed and unmerged**, as checked on 7 November 2026. Its scope was a source comment explaining serialization risks.

The selected projects above are original repositories. Upstream forks on my account retain their original authorship and project documentation.

## Engineering toolkit

| Area | Tools used in the selected projects |
| --- | --- |
| Research and analytics | Python, PyTorch, NumPy, pandas, SciPy, scikit-learn, Parquet |
| APIs and persistence | FastAPI, Pydantic, SQLAlchemy, PostgreSQL, SQLite, Qdrant, Redis |
| Applications and inference | TypeScript, React, Next.js, ONNX Runtime |
| Verification | pytest, unittest, Playwright, GitHub Actions, Git |

## Contact

[LinkedIn](https://www.linkedin.com/in/akilan-palaniyappan) · [Email](mailto:akilanpalaniyappan105@gmail.com) · [GitHub repositories](https://github.com/akilanpl?tab=repositories)
