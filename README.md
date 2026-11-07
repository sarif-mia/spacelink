# SpacelinkBD

This repository contains the SpacelinkBD static website:

- `index.html` is the page entry point and React app export.
- `assets/css/styles.css` contains the page's compiled utility stylesheet.
- `vercel.json` configures clean static URLs for Vercel.

The original export includes compiled app code, so no package manager or build
command is required.

## Deploy to Vercel

1. Import this repository into Vercel, or run `vercel` from the project root.
2. Select **Other** if Vercel asks for a framework preset.
3. Leave the build command and output directory unset. Vercel serves the root
   `index.html` and its CSS asset directly.

Every push to the connected Git repository can then trigger a new deployment.
