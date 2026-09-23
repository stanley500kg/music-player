# GitHub Music Player

Put supported audio files (`MP3`, `WAV`, `OGG`, `M4A`, `FLAC`, `AAC`, or `Opus`) in `music/`, and optional artwork in `picture/`. Enable GitHub Pages for the repository root. The app discovers the repository from the Pages URL; for local preview, open Settings and enter `owner / repository` and the branch.

The player is a static, dependency-free PWA. It includes queue and playlist persistence, IndexedDB/localStorage backup, GitHub tree caching and incremental refresh, responsive desktop/mobile players, Favorites and History, filename/embedded metadata fallback, dynamic cover background, EQ presets, normalization, sleep timer, Media Session, Wake Lock, Picture-in-Picture graceful fallback, LRC lyrics, context menus, offline shell caching, and GitHub Pages subpath-safe assets.

No downloaded dependencies or generated binaries are required.
