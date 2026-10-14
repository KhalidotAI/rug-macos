# Rug for Mac

A Persian carpet for your desktop. Slide, curl, roll and unfurl it to cover or reveal your desktop folders.

## Download

**[Download Rug for macOS](https://github.com/KhalidotAI/rug-macos/releases/tag/v2.5.0-preview)**
On the release page, open **Assets** and download `Rug-2.5-universal.dmg`. You do not need Git or Xcode.

**Requirements:** macOS 12 or later. Supports Apple Silicon and Intel Macs.

**Preview build:** This version is locally signed and has not been notarized by Apple. macOS may block it on another Mac. A Developer ID signed and notarized release is still pending.

## Install and launch

1. Download the DMG from the release page above.
2. Open the DMG and drag **Rug.app** into **Applications**.
3. Eject the Rug disk image.
4. Open **Applications → Rug**.
5. The carpet opens with an animated entrance. On a MacBook it prefers the built-in display; otherwise it uses the main display.

Rug lives in the **menu bar**. It does not open a normal document window or add a Dock icon. Click the carpet icon in the menu bar for its controls.

## Use the carpet

| Action | How |
| --- | --- |
| Move | Drag the middle of the rug. |
| Fold / reveal folders | Drag a corner inward. |
| Bring the carpet back | Pull the folded corner toward its original flat position. |
| Roll up / unfurl | Double left click the visible rug; double click again to reverse. |
| Change size | Menu bar → Make Bigger, Make Smaller, or Set Size. |
| Rotate and resize | Hold Option while dragging, or use trackpad pinch/rotation. |
| Return to center | Menu bar → Reset Position. |
| Quit | Menu bar → Quit Rug. |

The rug visually covers desktop icons; it does not move, delete, encrypt, or secure your files. Reveal the icons to use them normally. Position and size are saved.

## Start automatically

The first launch from Applications requests **Launch at Login**. Switch it off in the Rug menu if preferred.

If it does not start after signing in, check **System Settings → General → Login Items**. Confirm Rug appears in **Open at Login** and approve it if macOS asks. On macOS 12, check Login Items under Users & Groups. Automatic launch happens after signing in, not before the login screen.

## Troubleshooting

- **Cannot find the carpet:** use its menu bar icon → Reset Position. If rolled up, double click the visible strip or use Unfurl / Roll Up Rug.
- **macOS blocks opening:** this preview is not Apple-notarized. Do not disable Gatekeeper globally. Wait for the signed release if unsure about the download.
- **Update:** quit Rug, download the newest DMG, replace Rug in Applications, eject the disk image, and reopen the installed copy.
- **Report a problem:** open an issue with your macOS version, Mac model, and steps to reproduce it. Check recordings for private information before attaching them.

## About this repository

This repository contains app downloads and user documentation. Rug’s implementation source is not published. GitHub’s automatic “Source code” archives contain this repository’s public documentation, not the app implementation.
