# Tour de France — Design System

## Overview

Each rider section is visually distinguished through a dedicated combination of typeface, color palette, and tonal mood. The goal is for the design itself to tell the story of each era — before the reader processes a single word.

Two principles hold the system together across all sections:

1. **Contrast within continuity** — shared structural conventions (section label, rider name, body text hierarchy) let the color and typographic differences read as intentional variation, not inconsistency.
2. **The Hinault/LeMond Futura device** — both sections use Futura, but treated completely differently (all-caps + crimson + black vs. mixed case + yellow + open background). The same typeface becoming two opposite moods is itself a storytelling move.

---

## Section I — Maurice Garin

**Era:** 1903 · First Tour de France

### Typeface
- **Headlines:** Bodoni (or IM Fell English as web fallback)
- **Style:** Italic, high contrast between thick and thin strokes
- **Weight:** Regular / Italic only — no bold
- **Tracking:** Default (let the letterforms breathe)

### Color Palette

| Role | Name | Hex |
|---|---|---|
| Background | Warm ivory | `#F2EDE6` |
| Surface / cards | Parchment | `#E8E2D4` |
| Mid-tone | Warm gray | `#B5A990` |
| Secondary text | Slate | `#7A7060` |
| Primary text | Dark umber | `#3D3530` |
| Deepest accent | Near-black | `#1A1814` |

### Mood & Rationale
Deep charcoals and warm ivories evoke daguerreotype photography and newspaper broadsheets of the Belle Époque. No color — only the full tonal range of black-and-white print. Bodoni's hairline serifs and extreme stroke contrast echo the hand-set type of 1903 press coverage. This section should feel like lifting a page out of *L'Auto*.

---

## Section II — Fausto Coppi

**Era:** 1949–1952

### Typeface
- **Headlines & Body:** Chivo
- **Weights:** Light (300) for body, Regular (400) for captions, Bold (700) for display
- **Style:** Upright; no italics for headlines
- **Tracking:** Slightly loose on headlines

### Color Palette

| Role | Name | Hex |
|---|---|---|
| Background | Cream | `#FAF6EE` |
| Surface / cards | Warm linen | `#F0EAD8` |
| Mid-tone | Warm sand | `#C4B89E` |
| Secondary text | Warm taupe | `#8A8070` |
| Primary text | Warm umber | `#3D3830` |
| Deepest accent | Dark brown-black | `#2A2420` |

### Mood & Rationale
Slightly warmer and softer than Garin — Coppi's era lives in Italian postwar documentary film, with that characteristic warm-creamy grain. Chivo's geometric sans contrasts the handmade feel of the era's photography while still reading as mid-century serious. Where Garin feels like a broadsheet, Coppi should feel like a matte-finish photo book.

---

## Section III — Eddy Merckx

**Era:** 1969–1974

### Typeface
- **Headlines & Body:** Roboto
- **Weights:** Light (300) for pull quotes, Regular (400) for body, Bold (700) for display
- **Style:** Upright; tight letter-spacing on headlines (`letter-spacing: -0.02em`)
- **Tracking:** Compressed at large sizes

### Color Palette

| Role | Name | Hex |
|---|---|---|
| Background | Ice blue | `#F0F5FC` |
| Surface / cards | Cool pale blue | `#E8F0F8` |
| Accent (light) | Ochre gold | `#E8C84A` |
| Accent (mid) | Maillot jaune gold | `#C8A020` |
| Primary | Deep royal blue | `#185FA5` |
| Deepest accent | Belgian navy | `#0D2B4E` |

### Mood & Rationale
The Belgian tricolor's deep blue and gold anchor this palette — reinforced by the cold, clear blue that evokes 1970s Kodachrome film. The gold references the maillot jaune that Merckx wore for a record 96 stages. Roboto's mechanical precision mirrors his systematic, encyclopedic dominance of the sport. This section should feel like an official record.

---

## Section IV — Bernard Hinault

**Era:** 1978–1985

### Typeface
- **Headlines:** Futura
- **Style:** All-caps, tight tracking (`letter-spacing: 0.06em`), heavy weight
- **Body:** Futura Regular for captions; consider a neutral sans for long body text
- **Tracking:** Tight — the type should feel aggressive

### Color Palette

| Role | Name | Hex |
|---|---|---|
| Background | Near-black | `#1A1A1A` |
| Surface / cards | Dark charcoal | `#3A3A3A` |
| Accent (light) | Cream white | `#FFF5F0` |
| Accent (soft) | Warm off-white | `#F0E8D8` |
| Primary accent | Crimson | `#C8002A` |
| Deep accent | Dark blood red | `#8C0018` |

### Mood & Rationale
Hinault — "The Badger" — was all aggression and Gallic pride. Crimson red on near-black feels like a fight poster, echoing the French tricolor's red against the militant aesthetic of 1980s European sport design. Futura in all-caps reinforces his punishing, confrontational style. This is the darkest section in the project — deliberately so.

