# Backup FFmpeg static binaries for CI Tests

**This repository maintains temporary backups of selected FFmpeg static binaries (organized by date) sourced from various providers:** 

* https://johnvansickle.com/ffmpeg/ (_Licensed GNU General Public License version 3_)
* https://web.archive.org/web/20200919011114mp_/https://ffmpeg.zeranoe.com (_Licensed GNU General Public License version 3_)

**These backups ensure continuous integration (CI) tests remain reliable even if upstream download mirrors experience downtime.**

## Checksums

| File | MD5 | SHA-256 |
|------|-----|---------|
| `linux/ffmpeg-git-amd64-static.tar.xz` | `fa47f455ec3df1288c046fb6ccff6e13` | `2ae4c4fdd3b0f2102efba4df07a4cdc19ffed8efa7c5cf4a12e3b9509b1ef0e7` |
| `macOS/ffmpeg-latest-macos64-static.zip` | `62853b8490125196b9c035067adba587` | `83be7ad421a32cccb72c4af35eaa4c6aae266dc62e0de97e277bfccfaee3c5ab` |
| `windows/ffmpeg-latest-win32-static.zip` | `beb2fec1ea0245bf0a8ee33101ac4573` | `bcf172b0a1e985134789f822bcc2792b7d8eebcc068b55d60e913ded3ff3ed66` |
| `windows/ffmpeg-latest-win64-static.zip` | `8a32a45ddae1b5867d0e3f0694a4e129` | `e749576935776c0064b0268856efa60a9f38f0b5d6f11e5769ebc7447e4b9d3b` |

_All credits and ownership belongs to their rightful owners._