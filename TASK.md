Build a single-file `index.html` sacred geometry generator web app.

## Requirements

### Patterns (selectable via sidebar)
1. Flower of Life — overlapping circles in hexagonal grid
2. Metatron's Cube — Flower of Life + all internal lines connecting circle centers
3. Sri Yantra — 9 interlocking triangles forming 43 sub-triangles
4. Vesica Piscis — two overlapping circles, ratio sqrt(3)
5. Golden Spiral — Fibonacci-based logarithmic spiral
6. Seed of Life — 7 circles (center + 6 around)

### Controls (sidebar)
- Pattern selector (buttons or dropdown)
- Size/scale slider
- Iterations/complexity slider (where applicable)
- Line color picker (default: #6c63ff purple)
- Background color picker (default: #0f0f23 dark)
- Line width slider
- Show/hide labels toggle

### Export
- Download as SVG button
- Download as PNG button (use canvas)
- Copy embed code button (<svg>...</svg>)

### Design
- Full dark theme: background #0f0f23, accent #6c63ff
- Left sidebar (300px) with controls, right = canvas area
- Responsive — stacks on mobile
- Font: system-ui / Inter
- Subtle animations: pattern fades in on change

### CTA (bottom of sidebar)
"Love this pattern? Get it as a museum-quality archival print."
Link: https://mysticmasterpieces.com
Button style: outlined, purple

### Tech
- Pure vanilla JS + Canvas/SVG — zero dependencies
- All in one index.html file
- GitHub Pages compatible (static)
- Clean, commented code

### Extra polish
- Each pattern shows a 1-line esoteric description below the selector
- Page title: "Sacred Geometry Generator — @ChanneledCode"
- Meta description for SEO
- GitHub link in footer: github.com/ChanneledCode/sacred-geometry-generator
