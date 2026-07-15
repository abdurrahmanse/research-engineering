# 04 — Visual AI Agent Builder

Drag-and-drop canvas for composing LLM agents, tools, and evaluators.
Ship agents without writing orchestration code.

## Files

- `01_node_graph_engine.ts` — DAG execution, retries, parallelism, conditional edges
- `02_agent_runtime.ts` — Pluggable agent loop: tool use, memory, planning
- `03_tool_registry.ts` — Typed tool definitions, schema validation, sandboxing
- `04_evaluator_runner.ts` — Runs test sets and scores traces against graders
- `05_canvas_editor.tsx` — React Flow canvas: nodes, edges, inspector, minimap

## Stack

TypeScript · React Flow · LangGraph / custom runtime · Zod · OpenTelemetry
