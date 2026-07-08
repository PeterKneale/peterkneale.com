# peterkneale.com

Personal resume and portfolio site for Peter Kneale. A static single page site deployed to GitHub Pages.

## Source of truth

`resume.md` is the canonical source for all content (experience, skills, projects, education). The site is a visualisation of it. Update `resume.md` first, then reflect the change in `public/index.html`.

## Structure

- `resume.md` — canonical resume content
- `public/` — the deployed static site
  - `index.html` — the site, self contained with inline CSS
  - `CNAME` — custom domain (peterkneale.com)
  - `.nojekyll` — disables Jekyll processing
- `.github/workflows/pages.yml` — GitHub Actions workflow that deploys `public/` to GitHub Pages on every push to `main`

## Local preview

Open `public/index.html` in a browser, or serve the folder:

```
python3 -m http.server --directory public 8000
```

## Deployment

Pushing to `main` triggers the GitHub Actions workflow, which publishes `public/` to GitHub Pages.

## Custom domain

The site serves at peterkneale.com via the `CNAME` file. DNS needs apex `A` and `AAAA` records pointing at the GitHub Pages IP addresses, plus a `www` `CNAME` record pointing at `peterkneale.github.io`.
