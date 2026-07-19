# Scrum for Teens — Brand Guide

> **Source:** Extracted from scrumforteens.com via OpenClaw browser (Playwright CDP) + Cloudflare webcrawl, July 19, 2026.
> **Reference style:** EBFC AI brand kit (brand-kits/ebfc-ai.html)

---

## 1. Brand Overview

| Field | Value |
|-------|-------|
| **Name** | Scrum for Teens |
| **Tagline** | "Empower Readers to Master Scrum and Succeed!" |
| **Mission** | Equip teens (and their educators/parents) with Scrum framework skills to stay organized, tackle challenges, and achieve more — in school and beyond. |
| **Audience** | Teens (primary), educators, parents, Scrum coaches |
| **Founder** | Noah Engineer-Manriquez |
| **Domain** | scrumforteens.com |
| **App** | app.scrumforteens.com (separate product) |
| **Book** | "How to Master Scrum: A Teen's Guide to Success" (available on Amazon) |

### Voice & Tone

| Pillar | Description |
|--------|-------------|
| **Empowering** | Speaks directly to teens as capable, not clueless. "You can do this." |
| **Approachable** | Warm, friendly, never jargon-heavy. No corporate speak. |
| **Credible** | Grounded in real results — classroom success stories, competition wins, measurable outcomes. |
| **Teen-Friendly** | Uses analogies teens relate to (sports, gaming, Shakespeare). Avoids condescension. |
| **Actionable** | Every section ends with something you can *do* — try the app, read the book, join a workshop. |

### Writing Principles

1. **Second person** — "you," "your," not "students" or "users"
2. **Short paragraphs** — 2–3 sentences max on screen
3. **Active voice** — "Master Scrum" not "Scrum can be mastered"
4. **Encouragement over instruction** — "Level up" not "Complete module 3"
5. **Real stories** — Noah's journey, classroom wins, competition results

---

## 2. Logo System

### Current State
The site uses a text-based logo in the navbar: **"Scrum for Teens"** in Source Sans Pro 700, 14px, white on dark backgrounds. No SVG or standalone logo file was extracted.

### Logo Description
- **Wordmark:** "Scrum for Teens" — set in Source Sans Pro Bold
- **Color variants:**
  - On dark backgrounds (navbar, hero): White `#FFFFFF`
  - On light backgrounds (footer): Dark gray `rgb(27, 27, 27)` or `#1B1B1B`
  - On beige accent sections: Dark text `rgb(12, 12, 12)` or `#0C0C0C`

### Gaps
- ⚠️ No SVG logo file found in extraction
- ⚠️ No favicon or apple-touch-icon specific to the brand (uses a generic 180×180 PNG)
- 📋 **Recommendation:** Commission a standalone logo mark (icon + wordmark) in SVG

### Logo Usage Rules
- **Clear space:** Minimum 1× the height of the "S" in "Scrum" on all sides
- **Minimum width:** 120px (wordmark becomes illegible below this)
- **Don't:** Stretch, rotate, recolor outside approved palette, add drop shadows, place on busy photos without a solid overlay

---

## 3. Color Palette

### Primary Colors

| Name | Hex | RGB | Role |
|------|-----|-----|------|
| **Warm Brown 1** | `#9C9387` | rgb(156, 147, 135) | Primary accent — headings H1, CTA backgrounds |
| **Warm Brown 2** | `#948E85` | rgb(148, 142, 133) | Secondary accent — H3 quotes, section headings |
| **Warm Brown 3** | `#7D756A` | rgb(125, 117, 106) | Tertiary accent — body links, hover states |
| **Warm Brown 4** | `#75706A` | rgb(117, 112, 106) | Muted accent — subtle borders, disabled states |

*Source: docs/research/design-tokens.json, colors.accent*

### Neutral Colors

| Name | Hex | RGB | Role |
|------|-----|-----|------|
| **Black** | `#000000` | rgb(0, 0, 0) | Primary text (headings), buttons, footer bg |
| **Near Black** | `#161616` | rgb(22, 22, 22) | Dark section backgrounds |
| **Dark Gray** | `#0C0C0C` | rgb(12, 12, 12) | Heading color on light backgrounds |
| **Primary Text** | `#1B1B1B` | rgb(27, 27, 27) | Body text, H4 headings |
| **Secondary Text** | `#5E5E5E` | rgb(94, 94, 94) | Secondary body text, descriptions |
| **Muted Text** | `#808080` | rgb(128, 128, 128) | Captions, footnotes |
| **Light Text** | `#A4A4A4` | rgb(164, 164, 164) | Tertiary text on light backgrounds |

