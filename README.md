# Attendance data

The starting repo for the [attendance app](https://rsamyak.github.io/intu-attendance-tracker/).  On GitHub, use this template and choose Private.  A fork of this public repo cannot be made private.

`attendance.json` starts as one blank user, the record a new browser holds.  `shared.json` is the quota thresholds and the shared holidays built into the page.  The app reads and writes both.  `shared.json` changes when a browser edits a holiday or a threshold and syncs.

`sample.json` is a fake record for trying Load.  It is not the starting file.  It has three users, every status, planned and confirmed days, notes, and the quota change in April 2025.  Leave falls on weekdays only.

## Connect

1. Make a fine-grained token for your private repo only, with Contents read and write.
2. In the app, open Admin, Sync.  Paste `owner/repo` and the token, then Connect.
3. Share link opens the same repo on another device.  On iPhone, open it in Safari and add it to the Home Screen.  The icon keeps the link, and the token travels in that link.
