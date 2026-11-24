<p align="center">
  <a href="https://braylo.si">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="assets/braylo-signature-cream.png">
      <img src="assets/braylo-signature-navy.png" alt="Braylo signature" width="209">
    </picture>
  </a>
</p>

# Brandon "Braylo" Lopez

Certified Claude FDE & AI safety researcher, Techstars alum.

Founded 7 companies · [braylo.si](https://braylo.si): AI implementation for small businesses · install@braylo.si

## Featured

Numbers dated 2026-11-24. Each comes from the repo's `results/metrics.json` or test runner.

| Project | Numbers (2026-11-24) | Demo | Paper / Docs | CI |
| --- | --- | --- | --- | --- |
| **Gaden**: closed-loop hunger control (simulation, not a medical device) | Best controller (PID) passes 86.8% of 1,000 stress scenarios (95% Wilson CI 84.6–88.7%) · 496 tests · 97.6% coverage | [live](https://gaden-demo.braylo777.workers.dev) · [repo](https://github.com/braylo777/gaden-health-demo) | [How Gaden works](https://github.com/braylo777/gaden-health-demo/blob/main/docs/HOW-GADEN-WORKS.md) | [![CI](https://github.com/braylo777/gaden-health-demo/actions/workflows/ci.yml/badge.svg)](https://github.com/braylo777/gaden-health-demo/actions/workflows/ci.yml) |
| **NimBros**: agentic-native memecoin launchpad | 653 Node tests + 45 Rust tests · 3 agent interfaces (MCP, REST, C++ CLI) | [live](https://x-nimbros-si.pages.dev) · [repo](https://github.com/braylo777/nimbros) | [Architecture](https://github.com/braylo777/nimbros/blob/main/docs/ARCHITECTURE.md) | [![CI](https://github.com/braylo777/nimbros/actions/workflows/ci.yml/badge.svg)](https://github.com/braylo777/nimbros/actions/workflows/ci.yml) |
| **Nimbus Chain**: Agent-speed SI blockchain | 207K signed entries/s (M2 Pro) · 1.92 KB proof verified in 0.46 ms · 309 tests · 4 fuzz targets, 0 crashes (30 min each) | [live](https://nimbus-verifier.pages.dev) · [repo](https://github.com/braylo777/nimbus-chain) | [17-page dissertation](https://github.com/braylo777/nimbus-chain/blob/main/docs/dissertation/nimbus-dissertation.pdf) | [![CI](https://github.com/braylo777/nimbus-chain/actions/workflows/ci.yml/badge.svg)](https://github.com/braylo777/nimbus-chain/actions/workflows/ci.yml) |
| **.dov pLang**: rewritten C/C++ for agentic immutability | 383 tests · 93.8% coverage · 12 examples · 0 dependencies · emits C11 | [playground](https://dov-playground.pages.dev) · [repo](https://github.com/braylo777/dov-plang) | [Architecture](https://github.com/braylo777/dov-plang/blob/main/docs/ARCHITECTURE.md) | [![CI](https://github.com/braylo777/dov-plang/actions/workflows/ci.yml/badge.svg)](https://github.com/braylo777/dov-plang/actions/workflows/ci.yml) |
| **Empirical AI Welfare (EAW)**: behavioral stress benchmark for LLMs | 58.7% false-pass under pressure (95% CI 57.7–59.8%) over 55,080 real model runs · 25.2M simulated trials (simulation, labelled) · 383 tests | [dashboard](https://eaw-results.pages.dev) · [repo](https://github.com/braylo777/eas-benchmark) | [EAW paper](https://github.com/braylo777/eas-benchmark/blob/main/docs/EAW-paper.pdf) | [![CI](https://github.com/braylo777/eas-benchmark/actions/workflows/ci.yml/badge.svg)](https://github.com/braylo777/eas-benchmark/actions/workflows/ci.yml) |

## New: Forward Deployed Engineering, 12 stages (2026-11-24)

One Rust repo per stage of an enterprise AI rollout. Each has a library, a CLI, tests and a live WebAssembly demo that runs in your browser.

| Stage | Project | Links |
| --- | --- | --- |
| 1 | **Enterprise Identity & Agent RBAC**: Scoped tool tokens, delegated agent auth, SCIM auto-revocation, row-level security | [live](https://fde-01-agent-rbac.braylo777.workers.dev) · [repo](https://github.com/braylo777/fde-01-agent-rbac) |
| 2 | **Air-Gapped & VPC Inference**: Policy checks that keep an LLM inside a private VPC: pinned images, default-deny, no egress | [live](https://fde-02-airgap-deploy.braylo777.workers.dev) · [repo](https://github.com/braylo777/fde-02-airgap-deploy) |
| 3 | **Legacy Data Extraction & ETL**: Mainframe records, messy CSVs and documents into typed, reconciled data | [live](https://fde-03-legacy-etl.braylo777.workers.dev) · [repo](https://github.com/braylo777/fde-03-legacy-etl) |
| 4 | **Permission-Filtered RAG & GraphRAG**: ACL checks before ranking, tenant isolation, cited sentences, honest "I don't know" | [live](https://fde-04-permission-rag.braylo777.workers.dev) · [repo](https://github.com/braylo777/fde-04-permission-rag) |
| 5 | **MCP & Legacy Integration**: Raw JSON-RPC MCP server over SOAP and SAP with safe XML and rate limits | [live](https://fde-05-mcp-legacy-bridge.braylo777.workers.dev) · [repo](https://github.com/braylo777/fde-05-mcp-legacy-bridge) |
| 6 | **PII Cryptography & Guardrails**: Deterministic tokens before the model, role-based unmasking, tamper-evident log | [live](https://fde-06-pii-vault.braylo777.workers.dev) · [repo](https://github.com/braylo777/fde-06-pii-vault) |
| 7 | **Human-in-the-Loop & Durable Workflows**: Crash-safe agent workflows that wait for a human and never refund twice | [live](https://fde-07-durable-hitl.braylo777.workers.dev) · [repo](https://github.com/braylo777/fde-07-durable-hitl) |
| 8 | **Edge & On-Prem Inference**: Quantization that fits the customer's hardware, safe routing when a server is down | [live](https://fde-08-edge-inference.braylo777.workers.dev) · [repo](https://github.com/braylo777/fde-08-edge-inference) |
| 9 | **Telemetry, ROI & Customer Health**: LLM logs into OpenTelemetry traces, cost per department, ROI and an invoice | [live](https://fde-09-llm-telemetry.braylo777.workers.dev) · [repo](https://github.com/braylo777/fde-09-llm-telemetry) |
| 10 | **Shadow Evals on Customer Data**: Golden sets from logs, shadow grading, calibrated judge, McNemar paired tests | [live](https://fde-10-shadow-evals.braylo777.workers.dev) · [repo](https://github.com/braylo777/fde-10-shadow-evals) |
| 11 | **Discovery & SOW Scoping**: Workshop notes into a gap analysis, STRIDE threat model and a 4-week SOW | [live](https://fde-11-sow-scoper.braylo777.workers.dev) · [repo](https://github.com/braylo777/fde-11-sow-scoper) |
| 12 | **Handoff & Self-Serve Admin**: Runbooks that run, config portal with rollback, chaos tests, go / no-go score | [live](https://fde-12-handoff-admin.braylo777.workers.dev) · [repo](https://github.com/braylo777/fde-12-handoff-admin) |

## Recent builds

| Project | What it proves | Links |
| --- | --- | --- |
| **Bagz**: ATS-compatible, swipe-to-apply job app | 14.2K jobs indexed · 209 tests · 6 approval-gated agents · Rust 99% | [repo](https://github.com/braylo777/bagz) · [live](https://bagz-demo.braylo777.workers.dev) |
| **MCP LockGate (MLG)** | Immutable quarantine for poisoned MCP tool graphs: 94% of 690 attacks caught, 0% false positives on 1,000 benign manifests, p99 0.13 ms, 345 tests. | [repo](https://github.com/braylo777/mcp-prod-gateway) |
| **Governing-Docs Copilot** | Next.js App Router + Postgres row-level security multi-tenancy, pgvector hybrid retrieval, cited answers. 25 tests (Vitest, Playwright) incl. cross-tenant isolation. | [repo](https://github.com/braylo777/governing-docs-copilot) · [live](https://governing-docs-copilot.braylo777.workers.dev) |
| **Capacity Reservation & Matching Engine** | GPU-hour market with price-time matching, escrow and a double-entry ledger; 5 fast-check properties x 300 random markets (books balance, no overselling). | [repo](https://github.com/braylo777/capacity-matching-engine) · [live](https://capacity-matching-engine.braylo777.workers.dev) |
| **GPU Cluster Home Lab** *(simulated)* | Rust node agent (health, drain, Prometheus), K8s + Slurm configs, backfill sim: drain cut killed jobs 3,676 → 2 on a silent node failure. | [repo](https://github.com/braylo777/gpu-cluster-lab) · [live](https://gpu-cluster-lab.braylo777.workers.dev) |
| **Video-to-Data API** | Transcript (VTT/SRT) → chapters, entities, action items with owners; API + TS SDK. Holdout chapter F1 0.68 vs 0.24 naive (synthetic). | [repo](https://github.com/braylo777/video-to-data-api) · [live](https://video-to-data-api.braylo777.workers.dev) |
| **Wealth-Ops Agent** *(synthetic data)* | Finds reconciliation breaks, proposes fixes, human approval gate + audit log. 550/550 planted breaks found across 50 seeds. | [repo](https://github.com/braylo777/wealth-ops-agent) · [live](https://wealth-ops-agent.braylo777.workers.dev) |
| **RAG Assistant, Azure-ready** | Bicep + Terraform (managed identity) + deploy guide; runs locally/Cloudflare. No Azure account connected. | [repo](https://github.com/braylo777/rag-assistant-azure) · [live](https://rag-assistant-azure.braylo777.workers.dev) |
| **Compute Price Index** | Live $/GPU-hour index for 11 SKUs from vast.ai + RunPod quotes, MAD outlier rules, forward curve, own-vs-rent TCO, Postgres schema. 21 tests. | [repo](https://github.com/braylo777/compute-price-index) · [live](https://compute-price-index.braylo777.workers.dev) |
| **Eval Regression Lab** | 100 hand-labelled items, 4 ablations on the Copilot (hybrid 89% vs 80-87%), judge κ 0.95, CI gate that fails on regression. 15 tests. | [repo](https://github.com/braylo777/eval-regression-lab) · [live](https://eval-regression-lab.braylo777.workers.dev) |
| **Braylo SI RAG Assistant** | Hybrid retrieval, guards and traces on Workers AI. hit@5 0.958, 29/30 attacks blocked. | [repo](https://github.com/braylo777/braylo-si-rag) · [live](https://braylo-si-rag.braylo777.workers.dev) |
| **Agent Spend Guard** · **Review Trust** | Budget/merchant policy + fraud score for agent purchases · genuine vs deceptive review scorer. Private repos. | [live](https://agent-20-agent-spend-guard.braylo777.workers.dev) · [live](https://agent-21-review-trust.braylo777.workers.dev) |
| **CarNimbus** | Bilingual self-serve car-buying funnel, live for a Porsche dealer client. Private repo. | [live](https://carnimbus.us) |
| **AI Visibility Lab** | Share-of-voice measurement for local businesses in AI answers: Wilson/bootstrap CIs, Plackett-Luce, difference-in-differences. 32 tests. | private |

## Agent portfolio (live demos)

[01 Single ReAct agent](https://agent-01-single-agent.braylo777.workers.dev) ([repo](https://github.com/braylo777/agent-01-single-agent)) · [02 Tool calling](https://agent-02-tool-calling.braylo777.workers.dev) ([repo](https://github.com/braylo777/agent-02-tool-calling)) · [03 Multi-agent crew](https://agent-03-multi-agent.braylo777.workers.dev) ([repo](https://github.com/braylo777/agent-03-multi-agent)) · [04 Memory (KV)](https://agent-04-memory.braylo777.workers.dev) ([repo](https://github.com/braylo777/agent-04-memory)) · [05 RAG + citations](https://agent-05-rag.braylo777.workers.dev) ([repo](https://github.com/braylo777/agent-05-rag)) · [06 Remote MCP server](https://agent-06-mcp-server.braylo777.workers.dev) ([repo](https://github.com/braylo777/agent-06-mcp-server)) · [07 Durable workflow](https://agent-07-workflow.braylo777.workers.dev) ([repo](https://github.com/braylo777/agent-07-workflow)) · [08 Human-in-the-loop](https://agent-08-human-in-loop.braylo777.workers.dev) ([repo](https://github.com/braylo777/agent-08-human-in-loop)) · [09 Multi-agent platform](https://agent-09-multi-agent-platform.braylo777.workers.dev) ([repo](https://github.com/braylo777/agent-09-multi-agent-platform)) · [10 Production agent](https://agent-10-production-agent.braylo777.workers.dev) ([repo](https://github.com/braylo777/agent-10-production-agent)) · [11 RAG eval harness](https://agent-11-rag-eval-harness.braylo777.workers.dev) ([repo](https://github.com/braylo777/agent-11-rag-eval-harness)) · [12 LoRA fine-tune](https://agent-12-lora-finetune.braylo777.workers.dev) ([repo](https://github.com/braylo777/agent-12-lora-finetune)) · [13 Serving & observability](https://agent-13-serving-observability.braylo777.workers.dev) ([repo](https://github.com/braylo777/agent-13-serving-observability)) · [14 Guardrails red-team](https://agent-14-guardrails-redteam.braylo777.workers.dev) ([repo](https://github.com/braylo777/agent-14-guardrails-redteam)) · [15 Scam Shield](https://agent-15-scam-shield.braylo777.workers.dev) ([repo](https://github.com/braylo777/agent-15-scam-shield)) · [16 Agent analytics](https://agent-16-agent-analytics.braylo777.workers.dev) ([repo](https://github.com/braylo777/agent-16-agent-analytics)) · [17 Legal clause eval harness](https://agent-17-legal-eval-harness.braylo777.workers.dev) ([repo](https://github.com/braylo777/agent-17-legal-eval-harness)) · [18 Freight voice agent](https://agent-18-voice-agent-latency.braylo777.workers.dev) ([repo](https://github.com/braylo777/agent-18-voice-agent-latency)) · [19 Distilled reranker](https://agent-19-distilled-reranker.braylo777.workers.dev) ([repo](https://github.com/braylo777/agent-19-distilled-reranker))

**Stack:** Rust, WebAssembly, Python, TypeScript, React/Next.js, Postgres, Cloudflare Workers.
