# Remindian Homebrew Tap

Official Homebrew tap for [Remindian](https://github.com/Santofer/Remindian) — a native macOS menu-bar app that syncs your Obsidian tasks to Apple Reminders, Things 3, Todoist, or TickTick.

## Install

```sh
brew tap Santofer/tap
brew install --cask remindian
```

Or in one line:

```sh
brew install --cask Santofer/tap/remindian
```

## First launch

Remindian isn't notarized yet, so on first launch macOS Gatekeeper will warn about an unverified developer. Right-click the app in `/Applications` and choose **Open** once to bypass it. After that it launches normally.

## Updates

Remindian has a built-in updater that checks GitHub Releases on launch and every 24 hours, so the app keeps itself current — that's why the cask is marked `auto_updates true` and `brew upgrade` intentionally leaves it alone. To force a reinstall of the latest packaged build:

```sh
brew reinstall --cask remindian
```

## Requirements

macOS 13 (Ventura) or later.

## Links

- App & source: https://github.com/Santofer/Remindian
- Issues: https://github.com/Santofer/Remindian/issues
- Releases: https://github.com/Santofer/Remindian/releases
