# veradureke.github.io

Personal portfolio site for [Vera Dureke](https://github.com/veradureke) — Business Intelligence Analyst at Presidio, incoming PhD student in Computer Science at UIC, and incoming AI VR Intern at NASA Glenn Research Center.

Live at: <https://veradureke.github.io>

## What's here

A static site, no build step, no dependencies — GitHub Pages serves it directly from `main`.

- `index.html` — page structure and content (hero, about, experience timeline, project grid, contact)
- `styles.css` — all styling, including the light/dark theme
- `README.md` — this file

## Editing

To update the bio: edit the `#about` section in `index.html`.

To add a new role on the experience timeline: copy one of the existing `<div class="tl-item">` blocks and tweak the role name, dates, and description. The `--tl-color:` style controls the dot and accent color.

To add a new project: copy one of the existing `<a class="project-card">` blocks. Each card uses:
- `data-tags="ml viz analysis web"` — space-separated; controls which filter pills show it
- `style="--card-accent:#hex"` — accent color for the top border, hover state, and language pill

## Deploying

Push both `index.html` and `styles.css` to `main`. GitHub Pages picks them up automatically.

If the site doesn't appear:
1. Repo **Settings → Pages**
2. Under **Build and deployment**, set **Source** to `Deploy from a branch`
3. Branch: `main`, folder: `/ (root)`
4. Save, then wait ~1 minute for the first build
