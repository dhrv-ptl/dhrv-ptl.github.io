# Dhruv Patel Portfolio

Static portfolio website designed for GitHub Pages deployment from the repository root.

## Files

- `index.html` contains the site content, SEO metadata, and section structure.
- `styles.css` contains the visual system, layout, responsive behavior, and theme variables.
- `script.js` adds the mobile navigation toggle, active section highlighting, current year, and reveal-on-scroll behavior.

## Customize Content

Update these areas to personalize or maintain the site:

- Name, headline, intro text, and contact details in `index.html`
- GitHub, LinkedIn, project links, and demo URLs in `index.html`
- Resume link in `index.html`
  - Current file: `assets/dhruv__resume.pdf`
  - Add your resume PDF at that path or change the link to your preferred file
- Theme colors, spacing, and typography variables in `styles.css` under `:root`

## Run Locally

No build step is required.

1. Clone the repository.
2. Open `index.html` directly in a browser.

Optional local server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy To GitHub Pages

Recommended repository name:

`dhrv-ptl.github.io`

Deployment steps:

1. Push these files to the `main` branch of your repository.
2. Open your GitHub repository.
3. Go to `Settings -> Pages`.
4. Under `Build and deployment`, choose `Deploy from a branch`.
5. Select `main` and `/root`.
6. Save and wait for GitHub Pages to publish the site.

If the repository is named `dhrv-ptl.github.io`, the cleanest default URL is:

`https://dhrv-ptl.github.io/`

## Notes

- The site works without a framework or package manager.
- It is designed to be responsive across desktop, tablet, and mobile.
- All interactions use vanilla JavaScript and remain keyboard-friendly.
- `.DS_Store` and zip artifacts should stay untracked via `.gitignore`.
