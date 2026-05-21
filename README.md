# Zijin Chen Academic CV

This repository hosts the personal academic CV website for Zijin Chen, a PhD researcher working on Southern Ocean sea-ice processes, water-mass transformation, air-sea carbon exchange, and climate-model diagnostics.

Live site: https://zjhin.github.io/CV/

## Site Structure

The current site is a static GitHub Pages site. It does not require Jekyll, Ruby, Node, or a build step.

```text
.
├── index.html
├── assets/
│   ├── profile-avatar.jpg
│   ├── web-figures/
│   │   ├── directional-wmt.jpg
│   │   ├── inter-model-spread.jpg
│   │   └── carbon-uptake.jpg
│   └── full-figures/
│       ├── directional-wmt.jpg
│       ├── inter-model-spread.jpg
│       └── carbon-uptake.jpg
├── .nojekyll
├── LICENSE
└── README.md
```

## Content Areas

The homepage presents:

- research profile and contact links
- education, affiliations, and memberships
- publications and selected manuscripts
- selected visual work
- conferences and presentations
- links to Google Scholar, ORCID, LinkedIn, UTAS, AAPP, COSIMA, and related profiles

## Updating the Site

Most content is edited directly in `index.html`.

Images used by the Selected Visual Work section should follow these names so the existing page references continue to work:

```text
assets/web-figures/directional-wmt.jpg
assets/web-figures/inter-model-spread.jpg
assets/web-figures/carbon-uptake.jpg
assets/full-figures/directional-wmt.jpg
assets/full-figures/inter-model-spread.jpg
assets/full-figures/carbon-uptake.jpg
```

Use `assets/web-figures/` for lightweight card previews and `assets/full-figures/` for the click-through versions.

## Deployment

GitHub Pages serves the `master` branch from the repository root. After a commit, GitHub Pages can take a few minutes to refresh because of cache and deployment delay.

## Maintenance Notes

This repository was cleaned to keep only the static website and the assets referenced by the current homepage. Older Academic Pages/Jekyll template files, demo content, unused scripts, unused fonts, and duplicate figure uploads were removed to make the project easier to maintain.
