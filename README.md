# Nvidia Rebirth: Clean, Optimized Nvidia Graphics Driver for Gaming

![Cover](https://raw.githubusercontent.com/rakhalfps/Nvidia-Rebirth/124142ccbc11b8949b91383703d8b243ea138518/Media/Cover.png)

[![Downloads](https://img.shields.io/github/downloads/rakhalfps/Nvidia-Rebirth/total?color=blue)]()&nbsp;&nbsp;&nbsp;[![License](https://img.shields.io/badge/license-MIT-blue)](./LICENSE)

---

Nvidia Rebirth is a lightweight, optimized Nvidia driver that removes telemetry and background services to reduce input lag and improve frame stability. Designed for competitive gaming and creators. Tested on RTX 4060 and Ryzen 7 5700X3D. Supports GTX 10 through RTX 40 series GPUs.

> **Note:** This driver does *not* support or provide benefits for RTX 50-series GPUs. Use official drivers for those.

---

### System Specs & Performance

| Component      | Specification           |        | Game          | Avg FPS | Input Lag Reduction |
|----------------|-------------------------|--------|---------------|---------|---------------------|
| GPU            | RTX 4060 8GB            |        | Valorant      | 450     | ~5ms lower          |
| CPU            | Ryzen 7 5700X3D         |        | CS2           | 395     | ~4ms lower          |
| RAM            | 32GB DDR4 3600 CL16     |        | Apex Legends  | 248     | ~6ms lower          |
| OS             | Windows 10 Pro 24H2     |        | Fortnite      | 315     | ~5ms lower          |

---

### Key Features

- Removed telemetry and unnecessary background services  
- Improved CPU-GPU scheduling for smoother frame times  
- Reduced system latency and input delay  
- Optimized for high refresh rates (144–360Hz)  
- Stable frame pacing under CPU load  

---

### How to Install

1. Download the latest release from [here](https://github.com/rakhalfps/Nvidia-Rebirth/releases).  
2. Use [DDU](https://www.wagnardsoft.com/) to fully uninstall existing Nvidia drivers.  
3. Restart your PC.  
4. Run the Rebirth installer and follow the instructions.  
5. (Optional) Select “Clean Install” during setup to reset Nvidia settings.

---

### FAQ

- **Will this increase FPS?**  
  Mainly improves frame stability and reduces input lag; FPS gains vary by system and game.

- **Is it compatible with laptops?**  
  Yes, but hybrid GPU (Optimus) setups may behave differently.

- **How does it differ from official drivers?**  
  Removes telemetry, GeForce Experience, and unused services to reduce bloat and improve responsiveness.

---

### Roadmap & Support

- Install profiles for Gaming and Studio modes  
- Support for RTX 4090 and newer GPUs (except 50-series)  
- Built-in latency monitoring tools (planned)  
- Multi-language and multi-OS support coming  

Report issues or request features on [GitHub Issues](https://github.com/rakhalfps/Nvidia-Rebirth/issues).  
Join the community on [Discord](https://discord.gg/krpUAHkf5m).  
Contributions and pull requests welcome!

---

© MIT License | Thank you for choosing **Nvidia Rebirth**
