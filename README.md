# Bcwxo Blog

This blog is built with Zensical and deployed via GitHub Pages.

## Local preview

```bash
cd /home/bcwxo/projects/my-blog
source .venv/bin/activate
zensical serve
```

Open `http://localhost:8000`.

## Build

```bash
cd /home/bcwxo/projects/my-blog
source .venv/bin/activate
zensical build --clean
```

## Deploy

1. Update `site_url` in `zensical.toml` with your real GitHub Pages URL.
2. Push repository to GitHub (default branch: `main`).
3. In GitHub repo settings, enable Pages with source set to `GitHub Actions`.

The workflow is already defined in `.github/workflows/docs.yml`.
