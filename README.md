# My Gut Diary
A free, offline-capable personal food, nutrition, symptom and weight diary. No calories are tracked or shown.

## Publish for free with GitHub Pages
1. Create a free account at https://github.com/ (if you don't already have one).
2. Create a **public** repository named `my-gut-diary`. Do not upload your personal diary backups; the repository contains only app code.
3. Select **Add file → Upload files** and upload all six files in this folder (`index.html`, `app.js`, `sw.js`, `manifest.webmanifest`, `icon-192.png`, `icon-512.png`). Commit changes.
4. Open repository **Settings → Pages**. Under **Build and deployment**, select **Deploy from a branch**, branch **main**, folder **/(root)**, then **Save**.
5. After Pages deploys, open `https://YOUR-USERNAME.github.io/my-gut-diary/` in Safari on iPhone. Tap **Share → Add to Home Screen → Add**.
6. Log a test meal, close and reopen the app, and verify it persists. Export a backup from Settings regularly and store it privately.

## Notes
- Your entries are stored locally in browser storage on the device. They are not uploaded to GitHub. Browser data removal or changing devices can erase them; export backups regularly.
- Food estimates come from a small illustrative starter dataset, **not a verified clinical nutrition database**. Portions and food tags are approximate. Free-text entries intentionally have no nutrient estimate.
- Pattern counts are simple temporal summaries, not causal inferences or medical diagnoses.
- Reminders are not yet built in. Use the iPhone Reminders app for meal and vitamin reminders.
- The app runs offline after a successful initial load on HTTPS. Updates may require reopening or refreshing while online.
- GitHub Pages requires a public repository on the free plan; the code is public but your diary records remain local.
