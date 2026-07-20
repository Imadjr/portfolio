# Imad Eddine Djerarda — Portfolio

A dependency-free, responsive GitHub Pages portfolio for an Embedded Systems Engineer, IoT developer, educator, and project builder.

## Preview locally

You can open `index.html` directly, or run a small local server from this folder:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

## Publish with GitHub Pages

### Option A — Create a dedicated portfolio repository

1. Create a new public repository, for example `portfolio`.
2. Upload all files from this folder to the repository root.
3. Open **Settings → Pages** in the repository.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Choose the `main` branch and `/ (root)` folder, then save.
6. GitHub will publish the site at:

   `https://YOUR-GITHUB-USERNAME.github.io/portfolio/`

### Option B — Use your profile website URL

Create a public repository named exactly:

`YOUR-GITHUB-USERNAME.github.io`

Upload these files to its `main` branch and enable Pages. The site will be available at:

`https://YOUR-GITHUB-USERNAME.github.io/`

## Personalization checklist

Search the project for the following values and update them before publishing:

- `Imad Eddine Djerarda` — verify the preferred public name.
- `https://github.com/Imadjr` — replace if the GitHub username changes.
- `https://www.linkedin.com/in/imad-djr/` — verify the LinkedIn public URL.
- `imad.djerarda@gmail.com` — verify the public contact email.
- `https://imadjr.github.io/portfolio/` — update the Open Graph URL if the repository name or custom domain differs.
- `Institution and graduation details: add from CV` — replace with the university, degree, and dates.
- The Achievements introduction — replace the reminder with verified awards, publications, certificates, competition results, or teaching metrics.
- Project copy — add exact dates, your role, collaborators, measured results, and current status.

## Add project images

Place optimized project images inside `assets/images/`. Recommended format:

```text
assets/images/
├── smart-parking.webp
├── smart-agriculture.webp
├── fire-detection.webp
├── drowsiness-detection.webp
└── iot-dashboard.webp
```

Recommended image size: `1600 × 1000 px`, WebP, under `300 KB` each.

The current design intentionally uses technical CSS diagrams so the portfolio remains polished before photography is added. When real images are available, add an `<img>` inside the matching `.project-card` and write specific alternative text.

## Add the CV PDF

1. Place the PDF at:

   `assets/cv/Imad-Eddine-Djerarda-CV.pdf`

2. In `index.html`, find the `Request CV` link.
3. Replace its `href` with:

   `assets/cv/Imad-Eddine-Djerarda-CV.pdf`

4. Add the `download` attribute if you want the file to download directly:

```html
<a href="assets/cv/Imad-Eddine-Djerarda-CV.pdf" download>Download CV</a>
```

## Add a custom domain

In **Settings → Pages**, enter the custom domain. GitHub will create or request a `CNAME` file. Follow GitHub’s DNS instructions and enable **Enforce HTTPS** once it becomes available.

## Project structure

```text
.
├── index.html
├── styles.css
├── script.js
├── README.md
└── assets/
    ├── cv/
    └── images/
```

## Before sharing on a CV

- Replace all education and achievement placeholders.
- Add real project photos or screenshots where available.
- Add measurable outcomes without exaggeration.
- Confirm every external link.
- Upload a current CV PDF.
- Test on a phone and desktop.
- Keep only work you can explain confidently in an interview.

## License

The site content is personal to Imad Eddine Djerarda. Reuse the code structure as needed, but replace the personal content before publishing elsewhere.
