# Frunl Desktop

Frunl Desktop is the macOS public beta for turning rough product work into clearer build plans before code is written.

This repository is the public home for Frunl Desktop downloads, release notes, bug reports, and feature requests.

## Download

Download the latest public beta from:

https://github.com/frunl/desktop/releases/latest

Choose the asset for your Mac:

- `Frunl-macOS-Apple-Silicon.dmg` for Apple Silicon Macs.
- `Frunl-macOS-Intel.dmg` for Intel Macs, when an Intel build is available.

## Public Beta Note

Frunl Desktop beta builds may be unsigned and unnotarized while the product is in public beta. macOS can warn that it cannot verify the developer, or ask you to approve opening the app from System Settings.

Only open downloads from this repository's GitHub Releases page.

## Verify Downloads

Each release includes SHA256 checksum files and a `manifest.json`.

```sh
shasum -a 256 -c Frunl-macOS-Apple-Silicon.dmg.sha256
```

Use `Frunl-macOS-Intel.dmg.sha256` instead if you downloaded the Intel build.

## Report A Bug

Use the [bug report form](https://github.com/frunl/desktop/issues/new?template=bug_report.yml) when Frunl Desktop crashes, fails to open, gets stuck, or behaves differently from what you expected.

Please include:

- Frunl Desktop version.
- macOS version.
- Mac architecture: Apple Silicon or Intel.
- Steps to reproduce the problem.
- Screenshots or logs when they help explain the issue.

Do not include passwords, API keys, access tokens, private customer data, or other sensitive information in public issues.

## Request A Feature

Use the [feature request form](https://github.com/frunl/desktop/issues/new?template=feature_request.yml) to describe a workflow gap, missing capability, or improvement that would make Frunl Desktop more useful.

Good requests explain the problem, who it affects, the current workaround, and what outcome would feel successful.

## Contributing

Read [CONTRIBUTING.md](./CONTRIBUTING.md) before opening issues or pull requests.

This public repository does not accept direct code contributions. Please use issues to report problems or request improvements.

## Support And Privacy

For account-specific support, contact support@frunl.com.

For privacy requests or sensitive data concerns, contact privacy@frunl.com instead of opening a public issue.
