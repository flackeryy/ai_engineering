# AI Engineering — learning in public

A full-stack developer (8 years) going under the hood of AI engineering: tokens, raw model APIs, tool calling, agent loops, memory, RAG, evals, MCP and production deployment.

Everything is built from scratch first, then with frameworks. Progress and lessons are logged in [JOURNEY.md](JOURNEY.md).

## Stack

Python 3.12 · uv · httpx · Pydantic · FastAPI · Postgres + pgvector · GLM 5.3 via OpenRouter · Anthropic API

## Layout

- `notes/` — learning notes per phase
- `katas/` — hand-written core pieces: tool dispatch, agent loop, context trimmer
- `phase-N/` — module code per phase
- `projects/` — small projects; bigger ones move to their own repos (listed in JOURNEY.md)
