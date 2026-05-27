# Lyzr Layout Rules — Medium-Specific Reference

## 1. Presentation Decks

### Fonts
- Headings / Emphasis: **Playfair Display** (Bold or Semibold)
- Subheadings / Body: **Noto Sans** (Regular or Medium)

### Color Usage
- Headings, subheadings, key points: use contrast highlight (Lyzr Ferra `#71514F` on light BG)
- Body text: `#27272A` (dark on light) or `#FFFFFF` (on dark backgrounds)
- Infographics & tables: use Lyzr palette colors; adjust background opacity for clarity
- Background: White Amber `#F3EFEA` (default light) or Ferra `#71514F` (dark slides)

### Layout
- **Padding**: sufficient on all sides — never let content bleed to edge
  - Suggested: ~40–60px on content slides; more generous on title/cover slides
- **Alignment**: consistently center-aligned OR left-aligned within a deck (don't mix)
- **Suggested layout**: text left, infographic/image right
- **Text alignment within blocks**: left-aligned (especially paragraphs)
- **Information density**: limit content per slide — split dense content into multiple slides
- **Logo placement**: top corner, consistent position throughout deck

### Deck Background Styles
Two approved background approaches:
1. **Light (default)**: White Amber `#F3EFEA` with Cream Skin `#E3D0C2` accents
2. **Dark**: Ferra `#71514F` or Congo Brown `#4A2F2D` with White Amber text

Use Elevate-style layered decorative elements in right portion of slide for visual depth.
The diagonal banded style is signature — use on title slides, section breaks, end slides.

### Slide Types
- **Title slide**: logo prominent top-left, large Playfair headline, Elevate element right half
- **Content slide**: logo small top-right OR top-left, clean text/diagram layout
- **Section break**: Elevate element takes more real estate, section title in Playfair
- **End/Thank You**: mirrors title slide aesthetic

---

## 2. Social Media — Static Creative

### Logo
- Placement: **top of the creative**, prominent position
- Minimum size: **160px wide**

### Padding
- **Minimum 70px on all four sides** (no exceptions)

### Font Sizes
- Body / headline minimum: **34px**
- Secondary info (labels like "Live Webinar"): **24px minimum, 26px maximum**
- People designations: **24px minimum, 26px maximum**

### Layout Pattern
- Logo top, headline center, supporting info below, CTA button if needed
- Faces/portraits (for event creatives): large, high contrast, positioned to frame text
- Background: either White Amber light or dark Ferra — not a busy photo background

### Content Rules
- Keep headlines punchy and short
- Use Lyzr accent colors (Ferra) for CTA buttons and key label backgrounds
- Event details (date, time) should be clearly grouped and sized

---

## 3. Social Media — Carousel

### Same as static creative PLUS:
- **Padding: minimum 90px on all four sides** (more generous than static)
- Consistency across all cards: same logo position, same font sizes, same color scheme
- Card 1 is the hook — boldest headline, most visual impact
- Subsequent cards: consistent template, no layout surprises

---

## 4. YouTube Thumbnails

### Padding
- Left & Top: **100px minimum**
- Right & Bottom: **160px minimum**

### Fonts
- Primary: **Switzer** (brand font for thumbnails)
- Alternate / tight space: **DIN Condensed**
- Special emphasis: other fonts acceptable minimally — Switzer/DIN must dominate

### Font Sizes
- Title: as large as possible — big, bold, immediately readable at small sizes
  - Keep title **max 5 words** to spark curiosity
  - Enhance with arrows, colored backdrops, or highlights
- Subtext: **minimum 70px**

### Color Strategy
- **Lyzr Ferra must be prominently featured** in all thumbnails
- Use tints/shades of Ferra for visual hierarchy and depth
- Use Ferra to highlight key text or as background panel
- Supporting accent colors convey meaning: Orange (alert), Green (success/positive)
- Background: prefer **dark backgrounds** for maximum contrast and impact on YouTube feeds

### People / Faces
- Use faces large — makes thumbnails relatable and eye-catching
- Face should occupy significant portion of the thumbnail
- Ensure face is not obscured by text or graphic elements

### Background
- Add subtle depth element (can be less strict about Elevate style here — dark bg + depth texture is fine)
- For maximum impact: dark background, light/bright text = strongest contrast

### Composition Pattern (common)
```
[FACE large, right side] [TITLE large, left/center] 
[subtext panel below or overlaid]
[Lyzr Ferra panel or accent behind key text]
```

---

## 5. Web UI / React / HTML

### Color Application
```css
:root {
  --bg-primary:    #F3EFEA;
  --bg-secondary:  #E3D0C2;
  --accent:        #71514F;
  --accent-deep:   #4A2F2D;
  --text-primary:  #27272A;
  --text-inverse:  #F3EFEA;
  --white:         #FFFFFF;
}
```

### Typography
```css
font-family heading: 'Playfair Display', Georgia, serif;
font-family body:    'Noto Sans', 'Inter', system-ui, sans-serif;
```

### Component Guidelines
- Buttons (primary): Ferra background `#71514F`, White Amber text, no border-radius extreme (8–12px)
- Buttons (secondary): White Amber background, Ferra text/border
- Cards: White Amber or Cream Skin background, subtle border `#E3D0C2`
- Icons: Lucide React, unfilled by default, Ferra or Black color
- Dividers/rules: `#E3D0C2` (Cream Skin) — subtle, not harsh
- Focus states: Ferra outline at 2px, 2px offset

### Spacing
- Base unit: 8px grid
- Container padding: minimum 24px (mobile) / 40px (desktop)
- Generous whitespace — no cramped layouts

---

## 6. Documents / Reports

### Structure
- Cover: White Amber BG, Playfair Display title, Lyzr logo top-left, Elevate element accent
- Headers: Playfair Display Semibold, Ferra color `#71514F`
- Subheaders: Noto Sans Bold, `#27272A`
- Body text: Noto Sans Regular, `#27272A`, 14–16pt at 140% line height
- Tables: Cream Skin `#E3D0C2` header row, alternating `#F3EFEA`/`#FFFFFF` rows

### Callout Boxes
- Use Cream Skin background with Ferra left border (4px)
- Or use Ferra background with White Amber text for high-emphasis callouts

---

## 7. Diagrams & Infographics

### Color Usage
- Background: White Amber or transparent
- Nodes/boxes: Cream Skin with Lyzr Black text, OR Ferra with White Amber text
- Connecting lines/arrows: `#71514F` (Ferra) or `#27272A`
- Accent data elements: use matte accent palette sparingly for differentiation
- No rainbow color coding — use the tonal scale for differentiation

### Style
- Flat design, no drop shadows, no 3D effects
- Lucide React icons for node decoration
- Consistent stroke weights throughout
- For flow diagrams: rounded rectangles preferred over sharp corners
- Layer depth using opacity, not z-fighting colors
