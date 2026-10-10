# Commander Notes

A notepad for Magic: The Gathering Commander players. When a card underperforms (or you see one you love) mid-game, jot it down here instead of in the iPhone Notes app.

- Swipe through your commanders on the home screen.
- Each deck has **Cards to add** on top and **Cards to drop** below.
- Tap a card to note why (one-tap reasons or your own words), count how many times it let you down, pair a drop with an add as a swap, and see today's prices and where to buy it.
- **Quick note** jots a card into any deck in a few taps.
- Check off changes you've made; they move to the deck's History.
- **Copy list** gives you your cards to add in a format TCGplayer and Moxfield accept.

Card search, pictures and prices come from [Scryfall](https://scryfall.com/docs/api). Your notes are saved on your device; use **Backup** to save them to a file.

## Run it

Plain HTML, CSS and JavaScript. No install and no build step.

- **On a computer:** open `index.html` in a browser. Make the window narrow to see the phone layout.
- **On your phone:** turn on GitHub Pages (Settings → Pages → Deploy from a branch → `main`, `/ (root)`), then open `https://lukej16.github.io/commander-notes/` in Safari and tap **Share → Add to Home Screen**.

## Files

| File | What it does |
| --- | --- |
| `index.html` | The screens and pop-up sheets |
| `style.css` | The paper-notepad look; colors and fonts are at the top |
| `script.js` | Everything the app does; settings (like the reason chips) are at the top |
| `sw.js` | Lets the app open with no signal |
| `manifest.webmanifest`, `icon-*.png` | Name and icon for the home screen |
