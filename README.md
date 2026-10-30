# Coin Grind — Windows releases

This repository distributes **signed Windows binary packages only** for Coin Grind.

- The application's source code and development history live in a **separate private repository**.
- Published releases must contain a Windows application ZIP and a matching JSON release index signed with the project's Ed25519 release key.
- Release packages must not contain Python source files, Git history, credentials, configuration secrets, trading profiles, or user data.
- Release creation remains disabled until Windows installation, upgrade, data retention and rollback have been tested.
- Do not use GitHub's automatic "Source code (zip/tar.gz)" downloads as application updates.

**Status (2026-10-30):** Channel prepared. No approved signed application release has been published yet.