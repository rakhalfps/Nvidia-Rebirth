# 📥 Nvidia Rebirth Installation Guide

This guide will walk you through installing the **Nvidia Rebirth modded driver** safely and cleanly using **DDU** (Display Driver Uninstaller).

---

## 🔧 Requirements

- ✅ Windows 10 / 11 (64-bit only)
- ✅ Nvidia GPU (GTX 10 series or newer recommended)
- ✅ [DDU – Display Driver Uninstaller](https://www.wagnardsoft.com/)
- ✅ Latest **Nvidia Rebirth** driver `.zip` file from [Releases](https://github.com/your-username/Nvidia-Rebirth/releases)

---

## 🧼 Step 1: Uninstall Old Drivers with DDU

> 💡 **This step is crucial** to ensure no conflicts or leftover files.

1. Download **DDU** from the [official site](https://www.wagnardsoft.com/).
2. Extract and run `DDU.exe`.
3. Boot into **Safe Mode** (DDU will prompt you to do this).
4. Select **GPU > Nvidia** from the dropdown menu.
5. Click:  
   **"Clean and restart"**

---

## 📦 Step 2: Install Nvidia Rebirth Driver

1. Extract the `.zip` file downloaded from the **Releases** tab.
2. Run the installer (`setup.exe`) or open `setup.bat` (if provided).
3. Follow the custom Nvidia installer flow.
4. **Check** the box for:  
   ✅ *“Perform a clean installation”*
5. Complete the installation and reboot your PC.

---

## 📈 Step 3: Optimize (Optional)

- Disable **Hardware-accelerated GPU scheduling** (may vary by game).
- Use [Nvidia Profile Inspector](https://github.com/Orbmu2k/nvidiaProfileInspector) for advanced tweaks.
- Enable G-Sync or V-Sync based on your monitor type.

---

## 📦 Optional Tools

| Tool | Purpose |
|------|---------|
| [NV CleanInstall](https://www.techpowerup.com/download/techpowerup-nvcleanstall/) | Advanced custom driver installer |
| [MSI Mode Utility](https://forums.guru3d.com/threads/windows-line-based-vs-message-signaled-based-interrupts-msi-tool.378044/) | Reduce latency via IRQ changes |
| [LatencyMon](https://resplendence.com/latencymon) | Monitor system latency issues |

---

## ❗ Troubleshooting

| Issue | Solution |
|-------|----------|
| Install fails mid-way | Use DDU again, reboot, try clean install |
| Games crash after update | Delete shader cache from `%LocalAppData%\NVIDIA` |
| Driver doesn't show | Ensure you're not on a laptop with restricted BIOS |

---

## 💬 Need Help?

- Open an [Issue on GitHub](https://github.com/your-username/Nvidia-Rebirth/issues)
- Join our [Discord](https://discord.gg/your-discord) for fast support

---

Enjoy your cleaner, faster Nvidia experience with **Rebirth V2**!
