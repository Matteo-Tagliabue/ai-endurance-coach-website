# AI Endurance Coach website

Simple static website prepared for GitHub Pages.

## Files

- `index.html` — landing page
- `privacy.html` — privacy policy
- `styles.css` — design and responsive layout

## Before publishing

Replace every occurrence of:

```text
YOURDOMAIN.com
```

with the domain you own, for example:

```text
aiendurancecoach.com
```

The email, website and privacy policy should use the same parent domain for the Garmin Connect Developer Program.

## Publish with GitHub Pages

1. Create a new public GitHub repository, for example `ai-endurance-coach-site`.
2. Upload these three files to the root of the repository.
3. Open the repository settings.
4. Go to **Pages**.
5. Under **Build and deployment**, select:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`
6. Save.
7. GitHub will display the public website address after deployment.

## Connect a custom domain

After buying your domain:

1. In GitHub repository **Settings → Pages**, enter the custom domain.
2. In your domain provider's DNS settings, create the records requested by GitHub.
3. Enable **Enforce HTTPS** when available.
4. Use the same domain for:
   - the website;
   - the privacy policy;
   - your personalized email address.

Example:

```text
Website: https://aiendurancecoach.com
Privacy: https://aiendurancecoach.com/privacy.html
Email: matteo@aiendurancecoach.com
```

## Important

The privacy page is a practical starter template, not formal legal advice. Update it to reflect the services and processors actually used before launching publicly.
