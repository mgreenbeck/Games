# Games

One-thumb phone games, each a single self-contained HTML file.

| Game | Folder | What it is |
|------|--------|-----------|
| Star Thumb | [`star-thumb/`](star-thumb/) | Galaga-style space shooter |
| Dead Thumb | [`dead-thumb/`](dead-thumb/) | Zombie shooter with gun progression and pistol partners |
| Orbit Flip | [`orbit-flip/`](orbit-flip/) | Tap to flip between two rings, grab stars, dodge spikes |

`index.html` at the root is the games page: a Play button and Share and Copy link buttons for each game, plus a button to share the whole page.

Orbit Flip's `index.html` is a plain HTML version that plays on its own. `orbit-flip/Main.dc.html` is the original source from Claude's design canvas.

## Play

Open any `index.html` in a phone or desktop browser. No build step and no dependencies.

To host them free, turn on GitHub Pages (Settings → Pages → Deploy from branch → `main` / root). The menu will then be at `https://mgreenbeck.github.io/Games/`.
