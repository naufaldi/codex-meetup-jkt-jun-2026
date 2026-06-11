# Codex Meetup JKT Jun 2026

HTML slide deck for **Using Codex in Daily Work**.

This deck uses the `frontend-slides` fixed-stage approach:

- Browser-based HTML presentation
- No PDF workflow
- Single `index.html`
- Fixed 1920x1080 slide stage
- The whole stage scales to the viewport
- Screenshots and videos can be added under `assets/`

## Open Locally

Run from this folder:

```bash
python3 -m http.server 4173
```

Then open:

```text
http://localhost:4173
```

## Controls

- Next slide: `ArrowRight`, `Space`, `PageDown`, `Enter`
- Previous slide: `ArrowLeft`, `PageUp`, `Backspace`
- First slide: `Home`
- Last slide: `End`
- Edit visible text: press `E`

## Project Structure

```text
index.html
assets/
  coding/
  non-coding/
  videos/
notes/
  outline.md
```

## Updating Assets

Each before/after slide shows a placeholder filename. Put the real screenshot or video in the matching `assets/` folder, then update the slide array inside `index.html` to render the real media.

The non-coding plugin screenshot is already available at:

```text
assets/non-coding/codex-plugins.png
```
