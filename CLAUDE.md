# SEO Audit

One command: `/audit yoursite.com`. It grades every page on five layers - on-page (80 checks), technical (Lighthouse per template), AI readiness (31 checks), doorway pages, local - reports in plain English, waits for your yes, then fixes what it can on a loop and re-crawls until the number stops moving. Every pass rewrites `audit-report.html` so you can watch the score climb.

## Run it

1. Open this folder in Claude Code.
2. `/audit yoursite.com`
3. When it asks: paste your sitemap URL, the four Search Console exports (2 min), and three pastes from your Business Profile (About, Services, Products).
4. Read the report. Say what to fix. Watch the loop.

Connect Semrush (free tier is enough) to unlock the crawl, keywords and the rivals. The audit runs without it and says what it could not measure.

## What it never does

- Rewrite your copy. Titles, metas, alt text, tags, schema, links, files: yes. Your sentences: never.
- Delete anything. Removals are recommendations that wait for your yes.
- Show a green number for work that did not ship. Queued, routed and hand-done items never count as fixed.

## Files

- `.claude/commands/audit.md` - the `/audit` command
- `references/` - the check lists it grades against and the report template
- `code/check_page_similarity.py` - the doorway-page similarity checker

Full blueprint, the fix + build + launch layer and the machines: skool.com/automatable-free
