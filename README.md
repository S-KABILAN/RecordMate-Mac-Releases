# RecordMate Mac

Screen recording and video editing for **macOS 14 Sonoma or later** on **Apple silicon**.

[Download the latest release](https://github.com/S-KABILAN/RecordMate-Mac-Releases/releases/latest) · [RecordMate website](https://www.recordmate.app)

This repository contains the macOS installers, release notes, and update metadata.

## Install

1. Download the **arm64 DMG** from the latest release.
2. Open it and drag **RecordMate Mac** into **Applications**.
3. Open RecordMate Mac. The initial release is ad-hoc signed and not Apple notarized. If macOS blocks it, open **System Settings → Privacy & Security → Open Anyway**, then confirm **Open**.
4. Grant **Screen & System Audio Recording**, **Microphone** for narration, **Camera** for webcam footage, and **Accessibility** for cursor tracking. Restart the app after changing permissions if requested.

See [Apple's instructions for opening an app from an unidentified developer](https://support.apple.com/guide/mac-help/open-a-mac-app-from-an-unknown-developer-mh40616/mac).

## Features

- Screen and window recording with microphone and system sound.
- Cursor tracking and automatic zoom.
- Timeline editing, backgrounds, webcam overlays, and video export.
- Android recording over USB with USB Debugging enabled.
- Cloud captions powered by Groq. Generating captions uploads extracted recording audio to Groq.
- Recording history, editable projects, and automatic editor recovery.

## Updates

Use the app's update check, or download the latest DMG here. Open the installer and replace the app in Applications.

Testing versions through 1.0.44 used a different release repository. Install the first public **1.0.0** release manually to switch to this repository.

## Release assets

Most users should download the **DMG**. Each release also includes a ZIP, update blockmaps, `latest-mac.yml`, and `SHA256SUMS` for verification. The first release is for Apple silicon; no Intel installer is available yet.

For feedback, [open an issue](https://github.com/S-KABILAN/RecordMate-Mac-Releases/issues) and include your macOS version, Mac model, app version, and the steps to reproduce the problem.
