# Nooky

**The notch, made useful.** Downloads and website for Nooky, a notch-native companion app for macOS, Windows and Linux.

- **Website:** https://waseemmaya.github.io/nooky/
- **Download:** the [latest release](https://github.com/waseemmaya/nooky/releases/latest)

| System | File |
| --- | --- |
| macOS, Apple Silicon | `Nooky_aarch64.dmg` |
| macOS, Intel | `Nooky_x64.dmg` |
| Windows 10/11 | `Nooky_x64-setup.exe` or `Nooky_x64.msi` |
| Linux (x86_64) | `Nooky_amd64.AppImage` or `Nooky_amd64.deb` |

Builds are unsigned for now. macOS: after moving Nooky to Applications run `xattr -dr com.apple.quarantine /Applications/Nooky.app` once. Windows: SmartScreen → *More info → Run anyway*.

This repository holds the website (published with GitHub Pages from `main`) and the release files. The source code lives in the `nooky-app` repository, whose Release workflow builds every platform and publishes the files here.
