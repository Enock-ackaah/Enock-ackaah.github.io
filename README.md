# Enock Kumi Ackaah — Academic Website

This repository contains a Quarto academic website designed for GitHub Pages.

## Updating the website

1. Edit the relevant `.qmd` file directly on GitHub or in RStudio/VS Code.
2. Commit the change to the `main` branch.
3. GitHub Actions automatically rebuilds and publishes the website.

Main files:

- `index.qmd` — homepage and highlighted work
- `research.qmd` — research interests and projects
- `publications.qmd` — articles, preprints, manuscripts, and software
- `teaching.qmd` — teaching and consulting experience
- `cv.qmd` — brief online CV
- `assets/Enock_Kumi_Ackaah_CV.pdf` — downloadable CV
- `styles.css` — colors, typography, and layout

## First publication on GitHub Pages

1. Create a public GitHub repository named `Enock-ackaah.github.io`.
2. Upload all files in this project to the repository's `main` branch.
3. Open **Settings → Pages** in the repository.
4. Under **Build and deployment**, select **GitHub Actions** as the source.
5. Open the **Actions** tab and allow the publishing workflow to finish.
6. Visit `https://enock-ackaah.github.io`.

## Previewing locally

Install Quarto, open this directory, and run:

```bash
quarto preview
```

