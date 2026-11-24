# Sheikh Mehraan

I'm Sheikh Mehraan (also online as `sheikh mehraann`, `sheikhmehraan`, `Mehraann`, and `mehraann19`), a developer from Kashmir. I work on low-level Android internals, MediaTek bootloaders, kernel builds, and firmware tools, mostly around the Infinix GT 20 Pro (X6871 / MediaTek Dimensity 8200 Ultimate / MT6895).

## Public repos

### Bootloader, kernel, and OS bring-up
- [Fenrir-X6871](https://github.com/sheikhmehraann/Fenrir-X6871) - MediaTek LittleKernel (LK) payload injector and AVB/verified boot patcher for the Infinix GT 20 Pro (X6871) on Android 16.
- [Renkai-X6871](https://github.com/sheikhmehraann/Renkai-X6871) - Patched LittleKernel (`lk`) and bootloader images for X6871 on XOS 14 and XOS 15 (Android 14 and 15).
- [gki-5.10-kernel-builder](https://github.com/sheikhmehraann/gki-5.10-kernel-builder) - GitHub Actions workflow that builds Android GKI 5.10.270 with APatch root and packages an AnyKernel3 zip.
- [X6871-iOS-Port](https://github.com/sheikhmehraann/X6871-iOS-Port) - Experimental Darwin XNU / iOS 16 bring-up attempt for the Infinix GT 20 Pro (ARM64 boot shim, DeviceTree builder, and early driver stubs).

### Firmware, OTA, and flashing tools
- [SpeedFlasher](https://github.com/sheikhmehraann/SpeedFlasher) - Turns partition dumps (`.img` / `.img.zst`) into recovery-flashable zips and Fastboot flasher scripts for Windows, Linux, and Termux, with `vbmeta` flag controls.
- [Transsion-Firmware-Toolkit](https://github.com/sheikhmehraann/Transsion-Firmware-Toolkit) - CLI and GitHub Actions scripts for probing, extracting, repacking (`.tar.zst`), and flashing Transsion (Infinix, Tecno, itel) OTAs.
- [transsion-flashable-builder](https://github.com/sheikhmehraann/transsion-flashable-builder) - Builds A/B recovery-flashable zips from Transsion stock firmware dumps using `lptools` and zstd.
- [OTA-Extract](https://github.com/sheikhmehraann/OTA-Extract) - GitHub Actions extractor for pulling partition images out of full and incremental Android `payload.bin` OTAs.

### Android mods and utilities
- [OnePeek](https://github.com/sheikhmehraann/OnePeek) - Small libxposed (API 102 / LSPosed) module for Google One that queries Play Billing offers and free trials and shows the raw pricing phases.
- [IOS-Emoji-Font](https://github.com/sheikhmehraann/IOS-Emoji-Font) - Magisk, KernelSU, and APatch module replacing Android system fonts with Apple SF Pro and iOS emoji, with metric patch tools for Indian and RTL writing systems.
- [gofile-fast-link-transfer](https://github.com/sheikhmehraann/gofile-fast-link-transfer) - Transfers files from Google Drive, SourceForge, MediaFire, Dropbox, or direct URLs straight to GoFile using multi-connection downloads and `curl`.
- [WinMemoryCleaner](https://github.com/sheikhmehraann/WinMemoryCleaner) - Modified fork of Igor Mundstein's WinMemoryCleaner with extra Windows tweaks, minimize-to-tray behavior, and a compact settings layout.
- [Antigravity-Jailbreak](https://github.com/sheikhmehraann/Antigravity-Jailbreak) - System prompt profiles and a Python/Batch switcher for Google Antigravity `AGENTS.md` files.

## What I use

Python, C, ARM64 assembly, Kotlin, Shell, Batch, and C#. Most of the Android work uses LittleKernel, AVB/VBMeta, `lptools`, `payload.bin`, AnyKernel3, Magisk/KernelSU/APatch, LSPosed, and GitHub Actions.

## Where to find me

If you're looking for me online, these are my real accounts:

- GitHub: [github.com/sheikhmehraann](https://github.com/sheikhmehraann) (`@sheikhmehraann`)
- Telegram: [t.me/mehraann19](https://t.me/mehraann19) (`@mehraann19`)
- SourceForge: [sourceforge.net/u/mehraann19](https://sourceforge.net/u/mehraann19/profile/) (`mehraann19`)
- Email: mehraann.19@gmail.com
