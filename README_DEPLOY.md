# Nayeb.ai GitHub Pages Upload Instructions

This folder is ready for GitHub Pages.

## Files

- `index.html` — your landing page. GitHub Pages needs this exact filename.
- `assets/nayeblogo.svg` — put your local icon here with this exact name.
- `CNAME.example` — example only. Rename it to `CNAME` only after replacing the content with your real custom domain.

## How to update the icon

1. Open the `assets` folder.
2. Delete `PUT-YOUR-LOGO-HERE.txt`.
3. Copy your local icon into the `assets` folder.
4. Rename the icon exactly to:

```text
nayeblogo.svg
```

Recommended format: SVG. For best favicon results, keep it simple and readable at small sizes. If you also need an Apple home-screen icon, add a PNG later.

## How to publish on GitHub Pages

1. Create a new GitHub repository, for example: `nayeb-ai-website`.
2. Upload everything in this folder to the root of the repository, not inside another folder.
3. Go to repository `Settings` → `Pages`.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/root`, then Save.
6. GitHub will publish the site at a GitHub Pages URL.

## How to use your custom domain

1. In your repository, go to `Settings` → `Pages`.
2. Under **Custom domain**, enter your domain, for example `nayeb.ai` or `www.nayeb.ai`.
3. Save.
4. Configure your domain DNS records at your domain provider.
5. After GitHub confirms the domain, enable **Enforce HTTPS**.

## DNS note

For a `www` subdomain, you usually point `www` to your GitHub Pages domain using a CNAME record.
For an apex/root domain like `nayeb.ai`, follow GitHub's official Pages DNS instructions from the Pages settings screen.
