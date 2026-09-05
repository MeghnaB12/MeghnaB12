# Week 10 Micro-Polish Checklist

Small recruiter-facing cleanup items intentionally deferred until the final GitHub pass.

## Profile metadata
- [ ] Re-check GitHub profile bio for concise Full-Stack AI positioning.
- [ ] Re-check company/education/location/website fields for consistency with resume and LinkedIn.
- [ ] Confirm LinkedIn and portfolio links still work.
- [ ] Re-check every numeric claim in the profile README against the final repos (for example, `ragval` was originally described as having 32 tests but currently has 72 Python tests in CI; use the final Week 10 count rather than a stale number).

## Pinned repositories
- [ ] Re-evaluate final six pins after Weeks 2–9.
- [ ] Reorder pins based on strongest final evidence for Full-Stack AI / Applied AI Engineer roles.
- [ ] Make sure each pinned repository description highlights architecture and engineering value, not just the AI use case.

## Repository descriptions
- [ ] `ragval`: surface React + FastAPI + statistical RAG evaluation + tests/CI.
- [ ] `Agentic-Math-Solver`: surface React + FastAPI + LangGraph + Qdrant + Docker.
- [ ] `unified-broker`: surface WebSockets, broker integration, reconnect/reliability, normalization, and AI portfolio tooling.
- [ ] `physics-research-agent`: remove/avoid absolute accuracy or hallucination claims; emphasize equation-aware RAG + SymPy tool use.
- [ ] `NewsPostGen`: mention deployed FastAPI API and live demo.
- [ ] `agentic-financial-analyst`: mention router-based RAG, live web verification, observability/evaluation.

## GitHub Topics
- [ ] Add/review recruiter-relevant topics on the final six pins.
- [ ] Prefer specific topics such as `fastapi`, `react`, `typescript`, `langgraph`, `rag`, `llm-evaluation`, `postgresql`, `docker`, `gcp`, `websockets`, `ai-agents` where genuinely supported.
- [ ] Remove noisy or misleading topics.

## Visual consistency
- [ ] Ensure top repos have a screenshot/GIF or architecture diagram near the top of README.
- [ ] Standardize README section order across flagship repos.
- [ ] Confirm badges are useful and not decorative clutter.
- [ ] Check dark/light mode readability of diagrams and screenshots.

## Hygiene
- [ ] Remove `.DS_Store`, temporary outputs, debug files, stale logs, accidentally committed generated artifacts, and unused notebooks from highlighted repos where safe.
- [ ] Confirm `.gitignore` files cover OS/editor/env files.
- [ ] Confirm no secrets or credentials are committed.
- [ ] Archive trivial/abandoned public repos that dilute the engineering story if they no longer serve a purpose.

## Final recruiter test
- [ ] A recruiter can identify “Full-Stack AI Engineer” within 5–10 seconds.
- [ ] The first three pins collectively prove frontend, backend, AI, data, testing, deployment, and system reliability.
- [ ] At least one flagship project is live and usable.
- [ ] At least one repo demonstrates serious testing/evaluation.
- [ ] At least one repo demonstrates real full-stack architecture.
- [ ] At least one repo demonstrates realtime/integration/system-design work.