> **Note on Futura vs. LeMond:** Same typeface, opposite mood. The all-caps + dark background + tight tracking make Hinault's Futura read as hard and combative. LeMond's Futura will be looser, mixed-case, and bright. This contrast is intentional and should be preserved.

---

## Section V — Greg LeMond

**Era:** 1986–1990

### Typeface
- **Headlines:** Futura
- **Style:** Mixed case (not all-caps), looser tracking, lighter weight than Hinault
- **Body:** Futura Regular or a complementary neutral sans
- **Tracking:** Airy — let the type breathe

### Color Palette

| Role | Name | Hex |
|---|---|---|
| Background | Bright yellow | `#F5C800` |
| Surface / cards | Pale yellow | `#FFF9E0` |
| Lightest tint | Near-white yellow | `#FFFDF5` |
| Accent | Royal blue | `#004A9C` |
| Accent | Vivid red | `#C8002A` |
| Deep accent | Dark gold | `#C89800` |

### Mood & Rationale
LeMond's 1989 comeback — winning by 8 seconds in a final time trial — is one of sport's great American underdog stories. The palette pulls directly from his Z-Team jersey and the Stars & Stripes: saturated yellow with red and blue accents. Futura here feels lighter and more optimistic than Hinault's version. Where Hinault's section is a fight poster, LeMond's should feel like a sports magazine cover from 1990.

---

## Section VI — Lance Armstrong

**Era:** 1999–2005 *(titles stripped)*

### Typeface
- **Headlines & Body:** Share Tech (monospace)
- **Style:** Upright, no decorative treatments — let the monospace do the work
- **Weight:** Regular only
- **Tracking:** Default — the mechanical spacing is the point

### Color Palette

| Role | Name | Hex |
|---|---|---|
| Background | Off-white | `#F5F5F0` |
| Surface / cards | Cool light gray | `#D4D4CC` |
| Accent (light) | Faded gold | `#B8A000` |
| Accent (primary) | LiveStrong yellow | `#FFDD00` |
| Primary | Dark charcoal | `#2A2A2A` |
| Deepest accent | Near-black | `#111111` |

### Mood & Rationale
Share Tech's monospace feel evokes data outputs, clinical reports, and redacted documents — fitting for a section shaped by doping investigations, USADA proceedings, and stripped titles. The LiveStrong yellow intrudes on a cold, near-black ground. The overall palette feels *engineered* rather than felt: corporate, calculated, slightly ominous. The design should carry an undercurrent of unease — something that looked clean but wasn't.

---

## Section VII — Tadej Pogačar

**Era:** 2020–present

### Typeface
- **Headlines:** Stack Sans Notch
- **Body:** Stack Sans
- **Style:** Mixed case; headlines can go large and variable
- **Tracking:** Generous at display sizes; tight in body

### Color Palette

| Role | Name | Hex |
|---|---|---|
| Background | Warm white | `#F7F2E8` |
| Surface / cards | Pure white | `#FFFFFF` |
| Accent | UAE orange | `#E8491A` |
| Accent | UAE magenta | `#E83A8C` |
| Accent | Electric blue | `#1A6CE8` |
| Accent | Maillot jaune | `#E8C01A` |

### Mood & Rationale
Pogačar is the era of UAE Team Emirates' chromatic kits, Strava data culture, and joyful, almost reckless dominance. The palette is deliberately plural — orange, magenta, and electric blue used simultaneously, like the color channels of modern sports broadcast graphics. Stack Sans Notch in headlines nods to variable-font experimentation and the digital-native audience this section speaks to most directly. This should be the most visually alive section in the project.

---

## Implementation Notes

### Futura Web Font
Futura is not available on Google Fonts. Recommended sourcing options:
- **Adobe Fonts** (if you have a Creative Cloud subscription)
- **Font Squirrel** — free for web use
- **CSS fallback stack:** `'Futura', 'Century Gothic', 'Trebuchet MS', sans-serif`

### Google Fonts (available)
The following typefaces used in this system are available via Google Fonts:
- Chivo: `https://fonts.google.com/specimen/Chivo`
- Roboto: `https://fonts.google.com/specimen/Roboto`
- Share Tech: `https://fonts.google.com/specimen/Share+Tech`
- Stack Sans / Stack Sans Notch: `https://fonts.google.com/specimen/Stack`
- IM Fell English (Bodoni fallback): `https://fonts.google.com/specimen/IM+Fell+English`

### CSS Variable Structure (suggested)
Each section should override a shared set of CSS custom properties:

```css
/* Example: Merckx section */
.section-merckx {
  --section-bg: #F0F5FC;
  --section-surface: #E8F0F8;
  --section-text-primary: #0D2B4E;
  --section-text-secondary: #185FA5;
  --section-accent: #C8A020;
  --section-accent-light: #E8C84A;
  --section-font-display: 'Roboto', sans-serif;
  --section-font-body: 'Roboto', sans-serif;
}
```

### Monochrome Sections (Garin & Coppi)
These sections should have accessibility contrast ratios verified carefully — the warm gray mid-tones can fall below WCAG AA at small sizes. Recommend using `#3D3530` or darker for any body text under 18px.
