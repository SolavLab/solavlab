# SoBIG — solavlab.com

Jekyll site for the Solav Biomechanical Interfaces Group at Technion.

## Local preview

```
bundle exec jekyll serve
```
Then open http://localhost:4000/solavlab/

## How to update things

### Add a news post
Create a new file in `_posts/` named `YYYY-MM-DD-title.md`:

```markdown
---
layout: post
title: "Your post title"
date: 2026-09-15
image: "/assets/img/your-image.jpg"
---

Your post content here. Markdown is supported.
```

### Add / remove a team member
Edit `_data/team.yml` — add or remove a block under `current:` or `past:`.

### Update site info (email, phone, address)
Edit `_config.yml` — restart `jekyll serve` to see config changes.

### Add a publication
Edit `_data/publications.yml` (coming soon).

### Images and videos
All media live in `assets/img/`, one folder per section:
`team/`, `research/`, `news/`, `publications/`, `facilities/`, `gallery/`, `site/` (logos, hero video).
Refer to a file by its path, e.g. `photo: "/assets/img/team/zohar-oddes.jpg"`; the layouts add the
`/solavlab` prefix automatically. Keep photos under ~1600px wide / 500 KB, lowercase-dash file names,
and videos well under GitHub's 100 MB file limit.

## Deploy
Push to `main` → the GitHub Actions workflow (`.github/workflows/pages.yml`) builds and deploys
→ live at https://solavlab.github.io/solavlab/ within a couple of minutes.

### Moving solavlab.com over (when the site is ready)
1. Add a `CNAME` file containing `solavlab.com`.
2. In `_config.yml`: `url: "https://www.solavlab.com"`, `baseurl: ""`.
3. Set the custom domain in the repo's Settings → Pages, then update DNS at the registrar.
