# Prepare Module Demo

Static interactive prototype for the PCM, CCS, and WPOR screens.

## Publish with GitHub Pages

1. Create a GitHub repository and push this project to the `main` branch.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **GitHub Actions**.
4. Push to `main` or run the **Deploy demo to GitHub Pages** workflow manually.

The workflow in `.github/workflows/deploy-pages.yml` publishes the project root as a static site.

The demo uses browser-local mock data. Changes made by a visitor are not shared with other visitors and are reset when the page is refreshed.
