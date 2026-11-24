STUDYVAULT AI OFFLINE EDITION

This is an installable Progressive Web App (PWA), not an APK.
It has no Node server, no API key and no cloud AI dependency.

FEATURES
- Save typed notes, PDF files and handwritten-note photos in this browser's IndexedDB storage.
- Organize by subject, chapter, title and optional page number.
- Search saved titles, subjects, chapters and typed note text.
- Offline library helper uses local keyword matching to find relevant saved notes.
- Bookmark items.
- Service worker caches the app shell for offline launch after the first successful online visit.

IMPORTANT LIMITATIONS
- The helper is local smart search, not a generative AI model. It does not invent explanations.
- The app must first be published on an HTTPS static host and opened once online to install/cache it.
- Use Chrome's menu > Add to Home screen / Install app.
- Notes are stored only in this browser on this device. Clearing site data or uninstalling/clearing browser storage may erase notes. Export/backup is not included yet.
- Large PDFs/photos use phone storage. Browser storage quotas apply.
- A PWA opens like an app from its home-screen icon, but it is not a native APK.

PUBLISHING
Upload the contents of this folder to a static HTTPS host (for example GitHub Pages).
No backend/server runtime is required. Do not upload secrets; this project contains no API key.
