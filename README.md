# Saanvi — personal academic & AI engineering portfolio

A responsive, dependency-free static website for research and AI/ML engineering work. This is a **design draft**: bracketed details and labeled entries are placeholders, not claims about completed work.

## Preview locally

From the repository root, run:

```sh
python3 -m http.server 4173 --bind 0.0.0.0
```

Open `http://localhost:4173` in your local browser. In a remote development environment, forward port **4173** using its port forwarding feature. Stop the server with Ctrl+C. You can also open `index.html` directly; no build or installation is required.

## Edit the content

- `index.html`: bio, research entries, project cards, experience, education, and contact information.
- `styles.css`: colors and typography in `:root`, layout, and responsive breakpoints.
- `script.js`: optional current year and active navigation enhancement.

Replace the abstract portrait block with an image, for example `<img src="assets/portrait.jpg" alt="Portrait of Saanvi" width="340" height="350">`, and style it with `width:100%; height:350px; object-fit:cover`. Put image assets in `assets/`. Project illustrations are inline SVGs and can be replaced with screenshots. The site uses system fonts and no external image or font services.

Before sharing publicly, replace every bracketed field and placeholder label with verified details, remove unused entries, and add real email, CV, project, and professional profile links. No fake publication links or contact endpoints are included.

## Review and hosting

The first draft is on `feat/portfolio-first-draft`. Review the diff against the starting commit and use the local preview above. **No deployment workflow is included, and this change does not enable GitHub Pages.** Publishing and merging are separate future steps. All asset paths are relative so the site can run at a GitHub Pages repository subpath without a build.

Design inspiration: the concise academic portfolio structure of [Jon Barron](https://jonbarron.info/) and [Shivam Singh](https://shivamsingh12.com/). The layout, styling, and illustrations here are original; no reference content or assets are copied.
