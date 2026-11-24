# ProlificDev portfolio

A responsive, single-page portfolio for Abdulmalik Abdulrahman, built with semantic HTML, CSS, and vanilla JavaScript. It is a static site and has no build step or server-side requirement.

## Preview locally

Open `index.html` in a browser, or serve this folder with any static HTTP server. All site files are at the repository root, so the site can also be published directly from the root of a GitHub Pages branch.

## Deploy with GitHub Pages

1. Create a public GitHub repository and push these files to its default branch.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the default branch and the `/ (root)` folder, then save.
5. GitHub Pages will provide the published URL after its first deployment.

No custom domain is required. Since the site uses relative asset paths and no build process, it works at both a user-site URL and a repository-site URL.

## Update the portfolio

- Edit section copy and links in `index.html`.
- Update colors, typography, and responsive rules in `styles.css`.
- The mobile navigation and dynamic footer year are in `script.js`.
- Replace `favicon.svg` to change the tab icon.
- Update the page title, description, and Open Graph tags in the `<head>` of `index.html` if the portfolio details change.
- The verification figures describe local code and database checks; update them only when you have rerun the corresponding checks.

## Add genuine project screenshots

The NaijaSolarShop project includes a genuine homepage screenshot at `assets/naijasolarshop-home.png`. To replace or add screenshots:

1. Add optimized WebP or AVIF captures under a new `assets/` directory (for example, `assets/naijasolarshop-home.webp`).
2. Replace the `.project-preview` block in `index.html` with an `<img>` or a small `<figure>` containing the real capture.
3. Add descriptive alt text that explains the visible page, and set image dimensions to avoid layout shift.
4. Keep the typographic project details and live link alongside the screenshots.

## Contact and project links

The email, phone, GitHub, LinkedIn, and live project destinations are direct links. The GitHub project repository is not linked because a public repository URL has not been verified.
