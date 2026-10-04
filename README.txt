ProcessTracer, on-device version
================================
Your data stays on the device you use it on. These files are only the app;
they never contain your data.

1. Put the app online once (free, about 10 minutes, on a computer)
   a. Sign in at github.com (a free account works).
   b. Click + (top right), then New repository. Name it processtracer,
      keep it Public, click Create repository.
   c. Click "uploading an existing file". Drag in every file from this
      folder (the files, not the folder). Click Commit changes.
   d. Open Settings, then Pages. Under Build and deployment choose
      Source: Deploy from a branch, Branch: main, folder: / (root). Save.
   e. After a minute or two the Pages screen shows your address:
      https://YOUR-USERNAME.github.io/processtracer/

2. Install it on your iPhone
   a. Open that address in Safari.
   b. Tap Share, then Add to Home Screen, then Add.
   c. From then on, open ProcessTracer from the home screen icon. Start
      logging there, not in Safari: the home screen app keeps its own data,
      works without signal once opened, and iOS will not clear it.
   Android: open the address in Chrome, then menu, Install app.

3. Back up and sync
   - Settings > Back up now makes one .zip: your data, photos and rates.csv.
     Save it to Files (iCloud Drive, Google Drive) or AirDrop it.
   - On another device, open the same address and use Settings > Import a
     backup. For each sample, template and logged run the newest edit wins,
     and deletions carry over. Edit a given sample on one device at a time.
   - On a computer in Chrome or Edge you can also pick a folder in Settings;
     backups are then written there automatically.
   - Coming from the claude.ai version: there, Settings > Full backup (JSON),
     then import that file here. Text carries over; photos do not.

4. Updating the app later
   a. In the app: Settings > Back up now (just in case).
   b. Upload the new files to the same repository, replacing the old ones.
      Keep the same repository name, so the address stays the same.
   c. Open the app with signal: it downloads the update in the background
      but still shows the old version. Close it and open it again to run the
      new one. Your samples, photos and settings stay as they were.

Notes
- The repository holds only app code. Anyone with the address gets an empty
  copy of the app; nobody can see your data.
- Each browser keeps separate data: Safari and the home screen app on the
  same phone are separate, and so is each browser on your computer.
- The app makes no network requests except loading its own files.
