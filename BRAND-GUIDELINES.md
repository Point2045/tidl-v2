# TIDL Brand Guidelines

## Brand Identity

**Name:** TIDL  
**Tagline:** Peak Performance Medicine, Delivered  
**Voice:** Clinical authority meets modern accessibility. Direct, confident, never clinical-cold. Think: the competence of a top-tier medical practice with the ease of a luxury concierge.

---

## Logo System

### Primary Mark
- **Square mark:** Gold (#C4A35A) background, black serif "T" centered
- **Wordmark:** "TIDL" in Cormorant Garamond, 500 weight, letter-spacing: 2px
- **Lockup:** Square mark left, wordmark right, 10px gap

### Usage Rules
- Minimum clear space: 1× the mark height on all sides
- Never stretch, rotate, or alter the logo
- On dark backgrounds: gold mark stays gold, wordmark goes white
- On light backgrounds: gold mark stays gold, wordmark goes black (#0F0F0C)
- Never place on busy photography without a solid overlay

---

## Color Palette

### Primary Colors
| Token | Hex | Usage |
|-------|-----|-------|
| `--gold` | `#C4A35A` | Primary accent, CTAs, highlights, brand signature |
| `--gold-lt` | `#E2CFA0` | Hover states, secondary accents |
| `--gold-dk` | `#8B7030` | Labels, overlines, muted gold elements |
| `--gold-bg` | `#F7F1E4` | Light gold backgrounds, card highlights |
| `--text` | `#0F0F0C` | Primary text, headings |
| `--black` | `#0A0A08` | Dark section backgrounds |
| `--dark` | `#111110` | Hero backgrounds, dark sections |
| `--dark2` | `#1C1C19` | Card backgrounds in dark sections |
| `--cream` | `#FAFAF7` | Page background |
| `--white` | `#FFFFFF` | Card backgrounds, light sections |
| `--warm` | `#F4EFE6` | Subtle warm backgrounds |
| `--border` | `#E8E2D6` | Dividers, card borders |
| `--muted` | `#6B6860` | Secondary text, descriptions |
| `--subtle` | `#9E9B95` | Tertiary text, price labels |

### Semantic Colors
| Token | Hex | Usage |
|-------|-----|-------|
| `--success` | `#4A7C59` | Success states, confirmations |
| `--success-bg` | `#EDF5F0` | Success backgrounds |
| `--error` | `#B84233` | Error states, warnings |
| `--error-bg` | `#FDF0EE` | Error backgrounds |
| `--info` | `#3B6B9C` | Informational states |
| `--info-bg` | `#EDF3FA` | Info backgrounds |

### Color Rules
- **Gold is the signature.** Use it sparingly for maximum impact — CTAs, accents, hover states, brand marks.
- **Never use gold as body text.** It's for emphasis only.
- **Dark sections** use `--dark` (#111110) as background, white/gold for text hierarchy.
- **Light sections** use `--cream` (#FAFAF7) or `--white` (#FFFFFF) as background.
- **Contrast ratios:** All text must meet WCAG AA (4.5:1 for body, 3:1 for large text).

---

## Typography

### Type Scale
| Role | Font | Weight | Size | Letter-Spacing | Line-Height |
|------|------|--------|------|----------------|--------------|
| Display H1 | Cormorant Garamond | 300 | clamp(3rem, 6vw, 5.5rem) | -2px | 1.05 |
| Display H2 | Cormorant Garamond | 300 | clamp(2rem, 4vw, 3.2rem) | -1px | 1.1 |
| Section Title | Cormorant Garamond | 500 | 1.3–1.5rem | -0.3px | 1.2 |
| Overline | Inter | 600 | 0.65–0.68rem | 2–3px | 1.4 |
| Body | Inter | 300–400 | 0.85–0.92rem | 0 | 1.6–1.8 |
| Small/Caption | Inter | 400 | 0.72–0.78rem | 0–0.5px | 1.5 |
| Price | Cormorant Garamond | 300–400 | 1.5–3rem | -0.5 to -2px | 1 |
| CTA | Inter | 600 | 0.72–0.78rem | 1.5px | 1 |

### Font Families
- **Display:** `Cormorant Garamond`, Georgia, serif — for headings, prices, product names
- **Body:** `Inter`, -apple-system, BlinkMacSystemFont, sans-serif — for all UI text, descriptions, buttons

### Typography Rules
- **Cormorant Garamond** is for emotion and elegance — headings, prices, product names, testimonials
- **Inter** is for function and clarity — body copy, buttons, labels, navigation
- **Never** use Cormorant Garamond for body text below 1rem
- **Never** use Inter for display headings
- **Italic** in Cormorant Garamond = emphasis/gold color for key words
- **Overlines** are always uppercase, Inter 600, 2–3px letter-spacing, gold-dk color

---

## Spacing & Layout

### Spacing Scale
4 · 8 · 12 · 16 · 20 · 24 · 28 · 32 · 40 · 48 · 64 · 80 · 96px

### Grid
- **Max content width:** 1200px
- **Page padding:** 56px desktop, 24px mobile
- **Section padding:** 100–120px vertical (desktop), 80px (mobile)
- **Card gaps:** 16–20px
- **Grid columns:** 4-col (concerns), 3-col (products), 2-col (featured)

### Border Radius
- **Small:** 4px (tags, badges)
- **Medium:** 8px (inputs)
- **Large:** 12px (cards on mobile)
- **None (0):** Primary design language — sharp edges, architectural feel
- **Full (9999px):** Pills, badges only

---

## Components

### Buttons
| Variant | Background | Text | Border | Hover |
|---------|-----------|------|--------|-------|
| Primary | `--gold` | `--text` | none | `--gold-lt` bg |
| Outline (light) | transparent | `--white` | 1px rgba(255,255,255,0.2) | border gold, text gold |
| Outline (dark) | transparent | `--text` | 1px `--border` | border gold, text gold |
| Nav Primary | `--text` | `--cream` | none | `--gold` bg, `--text` text |

**All buttons:**
- Height: ~44px (primary), ~36px (nav)
- Padding: 14px 32px (primary), 10px 24px (nav)
- Font: Inter 600, 0.72rem, 1.5px letter-spacing, uppercase
- Transition: 0.25s ease
- Arrow (→) on primary CTAs, shifts right on hover

### Cards
- **Light cards:** `--white` or `--cream` bg, 1px `--border` border
- **Dark cards:** `rgba(255,255,255,0.03)` bg, `rgba(255,255,255,0.06)` border
- **Hover:** translateY(-2px to -3px), `--shadow-md`, border → `--gold`
- **Top accent line:** 3px `--gold` bar on hover (concern cards)

### Product Cards
- Image area: 220px height, `--dark` background
- Emoji as placeholder icon (replace with product photography)
- Tag badge: gold bg, black text, 0.62rem uppercase
- Price: Cormorant Garamond, large, with /mo or /dose in Inter small

### Navigation
- Fixed, 64px height
- Background: `rgba(250,250,247,0.97)` + blur(20px)
- Logo left, links center, CTA right
- Links: Inter 500, 0.78rem, underline on hover (gold, scale animation)
- Scroll state: solid bg + shadow-sm

---

## Iconography

- **Current:** Emoji placeholders (💊🧴🧠💤💇💪✨⚖️❤️🔥🩺📦🔒⭐📋💬💰🔬)
- **Production:** Replace with custom line icons in gold-dk (#8B7030) on light backgrounds, gold (#C4A35A) on dark backgrounds
- **Icon containers:** 48–56px square, `--gold-bg` background on light, `rgba(196,163,90,0.1)` on dark
- **Icon size:** 1.3–1.5rem within containers
- **Border:** 1px `rgba(196,163,90,0.2)` on dark containers

---

## Photography & Imagery

### Style
- **Clean, clinical, warm** — not cold or sterile
- Soft lighting, neutral backgrounds
- Product shots on dark (#111110) or warm (#F4EFE6) surfaces
- Lifestyle: real people, natural light, aspirational but accessible
- **No stock medical imagery** (no stethoscopes, no white coats on models)

### Treatment
- Subtle gold gradient overlay on hero images
- Dark sections: radial gold glow at 30–50% opacity
- Product photography: centered, well-lit, minimal props

---

## Voice & Copy

### Principles
1. **Direct, not clinical** — "Your health, delivered" not "Optimizing patient outcomes"
2. **Confident, not arrogant** — "Clinically-proven" not "The best treatment available"
3. **Warm, not casual** — "We're here for you" not "Hey bestie"
4. **Specific, not vague** — "$20/mo" not "Affordable pricing"
5. **Active, not passive** — "Start your visit" not "A visit can be started"

### Terminology
| Use | Don't Use |
|-----|-----------|
| Provider | Doctor (unless MD specifically) |
| Treatment | Medication (when broader) |
| Visit | Appointment |
| Delivered | Shipped (too transactional) |
| Personalized | Customized (too tech) |
| Evidence-based | Natural (implies unproven) |
| Discreet | Secret (implies shame) |

### CTA Patterns
- Primary: "Start Free Visit →" / "Get Started →"
- Secondary: "Learn More" / "See How It Works"
- Product: "Start Visit →"
- Never: "Submit" / "Click Here" / "Buy Now"

---

## Page Structure (Hims-Inspired)

### Homepage Flow
1. **Hero** — Bold headline, value prop, CTA, product preview grid
2. **Trust Bar** — Stats strip (providers, prescriptions, ratings, shipping)
3. **Shop by Concern** — 8-card grid (Hair Loss, ED, Skincare, Mental Health, Weight, Sleep, Heart Health, Cold Sores)
4. **Popular Products** — 6-card product grid with pricing
5. **Featured Protocol** — Spotlight product with benefits list
6. **How It Works** — 3-step (Assessment → Provider Review → Delivery)
7. **Why TIDL** — 6-card value props
8. **Testimonials** — 3-card social proof
9. **Trust Stats** — 4-stat credential bar
10. **CTA** — Final conversion push
11. **Footer** — Treatments, Company, Support, Legal

### Key Differences from Hims
- **Luxury positioning** — Gold accents, serif typography, architectural spacing
- **Darker palette** — Dark hero/sections vs Hims' all-white
- **Cormorant Garamond** — Elegant serif vs Hims' sans-serif system
- **Sharp edges** — No border-radius on primary components (architectural feel)
- **Gold accent system** — Consistent gold hierarchy vs Hims' blue/purple accents

---

## Responsive Breakpoints

| Breakpoint | Width | Changes |
|-----------|------|---------|
| Desktop | >1024px | Full grid, all sections |
| Tablet | 768–1024px | 2-col grids, nav links hidden |
| Mobile | <768px | Single column, reduced padding, simplified hero |

---

## File Structure

```
tidl-v2/
├── index.html          # Main wireframe
├── BRAND-GUIDELINES.md # This file
└── (assets/)           # Future: images, icons, fonts
```

---

## Implementation Notes

1. **Replace emojis** with custom SVG icons or product photography before production
2. **Add real product images** — dark background product shots, lifestyle imagery
3. **Interactive elements** — Concern cards and product CTAs should link to intake flows
4. **Accessibility** — All color combinations meet WCAG AA; add ARIA labels to interactive elements
5. **Performance** — Cormorant Garamond + Inter loaded via Google Fonts; consider self-hosting for production
6. **Animation** — Subtle hover transitions (0.25s ease); consider scroll-triggered reveals for production
7. **Forms** — Intake/assessment flow not yet designed; should follow same design system