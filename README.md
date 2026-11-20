# HAMA DYLIB IMAGE SWAPPER

A browser-only helper to inspect embedded JPEG/PNG images in a selected dylib, preview them, and attempt a same-slot replacement.

## Deploy
1. Upload `index.html` and `.github/workflows/pages.yml` to the repository's `main` branch.
2. In GitHub, open **Settings → Pages** and select **GitHub Actions** as the build/deployment source.
3. Open **Actions** and run or wait for **Deploy HAMA DYLIB Image Swapper**.
4. When green, open the Pages URL shown in the workflow summary.

## Important
The selected dylib is processed locally in the browser and is not uploaded by this page. The tool only attempts byte-slot replacement for validated JPEG/PNG data. Some dylibs store images in compressed asset catalogs or have separate size/checksum metadata; this simple replacement may not work for those formats. Keep an untouched backup and test the result. This tool does not modify tweak/game logic.
