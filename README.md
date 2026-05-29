# GitHub Pages update: CV link and manuscript proof links

Upload the contents of this folder to the root of the `hwiora.github.io` repository.

## Files added or replaced

- `index.html` - updates the CV path, removes the Applied Sciences special-issue note, and adds the Trajectory Variance submitted-manuscript links.
- `styles.css` - retained from the current site package.
- `.nojekyll` - keeps GitHub Pages on a simple static-file path.
- `assets/cv/Kanghwi_Lee_CV Public.pdf` - current public CV PDF.
- `assets/papers/Lee_COSYNE2024_Extended_Abstract.pdf` - COSYNE extended abstract.
- `assets/papers/Lee_Trajectory_Variance_Interspeech2026_Submitted.pdf` - submitted Interspeech manuscript.

## Remove obsolete file after uploading

Delete `assets/cv/Kanghwi_Lee_CV.pdf` from the repository after the new CV link is live. Otherwise the old direct URL may remain publicly accessible even though it is no longer linked from the site.

## Expected live checks after deployment

- The `CV` button opens `assets/cv/Kanghwi_Lee_CV%20Public.pdf`.
- The first research card no longer displays the special-issue note.
- The Trajectory Variance research card and submitted-publication entry each include a `Submitted Manuscript` link.
