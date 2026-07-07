# Kompresso — SEO Keyword Research & Strategy

Goal: rank for searches by people who have a **large video on their iPhone right now and need it smaller** — the highest-converting intent for a free iOS video compressor. We prioritize keywords with clear task intent ("how do I…") over vanity head terms, because task-intent searchers install immediately after reading the fix.

## Search intent tiers

1. **Transactional / app-seeking** — "video compressor app iphone". User wants an app. Highest conversion, most competitive.
2. **Problem-solving / how-to** — "how to compress a video on iphone for email". User has a problem; the app is the answer. This is our sweet spot: lower competition, buyer intent, and it lets us *earn the click, then present Kompresso as the fix*. Every guide page targets one of these.
3. **Symptom / frustration** — "why is my iphone video too big to send", "iphone video won't send in text". Top of funnel; we capture with FAQ + guides.

## Primary keywords (head terms — hero, title, H1, meta)

| Keyword | Intent | Competition | Placement |
|---|---|---|---|
| video compressor for iphone | Transactional | High | `<title>`, H1, hero |
| compress video iphone | Transactional | High | Hero, H2, description |
| iphone video compressor app | Transactional | High | Meta description, download CTA |
| reduce video size iphone | Problem | Med-High | Hero subhead, how-it-works |
| make video smaller iphone | Problem | Medium | FAQ, body copy |
| shrink video file iphone | Problem | Medium | Body copy |

## Secondary keywords (feature & attribute — supporting sections)

- free video compressor iphone (no watermark)
- compress video without losing quality iphone
- offline video compressor iphone / private
- batch video compressor iphone / compress multiple videos
- compress video for iphone and ipad
- HD / 1080p / 4K video compressor
- MP4 / MOV / M4V video compressor
- H.265 HEVC vs H.264 compression

## Long-tail keywords → one guide page each (the money pages)

These are the pages that will actually pull organic installs. Each targets a specific real-world task; each guide answers the question **then** shows how Kompresso does it in a few taps. Slugs live under `website/guides/`.

| # | Target keyword (+ variants) | Monthly intent | Guide slug |
|---|---|---|---|
| 1 | how to compress a video on iphone | Pillar / very high | `how-to-compress-a-video-on-iphone` |
| 2 | how to compress a video for email on iphone / make video small enough to email | High | `compress-video-for-email-iphone` |
| 3 | how to compress a video for whatsapp on iphone | High | `compress-video-for-whatsapp-iphone` |
| 4 | how to send a large video from iphone / video too big to send | High (frustration) | `how-to-send-a-large-video-from-iphone` |
| 5 | how to convert a video to mp4 / hevc to h.264 on iphone | Medium-high | `convert-video-to-mp4-iphone` |
| 6 | how to compress 4k video on iphone | Medium | `compress-4k-video-on-iphone` |
| 7 | how to reduce video file size without losing quality | Medium-high | `reduce-video-file-size-without-losing-quality` |
| 8 | how to compress a video for discord on iphone (8MB/10MB limit) | Medium | `compress-video-for-discord-iphone` |
| 9 | how to free up storage on iphone by compressing videos | Medium (storage-full pain) | `free-up-iphone-storage-compress-videos` |
| 10 | how to compress multiple / batch videos on iphone | Medium | `batch-compress-videos-on-iphone` |

## FAQ keywords (each = one SEO question, with a "Learn More" link to its guide)

- Why is my iPhone video file so large? → guide 9
- How do I make a video small enough to email? → guide 2
- What's the max video size for WhatsApp / iMessage? → guide 3 / 4
- Does compressing a video lower its quality? → guide 7
- What's the difference between H.264 and H.265 (HEVC)? → guide 5
- Can I compress a 4K video without losing quality? → guide 6
- Is it safe / private to compress videos? (offline) → home privacy section
- Can I compress many videos at once? → guide 10
- Does Kompresso add a watermark or cost money? → download section

## On-page SEO checklist applied

- Unique `<title>` + meta description per page, keyword-front-loaded, under ~60/155 chars.
- One H1 per page containing the primary keyword; H2/H3 mirror long-tail phrasings.
- Canonical URLs, Open Graph + Twitter cards, favicon, theme-color.
- JSON-LD structured data:
  - Home: `SoftwareApplication` (with `aggregateRating`, `offers` free), `FAQPage`, `WebSite`.
  - Each guide: `HowTo` + `BreadcrumbList`.
- Descriptive `alt` text on every screenshot with target keywords.
- Internal linking: home ↔ all guides ↔ related guides (topic cluster / hub-and-spoke).
- Fast, self-contained, mobile-first, semantic HTML, accessible landmarks.
- `sitemap.xml` + `robots.txt`.

## Domain note

Canonical base URL is set to `https://kompresso.app/` throughout as the assumed production domain (developer email uses `barisulas.app`). Update the `<base>`/canonical/OG URLs and `sitemap.xml` if the real domain differs.
