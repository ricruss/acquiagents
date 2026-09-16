# Acqui Agents

Downloads and update feed for **Acqui Agents**, a native macOS app that puts Claude Code, Codex, Google's Antigravity CLI and Apple's on-device model behind one chat window, with approval cards for every tool call and a pull request review loop.

This repository holds only the released builds and the Sparkle appcast. The application is not open source; the source lives in a private repository.

## Install

Download the latest `AcquiAgents-<version>.dmg` from [Releases](https://github.com/ricruss/acquiagents/releases), open it and drag the app to Applications. Ignore the "Source code (zip / tar.gz)" links GitHub adds to every release: they are snapshots of this repository, which is only this README and the update feed, not the application's source. The app is signed with a Developer ID certificate and notarized by Apple. It checks this feed for updates once a day and never installs one without asking.

## Requirements

- macOS 26 or later with Apple Intelligence enabled.
- The `claude`, `codex` and `agy` command line tools installed and logged in.

## Terms

The binaries are provided as is, for personal use, all rights reserved. No warranty.
