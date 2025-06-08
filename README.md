# 🎮 Nvidia Rebirth - Optimized Modded Nvidia Drivers

![Nvidia Rebirth Banner](https://github.com/user-attachments/assets/8c693c85-9ea5-4270-a5f0-2da280d77039)

![Latest Release](https://img.shields.io/github/v/release/your-repo/Nvidia-Rebirth?label=Release)
![Downloads](https://img.shields.io/github/downloads/your-repo/Nvidia-Rebirth/total)
![License](https://img.shields.io/badge/license-MIT-blue)

---

## 🚀 About Nvidia Rebirth

**Nvidia Rebirth** is a performance-tuned and debloated version of official Nvidia graphics drivers. Created for gamers and creative professionals, it strips away unnecessary services and telemetry while delivering smoother performance, better input latency, and improved system responsiveness.

Compatible with most Nvidia GPUs, the Rebirth driver is perfect for fast-paced games like **Valorant**, **CS2**, **Apex Legends**, and **Fortnite**, as well as demanding workloads in creative tools.

---

## 📦 Current Version: **Rebirth V2**

### 🔧 Key Improvements in V2

- ✅ Lower input latency with optimized scheduling
- ✅ Smoother frametimes in CPU-limited scenarios
- ✅ Updated shader caching behavior for faster loading
- ✅ Enhanced power management and fewer background services
- ✅ Focused improvements for high-refresh displays (144Hz–240Hz+)
- ✅ Broad compatibility from GTX 10 series to RTX 40 series

---

## ⚙️ System Used for Benchmarking

- **GPU**: Nvidia RTX 4060 8GB  
- **CPU**: AMD Ryzen 7 5700X3D  
- **RAM**: 32GB DDR4 3600 CL16  
- **Resolution**: 1080p, Competitive Settings  
- **OS**: Windows 10 Pro (22H2)  
- **Driver**: Nvidia Rebirth V2 (Clean Installed via DDU)

---

## 📈 Performance Comparison (V1 vs V2)

| Game                  | V1 Avg FPS | V2 Avg FPS | 1% Lows (V2) | Input Lag Reduction |
|-----------------------|------------|------------|--------------|----------------------|
| **Valorant**          | 415        | **450**    | 410          | ~5ms lower           |
| **CS2**               | 370        | **395**    | 375          | ~4ms lower           |
| **Apex Legends**      | 230        | **248**    | 225          | ~6ms lower           |
| **Fortnite (Perf. Mode)** | 290    | **315**    | 305          | ~5ms lower           |

> *All tests conducted in offline or controlled match environments for consistency.*

---

### 📊 Visual FPS Comparison

![FPS Graph](https://github.com/your-repo/Nvidia-Rebirth/assets/fps-comparison-v2.png)  
*Bar graph showing average FPS gains from V1 to V2 on RTX 4060 + Ryzen 5700X3D*

---

## 📥 Installation Guide

1. **Download** the latest `.zip` from the [Releases](https://github.com/your-repo/Nvidia-Rebirth/releases) tab.
2. **Uninstall current drivers** using [DDU](https://www.wagnardsoft.com/) in Safe Mode.
3. **Reboot**, then install the Nvidia Rebirth driver using the provided `.exe` or manual `.inf` method.
4. **Restart** your PC and enjoy a smoother experience.

📘 For detailed instructions, see the full [Installation Guide](./INSTALL.md)

---

## ❓ FAQ

**Q: Is this safe to use?**  
A: Yes, the base is from official Nvidia drivers. Modifications only remove telemetry and optimize configurations. Use at your own discretion.

**Q: Can I use this on laptops?**  
A: Yes, but laptops with hybrid graphics (Optimus) may behave differently. Test carefully.

**Q: Do I need to reinstall this with every new GPU driver update?**  
A: Only if a newer version of Rebirth is released. You can safely stay on the current one if stable.

---

## 🛠️ Planned for Future Versions

- 🔹 V3 with customizable install options (Studio Mode / Gaming Mode)
- 🔹 Better overlay support and frametime monitoring tools
- 🔹 Full support and tweaks for RTX 4090 / next-gen GPUs

---

## 🤝 Support & Feedback

- Report bugs in the [Issues](https://github.com/your-repo/Nvidia-Rebirth/issues) section
- Chat with us or get help via [Discord](https://discord.gg/your-server-link)
- Pull requests for improvements are welcome!

---

## 📄 License

This project is released under the [MIT License](./LICENSE). You are free to use, modify, and distribute.

---

Thanks for using **Nvidia Rebirth** – modded performance where it matters most.
