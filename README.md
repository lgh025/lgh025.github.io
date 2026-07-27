# Guanghui Liu — GitHub Pages Portfolio

A responsive one-page professional website inspired by the structure of the reference site, but redesigned as an original portfolio for bioinformatics, biomedical AI, data science, and machine-learning engineering roles.

## Preview locally

```bash
cd guanghui-liu-github-pages
python3 -m http.server 8000
```

Open `http://localhost:8000`.

## Publish with GitHub Pages

### Option A — Personal homepage

1. Create a GitHub repository named exactly:

   `YOUR_GITHUB_USERNAME.github.io`

2. Upload all files from this folder to the repository root.
3. Commit and push to the `main` branch.
4. In GitHub, open **Settings → Pages**.
5. Under **Build and deployment**, select **Deploy from a branch**.
6. Select branch `main` and folder `/ (root)`, then save.
7. Your site will be available at:

   `https://YOUR_GITHUB_USERNAME.github.io/`

### Option B — Project site

Use any repository name, for example `portfolio`, and publish the `main` branch root. The address will be:

`https://YOUR_GITHUB_USERNAME.github.io/portfolio/`

## Recommended edits before publishing

- Replace `assets/img/avatar.svg` with a professional headshot named `profile.jpg`, then update the image path in `index.html`.
- Add your preferred public email address in the Contact section.
- Add a PDF resume to `assets/Guanghui_Liu_Resume.pdf`, then add a Resume button.
- Replace or expand project descriptions with exact GitHub repository links.
- Review all dates and publication details against your current LinkedIn profile/CV.
- Change “15+ years” if you prefer a different positioning statement.

## Files

- `index.html` — all page content and metadata
- `assets/css/style.css` — layout, visual design, and responsive behavior
- `assets/js/main.js` — mobile navigation, animations, and current year
- `assets/img/avatar.svg` — temporary initials graphic
- `.nojekyll` — tells GitHub Pages to publish the static files directly

## Custom domain

After buying a domain, add it in **Settings → Pages → Custom domain**. GitHub will provide the DNS records to configure with your domain registrar.
