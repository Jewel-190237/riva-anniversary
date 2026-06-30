# Happy 3rd Anniversary, Riva ❤️

A beautifully crafted, animated anniversary webpage dedicated to **Sadia Tasmim Riva** — a heartfelt digital love letter celebrating 3 years of togetherness.

---

## Overview

This is a single-page HTML experience featuring soft animations, floating hearts, golden sparkles, a love letter card, and a 3-year timeline — all designed with an elegant pink and gold aesthetic.

---

## Features

- **Animated Background** — Shifting gradient background with blurred color circles and a shimmer overlay
- **Floating Hearts** — 12 animated hearts float upward continuously across the screen
- **Gold Sparkles** — 7 pulsing sparkle dots scattered across the background
- **Orbiting Heart Emblem** — Central emblem with 3 mini hearts orbiting around a pulsing main heart, surrounded by expanding pulse rings
- **Animated Headline** — "Happy 3rd Year Anniversary" in Great Vibes cursive with a pink-to-gold gradient
- **Name Block** — Full name and nickname displayed with elegant serif and script fonts
- **3-Year Timeline** — Visual timeline with Year One, Year Two, Year Three nodes connected by an animated flowing line
- **Love Letter Card** — Glassmorphism card with a wax-seal emblem, personal letter content, and a script sign-off
- **Couple Card** — Bottom section with couple names, infinity symbol, "Forever & Always" script, and a years badge
- **Fully Responsive** — Adapts to mobile, tablet, and desktop screen sizes
- **Reduced Motion Support** — Respects `prefers-reduced-motion` accessibility setting

---

## Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Structure and semantic markup |
| CSS3 | Animations, layout, glassmorphism effects |
| Google Fonts | Great Vibes, Cormorant Garamond, Poppins |

> No JavaScript. No external libraries. Pure HTML & CSS.

---

## Fonts Used

- **Great Vibes** — Script font for headlines, name, and sign-off
- **Cormorant Garamond** — Elegant serif for full name display
- **Poppins** — Clean sans-serif for body text and labels

---

## Color Palette

| Variable | Hex | Usage |
|---|---|---|
| `--pink` | `#ffd9e6` | Background accents |
| `--pink-soft` | `#ffe9f1` | Soft background circles |
| `--pink-deep` | `#e98bb0` | Hearts, dots, borders |
| `--pink-deeper` | `#d96b96` | Headlines, seal, sign-off |
| `--gold` | `#c9a04f` | Accent hearts, dividers |
| `--gold-light` | `#f3dca0` | Sparkles, background circles |
| `--gold-deep` | `#a9802f` | Labels, eyebrow text, badges |
| `--white` | `#fffaf8` | Base white |
| `--ink` | `#4a2c3a` | Primary text |
| `--ink-soft` | `#7a5263` | Secondary / muted text |

---

## Page Structure

```
index.html
│
├── bg-decor          → Fixed background layer (blur circles, shimmer, hearts, sparkles)
│
└── main.page         → Main content column (max-width: 420px)
    ├── hero              → Eyebrow text, emblem, headline, name block, subtitle
    ├── divider
    ├── timeline-wrap     → "Three Years of Love" timeline (Year 1 → 2 → 3)
    ├── divider
    ├── letter-card       → Love letter with seal, greeting, paragraphs, sign-off
    ├── divider
    ├── bottom-section    → Infinity symbol, "Forever & Always", couple card
    └── footer            → "Made with endless love ❤️ for Riva"
```

---

## Animations

| Animation | Element | Description |
|---|---|---|
| `gradientShift` | Body background | Slowly shifts gradient position |
| `floatUp` | Hearts (h1–h12) | Hearts rise from bottom and fade out |
| `sparklePulse` | Sparkles (s1–s7) | Sparkles pulse in and out |
| `heartbeat` | Main heart, seal, amp-heart | Double-beat heart pulse |
| `ringExpand` | Pulse rings | Rings expand outward and fade |
| `rotateOrbit` | Orbit wrapper | Mini hearts orbit continuously |
| `floatGentle` | Headline, Forever text | Gentle vertical float |
| `shimmerMove` | Shimmer overlay, couple card | Moving light sheen |
| `lineFlow` | Timeline line | Gradient flows along the line |
| `dotPulse` | Timeline dots | Dots gently scale up and down |
| `shineText` | Infinity symbol | Gradient shine sweeps across text |
| `fadeIn` | Hero, bottom section, footer | Fade in on load |
| `fadeInUp` | Name block, subtitle, cards | Slide up and fade in on load |

---

## Responsive Breakpoints

| Breakpoint | Changes |
|---|---|
| `min-width: 480px` | Larger headline, bigger nick-name, more card padding |
| `max-width: 340px` | Smaller headline, heart, nick-name, and emblem |

---

## Dedicated To

> **From:** Din Muhammad Jewel
> **To:** Sadia Tasmim Riva
> **Celebrating:** 3 Beautiful Years Together ✦

---

*Made with endless love ❤️ for Riva*