*Source: docs/research/design-tokens.json, colors.text*

### Background Colors

| Name | Hex | RGB | Role |
|------|-----|-----|------|
| **White** | `#FFFFFF` | rgb(255, 255, 255) | Card backgrounds, main section bg |
| **Off White** | `#F7F7F7` | rgb(247, 247, 247) | Page background (body) |
| **Section Alt** | `#F6F6F6` | rgb(246, 246, 246) | Alternating section background |
| **Beige** | `#D5CFC7` | rgb(213, 207, 199) | Accent section background, dividers |

*Source: docs/research/design-tokens.json, colors.background*

### Semantic Colors

| Name | Hex | Usage |
|------|-----|-------|
| **CTA Black** | `#000000` | Primary button background |
| **CTA White** | `#FFFFFF` | Primary button text |
| **Link/Interactive** | `#575757` | rgb(87, 87, 87) — Hover states |
| **Error/Alert** | Not defined in extraction | 📋 Recommendation: define error red `#C62828` and success green `#2E7D32` |

---

## 4. Typography

### Font Stack

| Role | Font | Fallback | Weight |
|------|------|----------|--------|
| **Display / H1 / H2** | Playfair Display | Georgia, serif | 400 (regular) |
| **Body / UI / H4 / H6** | Source Sans Pro | Arial, sans-serif | 400 regular, 700 bold |
| **Computed fallback** | Times | — | — |

*Source: docs/research/design-tokens.json, fonts; docs/research/pages/README.md, Shared Patterns*

### Type Scale

| Token | Size | Line Height | Weight | Color | Usage |
|-------|------|-------------|--------|-------|-------|
| **H1 Hero** | 62px | 74.4px | 400 | `#FFFFFF` (on dark bg) | Home page hero only |
| **H1 Sub-page** | 38px | 53.2px | 400 | `#9C9387` (warm brown) | All other page main headings |
| **H2** | 38px | — | 400 | `#9C9387` / `#948E85` | Section headings |
| **H3** | 30px | 37.5px | 400 | `#948E85` | Quotes, pull-quotes |
| **H4** | 22px | 27.5px | 700 | `#1B1B1B` | Sub-headings, card titles |
| **H6 / Eyebrow** | 14–22px | — | 600 | `#151515` | Small section labels |
| **Body** | 16px | — | 400 | `#1B1B1B` | Default body text |
| **Nav** | 14px | — | 700 | `#FFFFFF` / `#1B1B1B` | Navigation items |
| **Small / Caption** | 12px | — | 400 | `#808080` | Footer, captions |

*Source: docs/research/pages/README.md, Font Size Scale; docs/research/design-tokens.json, fontSizes*

### Letter Spacing
- **Headings (H1/H2):** Normal (0)
- **Nav items:** Slight tracking (~0.04em)
- **Eyebrows (H6):** Tracking ~0.12em uppercase

### Google Fonts Import
```html
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400&family=Source+Sans+Pro:wght@400;600;700&display=swap" rel="stylesheet">
```

---

## 5. Component Patterns

### Buttons

| Property | Value |
|----------|-------|
| **Font** | Source Sans Pro, 14px, weight 700 |
| **Background** | `#000000` (black) |
| **Text color** | `#FFFFFF` (white) |
| **Padding** | 8px 32px |
| **Height** | 56px |
| **Width** | 444px (primary CTA), auto (secondary) |
| **Border radius** | 4px |
| **Display** | inline-flex |

```css
.cta-button {
  font-family: "Source Sans Pro", arial, sans-serif;
  font-size: 14px;
  font-weight: 700;
  color: #FFFFFF;
  background-color: #000000;
  padding: 8px 32px;
  height: 56px;
  border-radius: 4px;
  display: inline-flex;
  align-items: center;
  justify-content: center;
}
```

*Source: docs/research/design-tokens.json, button*

### Navigation Bar

| Property | Value |
|----------|-------|
| **Background** | `#161616` (near black) |
| **Text** | `#FFFFFF` (white), 14px, weight 700 |
| **Active/hover** | `#9C9387` (warm brown) |
| **Height** | ~60px |
| **Layout** | Horizontal, logo left, links right |
| **Mobile** | Hamburger menu with slide-out |
| **Links** | Home, About the Author, About the Book, App Features, Media Kit, Try the Free App! |

