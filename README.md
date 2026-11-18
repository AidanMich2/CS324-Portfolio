# Software Design & Development Portfolio

Personal project portfolio for Software Design and Development (Fall 2026), built with [Hugo](https://gohugo.io/) and the [PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme.

## Structure

Each competency has its own page under `content/competencies/<category>/`. Pages start as drafts (`draft: true`) with the required questions listed — fill in the sample, contribution statement, AI disclosure, and analysis, then set `draft: false` to publish.

## Local development

```bash
hugo server -D   # -D includes drafts while writing
```

Visit http://localhost:1313/.

## Publishing

Push to `main` — the GitHub Actions workflow (`.github/workflows/hugo.yml`) builds and deploys to GitHub Pages automatically. Enable Pages in repo Settings → Pages → Source: "GitHub Actions" (one-time setup).
