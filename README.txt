BETWEEN THE PAGES — ANDROID-FRIENDLY STARTER

This project supports PDF and EPUB import in a browser-based app prototype.
It uses IndexedDB for imported book files and localStorage for library metadata.

IMPORTANT:
- This is a PWA starter project, not an APK yet.
- To install it as a proper home-screen web app, it must be served over HTTPS (for example, a free static hosting service).
- On Android Chrome, open the hosted site menu and choose "Install app" or "Add to Home screen".
- The PDF.js and JSZip libraries are loaded from CDNs, so first use needs internet.
- EPUB rendering in this starter is chapter-based and may not support every unusual EPUB layout.
- Realistic page curl and online English-to-Myanmar translation are not implemented yet.
- Keep original e-books and export backups. Large JSON backups can become very large.

FILES:
index.html — app
manifest.webmanifest — installable web app metadata
sw.js — basic offline shell cache
