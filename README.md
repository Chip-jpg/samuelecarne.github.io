# samuelecarne.me

Personal portfolio website of Samuele Carne, live at [samuelecarne.me](https://samuelecarne.me).

A single-page static site written in plain HTML, CSS and JavaScript, with no build step and no dependencies beyond two Google Fonts. It is hosted on GitHub Pages under a custom domain.

## Sections

- **Hero and About:** short introduction and key facts.
- **Skills:** skills grouped by how well I know them, with an English certifications modal (Cambridge B1, Oxford B2).
- **Learning:** what I am currently studying.
- **Projects:** personal projects with a status badge (Released, Work in Progress) and a link to the source.
- **Contact:** links to GitHub and other profiles.

## Design

- Dark theme with a gold accent.
- Instrument Serif for headings and DM Sans for body text, loaded from Google Fonts.
- Scroll-triggered reveal animations.
- Responsive layout for mobile and desktop.

## Run locally

No tooling is required. Clone the repository and open `index.html` in a browser:

```
git clone https://github.com/Chip-jpg/samuelecarne.github.io.git
cd samuelecarne.github.io
xdg-open index.html     # Linux
open index.html         # macOS
start index.html        # Windows
```

## Project layout

```
index.html        The whole site: markup, styles and scripts
certificates/     PDF certificates linked from the site
CNAME             Custom domain for GitHub Pages
```

## Deployment

The site is served by GitHub Pages from the `main` branch. Pushing to `main` publishes the change. The custom domain is set by the `CNAME` file and a DNS record at the registrar, and HTTPS is enforced through GitHub Pages.

## Updating the projects section

Each project is a `project-card` block inside the `#projects` section of `index.html`. To add one, copy an existing card and change the badge, title, description, tags and link. The badge classes are `badge-released`, `badge-wip` and `badge-concept`.

## Contact

- GitHub: [github.com/Chip-jpg](https://github.com/Chip-jpg)
- Google Developer profile: [g.dev/samuelecarne](https://g.dev/samuelecarne)
- Website: [samuelecarne.me](https://samuelecarne.me)
