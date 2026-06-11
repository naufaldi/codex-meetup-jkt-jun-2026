# Codex Meetup Deck Design Notes

## Source Image

Reference image:

`/Users/naufaldi.satriya/Downloads/codex-img.png`

Project copy:

`assets/backgrounds/codex-img.png`

The image is a luminous blue/purple macro texture. It is used as a full-deck background source with a blue overlay, not as repeated content inside slides.

## Sampled Palette

- Deep blue: `#242cac`
- Blue base: `#2f58d7`
- Primary violet-blue: `#5d61ea`
- Secondary violet: `#8b72f5`
- Soft accent: `#a5c5f5`
- Glow/near-white: `#d3dcf2`
- Pale lavender: `#e4e3f3`

## Chosen Tokens

- `--stage-bg`: `#1729a8`
- `--slide-bg`: `#203fd0`
- `--primary`: `#5d61ea`
- `--secondary`: `#8b72f5`
- `--accent`: `#a5c5f5`
- `--glow`: `#d3dcf2`
- `--ink`: `#f7f9ff`
- `--muted`: `#d7def8`
- `--panel`: `rgba(18, 35, 150, 0.34)`
- `--panel-strong`: `rgba(21, 35, 130, 0.58)`
- `--before`: `#e4e3f3`
- `--after`: `#a5c5f5`

## Background Treatment

Each slide uses the reference image with:

- `background-size: cover`
- `background-position: center`
- blue overlay gradients for readability
- subtle grid and glow overlays for the professional tech meetup feel

## Accessibility Rule

Use white or near-white text over deep translucent blue panels. Avoid putting small text directly over bright image areas. When adding screenshots or videos, keep them inside the existing glass panels so contrast remains stable.

## Workflow Slide Redesign

Planning and PRD/RFC workflow slides should feel like live presentation slides, not article pages.

- Density: low-density, speaker-led, one idea per slide.
- Before Codex: scattered/manual flow with loose nodes, dashed connectors, and visible uncertainty.
- After Codex: structured Codex-assisted flow with clear lanes, glowing connectors, and output chips.
- Visual method: workflow diagrams must be generated with GPT Image Gen and saved as image assets. Generate diagram artwork only, not entire slide screenshots. Keep slide title, supporting copy, footer, counter, and layout as editable HTML/CSS. Do not draw workflow diagrams with HTML/CSS boxes or connector maps; CSS is only for layout, framing, typography, and image placement.
- Reading order: big claim first, short support sentence second, diagram third.
- Overflow rule: split content into additional slides instead of shrinking text below comfortable presentation size.

Reference principles used for this redesign:

- BrightCarbon visual hierarchy: guide the audience through ordered steps.
- Figma presentation ideas: keep a cohesive two-tone visual system.
- Storytelling With Data makeover: reduce clutter and make the main message obvious.
