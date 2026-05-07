# linkml.github.io

Source for the [linkml.io](https://linkml.io) splash page. Plain HTML and CSS — no build step, no dependencies.

## Previewing locally

Open `index.html` directly in your browser:

```bash
open index.html
```

Or double-click it in Finder. No server required.

## Making edits

| What to change | Where |
|---|---|
| Headline, description, hero copy | `index.html` — see the `HERO` section comment |
| Navigation links | `index.html` — see the `HEADER` section comment |
| Community logos, stats, ecosystem cards | `index.html` — inline comments mark each section |
| Styles, colors, layout | `css/styles.css` |
| Images and logos | `uploads/` |

## Deployment

Pushing to `master` triggers a GitHub Pages build and deploys automatically to [linkml.io](https://linkml.io). No action needed beyond merging a PR.

## File structure

```
index.html        # entire site — one file, section comments throughout
css/styles.css    # all styles
uploads/          # images and logos
CNAME             # linkml.io
.nojekyll         # disables Jekyll processing on GitHub Pages
```
