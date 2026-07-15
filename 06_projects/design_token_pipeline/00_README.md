# 06 — Design Token Pipeline

Single source of truth for design tokens that compiles to CSS variables,
Tailwind themes, and native platform formats.

## Files

- `01_token_definitions.json` — Canonical token schema (color, spacing, typography)
- `02_token_transformer.ts` — DTCG-style transforms (alias resolution, references)
- `03_css_variables_generator.ts` — Emits `:root { --color-... }` for any web project
- `04_tailwind_theme_emitter.ts` — Emits a Tailwind theme object from the same source

## Stack

TypeScript · DTCG · Style Dictionary · Tailwind · CSS variables
