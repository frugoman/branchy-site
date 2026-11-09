# Branchy site SEO

## Audit score (`seo-audit.mjs`)
- Baseline 2026-11-09 (live): **9/21**
- After (local server of this branch): **18/21**. Remaining fails are N/A for a macOS-only, English-only site: hreflang, apple-itunes-app, App Store link.

## Done
canonical, twitter:card, og:type/url, JSON-LD SoftwareApplication (macOS, free, DMG download), robots.txt + sitemap.xml, 404.html, `/guides/` with two guides (Article + FAQPage JSON-LD), Guides link in nav and footer.

## Keyword research (WebSearch 2026-11-09, no volume data; honest read)
Head terms ("best git GUI Mac", "git client mac") are dominated by Tower/Fork/GitKraken roundups and aren't winnable. Branchy's real edge is worktrees + PR inbox. Candidates, ranked:
1. **git worktree: work on multiple branches without stashing** — published (`/guides/git-worktree-multiple-branches/`). Steady how-to demand, competition is DataCamp/dev.to-level, a good guide can compete.
2. **git worktrees for parallel AI coding agents (Claude Code etc.)** — published (`/guides/git-worktree-ai-coding-agents/`). Hot, new, many shallow posts; gotchas angle is differentiated.
3. git worktree vs git clone vs git stash (comparison)
4. "fatal: is already used by worktree" fix (error-message query, great long-tail)
5. git worktree node_modules / .env / copy ignored files
6. How to review a pull request locally without losing your work
7. Resolve "this branch has conflicts" on a PR locally (links to Fix conflicts)
8. Stage individual lines/hunks (`git add -p` vs GUI)
9. Generate commit messages with AI (Ollama local option)
10. Git GUI for Mac with worktree support (comparison; needs fact-checking of rivals)

Not verified: search volumes. Check Search Console after indexing and pick the next guide from `gsc-report.mjs opps`.

## Open items / to verify
- Guide claims about Claude Code storing worktrees in `.claude/worktrees/` come from direct observation; other agent-specific flags deliberately omitted.
- Guides have no app screenshots yet; add real Branchy worktree sidebar screenshot.
- og:image is the 512px icon; a 1200x630 social card would be better.
- "frugoman.github.io/branchy-site" in the app README is stale (site is branchy.frusoft.dev).
