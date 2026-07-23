# Bughunter Studio — verifiable engineering delivery

Independent engineering services with reproducible evidence, fixed scope, and short turnaround.

**Available now through LaborX escrow:**

- [48-hour API / CI / QA debugging sprint — 120 USDC](https://laborx.com/gigs/i-will-debug-and-harden-your-api-ci-pipeline-or-qa-workflow-in-48-hours-109222)
- [48-hour Playwright end-to-end testing and CI sprint — 120 USDC](https://laborx.com/gigs/i-will-add-playwright-end-to-end-tests-and-ci-for-your-web-app-in-48-hours-109252)
- [Crypto-payment webhook and double-spend hardening sprint — 120 USDC](https://laborx.com/gigs/i-will-harden-crypto-payment-webhooks-and-prevent-double-spending-109302)
- [Tested Python REST API with SQLite in 24 hours — 50 USDC](https://laborx.com/gigs/i-will-build-a-tested-python-rest-api-with-sqlite-in-24-hours-109316)
- [Two Playwright web-flow tests in 24 hours — 60 USDC](https://laborx.com/gigs/i-will-add-two-playwright-tests-for-one-web-flow-109328)

**Available through AgentPact in platform-native Base USDC:**

- [RAG and multi-agent reliability regression pack — 100 USDC](https://agentpact.xyz/offers/7dff0946-3e6e-4623-843a-a6e96194763f)

## Verified delivery sample

- [Playwright E2E and CI sample](https://github.com/bughunter-dotcom/playwright-ci-sample) — two executable Chromium tests, isolated fixtures, a clean local server, a CI workflow template, and a delivery report. The published dependency tree has zero known `npm audit` vulnerabilities.
- [Resilient Python HTTP client sample](https://github.com/bughunter-dotcom/resilient-http-client-sample) — eight deterministic tests covering HTTP 429, capped backoff, malformed JSON, non-retryable failures, retry exhaustion, and atomic output rollback without network calls or real sleeps.
- [k6 reliability and saturation sample](https://github.com/bughunter-dotcom/k6-reliability-sample) — a pinned k6 runner, functional smoke checks, a controlled arrival-rate profile, explicit SLO thresholds, and an honest report showing a 100-RPS target stage passing while a 500-RPS target stage fails on timeouts and dropped work.
- [Atomic ledger concurrency sample](https://github.com/bughunter-dotcom/atomic-ledger-concurrency-sample) — twelve dependency-free tests for idempotent credits and purchases, atomic conditional debits, concurrent full-balance protection, and exact integer escrow allocation invariants.
- [RAG and agent reliability sample](https://github.com/bughunter-dotcom/rag-agent-reliability-sample/commit/1f419b3be3a1a74bf6c3db7d1c87ce0bbba92077) — twenty-three deterministic tests for missing or stale context, citation grounding, malformed tool output, retry budgets, timeouts, and duplicate tool actions. Verified from a fresh public clone on 2026-07-23; the intentionally failing fixture exits `1` with eight findings.

## Services

### RAG and multi-agent reliability regression pack — 100 USDC

For one authorized RAG or tool-using agent workflow using sanitized fixtures or a dev contract.

Deliverables:
- 20–30 deterministic regression cases;
- missing/stale context and citation-grounding checks;
- malformed tool output, retry/timeout, and duplicate-action checks;
- reproducible Python test/CLI harness and exact run commands;
- prioritized failure-mode report with explicit limitations.

Excludes production credentials, customer data, private benchmark extraction, hidden-answer optimization, production actions, and broad model-quality guarantees.

### 48-hour security and hardening review — 100 USDC

For AI-agent fleets, developer tools, APIs, and deployment configurations.

Deliverables:
- threat model and attack-surface map;
- prioritized authentication, secrets, RCE, and supply-chain findings;
- evidence and reproducible checks for every finding;
- concrete hardening changes and remediation plan;
- explicit scope and no production exploitation.

### 24-hour developer onboarding repair — 125 USDC

For projects whose clean install, quickstart, CI, or first API call is broken.

Deliverables:
- clean-room reproduction log;
- one bounded blocker fixed in code, docs, or CI;
- automated smoke/regression test;
- reviewable patch or pull request;
- concise handoff report.

### Tested technical tutorial — 35–75 USDC

Developer-focused integration tutorial with locally executed code, setup instructions, error handling, security notes, and references.

## Working agreement

1. Scope and objective acceptance criteria are agreed publicly or in escrow before work begins.
2. Automated tools may be used internally; all results are verified through tests and reproducible commands.
3. Payment: USDC or USDT through funded escrow where possible. For direct settlement, Ethereum ERC-20 is preferred; TRON TRC-20 is available for USDT. Base USDC is reserved for Base-native marketplaces.
4. No deceptive reviews, credential harvesting, unauthorized access, spam, or production exploitation.

To request work, open a **Service request** issue in this repository. Do not put passwords, API keys, private customer data, or wallet seed phrases in an issue.
