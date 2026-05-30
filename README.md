![Project Lead](https://img.shields.io/badge/Aether_Infra-Project_Lead-6b1e23?style=for-the-badge&logo=gnubash&logoColor=white)
![Core Maintainer](https://img.shields.io/badge/Aether_Infra-Core_Maintainer-2d1e2f?style=for-the-badge&logo=gnubash&logoColor=white)

# Hi, I'm Aritrash Sarkar

### Systems & Kernel Developer | Hardware-Software Integration | Deep-Tech R&D

I am a low-level systems engineer focused on **operating systems, kernel scheduling, and embedded hardware architectures**. 

I build software where the hardware constraints are absolute—from custom bare-metal bootloaders and intent-aware task schedulers for ARM AArch64, to patented edge-inference sensor networks and custom PCB designs. My work focuses on understanding and manipulating modern computing architectures (ARM, x86_64) directly at the silicon level to build deeply integrated, reliable infrastructure.

---

### 🚀 Flagship Project: Obisync Kernel
A bare-metal operating system kernel built for ARM AArch64, successfully booted and validated on physical Raspberry Pi 4 hardware.
* **ITAS (Intent Aware Scheduler):** Designed and implemented a custom $O(1)$-style semantic scheduling framework. It evaluates execution heat, starvation pressure, and latency sensitivity to dynamically adapt execution strategy without expensive global sweeps.
* **Memory Management:** Actively developing the MM5 subsystem, focusing on Userspace Virtual Addressing (VA), Page Table isolation, and User Code Mapping (MM5.D.C).
* **Hardware Validation:** Passed physical silicon startup self-tests, validating UART initialization, memory management, and framebuffer setups with HDMI output.

### ⚡ Hardware Engineering & Patents
I actively design physical sensor networks and PCB architectures, writing the firmware that bridges low-level code with environmental hardware.
* **AQI Monitor (Form 2 Patent Pending):** Designed a custom double-sided PCB integrating an analog front-end (LM358/LM339) for a laser-based Mie scattering chamber. Executes a TinyML inference model directly on an ESP32 for real-time, cloud-independent particulate quantification.
* **ADEMS (Form 2 Patent Pending):** A decentralized, multi-modal sensor fusion building management system. Features hierarchical conditional edge-inference activation to heavily optimize power consumption across distributed IoT nodes.
* **Hardware Interfacing:** Extensive development with ESP32 to Raspberry Pi 4 distributed communication protocols, I2C/SPI sensor integrations, and custom PCB designs (e.g., MIDI DrumBridge).

### 🛠️ The AetherOS Project
A family of experimental operating systems targeting distinct architectures, built to establish foundational IP for future ARM ecosystem manufacturing and edge-compute fabrics.
* **Aether Grim (x86-64 | Rust):** A monolithic desktop OS kernel built with Limine, featuring a custom Physical/Virtual Memory Manager, double-buffered software compositor, and GUI framework.
* **Aether EdgeCloud (ARMv8 | Rust):** An infrastructure OS designed for headless server environments, featuring VirtIO drivers, a smoltcp networking stack, and an EL1 kernel.
* **Aether WebOS (ARM | C):** A lightweight server OS focusing on networking infrastructure, featuring a custom TCP stack, PCI enumeration, and xHCI USB drivers. *(Copyright Application Pending).*
* **AcceleronOS (16-bit Assembly):** A custom, monolithic kernel built entirely in NASM x86 Assembly running in real-mode.

### 🔬 Research & Innovation
* **Photonics Computing:** Actively conducting research on Non-Binary Polarization-Coded Photonic Computing paradigms.
* **Texas A&M Invent for the Planet 2025:** Winner.
* **Ministry of Education (MoE) IIC:** Appointed Innovation Ambassador.

### 🎸 Beyond the Terminal: Audio Systems
Systems engineering extends directly into my audio production work. As a rhythm guitarist, vocalist, and producer, I manage zero-latency digital signal chains, DSP configurations in Reaper, and technical tracking setups for live acoustic drumming. Managing high-fidelity audio buffers and hardware routing requires the exact same mechanical sympathy as writing a kernel scheduler or optimizing a TCP stack.

---

### 💻 Technologies & Architectures
* **Languages:** C, Rust, C++, Python, NASM Assembly.
* **Architectures:** ARM AArch64, ARMv8, x86-64.
* **Systems Concepts:** Bare-metal Bootloaders, Memory Management (Paging/Virtual Addressing), Device Drivers (PCI, VirtIO, USB xHCI), Kernel Networking, Edge ML (TinyML).

---
📫 **Connect With Me**
* **LinkedIn:** https://linkedin.com/in/aritrash-sarkar
* **ORCID:** 0009-0004-4878-8199
* **Email:** aritrashsarkar@gmail.com

<p align="center">
<i>
"Understanding systems from the transistor to the application layer enables building truly reliable software."
</i>
</p>
