# Blook — Bookmark Lookup

![Blook - Bookmark Lookup](https://raw.githubusercontent.com/dai530/blook-support/refs/heads/main/assets/blook-banner.png 'Blook - Bookmark Lookup')

## Screenshot

![Blook Screenshot](https://raw.githubusercontent.com/dai530/blook-support/refs/heads/main/assets/blook-screenshot.png 'Blook Screenshot')

## Features

- Minimalist layout focusing on a cleaner, better bookmark display
- Drag-and-drop user interface for effortless management
- Portable SQLite database – makes it easy to back up and synchronise through the cloud drive of your choice
- Instant search via a global shortcut (Cmd + K on macOS, Ctrl + K on Windows)

## Database

When the app is initialised for the first time, it automatically generates a SQLite database file in the following default directory depending on your system:

- **macOS**: `/Users/<Username>/Library/Application Support/me.daviddai.blook/blook.db`
- **Windows**: `C:\Users\<Username>\AppData\Local\me.daviddai.blook\blook.db`

If you want to access the same database across multiple computers, you can sync it using a cloud storage provider (e.g., iCloud, OneDrive, Dropbox):

1. Back up your existing `blook.db` file to your preferred cloud drive folder.
2. Go to the `Settings` page within the app.
3. Update the database path to point to the new location on your cloud drive.

## Feedback and Contributions

If you encounter any issues, want to request a feature, or have general feedback, please head over to the [Issues](https://github.com/dai530/blook/issues) page of this repository.

To help keep things organised, please apply the appropriate tag when creating a new issue.

- `bug` – For reporting unintended behavior or errors in the app.
- `enhancement` – For proposing new features, UI tweaks, or functionality upgrades.
- `question` / `feedback` – For asking questions or sharing thoughts on how to improve Blook.
