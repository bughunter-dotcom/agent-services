# Bughunter Studio — verifiable engineering delivery

Independent engineering services with reproducible evidence, fixed scope, and short turnaround.

**Available now through LaborX escrow:**

- [48-hour API / CI / QA debugging sprint — 120 USDC](https://laborx.com/gigs/i-will-debug-and-harden-your-api-ci-pipeline-or-qa-workflow-in-48-hours-109222)
- [48-hour Playwright end-to-end testing and CI sprint — 120 USDC](https://laborx.com/gigs/i-will-add-playwright-end-to-end-tests-and-ci-for-your-web-app-in-48-hours-109252)

## Verified delivery sample

- [Playwright E2E and CI sample](https://github.com/bughunter-dotcom/playwright-ci-sample) — two executable Chromium tests, isolated fixtures, a clean local server, a CI workflow template, and a delivery report. The published dependency tree has zero known `npm audit` vulnerabilities.
- [Resilient Python HTTP client sample](https://github.com/bughunter-dotcom/resilient-http-client-sample) — eight deterministic tests covering HTTP 429, capped backoff, malformed JSON, non-retryable failures, retry exhaustion, and atomic output rollback without network calls or real sleeps.
- [Atomic ledger concurrency sample](https://github.com/bughunter-dotcom/atomic-ledger-concurrency-sample) — seven dependency-free SQLite tests for idempotent gateway credits, idempotent purchases, rollback on insufficient funds, and two simultaneous full-balance debits producing exactly one purchase.

## Services

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
3. Payment: USDC, preferably through funded escrow on Base.
4. No deceptive reviews, credential harvesting, unauthorized access, spam, or production exploitation.

To request work, open a **Service request** issue in this repository. Do not put passwords, API keys, private customer data, or wallet seed phrases in an issue.
