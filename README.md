# website

Personal portfolio site for Joshua Miller. Plain HTML and CSS, no build step.

Live at: https://joshua-miller-ri.github.io/website/

## Files

- `index.html` — the page
- `style.css` — styles
- `resume/JoshuaMiller_Resume3.2.pdf` — linked from the "Resume" button

## Deploying

In the repo, go to **Settings → Pages** and set the source to **Deploy from a branch**, `main`, `/ (root)`. Every push to `main` redeploys the site.

To update the resume, either overwrite the PDF using the same filename, or change the `href` on the Resume link in `index.html` to the new filename. GitHub Pages paths are case-sensitive, so the link has to match the filename exactly.
