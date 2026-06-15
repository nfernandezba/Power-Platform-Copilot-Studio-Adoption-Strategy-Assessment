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
