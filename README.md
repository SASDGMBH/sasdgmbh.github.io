# SASD-GmbH GitHub Pages Website

This repository contains the public GitHub Pages website for **SASD-GmbH – Scientific and Software Development**.

The website is intended as a compact technical profile for the public SASD GitHub presence. It presents the company focus, service areas, working approach and selected public work in a clear and maintainable static format.

Live website:

<https://sasdgmbh.github.io>

Main GitHub organization:

<https://github.com/SASDGMBH>

---

## Purpose

This website is not intended to be a full legal company website. It is a public technical profile connected to the SASD-GmbH GitHub organization.

The primary goals are:

- present SASD-GmbH in a professional and customer-facing way;
- explain the focus on software development, Linux infrastructure, data-backed applications and technical documentation;
- provide a clean entry point for visitors coming from GitHub;
- avoid presenting unfinished internal work as customer-ready public projects;
- keep the site simple, fast, static and easy to maintain.

The official company website remains:

<https://www.sasd.de>

---

## Website structure

```text
.
├── index.html
├── services.html
├── approach.html
├── public-work.html
├── contact.html
├── assets/
│   ├── css/
│   │   └── styles.css
│   ├── js/
│   │   └── site.js
│   └── img/
│       ├── sasd-mark.svg
│       ├── hero-engineering-map.svg
│       └── process-map.svg
├── README.md
└── LICENSE.md
```

### Pages

- `index.html` – landing page and positioning
- `services.html` – service overview
- `approach.html` – working method and delivery philosophy
- `public-work.html` – public GitHub positioning
- `contact.html` – contact information

---

## Design direction

The site uses a calm technical B2B style:

- dark navy / petrol color palette;
- static HTML, CSS and a small amount of JavaScript;
- no external framework dependency;
- no stock photography;
- original SVG graphics;
- responsive layout for desktop, tablet and mobile screens.

The design is intentionally restrained. The goal is to communicate reliability, technical clarity and maintainability rather than short-lived visual trends.

---

## Local preview

Because this is a static website, it can be opened directly in a browser.

For a slightly more realistic local preview, start a small local web server from the repository root:

```bash
python -m http.server 8000
```

Then open:

<http://localhost:8000>

---

## Deployment

The website is deployed through GitHub Pages.

Typical workflow:

```bash
git status
git add .
git commit -m "Update SASD GitHub Pages website"
git push
```

After pushing, check:

<https://sasdgmbh.github.io>

If the live website does not update, verify the GitHub Pages settings in the repository:

```text
Settings → Pages → Build and deployment
```

Recommended source for this repository:

```text
Deploy from a branch
Branch: master
Folder: /root
```

Depending on the repository settings, GitHub Pages may also use GitHub Actions. In that case, check the latest workflow run under the `Actions` tab.

---

## Repository status

This repository contains the public static website for the SASD-GmbH GitHub organization.

Status: **Public technical profile / static website**

The repository is intentionally small and should remain easy to understand. It should not become a dumping ground for unrelated experiments, unfinished prototypes or large generated assets.

---

## Maintenance checklist

Before major updates, check:

- Does the text still match the current SASD-GmbH positioning?
- Are public project links still valid?
- Are contact details correct?
- Are the GitHub organization profile and this website consistent?
- Does the website still work on mobile screens?
- Does the live GitHub Pages deployment show the current repository content?
- Are legal requirements such as imprint and privacy information handled by the official company website or linked clearly?

---

## Licensing

This repository contains both source code and company content.

The website source code may be reused under the conditions described in `LICENSE.md`.

Company names, logos, graphics, branding, layout, written content and business descriptions are protected and may not be reused as if they were generic open-source material.

See:

```text
LICENSE.md
```

---

## Contact

SASD-GmbH – Scientific and Software Development

Website: <https://www.sasd.de>  
GitHub: <https://github.com/SASDGMBH>
