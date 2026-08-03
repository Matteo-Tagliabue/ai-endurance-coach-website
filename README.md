# AI Endurance Coach website

Static website hosted with GitHub Pages.

## Production details

- Website: `https://aiendurancecoach.app`
- Privacy policy: `https://aiendurancecoach.app/privacy.html`
- Contact email: `contact@aiendurancecoach.app`

The website, privacy policy and contact email use the same parent domain for the Garmin Connect Developer Program.

## Files

- `index.html` — landing page
- `privacy.html` — privacy policy
- `styles.css` — responsive design

## Publish updates

After editing the files:

```bash
git add .
git commit -m "Update website"
git push
```

GitHub Pages will redeploy automatically from the `main` branch.

## GitHub Pages configuration

Repository settings:

- Source: `Deploy from a branch`
- Branch: `main`
- Folder: `/ (root)`
- Custom domain: `aiendurancecoach.app`
- Enforce HTTPS: enabled

## Important

The privacy page is a practical starter policy and should be kept aligned with the services and data processors actually used by the platform.
