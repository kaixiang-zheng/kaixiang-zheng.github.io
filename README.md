# Kaixiang Zheng — Academic Homepage

Website: https://kaixiang-zheng.github.io/

This is a static HTML/CSS website. No installation or build step is needed.

## Files

- `index.html`: biography, news, publications, teaching, service, and contact details.
- `styles.css`: desktop and mobile layout.
- `assets/portrait.jpg`: profile photograph.
- `assets/CV-Kaixiang-Zheng.pdf`: current two-page CV.
- `assets/favicon.svg`: site icon.
- `.nojekyll`: serves the static files without Jekyll processing.

## Publishing

In repository Settings → Pages, choose **Deploy from a branch**, branch **main**, folder **/(root)**. Changes committed to main are then published automatically.

## Maintenance checks

After publishing, verify the homepage, portrait, and CV download at the public URL. Keep asset paths relative so the site remains portable. When replacing the CV, check its title and author metadata as well as its page count.

## Future updates

This repository is the source for the public homepage. It can be maintained through ChatGPT/Codex with the GitHub connection authorized for this repository. Preserve the publication ordering (NeurIPS and ICLR first), existing links, and responsive layout when editing.
