# SEO & AI Visibility Report

**Prepared for:** Craig Peterson  
**Business:** The Joint Chiropractic — Franchise Owner  
**Market:** Southeast Valley, Arizona (Queen Creek, Power Ranch, San Tan Valley, Gilbert)  
**Prepared by:** Rob Hartwig  
**Scan date:** September 3, 2026  
**Portfolio score:** 83 / 100 (Good)

This report is the public client deliverable from SiteScan. It covers five websites Craig owns or operates: the custom franchise site and four The Joint Chiropractic location pages in the Southeast Valley.

---

## How to read this

Each site is scored 0–100 across five weighted categories:

| Category | Weight | What it measures |
| --- | --- | --- |
| SEO fundamentals | 28% | Titles, descriptions, headings, canonical, sitemap, breadcrumbs, freshness |
| AI visibility | 28% | Structured data, AI crawler access, llms.txt, crawlable content |
| Links & mentions | 18% | Internal/outbound links, anchor text, NAP, social citations |
| Technical health | 18% | HTTPS, speed, page weight, Core Web Vitals proxies, security headers |
| Social & sharing | 8% | Open Graph, Twitter cards, favicon |

**Inbound links cannot be counted from a page’s HTML.** Google’s index is the free source of truth. Each site section includes one-click `site:`, `-site:`, `cache:`, and `related:` searches so you can see indexation, inbound URL mentions, and off-site brand mentions without a paid backlink tool.

Ownership matters for a franchise:

- **Convenient Chiropractic** is Craig’s custom site. Fixes here can be made immediately.
- **The four thejoint.com location pages** are a corporate template. Local content and listings are still Craig’s to improve; template/schema/performance issues need a request to The Joint corporate web team.

---

## Executive summary

The portfolio averages **83**. The custom site is in clearly better shape than the corporate location pages. Every site is missing the single highest-impact local/AI fix: **Chiropractor / LocalBusiness schema** (name, address, phone, hours, geo, and `sameAs` links to Google Business Profile). Until that exists, ChatGPT, Gemini, and Google’s local pack have to guess who you are.

