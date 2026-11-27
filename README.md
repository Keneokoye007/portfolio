# Kene Okoye — Portfolio

A responsive, static portfolio for B2B business development and account management. English (`index.html`) and French (`fr.html`) pages share `styles.css`; no installation or build step is required. The header provides a language switcher. The downloadable CV and external contact form are shared between the two versions.

## Preview

Open `index.html` in a browser, or serve this folder with:

```sh
python -m http.server 4173 --bind 127.0.0.1
```

Then visit http://127.0.0.1:4173.

## Publish with GitHub Pages

In the repository's **Settings → Pages**, use **GitHub Actions** as the publishing source. `.github/workflows/static.yml` uploads the static files and deploys them in a separate job on each push to `main`.

The project-site address will be https://keneokoye007.github.io/portfolio/.

GitHub's setup guide: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site.

## Update

Update both language pages when changing content, edit `styles.css` for shared design changes, then push to `main`. The French version is available at https://keneokoye007.github.io/portfolio/fr.html.

The contact section links to LinkedIn and a Google Form. Download CV buttons serve the account-manager CV from `assets/documents/kene-okoye-cv.pdf`.

The portfolio includes six expertise cards, selected sales results, and Kene's portraits. Image sources are recorded in `assets/IMAGE-CREDITS.md`.
