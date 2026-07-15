# 08 — Micro-Frontend E-Commerce

A storefront built from independently deployable micro-frontends.
Each team owns a vertical slice end-to-end.

## Files

- `01_module_federation_config.ts` — Webpack 5 / Vite module federation wiring
- `02_catalog_microfrontend.tsx` — Browse, search, product detail
- `03_cart_microfrontend.tsx` — Cart, cross-tab state, optimistic updates
- `04_checkout_microfrontend.tsx` — Multi-step checkout, payments, addresses
- `05_shared_design_system.tsx` — Tokens, primitives, and a11y patterns consumed by all

## Stack

TypeScript · Module Federation · React · Tailwind · Stripe · Storybook
