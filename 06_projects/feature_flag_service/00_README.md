# 11 — Tiny Feature Flag Service

Lightweight feature flags for frontend teams: targeting, percentage rollouts, A/B tests.

## Files

- `01_flag_definitions.ts` — Strongly-typed flag definitions
- `02_evaluation_engine.ts` — Targeting rules + percentage rollout hashing
- `03_react_provider.tsx` — React context + hooks (`useFlag`, `useVariant`)

## Stack

TypeScript · React · Edge KV (for low-latency evaluation) · PostHog-style events
