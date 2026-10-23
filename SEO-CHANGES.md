# SEO update: location targeting (Hapur, Uttar Pradesh, "agency in UP", "creative marketing agency")

Only the hidden search-engine information changed. Nothing visible on the pages changed: screenshots of the home and
privacy pages are pixel-identical to before, at desktop and phone width.

## What changed (home page unless noted)

| Item | Before | After |
|---|---|---|
| Page title | Formera \| Creative Agency in Hapur: Motion Graphics & Video | **Formera \| Creative Marketing Agency in Hapur, Uttar Pradesh** |
| Description (also used for Facebook / X / WhatsApp previews and the structured data) | …agency in Hapur, Uttar Pradesh. …brands in Western UP and across India. | **Creative marketing agency in Hapur, Uttar Pradesh (UP). Motion graphics, video editing, graphic design and video shoots for brands across UP and India.** |
| Keywords | 14 phrases | 27 phrases: "agency in UP", "creative agency in UP", "creative marketing agency in UP / Hapur", "marketing agency in Uttar Pradesh / Hapur", "video editing / graphic design / motion graphics agency in Hapur / UP", "advertising agency Hapur", "branding agency Uttar Pradesh" (all earlier phrases kept) |
| Location tags | none | `geo.region` IN-UP, `geo.placename` Hapur, Uttar Pradesh, `geo.country` IN |
| Language / region | `lang="en"` | `lang="en-IN"` plus `hreflang` en-IN and x-default links (home and privacy pages) |
| Structured data, areas served | Hapur, Western UP, Uttar Pradesh, India | Hapur, **Ghaziabad, Meerut, Noida, Bulandshahr, Moradabad**, Western UP, Uttar Pradesh, India |
| Structured data, topics | 9 topics | + Creative Marketing, Branding Strategy, Marketing Strategy |
| `sitemap.xml` | no dates | `lastmod` 2026-10-15 for both pages |

The five extra cities are my choice of the nearest big Western UP markets. Remove or add cities in the `areaServed`
list (search for `Ghaziabad` in `index.html`) if that doesn't match where you really work.

## Before you deploy: set your real domain (most important)

Canonical links, `og:url`, the structured data, `robots.txt` and `sitemap.xml` still use the address that was in
your project: `https://corridor-showcase.lovable.app`. If you host on your own domain and leave this, Google is told
that the lovable.app address is the "real" site and your own domain will not rank. Send me your live address and I
will put it in every file, or replace it yourself in `index.html`, `privacy.html`, `robots.txt`, `sitemap.xml`.

## Nobody can promise first place

Ranking first for "agency in UP" or "creative marketing agency" depends on competition, links to your site and your
Google Business Profile, not on page code alone. This update makes sure search engines understand what you do and where.
These steps move rankings most (none can be done in code):

1. Create and verify a **Google Business Profile** for Formera (Hapur, service area Uttar Pradesh) with the same phone and
   email as the site, photos, and a few client reviews. This matters most for "near me" and "in UP" searches.
2. Add the site to **Google Search Console** (and Bing Webmaster Tools) and submit `sitemap.xml`.
3. List the agency in directories (Justdial, Sulekha, Clutch, LinkedIn, Instagram bio link) with the same name, phone and city.
4. Get links from local businesses, clients and partners that point to your site.

## Recommended, NOT applied (these change what visitors see, so I need your OK)

- One visible sentence with the target words, for example under "We shape motion, light and form.": *"Formera Creations is a
  creative marketing agency in Hapur, Uttar Pradesh, working with brands across Western UP and India."* Search engines
  rely heavily on visible text, so this is the biggest on-page gain still available.
- A small visible "Where we work" line listing Hapur, Ghaziabad, Meerut, Noida, Bulandshahr and Moradabad.
- A 1200 x 630 sharing image (add `og:image` / `twitter:image` tags) so links shared on WhatsApp / Facebook / LinkedIn show a picture.
- Your street address on the page (and in the structured data) once you have a Google Business Profile.
