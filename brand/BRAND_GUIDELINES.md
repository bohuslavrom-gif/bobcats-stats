# PlayMetric — Brand Guidelines

Sport stats platform — measure every play.

## Brand voice

| Atribut | Description |
|---|---|
| Positioning | Sports analytics tool pro vážné týmy, ligy a svazy |
| Personality | Profesionální, datově orientovaný, důvěryhodný, moderní |
| Tagline | **Measure every play** |
| Alt taglines | "Data-driven sport" · "From play to performance" · "Stats that coach" |
| Tone | Technický ale srozumitelný, věcný, bez vykřičníků |

## Color palette

### Primary (brand)

| Token | Hex | RGB | Usage |
|---|---|---|---|
| Ink | `#0F1B2D` | 15, 27, 45 | Primary brand, dark backgrounds, body text on light |
| Signal Red | `#E63946` | 230, 57, 70 | Action color, highlights, CTAs (max 5–10 % composition) |

### Neutrals

| Token | Hex | Usage |
|---|---|---|
| Pearl | `#FFFFFF` | Primary surface |
| Mist | `#F5F7FA` | Secondary surface, page background |
| Stone | `#E1E5EB` | Borders, dividers |
| Slate | `#5B6B7E` | Secondary text, muted labels |
| Graphite | `#2D3748` | Primary body text on light |

### Data viz / accents

| Token | Hex | Usage |
|---|---|---|
| Sky | `#7AB5D9` | Data series 1, neutral data bars |
| Verde | `#2A9D8F` | Success, positive trend |
| Spark | `#F4A261` | Warning, secondary chart |
| Plum | `#7B5BA6` | Tertiary chart series |

### Pravidla použití

- **Ink dominuje** — ~70 % každé kompozice (pozadí, header, body text)
- **Red akcentuje** — 5–10 %, jen CTA / klíčové highlighty / důležité skóre. Nikdy plochy a velké bloky.
- Na barevných pozadích používej text 8/9 stop ze stejného ramenu, ne plain black.
- Dark mode je primární pro app shell (PWA na mobilu), light mode pro public/coaches widgety na GitHub Pages.

## Typography

### Font stack

```css
font-family: 'Inter', system-ui, -apple-system, BlinkMacSystemFont, sans-serif;
```

Inter (Google Fonts) — moderní, vysoce čitelná geometrická sans, výborně optimalizovaná pro UI.

### Weights

- **400** — body text
- **500** — labels, sub-headings, "Play" v wordmarku
- **700** — headings, "Metric" v wordmarku, key numbers

Žádné jiné váhy. Two-weight rule: 500 + 700.

### Scale

| Use | Size | Weight | Letter-spacing |
|---|---|---|---|
| Display (hero) | 36–48 px | 700 | -1.2 px |
| H1 | 28–32 px | 700 | -0.8 px |
| H2 | 22 px | 500 | -0.4 px |
| H3 / large label | 16 px | 500 | 0 |
| Body | 14 px | 400 | 0 |
| Caption / micro | 11–12 px | 500 (ALL CAPS allowed) | 0.08 em |

## Logo system

| File | Use |
|---|---|
| `playmetric-icon.svg` | Standalone icon (data viz cards, inline) |
| `playmetric-icon-white.svg` | Icon na navy/dark background |
| `playmetric-icon-mono.svg` | Monochrome (single-color print, watermark) |
| `playmetric-logo-horizontal.svg` | Hlavičky, faktury, dokumenty (light bg) |
| `playmetric-logo-horizontal-white.svg` | Hlavičky na dark bg |
| `playmetric-logo-stacked.svg` | Square / vertical aspect (loading screens) |
| `playmetric-wordmark.svg` | Pure text variant (constrained heights) |
| `playmetric-app-icon.svg` | PWA / iOS home screen (512×512) |
| `playmetric-favicon.svg` | Browser tab (32×32) |

### Clear space

Minimální clear space kolem loga = výška "M" v "PlayMetric" (cca 1× kapitálka).

### Minimum size

- Horizontal logo: 120 px / 28 mm wide
- Icon only: 24 px / 6 mm
- Pod tyto rozměry hrozí ztráta čitelnosti červeného trojúhelníku.

### Don'ts

- ❌ Neměnit barvy elementů loga (modré sloupce, červený sloupec + trojúhelník — fixní)
- ❌ Nepoužívat na mletých/foto pozadích bez navy plochy pod logem
- ❌ Neotáčet, nezkosovat, neprotahovat
- ❌ Nepoužívat starou verzi (Bobcats logo) v PlayMetric kontextu

## Application

### App (data input PWA)

- Theme color: Ink `#0F1B2D`
- Status bar: black-translucent na iOS
- Home screen icon: `playmetric-app-icon.svg`
- App title: "PlayMetric"

### Public / Coaches widgety

- Team brand (např. Bobcats) zůstává dominantní v hero
- PlayMetric attribution = slim brand bar nahoře (logo vlevo, tagline vpravo)
- Footer: "Powered by PlayMetric · [link]"
