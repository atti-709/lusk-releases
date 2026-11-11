# Lusk releases

Downloads and the auto-update feed for **Lusk**, the macOS app that turns podcasts and sermons into vertical shorts. The source code is private; this repository holds only the built app.

- **Download:** the newest `Lusk-<version>-arm64.dmg` under [Releases](../../releases/latest) (Apple Silicon, macOS 13 or newer).
- **First launch:** the app is not notarized yet, so macOS blocks it once. Run `xattr -cr /Applications/Lusk.app`, then open it.
- **Updates:** installed apps read `latest-mac.yml` from the latest release here and offer the update themselves.

The release workflow (`.github/workflows/release.yml`) builds the app from the private source with a read-only deploy key and publishes it here.
