# Static portfolio bundle

This folder contains a standalone static version of the portfolio ready to be deployed to GitHub Pages.

To publish to GitHub Pages (push to the `gh-pages` branch):

```bash
cd static-portfolio
git init
git checkout -b gh-pages
git add .
git commit -m "Add static portfolio"
git remote add origin git@github.com:kaureena/portfolio.git
git push -u origin gh-pages
```

Replace the `origin` URL if you prefer HTTPS.
