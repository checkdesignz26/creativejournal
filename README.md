# Studio Diary (Seamless Creative)

A spiral-notebook diary for pattern designers: journal, moodboards, colour palettes, milestones, sales log, pitches and to-dos. Single-file HTML app, works offline, installs to the iPad home screen.

## Files
- `index.html` – the whole app
- `manifest.webmanifest`, `sw.js`, `icons/` – install-to-home-screen and offline support

## Use
Serve the folder over https (e.g. GitHub Pages: Settings > Pages > Deploy from branch `main`, folder `/`).
- iPad: open the page in Safari > Share > Add to Home Screen
- Desktop Chrome/Edge: install icon in the address bar

Entries are stored on the device (IndexedDB). Use Export / Import in the top bar for JSON backups.

Suite use: link to `index.html` as a tab in the Seamless Creative suite; same file, same data.
