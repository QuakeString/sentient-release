# SENTIENT releases

Downloads of the SENTIENT IIoT platform for the **SENTIENT Platform Manager**
(SENTIENT Setup). No source code lives here.

<!-- downloads:start -->
## Downloads

| Product | Latest | What it is |
|---|---|---|
| SENTIENT | [SENTIENT 4.4.1.7](https://github.com/QuakeString/sentient-release/releases/tag/4.4.1.7) | The platform for Windows and Linux; installed and updated by the Platform Manager. Docker: `quakestring/sentient`. |
| SENTIENT Platform Manager | [SENTIENT Platform Manager 0.9.7](https://github.com/QuakeString/sentient-release/releases/tag/spm-v0.9.7) | Installs, updates, backs up and manages SENTIENT (Windows installer; Linux .deb, .rpm, Arch, AppImage and Flatpak packages, and a plain binary). The Flatpak is for managing SENTIENT on other computers (remote management); installing or managing SENTIENT on this same computer needs the .deb, .rpm, AppImage or Arch package. |
| SENTIENT Gateway | [Sentient Gateway 4.18.3](https://github.com/QuakeString/sentient-release/releases/tag/gateway-4.18.3) | Connects field devices and PLCs to SENTIENT (Windows installer, Linux packages). |
| SENTIENT mobile app | [SENTIENT-mobile-app 2.0.1 (build 17)](https://github.com/QuakeString/sentient-release/releases/tag/SENTIENT-mobile-app-2.0.1-17) | Android app for SENTIENT dashboards and alarms. |

Every release page lists its files with their SHA-256.
<!-- downloads:end -->

Each release is tagged with the SENTIENT version (for example `4.3.0.48`) and
carries:

| File | What |
|---|---|
| `manifest.json` | The version, and every file below with its size and SHA-256 |
| `sentient-payload.tar` | SENTIENT for Windows x64 (server, schema tool, UI, system data) |
| `postgresql-18.6-1-windows-x64-binaries.zip` | PostgreSQL for Windows, as SENTIENT Setup installs it |
| `timescaledb-postgresql-18-windows-amd64.zip` | TimescaleDB for that PostgreSQL |
| `vc_redist.x64.exe` | Microsoft Visual C++ runtime |
| `sentient-payload-linux-x86_64.tar` | SENTIENT for Linux x86_64 (native systemd installs) |

SENTIENT Setup and the Platform Manager read
`https://github.com/QuakeString/sentient-release/releases/latest/download/manifest.json`,
download what the computer needs and check every file against its SHA-256
before using it. Docker installs use the `quakestring/sentient` image instead.

Running SENTIENT needs a licence, managed inside SENTIENT.

Copyright © 2026 INVENIA SYSTEMS and the SENTIENT Authors. All rights reserved.
