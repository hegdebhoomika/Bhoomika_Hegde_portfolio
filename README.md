# Bhoomika Hegde — Portfolio Website

## Preview locally
1. Extract this ZIP.
2. Open the extracted `bhoomika_portfolio_complete` folder in VS Code.
3. Open `index.html`.
4. Right-click and choose **Open with Live Server**.

## Files
- `index.html` — all website content and project sections
- `style.css` — typography, layout, colours and responsive behaviour
- `script.js` — mobile navigation
- `assets/images/` — add your portrait here
- `assets/projects/` — add project images here
- `assets/creative/` — add art and photography here

## Adding your portrait later
Put your photo in `assets/images/` as `bhoomika.jpg`. In `index.html`, replace:
```html
<div class="portrait-placeholder"><span>YOUR PORTRAIT</span></div>
```
with:
```html
<img class="portrait-image" src="assets/images/bhoomika.jpg" alt="Bhoomika Hegde">
```
Then add this to `style.css`:
```css
.portrait-image {
  width: min(25vw, 330px);
  height: min(34vw, 430px);
  object-fit: cover;
  border-radius: 48% 48% 46% 46%;
}
@media (max-width: 620px) {
  .portrait-image { width: 58%; height: auto; aspect-ratio: .78; }
}
```

## Adding project images
For each project, add an image to `assets/projects/`. Replace the placeholder `<span>` inside its `.project-image` or `.case-visual` with an `<img>` element. The image placeholders are intentionally visible until you provide final assets.

## Content accuracy
This build uses project facts currently available in the conversation. Oxycurv and Google Arts & Culture detailed descriptions are intentionally left open until the original source content is provided. MTP Phase 2 is also reserved for your final documentation. No unverified outcomes or claims have been added.

## Important
The website is a complete navigable structure with working section navigation and project anchors. Project case-study content and imagery can be expanded as you provide original portfolio materials.


### Portrait
The homepage portrait is stored at `assets/images/bhoomika-portrait.jpg`. Replace this file with another portrait using the same filename to update it.

## Updating project covers and documents
- Replace a homepage cover image inside `assets/covers/` with a new image using the same filename to update it without editing HTML.
- Replace a project PDF inside `assets/documents/` with the new PDF using the exact same filename. The project page reads that file automatically.
- Tall PDF boards are rendered in smaller vertical sections to avoid blank pages/canvas-size problems. PDF links remain clickable where the source PDF contains web links.
- See `UPDATE_PROJECT_DOCUMENTS.md` for the complete file-name mapping.
