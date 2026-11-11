# Pablo J. Ordóñez — personal website

A static site for GitHub Pages. No build step: the files are served as they are.

## Files

| File | What it is |
| --- | --- |
| `index.html` | Home page (bio, photo, contact links) |
| `research.html` | Publications, working papers, reviews |
| `cv.html` | CV download, position, education, teaching |
| `style.css` | All styling. Change `--accent` at the top to change the site color |
| `images/` | Paper illustrations, favicon, and your photo (`photo.jpg`) |
| `files/` | Put PDFs here (CV, paper drafts) |

## Publish on GitHub Pages

1. Sign in to GitHub and create a new **public** repository named `YOUR-USERNAME.github.io` (for example `pablojordonez.github.io`). The name must match your username exactly.
2. On the new repository page choose **uploading an existing file**, drag in everything inside this folder (not the folder itself), and commit.
3. Open **Settings → Pages** and check that the site is published from the `main` branch, root folder.
4. After a minute or two the site is live at `https://YOUR-USERNAME.github.io`.

To change the site later, edit a file on GitHub (pencil icon) and commit; the live site updates within a couple of minutes.

## To do before sharing the link

Each item is marked with a `TODO` comment in the HTML.

- [x] `images/photo.jpg`: your photo is in place. Replace the file to change it (square crop).
- [ ] `index.html`: add your LinkedIn address and uncomment the link.
- [x] `research.html`: Costa Rica paper updated from the CV (new title, coauthors, JEEM conditionally accepted).
- [ ] `research.html`: status for the Colombia paper, if any; newer drafts of both papers.
- [x] `research.html`: abstracts for the PNAS and ERL papers.
- [ ] `research.html`: press coverage link for the PNAS paper.
- [ ] `research.html`: work in progress titles.
- [x] `cv.html`: CV is at `files/CV_Ordonez.pdf`. Replace the file (same name) to update it.
- [x] `cv.html`: positions, education, teaching and fellowships filled in from the CV.
- [ ] `cv.html`: IDB seminars and training, if you want them listed under Teaching.
