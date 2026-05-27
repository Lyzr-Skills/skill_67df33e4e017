# Lyzr Brand Tokens — Complete Reference

## Color Tokens

### Primary Palette

```
--lyzr-ferra:        #71514F   /* Primary accent — CTAs, highlights, key elements */
--lyzr-white-amber:  #F3EFEA   /* Primary background — light canvas */
--lyzr-cream-skin:   #E3D0C2   /* Secondary background — panels, cards */
--lyzr-congo-brown:  #4A2F2D   /* Deep accent — dark backgrounds, depth */
--lyzr-black:        #27272A   /* Body text, neutrals */
--white:             #FFFFFF
```

### Extended Tonal Scale (Ferra family)
The full brand ramp from white to near-black through the Ferra family. Use these for gradients,
layered elements, tints, and shades. All values are matte.

```
0:    #FFFFFF
0.125:#FBF9F7
0.25: #F3EFEA   ← White Amber (primary BG)
0.5:  #F0E9E3
1:    #ECE2DA
1.5:  #E8DACF
2:    #E3D0C2   ← Cream Skin (secondary BG)
3:    #DEC6B6
4:    #D2B7A8
5:    #C6A89A
6:    #BA998D
7:    #AE8A80
8:    #9E7A73
9:    #8E6A67
10:   #7F5D5A
11:   #71514F   ← Lyzr Ferra (primary accent)
11.5: #5E403E
12:   #4A2F2D   ← Congo Brown (deep accent)
13:   #351D1C
14:   #1F1010
```

### Accent Colors (use very sparingly)

```
--accent-warm:     #EC7843   /* Warm highlights, energy */
--accent-cool:     #4A6FA8   /* Cool highlights, technical emphasis */
--success:         #3D8C6C
--warning:         #CFA031
--error:           #C84658
--insight:         #7A639D   /* Insight, highlight, special callouts */
```

Usage rules for accents:
- Apply through opacity, borders, or subtle fills only
- Never as a dominant background color
- Only in infographics, data viz, alert states, or emphasis
- All must remain matte — no saturated/neon variants allowed
- New accent colors (if ever needed) must be matte to match palette tone

### 60-30-10 Combinations

**Light theme (default):**
```
60% → #F3EFEA  (White Amber)
30% → #E3D0C2  (Cream Skin)
10% → #71514F  (Lyzr Ferra) or neutral accents
Neutral support: #27272A, #FFFFFF
```

**Dark theme:**
```
60% → #71514F  (Lyzr Ferra)
30% → #4A2F2D  (Congo Brown)
10% → #F3EFEA  (White Amber) or neutral accents
Neutral support: #27272A, #FFFFFF
```

### Contrast / Safe Pairs (WCAG AA+)

| Foreground | Background | Level |
|-----------|-----------|-------|
| `#F3EFEA` or `#FFFFFF` | `#71514F` | AAA |
| `#F3EFEA` or `#FFFFFF` | `#4A2F2D` | AAA |
| `#F3EFEA` or `#FFFFFF` | `#27272A` | AAA |
| `#27272A` or `#71514F` | `#F3EFEA` | AAA |
| `#27272A` or `#71514F` | `#E3D0C2` | AAA |
| `#FFFFFF` | `#4A6FA8` | AA |
| `#27272A` | `#CFA031` | AA |
| `#FFFFFF` | `#C84658` | AA |
| `#FFFFFF` | `#3D8C6C` | AA |
| `#FFFFFF` | `#7A639D` | AA |

---

## Typography Tokens

### Fonts

```
--font-heading:    'Playfair Display', Georgia, serif
--font-body:       'Noto Sans', 'Inter', system-ui, sans-serif
--font-thumbnail:  'Switzer', 'Noto Sans', sans-serif
--font-condensed:  'DIN Condensed', 'Noto Sans Condensed', sans-serif  /* thumbnails only */
```

### Weight Rules

```
Playfair Display:
  --font-weight-heading-bold:     700  /* Primary heading */
  --font-weight-heading-semibold: 600  /* Section heading */
  --font-weight-heading-medium:   500  /* Subheading, emphasis */
  /* NEVER USE: 300 (light), 400 (regular) — too thin for screens */

Noto Sans:
  --font-weight-bold:     700
  --font-weight-semibold: 600
  --font-weight-medium:   500
  --font-weight-regular:  400
  --font-weight-light:    300  /* Body only, never headings */
```

