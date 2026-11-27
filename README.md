# MODETOUR · TAIPEI

Static HTML training microsite for GitHub Pages.

## Publish on GitHub Pages
1. Create a GitHub repository (for example, `taipei-training`).
2. Upload `index.html` to the repository root and commit it to the `main` branch.
3. Open **Settings → Pages**.
4. Under **Build and deployment → Source**, select **Deploy from a branch**.
5. Choose branch `main` and folder `/ (root)`, then click **Save**.
6. Wait for the deployment. The site URL will be shown on the Pages settings screen.


## Notes
- This site uses CDN-hosted Tailwind CSS, Leaflet, and Google Fonts.
- Images and map tiles load from external services, so the visitor needs an internet connection.
- A missing local image in the original HTML is handled by its existing online fallback chain.
