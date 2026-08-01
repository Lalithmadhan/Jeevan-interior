# Jeevan Interiors — Website

## Files
- `index.html` — the full website (open this in any browser)
- `images/` — logo + service photos used on the site
- `images/gallery/` — empty folder, ready for your project photos

## Adding gallery photos later
1. Copy your finished-project photos into `images/gallery/` (e.g. `project1.jpg`, `project2.jpg`).
2. Open `index.html`, find the `<div class="gal-grid reveal">` block in the Gallery section.
3. Replace a placeholder card like this:
   ```html
   <div class="gal-card"><span class="corner">G-01</span><div class="plus">+</div><span>Add photo</span></div>
   ```
   with:
   ```html
   <div class="gal-card" style="aspect-ratio:4/3.1;">
     <img src="images/gallery/project1.jpg" alt="Completed project" style="width:100%;height:100%;object-fit:cover;">
   </div>
   ```
4. Repeat for each new photo. No other changes needed — the layout adapts automatically.

## Hosting
Upload the whole folder (index.html + images/) to any hosting provider (e.g. Hostinger, GitHub Pages, Netlify) or point a domain like `jeevaninteriors.in` at it.
