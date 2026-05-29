# Kanghwi Lee — Personal Research Website

A single-page static website prepared for deployment as a GitHub Pages user site.

## Files

```text
hwiora.github.io/
├── index.html
├── styles.css
├── .nojekyll
└── assets/
    └── cv/
        └── Kanghwi_Lee_CV.pdf   # add after final public CV review
```

The site has no external JavaScript libraries, font dependencies, or build process.

## CV link before deployment

The CV link is intentionally not shown in `index.html` until the public CV is reviewed. After the final PDF is ready:

1. Save it as `assets/cv/Kanghwi_Lee_CV.pdf`.
2. In `index.html`, locate the comment beginning `CV LINK` in the Hero section.
3. Uncomment the CV anchor element.

## Local preview

From the repository directory:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000` in a browser.

## GitHub Pages deployment

Target user-site address: `https://hwiora.github.io`

As checked on 2026-05-29, a public `hwiora/hwiora.github.io` repository was not yet present.

1. Create a repository named exactly `hwiora.github.io` under the GitHub account `hwiora`.
2. Upload or push `index.html`, `styles.css`, `.nojekyll`, and the `assets/` directory to the repository root.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select the `main` branch and the `/ (root)` folder, then save.
6. After GitHub publishes the site, open `https://hwiora.github.io`.

## Status-sensitive content

The page describes *Trajectory Variance: An Unsupervised Measure of Developmental Vocal Plasticity* as **Submitted for review to Interspeech 2026**. Update both the research card and publication entry if the status changes.
