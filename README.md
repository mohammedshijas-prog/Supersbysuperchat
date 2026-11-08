# Supers

Supers is a 3D avatar maker in five greens, ready for Figma.

You build a soft character by choosing a shape, eyes, a mood, glasses and an extra, then export it with a transparent background.

## Features

- **Two styles:** Soft 3D (smooth, inflated shading with Depth and Shine controls) and Flat (fully editable vectors).
- **Palette:** Onyx `#022B1A`, Malachite `#016E41`, Emerald `#00E385`, Sea Glass `#AFF6D9`, Ice Jade `#FAFEFD`.
- **Pieces:** 9 shapes, 6 eye styles, 16 moods with a search dropdown, 6 glasses and 8 extras (beret, cap, crown, bow, party hat, sprout, bow tie, headphones).
- **Drag to place:** move the face, glasses or hat in the preview, then set their size and rotation. Arrow keys nudge the selected part.
- **Noise controls:** amount, grain size, density and tone.
- **Export:** Copy SVG (paste straight into Figma), Copy PNG, or download SVG or PNG at 512, 1024 or 2048 px. Every export has a transparent background.
- Undo and redo (⌘Z / ⇧⌘Z), plus a Save button that remembers your character in this browser.

## Run it

It's one self-contained file with no build step. Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

To host it, deploy the folder as a static site (GitHub Pages, Netlify or Vercel).