### Footer

| Property | Value |
|----------|-------|
| **Background** | `#000000` (black) |
| **Text** | `#FFFFFF` / `#A4A4A4` |
| **Layout** | Centered, 2–3 column on desktop |
| **Content** | Navigation links, email (info@scrumforteens.com), LinkedIn link |

### Section Alternation Pattern
Pages alternate section backgrounds to create visual rhythm:
1. **White** `#FFFFFF` — first section after hero
2. **Off White/Alt** `#F6F6F6` — second section
3. **Beige** `#D5CFC7` — accent section (quotes, CTAs)
4. Repeat as needed

### Cards
- White background `#FFFFFF`
- Minimal shadow or border
- H4 titles in `#1B1B1B`
- Body text in `#5E5E5E`

---

## 6. Layout System

### Page Dimensions
- **Max content width:** ~980px (GoDaddy builder default)
- **Page background:** `#F7F7F7`
- **Section padding:** ~40–60px vertical, ~20px horizontal (mobile ~16px)

### Responsive Breakpoints

| Breakpoint | Layout |
|-----------|--------|
| **Mobile** (< 600px) | Single column, stacked sections, full-width CTAs |
| **Tablet** (600–900px) | 2-column grids where applicable |
| **Desktop** (> 900px) | 3-column grids, side-by-side layouts |

### Grid Patterns
- **Feature cards:** 3-column on desktop → 1-column mobile
- **Hero:** Full-width image + overlay text
- **Content sections:** Alternating image-left / image-right

---

## 7. Imagery & Photography

### Style Direction
- **Authentic over stock:** Real photos of Noah, teens in workshops, classroom settings
- **Warm tones:** Photos naturally align with the warm brown palette — earth tones, natural light
- **Context:** Scrum boards, sticky notes, classroom scenes, book covers, event photos

### Image Assets (Extracted)

| Image | Dimensions | Source |
|-------|-----------|--------|
| Book cover | 984×1477 | CDN (home page) |
| Author headshot (Noah) | 899×1124 | CDN (about-the-author) |
| Scrum framework diagram | 984×718 | CDN (home page) |
| Content image (workshop) | 984×638 | CDN (home page) |
| Interview thumbnail | 600×300 | CDN (about-the-author) |
| App screenshots | 600×300 each | CDN (app-features) |

