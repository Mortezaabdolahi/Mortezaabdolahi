# Hi there, I'm Morteza Abdolahi 👋

![Role](https://img.shields.io/badge/Role-EMBEDDED%20%26%20LINUX%20DEVELOPER-blue)
![Focus](https://img.shields.io/badge/Focus-FIRMWARE%20%7C%20DSP%20%7C%20GUI%20%7C%20LINUX-green)
![Location](https://img.shields.io/badge/Location-IRAN-red)

Passionate about building reliable embedded systems, real-time firmware, custom Linux BSPs, and desktop GUI tools. I bridge the gap between low-level hardware control, digital signal processing, and host-side telemetry interfaces.

---

## 🛠️ Core Technical Stack

- **Languages:** C, C++(Qt Widgets), C# (WinForms)
- **Microcontrollers & Firmware:** STM32 (HAL), Cortex-M4-M3, DMA, Timers, Interrupts, FreeRTOS
- **Embedded Linux & BSP:** Buildroot, Device Tree, POSIX C, System Programming, Raspberry Pi 4
- **Protocols & Buses:** SPI, I2C, CAN (MCP2515), UART, Ethernet (W5500)
- **DSP & Math:** 1024-pt Complex FFT (`arm_cfft_f32`), Digital IQ Mixing, Hann Windowing, dBm Calibration
- **GUI & Tools:** C#, WinForms, C++/Qt, GDB, Git, VS Code, Keil uVision

---

## 🚀 Featured Projects
### 1. Modular Embedded Architecture & Real-Time DSP Pipeline

A scalable, RTOS-ready firmware framework designed for high-speed data acquisition, multi-protocol communication, and real-time DSP. Built around a reusable core architecture, this framework has been successfully deployed across 3 distinct embedded applications:

- **Modular Core Framework:** Designed with clean abstraction layers (HAL/LL), hardware-triggered DMA buffers, and RTOS-ready task architecture for seamless portability across STM32 platforms.
- **High-Speed DSP Pipeline:** Real-time acquisition (Timer+DMA), block DC removal, digital IQ mixing ($f_{\text{LO}} = 1\text{ kHz}$), Hann windowing, and 1024-point CFFT with calibrated power spectrum output ($\pm 5\text{ kHz}$ baseband at $10\text{ kSa/s}$).
- **Multi-Transport & Networking:** Stacked TCP/IP communication layer (via W5500) and reliable UART/SPI streaming protocols for live telemetry to PC/Embedded Linux host viewers.
- **Host GUI (C# WinForms):** Multi-threaded architecture (Telemetry polling, real-time dual-side $\pm 5\text{ kHz}$ spectral rendering, and queued Excel/CSV logging via `ConcurrentQueue`).
### 2. Custom Embedded Linux BSP & Systems Interfacing (RPi 4)
- **Custom OS Development:** Engineered lightweight, optimized root file systems (~150MB) using **Buildroot** for Raspberry Pi 4, tailored for high-performance industrial applications.
- **Advanced Peripheral Integration:** Implemented robust userspace POSIX C drivers for:
  - **I2C/SPI:** AT24C32 EEPROM, DS1307 RTC, and ST7789 displays.
  - **CAN Bus:** High-speed communication using MCP2515.
  - **UART Multi-threading:** Designed thread-safe UART communication using **POSIX Threads (Pthreads)** for simultaneous Tx/Rx and telemetry handling.
- **Development & Debugging Toolchain:** Proficient in remote cross-platform development environment:
  - Real-time debugging using **GDB** and **VS Code Remote Development** over **SSH**.
  - System-level monitoring and remote administration via SSH & Secure SFTP.
  - **Roadmap:** Developing independent stand-alone instruments powered by **Qt/C++** on embedded Linux.

---

## 🔬 Hardware & Lab Instrumentation
- Hands-on troubleshooting and hardware debugging with Oscilloscopes and Spectrum Analyzers

📫 **Let's connect:** 
- [GitHub](https://github.com/Mortezaabdolahi)
- [Email](mailto:mortezaabdolahi007@gmail.com)
