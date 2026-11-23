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

### Logo files
`assets/img/site/logo/` holds the SoBIG logo (text converted to outlines, so no font is needed):
- `sobig-logo.svg` / `.png`: full logo for light backgrounds; `sobig-logo-on-navy.*` for dark backgrounds
- `sobig-logo-compact.*`: symbol + SoBIG only (small spaces, phone header)
- `*-large-text.*`: same layouts with SoBIG as tall as the symbol (posters, slides, banners)
- `sobig-symbol.svg` / `.png`, `sobig-icon.svg` / `.png` (navy rounded square): favicon, social avatars
Use the SVG files for print and posters; use PNG for Word / PowerPoint.

## Deploy
Push to `main` → the GitHub Actions workflow (`.github/workflows/pages.yml`) builds and deploys
→ live at https://www.solavlab.com/ within a couple of minutes.

### Domain
- The custom domain `www.solavlab.com` is set in the repo's Settings → Pages (no `CNAME` file is
  needed with the Actions deploy). `solavlab.com` and `solavlab.github.io/solavlab` redirect to it.
- The domain is registered at Wix, which also hosts its DNS. The website uses four A records
  (`185.199.108-111.153`) and CNAME `www` → `solavlab.github.io`.
- Email (Google Workspace) depends on the MX and SPF/verification TXT records. Never remove them
  when editing DNS.
