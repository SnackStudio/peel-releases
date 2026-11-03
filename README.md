# Peel

**Files, Unwrapped.** Peel is a free Mac unarchiver from [Snack Studio](https://www.snackstud.io). Double-click a ZIP, RAR, 7z or TAR archive and it opens like a folder in Finder; preview it with Quick Look, or extract it with **Peel**, **Peel to…** and **Peel & Reveal**.

[filesunwrapped.com](https://filesunwrapped.com) · [Download](https://github.com/SnackStudio/peel-releases/releases/latest) · [Support](https://filesunwrapped.com/support) · [Privacy](https://filesunwrapped.com/privacy)

## Download

From the [latest release](https://github.com/SnackStudio/peel-releases/releases/latest), open **`Peel-<version>.pkg`** and follow the installer. Or open `Peel-<version>.dmg` and drag Peel to Applications; opened from the disk image or Downloads, Peel offers to move itself. Or install with Homebrew:

```bash
brew install --cask snackstudio/tap/peel
```

Peel updates itself: **Peel ▸ Check for Updates…**

## What it opens

- **Archives:** ZIP, RAR (including multipart sets), 7z (including solid), and TAR plain or compressed with gzip, bzip2, xz or zstd; single gzip, bzip2, xz and zstd files.
- **Files that are ZIPs underneath:** EPUB, JAR, WAR, EAR, APK, CBZ, USDZ, 3MF, Office and OpenDocument files.
- **Also:** installer packages (`.pkg`, `.mpkg`), comic books (`.cbz`, `.cbr`, `.cb7`, `.cbt`), Sketch files, and single-file Pages, Numbers and Keynote documents.
- **Passwords:** ZIP (ZipCrypto and WinZip AES), 7z and RAR ask once, and Peel can remember the password in your Keychain. **Compress with Password…** in Finder makes AES-256 ZIPs.

## Requirements

macOS 13 Ventura or later, on Apple silicon or Intel. Peel, its installer and its disk image are signed with a Developer ID and notarized by Apple.

## Safety and privacy

Peel never writes outside the folder you extract to: entries like `../` or absolute paths are refused, and a symbolic link in an archive can't send a file anywhere else. It stops archives that would expand to an unreasonable size. Your files never leave your Mac, and the app has no analytics; see the [privacy policy](https://filesunwrapped.com/privacy).

## License

Peel is free to download and use. It is proprietary software of Snack Studio; this repository hosts release downloads only. Third-party components are listed in `Third-Party Notices.txt` with every release.

Questions and bug reports: [Issues](https://github.com/SnackStudio/peel-releases/issues), or [hello@snackstud.io](mailto:hello@snackstud.io).
