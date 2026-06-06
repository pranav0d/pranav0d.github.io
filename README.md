# Academic Pages — Pranav Reddy Danda

These files populate an [Academic Pages](https://github.com/academicpages/academicpages.github.io) site.

## Quick start

1. Fork the template: go to https://github.com/academicpages/academicpages.github.io, click **Use this template**, and name your repo `YOURUSERNAME.github.io` (for you, `pranav0d.github.io`).
2. Drop these files into the matching folders in your repo:
   - `_config.yml` → repo root (overwrite, then edit `url`/`repository`)
   - `_pages/about.md`, `_pages/cv.md`, `_pages/publications.md` → `_pages/`
   - `_publications/2026-energy-profiling-pruned-llms.md` → `_publications/`
   - `_data/navigation.yml` → `_data/`
3. Add a `profile.png` headshot to `images/` (referenced by the sidebar `avatar`).
4. Commit. GitHub Pages builds automatically; your site appears at `https://pranav0d.github.io`.

## Run locally (optional)

```bash
bundle install
bundle exec jekyll serve
# visit http://localhost:4000
```

## Things to update

- `_config.yml`: set `url` and `repository` to your actual GitHub Pages address; add `googlescholar`/`orcid` if you have them.
- Replace the `profile.png` avatar.
- Add a PDF of your CV to `files/` and link it if you want a downloadable version.
