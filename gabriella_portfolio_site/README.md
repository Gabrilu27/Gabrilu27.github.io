# Gabriella Lucci — Portfolio (GitHub Pages)

This is a static portfolio website you can deploy on GitHub Pages in minutes.

## Quick deploy (user site)

1. Create a GitHub account if you don’t have one.
2. Create a new repository named **USERNAME.github.io** (replace USERNAME with your GitHub username).
3. Upload all the files in this folder (keep the same structure).
4. Commit and wait ~1 minute; your site will go live at **https://USERNAME.github.io**.

## Alternative: project site

1. Create a repo with any name, e.g., `portfolio`.
2. Upload these files.
3. In **Settings → Pages**, under **Build and deployment**, choose **Deploy from a branch**, then set **Branch: main / root**.
4. Your site will be at **https://USERNAME.github.io/REPO**.

## Replace images

- Add your image files under `assets/images/` and update the `src` of each project in `portfolio.html` if you use different filenames.
- The default uses `assets/images/placeholder.svg` so the layout looks complete until you add real images.

## Edit text

- Update any copy directly in the HTML files (they’re simple and well‑commented).
- For SEO, edit the `<title>` and `<meta name="description">` in each page `<head>`.

## Custom domain (optional)

- Buy a domain from any registrar.
- Add a DNS record: `A` pointing to GitHub Pages IPs (see GitHub docs) *or* a `CNAME` to `USERNAME.github.io`.
- Add a file named `CNAME` in the repo root that contains just your domain name.

## License / Images

The code here is MIT‑licensed. Replace all placeholder images with images you own or have permission to publish.