| Site | Score | Grade | Who can fix it |
| --- | ---: | --- | --- |
| [Convenient Chiropractic](https://convenient-chiropractic.com/) | 89 | Good | Craig (custom site) |
| [The Joint — Queen Creek](https://www.thejoint.com/arizona/queen-creek/queen-creek-48031) | 81 | Good | Mostly corporate template |
| [The Joint — Power Ranch](https://www.thejoint.com/arizona/queen-creek/power-ranch-48064) | 81 | Good | Mostly corporate template |
| [The Joint — San Tan Valley](https://www.thejoint.com/arizona/san-tan-valley/san-tan-valley-48057) | 81 | Good | Mostly corporate template |
| [The Joint — San Tan Village](https://www.thejoint.com/arizona/gilbert/san-tan-village-48035) | 81 | Good | Mostly corporate template |

### What to do first

1. **Add Chiropractor schema to convenient-chiropractic.com** — hours, NAP, geo, and `sameAs` for GBP, Facebook, Instagram, and Yelp. This is the #1 AI-visibility and local-pack fix, and Craig controls this site.
2. **Add an FAQ with FAQPage schema** on the custom site (pricing, walk-ins, membership, insurance, what to expect). AI assistants quote these answers.
3. **Add review/star markup you have the rights to use**, and keep Google Business Profile reviews current for each of the four clinics.
4. **Ask The Joint corporate** to add LocalBusiness schema, shorten titles (~60 characters), cut the 1–2 MB HTML payloads, lazy-load images, and replace “learn more / click here” anchors on location pages. Those four pages share one template, so one corporate fix repairs all four clinics.
5. **Run the Google searches below** for inbound mentions and unlinked citations (Yelp, Healthgrades, local news, chambers). Turning unlinked mentions into links is the inbound-link work a franchisee can do without touching corporate HTML.

---

## Portfolio scorecard

| Category | Convenient Chiropractic | Queen Creek | Power Ranch | San Tan Valley | San Tan Village |
| --- | ---: | ---: | ---: | ---: | ---: |
| **Overall** | 89 | 81 | 81 | 81 | 81 |
| SEO fundamentals | 98 | 89 | 89 | 89 | 89 |
| AI visibility | 74 | 76 | 76 | 76 | 76 |
| Links & mentions | 92 | 77 | 77 | 77 | 77 |
| Social & sharing | 100 | 80 | 80 | 80 | 80 |
| Technical health | 89 | 80 | 80 | 80 | 80 |

---

## Convenient Chiropractic — 89 (Good)

**URL:** https://convenient-chiropractic.com/  
**Page title:** Chiropractor in the Southeast Valley AZ | Walk-In Care | $29  
**HTTP:** 200 in 1624 ms  
**Control:** Craig’s custom site — changes can ship now

| Category | Score |
| --- | ---: |
| SEO fundamentals | 98 |
| AI visibility | 74 |
| Links & mentions | 92 |
| Social & sharing | 100 |
| Technical health | 89 |

### Findings

#### SEO fundamentals

| | Check | Result | Next step |
| --- | --- | --- | --- |
| ✅ | Page title | “Chiropractor in the Southeast Valley AZ \| Walk-In Care \| $29” (60 chars). | — |
| ✅ | Meta description | 161 chars — good length. | — |
| ✅ | H1 heading | “Affordable Chiropractor in the Southeast Valley, AZ Walk-In Care Available” | — |
| ✅ | Heading structure | 7 H2 headings organizing the content. | — |
| ✅ | Canonical URL | https://convenient-chiropractic.com/ | — |
| ✅ | Indexability | Meta robots: “index, follow, max-image-preview:large, max-snippet:-1, max-video-preview:-1”. | — |
| ⚠️ | Image alt text | 9 of 19 images missing alt text. | Add descriptive alt text to every meaningful image — it feeds image search and accessibility. |
| ✅ | Language declaration | <html lang="en-US"> | — |
| ✅ | robots.txt | Found at https://convenient-chiropractic.com/robots.txt. | — |
| ✅ | XML sitemap | Found: https://convenient-chiropractic.com/sitemap.xml. | — |
| ℹ️ | hreflang alternates | No hreflang tags — fine for a single-language US site. | — |
| ✅ | Breadcrumb trail | Breadcrumbs present (schema and/or visible nav). | — |
| ✅ | Content freshness signal | Last-modified / time markup: 2026-08-25T18:42:55+00:00. | — |
| ℹ️ | Geo / locality meta | No geo meta tags. LocalBusiness schema (checked under AI visibility) is the preferred replacement. | — |

#### AI visibility

| | Check | Result | Next step |
| --- | --- | --- | --- |
| ✅ | Structured data (JSON-LD) | 1 block — types: WebPage, MedicalWebPage, ImageObject, BreadcrumbList, WebSite. | — |
| ❌ | LocalBusiness / Chiropractor schema | No LocalBusiness, Chiropractor, or Organization schema. | Add Chiropractor schema (schema.org/Chiropractor) with NAP data, hours, geo, and sameAs links to your Google Business Profile and social accounts. |
| ⚠️ | FAQ schema | No FAQPage schema. | Add an FAQ section with FAQPage schema answering common questions (pricing, walk-ins, insurance, what to expect). AI assistants lift these answers verbatim. |
| ⚠️ | Review / AggregateRating schema | No Review or AggregateRating schema. | Add AggregateRating (and individual reviews you own the rights to) so Google can show stars and AI answers can cite social proof. |
| ℹ️ | Speakable schema | No Speakable schema — optional, but it flags the sentences you want voice assistants to read aloud. | — |
| ✅ | AI crawler access | robots.txt allows all 7 major AI crawlers (GPTBot, ClaudeBot, PerplexityBot, …). | — |
| ✅ | llms.txt | Found at https://convenient-chiropractic.com/llms.txt. | — |
| ✅ | Server-rendered content | ~1906 words available without JavaScript. | — |
| ✅ | Semantic HTML | Uses article, nav, header, footer. | — |

#### Links & mentions

| | Check | Result | Next step |
| --- | --- | --- | --- |
| ✅ | Internal links | 25 internal links — crawlers can move around the site. | — |
| ✅ | Outbound links | 10 outbound links to 2 hosts (thejoint.co, maps.app.goo.gl). | — |
| ✅ | Outbound follow vs nofollow | 10 follow / 0 nofollow (100% pass equity). | — |
| ✅ | Anchor text quality | No generic “click here / learn more” anchors detected. | — |
| ⚠️ | Href quality | 4 empty, “#”, or javascript: hrefs. | Crawlers and assistive tech cannot follow those. Point them at real URLs. |
| ⚠️ | target=_blank safety | 13 target=_blank links missing rel="noopener". | Add rel="noopener noreferrer" so the destination page cannot access window.opener. |
| ✅ | Social / citation profile links | Found 5: maps.app.goo.gl. | — |
| ✅ | Clickable NAP (phone / email) | 3 tel: and 0 mailto: links. | — |
| ℹ️ | Inbound links (off-site) | Inbound links cannot be counted from this page alone — Google’s index is the free source of truth. Use the research searches below (especially “Inbound mentions of this URL” and “Brand mentions off-site”). | Run those Google queries, then chase unlinked mentions (directories, sponsors, local news) and ask them to link. |

#### Social & sharing

| | Check | Result | Next step |
| --- | --- | --- | --- |
| ✅ | Open Graph tags | og:title, og:description, and og:image all present. | — |
| ✅ | og:type and og:url | og:type=website; og:url present. | — |
| ✅ | Twitter/X card | twitter:card = “summary_large_image”. | — |
| ✅ | Favicon | Favicon link tag present. | — |

#### Technical health

| | Check | Result | Next step |
| --- | --- | --- | --- |
| ✅ | HTTPS | Site serves over HTTPS. | — |
| ✅ | HTTP status | 200 OK. | — |
| ⚠️ | Server response time | 1624 ms — noticeably slow. | Aim for under ~800 ms. Enable caching/CDN or upgrade hosting. |
| ✅ | HTML size | 193 KB of HTML. | — |
| ✅ | Mobile viewport | “width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=0”. | — |
| ✅ | Mixed content | No insecure http:// resources referenced. | — |
| ⚠️ | HSTS | No Strict-Transport-Security header. | Send HSTS so browsers always use HTTPS — a small ranking and trust signal. |
| ⚠️ | X-Content-Type-Options | Missing X-Content-Type-Options: nosniff. | Add the header to block MIME sniffing. |
| ✅ | Response compression | Content-Encoding: gzip. | — |
| ✅ | Cache-Control | max-age=7200 | — |
| ✅ | X-Robots-Tag | No blocking X-Robots-Tag header. | — |
| ✅ | Image lazy-loading | 13 of 19 images use loading="lazy". | — |
| ℹ️ | Image width/height (CLS) | 4 of 19 images missing width or height. | Set width and height (or aspect-ratio) so the page does not jump as images load. |
| ✅ | Modern image formats | 3 WebP/AVIF references. | — |
| ⚠️ | Render-blocking scripts | 2 render-blocking scripts in <head>. | Add defer/async (or type=module) so first paint is not held up — a Core Web Vitals item. |
| ✅ | Preconnect / DNS-prefetch | 1 early-connection hint. | — |

### Google research (indexation, inbound mentions, citations)

Open these in a logged-in browser. Result counts and the pages listed are what Google currently shows — that is the inbound / mention audit.

| Question | Query | Search |
| --- | --- | --- |
| Pages Google has indexed | `site:convenient-chiropractic.com` | [Open in Google](https://www.google.com/search?q=site%3Aconvenient-chiropractic.com) |
| Inbound mentions of this URL | `"https://convenient-chiropractic.com/" -site:convenient-chiropractic.com` | [Open in Google](https://www.google.com/search?q=%22https%3A%2F%2Fconvenient-chiropractic.com%2F%22%20-site%3Aconvenient-chiropractic.com) |
| Brand mentions off-site | `"Convenient Chiropractic" -site:convenient-chiropractic.com` | [Open in Google](https://www.google.com/search?q=%22Convenient%20Chiropractic%22%20-site%3Aconvenient-chiropractic.com) |
| Cached / last crawled copy | `cache:https://convenient-chiropractic.com/` | [Open in Google](https://www.google.com/search?q=cache%3Ahttps%3A%2F%2Fconvenient-chiropractic.com%2F) |
| Related sites Google associates | `related:convenient-chiropractic.com` | [Open in Google](https://www.google.com/search?q=related%3Aconvenient-chiropractic.com) |
| News and PR mentions | `"Convenient Chiropractic"` | [Open in Google](https://www.google.com/search?tbm=nws&q=%22Convenient%20Chiropractic%22) |

---
