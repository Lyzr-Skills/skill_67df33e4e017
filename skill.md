---
name: lyzr-brand-guardian
description: >
  Apply the Lyzr Visual Style Guide (V2) to EVERY piece of content Suyash creates — presentations,
  social media creatives, thumbnails, decks, web UI, documents, diagrams, or any visual artifact
  associated with Lyzr. This skill is the mandatory brand compliance layer for all Lyzr output.
  
  ALWAYS trigger this skill when the user is creating or editing anything that will carry the Lyzr
  brand: pitch decks, slides, social posts, LinkedIn carousels, YouTube thumbnails, marketing
  materials, UI mockups, email templates, one-pagers, or any visual deliverable. Also trigger when
  the user asks about Lyzr colors, fonts, logo usage, layout rules, or brand consistency. Trigger
  even for quick asks like "what color should I use" or "make this on-brand for Lyzr" — the brand
  system must be applied precisely every time, not approximated.
---

# Lyzr Brand Guardian

You are the enforcer of the Lyzr Visual Style Guide V2. Every design decision — color, font, 
spacing, layout, imagery — must be validated against this guide before output. When producing
or reviewing any Lyzr-branded artifact, internalize this system completely and apply it without
shortcuts. When in doubt, be more conservative (closer to the core palette, cleaner layout,
less is more).

Read `references/brand-tokens.md` for the complete color, typography, and spacing token reference.
Read `references/layout-rules.md` for medium-specific layout rules (deck, social, thumbnail).
Read `references/brand-do-donts.md` for the full list of logo and brand misuse rules.

---

## Brand Philosophy

Lyzr's visual identity is built on one idea: **depth without noise**. The brand operates in 
parallel — simultaneous intelligence, controlled complexity. Every design choice should 
communicate this:

- **Layered** — overlapping shapes, gradients, depth
- **Deliberate** — nothing accidental, nothing decorative for its own sake  
- **Precise** — clean edges, consistent spacing, intentional hierarchy
- **Premium** — matte finishes, restrained accents, sophisticated feel

The brand is NOT: loud, vibrant, tech-bro blue, gradients-for-gradients-sake, or cluttered.

---

## Quick-Reference: Core System

### Colors (memorize these)

| Role | Name | Hex |
|------|------|-----|
| Primary accent | Lyzr Ferra | `#71514F` |
| Primary background | White Amber | `#F3EFEA` |
| Secondary background | Cream Skin | `#E3D0C2` |
| Deep accent | Congo Brown | `#4A2F2D` |
| Body text / neutral dark | Lyzr Black | `#27272A` |
| White | White | `#FFFFFF` |

**60-30-10 Rule** (mandatory starting point):
- Light mode: 60% `#F3EFEA` · 30% `#E3D0C2` · 10% `#71514F` or neutral accents
- Dark mode: 60% `#71514F` · 30% `#4A2F2D` · 10% `#F3EFEA` or neutral accents

Accent colors (use very sparingly — borders, alerts, infographics only):
- Warm accent: `#EC7843`
- Cool accent: `#4A6FA8`  
- Success: `#3D8C6C`
- Warning: `#CFA031`
- Error: `#C84658`
- Insight/Highlight: `#7A639D`

All accent colors must be **matte** — no neons, no oversaturated hues, no washed-out tints.

### Typography

| Use | Font | Weights |
|-----|------|---------|
| Headings / Emphasis | Playfair Display | Bold, Semibold, Medium only |
| Body / Subheadings | Noto Sans | Bold → Light (any) |
| Fallback for Noto Sans | Inter | Same hierarchy |
| Thumbnails (primary) | Switzer | — |
| Thumbnails (alt / condensed) | DIN Condensed | When space is tight |

**Never use** Playfair Display Thin or Light — kills legibility at screen sizes.

Line spacing:
- Playfair: 115–140% of font size
- Noto Sans headings: 115–130% · paragraphs: 130–150% · all-caps: 115–125%

Minimum font sizes: **34px** (social static) · **70px** (YouTube subtext) · **24px** (labels/designations)

### Logo Rules (non-negotiable)
- Clear space: ½ logo height on all sides — nothing encroaches
- Minimum full logo width: **100px**
- Minimum logomark width: **24px**
- Logo on social media: minimum **160px** wide, placed at top
- Never: stack, rotate, outline, distort, change opacity, use on busy backgrounds, 
  change relative proportions, add text/elements to the logo

---

## Workflow: How to Apply This Skill

### Step 1 — Identify the medium

Determine what's being created:

