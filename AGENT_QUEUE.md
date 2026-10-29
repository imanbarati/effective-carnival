# AGENT QUEUE — Iman Manati projects

**For any AI agent:** This is the cross-project priority list. Open the specific repo HANDOFF.md before doing work. Do not start a project without reading its handoff.

**Owner:** imanbarati (Iman Manati)  
**Updated:** 2026-10-29

---

## Priority order

### 1. TanCMS (highest product priority)
- **Repo:** https://github.com/imanbarati/tancms (private)
- **Handoff:** `HANDOFF.md` + `CONTINUE.md` in that repo
- **Next:** Set DATABASE_URL + JWT_SECRET → contract:emit → db:init → db:seed → deploy (Prisma Compute). Then clean legacy Prisma 6 files, admin auth gate, Pages CRUD.
- **Paste prompt:** use the CONTINUE prompt at the top of tancms/HANDOFF.md

### 2. E2EGram
- **Repo:** https://github.com/imanbarati/E2EGram
- **Handoff:** `HANDOFF.md`
- **Next:** Add Actions secrets APP_ID + APP_HASH → build debug APK → test E2E-only mode
- **Paste prompt:** see E2EGram/HANDOFF.md “Quick continue prompt”

### 3. Effective Carnival (this repo — book)
- **Repo:** https://github.com/imanbarati/effective-carnival
- **Handoff:** `HANDOFF.md`
- **Next:** Fact-check all numbers → write Ch 6 & Ch 7 (or Ch 3) → Ch 9 / Part IV
- **Paste prompt:** see HANDOFF.md “Quick continue prompt”

### 4. ideal-waddle (xAI marketplace archive)
- **Repo:** https://github.com/imanbarati/ideal-waddle
- **Handoff:** `HANDOFF.md`
- **Next:** robots/terms review → small test crawl → full crawl + coverage report

### 5. steamdeck-qwen-coding-agent
- **Repo:** https://github.com/imanbarati/steamdeck-qwen-coding-agent
- **Handoff:** `HANDOFF.md`
- **Next:** Verify model URL / llama.cpp / OpenCode schema → diagnostics → layered tests (label untested hardware)

### 6. ubiquitous-rotary-phone (Persian Engram / Souls)
- **Repo:** https://github.com/imanbarati/ubiquitous-rotary-phone
- **Handoff:** `HANDOFF.md` (Persian + English context)
- **Next:** Q&A on public sources, guided interview, real content import (data folders still mostly empty)

---

## Global agent rules

1. Read the project’s HANDOFF.md before any code or prose changes.
2. Prefer GitHub Actions / cloud automation over heavy local setup when the handoff says so.
3. Never commit secrets (DATABASE_URL, JWT_SECRET, APP_ID, APP_HASH, tokens).
4. After meaningful work, update that project’s HANDOFF Done/Left sections.
5. Do not re-scaffold a project that already has structure and a handoff.

---

## How to hand off to Claude / another agent

1. Open the target repo.
2. Paste the **Quick continue prompt** from that repo’s HANDOFF.md as the first message.
3. Optionally also paste or link this AGENT_QUEUE.md so the agent knows relative priority.

---

*End of queue.*
