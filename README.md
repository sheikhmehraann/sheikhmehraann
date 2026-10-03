# Sheikh Mehraan

Systems, firmware, and low-level Android developer. Most of my work centers around MediaTek bootchains (Dimensity 8200 / MT6895), custom recovery compilation, ARM64 kernel packaging, and dynamic partition engineering.

---

## Focus Areas

- **Android Bootchains & Hardware Security**: Research on MediaTek EL3 and BL2 bootloader stages, AVB 2.0 / VBMeta integrity patching, verified boot state handling (`ro.boot.verifiedbootstate`), and hardware lock state controls (`LKS_LOCK`).
- **Kernel & Recovery Development**: Compiling and porting custom recoveries (OrangeFox R12 in `vendor_boot`) and maintaining automated GKI 5.10.270 kernel builds bundled with KernelSU / APatch and AnyKernel3 packaging.
- **Firmware & Partition Engineering**: Building tools to deconstruct and repack Transsion (Infinix, Tecno, itel) stock firmware dumps, dynamic partition rebuilding (`lpmake` / `lptools`), and automated cloud extraction of full/differential OTA payloads (`payload.bin`).
- **Native & Embedded Tooling**: Low-level device flashing tools written in Rust and C to interface directly with MediaTek BootROM/VCOM without relying on third-party Windows driver workarounds, alongside network diagnostic tools (`wifi-audit-rs`).
- **Release Automation**: Multi-gigabit cloud pipelines on GitHub Actions for firmware unpacking, dynamic `super.img` deconstruction, and direct synchronization to SourceForge FRS.

---

## Selected Projects

| Project | Description | Stack |
| --- | --- | --- |
| [fenrir](https://github.com/sheikhmehraann/fenrir) / [Fenrir-X6871](https://github.com/sheikhmehraann/Fenrir-X6871) | MediaTek Dimensity EL3 bootchain research and hardware state spoofing for Infinix GT 20 Pro (`mt6895`). | C, ARM64, Python |
| [DOOM](https://github.com/sheikhmehraann/DOOM) | Rust-based MediaTek flashing and partition management engine with zero-driver Windows VCOM support. | Rust, USB/COM |
| [X6871-Recovery-Project](https://github.com/sheikhmehraann/X6871-Recovery-Project) | Custom OrangeFox R12.0 recovery build for the Infinix GT 20 Pro targeting `vendor_boot` on Android 15. | C++, Shell, Makefile |
| [Flashable-Maker](https://github.com/sheikhmehraann/Flashable-Maker) / [SpeedFlasher](https://github.com/sheikhmehraann/SpeedFlasher) | Cross-platform flashable ROM maker for Windows, Linux, and Termux with dynamic partition and AVB controls. | Shell, Python, Batch |
| [Transsion-Firmware-Toolkit](https://github.com/sheikhmehraann/Transsion-Firmware-Toolkit) | Stock firmware dump parser and recovery-flashable ZIP generator for Transsion OEM devices. | Python, `lpmake` |
| [gki-5.10-kernel-builder](https://github.com/sheikhmehraann/gki-5.10-kernel-builder) | Automated GKI 5.10 kernel builder pipeline with KernelSU and APatch integration. | Shell, Clang/LLVM |
| [MTK-ATS](https://github.com/sheikhmehraann/MTK-ATS) | MediaTek & Transsion anti-tamper system analysis and partition integrity engine. | Rust |
| [wifi-audit-rs](https://github.com/sheikhmehraann/wifi-audit-rs) | Windows terminal UI application for 802.11 network auditing and frame analysis. | Rust, Ratatui |
| [OTA-Extract](https://github.com/sheikhmehraann/OTA-Extract) / [fw](https://github.com/sheikhmehraann/fw) | Cloud-powered pipelines for automated partition decompression and extraction from raw OTA payloads. | Python, Shell, Zstandard |
| [WinMemoryCleaner](https://github.com/sheikhmehraann/WinMemoryCleaner) | Optimized NT Native API utility for trimming Windows working sets and system memory caches. | C#, Win32 Native API |

---

## Technical Background

- **Languages**: Rust, C, C++, ARM64 Assembly, Python, Bash / POSIX Shell, PowerShell, C#
- **Platforms & Targets**: MediaTek Dimensity (MT6895 / Dimensity 8200), Transsion (Infinix X6871, Tecno Camon), Android GKI (5.10 / 6.1), Windows NT internals
- **Systems & Tooling**: `lpmake`, `lptools`, `simg2img`, AnyKernel3, Clang/LLVM cross-compilers, Ghidra, IDA Pro, Git, GitHub Actions CI/CD

---

## Links

- SourceForge: [mehraann19](https://sourceforge.net/u/mehraann19/profile/)
- Telegram: [@mehraann19](https://t.me/mehraann19)
- GitHub: [sheikhmehraann](https://github.com/sheikhmehraann)
