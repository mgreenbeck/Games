# Games

One-thumb phone games, each a single self-contained HTML file.

| Game | Folder | What it is |
|------|--------|-----------|
| Star Thumb | [`star-thumb/`](star-thumb/) | Galaga-style space shooter |
| Dead Thumb | [`dead-thumb/`](dead-thumb/) | Zombie shooter with gun progression and pistol partners |
| Orbit Flip | [`orbit-flip/`](orbit-flip/) | Tap to flip between two rings, grab stars, dodge spikes (source only, see below) |

`index.html` at the root is a simple menu linking to both.

Orbit Flip is saved as its source from Claude's design canvas (`orbit-flip/Main.dc.html`). It needs that canvas to run, so it doesn't play on its own yet and isn't on the menu.

## Play

Open any `index.html` in a phone or desktop browser. No build step and no dependencies.

To host them free, turn on GitHub Pages (Settings → Pages → Deploy from branch → `main` / root). The menu will then be at `https://mgreenbeck.github.io/Games/`.
