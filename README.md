# Brandon "Braylo" Lopez

AI engineer: evals, RAG, and agents with human approval. Founder of [Braylo SI](https://braylo-si.pages.dev), AI implementation for small businesses.

## Recent builds

| Project | What it proves | Links |
| --- | --- | --- |
| **Governing-Docs Copilot** | Next.js App Router + Postgres row-level security multi-tenancy, pgvector hybrid retrieval, cited answers. 25 tests (Vitest, Playwright) incl. cross-tenant isolation. | [repo](https://github.com/braylo777/governing-docs-copilot) · [live](https://governing-docs-copilot.braylo777.workers.dev) |
| **Capacity Reservation & Matching Engine** | GPU-hour market with price-time matching, escrow and a double-entry ledger; 5 fast-check properties x 300 random markets (books balance, no overselling). | [repo](https://github.com/braylo777/capacity-matching-engine) · [live](https://capacity-matching-engine.braylo777.workers.dev) |
| **GPU Cluster Home Lab** *(simulated)* | Rust node agent (health, drain, Prometheus), K8s + Slurm configs, backfill sim: drain cut killed jobs 3,676 → 2 on a silent node failure. | [repo](https://github.com/braylo777/gpu-cluster-lab) · [live](https://gpu-cluster-lab.braylo777.workers.dev) |
| **Video-to-Data API** | Transcript (VTT/SRT) → chapters, entities, action items with owners; API + TS SDK. Holdout chapter F1 0.68 vs 0.24 naive (synthetic). | [repo](https://github.com/braylo777/video-to-data-api) · [live](https://video-to-data-api.braylo777.workers.dev) |
| **Wealth-Ops Agent** *(synthetic data)* | Finds reconciliation breaks, proposes fixes, human approval gate + audit log. 550/550 planted breaks found across 50 seeds. | [repo](https://github.com/braylo777/wealth-ops-agent) · [live](https://wealth-ops-agent.braylo777.workers.dev) |
| **RAG Assistant, Azure-ready** | Bicep + Terraform (managed identity) + deploy guide; runs locally/Cloudflare. No Azure account connected. | [repo](https://github.com/braylo777/rag-assistant-azure) · [live](https://rag-assistant-azure.braylo777.workers.dev) |
| **Compute Price Index** | Live $/GPU-hour index for 11 SKUs from vast.ai + RunPod quotes, MAD outlier rules, forward curve, own-vs-rent TCO, Postgres schema. 21 tests. | [repo](https://github.com/braylo777/compute-price-index) · [live](https://compute-price-index.braylo777.workers.dev) |
| **Eval Regression Lab** | 100 hand-labelled items, 4 ablations on the Copilot (hybrid 89% vs 80-87%), judge κ 0.95, CI gate that fails on regression. 15 tests. | [repo](https://github.com/braylo777/eval-regression-lab) · [live](https://eval-regression-lab.braylo777.workers.dev) |
| **Braylo SI RAG Assistant** | Hybrid retrieval, guards and traces on Workers AI. hit@5 0.958, 29/30 attacks blocked. | [repo](https://github.com/braylo777/braylo-si-rag) |
| **Legal clause eval harness** | 240 CUAD cases; verifier lifted precision 0.464 → 0.614, judge kappa 0.74 → 0.91. | [repo](https://github.com/braylo777/agent-17-legal-eval-harness) |
| **Freight voice agent** | Streaming call agent, first token 108 ms p50, 0 guardrail violations on 60 calls. | [repo](https://github.com/braylo777/agent-18-voice-agent-latency) |
| **CarNimbus** | Bilingual self-serve car-buying funnel, live for a Porsche dealer client. | [repo](https://github.com/braylo777/carnimbus-us) · [live](https://carnimbus.us) |
| **AI Visibility Lab** | Share-of-voice measurement for local businesses in AI answers: Wilson/bootstrap CIs, Plackett-Luce, difference-in-differences. 32 tests. | private |

Plus 20 ML/AI projects (`agent-01` … `agent-19`), each with tests and a live Workers demo.

## Building next

Copilot refusal fix (topic-gap check, eval-gated) · next project proposals.

**Stack:** Python, TypeScript, React/Next.js, Postgres, Cloudflare Workers, Rust/Anchor.
