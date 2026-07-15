# 01_solid / mini_projects

Five small, real-world mini projects that exercise **all five SOLID principles together**.
Each project is a single self-contained file (small enough to read in 15 minutes) and targets a
2026-relevant frontend or full-stack scenario.

## Projects

| # | File | Scenario | Principles in focus |
|---|---|---|---|
| 1 | `01_ai_chat_widget_solid.py` | Embeddable AI chat widget with pluggable transports and renderers | SRP, OCP, DIP |
| 2 | `02_dark_mode_provider_solid.py` | Theme provider with multiple strategies (CSS vars, classes, system) | OCP, LSP, DIP |
| 3 | `03_form_validation_engine_solid.py` | Composable validators with rule chaining and custom error renderers | SRP, OCP, ISP |
| 4 | `04_realtime_notification_hub_solid.py` | Hub that fans out events to pluggable channels (toast, sound, push) | OCP, DIP, ISP |
| 5 | `05_api_client_with_retries_solid.py` | HTTP client with pluggable retry / cache / auth strategies | DIP, OCP, LSP |

Each project follows the same shape: a short narrative, an intentional SOLID violation, and a
step-by-step refactor to a clean design. Read them in order; later projects assume earlier idioms.
