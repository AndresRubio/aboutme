# aboutme

My CV, as a static page. Live at **https://andresrubio.github.io/aboutme/**

## What's here

| File | Purpose |
| --- | --- |
| `index.html` | The whole CV. Content lives in the markup — edit it here. |
| `style.css` | Single stylesheet. Light/dark via `prefers-color-scheme`, plus a print stylesheet. |
| `.github/workflows/deploy.yml` | Publishes to GitHub Pages on every push to `main`. |
| `.nojekyll` | Stops GitHub running Jekyll over the files. |

No build step, no dependencies. Open `index.html` in a browser to preview.

## Updating

Edit `index.html`, commit, push to `main`. The Action redeploys in about a minute.

## PDF

There's no PDF in the repo — printing the page (Cmd/Ctrl-P) produces a clean,
paginated CV from the print stylesheet, so it can never drift from the web version.
