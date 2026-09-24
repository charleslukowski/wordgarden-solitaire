# Wordgarden — Solitaire Associations

An ad-free, mobile-first word association solitaire game inspired by the category and tableau loop of Solitaire Associations Journey. It runs as a static site on GitHub Pages and can be added to a phone's home screen.

## Play

Each hard level has 15 category families with varied sizes. The five crown spaces above the columns hold category cards; complete a family to free its crown. Five free cells at the top temporarily hold exposed cards, like FreeCell. The other category cards are mixed into the draw pile. Only exposed column cards, the top waste card, and held free-cell cards can be played. Draws, category placements, matches, wrong guesses, tableau moves, free-cell moves, and hints spend turns. Undo costs a turn without refunding the action; recycling waste is free. The one-use Joker sorts a playable word for free. The board and level are saved on that device.

Hard mode starts at Level 4 and contains six substantial rounds with 90 unique category families, drawn from the existing hard set plus 18 new families. Group sizes vary from 3 to 8 items. After the sixth level, the game offers a deliberate replay instead of silently repeating categories.

## Publish with GitHub Pages

In the repository, open **Settings → Pages**, select **Deploy from a branch**, choose `main` and `/ (root)`, and save. The site will be served from the repository root.

## Files

- `index.html` — game interface, category packs and rules
- `manifest.webmanifest` and `icon.svg` — installable web app metadata
- `sw.js` — offline cache for repeat play
