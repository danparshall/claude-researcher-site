# claude-researcher-site

Lightweight static site for [`claude_researcher`](https://github.com/danparshall/claude_researcher) — a human-facing landing page for people who would be put off by GitHub.

Built on the [`simple_academic_website`](https://github.com/danparshall/simple_academic_website) template: plain HTML/CSS, no JavaScript, no build tools.

## Pages

- `index.html` — home, derived from the upstream `claude_researcher` README
- `background.html` — long-form background and tips, derived from upstream `HUMANS.md`
- `resources.html` — adjacent projects, Claude usage references, related templates

## Updating

When upstream `claude_researcher` changes its README or `HUMANS.md` substantively, mirror the change here by hand. There's no auto-sync — the site is a curated human-facing surface, not a copy.

## Hosting

Static; serve from anywhere. If you want GitHub Pages, enable it in repo Settings → Pages → Source: `main` branch, `/` root.
