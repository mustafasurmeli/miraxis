# MIRAXIS - GitHub Pages Setup

## How to Deploy

1. **Create a repository** named `miraxis` on GitHub.

2. **Push this project** (or just the `docs/` folder) to the `main` branch.

3. **Enable GitHub Pages:**
   - Go to your repository on GitHub.
   - Navigate to **Settings** > **Pages**.
   - Under **Source**, select **main** branch and **/docs** folder.
   - Click **Save**.

4. **Wait a few minutes** — your site will be live at:
   ```
   https://surmeli.github.io/miraxis/
   ```

## Pages

| Page | URL | Description |
|------|-----|-------------|
| Privacy Policy | `/index.html` | English privacy policy |
| KVKK | `/kvkk.html` | Turkish KVKK compliance text |
| Terms of Service | `/terms.html` | English terms of service |

## Update These URLs In Your App

After the site is live, update the following files with the actual URLs:

- `PrivacyPolicyScreen.kt` — privacy policy link
- `ConsentDialog.kt` — consent dialog links
- **Google Play Console** — Store listing > Privacy policy URL
