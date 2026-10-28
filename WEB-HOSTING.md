# Static site hosting notes

The landing page is plain HTML and CSS. It has no build step, package dependencies, API, secrets, or server-side behavior. All images and the SVG favicon are referenced with relative paths, so they continue to resolve when GitHub Pages serves the repository beneath a project path such as `/repository-name/`.

## Hosting options

Choose one deployment topology when publication is approved:

- **GitHub Pages:** publish the repository root from the selected branch. The page is designed to work as a project site under a repository subpath; no custom domain or `CNAME` file is assumed.
- **Cloudflare Pages connected to GitHub:** use the repository root as the project root, with no build command, and publish the repository root as the static output. Cloudflare Pages can serve this static site directly; a separate Worker is not needed for the page itself.
- **GitHub Pages behind a Cloudflare Worker or proxy:** keep GitHub Pages as the origin and configure the Worker/proxy separately. Preserve the request path, including the repository subpath, when forwarding requests. This draft does not include Worker routing or proxy code.

These are alternative hosting arrangements, not a deployment performed by this pack. If the intended setup is “Cloudflare Pages builds from GitHub,” GitHub Pages does not also need to serve the same site. If the intended setup is “GitHub Pages behind a Worker,” the Worker route and origin behavior must be configured separately.

## Files and paths

- `index.html` is the page entry point.
- `assets/favicon.svg` is declared in the page's `<head>` as the favicon.
- Promotional illustrations and the favicon are stored in `assets/` and referenced relatively (for example, `assets/promo-human-review.png`).
- The checklist and guidance links point to the existing Markdown source files. They remain source documents; this landing page does not convert them into a separate documentation site.

## Publication hold

This remains a **draft only** and is not approved or adopted. No GitHub repository has been created, and no files have been pushed, published, or deployed. Resolve the repository name, visibility, license, other open decisions, and the required publication approval before making the site public. The `LICENSE` file remains intentionally omitted.
