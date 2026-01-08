# SimpleSample — GitHub Pages demo ✅

A minimal static site ready to publish to GitHub Pages for testing.

## What's included

- `index.html` — simple page with a small interactive button
- `styles.css` — minimal styling
- `.github/workflows/deploy.yml` — GitHub Actions workflow that publishes the site on push to `main`

## Quick deploy instructions

1. Create a new GitHub repository and push this project to the `main` branch:

```bash
git init
git add .
git commit -m "Add SimpleSample site"
git branch -M main
git remote add origin https://github.com/<your-username>/<your-repo>.git
git push -u origin main
```

2. The `deploy` workflow will run on push to `main`. After the Actions job completes, GitHub Pages will publish the site.

3. Your site URL will be: `https://<your-username>.github.io/<your-repo>/`

## Test locally

Run a simple HTTP server from the project folder:

```bash
# Python 3
python -m http.server 8000
# then open http://localhost:8000
```

---

If you'd like, I can also:

- Rename the default branch, create the repo, and push for you (if you give me the repo name), or
- Adjust the workflow to use a `gh-pages` branch instead.
