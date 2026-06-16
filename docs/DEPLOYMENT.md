# Deployment Guide

## GitHub Pages

The repository is prepared to be published directly from its root folder.

### Required repository structure

```text
/
├── index.html
├── README.md
├── LICENSE
├── .nojekyll
├── assets/
│   ├── icons/
│   └── images/
└── docs/
```

### Deployment steps

1. Create or open the GitHub repository.
2. Upload the contents of this package to the repository root.
3. Confirm that `index.html` is located at `/index.html`.
4. Open **Settings > Pages**.
5. Under **Build and deployment**, select **Deploy from a branch**.
6. Select the main branch and the `/root` folder.
7. Save the configuration.
8. Wait for the GitHub Pages deployment to complete.

The expected public URL follows this pattern:

```text
https://<github-user>.github.io/<repository-name>/
```

## Important path rule

The application uses relative paths beginning with `./assets/`. Do not replace
them with `/assets/`, because an absolute root path may fail when the site is
published inside a GitHub Pages repository path.

## Local use

The application can also be opened locally by launching `index.html` in a
modern browser. An Internet connection is recommended because the normal PDF
generator loads jsPDF from a CDN.

## Version

The public assessment version is fixed at `v1.0`.

## Header identity line

The header includes the mandatory 3 px CoE Toolkit multicolor identity line.
It is rendered directly below the black application header and spans the full
viewport width.

## Footer format

The footer follows the standard three-line CoE Toolkit layout:

1. Tool name, CoE Toolkit, public version, and current year.
2. LinkedIn icon and Nico Fernandez author link.
3. A localized privacy statement describing local processing, browser language storage, and public third-party resources.

The footer is centered, uses the standard dark background, and remains at the end of the page through the Application Shell grid.

## Favicon

The favicon files are stored in `assets/icons/` and referenced through relative
paths. The query parameter `?rev=2` forces browsers and GitHub Pages to refresh
previously cached favicon files.

After deployment, if an older favicon is still shown:

1. Open the site in a private browser window.
2. Perform a hard refresh.
3. Close and reopen the browser tab.
4. Confirm that `assets/icons/favicon.svg?rev=2` is publicly accessible.

## Centered initial hero

The initial screen follows the CoE Toolkit centered hero standard:

- centered container with a maximum width of 900 px;
- local CoE Toolkit SVG displayed at 78 × 78 px;
- no glow, shadow, halo, background, pulse, or animation;
- Aptos Display H1 with responsive `clamp()` sizing;
- Aptos description limited to 650 px;
- identical layout rules in Spanish and English.
