# The Digital Portal for Plants — starter project

## What is included
- `index.html`: responsive, mobile-first plant catalogue.
- Search across plant names and taxonomy; filter by family and growth habit.
- View, add and edit plant records.
- Import/export a JSON backup.
- Records are saved in the current browser using localStorage.

## Open on Android
1. Download and extract the ZIP.
2. Open `index.html` using a code editor/HTML preview app that supports JavaScript, or upload the folder to a static host such as GitHub Pages or Netlify.
3. For an online link, create a repository and upload `index.html`, then enable GitHub Pages, or use Netlify's manual deploy from its website. You can do this from a mobile browser, although uploading multiple files is easier with a file manager.

## Important limitations
This is a working front-end prototype, not a multi-user database. Browser data stays on the same browser/device and can be lost if site data is cleared. Export JSON backups regularly. Hosting the file online makes the catalogue viewable but does not sync edits between users. A shared admin login/database requires a backend service and configuration.

## Academic data quality
The starter records include scientific names transcribed from the dissertation's taxonomic matrix. Missing family, genus/species breakdown, local name, habit, field site, and image are left blank or marked “Not recorded” rather than guessed. Check spellings and all botanical details against the original dissertation and field notes before submitting.
