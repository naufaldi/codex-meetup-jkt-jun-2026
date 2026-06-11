# Codex Meetup Deck Instructions

## Presentation Intent

- This repo is a live HTML slide presentation, not an article or document.
- Keep this deck as a single-root `index.html` presentation unless the user explicitly asks for a larger architecture refactor.
- Prefer low-density, speaker-led slides with one clear idea per slide.
- Use visual hierarchy so the audience knows what to read first, second, and third.
- Replace dense paragraph blocks with diagram assets, shapes, chips, connectors, and proof objects.
- Split dense ideas into more slides instead of shrinking text until it becomes hard to read.

## Design Rules

- Keep the fixed 1920x1080 stage behavior in `index.html`.
- Preserve the blue Codex visual system unless the deck is intentionally redesigned.
- For before/after workflow slides, use visual contrast:
  - Before Codex: scattered, manual, dashed, fragmented, looser spacing.
  - After Codex: structured, assisted, connected, glowing, clearer lanes.
- For workflow image placement:
  - Before Codex generated diagrams should sit on the right side of the content slide, with content on the left.
  - After Codex proof images/screenshots should go on the slide after the content slide so the image can be larger and easier to read.
- Never build workflow diagrams as HTML/CSS boxes or connector maps.
- Generate diagram visuals with GPT Image Gen, save them as image assets, and place those images into the slide.
- GPT Image Gen is for diagram artwork only, not for rendering an entire slide.
- Keep slide title, supporting copy, footer, counter, and layout as editable HTML/CSS.
- CSS is only for slide layout, framing, typography, and image placement, not for drawing the diagram itself.
- Do not add decorative cards that repeat the same paragraph. Let diagrams carry the detail.

## Verification

- After changing slides or deck tooling, run the deck locally with Vite:
  - First-time setup: `npm install`
  - Dev server: `npm run dev`
  - Production build check: `npm run build`
- Verify in Chrome at desktop size using the Vite local URL. The default is `http://127.0.0.1:4173`, but if Vite reports that the port is occupied, use the fallback URL printed in the terminal.
- Check direct `#slide-N` navigation, slide counter, text overflow, and visual overlap.
- Changed slides must remain readable at presentation distance.
- Vite live reload is only for faster edit feedback; it does not change the fixed-stage slide architecture.
- Vite is installed for dev/build. Vitest latest was checked during setup, but it is intentionally not installed until deck logic is extracted into testable modules.
