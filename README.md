# ricardobrancas.com

Personal website. Plain static HTML — no build step, no Jekyll, no Ruby.

## Files

- `index.html` — homepage (about, publications, projects)
- `cv.html` — CV
- `style.css` — single stylesheet
- `files/` — paper PDFs
- `images/` — profile photos
- `CNAME` — GitHub Pages custom domain

## Local preview

```sh
python -m http.server
```

Then open <http://localhost:8000>.

## Adding a publication

Edit `index.html` and add a new `<div class="pub">…</div>` block under the Publications section. Drop the PDF into `files/`.

## Deploy

Push to `master`. GitHub Pages serves the files directly.
