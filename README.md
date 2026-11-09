# StreamerX for Windows, web and Android

Movies, shows, anime and Live TV in an original charcoal, cyan and lime interface.

[Download Windows 1.3.0](https://github.com/Benighter/StreamerX-Releases/releases/download/v1.3.0/StreamerX-Setup-1.3.0-x64.exe) · [Open StreamerX](https://streamerx-benighter.vercel.app) · [Download Android 1.3.0](https://github.com/Benighter/StreamerX-Releases/releases/download/v1.3.0/StreamerX-1.3.0.apk) · [Release notes](https://github.com/Benighter/StreamerX-Releases/releases/tag/v1.3.0) · [App catalogue](https://benighters-personal-projects.vercel.app)

Android 8.0 or newer. Package: `com.benighter.streamerx`.

- All five categories: Home, Movies, Shows, Anime and Live TV.
- Automatically looping Spotlight with a gentle image pan, swipes, dots and Pause/Play.
- Top-right Profile with OpenBackend registration, sign-in, sign-out and email password recovery.
- Account-synced saved titles, ratings, watched markers and viewing progress across Android and web, including offline edits and separate libraries for each account.
- Search, genre/year filters, seasons and episodes, library backups and playback resume.
- Dedicated Anime search, account-synced Favourites, and local offline downloads on Windows and Android.
- Centred Android player controls without a persistent Next button; dub preference carries to the next episode with sub fallback when needed.
- Automatic data saving outside Wi-Fi, with manual quality selection.
- Signed update checks on launch and from Settings, with release notes and download verification. Android asks before installation.

Windows and Android save playback progress automatically. In the web player, use Current minute / Save position to sync your position. If embedded playback stays on Still loading, choose **Open player in a new tab** and complete any provider verification there. Guests can keep a local library. Registration email verification is not enabled. Live TV uses a separate Watched account; catalogue, browser verification and playback availability depend on the provider. StreamerX does not host media.

The original local 1.0.0 preview needs this one-time installation to enable automatic update checks.

This repository contains public update manifests, checksums, release notes and app release assets. [Source code](https://github.com/Benighter/StreamerX) is private.

Update feed: https://benighters-personal-projects.vercel.app/releases/streamerx/latest.json

Signing certificate SHA-256: `e06fc96fa24c2fda1653cd7f4badf124d75a15759b0e8c0c47c26f96c8002b62`.

Windows 1.3.0 installs per user with desktop and Start menu shortcuts. Playback stays inside the main app, with Back, fullscreen and resume. Its bundled interface works independently of the hosted website. Windows account sessions use secure storage. Updates verify pinned signed metadata and the installer digest before asking to install and restart. The Windows installer is not Authenticode signed. Android 1.3.0 retains its existing package and signing certificate. Downloaded media stays on each device; media files do not sync between devices.
