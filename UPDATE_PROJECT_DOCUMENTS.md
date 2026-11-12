# Updating project documentation later

Your original PDFs are kept in `assets/documents/`. Each project page displays the PDF directly in the page, split into safe-height visual sections so tall boards do not turn blank or exceed browser canvas limits. PDF links are kept clickable where the source PDF contains web links.

To replace a project document: replace the matching PDF in `assets/documents/` and keep its exact filename. The site uses these filenames: `masters-thesis-phase-1.pdf`, `google-arts-culture.pdf`, `kriyaa.pdf`, `speakup-vr.pdf`, `riddle-rush.pdf`, `kisan-mr-mtp-phase-2.pdf`, `miles-or-cash.pdf`, `comfort-aid.pdf`, `3d-world-building.pdf`, `oxycurv.pdf`, and `sharebite.pdf`.

Most pages render PDFs in the browser using PDF.js. ShareBite and Comfort Aid use image slices for reliable display of their very tall documentation; their original PDFs are retained as downloadable files. If you update either of these two PDFs, also replace the matching image slices in assets/pdf-rendered/sharebite/ or assets/pdf-rendered/comfort-aid/.

The Riddle Rush page also has a separate `WATCH VIDEO PROTOTYPE` link to the Google Drive video you shared.
