# Wordgarden — Solitaire Associations

An ad-free, mobile-first word association solitaire game inspired by the category and tableau loop of Solitaire Associations Journey. It runs as a static site on GitHub Pages and can be added to a phone's home screen.

## Play

Open `index.html` in a browser or visit the hosted page. Sort six words into each of four category stacks. Only the exposed card in each tableau column and the top card in waste are playable. Draw cards from stock, move cards between columns to uncover hidden words, or spend the free Joker to auto-sort one exposed card. Every draw, category guess, and tableau move uses a turn; recycling waste, hints, and undo are free. Hard mode starts at Level 4 and progresses through nine distinct challenge packs, with no repeated category lists in the new material. Each round has a 36-turn budget. The board and level are saved on that device.

Each deal includes 24 words: 20 in four tableau columns (four face-down and one exposed in each) plus four in the draw pile. The game starts at Level 4, with four categories of six related words and a 36-turn budget. Winning advances through the nine hard challenge packs before the set cycles; the earlier introductory levels are skipped.

## Publish with GitHub Pages

In the repository, open **Settings → Pages**, select **Deploy from a branch**, choose `main` and `/ (root)`, and save. The site will be served from the repository root.

## Files

- `index.html` — game interface, category packs and rules
- `manifest.webmanifest` and `icon.svg` — installable web app metadata
- `sw.js` — offline cache for repeat play
