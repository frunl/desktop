# frunl/desktop

Public release repository for Frunl Desktop beta builds.

This repository exists only for GitHub Releases. Do not commit DMG binaries to the repository. Release assets are published from the private platform repository by the manual `Desktop Beta Release` GitHub Actions workflow.

## Download

Download the latest beta from:

https://github.com/frunl/desktop/releases/latest

Choose the asset for your Mac:

- `Frunl-macOS-Apple-Silicon.dmg` for Apple Silicon Macs.
- `Frunl-macOS-Intel.dmg` when an Intel build is published.

## Public Beta Warning

Frunl Desktop beta builds are unsigned and unnotarized for now. macOS may warn that it cannot verify the developer. Open the app only if you downloaded it from this repository, and approve it from System Settings if macOS blocks first launch.

## Verify Checksums

Each release includes SHA256 checksum files and a `manifest.json`.

```sh
shasum -a 256 -c Frunl-macOS-Apple-Silicon.dmg.sha256
```

Use `Frunl-macOS-Intel.dmg.sha256` instead if you downloaded the Intel build.

## Release Process

Releases are created by maintainers from `frunl/platform` using manual GitHub Actions dispatch. Publishing requires `FRUNL_DESKTOP_RELEASE_TOKEN` with permission to create releases in this repository.
