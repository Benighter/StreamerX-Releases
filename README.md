# StreamerX for Windows, web and Android

Movies, shows, anime and Live TV in an original charcoal, cyan and lime interface.

[Download Windows 1.2.0](https://github.com/Benighter/StreamerX-Releases/releases/download/v1.2.0/StreamerX-Setup-1.2.0-x64.exe) · [Open StreamerX](https://streamerx-benighter.vercel.app) · [Download Android 1.1.0](https://benighters-personal-projects.vercel.app/releases/streamerx/1.1.0/StreamerX-1.1.0.apk) · [Release notes](https://github.com/Benighter/StreamerX-Releases/releases/tag/v1.2.0) · [App catalogue](https://benighters-personal-projects.vercel.app)

Android 8.0 or newer. Package: `com.benighter.streamerx`.

- All five categories: Home, Movies, Shows, Anime and Live TV.
- Automatically looping Spotlight with a gentle image pan, swipes, dots and Pause/Play.
- Top-right Profile with OpenBackend registration, sign-in, sign-out and email password recovery.
- Account-synced saved titles, ratings, watched markers and viewing progress across Android and web, including offline edits and separate libraries for each account.
- Search, genre/year filters, seasons and episodes, library backups and playback resume.
- Signed update checks on launch and from Settings, with release notes and download verification. Android asks before installation.

Windows and Android save playback progress automatically. In the web player, use Current minute / Save position to sync your position. If embedded playback stays on Still loading, choose **Open player in a new tab** and complete any provider verification there. Guests can keep a local library. Registration email verification is not enabled. Live TV uses a separate Watched account; catalogue, browser verification and playback availability depend on the provider. StreamerX does not host media.

The original local 1.0.0 preview needs this one-time installation to enable automatic update checks.

This repository contains only public update manifests, checksums, release notes and signed APK release assets. [Source code](https://github.com/Benighter/StreamerX) is private.

Update feed: https://benighters-personal-projects.vercel.app/releases/streamerx/latest.json

Signing certificate SHA-256: `e06fc96fa24c2fda1653cd7f4badf124d75a15759b0e8c0c47c26f96c8002b62`.

Windows 1.2.0 installs per user with desktop and Start menu shortcuts. Its bundled interface and separate player work independently of the hosted website. Windows account sessions use secure storage. Updates verify pinned signed metadata and the installer digest before asking to install and restart. The Windows installer is not Authenticode signed. Android remains 1.1.0.
