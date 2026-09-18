# DualManip project page

This directory is a self-contained static project website prepared for `https://lcx.github.io/dualmanip/`. It has no build step or external dependencies. Its local directory name does not determine the published URL; the GitHub owner and repository name do.

## Before publishing

- The paper currently lists anonymous authors; add public author/affiliation information only when appropriate.
- The three general-task and three assembly-task image panels are placeholders. Replace their `.task-image` blocks in `index.html` with `<img>` elements when the experiment photos are ready, and add appropriate `alt` text. The hero illustration is deliberately labeled *conceptual*.
- The included `assets/dualmanip-paper.pdf` is the supplied manuscript. Replace it when a public version is ready. The code link is intentionally omitted until a repository is available.
- Publish from a repository named `dualmanip` owned by the GitHub account `lcx` to obtain the intended URL. The site's CSS, figure, PDF, and icon links are relative, so they work under the `/dualmanip/` path.

## Local preview

From this directory, run `python3 -m http.server 8000` and open `http://localhost:8000/`.

## GitHub Pages

Create a repository named `dualmanip` under the `lcx` GitHub account, copy this directory's contents into the repository root, and configure Pages to publish from the chosen branch's root. If the `dualmanip` repository already holds project code, the site files can instead go in its `docs/` directory and Pages can publish from that folder. The exact settings are available under **Settings → Pages**.
