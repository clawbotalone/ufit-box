# BRIEF — UFIT BOX

You are building a production-quality demo website for a Slovenian small business.
Language: **Slovenian (sl)** throughout (visible text, meta, alt). Do NOT use English in user-visible copy.

## Business

- **Name:** UFIT BOX
- **Slug:** ufit-box
- **City:** Murska Sobota
- **Industry / type:** podjetje
- **Address:** Bakovska ulica 2, 9000 Murska Sobota

## Contact

- **Phone:** 041 991 068
- **Email:** ufit.coach@gmail.com
- **Facebook:** https://www.facebook.com/UFit.osebnotrenerstvo/
- **Instagram:** *none*
- **Google Maps:** *none*
- **Existing website:** *none — this is a fresh demo*

## Services to feature (none)

*No curated services available — INFER 4-6 plausible services for this industry and clearly mark them as "PREDLAGANO — preverite z naročnikom".*


If a service has empty description, write 2-3 short Slovenian sentences that fit the industry.
Always include the price hint when given. Keep tone professional and warm.

## Design tokens

Use these EXACT colors and fonts as CSS custom properties on `:root`:

```css
:root {
  --bg-primary: #0a0f1e;
  --bg-secondary: #111827;
  --accent: #3b82f6;
  --accent-2: #06b6d4;
  --text: #f1f5f9;
  --text-muted: #94a3b8;
  --font-serif: 'Playfair Display', serif;
  --font-sans: 'Inter', system-ui, sans-serif;
}
```

Load both fonts via Google Fonts.

## Images available

Reference these as relative paths from the page:

*No images generated. Use CSS gradients in hero and skip the about photo section.*


Do not invent extra `<img>` tags. If a slot is missing, replace with a CSS gradient or omit entirely.

## Required page structure

1. **Fixed nav** with anchor links: O nas, Storitve, Kontakt
2. **Hero section** with business name (h1), tagline, 1-2 CTAs, hero image as background
3. **Services section** — grid of cards, one per service from the list above
4. **About section** — 2-3 paragraphs of Slovenian copy about the business + about photo
5. **Contact section** — phone, email, address, embedded Google Maps if available, contact form (visual only, no real submission)
6. **Footer** — copyright, social links, year

## Required technical features

- Mobile-responsive (320px → desktop). Use CSS grid + flexbox.
- Smooth scroll: load Lenis from https://unpkg.com/lenis@latest/dist/lenis.min.js
- Scroll animations: load GSAP + ScrollTrigger from https://cdn.jsdelivr.net/npm/gsap@3.12.5/dist/gsap.min.js and ScrollTrigger.min.js
- Stagger reveals on section entry
- Hover states on service cards (scale + border glow)
- Mobile hamburger menu for nav at <768px
- Skip-link, prefers-reduced-motion respect, semantic HTML (header, nav, main, section, footer)
- Meta tags: title, description, og:title, og:description, og:locale=sl_SI

## Output requirements

- Write a SINGLE complete `index.html` file at: `/home/clawdbot/sources/ufit-box/index.html`
- Minimum 1000 lines of HTML (inline CSS and JS, fully self-contained).
- All visible text in Slovenian.
- DO NOT add a PREDOGLED badge — the deploy step adds it later.
- Reference the images by relative path `images/...` (the images folder will be a sibling of index.html at deploy time).
- No external image hosts (Unsplash, etc.) — use ONLY the listed local images plus CSS effects.

When done, your final reply should confirm the file was written. No need to summarize the HTML.
