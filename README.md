![Project Lead](https://img.shields.io/badge/Aether_Infra-Project_Lead-6b1e23?style=for-the-badge&logo=gnubash&logoColor=white)
![Core Maintainer](https://img.shields.io/badge/Aether_Infra-Core_Maintainer-2d1e2f?style=for-the-badge&logo=gnubash&logoColor=white)
![DTPU](https://img.shields.io/badge/DTPU-Distributed_Systems_Engineer-0D47A1?style=for-the-badge&logo=raspberrypi&logoColor=white)

# Hi, I'm Aritrash Sarkar

### Systems & Hardware Architect | HW/SW Co-Design | Deep-Tech R&D

I build at the absolute intersection of physical silicon and system software. 

My core engineering focus is on pushing the boundaries of chip microarchitecture, maximizing performance-per-watt, and writing the bare-metal OS kernels and firmware required to drive custom hardware. I specialize in understanding and manipulating modern computing architectures (ARM, x86_64) directly at the silicon level to build deeply integrated, reliable infrastructure.

🔗 **[📄 View My Resume: Systems & Hardware Architect](Resume_Jun26.pdf)**

---

### Flagship Project: Obisync Kernel
A bare-metal operating system kernel built for ARM AArch64, successfully booted and validated on physical Raspberry Pi 4 hardware.
* **Bare-Metal Initialization:** Passed physical silicon startup self-tests, bypassing virtualization to validate UART initialization and framebuffer setups with HDMI output.
* **Memory Management:** Actively developing the MM5 subsystem, focusing on Userspace Virtual Addressing (VA), Page Table isolation, and User Code Mapping (MM5.D.C).

### Patent-Pending Edge Hardware
I actively design physical sensor networks and PCB architectures, writing the firmware that bridges low-level code with environmental hardware.
* **ADEMS (Form 2 Patent Pending):** Engineered an Active Decentralized Embedded Management System integrating custom hardware and Convolutional Neural Networks across ESP32 and Raspberry Pi nodes. Features hierarchical conditional edge-inference activation to optimize power consumption.
* **Desktop AQI Sensor (Form 2 Patent Pending):** Designed a custom double-sided PCB integrating an analog front-end for a laser-based Mie scattering chamber. Executes a TinyML inference model directly on an ESP32 for real-time, cloud-independent particulate quantification.
* **Hardware Interfacing:** Extensive development with ESP32 to Raspberry Pi 4 distributed communication protocols, I2C/SPI sensor integrations, and custom PCB designs (e.g., MIDI DrumBridge).

### The Aether OS Ecosystem
A family of experimental operating systems targeting distinct architectures, built to establish foundational IP for future ARM ecosystem manufacturing and edge-compute fabrics.
* **Aether WebOS (ARM | C):** An ARM-native headless server OS kernel featuring minimal drivers, a custom TCP stack, PCI enumeration, and VirtIO support on QEMU. *(Copyright Application Submitted).*
* **Aether EdgeCloud (ARMv8 | Rust):** An ARM64 EL2 micro-hypervisor designed for infrastructure OS and headless server environments.
* **Aether Grim (x86-64 | Rust):** A monolithic desktop OS bare-metal kernel built with Limine, featuring a custom Physical/Virtual Memory Manager.
* **AcceleronOS (16-bit Assembly):** A custom, monolithic kernel built entirely in NASM x86 Assembly running in real-mode.

### Research & Innovation
* **Ternary Photonic Architecture (TPA-1):** Architecting a 3D stacked die framework featuring MRR technology and a custom Photonic ALU to bypass traditional CMOS bottlenecks. 
* **Texas A&M Invent for the Planet 2025:** Winner.
* **Ministry of Education (MoE) IIC:** Appointed Innovation Ambassador.

### Digital Signal Processing & Audio Systems
Systems engineering extends directly into my audio production work. As a rhythm guitarist, vocalist, and producer, I manage zero-latency digital signal chains, DSP configurations in Reaper, and technical tracking setups for live acoustic drumming. Managing high-fidelity audio buffers and hardware routing requires the exact same mechanical sympathy as writing a kernel scheduler or optimizing a TCP stack.

---

### Technologies & Architectures
* **Languages:** C, Rust, C++, Python, NASM Assembly, Verilog.
* **Architecture & Core:** HW/SW Co-Design, Kernel Development, Chip Microarchitecture, VLSI Design, SoC Power Integrity.
* **Systems Concepts:** Bare-Metal Bootloaders, Memory Management (Paging/Virtual Addressing), Device Drivers (PCI, VirtIO, USB xHCI), Edge ML (TinyML).

---
**Connect With Me**
* **LinkedIn:** https://linkedin.com/in/aritrash-sarkar
* **ORCID:** 0009-0004-4878-8199
* **Email:** aritrashsarkar@gmail.com

<p align="center">
<i>
"Understanding systems from the transistor to the application layer enables building truly reliable software."
</i>
</p>
