# ZF Menu Designer V5 — GitHub + Render

## Deploy
1. Create a new GitHub repository (e.g. `zf-menu-designer`).
2. Upload **index.html**, **decorations.png**, and **render.yaml** from this ZIP to the repository root. Commit changes.
3. In Render select **New → Blueprint**, connect GitHub, and choose this repository. Render reads `render.yaml` and creates a static site.
4. Open the `onrender.com` address Render supplies. Do not assume the URL until Render confirms it.

Alternative: Render **New → Static Site** → connect repository → Build Command `echo ready` → Publish Directory `.`.

## Updating
Edit the files in GitHub, commit changes, and Render will redeploy automatically. If the old design persists, hard refresh the browser (Ctrl+Shift+R).

## Test
Choose a template and confirm it opens the editor; try changing restaurant name, adding and dragging decorations, and logo upload.
