# Roc Editor

A cross-platform JSON desktop workspace for Windows, macOS and Linux. This public repository contains official installers, signed update archives and release notes only. Application source remains private.

[Download the latest release](https://github.com/roc198419/roc-editor-releases/releases/latest)

## Features

- Multiple file tabs with JSON syntax highlighting and validation
- Find in file, formatting, minification and JSONPath queries
- Autosave, draft recovery and external-change protection
- Automatic update detection; downloads and installs only after you click Update

## Installation

Windows: choose the x64 (amd64) or ARM64 setup installer.
macOS: use the universal DMG for Intel and Apple Silicon.
Linux: choose a Debian package or a tar.gz archive with install.sh. User-directory archive installations support in-app updates; system package installations should be updated through the package manager.

Releases include SHA256SUMS.txt. Update archives use Ed25519 signatures checked against the public key embedded in the app. Windows installers are currently unsigned; macOS apps use ad-hoc signing and are not notarized.

Users of v0.2.0 or earlier need to install v0.3.0 once manually to enable in-app updates.