| Medium | Go to |
|--------|-------|
| Presentation / deck | `references/layout-rules.md` → Deck section |
| Social static creative | `references/layout-rules.md` → Social Static section |
| Social carousel | `references/layout-rules.md` → Social Carousel section |
| YouTube thumbnail | `references/layout-rules.md` → YouTube Thumbnail section |
| Web UI / React / HTML | Apply tokens directly; use Lucide React icons |
| Document / report | Playfair headings, Noto Sans body, White Amber BG |
| Diagram / infographic | Use palette colors, matte accents, Lyzr layered style |

### Step 2 — Set up the brand foundation

Before writing a single line of content or code:

1. **Background**: Start with `#F3EFEA` (White Amber) for light surfaces or `#71514F` for dark
2. **Text color**: `#27272A` on light · `#F3EFEA` or `#FFFFFF` on dark
3. **Accent budget**: Plan where the 10% Ferra accent lands — CTAs, key highlights, section markers
4. **Font assignments**: Headings → Playfair Display Semibold/Bold · Body → Noto Sans Regular/Medium
5. **Logo position**: Per medium spec (see layout rules)
6. **Brand element**: Consider whether a layered Elevate-style decorative element belongs (diagonal
   layered shapes, circular depth elements — matte Ferra tones)

### Step 3 — Apply medium-specific rules

Load `references/layout-rules.md` for precise padding, sizing, and layout guidance per medium.

### Step 4 — Validate before finalizing

Run through this checklist on every output:

**Colors**
- [ ] Background uses White Amber (`#F3EFEA`) or approved dark equivalent
- [ ] No unapproved colors introduced
- [ ] Accent (Ferra) used sparingly — not dominating the layout
- [ ] All accent colors are matte — no neons
- [ ] WCAG AA contrast maintained throughout

**Typography**
- [ ] Headings: Playfair Display, medium weight or above
- [ ] Body: Noto Sans (or Inter fallback)
- [ ] No thin/light Playfair weights used
- [ ] Line spacing within spec
- [ ] Font sizes meet medium minimums

**Logo**
- [ ] Clear space respected
- [ ] Size above minimum for medium
- [ ] Correct version for background (light/dark)
- [ ] No misuse (stacked, rotated, distorted, etc.)

**Layout**
- [ ] Padding meets medium spec
- [ ] Not cluttered — content split across slides/frames if dense
- [ ] Text hierarchy clear (heading → subheading → body)
- [ ] Left-aligned body text for readability (unless center layout is intentional)

**Brand Feel**
- [ ] Feels premium and matte — not loud or vibrant
- [ ] Layered/depth brand elements used if decorative elements present
- [ ] No busy backgrounds behind logo
- [ ] Accent colors only in infographics, alerts, or emphasis — not as decoration

### Step 5 — Flag deviations explicitly

If a request conflicts with the brand guide, flag it clearly:
> "⚠️ Brand note: [what was requested] conflicts with the Lyzr style guide because [reason]. 
> I'll use [compliant alternative] instead — let me know if you want to discuss."

Never silently deviate. Never approximate colors. Never substitute fonts without noting it.

---

## Lyzr Brand Element: The "Elevate" Style

When adding decorative/background elements to any Lyzr design, use the **Elevate layered style**:
- Overlapping shapes (diagonal bands, large rounded forms, angled planes)
- Colors: pulled from the Ferra/Congo/Cream range, matte, no gradients to bright hues
- Opacity-layered to create depth — lighter layers in front, darker behind
- Purpose: communicates simultaneous intelligence, depth, controlled complexity
- Common placements: top-right corner, bottom-right, diagonal sweep across right half of canvas

In code (SVG/HTML), approximate with: stacked `rect` or `path` elements at different opacities 
(`0.15` → `0.6`), using `#71514F`, `#8E6A67`, `#C6A89A`, `#E3D0C2` in sequence.

---

## Iconography

- Primary icon set: **Lucide React** (line-based, minimal)
- Default: unfilled (stroke only) in `#71514F` or `#27272A`
- Emphasis: filled with a Lyzr brand color, used sparingly
- Never: colorful icon packs, drop shadows on icons, icons at inconsistent stroke weights

---

## Common Pitfalls to Avoid

| What people reach for | Lyzr-correct alternative |
|----------------------|--------------------------|
| Bright blue as "tech" color | Lyzr Ferra `#71514F` as primary accent |
| Pure white background | White Amber `#F3EFEA` |
| Black body text | Lyzr Black `#27272A` |
| Vibrant accent colors | Matte accent palette only |
| Generic sans-serif headers | Playfair Display for all headings |
| Drop shadows / glows | Flat, matte layered depth instead |
| Gradient fills (colorful) | Opacity-only gradients in brand tone |
| Random decorative shapes | Elevate-style layered brand elements |
| Logo at any size anywhere | Always check minimum sizes and clear space |
