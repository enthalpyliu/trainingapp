# Strength Log PWA

A first-version, offline-friendly workout tracker for the 12-week A/B plan.

## Install on Android
A Progressive Web App must be served from HTTPS (or localhost) for installation and offline caching. The simplest route:

1. Create a free GitHub repository and upload the contents of this folder (not the enclosing ZIP).
2. In the repository, open **Settings → Pages**.
3. Under Build and deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
4. Wait for the published HTTPS address. Open it in Chrome on Android.
5. Chrome menu (⋮) → **Install app** or **Add to Home screen**.

You can also host the folder on Netlify or another static HTTPS host. No backend is required.

## Data
Workout logs and measurements are saved in browser local storage on this device. Use **Data → Export backup** regularly. Importing a backup replaces current local data.

## Important
- This app is a tracker, not medical advice or a diagnostic tool.
- The chest-supported row requires an incline bench. If unavailable, skip it rather than doing an unsupported bent-over row.
- Because of the history of significant episodic low-back pain, get an individualized PT/clinician assessment before progressing to heavy lifting.
- The exercise list and loads are conservative starting suggestions. Stop or modify movements that provoke symptoms.
