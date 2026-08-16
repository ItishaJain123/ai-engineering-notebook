# Learning Log — AI Engineering with Claude Code

> Maintained by your AI tutor. Updated at the end of every session so we always
> pick up exactly where we left off.

**Student:** itu.yash3003@gmail.com
**Started:** 2026-08-14
**Notebook:** `index.html` (open by double-clicking, or live at
https://itishajain123.github.io/ai-engineering-notebook/)

---

## Learner profile
- JS only (no Python)
- Prefers basics-first, then advancing
- Structured curriculum (not one big project)
- Wants full terminology coverage and nicely formatted/syntax-highlighted code in every chapter

---

## Progress tracker

Legend: ⬜ not started · 🟡 in progress · ✅ covered & explained back

### Part 0 — GenAI Foundations
- 🟡 0a. How LLMs Actually Work — tokens, embeddings, attention (`chapters/ch00a-...html`)
- 🟡 0b. Training Lifecycle — pretraining, SFT, RLHF (`chapters/ch00b-...html`)
- 🟡 0c. Sampling & Generation Parameters — temperature, top-p/top-k (`chapters/ch00c-...html`)
- 🟡 0d. Beyond Text — diffusion models, multimodal vs. generation (`chapters/ch00d-...html`)
- 🟡 0e. Glossary of Terms — searchable reference, all 31 chapters (`chapters/ch00e-glossary.html`)

### Part 1 — Claude Code & Anthropic Platform
- 🟡 1. Claude Code fundamentals — notes written (`chapters/ch01-...html`); awaiting exercise
- 🟡 2. Context management — notes written (`chapters/ch02-...html`)
- 🟡 3. Skills vs. Plugins — notes written (`chapters/ch03-...html`)
- 🟡 4. MCP (Model Context Protocol) — notes written (`chapters/ch04-mcp.html`)
- 🟡 5. Subagents / Agent (Task) tool — notes written (`chapters/ch05-...html`)
- 🟡 6. Claude Agent SDK — notes written (`chapters/ch06-...html`)
- 🟡 7. Computer use / browser automation — notes written (`chapters/ch07-...html`)

### Part 2 — Core LLM Engineering
- 🟡 8. Prompt engineering — notes written (`chapters/ch08-...html`)
- 🟡 9. Structured output — notes written (`chapters/ch09-...html`)
- 🟡 10. Prompt caching — notes written (`chapters/ch10-...html`)
- 🟡 11. Tool use / function calling — notes written (`chapters/ch11-...html`)
- 🟡 12. Extended thinking / reasoning — notes written (`chapters/ch12-...html`)
- 🟡 13. Streaming — notes written (`chapters/ch13-...html`)
- 🟡 14. Agent loop engineering — notes written (`chapters/ch14-...html`)
- 🟡 15. Cost & latency optimization — notes written (`chapters/ch15-...html`)

### Part 3 — RAG & Retrieval
- ⬜ 16. Embeddings deep-dive
- ⬜ 17. Chunking strategies
- ⬜ 18. Vector stores
- ⬜ 19. Retrieval strategies
- ⬜ 20. Advanced RAG
- ⬜ 21. RAG vs. fine-tuning vs. prompting

### Part 4 — Orchestration Frameworks
- ⬜ 22. LangChain
- ⬜ 23. LangGraph
- ⬜ 24. Multi-agent systems

### Part 5 — Safety, Evaluation & Production
- ⬜ 25. Guardrails
- ⬜ 26. Prompt injection defense
- ⬜ 27. PII redaction & data governance
- ⬜ 28. Evals
- ⬜ 29. Observability & tracing
- ⬜ 30. Red-teaming / adversarial testing
- ⬜ 31. Deployment patterns

---

## Session log

### Session 1 — 2026-08-14
- Built `index.html` scaffold (all 31 chapters stubbed, nav, progress bar,
  dark mode, search, localStorage completion tracking).
- Created this learning log.
- Learner profile: JS only (no Python), basics-first, structured curriculum, start Ch.1.
- Restructured to **one HTML file per chapter** under `chapters/`; index became a hub launcher.
- **Wrote up all of Part 1 (Ch.1–7)** with full notes: explanation, analogy, JS code,
  key takeaways, exercises, understanding checks. Files: `chapters/ch01…ch07`.

### Session 2 — 2026-08-16
- Learner flagged that "actual GenAI concepts" weren't covered — added
  **Part 0 — GenAI Foundations** (Ch.0a–0d): tokens/embeddings/attention,
  pretrain→SFT→RLHF, temperature/top-p/top-k sampling, diffusion/multimodal basics.
- Added **Chapter 0e: Glossary of Terms** — searchable reference covering
  terminology from all 31 chapters, including ones not yet written (RAG/orchestration/
  safety terms), each linked to its home chapter.
- Added automatic syntax highlighting (keywords/strings/comments/numbers/function
  names) to every code block across all chapters via a shared regex-based highlighter.
- Pushed the whole notebook to GitHub: https://github.com/ItishaJain123/ai-engineering-notebook
  — enabled GitHub Pages, fixed a 404 by renaming the hub file to `index.html`
  (GitHub Pages requires that filename at the repo root) and updating all
  chapter back-links accordingly. `.claude/` is gitignored, never pushed.
- **Wrote up all of Part 2 (Ch.8–15)**: prompt engineering, structured output,
  prompt caching, tool use, extended thinking, streaming, agent loop engineering,
  cost & latency optimization — same format (analogy, diagrams, real Claude API
  code, key takeaways, exercise, understanding check) as Parts 0–1.
- Next: learner does exercises across Parts 0–2 so we can review and mark
  chapters ✅, then move to Part 3 (Ch.16 Embeddings Deep-Dive) — or continue
  writing ahead into Part 3 if the learner prefers content-first, exercises-later.

---

## Open questions / things to revisit
- Whether to pause for hands-on exercises now, or keep writing chapters through
  Part 3–5 before the learner does any exercises.

## Next steps
- Await learner's choice: do exercises now, or continue to Part 3 (RAG & Retrieval).
