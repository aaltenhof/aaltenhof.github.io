# Aja Altenhof — personal site

Plain HTML/CSS, served by GitHub Pages. No build step.

- `index.html` — all content; About, Publications, and Teaching are tabs (`#about`, `#publications`, `#teaching`), and the CV tab opens the PDF
- `style.css` — layout and the Semantic Load palette (variables at the top)
- `Altenhof_CV.pdf` — linked from the CV icon and the CV tab
- `images/profile.jpg` — add a square photo here; the "AA" circle shows until you do

## To edit
- Add a publication: copy one `<div class="entry">…</div>` block in `index.html`.
- Icon links (email, GitHub, Scholar, CV) are in the `<ul class="icons">` block.
- Update the CV: replace `Altenhof_CV.pdf` with a file of the same name.

## Publishing
1. Create a public repo named `aaltenhof.github.io`.
2. Upload these files to it (drag-and-drop on github.com works).
3. Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
4. The site goes live at `https://aaltenhof.github.io` within a minute or two.
