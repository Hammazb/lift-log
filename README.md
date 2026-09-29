# Lift Log (standalone)

Static site, no build step. Data is saved in the browser on each device (localStorage). Use History > Export for CSV backups.

## Deploy on Vercel
Option A (GitHub): push this folder to a new GitHub repo, then Vercel > Add New > Project > import it. Framework preset: Other. No build command, output directory is the root.
Option B (CLI): `npm i -g vercel`, then run `vercel --prod` inside this folder.

## Put it on your iPhone
Open the Vercel URL in Safari > Share > Add to Home Screen. It opens full screen and works offline.

## Updating
Edit index.html, bump VERSION in sw.js (e.g. lift-log-v2), redeploy.
