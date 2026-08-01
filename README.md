# Fashion Designer Prototype

Mobile-first static prototype for moderated usability testing with independent bespoke fashion designers.

## Local preview

Run a static web server in this folder and open `http://localhost:8000/`.

## Deployment

This repository is ready for Vercel with `index.html` as its entry point. No build command or environment variables are required.

After the GitHub repository is connected to Vercel, every push to the default branch creates a new production deployment at the same public URL.

## Update workflow

1. Replace or edit `index.html` while preserving its self-contained assets.
2. Preview and test the reset flow locally.
3. Commit the change and push it to the default branch.
4. Vercel deploys the update automatically.

## Test reset

Use the prototype's reset control before each participant session. The app stores session data in the browser's session storage, so each participant/device starts independently.
