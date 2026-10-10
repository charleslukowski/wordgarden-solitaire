# Wordgarden — Solitaire Associations

An ad-free, mobile-first word association solitaire game inspired by the category and tableau loop of Solitaire Associations Journey. It runs as a static site on GitHub Pages and can be added to a phone's home screen.

## Play

Each level hides a few categories. Every category has a crown card and a set of word cards, all shuffled into the columns and the draw pile.

- Only the bottom card of each column can be played. Moving it uncovers the face-down card above.
- Tap a crown card to put it in an empty crown slot at the top, then tap matching word cards to collect them. A full category clears and frees its slot.
- A word card can go on another word from the same category, or into an empty column. A run of same-category cards moves together.
- Tap the draw pile to turn over a card. Every draw and move costs one move; turning the pile over is free. Undo costs a move, and the Joker plays one card for free.
- Clear every category before the moves run out.

There are six levels. They start with 3 categories and 3 crown slots and build to 5 categories competing for 3–4 slots with fewer spare moves. Each deal is checked by a built-in solver before it is shown, and the move budget is the solver's move count plus that level's spare moves, so every deal can be won.

## Publish with GitHub Pages

In the repository, open **Settings → Pages**, select **Deploy from a branch**, choose `main` and `/ (root)`, and save. The site will be served from the repository root.

## Files

- `index.html` — game interface, category packs and rules
- `manifest.webmanifest` and `icon.svg` — installable web app metadata
- `sw.js` — offline cache for repeat play
