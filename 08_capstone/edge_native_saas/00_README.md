# 03 — Edge-Native SaaS Starter

A complete multi-tenant SaaS shell designed to run on edge functions.
Fast everywhere, by default.

## Files

- `01_multi_tenant_routing.ts` — Host / path-based tenant resolution at the edge
- `02_kv_data_layer.ts` — Typed data access on top of edge KV / Durable Objects
- `03_billing_stripe_webhook.ts` — Subscription state sync via signed webhooks
- `04_rbac_authorizer.ts` — Role + permission checks, cached per request
- `05_admin_dashboard.tsx` — Server-rendered admin with charts and tables
- `06_observability_tracing.ts` — OpenTelemetry traces, structured logs, metrics

## Stack

TypeScript · Cloudflare Workers / Vercel Edge · Stripe · Drizzle ORM · OpenTelemetry
