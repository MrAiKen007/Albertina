<!-- SEED — re-run $impeccable document once there's code to capture the actual tokens and components. -->

# Design System: Albertina

## 1. Overview

**Creative North Star: "The Warm Workshop"**

A portfolio that balances editorial boldness with technical craft. Display typography leads with confidence while monospace body text grounds the work in Albertina's developer identity. The committed color strategy means a single warm hue carries the visual identity across 30-60% of surfaces — not as decoration, but as structure. Motion is restrained: nothing moves unless responding to a person's action. The site should feel like a thoughtfully made object, not a template.

**Key Characteristics:**
- Committed single-hue warmth, no timid accents
- Editorial display scale + technical monospace rhythm
- Motion only as a response to interaction
- Anti-template: no generic card grids, no hero-metric blocks

## 2. Colors

**The Committed Hue Rule.** One warm color carries 30-60% of the surface area. Its prevalence is intentional — it shapes the page, it doesn't decorate it.

### Primary
- **Warm Terracotta** (`[to be resolved during implementation]`): The committed hue. Used for primary surfaces (hero background, section fills, key dividers), major headings when emphasis is needed, and interactive elements.

### Neutral
- **Warm Off-White** (`[to be resolved during implementation]`): The primary background. Tinted warm — never pure white.
- **Warm Charcoal** (`[to be resolved during implementation]`): Primary text. Tinted warm — never pure black.
- **Stone** (`[to be resolved during implementation]`): Secondary text, borders, subtle dividers.

### Named Rules
**The Committed Hue Rule.** A single warm color fills 30-60% of surfaces. Its frequency is the point. If the page looks like it could work with any other color swapped in, the hue isn't doing enough work.

## 3. Typography

**Display Font:** [to be chosen at implementation] — a bold, characterful display typeface with strong contrast and presence.
**Body/Mono Font:** [to be chosen at implementation] — a legible monospace with warmth, for body text and code.

**Character:** The pairing bridges editorial polish and developer authenticity. Display type commands attention; monospace body rewards reading.

### Hierarchy
- **Display** (bold, `[size/clamp]`, `[line-height]`): Hero name, major section titles. Maximum 1-2 per page.
- **Headline** (semibold, `[size]`, `[line-height]`): Section headings throughout.
- **Title** (medium, `[size]`, `[line-height]`): Project titles, card headings.
- **Body** (regular, `[size/clamp]`, `[line-height]`): Paragraph text, project descriptions. Max 70ch line length.
- **Label** (medium, `[size]`, uppercase, `[letter-spacing]`): Small labels, tags, metadata.

## 4. Elevation

Flat by default. Depth is conveyed through color blocking and spacing, not shadows. The committed hue creates natural surface separation without relying on box-shadows. No elevation unless interactive state demands it.

## 5. Components

[To be documented at implementation. Run `$impeccable document` once there are components to scan.]

## 6. Do's and Don'ts

### Do:
- **Do** let the committed warm hue carry the visual weight — use it on large surfaces (hero, section backgrounds), not just small accents.
- **Do** use display type sparingly — 1-2 per page maximum, so it lands with force.
- **Do** respect line length: body text capped at 70ch.
- **Do** respect reduced motion preferences.

### Don't:
- **Don't** use template-looking patterns: no identical card grids with icon + text, no hero-metric templates, no side-stripe borders.
- **Don't** treat the warm hue as a secondary accent — it's the primary shaping force (30-60% of surfaces).
- **Don't** use pure black (#000) or pure white (#fff) anywhere.
- **Don't** animate layout properties. No bounce, no elastic easing.
- **Don't** use gradient text, glassmorphism, or decorative blurs.
