# Wordgarden — Solitaire Associations

An ad-free, mobile-first word association solitaire game inspired by the category and tableau loop of Solitaire Associations Journey. It runs as a static site on GitHub Pages and can be added to a phone's home screen.

## Play

Open `index.html` in a browser or visit the hosted page. Build four category stacks by sorting their six word cards. Only the exposed card in each tableau column and the top card in waste are playable. Draw cards from stock, move cards between columns to uncover hidden words, or spend the free Joker to auto-sort one exposed card. Every draw, category guess, and tableau move uses a turn; recycling waste, hints, and undo are free. The board and level are saved on that device.

Each deal includes 24 words, four face-down tableau cards per column, and eight stock cards. Category labels are shown to make the game easier to learn on a phone.

## Publish with GitHub Pages

In the repository, open **Settings → Pages**, select **Deploy from a branch**, choose `main` and `/ (root)`, and save. The site will be served from the repository root.

## Files

- `index.html` — game interface, category packs and rules
- `manifest.webmanifest` and `icon.svg` — installable web app metadata
- `sw.js` — offline cache for repeat play
