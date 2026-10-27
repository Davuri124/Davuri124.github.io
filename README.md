# Agnes Teresa Davuri · Portfolio

Static site. No build step.

## Deploy (GitHub Pages, free)
1. Create a repo named `Davuri124.github.io` and push everything in this folder to its root.
2. Settings → Pages → deploy from the `main` branch, `/ (root)`.
3. Live at https://Davuri124.github.io

## Edit
- `index.html`: project cards are the `R` array, books are the `B` array, short writing is `W` (near the bottom).
- `demos/`: the 9 live demos. Each has a back link to `../index.html`.
- `covers/`: drop a cover as `covers/<slug>.jpg` (2:3, about 600×900px, under 200KB). Slugs are the `i` values in `B`, e.g. `queen-with-curse.jpg`. Covers are already added.
- `resume/`: the two PDFs.

## To fill in
- Blurbs and Wattpad links for each book (add `l:"https://..."` and a button, or ask me).

## Custom domain
Add a `CNAME` file containing your domain (e.g. `agnes.dev`) and set the DNS records your registrar shows. HTTPS is automatic on GitHub Pages.

## Articles
- Pages are generated from the Medium drafts into `articles/<slug>/`. To link the Medium version, set `m:"https://medium.com/..."` on that item in the `A` array in `index.html` (an **On Medium** button appears).
- All 10 project articles are live. When you run the HITL confirmatory test, add its result to `articles/hitl-orchestrator/index.html` (the paragraph that starts "Where this stands").

## Papers
`papers/` holds the full reports and documents linked from each project card (the **Documents** line). To add one, copy the file in and add `w:[["Label","papers/file.pdf"]]` to that project in the `R` array.
