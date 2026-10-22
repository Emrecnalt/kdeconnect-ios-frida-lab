# KDE Connect Lab cloud build
Manually triggered unsigned Debug builds from KDE's pinned upstream source.
Source: https://github.com/KDE/kdeconnect-ios (GPL licensed; see upstream LICENSES).
No Apple credentials, certificates, provisioning profiles or device identifiers are used in CI.
The bundle ID differs from the App Store app. This is an unofficial research build.
Sign locally with your own Apple account before installing. Debug entitlements must be verified after signing; unsigned builds alone do not enable Frida access.
