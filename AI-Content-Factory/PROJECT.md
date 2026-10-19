# AI Content Factory

## Project Name
AI Content Factory

## Goal
Membangun Agentic AI Workflow yang membantu Content Creator mengubah hasil riset dan tren dari internet menjadi konten media sosial yang siap dipublikasikan.

## Use Case
Membuat konten Instagram Reels bertema tips dan insight karier untuk fresh graduate di Indonesia.

## Workflow
1. **Research Agent**: Mencari dan mengumpulkan informasi dari web.
2. **Strategy Agent**: Membaca hasil research dan mengubahnya menjadi content strategy.
3. **Execution Agent**: Membaca research dan strategy lalu menghasilkan video script dan Instagram caption.

## Handoff
- **Research Agent** → `research/research-result.md`
- **Strategy Agent** membaca `research-result.md` → `strategy/content-strategy.md`
- **Execution Agent** membaca `research-result.md` dan `content-strategy.md` → output final.

## Tools
- Web Search / Browser
- Local File System
- Antigravity Agent
- Google Workspace jika diperlukan

## Rules
- Jangan membuat data atau statistik tanpa sumber.
- Research Agent harus mencantumkan sumber.
- Strategy Agent harus menggunakan hasil Research Agent.
- Execution Agent harus menggunakan hasil Strategy Agent.
- Jangan melewati tahapan workflow.
- Gunakan bahasa Indonesia yang natural.
- Jangan mengarang informasi.
- Semua output harus tersimpan di workspace.

## Success Criteria
- Minimal dua ecosystem/tool digunakan.
- Terdapat minimal dua tahap handoff.
- Research menghasilkan data yang dapat digunakan.
- Strategy menghasilkan keputusan content.
- Execution menghasilkan script dan caption.
- Semua proses dapat dibuktikan melalui screenshot.
