FocusFlow — Premium Daily Planner PWA
Mobile-first Bangla-friendly task manager, weekly habit tracker, daily planner, notes, goals, dark/light theme, local autosave, JSON backup/restore, weekly task chart and offline app-shell caching.
Update your existing GitHub repository
Download and extract this ZIP.
Open your existing `focusflow` repository.
Replace `index.html`, `manifest.json`, `sw.js`, `icon-192.png`, and `icon-512.png` with the files from this folder. Keep README and `.nojekyll` if already present.
Commit changes.
Wait for GitHub Pages deployment, then reload the published site.
Important
Existing localStorage key `focusflow-data` is retained to preserve existing app data on the same origin.
If you have older cached app files, close/reopen the app or refresh after deployment. If needed, remove the old home-screen shortcut and add it again.
Data is stored only in the current browser/device. Use JSON backup regularly.
