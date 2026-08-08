# Oneplus_Resuki-snap865
These kernes are for all oneplus devices which have snapdragon 865 processors and OxygenOs 13.1 with kernel version 


⚡ ACALLED X Kernel

Custom Kernel for the OnePlus 8 Series & 9R

instantnoodle · instantnoodlep · kebab · lemonades

Kernel Branch Root SUSFS ROM Support License

📱 Supported Devices

Device	Codename
OnePlus 8	instantnoodle
OnePlus 8 Pro	instantnoodlep
OnePlus 8T	kebab
OnePlus 9R	lemonades
🛣️ ROM Compatibility

ROM Type	Status
Stock (OxygenOS / ColorOS-based)	✅ Supported
Custom ROMs (Android 16 / A16)	🚧 Coming soon
✨ Features

🧠 Three root method builds — choose KernelSU-Next, ReSukiSU, or SukiSU-Ultra (see below)
🥷 SUSFS v2.2.0 — kernel-level root/module hiding for stronger detection resistance
📦 Systemless AnyKernel3 installer — OTA-friendly, compatible with autoflash apps
🐧 Linux 4.19.325-cip132 base
🔑 Root Solutions

ACALLED X is built in three separate root-method variants — flash whichever zip matches the root solution you want, they aren't combined into one build.



📥 Installation

Make sure your bootloader is unlocked and you're on a stock-based ROM/firmware (custom ROM support is coming soon).
Download the flashable zip matching your preferred root method (KSU-Next, ReSukiSU, or SukiSU-Ultra) from the XDA thread or the repo's Releases page.
Flash the zip via TWRP, OrangeFox, or the AnyKernel Flasher app — over your current stock boot setup.
Reboot. First boot after flashing may take a little longer than usual.


💖 Support Development

Custom ROM (A16) support is in the works — if you'd like to help speed that up, donations go straight toward development time and testing devices.

USDT BEP20 (0x7312c6f5c07480f90F4Ef47097a572920e7e5Fcf)
Every bit helps push custom ROM compatibility forward faster. 🙏

📖 About

ACALLED X is a kernel for the OnePlus 8, 8 Pro, 8T, and 9R, built in three root-method variants — KernelSU-Next, ReSukiSU, and SukiSU-Ultra — each with SUSFS v2.2.0, a modern LLVM toolchain, and a systemless AnyKernel3 installer. It's built for daily-driver stability first, with performance and root access layered on top without breaking OTA compatibility.

⚠️ Disclaimer: Flashing a custom kernel carries risk of instability, bootloops, or other issues. You flash entirely at your own risk — the maintainer is not responsible for any damage to your device.
🙏 Credits



Credit	For

KernelSU	Original root solution
KernelSU-Next	Continued KSU development
SukiSU-Ultra	Root/KPM lineage
ReSukiSU	Root implementation used
SUSFS	Root-hiding subsystem
AnyKernel3	Flashable zip framework
Claude AI (Anthropic)	Docs & build analysis
Everyone testing and reporting issues on XDA	Community support
📜 License

This kernel is released under the GPL-2.0 License, in keeping with the license of the Linux kernel it's derived from.
