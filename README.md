# Wordgarden — Solitaire Associations

An ad-free, mobile-first word association solitaire game inspired by the category and tableau loop of Solitaire Associations Journey. It runs as a static site on GitHub Pages and can be added to a phone's home screen.

## Play

Open `index.html` in a browser or visit the hosted page. Sort six words into each of four category stacks. The five tableau columns carry both face-down word cards and category cards, so category targets sit directly in the card layout. Only the exposed word in each column and the top card in waste are playable. Draw cards from stock, move cards between columns to uncover hidden words, or use the one-use free Joker to auto-sort an exposed card. Draws, matches, wrong guesses, tableau moves, and hints spend turns. Undo costs a turn without refunding the action; recycling waste is free. Hard mode starts at Level 4 and progresses through 18 distinct hard challenge packs with 72 category sets and no repeated category names or card words in the new material. Each round has a 31-turn budget. This gives a clean sort only three spare turns without the Joker, so mistakes and detours need to be chosen carefully. The board and level are saved on that device.

Each deal includes 24 words: 20 in five tableau columns (three face-down and one exposed in each) plus four in the draw pile. Four category targets sit at the foot of the first four columns; completed categories move into the four foundation slots in the header. The game starts at Level 4, with four categories of six related words and a 31-turn budget. Winning advances through the 18 hard challenge packs before the set cycles; the earlier introductory levels are skipped.

## Publish with GitHub Pages

In the repository, open **Settings → Pages**, select **Deploy from a branch**, choose `main` and `/ (root)`, and save. The site will be served from the repository root.

## Files

- `index.html` — game interface, category packs and rules
- `manifest.webmanifest` and `icon.svg` — installable web app metadata
- `sw.js` — offline cache for repeat play
