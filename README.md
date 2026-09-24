# Wordgarden — Solitaire Associations

An ad-free, mobile-first word association solitaire game inspired by the category and tableau loop of Solitaire Associations Journey. It runs as a static site on GitHub Pages and can be added to a phone's home screen.

## Play

Open `index.html` in a browser or visit the hosted page. Each hard level has 15 different category families with varied sizes, five empty category spaces at the top, and a five-column tableau. Five hidden gold category anchors start at the head of the columns; the other ten are mixed into the draw pile. Reveal and place a category anchor before sorting its words. Completing a family frees its slot for the next one. Only the exposed card in each column and the top card in waste are playable. Draws, category placements, matches, wrong guesses, tableau moves, and hints spend turns. Undo costs a turn without refunding the action; recycling waste is free. The one-use Joker sorts a playable word for free. The move budget scales with each deal, leaving a small margin for mistakes. The board and level are saved on that device.

Hard mode starts at Level 4 and contains six substantial rounds with 90 unique category families, drawn from the existing hard set plus 18 new families. Group sizes vary from 3 to 8 items. After the sixth level, the game offers a deliberate replay instead of silently repeating categories. Older saves keep their sorted cards and points when migrated; new families are added to their current round.
## Publish with GitHub Pages

In the repository, open **Settings → Pages**, select **Deploy from a branch**, choose `main` and `/ (root)`, and save. The site will be served from the repository root.

## Files

- `index.html` — game interface, category packs and rules
- `manifest.webmanifest` and `icon.svg` — installable web app metadata
- `sw.js` — offline cache for repeat play
