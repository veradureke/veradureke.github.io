# veradureke.github.io

Personal portfolio site for [Vera Dureke](https://github.com/veradureke) — Data Science & Mathematics student at Indiana University East.

Live at: <https://veradureke.github.io>

## What's here

A single-file static site (`index.html`) with embedded CSS and JS. No build step, no dependencies — GitHub Pages serves it directly from the `main` branch.

Features:
- Light / dark theme toggle (remembers your choice)
- Project grid with category filters, linking out to every public repo
- Mobile-responsive layout
- Smooth on-scroll reveal animations

## Editing

To add a new project, open `index.html`, find the `<div class="project-grid">` block, and copy one of the existing `<a class="project-card">` cards. Each card uses:

- `data-tags="ml viz analysis web"` — space-separated; controls which filter pills show it
- `style="--card-accent:#hex"` — the accent color used on the top border, hover state, and language pill

To change the bio, edit the `#about` section. To add a social link, edit the `#contact` grid.

## Deploying

Just push to `main`. GitHub Pages picks up `index.html` automatically. No workflow file or Jekyll config needed.

If the site doesn't appear:
1. Go to repo **Settings → Pages**
2. Under **Build and deployment**, set **Source** to `Deploy from a branch`
3. Branch: `main`, folder: `/ (root)`
4. Save, then wait ~1 minute for the first build
