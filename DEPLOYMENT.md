# Deploying to GitHub Pages (User Site)

This site is designed for the GitHub user site: `dagon575.github.io`.

## One-time setup

1. Create (or clone) repo named `dagon575.github.io` on GitHub.
2. Add the `CNAME` file with:

```text
www.cyniccafe.top
```

1. In the repository settings → Pages, set the custom domain to `www.cyniccafe.top`.
2. Point DNS CNAME record for `www` to `dagon575.github.io`.

## Deploy steps

```bash
# from repository root
git add .
git commit -m "Add static homepage"
git branch -M main
# if local repo not connected yet
# git remote add origin git@github.com:dagon575/dagon575.github.io.git
# push
git push -u origin main
```

Changes should be live within ~30-60 seconds.
