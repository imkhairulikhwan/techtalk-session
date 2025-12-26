<!-- filename: README.md -->
# TechTalk – Weekly Session for Knowledge Sharing

A static site hosted on GitHub Pages to list upcoming TechTalk topics.

## Deploy

1. Create a new public repo on GitHub (e.g., `techtalk`).
2. Add `index.html` (from this project) to the repo and commit.
3. In GitHub:
   - Settings → Pages
   - Source: Deploy from a branch
   - Branch: `main` (or `gh-pages`) and folder `/root`
4. Wait for the page to build. Your site will be live at:
   `https://<your-username>.github.io/<repo-name>/`

## Update sessions

Open `index.html` and edit the `sessions` array:

```js
const sessions = [
  { date: "2026-01-08", title: "Intro to TDD", speaker: "Your Name" },
  { date: "2026-01-15", title: "GraphQL in Practice", speaker: "Your Name" }
];
