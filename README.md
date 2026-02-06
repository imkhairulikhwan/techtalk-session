# TechTalk – Weekly Session for Knowledge Sharing

Static site auto-published via GitHub Pages using GitHub Actions. Update `sessions.json` and push to `main`; CI deploys automatically.

## Setup

1. Create a public repo (e.g., `techtalk`).
2. Add these files: `index.html`, `sessions.json`, `.github/workflows/deploy.yml`.
3. Push to `main`.
4. In GitHub:
   - Settings → Pages → Build and deployment → Source: GitHub Actions.
5. Wait for the workflow to finish; live URL:
   `https://imkhairulikhwan.github.io/techtalk-session/`

## Updating sessions

Edit `sessions.json` and push:

```json
[
  { "date": "2026-01-08", "title": "Intro to TDD", "speaker": "Khairul Ikhwan" },
  { "date": "2026-01-15", "title": "GraphQL in Practice", "speaker": "Saufi" }
]
