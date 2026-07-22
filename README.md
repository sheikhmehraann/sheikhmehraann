# Sheikh Mehraan

**Android System & Security Engineer | ARM64 & Bootchain Security Researcher**  
*Specializing in Low-Level MediaTek Exploitation, Linux Kernel Subsystems, and Custom Android Architecture.*

---

## 🔬 About & Focus Areas

I am an Android low-level developer and security researcher focused on bootchain security, low-level platform exploitation, and kernel subsystem architecture.

- **ARM64 & Bootchain Security**: Vulnerability research and patch engineering for MediaTek bootloader components (`Preloader`, `bl2_ext`, `LK`).
- **Android Verified Boot (AVB)**: Hardware-level security state emulation (`ro.boot.verifiedbootstate`, `ro.boot.flash.locked`).
- **Kernel Subsystems**: Linux Kernel 5.10+ VFS mount namespace isolation, syscall-level path filtering, and KernelSU integration.
- **Platform Porting**: Android 15 (XOS 15) vendor/system image rebuilding and dynamic partition architecture.

---

## 🛠️ Technical Competencies

| Category | Primary Technologies & Tooling |
| :--- | :--- |
| **Systems & Languages** | C, C++20, ARM64 Assembly, Python 3, Bash, PowerShell |
| **Bootloader & Firmware Security** | MediaTek LK, Preloader (EL3), AVB 2.0, `seccfg`, GFH Containers |
| **Reverse Engineering** | Ghidra, IDA Pro, Binary Disassembly, Memory Inspection |
| **Kernel & OS Internals** | Linux Kernel 5.10+, VFS, Mount Namespaces, KernelSU, Android 15 |
| **DevOps & Tooling** | Git, Cross-Platform Automation, ADB / Fastboot Internals |

---

## 📁 Key Repositories

### 🐺 [Fenrir — MediaTek Bootchain Exploit Framework](https://github.com/sheikhmehraann/fenrir)
*PoC exploit and hardware patch framework targeting MediaTek EL3 bootchain vulnerabilities on Infinix GT 20 Pro (`X6871`).*
- Hardware-level `ro.boot.verifiedbootstate = green` enforcement for Play Integrity.
- Hardware lock state spoofing (`LKS_LOCK`) for TEE and DRM compatibility.
- Unrestricted Fastboot command dispatcher and key combination boot routing.
- Native 1-click build (`build.py`) and automated flasher (`flash.py`) tooling.

### ⚡ [Disable-Vbmeta-Flashable](https://github.com/sheikhmehraann/Disable-Vbmeta-Flashable)
*Recovery-flashable utility script to patch AVB VBMeta verification flags across MediaTek and Android platforms.*

### 🛠️ [ROM-Toolkit](https://github.com/sheikhmehraann/ROM-Toolkit)
*Low-level Android ROM porting, image unpacking, dynamic partition rebuilding, and vendor modification scripts.*

---

## 📊 Activity & Statistics

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=sheikhmehraann&show_icons=true&theme=dark&hide_border=true" alt="GitHub Stats" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sheikhmehraann&layout=compact&theme=dark&hide_border=true&hide=html,css" alt="Top Languages" width="48%" />
</div>

---

## 📬 Contact & Links

- **GitHub**: [@sheikhmehraann](https://github.com/sheikhmehraann)
- **Telegram**: [@mehraann19](https://t.me/mehraann19)
