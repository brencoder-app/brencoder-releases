# BREncoder releases

Official downloads of **BREncoder**: capture, restore, mix, encode, stream, and author and burn BD video, 4K UHD
and DVD discs, in one app. Website: **https://brencoder.com**

> This repository holds release builds only. BREncoder's source code is not public.

## Download

Get the latest version from the **[Releases page](../../releases/latest)**:

| Platform | File |
|---|---|
| Windows 10/11 (64-bit) | `BREncoder-Windows-x64.zip` |
| Linux (x86_64, any distro) | `BREncoder-Linux-x86_64.zip` |
| Checksums | `SHA256SUMS.txt` |

## Requirements

BREncoder needs **FFmpeg**, which is free and open source, installed separately. Setup takes a few minutes; see
the [Installation Guide](https://brencoder.com/userguide/installation/).

## Install

**Windows:** unzip and run `BREncoder.exe`. No installer is needed. If Windows SmartScreen warns on first launch,
click **More info → Run anyway**.

**Linux:** unzip, then either run `BREncoder-x86_64.AppImage` directly, or run `./install_linux.sh` to add
BREncoder to your applications menu (`./install_linux.sh --uninstall` removes it).

## Verify your download

```
sha256sum -c SHA256SUMS.txt          # Linux / macOS
certutil -hashfile BREncoder-Windows-x64.zip SHA256   # Windows
```

## Licensing

The free trial is the full app, with a watermark and a 10-minute output limit. A license removes both.

- Licenses are time-based: a month, a year or five years.
- Your time starts when you **first activate** your key, which must be within 12 months of purchase.
- To activate: **About → Enter Key**.

Details: https://brencoder.com

## Help

help@brencoder.com

---
Copyright © Zebadiah J. Drinkwater. BREncoder is a trademark of Zebadiah J. Drinkwater.
Blu-ray Disc™ is a trademark of the Blu-ray Disc Association. BREncoder is not affiliated with or endorsed by the
Blu-ray Disc Association.
