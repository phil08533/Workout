# WORKOUT — Train with purpose

A mobile-first, static workout tracker built for GitHub Pages. No framework, backend, account, or paid service is required.

## Features
- Phil's Monday chest/triceps and Tuesday back/biceps split is the default plan, with optional legs and core days.
- Track actual weight, reps, completed sets, session notes, history, training volume, and best logged weights.
- Edit the plan, add workout days and exercises, and create custom routines.
- Export/import a shareable workout-plan JSON file or a full local-data backup.
- Dark, graphite, and light themes.
- Optional daily reminder (works while the app is open; browser notification permission may be required).
- Installable/offline app shell through the service worker.
- Exercise-specific YouTube form-demo search links and links to the supplied playlists and ab routine.

## Publish with GitHub Pages
1. Open the repository's **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select **main** and **/(root)**, then save.
4. Wait for GitHub Pages to finish deploying; the URL appears in the Pages settings.

## Local data and backups
All app data is stored in this browser's localStorage. It is not synced between devices or users. Use **Settings → Download full backup** to save history and plans, or **Export workout plan** to share a routine. Import the JSON file on another device to restore it. Clearing history and plans deletes both; export first if you want to keep a copy.

## Notes
The exercise-demo links open YouTube search results for the named movement rather than claiming a specific video is medically or technically vetted. Exercise names and cues can be edited. Use conservative loads, prioritize form, and stop if you experience pain or unusual symptoms.
