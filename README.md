# Alan Wu — Academic Website

This is a static, single-page academic/research website. No build tools are required.

## Files

- `index.html` — page content
- `styles.css` — styling
- `assets/Alan_Wu_Resume.pdf` — resume linked from the site

## Preview locally

Double-click `index.html`, or run a simple local server from this folder:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Publish with GitHub Pages

1. Create a new public GitHub repository. For the shortest URL, name it `<your-github-username>.github.io`.
2. Upload the contents of this folder to the repository root.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.
6. GitHub will provide the public URL after deployment.

If you prefer not to make your other GitHub work public, that is fine: only this website repository needs to be public for GitHub Pages.

## Before publishing

Review these items in `index.html`:

- research interests
- project wording
- NYU email
- education dates

The site intentionally does **not** publish a phone number, home address, LinkedIn profile, or private repositories.
