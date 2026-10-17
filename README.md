# Peel

**Files, Unwrapped.** Peel is a macOS unarchiver from [Snack Studio](https://www.snackstud.io/peel). Double-click an archive and it opens like a folder in Finder; extract with Finder Services (**Peel**, **Peel to…**, **Peel & Reveal**); preview with Quick Look.

## Download

Get **`Peel-<version>.dmg`** from [Releases](https://github.com/SnackStudio/peel-releases/releases), open it, and drag Peel to Applications. Or install with Homebrew:

```bash
brew install --cask snackstudio/tap/peel
```

Peel updates itself: **Peel → Check for Updates…**

## Formats

ZIP (and ZIP-based files such as EPUB, JAR, APK, CBZ, Office documents), RAR including multipart sets, 7z, and TAR with gzip, bzip2, xz or zstd, plus single gzip, bzip2, xz and zstd files. Encrypted archives prompt once for the password.

## Requirements

macOS 13 or later, on Apple silicon or Intel. Peel and its disk image are signed with Snack Studio's Developer ID and notarized by Apple.

For same-window browsing, allow **System Settings → Privacy & Security → Automation → Peel → Finder** when asked.

## Safety

Peel never writes outside the folder you extract to and never follows links out of it, whatever the archive contains, and it stops archives that would expand to an unreasonable size.

## License

Peel is free to download and use. It is proprietary software of Snack Studio; this repository hosts release downloads only. Third-party components are listed in `Third-Party Notices.txt` in the disk image.

Questions and bug reports: [Issues](https://github.com/SnackStudio/peel-releases/issues).
