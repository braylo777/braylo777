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

| Project | Numbers | Links |
| --- | --- | --- |
| **Gaden**: closed-loop hunger control | 83% stress pass across 240 scenarios · 4 controllers (PID, MPC, bandit, open-loop) · fit RMSE 0.012 · 178 tests · 97% coverage | [gaden-health-demo](https://github.com/braylo777/gaden-health-demo) |
| **NimBros**: agentic-native memecoin launchpad | 5+ launchpads · 35 coins live · $70M 24h volume tracked (snapshot 2026-11-21) · 3 agent interfaces (MCP, REST, C++ CLI) | [live](https://x-nimbros-si.pages.dev) |
| **Nimbus Chain**: Agent-speed SI blockchain. | 150K–183K signed entries/s on 4 cores · 195 ns/op order matching · 8.4M ops/s across 16 markets · 3.8 KB light-client proof, verified in 1.1 ms · 120 Rust tests | [nimbus-chain](https://github.com/braylo777/nimbus-chain) |
| **.dov pLang**: rewritten C/C++ for agentic immutability | Immutable by default · agents, not threads · emits C11 · 35 tests · 0 dependencies · Rust 95% | [dov-plang](https://github.com/braylo777/dov-plang) |
| **Empirical AI Welfare (EAW)**: LLM pre-training "trauma" benchmark | 56% false-pass (CI 55.8–56.1%) · 25.2M trials · 11 models · 187 tests · 98% coverage | [eas-benchmark](https://github.com/braylo777/eas-benchmark) |

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