### Line Spacing

```
Playfair:
  --line-height-heading: 1.2   /* 120% — tight, impactful */
  --line-height-display: 1.15  /* 115% minimum */
  --line-height-max:     1.4   /* 140% maximum */

Noto Sans:
  --line-height-heading:   1.2   /* 120% */
  --line-height-paragraph: 1.4   /* 140% */
  --line-height-all-caps:  1.2   /* 120% */
  /* Range: 115% minimum, 150% maximum */
```

### Minimum Font Sizes by Medium

```
Social static creative:    34px (body/headlines) · 24px (labels, designations) · 26px (label max)
Social carousel:           34px (body) · 24px (labels)
YouTube thumbnails:        70px (subtext minimum) · title: as large as possible
Presentation/deck slides:  No hard minimum, but maintain clear visual hierarchy
Web/UI:                    12px minimum (14px+ recommended for body)
```

### Hierarchy Pattern

```
H1 / Slide Title / Display:  Playfair Display Bold, largest size
H2 / Section Header:         Playfair Display Semibold OR Noto Sans Bold
H3 / Subheading:             Noto Sans Semibold or Medium
Body:                        Noto Sans Regular (400)
Caption / Label:             Noto Sans Light or Regular, smaller size
```

---

## Spacing Tokens

### Logo Clear Space
```
Minimum clear space = ½ × logo height on ALL sides
Full logo minimum width:  100px
Logomark minimum width:    24px
Social media logo minimum: 160px wide
```

### Social Media Padding

```
Static creative (posts):
  --padding-social-static: 70px minimum all sides

Carousel:
  --padding-social-carousel: 90px minimum all sides
```

### YouTube Thumbnail Padding

```
--padding-yt-left-top:    100px minimum
--padding-yt-right-bottom: 160px minimum
```

### Deck / Presentation
```
Sufficient padding all sides (no hard px value — maintain visual breathing room)
Suggested: ~40-60px on content slides, more on title/section slides
```

---

## Brand Element: Elevate Layered Style

The signature Lyzr decorative element. Use for backgrounds, corner accents, section breaks.

### Visual Description
- Overlapping diagonal bands OR large rounded/circular forms
- Colors: drawn from the Ferra tonal ramp (steps 1–13 above)
- Opacity-layered: darkest layer at ~0.8, lighter layers at ~0.2–0.4
- Shape: angled planes (diagonal), rounded blobs, chevron/arrow-like forms
- Placement: typically top-right or bottom-right corner; sometimes full diagonal sweep

### Color Order for Layers (light to dark)

For a diagonal sweep going from top-right to bottom-right:
```
Layer 1 (outermost/lightest): #DEC6B6 at 20% opacity
Layer 2:                      #C6A89A at 30% opacity  
Layer 3:                      #9E7A73 at 45% opacity
Layer 4:                      #7F5D5A at 60% opacity
Layer 5 (innermost/darkest):  #4A2F2D at 80% opacity
```

For a dark-background Elevate element (light layering):
```
Layer 1: #E3D0C2 at 15% opacity
Layer 2: #C6A89A at 25% opacity
Layer 3: #9E7A73 at 35% opacity
...
```

### SVG Approximation Pattern

```html
<!-- Diagonal layered sweep, top-right corner -->
<g opacity="1">
  <rect transform="rotate(-30)" fill="#DEC6B6" opacity="0.20" ... />
  <rect transform="rotate(-30)" fill="#C6A89A" opacity="0.30" ... />
  <rect transform="rotate(-30)" fill="#9E7A73" opacity="0.45" ... />
  <rect transform="rotate(-30)" fill="#71514F" opacity="0.60" ... />
  <rect transform="rotate(-30)" fill="#4A2F2D" opacity="0.80" ... />
</g>
```

Use `clip-path` to constrain to canvas bounds.

---

## Iconography

```
Icon set:   Lucide React (primary, always preferred)
Style:      Line-based, 1.5px stroke, no fill by default
Default color: #71514F (Ferra) or #27272A (Black)
Emphasis:   Fill with brand color — used SPARINGLY
Never:      Drop shadows, glows, colorful packs, inconsistent stroke weights
```
