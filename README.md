# DualManip project page

This directory is a self-contained static project website for `https://lichengxi1.github.io/Dualmanip/`. It has no build step or external dependencies.

## Before publishing

- The page includes the public author and affiliation information in `index.html`.
- The teaser uses `assets/teaser.pdf`; `assets/teaser.png` is its web-friendly preview image.
- The experiment section uses two figures: snake placement under continuous dynamic scene changes, and the combined toy positioning and block placement sequence under a single scene change. The PNG files are web-friendly previews generated from the supplied result PDFs; clicking a figure opens its original PDF.
- The included `assets/dualmanip-paper.pdf` is the supplied manuscript. Replace it when a public version is ready.

## Local preview

From this directory, run `python3 -m http.server 8000` and open `http://localhost:8000/`.

## GitHub Pages

Create a repository named `dualmanip` under the `lcx` GitHub account, copy this directory's contents into the repository root, and configure Pages to publish from the chosen branch's root. If the `dualmanip` repository already holds project code, the site files can instead go in its `docs/` directory and Pages can publish from that folder. The exact settings are available under **Settings → Pages**.
