# A Garden of Letters — HTTPS Website

This is a static website designed for GitHub Pages.

## Publish it as HTTPS

1. Create a GitHub repository named `birthday-letter-garden`.
2. Upload `index.html` and `.nojekyll` to the repository root.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.
6. GitHub Pages will publish the site at an HTTPS address such as:
   `https://YOUR-USERNAME.github.io/birthday-letter-garden/`

GitHub Pages provides HTTPS for the published site. It can take a few minutes for the first deployment.

## Sharing / QR code

The website uses the current page's URL for the Share panel and QR code. Once the site is opened from its HTTPS GitHub Pages address, the QR code and copied link will point to that public HTTPS address instead of a local `file://` path.

## Important about saved letters

Letters are stored in the browser using localStorage. This means letters added on one device/browser do not automatically appear on another device. The site also includes an Export Garden function for creating a shareable URL containing the letters.
