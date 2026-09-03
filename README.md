# SiteScan — SEO & AI Visibility Scanner

A dashboard for scanning client websites and grading how well they are set up
for search engines and AI assistants (ChatGPT, Claude, Perplexity, Gemini).
Built for agency-style client reporting. The first configured client is Craig
Peterson, franchise owner of The Joint Chiropractic (Queen Creek, Power Ranch,
San Tan Valley, and San Tan Village / Gilbert, AZ), plus his custom franchise
site at convenient-chiropractic.com.

## What it checks

Each scan fetches the live page (plus `robots.txt`, `sitemap.xml`, and
`llms.txt`) and grades five categories:

- **SEO fundamentals** — title and meta description, H1/headings, canonical,
  indexability, image alt text, language, robots.txt, XML sitemap, hreflang,
  breadcrumbs, content-freshness markup, geo meta.
- **AI visibility** — JSON-LD (LocalBusiness / Chiropractor), FAQ and review
  schema, speakable, AI crawler access (GPTBot, ClaudeBot, PerplexityBot,
  Google-Extended, …), llms.txt, server-rendered content depth, semantic HTML.
- **Links & mentions** — internal links, outbound follow/nofollow, anchor-text
  quality, empty/javascript hrefs, `target=_blank` safety, social/citation
  profile links, clickable NAP. Inbound links are researched via Google, not
  guessed from HTML.
- **Social & sharing** — Open Graph (including type/url), Twitter/X card,
  favicon.
- **Technical health** — HTTPS, status, TTFB, HTML weight, viewport, mixed
  content, HSTS, nosniff, compression, cache headers, X-Robots-Tag, lazy
  loading, image dimensions (CLS), WebP/AVIF, render-blocking scripts,
  preconnect.

Overall score weights: SEO 28%, AI 28%, links 18%, technical 18%, social 8%.

## Google research shortcuts

Google does not allow automated scraping of search results, and inbound links
cannot be counted from a page’s own HTML. After each scan the report includes
ready-to-click searches:

| Query | What it answers |
| --- | --- |
| `site:domain.com` | How many pages Google has indexed |
| `site:domain.com/path` | Whether this exact URL is indexed |
| `"https://…" -site:domain.com` | Off-site pages that mention this URL (inbound) |
| `"Brand" -site:domain.com` | Unlinked brand mentions |
| `cache:url` | Google’s last stored snapshot |
| `related:domain.com` | Sites Google treats as peers |
| Brand + city + (yelp OR maps OR facebook) | Local citations |
| News tab for the brand | Recent PR / E-E-A-T coverage |

## Running locally

```bash
npm install
npm run dev
```

Then open http://localhost:3000 (or pass `-p <port>`). Scans run through
`/api/scan`, so the server needs outbound internet access.

## Sharing a client report

The public deliverable for Craig Peterson is:

- **Markdown (best for GitHub):** [reports/craig-peterson.md](https://github.com/robbyrobaz/sitescan/blob/main/reports/craig-peterson.md)
- **Formatted web page:** `/reports/craig-peterson` when the app is running or deployed

Send Craig this link:

https://github.com/robbyrobaz/sitescan/blob/main/reports/craig-peterson.md

That file is a snapshot of live scans (scores, findings, recommendations, and Google `site:` research links). It does not require anyone to run the scanner.

## Adding clients or sites

Client sites live in `src/lib/clients.ts`. Any extra URL can be added from
the “Scan another site” form on the dashboard.

## Stack

- [Next.js](https://nextjs.org) (App Router, TypeScript)
- [Tailwind CSS](https://tailwindcss.com) + [shadcn/ui](https://ui.shadcn.com)
- [cheerio](https://cheerio.js.org) for server-side HTML analysis
