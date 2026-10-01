# Funngro Website SEO Audit — 1 October 2026

## Scope
Reviewed the current public Funngro homepage, Teen page, For Brands page, About, Contact, FAQ, Privacy Policy and Terms pages.

## What is already working
1. The site has dedicated intent pages such as `/teen` and `/for-brands`, which gives search engines clearer topical targets.
2. The Teen page uses descriptive headings around online earning, part-time work, brand campaigns and FAQs.
3. The current site publishes an FAQ page with a large set of user-intent questions.
4. The current Contact page exposes dedicated support and partnership email addresses.
5. The site contains substantial text content rather than relying only on graphics.

## Priority improvements

### P0 — Search intent and information architecture
- Keep separate landing pages for **Teens** and **Companies/Brands**.
- Give each page one clear primary intent and one primary CTA.
- Avoid stuffing repeated variants of “earn money online” into every section. Use natural topic clusters and supporting pages.

### P0 — Metadata
Every indexable page should have:
- Unique `<title>` around 50–60 characters where practical.
- Unique meta description around 140–160 characters where practical.
- Canonical URL.
- Open Graph title/description/image.
- Descriptive image `alt` text.
- One clear H1.

### P0 — Structured data
Use only schema types that genuinely describe the page. Recommended:
- `Organization` on the company/about layer.
- `WebSite` on the root.
- `FAQPage` only where the visible page actually contains the FAQ content.
- `BreadcrumbList` on deeper pages.

### P1 — Internal linking
Create a simple crawl path:
Home → Teen → How it works → FAQ
Home → For Companies → Campaign formats → Contact
About/Trust → Privacy → Terms

Use descriptive anchor text instead of generic “click here”.

### P1 — Content quality
The current pages contain many strong commercial claims. Claims such as user counts, brand counts, earnings and campaign performance should always be:
- dated,
- clearly attributed to Funngro,
- supported by an underlying source where possible,
- and not presented as a guaranteed result for an individual user.

### P1 — Performance / Core Web Vitals
Before production:
- Serve responsive WebP/AVIF images.
- Lazy-load below-the-fold images.
- Avoid oversized hero media.
- Minify CSS/JS.
- Preload only genuinely critical fonts.
- Keep third-party scripts to a minimum.

### P2 — Trust and safety
Because the platform serves young people, trust content should be easy to find:
- eligibility,
- parent/minor safeguards,
- privacy,
- support,
- reporting/safety,
- payout terms,
- and clear explanations of what a project requires.

### P2 — Conversion
The B2B page should show:
- target audience,
- campaign formats,
- process,
- evidence,
- FAQs,
- and a short lead form.
The Teen page should show:
- what a project looks like,
- how selection works,
- what happens after submission,
- payout expectations,
- and safety/support information.

## Current-site facts used for the redesign
Funngro's current public site describes 70 lakh+ young Indians and 5,000+ brands, and its current For Brands page describes a 14–25 audience. These are company-reported figures and should be presented as such. The current Contact page lists `hello@funngro.com` for brands/partnerships and `teenlancer@funngro.com` for support.

## Prototype changes
This submission contains two original static prototype pages:
- `teen.html` — Teen experience
- `companies.html` — Company/brand experience

Both include:
- semantic headings,
- unique titles/descriptions,
- canonical tags,
- Open Graph basics,
- JSON-LD WebPage schema,
- responsive CSS,
- accessible button/link structure,
- clear CTAs,
- mobile layout.

## Important submission note
This is a **prototype**, not a production deployment. The form currently uses a mailto action and should be connected to Funngro's actual lead system before production.

### Sources
- https://www.funngro.com/
- https://www.funngro.com/teen
- https://www.funngro.com/for-brands
- https://www.funngro.com/about
- https://www.funngro.com/contact
- https://www.funngro.com/faq
- https://www.funngro.com/privacy-policy
- https://www.funngro.com/terms-and-conditions
