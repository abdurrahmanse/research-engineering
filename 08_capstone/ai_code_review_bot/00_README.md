# 07 — AI-Powered Code Review Bot

Drop a bot into your GitHub repo and get thoughtful, line-level review comments
on every pull request.

## Files

- `01_diff_parser.ts` — Unified diff → structured change objects with line context
- `02_review_prompts.ts` — Specialized prompts (security, perf, style, tests)
- `03_llm_judge.ts` — Multi-judge LLM voting with confidence scores
- `04_github_webhook_handler.ts` — App auth, signature verification, event routing
- `05_pr_comment_formatter.ts` — Inline comments, severity labels, suggested fixes

## Stack

TypeScript · GitHub Apps · OpenAI / Claude · unified diff parser · Probot
