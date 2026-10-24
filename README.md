# SENTIENT releases

Downloads of the SENTIENT IIoT platform for the **SENTIENT Platform Manager**
(SENTIENT Setup). No source code lives here.

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
`https://github.com/QuakeString/sentient-releases/releases/latest/download/manifest.json`,
download what the computer needs and check every file against its SHA-256
before using it. Docker installs use the `quakestring/sentient` image instead.

Running SENTIENT needs a licence, managed inside SENTIENT.

Copyright © 2026 INVENIA SYSTEMS and the SENTIENT Authors. All rights reserved.
