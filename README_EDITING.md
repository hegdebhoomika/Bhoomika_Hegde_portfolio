# Bhoomika Hegde — Portfolio editing guide

## Open the website
1. Extract this ZIP.
2. Open the extracted `portfolio_build` folder in VS Code.
3. Open `index.html` with Live Server.

## Change a homepage project cover
All homepage covers are inside `assets/covers/`. Replace the image with your new image and keep the exact same filename. Refresh the website.

Cover filenames:
- `speakup-vr.jpg`
- `google-arts-culture.webp`
- `kisan-mr-mtp-phase-2.png`
- `comfort-aid.png`
- `game-design.png`
- `cashormiles-redesign.png`
- `kriyaa.png`
- `3d-world-building.jpg`
- `masters-thesis-phase-1.jpg`
- `oxycurv.png`
- `sharebite-preview.jpg` (temporary preview made from the first page of the ShareBite PDF because no separate cover was supplied)

## Replace a project PDF
Open `assets/documents/` and replace the matching PDF. Keep the exact filename:
- `masters-thesis-phase-1.pdf`
- `google-arts-culture.pdf`
- `kriyaa.pdf`
- `speakup-vr.pdf`
- `riddle-rush.pdf`
- `kisan-mr-mtp-phase-2.pdf`
- `miles-or-cash.pdf`
- `comfort-aid.pdf`
- `3d-world-building.pdf`
- `oxycurv.pdf`
- `sharebite.pdf`

Project pages display the PDF documentation inside the website. ShareBite and Comfort Aid use high-resolution image slices to keep their unusually tall boards reliable across browsers; their original PDFs are also kept in assets/documents for opening or downloading. If you replace either of those PDFs, regenerate the matching image slices in assets/pdf-rendered/sharebite/ or assets/pdf-rendered/comfort-aid/ as well. Other project pages continue to use PDF.js.

## Riddle Rush video prototype
The Riddle Rush project page includes a `WATCH VIDEO PROTOTYPE` link to your Google Drive video. To change it later, edit the link in `projects/game-design/index.html`.

## Edit text or layout
- `index.html` — homepage text and project cards
- `style.css` — homepage layout and styling
- `project.css` — project page styling
- `projects/<project-name>/index.html` — individual project page content

Keep the `assets` folder structure intact so all images and PDFs continue to load.


## Prototype and Behance links
Project-specific WATCH THE PROTOTYPE and OPEN IN BEHANCE links are maintained in each project's `index.html` and on the homepage project cards. Do not reuse one project's video URL for another project.
