# Backup FFmpeg static binaries for CI Tests

**This repository maintains temporary backups of selected FFmpeg static binaries (organized by date) sourced from various providers:** 

* https://johnvansickle.com/ffmpeg/ _(Licensed GNU General Public License version 3)_
* https://evermeet.cx/ffmpeg/  _(Licensed GNU General Public License version 3)_
* https://github.com/FFmpeg-Builds/FFmpeg-Builds _(Licensed GNU General Public License version 3)_

**These backups ensure continuous integration (CI) tests remain reliable even if upstream download mirrors experience downtime.**

## Checksums

| File | MD5 | SHA-256 |
|------|-----|---------|
| `linux/ffmpeg-git-amd64-static.tar.xz` | `0181ece1c6688111310d2d3b21912713` | `af2c62a95255b2f97f9092a5e86c6356119dba8d7c7e2ee0fe55672dbd71f68f` |
| `macOS/ffmpeg-latest-macos64-static.zip` | `b71f3cc3128e6bb7a8fc714ef8d62182` | `61eb80dc44a2c136d312aed2fa4dcff3fb062cc0699d999d21485a74ea746a17` |
| `windows/ffmpeg-latest-win64-static.7z` | `0646578c0272548b3340ff612a1d561e` | `4705843ccaaf54257c16ad90f3e952ece33c17df964ecf7bfdbb0f49c7171077` |

_All credits and ownership belongs to their rightful owners._