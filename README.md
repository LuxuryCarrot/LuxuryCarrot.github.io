# LuxuryCarrot

Personal site → **https://luxurycarrot.github.io**

Small, fast, privacy-first tools that run entirely on your own machine.

## Projects

### 🥕 Filey — [Open the app →](https://luxurycarrot.github.io/filey/)

A fast, lightweight, 100% local file converter & editor. Convert and edit PDFs, images,
and documents in one place — merge, split, rotate, compress, annotate, and convert
formats. Everything runs locally in your browser (WebAssembly) or on the desktop, so
your files never leave your device: no uploads, no servers, no accounts.

## How this site is built

The static site lives in [`public/`](public/) — the landing page plus the Filey app
under [`public/filey/`](public/filey/). It deploys to GitHub Pages via GitHub Actions
([`.github/workflows/deploy.yml`](.github/workflows/deploy.yml)). There is no build
step: the content is already static, so nothing can break at deploy time.
