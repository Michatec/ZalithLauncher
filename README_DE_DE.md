# Zalith Launcher 2
![Downloads](https://img.shields.io/github/downloads/ZalithLauncher/ZalithLauncher2/total)
[![Sponsor](https://img.shields.io/badge/sponsor-30363D?logo=GitHub-Sponsors)](https://afdian.com/a/MovTery)

[简体中文](README.md) | [繁體中文](README_ZH_TW.md) | [German](README_DE_DE.md)


> [!IMPORTANT]
> Dieses Projekt ist **vollständig unabhängig** von [ZalithLauncher](https://github.com/ZalithLauncher/ZalithLauncher).

**Zalith Launcher 2** ist ein neu entwickelter Launcher für **Android-Geräte**, der speziell für [Minecraft: Java Edition](https://www.minecraft.net/) konzipiert wurde. Als zentrale Start-Engine verwendet das Projekt [PojavLauncher](https://github.com/PojavLauncherTeam/PojavLauncher/tree/v3_openjdk/app_pojavlauncher/src/main/jni). Die moderne Benutzeroberfläche basiert auf **Jetpack Compose** und **Material Design 3**.
Wir arbeiten derzeit an unserer offiziellen Website [zalithlauncher.cn](https://zalithlauncher.cn).
Uns ist außerdem bekannt, dass eine Website eines Drittanbieters unter dem Namen „Zalith Launcher“ auftritt und den Eindruck erweckt, offiziell zu sein. Bitte beachte: **Diese Website wurde nicht von uns erstellt.** Sie nutzt den Namen des Projekts, um mit Werbung Geld zu verdienen. Wir sind an solchen Inhalten **nicht beteiligt**, unterstützen sie nicht und vertrauen ihnen nicht.
Bitte sei wachsam und **schütze deine persönlichen Daten und deine Privatsphäre!**

## 🌐 Sprach- und Übersetzungsunterstützung

Für die Übersetzung von Zalith Launcher 2 verwenden wir die Plattform Weblate. Du bist herzlich eingeladen, unserem [Weblate-Projekt](https://hosted.weblate.org/projects/zalithlauncher2) beizutreten und bei den Übersetzungen mitzuhelfen!
Vielen Dank an alle, die durch ihre Übersetzungsbeiträge dazu beitragen, Zalith Launcher 2 mehrsprachig und weltweit zugänglich zu machen!

## 📦 Build-Anleitung (für Entwickler)

> Dieser Abschnitt richtet sich an Entwickler, die zum Projekt beitragen oder das Projekt lokal kompilieren möchten.

### Voraussetzungen

- Android Studio **Bumblebee** oder neuer
- Android SDK:
  - **Minimale API-Version:** 26
  - **Ziel-API-Version:** 35
- JDK 11

### Build-Schritte

```bash
git clone git@github.com:ZalithLauncher/ZalithLauncher2.git
# Öffne das Projekt in Android Studio und starte den Build.
```

## 📜 Lizenz

Dieses Projekt ist unter der **[GPL-3.0-Lizenz](LICENSE)** lizenziert.

### Zusätzliche Bedingungen (gemäß Abschnitt 7 der GPLv3-Lizenz)

1. Wenn du eine modifizierte Version dieses Programms weiterverbreitest, musst du den Namen oder die Versionsnummer des Programms in angemessener Weise ändern, damit sie sich vom Original unterscheiden lässt. (Gemäß [GPLv3, Abschnitt 7(c)](https://github.com/ZalithLauncher/ZalithLauncher2/blob/969827b/LICENSE#L372-L374))
   - Modifizierte Versionen **dürfen weder den ursprünglichen Programmnamen „ZalithLauncher“ noch dessen Abkürzung „ZL“ im Namen enthalten. Auch Namen, die dem offiziellen Namen so ähnlich sind, dass Verwechslungsgefahr entstehen könnte, sind nicht zulässig.**
   - Alle modifizierten Versionen **müssen auf dem Startbildschirm oder in der Hauptoberfläche deutlich als „Unofficial Modified Version“ (inoffizielle modifizierte Version) gekennzeichnet sein.**
   - Der Anwendungsname kann in der Datei [gradle.properties](./ZalithLauncher/gradle.properties) geändert werden.

2. Die im Programm angezeigten Urheberrechtshinweise dürfen nicht entfernt werden. (Gemäß [GPLv3, Abschnitt 7(b)](https://github.com/ZalithLauncher/ZalithLauncher2/blob/969827b/LICENSE#L368-L370))

## Verwendete Open-Source-Bibliotheken und Lizenzen

Diese Software verwendet die folgenden Open-Source-Bibliotheken:

| Library                               | Copyright                                                                                                     | License              | Official Link                                                                      |
|---------------------------------------|---------------------------------------------------------------------------------------------------------------|----------------------|------------------------------------------------------------------------------------|
| androidx-appcompat                    | Copyright © The Android Open Source Project                                                                   | Apache 2.0           | [Link↗](https://developer.android.com/jetpack/androidx/releases/appcompat)         |
| androidx-constraintlayout-compose     | Copyright © The Android Open Source Project                                                                   | Apache 2.0           | [Link↗](https://developer.android.com/develop/ui/compose/layouts/constraintlayout) |
| androidx-webkit                       | Copyright © The Android Open Source Project                                                                   | Apache 2.0           | [Link↗](https://developer.android.com/jetpack/androidx/releases/webkit)            |
| ANGLE                                 | Copyright 2018 The ANGLE Project Authors                                                                      | BSD 3-Clause License | [Link↗](http://angleproject.org/)                                                  |
| Apache Commons Codec                  | -                                                                                                             | Apache 2.0           | [Link↗](https://commons.apache.org/proper/commons-codec)                           |
| Apache Commons Compress               | -                                                                                                             | Apache 2.0           | [Link↗](https://commons.apache.org/proper/commons-compress)                        |
| Apache Commons IO                     | -                                                                                                             | Apache 2.0           | [Link↗](https://commons.apache.org/proper/commons-io)                              |
| ByteHook                              | Copyright © 2020-2024 ByteDance, Inc.                                                                         | MIT License          | [Link↗](https://github.com/bytedance/bhook)                                        |
| BuildKeys                             | Copyright © 2026 MovTery                                                                                      | Aoache 2.0           | [Link↗](https://github.com/MovTery/BuildKeys)                                      |
| Coil Compose                          | Copyright © 2025 Coil Contributors                                                                            | Apache 2.0           | [Link↗](https://github.com/coil-kt/coil)                                           |
| Coil Gifs                             | Copyright © 2025 Coil Contributors                                                                            | Apache 2.0           | [Link↗](https://github.com/coil-kt/coil)                                           |
| Coil SVG                              | Copyright © 2025 Coil Contributors                                                                            | Apache 2.0           | [Link↗](https://github.com/coil-kt/coil)                                           |
| Fishnet                               | Copyright © 2025 Kyant                                                                                        | Apache 2.0           | [Link↗](https://github.com/Kyant0/Fishnet)                                         |
| gl4es_extra_extra                     | Copyright © 2016-2018 Sebastien Chevalier; Copyright (c) 2013-2016 Ryan Hileman                               | MIT License          | [Link↗](https://github.com/PojavLauncherTeam/gl4es_extra_extra)                    |
| Gson                                  | Copyright © 2008 Google Inc.                                                                                  | Apache 2.0           | [Link↗](https://github.com/google/gson)                                            |
| kotlinx.coroutines                    | Copyright © 2000-2020 JetBrains s.r.o.                                                                        | Apache 2.0           | [Link↗](https://github.com/Kotlin/kotlinx.coroutines)                              |
| ktor-client-content-negotiation       | Copyright © 2000-2023 JetBrains s.r.o.                                                                        | Apache 2.0           | [Link↗](https://ktor.io)                                                           |
| ktor-client-core                      | Copyright © 2000-2023 JetBrains s.r.o.                                                                        | Apache 2.0           | [Link↗](https://ktor.io)                                                           |
| ktor-client-okhttp                    | Copyright © 2000-2023 JetBrains s.r.o.                                                                        | Apache 2.0           | [Link↗](https://ktor.io)                                                           |
| ktor-http                             | Copyright © 2000-2023 JetBrains s.r.o.                                                                        | Apache 2.0           | [Link↗](https://ktor.io)                                                           |
| ktor-serialization-kotlinx-json       | Copyright © 2000-2023 JetBrains s.r.o.                                                                        | Apache 2.0           | [Link↗](https://ktor.io)                                                           |
| LWJGL - Lightweight Java Game Library | Copyright © 2012-present Lightweight Java Game Library All rights reserved.                                   | BSD 3-Clause License | [Link↗](https://github.com/LWJGL/lwjgl3)                                           |
| material-color-utilities              | Copyright 2021 Google LLC                                                                                     | Apache 2.0           | [Link↗](https://github.com/material-foundation/material-color-utilities)           |
| Maven Artifact                        | Copyright © The Apache Software Foundation                                                                    | Apache 2.0           | [Link↗](https://github.com/apache/maven/tree/maven-3.9.9/maven-artifact)           |
| Media3                                | Copyright © The Android Open Source Project                                                                   | Apache 2.0           | [Link↗](https://developer.android.com/jetpack/androidx/releases/media3)            |
| Mesa                                  | Copyright © The Mesa Authors                                                                                  | MIT License          | [Link↗](https://mesa3d.org/)                                                       |
| MobileGlues                           | Copyright © 2025-2026 MobileGL-Dev                                                                           | LGPL-2.1 License     | [Link↗](https://github.com/MobileGL-Dev/MobileGlues)                             |
| MMKV                                  | Copyright © 2018 THL A29 Limited, a Tencent company.                                                          | BSD 3-Clause License | [Link↗](https://github.com/Tencent/MMKV)                                           |
| Navigation 3                          | Copyright © The Android Open Source Project                                                                   | Apache 2.0           | [Link↗](https://developer.android.com/jetpack/androidx/releases/navigation3)       |
| NG-GL4ES                              | Copyright © 2016-2018 Sebastien Chevalier; Copyright © 2013-2016 Ryan Hileman; Copyright (c) 2025-2026 BZLZHH | MIT License          | [Link↗](https://github.com/BZLZHH/NG-GL4ES)                                        |
| OkHttp                                | Copyright © 2019 Square, Inc.                                                                                 | Apache 2.0           | [Link↗](https://github.com/square/okhttp)                                          |
| Okio                                  | Copyright © 2013 Square, Inc.                                                                                 | Apache 2.0           | [Link↗](https://square.github.io/okio/)                                            |
| OpenNBT                               | Copyright © 2013-2021 Steveice10.                                                                             | MIT License          | [Link↗](https://github.com/GeyserMC/OpenNBT)                                       |
| Process Phoenix                       | Copyright © 2015 Jake Wharton                                                                                 | Apache 2.0           | [Link↗](https://github.com/JakeWharton/ProcessPhoenix)                             |
| proxy-client-android                  | -                                                                                                             | LGPL-3.0 License     | [Link↗](https://github.com/TouchController/TouchController)                        |
| Reorderable                           | Copyright © 2023 Calvin Liang                                                                                 | Apache 2.0           | [Link↗](https://github.com/Calvin-LL/Reorderable)                                  |
| sdl2-compat                           | Copyright (C) 2026 Sam Lantinga <slouken@libsdl.org>                                                          | Zlib License         | [Link↗](https://github.com/libsdl-org/sdl2-compat)                                 |
| SDL3                                  | Copyright (C) 1997-2026 Sam Lantinga <slouken@libsdl.org>                                                     | Zlib License         | [Link↗](https://github.com/libsdl-org/SDL)                                         |
| SimpleFPEWrapper                      | Copyright © 2026 MobileGL-Dev                                                                                | LGPL-3.0 License     | [Link↗](https://github.com/MobileGL-Dev/SimpleFPEWrapper)                        |
| sora-editor                           | Copyright (C) 2020-2026  Rosemoe                                                                              | LGPL-2.1 License     | [Link↗](https://github.com/Rosemoe/sora-editor)                                    |
| StringFog                             | Copyright © 2016-2023, Megatron King                                                                          | Apache 2.0           | [Link↗](https://github.com/MegatronKing/StringFog)                                 |
| tm4e (TextMate for Eclipse)           | Copyright © Eclipse Foundation                                                                                | EPL-2.0 License      | [Link↗](https://github.com/eclipse-tm4e/tm4e)                                      |
| XZ for Java                           | Copyright © The XZ for Java authors and contributors                                                          | 0BSD License         | [Link↗](https://tukaani.org/xz/java.html)                                          |
