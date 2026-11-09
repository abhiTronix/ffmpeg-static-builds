# Backup FFmpeg static binaries for CI Tests

**This repository maintains temporary backups of selected FFmpeg static binaries (organized by date) sourced from various providers:** 

* https://johnvansickle.com/ffmpeg/ _(Licensed GNU General Public License version 3)_
* https://evermeet.cx/ffmpeg/  _(Licensed GNU General Public License version 3)_
* https://github.com/FFmpeg-Builds/FFmpeg-Builds _(Licensed GNU General Public License version 3)_

**These backups ensure continuous integration (CI) tests remain reliable even if upstream download mirrors experience downtime.**

## Checksums

| File | MD5 | SHA-256 |
|------|-----|---------|
| `linux/ffmpeg-git-amd64-static.tar.xz` | `48e3552546a60d5ff6981c7556e7b34c` | `bdd1fa81b96e1e94c21dfbd3cf7047f7d6c4245710bdb46122009e723ca31145` |
| `macOS/ffmpeg-latest-macos64-static.zip` | `fdf1610edd42b883d1ae09860a398130` | `1ddcff0ae424f61d85471d66bdf3f89bfdcee318d29a98680d920450e4f99300` |
| `windows/ffmpeg-latest-win64-static.7z` | `cc7c4f4b721a03375aa0f0d93a3e8727` | `cc7015a21ada3efe802935cf009c1bc39d117933ad48ef9a5a5a8cdc2ed037ce` |

## Archive Structure

All FFmpeg binaries live under `ffmpeg/bin/` inside each archive.

**`linux/ffmpeg-git-amd64-static.tar.xz`**

```
ffmpeg/
├── bin/
│   ├── ffmpeg
│   ├── ffprobe
│   └── qt-faststart
├── manpages/
├── model/
├── GPLv3.txt
└── readme.txt
```

**`macOS/ffmpeg-latest-macos64-static.zip`**

```
ffmpeg/
└── bin/
    ├── ffmpeg
    ├── ffplay
    └── ffprobe
```

**`windows/ffmpeg-latest-win64-static.7z`**

```
ffmpeg/
├── bin/
│   ├── ffmpeg.exe
│   ├── ffplay.exe
│   └── ffprobe.exe
├── doc/
├── presets/
├── LICENSE
└── README.txt
```

_All credits and ownership belongs to their rightful owners._