*Source: docs/research/pages/*.json, images arrays*

### Image Treatment
- No rounded corners on full-width hero images
- Slight padding on in-content images
- No heavy filters or overlays — clean, natural presentation
- Alt text should always be descriptive (accessibility)

---

## 8. Iconography

### Current State
The site uses minimal custom iconography — primarily text-based navigation and CTAs. No icon font or SVG icon system was extracted.

### Guidance
- **Style:** Simple, line-based icons (2px stroke) matching Source Sans Pro's geometric feel
- **Size:** 24px default, 16px inline, 32px feature cards
- **Color:** Inherit from parent text color, or use `#9C9387` (warm brown) for accent icons
- **Recommendation:** Adopt a consistent icon set (e.g., Lucide, Phosphor) for app features and CTAs

---

## 9. Content Pillars

| Pillar | Description | Example Topics |
|--------|-------------|---------------|
| **Scrum Education** | Teaching Scrum framework fundamentals to teens | Sprint planning, daily standups, retrospectives, backlogs |
| **Teen Empowerment** | Showing teens they can lead and organize | Noah's story, competition wins, classroom success |
| **Classroom Success** | Real results from applying Scrum in school | Grades improvement, project management, collaboration |
| **Noah's Journey** | Personal story of the young author | 7th grader → published author, Scrum practitioner → teacher |
| **Free App** | Companion tool for hands-on practice | Sprint tracking, achievement system, practice logging |

---

## 10. Accessibility

### Color Contrast

| Combination | Ratio | WCAG AA | WCAG AAA |
|------------|-------|---------|----------|
| `#1B1B1B` on `#FFFFFF` | 14.7:1 | ✅ | ✅ |
| `#5E5E5E` on `#FFFFFF` | 5.3:1 | ✅ | ❌ |
| `#FFFFFF` on `#000000` | 21:1 | ✅ | ✅ |
| `#FFFFFF` on `#161616` | 16.2:1 | ✅ | ✅ |
| `#9C9387` on `#FFFFFF` | 3.5:1 | ❌ (large text only) | ❌ |
| `#948E85` on `#FFFFFF` | 3.3:1 | ❌ (large text only) | ❌ |

**⚠️ Contrast Issues:**
- Warm brown headings (`#9C9387`, `#948E85`) on white backgrounds fail WCAG AA for normal text (need 4.5:1). They pass for large text (≥18px bold or ≥24px regular) at 3:1.
- **Recommendation:** For small text using warm browns, darken to `#6B6258` (4.5:1 on white) or use the primary `#1B1B1B` text color instead.

### Font Size Minimums
- Body: 16px (meets WCAG recommendation)
- Nav: 14px (acceptable for navigation)
- Small text: 12px minimum (captions/footnotes only)

### Touch Targets
- CTA buttons: 56px height × 444px width — exceeds 44×44px minimum ✅
- Nav links: Ensure ≥44px tap target (consider padding)

### Images
- All images must have descriptive `alt` text
- Decorative images use `alt=""` with `role="presentation"`

---

## 11. Implementation Notes

### CSS Custom Properties (for globals.css)

```css
:root {
  /* Colors */
  --color-warm-brown-1: #9C9387;
  --color-warm-brown-2: #948E85;
  --color-warm-brown-3: #7D756A;
  --color-warm-brown-4: #75706A;
  --color-text-primary: #1B1B1B;
  --color-text-secondary: #5E5E5E;
  --color-text-muted: #808080;
  --color-text-light: #A4A4A4;
  --color-bg-page: #F7F7F7;
  --color-bg-white: #FFFFFF;
  --color-bg-alt: #F6F6F6;
  --color-bg-beige: #D5CFC7;
  --color-bg-dark: #161616;
  --color-bg-black: #000000;

  /* Typography */
  --font-display: "Playfair Display", Georgia, serif;
  --font-body: "Source Sans Pro", Arial, sans-serif;
  --font-size-h1-hero: 62px;
  --font-size-h1: 38px;
  --font-size-h2: 38px;
  --font-size-h3: 30px;
  --font-size-h4: 22px;
  --font-size-body: 16px;
  --font-size-nav: 14px;
  --font-size-small: 12px;

  /* Buttons */
  --btn-height: 56px;
  --btn-radius: 4px;
}
```

### Tailwind Utility Mapping

| Design Token | Tailwind Class |
|-------------|---------------|
| `#9C9387` | `text-[#9C9387]` or custom `text-warm-brown-1` |
| `#D5CFC7` | `bg-[#D5CFC7]` or custom `bg-beige` |
| Playfair Display | `font-display` (extend theme) |
| Source Sans Pro | `font-body` (extend theme) |
| 62px hero text | `text-[62px] leading-[74px]` |
| 56px CTA button | `h-14 px-8 rounded` |

### Next.js Font Setup

```tsx
// layout.tsx
import { Playfair_Display, Source_Sans_3 } from 'next/font/google';

const playfair = Playfair_Display({
  weight: '400',
  subsets: ['latin'],
  variable: '--font-display',
});

const sourceSans = Source_Sans_3({
  weight: ['400', '600', '700'],
  subsets: ['latin'],
  variable: '--font-body',
});
```

---

## 12. Do's and Don'ts

### ✅ Do

- Use Playfair Display for headings, Source Sans Pro for body — never swap
- Use warm brown palette for accent text and backgrounds
- Maintain the alternating white/off-white/beige section rhythm
- Keep CTA buttons at 56px height with black background
- Use real photos of Noah and teens — avoid generic stock imagery
- Write in second person ("you") for all marketing content
- Include alt text on every image
- Test warm brown text contrast against white backgrounds (may need darkening)

### ❌ Don't

- Don't use Playfair Display for body text — it's a display font only
- Don't introduce new accent colors outside the warm brown family without brand approval
- Don't use blue, green, or other brand colors from EBFC AI — this is a separate brand
- Don't set warm brown text below 18px on white backgrounds (contrast failure)
- Don't use placeholder or stock photos of generic teens
- Don't add rounded corners to hero images (max 4px radius on CTAs only)
- Don't use technical Scrum jargon without plain-language context
- Don't write in third person or passive voice

---

*Generated: July 19, 2026 | Source: website-cloner skill Path B extraction*