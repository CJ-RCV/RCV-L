# RCV Launcher

RCV Launcher is an **unofficial modified version** of [Zalith Launcher 2](https://github.com/ZalithLauncher/ZalithLauncher2), targeting Android phones.

## Phase 1 — RCV identity
- Independent Android application ID: `com.rcv.launcher`
- Custom launcher display name and version (`0.1.0-rcv`)
- New welcome card on the existing launcher home screen, with RCV website and Twitch links
- Arabic/English localization for the RCV elements
- Original copyright notices, credit sections, and library licenses retained
- Explicit Unofficial Modified Version designation on home screen

**Original software:** Zalith Launcher 2, Copyright (C) 2025 MovTery and contributors.
**License:** GPL-3.0-or-later; see [LICENSE](LICENSE).
The modified source is distributed under the same license.
The RCV project is not affiliated with or endorsed by the original launcher authors or Mojang/Microsoft.

## Build
Android Studio with JDK 21 and the matching Android SDK/NDK from the Gradle configuration.
Build debug using `./gradlew :ZalithLauncher:assembleDebug -Darch=arm64`.
The launcher must be compiled and tested before distributing APKs.
