# Gropius House Environmental Atlas Rebuild

This folder contains a rebuilt static homepage for the Gropius House environmental atlas project.

## Included

- `index.html`: new homepage shell and section structure
- `styles.css`: redesigned visual system and responsive layout
- `app.js`: rebuilt interaction layer for the atlas, repairs archive, pest comparison, and image records
- `data.js`: extracted source data used by the new interface
- `assets/`: updated first-floor, second-floor, basement, and site-plan drawings plus linked conservation PDFs
- `images/`: recovered original site photos and pest-board photos from the shared source package

## Notes

- The first-floor, second-floor, basement, latest-site, and pest-comparison images now point to recovered source files instead of fallback placeholders.
- The active plan files are `assets/gropius-first-floor-plan.png`, `assets/gropius-second-floor-plan.png`, `assets/gropius-basement-floor-plan.png`, and `assets/gropius-site-plan.png`.
- No archival section/elevation image was present in the recovered source site package, so those blank placeholders were removed from the drawings strip.
- The oversized archival file `gro-cmp-additional-resources-2016.pdf` was moved out of this GitHub upload folder to keep browser upload warnings from appearing. A local copy is preserved in `../offline-only-docs/`.

## GitHub Upload

Upload these files and folders to the repository root:

- `index.html`
- `styles.css`
- `app.js`
- `data.js`
- `assets/`
- `images/`

Optional to keep:

- `README.md`

If GitHub Pages is already configured for the repo root, the site should publish from `index.html`.
