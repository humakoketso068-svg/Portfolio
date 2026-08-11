# Koketso Cassious Huma — Portfolio

A single-page personal portfolio site for **Koketso Cassious Huma**, a BCom
Information Systems student at the University of Johannesburg working
toward a career in data engineering.

## Live site

Once deployed via GitHub Pages, the site will be available at:

```
https://humakoketso068-svg.github.io/
```

*(update this link once your repo is set up and Pages is enabled)*

## About

This site introduces Koketso, his academic background, current skillset,
and provides contact details for recruiters, collaborators, or anyone
interested in connecting.

Sections include:

- **Hero** — name, tagline, and a headshot photo
- **About** — brief background and current focus (BCom Information Systems,
  data engineering track)
- **Skills** — a visual "pipeline" of current tools: C#, Python, HTML, CSS,
  and JavaScript
- **Projects** — placeholder slots ready to be filled in as real projects
  are completed
- **Contact** — email, GitHub, and LinkedIn links

## Tech stack

- Plain **HTML5** and **CSS3** — no frameworks or build tools required
- Google Fonts: [Zilla Slab](https://fonts.google.com/specimen/Zilla+Slab),
  [IBM Plex Mono](https://fonts.google.com/specimen/IBM+Plex+Mono), and
  [Work Sans](https://fonts.google.com/specimen/Work+Sans)
- Fully responsive layout (adjusts for mobile screens)
- Respects `prefers-reduced-motion` for users sensitive to animation

## Project structure

```
.
├── index.html    # Main site (rename from Koketsohuma.html for GitHub Pages)
├── photo.jpg     # Hero section headshot
└── README.md     # This file
```

> **Important:** `index.html` and `photo.jpg` must stay in the same folder —
> the page references the photo by a relative path (`src="photo.jpg"`).

## Running locally

No build step needed. Just open `index.html` directly in a browser, or serve
it locally:

```bash
# Python 3
python -m http.server 8000
```

Then visit `http://localhost:8000` in your browser.

## Deployment (GitHub Pages)

1. Push this project to a GitHub repository.
2. In the repo, go to **Settings → Pages**.
3. Under **Source**, select the `main` branch and `/ (root)` folder, then save.
4. GitHub will publish the site at `https://<your-username>.github.io/<repo-name>/`
   (or `https://<your-username>.github.io/` if the repo is named
   `<your-username>.github.io`).

## Roadmap / to-do

- [ ] Replace the two "Coming soon" project placeholders with real projects
      (scripts, apps, or coursework worth showcasing)
- [ ] Add project links/screenshots as they're completed
- [ ] Consider adding a resume/CV download link

## Contact

- **Email:** [humakoketso068@gmail.com](mailto:humakoketso068@gmail.com)
- **GitHub:** [github.com/humakoketso068-svg](https://github.com/humakoketso068-svg/)
- **LinkedIn:** [linkedin.com/in/koketso-huma-16683a356](https://www.linkedin.com/in/koketso-huma-16683a356)

## License
This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.
