# Portfolio (static, no build)

Files: `index.html`, `photo.jpg`, `Mahmoud-Alnabawi-CV.pdf` (add yours), `robots.txt`, `sitemap.xml`.

**Deploy:** push all files to the root of the GitHub repo, then Settings > Pages > Deploy from branch `main` / root.

**Edit content:** projects are in the `PROJECTS` array at the top of the script (add `repo:"https://github.com/..."` for a GitHub button). Text sections are plain HTML in `index.html`.

**Contact form:** create a form at formspree.io with your email and replace `YOUR_FORM_ID` in `FORM_ENDPOINT`. No secrets are stored in the page.

**Still needed:** an Open Graph image (add `<meta property="og:image">`), and the CV PDF.
