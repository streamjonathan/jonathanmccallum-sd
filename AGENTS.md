# AGENTS.md — jonathanmccallum-sd (Sindhi mirror of jonathanmccallum.com)

Sindhi mirror site. Same theme and design as the main site (Paper Light),
content translated into Sindhi, meaning-first. Repo: streamjonathan/jonathanmccallum-sd.
Live (when approved): sd.jonathanmccallum.com. Proof: jonathanmccallum-sd.pages.dev.

## Mission

Mirror jonathanmccallum.com in Sindhi — every article translated for meaning,
not word for word, in Jonathan's voice: plain short sentences, friendly, positive,
never preachy. An average person interested in Jesus, not an expert or theologian.

## Roles

- **Bobby (Muse) is the lead builder.** He coordinates, builds, pushes to GitHub
  and deploys to Cloudflare. He is the ONLY one who pushes or deploys.
- **Claude advises and reviews** translation quality. He does not push or deploy.
- **Helper Muses translate** one article at a time, drafts only.

## The one rule above all

**Never publish or alter live production assets without Jonathan's clear
permission.** The Sindhi site goes live on sd.jonathanmccallum.com only when
he says so, after reading the pilot article(s). Drafts stay drafts until he
approves them. Work on a branch, never straight on main. Give Bobby a preview URL.

## Translation rules

- English repo (streamjonathan.github.io) is the source of truth. Articles are
  translated from the English Markdown, keeping the same date, slug, source_video
  and shareImage. Only the title and body are translated.
- Lewis quotations: use the published Sindhi translation where one exists
  (cite it); otherwise translate fresh and mark it "translated for this site".
- Bible verses: use the 19th-century Sindhi Bible (public domain by age) — verify text from a scan before quoting wording, never
  re-translate from the English article.
- Names (never vary): يسوع, خدا, اصلان, نارنيا, ڊگوري, ليوس. Book titles use the standard published Sindhi titles.
- Voice: Plain everyday register, short sentences, warm and direct.
- No emojis, no newsletter form, no links the English article does not have.
- Never invent facts, dates, links or details.

## Site facts

- Eleventy 3, Cloudflare Pages, Paper Light theme (Fraunces + Newsreader).
- No Ask chat and no note Worker on this site yet — search (Pagefind) works,
  Ask and notes come later. The Ask floating button and ask.js are removed.
- CSS is preloaded, not inlined (CSP blocks inline style). Bump the `?v=` query
  on any CSS/JS file you change.
