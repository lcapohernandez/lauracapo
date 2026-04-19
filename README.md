# lauracapo.com

Personal portfolio site for **Laura Capo** — Software Engineer & QA Engineer.

Static site built with plain HTML, CSS, and a small amount of vanilla JavaScript,
designed to be deployed to GitHub Pages with the custom domain **lauracapo.com**.

## Local preview

Open `index.html` directly in a browser, or run any static server:

```bash
python3 -m http.server 8080
# then visit http://localhost:8080
```

## Deploy

1. Push to the `main` branch of this repository.
2. In GitHub → Settings → Pages, set the source to **main / root**.
3. Add a custom domain: `lauracapo.com` (the `CNAME` file is already included).
4. Point the domain's DNS `A` / `CNAME` records at GitHub Pages.

## Workflow

- Feature work happens on the `dev` branch.
- Pull requests are opened from `dev` → `main` before releasing.

## Structure

```
.
├── index.html     # Single-page portfolio
├── styles.css     # Styling
├── script.js      # Small UI interactions
├── CNAME          # Custom domain for GitHub Pages
└── README.md
```
