# Sathkruthi

**Backend reliability · Distributed systems · Debugging · CI/CD**

My engineering portfolio explores how systems preserve correctness when messages arrive late, workers crash, dependencies fail, and deployments regress. Each project includes executable failure scenarios, measured evidence, and explicit limitations.

## Featured engineering projects

| Project | Engineering focus | Start here |
|---|---|---|
| [FactoryMesh](https://github.com/sathkruthi/factorymesh-industrial-observability) | Go, MQTT, PostgreSQL, OpenTelemetry — durable telemetry ingestion, ordering protection, duplicate handling, and alert state | [Architecture and verified demo](https://github.com/sathkruthi/factorymesh-industrial-observability#readme) |
| [LedgerFlow](https://github.com/sathkruthi/ledgerflow-transaction-recovery) | Go, PostgreSQL — integer double-entry accounting, idempotency, transactional outbox, crash recovery, and reconciliation | [Publisher crash investigation](https://github.com/sathkruthi/ledgerflow-transaction-recovery/blob/main/incidents/002/problem.md) |
| [ReleaseGuard](https://github.com/sathkruthi/releaseguard-deployment-reliability) | Python, Go, Kubernetes, Helm, Prometheus — configuration safety, failure attribution, guarded rollback, and fresh recovery verification | [Failed rollout and recovery](https://github.com/sathkruthi/releaseguard-deployment-reliability/blob/main/incidents/INCIDENT-002.md) |

## What the projects demonstrate

- Clear contracts for ordering, idempotency, accounting invariants, and uncertain outcomes.
- Investigation through source, structured logs, metrics, traces, and reproducible failures.
- Regression tests and real local integration, repeated on fresh GitHub Actions runners.
- Architecture decisions and runbooks that explain trade-offs and recovery behavior.

**Verified workflows:** [FactoryMesh](https://github.com/sathkruthi/factorymesh-industrial-observability/actions/workflows/ci.yml) · [LedgerFlow](https://github.com/sathkruthi/ledgerflow-transaction-recovery/actions/workflows/ci.yml) · [ReleaseGuard](https://github.com/sathkruthi/releaseguard-deployment-reliability/actions/workflows/ci.yml)

These original portfolio projects were created with AI assistance and use synthetic data. They are engineering demonstrations, with documented verification and limits, rather than claims of production employment or customer impact.
