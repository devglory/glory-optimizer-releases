# Glory Optimizer

See where your disk space went and clean it up safely. macOS 13+, Apple Silicon (M1 or newer).

This repository only hosts downloads and automatic updates.

## Install

1. Download the `.dmg` from the [latest release](https://github.com/devglory/glory-optimizer-releases/releases/latest).
2. Open it and drag **Glory Optimizer** into **Applications**.
3. Open it. macOS will say it can't verify the developer: click **Done**, then go to
   **System Settings › Privacy & Security**, scroll down and click **Open Anyway**.
4. Follow the yellow banner in the app to turn on **Full Disk Access**, then reopen the app.

If macOS says the app "is damaged", run this once in Terminal and open it again:

```bash
xattr -cr "/Applications/Glory Optimizer.app"
```

## Updates

The app updates itself. When a new version is ready you'll see a **Restart** button.
After an update, give Full Disk Access again: in **System Settings › Privacy & Security › Full
Disk Access**, select Glory Optimizer, remove it with **−**, then add it back with **+**.

## Privacy

Glory Optimizer doesn't collect, upload or share your files or any personal data. Scans, history
and settings stay on your Mac. The only network request is the update check to GitHub.

## Terms

© 2026 Svetoslav Halachev. All rights reserved. Free to install and use; provided as is, without
warranty. Please don't redistribute it. Full terms: [LICENSE](LICENSE). Open-source components
and their licenses are listed in the app under **Settings › About › Open-source licenses**.
