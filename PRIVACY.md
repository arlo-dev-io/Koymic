# Koymic privacy policy

_Last updated: 2 November 2026. This is a plain-language draft, have it reviewed before wide publication._

Koymic works without an account and then stores everything on your device only. This policy covers the
optional **account & sync** feature.

## What is stored when you create an account

Stored on Supabase (project region: West EU):

- Your **username** (as an internal sign-in address `username@users.koymic.app`) and a **hashed password**.
  We can't see your password.
- One **synced backup** per account: library entries (titles, source IDs, URLs), categories, chapter
  read/bookmark/last-page state, reading history and tracker links (which entry on which tracker, not your
  tracker login).
- Technical metadata: sync version number, checksum, size, last-updated time and your device model name.

## What is not stored

Tracker logins, source/extension settings, app settings, downloaded chapters, and your device storage paths
stay on the device. Koymic includes no analytics or crash-reporting service.

## How it is protected

Data is sent over HTTPS. Row Level Security on the database lets each signed-in user read and write only their
own row. The session token is kept in the app's private storage and is excluded from backups.

## Your control

- **Sign out** at any time in Settings → Account & sync.
- **Delete account and cloud data** in the same screen. This permanently removes the account and its synced
  backup. Your on-device library is unaffected.
- Usernames have no e-mail attached, so there is **no password reset**.

## Contact

[add your contact e-mail here]
