# Liber

Ebook library manager: import your books, browse and download free titles from Project Gutenberg and Standard Ebooks, send books directly to your device, and track your reading — 100% local, no accounts required.

> Beta · Linux / macOS / Windows

---

## Download

→ **[Latest release](https://github.com/liberebooks/liber/releases/latest)**

| Platform | File |
|---|---|
| Linux (Debian/Ubuntu/Kali) | `liber_x.x.x_amd64.deb` |
| Linux (universal) | `liber_x.x.x_amd64.AppImage` |
| macOS | `liber_x.x.x_x64.dmg` |
| Windows | `liber_x.x.x_x64-setup.exe` |

---

## Install

**Linux — .deb**
```sh
sudo dpkg -i liber_*.deb
```

**Linux — AppImage**
```sh
chmod +x liber_*.AppImage
./liber_*.AppImage
```

**macOS**
Open the `.dmg` and drag Liber to Applications.

**Windows**
Run the installer. SmartScreen may warn on first run since the binary isn't signed yet — click "More info" → "Run anyway".

---

## Features

### Library
- Import EPUB, PDF, MOBI, AZW3, FB2, CBZ, CBR
- Covers and metadata fetched automatically from OpenLibrary and Google Books
- Full-text search across title, author, and tags — results in under 50ms
- Filter by format, language, read status, or tags
- Works fast with thousands of books

### Reader
- Built-in EPUB reader: paginated, adjustable font size, table of contents, keyboard navigation
- Built-in PDF reader: zoom, page navigation, Retina rendering
- Reading position saved automatically per book

### Devices
- USB detection for Kindle, Kobo, PocketBook, BOOX, reMarkable, and 40+ other devices
- Direct transfer — converts to the right format automatically if needed
- Browse and delete files on a connected device from inside the app
- Send to Kindle via email (SMTP, works with Gmail App Passwords)

### Metadata
- Edit title, author, publisher, year, language, tags, and description
- One-click restore per field to recover the original value from the source file
- Tags with color labels, visible on book cards and usable as filters

### Discover
- Browse and import from Project Gutenberg (70,000+ public domain books)
- Browse and import from Standard Ebooks (curated, properly formatted editions)
- Import reading history from a Goodreads CSV export — matches books you already have and carries over ratings, shelves, and read dates

### Stats
- Monthly chart of books added and finished
- Reading streaks and total time logged
- Breakdown by format and language

### Other
- Dark and light theme
- Available in English and Spanish
- In-app updater (Settings → About & Updates)
- No telemetry

---

## Coming soon

- Comic reader (CBZ/CBR)
- Highlights and annotations in the built-in reader
- Cloud sync (opt-in, WebDAV/iCloud)
- AI features: summaries, smart tagging, reading assistant (opt-in, local-first)
- Native conversion engine — Liber currently uses Calibre's `ebook-convert` for format conversion. A built-in Rust-based engine is in development and will replace it, removing the external dependency entirely.

Have a feature request or suggestion? Open an issue or find us on social media.

---

## Format conversion

Conversion requires Calibre's `ebook-convert`. On first launch Liber will ask to download it (~120 MB). You can also skip this and point it to an existing Calibre installation. The engine is downloaded separately and is not bundled with Liber.

---

## Community

- Reddit: [r/liberapp](https://reddit.com/r/liberapp)
- Twitter / X: [@liberebooks](https://x.com/liberebooks)
- Instagram: [@liberebooks](https://instagram.com/liberebooks)
- Issues & suggestions: [GitHub Issues](https://github.com/liberebooks/liber/issues)

---

## License

© 2026 Liber. All rights reserved.  
Redistribution of these binaries without permission is prohibited.

Calibre/ebook-convert: GPL-3.0 (downloaded separately, not bundled by Liber)
