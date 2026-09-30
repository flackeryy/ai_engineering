# JOURNEY.md — where Andriy is, and what happened so far

Sessions: read the **Now** section first. Append to the **Log** at the end of every module (newest entry at the top). The coordinator maintains everything above the Log.

## Now

- **Phase:** 0 — Setup
- **Next step:** finish the Phase 0 gate below, then start Phase 1, module 01 (Python idioms for a Node developer)
- **Blocked on:** nothing

## Phases and gates

| Phase | Weeks | Focus | Gate | Status |
| --- | --- | --- | --- | --- |
| 0 | weekend | Setup | curl to OpenRouter works · pgvector runs · repo pushed | in progress |
| 1 | 1-4 | Under the hood: tokens, raw APIs, tools, agent loop, sessions | agent-from-scratch runs on GLM 5.3 and Claude · 3 katas done · 20-turn session stays in budget | not started |
| 2 | 5-7 | Embeddings and RAG | 50-question eval set · vector vs hybrid+re-rank scores · live demo | not started |
| 3 | 8-9 | Evals and tracing | evals in CI · error analysis on 50 failures · one measured fix | not started |
| 4 | 10-14 | Frameworks, agents, MCP | MCP server works in a real client · 30 agent scenarios · injection tests | not started |
| 5 | 15-20 | Production, cloud, enterprise (FDE) | capstone on AWS via Terraform · permission tests · threat model · demo video | not started |
| 6 | 21-24 | Portfolio and applying | 4 case studies · 20 applications · 1 paid AI project | not started |

### Phase 0 checklist

- [ ] OpenRouter account, credit added, monthly limit set, key in `.env`
- [ ] Anthropic API key with a $5 limit, in `.env`
- [ ] Python 3.12+ via `uv`
- [ ] Docker running Postgres + pgvector
- [ ] A raw `curl` to OpenRouter returns a GLM 5.3 answer
- [ ] First commit pushed (CLAUDE.md, JOURNEY.md, README.md)

### Phase 1 modules

| # | Module | Kata | Status |
| --- | --- | --- | --- |
| 01 | Python idioms for a Node developer | | not started |
| 02 | Tokens and cost | | not started |
| 03 | Raw API calls and streaming (OpenRouter, then Anthropic) | | not started |
| 04 | Structured outputs | | not started |
| 05 | Tool calling by hand | tool_dispatch | not started |
| 06 | The agent loop | agent_loop | not started |
| 07 | One model interface (LLMClient) | | not started |
| 08 | Sessions and memory | context_trimmer | not started |

## Decisions

| Date | Decision | Why |
| --- | --- | --- |
| 2026-09-30 | Default model: GLM 5.3 via OpenRouter; no local models | Cheap, capable, supports tools; the same model can be used in real workflows later |
| 2026-09-30 | Claude Code writes the code; Andriy designs first, reviews every line, explains back | Speed of AI-assisted work, without losing understanding |
| 2026-09-30 | Three katas are hand-written: tool dispatch, agent loop, context trimmer | Core mental model; asked about in interviews |
| 2026-09-30 | Phase 1 is framework- and SDK-free | See the real mechanics before the abstractions |
| 2026-09-30 | Projects get their own repo once they have a demo and a public README | Keeps GitHub active and each project presentable |

## Graduated repos

| Project | Repo | Demo |
| --- | --- | --- |
| — | — | — |

## Open gaps and questions

Things Andriy could not explain back yet, or wants to revisit. Remove a line when it is resolved.

- (none yet)

## Log

<!-- Template — copy for each module, newest at the top:

### YYYY-MM-DD — Phase X, module NN: <name>
- **Built:** 
- **Learned:** 
- **Surprised me / broke:** 
- **Gaps:** 
- **Cost:** $ (input / output tokens)
-->

### 2026-09-30 — Phase 0: repo created
- **Built:** repo, CLAUDE.md, JOURNEY.md, README.md, .gitignore, .env.example
- **Learned:** —
- **Gaps:** —
- **Cost:** $0
