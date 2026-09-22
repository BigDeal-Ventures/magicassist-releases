# MagicAssist Releases

This public repository contains **release artifacts only** for MagicAssist clients and runtimes. It does not contain the private application source code, infrastructure configuration, credentials, or customer data.

## CLI and runtime installer

Install the current CLI/runtime bootstrap on macOS or Linux:

```bash
curl -fsSL https://github.com/BigDeal-Ventures/magicassist-releases/releases/latest/download/magicassist-install.sh | bash
```

After installation, the command is available as `magicassist`. The installer uses `/usr/local/bin` when writable and otherwise installs to `~/.local/bin` and updates the shell PATH where possible.

## Desktop app

Desktop releases publish signed platform installers and the updater metadata required by the installed Mac app. A Mac build must first be bridged to this public feed; later releases can then be installed from the app's own update flow.

## Mobile apps

Android release artifacts are published here as APK files with checksums. iOS builds are distributed through the project's TestFlight groups rather than as public source or signing material.

## Distribution policy

Only allowlisted binaries, checksums, installer scripts, and updater metadata belong here. The private MagicAssist source repository remains private and is never mirrored into this repository.
