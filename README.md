# iVALT Resources

Shared image and asset library for iVALT, served at **https://resources.ivalt.com**.

## Contents

- `index.html` — responsive gallery with search, full-size preview (lightbox), and copy-direct-link / download actions.
- `images/` — source assets (PNG, JPG, WebP).
- `vercel.json` — cache headers and clean URLs for the Vercel deployment.

## Local preview

Open `index.html` directly, or serve the folder:

```sh
python3 -m http.server 8080
# then visit http://localhost:8080
```

## Deployment

Deployed to Vercel. Pushing to `main` publishes the site; the custom domain
`resources.ivalt.com` is attached to the project.

## Adding an asset

1. Drop the file into `images/`.
2. Add an entry to the `ASSETS` array in `index.html` (filename + display size).
3. Commit and push.
