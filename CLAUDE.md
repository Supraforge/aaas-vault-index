# CLAUDE.md — aaas-vault-index

> First-read pointer for AI agents working in this repo.
## AaaS-wide context (canonical knowledge surface)

When working in this repo on anything that touches the broader AaaS context —
funnel, history, killshots, strategy, ICP, pricing rationale, what's shipped,
killed, or shelved — **the megadoc is the canonical source**:

- Master + part dirs: `AaaS-Love/aaas.com:docs/ecosystem-megadoc-2026-05-24/`
- Live research queue: `AaaS-Love/aaas.com:docs/ecosystem-megadoc-2026-05-24/RESEARCH-QUEUE.md`
- Queryable via AaaS Internals NotebookLM (synced every 15 min from `aaas.com:main`)
- One-liner: `python3 ~/.claude/scripts/notebooklm/route_query.py "<question>"` returns the right notebook URL
- Full runbook: `AaaS-Love/aaas.com:docs/operations/notebooklm-docs-sync.md`

**Don't re-derive what the megadoc already says.** If you find a gap, edit a megadoc
`.md` in aaas.com instead of working around it locally.
