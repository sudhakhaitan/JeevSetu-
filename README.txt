JeevSetu V2-5-134 — Persistent Multi-Patient Archive Fix

Upload index.html to the SAME GitHub repository and Pages URL you are testing.
This version adds periodic local archive saving, pagehide/visibility saving, an archive count/status message, and an attempt to verify each save.
Patient data remains in the current browser's localStorage; it is not uploaded to GitHub or a server.
Use the exact same GitHub Pages URL and Chrome profile to retrieve records. Different Pages URLs/origins have separate localStorage.
This patch has not been verified on the user's tablet. Test with dummy data first and download JSON backups before clinical use.
