# SoBIG — solavlab.com

Jekyll site for the Solav Biomechanical Interfaces Group at Technion.

## Local preview

```
bundle exec jekyll serve
```
Then open http://localhost:4000

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

## Deploy
Push to GitHub → GitHub Pages builds automatically → live at solavlab.com within ~60 seconds.
