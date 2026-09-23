# Wordgarden

A small, ad-free mobile word-association solitaire game built as a static site. It runs on GitHub Pages and can be added to a phone's home screen.

## Play

Open `index.html` in a browser or publish the repository with GitHub Pages. Tap a face-up word card, then its matching family. Tap a selected card and an empty tableau column to reposition it. The game remembers the board and level on that device.

## Publish with GitHub Pages

In the repository, open **Settings → Pages**, select **Deploy from a branch**, choose `main` and `/ (root)`, and save. The site will be served from the repository root.

## Files

- `index.html` — game interface, data and logic
- `manifest.webmanifest` and `icon.svg` — installable web app metadata
- `sw.js` — offline cache for repeat play
