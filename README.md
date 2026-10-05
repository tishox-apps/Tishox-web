# tishox.com homepage

Upload the contents of this folder to the root of tishox.com.

- `index.html`: the page
- `img/logo-on-dark.png`: Pomegranate logo for its app tile
- `media/`: Pomegranate's carousel video and poster image

## Adding the next app

Each app is one `<article class="app">` tile inside `<div class="apps">`. To add one:
1. Copy the Pomegranate `<article>` and give it its own class (for example `app--myapp`) with that app's colours in the CSS, next to `.app--pomegranate`.
2. Update the count in the Apps header (`01` → `02`).
3. Once there are two or more apps, add `grid-column: span 6` to the tiles to show them side by side, and remove the "More apps on the way" box if you like.
4. Add the app to the footer's "Apps:" line.
