# Luxury Beauty Website Design Reference

*A design/creative-direction reference compiled from Chanel Fragrance, Kylie Cosmetics, and Augustinus Bader — for use as inspiration on future luxury beauty/haircare site builds (e.g. MAISON D'VUE). Compiled August 11, 2026 via live site research.*

> **Note on accuracy:** Color hex codes and font-family names below combine direct page inspection with AI-assisted visual analysis of each site. Treat hex values as close approximations of the brand's palette family, not pixel-exact swatches — for a production build, pull final hex/font values from each site's live CSS with a browser inspector before locking a palette.

---

## 1. Chanel — Fragrance (chanel.com/in/fragrance)

**URL researched:** https://www.chanel.com/in/fragrance/

### Design Theme
Luxurious minimalist / high-editorial. Product is treated like art — large uninterrupted imagery, almost no visual clutter, no aggressive sales language. Confidence expressed through restraint: a lot of white space and very few competing elements per screen.

### Color Palette
- Background: white (#FFFFFF) — dominant throughout
- Text: black (#000000)
- Accent: warm gold (~#DAA520 family) used sparingly for highlights, limited-edition badges, and hover states
- No secondary brand colors — Chanel deliberately restricts itself to black/white/gold across all digital touchpoints

### Typography
- Headings: sans-serif, bold weight, wide letter-spacing (~0.1em), set in ALL CAPS — gives the editorial, fashion-house authority
- Body copy: sans-serif (Helvetica/Arial family), regular weight, tighter tracking, sentence case — kept quiet so headlines and imagery lead
- Overall type hierarchy is very high-contrast: bold caps headline vs. quiet body copy, almost no mid-weight text

### Layout Style
Full-bleed hero → horizontal scrolling product carousel → alternating large single-image editorial "pushes" (image + short headline + one CTA) → grid-based category tiles → repeat. Everything is single-column on mobile, generous multi-column grid on desktop. No sidebar clutter, no dense text blocks.

### Buttons / CTAs
Minimal — thin-bordered or text-only links ("Sign up," "Discover," "SHOP NOW") rather than heavy filled buttons. Rounded, low-emphasis styling with subtle shadow; CTAs never compete visually with the product photography.

### Spacing
Generous whitespace between every section; each editorial "push" gets to breathe as essentially its own full-screen moment before the next begins.

### Video & Photo Usage by Section

| Section | Videos | Photos |
|---|---|---|
| Hero ("Coco Mademoiselle Crush Absolu") | 1 looped, muted, pausable background video | 0 |
| "The Essentials" (horizontal product carousel) | 0 | 6 product shots |
| Editorial pushes (Coco Mademoiselle EDP / Les Exclusifs / Bleu de Chanel L'Exclusif) | 0 | 3 large lifestyle/product images |
| Shop by Category grid | 0 | 4 category tile images |
| "The Bleu de Chanel Ritual" banner | 0 | 1 |
| "Give care, give Chanel" (gifting push) | 0 | 1 |
| Special Editions push | 0 | 1 |
| **Total (page as scraped)** | **1 video** | **~16 photos** |

Chanel is video-light and photo-led — one atmospheric hero video sets the tone, and everything after that is still photography treated at large scale.

---

## 2. Kylie Cosmetics (kyliecosmetics.com)

**URL researched:** https://kyliecosmetics.com/

### Design Theme
Playful maximalist DTC / pop-glam. Bright, high-energy, influencer-driven — built around a rotating fragrance/product launch narrative ("Mood Stones") and constant social proof via a live Instagram feed. Much more "always launching something" energy than Chanel or Augustinus Bader.

### Color Palette
- Background: white (#FFFFFF), with black (#000000) used for nav/footer/contrast blocks
- Accent palette is warm and glam-driven: blush pink (~#D9B9C2), gold (~#FFD700 / #F4D03F), and a saturated pink CTA color (~#ED5A96) used consistently for buttons
- Overall palette reads soft-neutral base + one loud accent color per product launch (fragrance trio names like "cashmere muse," "blush wood," "velvet brew" each get their own supporting tone)

### Typography
- Headings: sans-serif, bold, all lowercase (a deliberate brand choice — headlines like "introducing mood stones" are set in lowercase, not caps), tight letter-spacing
- Body: sans-serif (Arial-family), regular weight
- The all-lowercase headline treatment is a distinct signature vs. Chanel's all-caps — reads younger, more casual, more "text from a friend" than formal luxury

### Layout Style
Dense, scroll-heavy grid. Hero slideshow → mini product carousel → autoplay video section → three repeating "scent story" blocks (each pairing a product shot with a lifestyle/portrait image) → shoppable product grid with add-to-cart inline → shop-by-category tile grid → Virtual Try-On promo (appears twice) → a very large, continuously-loading Instagram feed grid at the bottom.

### Buttons / CTAs
Rounded corners (~8px radius), solid-fill pink background, white text — high contrast, high visibility, clearly optimized for click-through/conversion rather than restraint.

### Spacing
Still generous by DTC standards, but sections are packed closer together than Chanel — more content per scroll, reflecting a conversion-first Shopify template rather than an editorial magazine feel.

### Video & Photo Usage by Section

| Section | Videos | Photos |
|---|---|---|
| Hero ("Introducing Mood Stones") | 0 (static rotating banner, "Pause slide rotation" control) | 1 hero banner (desktop + mobile crops) |
| Mini product carousel under hero | 0 | 3 product tiles |
| "A New Fragrance Experience" | 1 autoplay video (desktop + mobile versions) | 0 |
| Per-scent story blocks (cashmere muse / blush wood / velvet brew) | 0 | 6 (product shot + portrait per scent × 3 scents) |
| "Shop Mood Stones" product grid | 0 | 4 |
| Shop by Category grid | 0 | 6 |
| Virtual Try-On promo (appears twice on page) | 0 | ~4 (desktop + mobile banners across both instances) |
| "Shop Our IG" live feed | 0 | ~17+ (continuously-loading UGC grid, more load on scroll) |
| **Total (page as scraped)** | **1 video** | **~40+ photos** |

Kylie Cosmetics is the most photo-dense of the three by a wide margin, almost entirely driven by the live Instagram grid and the density of product/lifestyle imagery per launch.

---

## 3. Augustinus Bader (augustinusbader.com)

**URL researched:** https://augustinusbader.com/

### Design Theme
Clinical luxury / "science you can trust." Warmer and quieter than Kylie, more data-forward than Chanel — the design exists to support a constant drumbeat of proof points (percentages, clinical trial stats, press awards) without feeling like a spreadsheet. Reads premium but credentialed rather than purely aspirational.

### Color Palette
- Background: white (#FFFFFF)
- Text: black (#000000)
- Accent/supporting tones: warm neutrals — cream/sand (~#F1E3D3), dusty rose/mauve (~#C8A8A0, ~#A67B7C) — used in product packaging photography, icon backgrounds, and CTA fills
- Palette overall is a soft, warm neutral system rather than a single loud brand color — consistent with the "clinical skincare" positioning (calm, dermatological, not flashy)

### Typography
- Headings: sans-serif, bold, moderate letter-spacing (~0.05em), sentence case (not all-caps — softer and more approachable than Chanel)
- Body: sans-serif (Helvetica Neue family), regular weight
- Numbers/stats (the "97% agree...", "$365.00" etc.) are treated as first-class typographic elements — large, bold figures are a recurring design motif across the page, more so than either other site

### Layout Style
Hero slideshow (2 rotating banners) → tabbed product carousel (Latest Innovations / Bestsellers / On-the-go) → founder credibility block → press/awards logo-and-quote grid → customer testimonial quotes (text-only) → an extensive "Clinical and User Trials" interactive carousel with percentage call-outs per product → TFC8® technology explainer with diagram + animation → membership/loyalty icon row → auto-replenishment banner → journal/blog teaser grid. This is the most content-heavy, longest-scrolling homepage of the three, built to progressively build trust through evidence rather than pure atmosphere.

### Buttons / CTAs
Rounded-corner buttons, bold fill in the dusty-rose/mauve accent tone. "Learn More," "Shop Now," "View All Awards" — direct and instructional rather than evocative.

### Spacing
Generous section-to-section spacing, but each section itself is denser with text/data than Chanel or Kylie — lots of small-print clinical disclaimers, stat call-outs, and structured data tables of trial results.

### Video & Photo Usage by Section

| Section | Videos | Photos |
|---|---|---|
| Hero (Award-Winning Skincare / Summer Edit rotating banner) | 0 | 2 |
| Trending Products tabbed carousel (Latest Innovations / Bestsellers / On-the-go) | 0 | ~13 product shots across 3 tabs |
| Founder block (Professor Augustinus Bader) | 0 | 1 |
| Awards/press grid (Esquire, Vogue, InStyle, Beauty Life, Harper's Bazaar, Allure, Glamour, British Vogue, Cosmopolitan, Marie Claire) | 0 | 10 |
| Customer testimonials | 0 | 0 (text-only quotes) |
| "Dive into the Evidence" clinical trial carousel | 0 | 4 product shots (Rich Cream, Cream, Body Cream, Face Oil) |
| "The Science of TFC8®" explainer | 1 (TFC8® animation) | 1 diagram |
| Exclusive Club Rewards | 0 | 6 icon graphics |
| Auto-Replenishment banner | 0 | 1 |
| "Expert tested" journal/blog teaser | 0 | 3 article thumbnails |
| **Total (page as scraped)** | **1 video** | **~41 photos** |

Augustinus Bader is photo-heavy like Kylie, but the imagery is almost entirely product packshots and press/award tiles rather than lifestyle or UGC content — reinforcing the clinical, evidence-driven brand voice.

---

## 4. Side-by-Side Comparison

| | Chanel Fragrance | Kylie Cosmetics | Augustinus Bader |
|---|---|---|---|
| **Theme** | Luxurious minimalist / editorial | Playful maximalist DTC / pop-glam | Clinical luxury / evidence-driven |
| **Background** | White | White + black contrast blocks | White |
| **Primary accent** | Gold | Pink / gold | Dusty rose, cream |
| **Headline case** | ALL CAPS | all lowercase | Sentence case |
| **Headline weight** | Bold, wide tracking | Bold, tight tracking | Bold, moderate tracking |
| **Body font family** | Helvetica/Arial | Arial | Helvetica Neue |
| **CTA style** | Minimal, text-link/thin border | Solid pink fill, rounded | Solid mauve fill, rounded |
| **Layout density** | Sparse, one idea per screen | Dense, launch-driven | Dense, data/proof-driven |
| **Video usage** | 1 atmospheric hero video | 1 lifestyle/product video | 1 technology-explainer animation |
| **Photo volume (homepage)** | ~16 | ~40+ | ~41 |
| **Dominant imagery type** | Editorial lifestyle + product | UGC/Instagram + lifestyle + product | Product packshots + press/awards |
| **Social proof style** | None on this page (pure brand storytelling) | Live Instagram feed, product ratings | Clinical stats, press quotes, testimonials |

## 5. Takeaways for Future Reference

- **If aiming for "quiet luxury" (closest to MAISON D'VUE's current direction):** follow Chanel's model — one strong hero video/image, minimal CTAs, huge whitespace, all-caps wide-tracked headlines, single accent color (gold), and let large-format photography do the selling rather than data or social proof.
- **If aiming for launch-hype/DTC energy:** Kylie's model — lowercase casual headlines, one loud accent color per product drop, heavy use of UGC/social feed, dense conversion-focused CTAs.
- **If aiming to build trust through science/proof (relevant if MAISON D'VUE leans into its patent-pending Affinity Matrix™ claim):** Augustinus Bader's model — treat statistics and clinical/consumer trial results as hero-level typography, dedicate a full section to "how the technology works," and stack press/award credibility directly under the hero.
- Across all three, the base palette is always white background + black text — luxury beauty sites consistently reserve color for a single accent rather than a multi-color system. This validates MAISON D'VUE's current cobalt/gold + Âme de Vue™ scent-thread approach as being in line with category norms.
- All three sites are effectively video-light (1 hero-level video each) — video is used as an atmospheric accent, not a primary storytelling device. Photography carries the bulk of the visual weight everywhere.
