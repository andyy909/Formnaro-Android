# Formano Mini for Android

Formano Mini is a tablet CAD app with an offline S Pen sketchbook and a companion mode for Formnaro on Windows. The Android app is new and under active development. Pilot 32 is an early test build, and features and workflows may change.

**[Pilot 32 APK and SHA-256 checksum](https://github.com/andyy909/Formnaro-Android/releases/tag/v0.1.0-pilot.32)** · [Formnaro for Windows](https://github.com/andyy909/Formnaro-cad)

**Deutsch:** Formano Mini für Android ist frisch und wird aktiv weiterentwickelt. Pilot 32 ist eine frühe Testversion.

## Verified compatibility

| Android release | Android device tested | Windows build tested |
| --- | --- | --- |
| Pilot 32 · 0.1.0-pilot.32 (build 36) | Samsung Galaxy Tab S7 Plus (SM-T970) | Private Formnaro PC Companion Pilot 32, commit `64cf5fd409231014090b2b57c3c556ccaf2f299f` |

The APK requires Android 10 or later and uses the pilot signing certificate. The public Windows repository provides the regular desktop downloads. PC pairing for this APK was verified with the private companion build in the table.

## Pair with the PC

1. Connect the tablet and PC to the same local network.
2. In the Windows companion build, open **Projekte → Tablet verbinden** and generate an invitation. Enable live controls if you want the tablet to control the PC view.
3. In Formano Mini, open **CAD-Projekt → Mit PC verbinden**. Scan the QR code or paste the manual pairing code, then confirm the connection on Windows.

The sketchbook is available directly from the tablet toolbar. After pairing, a sketchbook page can be sent to a saved Windows project and opened there under **Projekte → Tablet-Notizen**.

## Report an issue

Include the Android pilot number, device and Android version, the Windows build if involved, and the steps to reproduce the issue. Keep pairing codes and personal model files out of reports.

## Development

Android and Windows share the CAD kernel integration, sketch editor and project-file code in the Formnaro development repository.
