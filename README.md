# Codex Meetup JKT Jun 2026

HTML slide deck for **Using Codex in Daily Work**.

This deck uses the `frontend-slides` fixed-stage approach:

- Browser-based HTML presentation
- No PDF workflow
- Single `index.html`
- Fixed 1920x1080 slide stage
- The whole stage scales to the viewport
- Vite dev server for live reload while editing
- Screenshots and videos can be added under `assets/`

## Open Locally

Install dependencies once:

```bash
npm install
```

Start the Vite dev server:

```bash
npm run dev
```

Then open:

```text
http://127.0.0.1:4173
```

Vite watches the root `index.html` and asset files, then refreshes the browser when edits are saved. The deck stays a single HTML presentation; Vite is only the local dev and production build wrapper.

## Build And Preview

Build the static output:

```bash
npm run build
```

Preview the production build locally:

```bash
npm run preview
```

Netlify builds with `npm run build` and publishes `dist/`.

## Controls

- Next slide: `ArrowRight`, `Space`, `PageDown`, `Enter`
- Previous slide: `ArrowLeft`, `PageUp`, `Backspace`
- First slide: `Home`
- Last slide: `End`
- Edit visible text: press `E`

## Project Structure

```text
index.html
package.json
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
