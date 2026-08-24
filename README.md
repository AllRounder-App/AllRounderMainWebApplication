# AllRounder Website

AllRounder is a static HTML, CSS, and JavaScript marketing website for the local jobs and services app.

## Pages

- `index.html` - Home page
- `about.html` - About AllRounder
- `contact.html` - Contact page
- `privacy-policy.html` - Privacy policy
- `terms-conditions.html` - Terms and conditions

## Local preview

Serve the project directory with any static web server. For example:

```powershell
python -m http.server 8000
```

Then open `http://localhost:8000`.

The site has no React runtime, bundler, package manager, or build step. Its only browser-side behavior is in `script.js`, which handles the mobile navigation, FAQ accordion, and active navigation state.

## GitHub Pages

This site can be hosted directly from GitHub Pages:

1. Push the repository to GitHub.
2. Open **Settings > Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and the `/ (root)` folder, then click **Save**.

The root `CNAME` file is already configured for `allrounderapp.com`. Point that domain's DNS records to GitHub Pages if the custom domain is not already connected.
