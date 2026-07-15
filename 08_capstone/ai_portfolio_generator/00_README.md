# 01 — AI-Powered Portfolio Generator

Drop in a resume, get a fully-styled, deployable static portfolio site.
AI writes the copy; the theme engine produces the design.

## Files

- `01_resume_parser.ts` — PDF / DOCX → structured JSON (experience, skills, projects)
- `02_ai_section_writer.ts` — LLM rewrites bullet points into impact-driven copy
- `03_theme_engine.ts` — Selects typography, color palette, and layout from preferences
- `04_static_site_emitter.ts` — Renders Astro / Next.js static site with sections
- `05_deployment_pipeline.ts` — GitHub Actions: build → preview → production deploy

## Stack

TypeScript · LLM APIs · Astro / Next.js · Tailwind · GitHub Actions · Vercel
