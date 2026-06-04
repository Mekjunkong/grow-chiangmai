# Design

## Design System Overview

Grow Chiang Mai uses a tactile, field-led brand surface: warm off-white paper, soil browns, leaf greens, harvest yellow, clay, and water blue. The page should feel sunlit, practical, and handmade without becoming rustic kitsch. The design is a committed brand landing page with real farm imagery, strong typographic scale, and visible service structure.

## Color Palette

Use OKLCH color values.

- `--paper`: `oklch(0.965 0.018 83)` for warm page background.
- `--paper-deep`: `oklch(0.91 0.04 82)` for tinted panels.
- `--soil`: `oklch(0.34 0.055 58)` for primary text and grounded surfaces.
- `--leaf`: `oklch(0.47 0.11 142)` for primary actions.
- `--leaf-dark`: `oklch(0.34 0.09 144)` for hover and deep accents.
- `--harvest`: `oklch(0.82 0.13 86)` for warmth and small highlights.
- `--clay`: `oklch(0.58 0.105 42)` for secondary emphasis.
- `--water`: `oklch(0.78 0.07 205)` for camera/irrigation details.
- `--ink-muted`: `oklch(0.45 0.03 96)` for secondary copy.
- `--line`: `oklch(0.77 0.035 82)` for subtle rules.

## Typography

Use a non-reflex warm display/body pairing:

- Display: `Bricolage Grotesque`, chosen for hand-built confidence without looking like a generic eco serif.
- Body: `Atkinson Hyperlegible`, chosen for clarity and accessibility for international readers.

Avoid overly editorial serif layouts, monospace costume, and flat type scales. Hero headlines should be large and physical; body copy should stay under 75 characters per line.

## Layout

Use a long-form landing page with generous rhythm, not a centered SaaS stack. The hero should show the brand/product in the first viewport with real farm imagery and a hint of the next section. Use asymmetric compositions, field-map motifs, full-width bands, and clear horizontal rules. Cards are allowed for package choices and form containers, but avoid nested cards and repeated identical icon grids.

## Components

- Header: simple text logo, section anchors, single waitlist CTA.
- Hero: oversized headline, grounded subcopy, real farm image, domain/status badge, and founding waitlist CTA.
- How-it-works strip: five compact steps with crop/field language.
- Package comparison: three packages, with Managed Plot visually preferred.
- Field map: schematic showing plots, drip line, caretaker, compost, camera.
- Waitlist form: accessible labels, clear success/error states, consent language.
- FAQ: inline accordion-free blocks or simple details elements.

## Motion

Use subtle page-load reveals and hover feedback only. Avoid bounce or layout-property animation. Respect `prefers-reduced-motion`. Motion should feel like field notes appearing, not an app demo.

## Imagery

Use real or realistic farm/garden imagery. Hero imagery should show actual growing beds, soil, hands, vegetables, irrigation, or village farmland. Below-fold images may include vegetables, compost/soil, and Chiang Mai countryside. Do not ship abstract colored rectangles as primary media.
