# Sohrab Dhillon — Engineering Portfolio

A responsive, static portfolio built from Resume_Sep26.pdf. No framework, package install, or build step is required.

## Preview
Open `index.html` in a web browser. All assets use relative paths, so the site supports both a GitHub Pages user site and a project site.

## Publish to GitHub Pages
1. Create or select a GitHub repository.
2. Upload this folder's contents to the repository root, including `index.html`, `styles.css`, `.nojekyll`, and `assets/`.
3. In the repository's Settings → Pages, select **Deploy from a branch**, then **main** and **/(root)**, and save.
4. GitHub will display the published URL once deployment completes.

## Replace the photo placeholders
All placeholders are intentionally labeled; they are not photographs of completed work.

Place your photos in `assets/` and replace the corresponding `.placeholder` element in `index.html` with an image, for example:

```html
<img class="project-image real-photo" src="assets/uas-airframe.jpg" alt="Balsa UAS airframe showing circular and oval lightening cutouts">
```

Add this rule to styles.css:

```css
.real-photo { display: block; width: 100%; height: 100%; object-fit: cover; }
```

For the headshot, use an image inside the existing `.portrait` figure and preserve the caption as desired. Suggested filenames: `headshot.jpg`, `uas-airframe.jpg`, `composite-beam.jpg`, `classroom-power.jpg`, `campus-food-system.jpg`, `lifeguarding.jpg`.

## Content
- Email and LinkedIn match the supplied resume.
- Resume download retains the original PDF, including its phone number.
- Conceptual targets and simulation results are identified as such.
- CSWP is shown as in progress, not achieved.
- Fall 2025 and Winter 2026 beam work is grouped with separate descriptions.
- Edit content in index.html and appearance in styles.css.
