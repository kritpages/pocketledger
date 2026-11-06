# PocketLedger Pages bundle

This folder is a standalone GitHub Pages publishing bundle. Its repository root should contain `.github/`, `.gitignore`, and `dist/`.

## Publish

1. Push the **contents of this folder** to the default branch of a GitHub repository. The workflow currently deploys from `main`; change that branch in `.github/workflows/deploy-pages.yml` if your default branch is named differently.
2. In the repository, open **Settings → Pages** and set **Build and deployment → Source** to **GitHub Actions**.
3. Check the Actions tab for the deployment. The workflow publishes the prebuilt `dist/` folder.

The repository can remain private and the site can be public if your GitHub plan permits Pages for private repositories. GitHub Free requires a public repository for Pages. The published site is public, while the repository remains private.
