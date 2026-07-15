# 06 — Realtime Analytics Dashboard

Live event-stream analytics with sub-second updates.
The product dashboard every internal team wants in 2026.

## Files

- `01_event_collector.ts` — Server-side event ingestion, schema validation
- `02_aggregation_worker.ts` — Streaming aggregations (counts, percentiles, funnels)
- `03_charting_components.tsx` — Reusable line, bar, sankey, and heatmap components
- `04_filter_state_manager.ts` — URL-synced filter state with undo / redo
- `05_dashboard_canvas.tsx` — Drag-and-drop dashboard with persisted layouts

## Stack

TypeScript · React · Kafka / Redis Streams · ECharts / visx · Zustand / Jotai
