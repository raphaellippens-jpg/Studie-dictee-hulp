STUDYSONIC V1.0 — GITHUB PAGES

FILES
- index.html + style.css: version hub / start screen
- versions/v1/: the V1.0 study app

PUBLISH ON GITHUB
1. Create one GitHub repository.
2. Upload the contents of this ZIP (keep the folders).
3. In the repository, open Settings → Pages.
4. Choose Deploy from a branch, select main and / (root), then Save.
5. Open the GitHub Pages URL. The version hub is the start screen.

ADDING A FUTURE VERSION
1. Create a folder such as versions/v2/.
2. Put that version's index.html, style.css and app.js inside it.
3. Edit the root index.html and add another version card linking to:
   versions/v2/index.html
4. Commit the changes. The same repository and Pages URL will show the new version.

NOTES
- Microphone recording generally requires HTTPS. GitHub Pages provides HTTPS.
- Recordings and theme settings are saved in this browser on this device.
- Audio recordings use IndexedDB. Clearing browser website data can delete them.
- This is a static website; it does not sync recordings between devices.
