# Pocket World website

Pocket World is a static website. Its entry point is `index.html`; the PNG files beside it are used as screen artwork and quiz imagery.

## Publish with GitHub Pages

The workflow in `.github/workflows/pages.yml` deploys the website whenever changes are pushed to the `main` branch. It publishes only `index.html` and the images it needs.

1. Create a GitHub repository and upload the website files from this folder, including `.github/workflows/pages.yml`.
2. In the repository, open **Settings → Pages** and set the build and deployment source to **GitHub Actions**.
3. Push or merge a commit to `main`, or run **Deploy Pocket World to GitHub Pages** from the **Actions** tab.
4. Open the Pages URL shown in the deployment workflow. It will usually be `https://<your-github-username>.github.io/<repository-name>/`.

The sign-up and login data is stored in the visitor's browser on that device; this static site does not provide shared accounts or a server-side database.
