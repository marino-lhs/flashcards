# Around the World: Music Terms and Symbols

A flash card game for the classroom. It shows one music symbol or term at a time on a projected screen. The teacher decides whether each answer is right, so the cards show no answers.

The whole app is one file: `index.html`. It has no build step and no dependencies to install.

## How to play

- **Next card** (or Space / →) deals a random card. Cards do not repeat within a game.
- **New game** (or N) reshuffles every card back into the deck.
- **⛶** (or F) toggles full screen.

The deck has 66 cards: 40 symbols and 26 terms.

## Editing cards

**Edit cards** lets anyone add, change, or delete cards. A card can be text or an uploaded picture.

Changes are saved in the browser's local storage. They stay on that browser on that computer only. They never change `index.html` or the deck other people see.

- Another computer or browser shows the original deck.
- Clearing browser data erases the changes.
- Private or incognito windows lose changes when the window closes.
- **Restore original deck** erases this browser's changes.

## Publishing with GitHub Pages

1. Upload `index.html` and the other files to the repository.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set the source to **Deploy from a branch**. Choose `main` and `/ (root)`.
4. Save. The site appears at `https://<username>.github.io/<repository>/` after a minute or two.

Saved edits are tied to the web address. Edits made on one address do not appear on another.

## Changing the built-in deck

Open `index.html` in a text editor.

- Term cards are in the `WORDS` list.
- Symbol cards are in the `SYMBOLS` list. Each one is drawn in code from music font outlines.

## Credits

- Music symbols are outlines from the [Bravura](https://github.com/steinbergmedia/bravura) font by Steinberg Media Technologies. Bravura is licensed under the SIL Open Font License 1.1. See `OFL-Bravura.txt`.
- Text uses [Atkinson Hyperlegible](https://fonts.google.com/specimen/Atkinson+Hyperlegible), loaded from Google Fonts. If it cannot load, the page uses the system font.
