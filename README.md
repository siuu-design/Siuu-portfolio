# Siuu Design Studio — compact 4-column portfolio

## Main files
- `index.html` : homepage
- `work.html` : work gallery
- `styles.css` : colors, spacing, typography, grid
- `assets/` : portfolio images
- `project-*.html` : individual project pages

## How to replace a portfolio image
1. Put your image inside the `assets` folder.
2. Give it a simple English file name, e.g. `witch-shop.jpg`
3. Open `index.html` or `work.html` in a text editor.
4. Find the project you want to change.
5. Replace:
   `src="assets/old-image.jpg"`
   with:
   `src="assets/witch-shop.jpg"`

Example:
`<img src="assets/witch-shop.jpg" alt="Witch Shop Packaging">`

## How to change project title/category
Inside each project card, edit:
- `<h3>Project title</h3>`
- `<p>Package · Branding</p>`
- `data-cat="package branding"`

Available filter categories:
- `package`
- `logo`
- `branding`

## Recommended image ratio
For the 4-column gallery, square or slightly vertical images work best:
- 1:1
- 4:5

You do not need to resize every file perfectly because CSS crops images automatically with `object-fit: cover`.
