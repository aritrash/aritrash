![Project Lead](https://img.shields.io/badge/Aether_Infra-Project_Lead-7b2cbf?style=for-the-badge&logo=cpu&logoColor=white)
![Core Maintainer](https://img.shields.io/badge/Aether_Infra-Core_Maintainer-5a189a?style=for-the-badge&logo=cpu&logoColor=white)

# Hi, I'm Aritrash 

### Systems & Kernel Developer | Low-Level Engineer

I am a systems developer focused on **operating systems, kernel engineering, and low-level infrastructure**.  
I enjoy building software where hardware and software meet — from **bootloaders and memory managers to device drivers, compositors, and networking stacks**.

Most of my work revolves around **building operating systems and system infrastructure from scratch** to deeply understand how modern computing systems work.

---

# Core Projects

## AetherOS Project
A family of experimental operating systems targeting different architectures and use-cases.

### Aether Grim (x86-64 | Rust)
A modern **monolithic desktop operating system kernel** built using the **Limine bootloader**.

**Key components implemented**

• Physical Memory Manager (PMM)  
• Virtual Memory / Paging  
• GDT, IDT, PIC, PIT timer  
• PS/2 keyboard and mouse drivers  
• Software compositor with:
  - window buffers  
  - alpha blending  
  - z-order management  
  - double buffering  
• Window manager and GUI framework  
• GrimBox built-in shell  
• Custom rendering pipeline (framebuffer + backbuffer)  

Currently expanding with:

• Filesystem support  
• USB input drivers (xHCI / OHCI)  
• networking stack  
• optional **headless server mode with web dashboard**

---

### Aether EdgeCloud (ARMv8 | Rust)
An **ARM64 infrastructure operating system** designed for **headless server environments**.

Focus areas:

• ARM exception levels (EL1 kernel)  
• PCI subsystem  
• VirtIO drivers (GPU, networking)  
• smoltcp networking stack  
• device driver framework  

The OS is designed to run **server workloads with web-based management interfaces** instead of local GUIs.

---

### Aether WebOS (ARM | C)
A lightweight ARM server OS written in **C**, focusing on networking and infrastructure.

Features include:

• custom TCP stack  
• VirtIO networking  
• PCI enumeration  
• xHCI USB driver implementation  
• minimal web-based system interface

---

### AcceleronOS (x86 Assembly)
A **16-bit bare-metal operating system written entirely in NASM assembly**.

Features:

• custom bootloader  
• real-mode kernel  
• CLI shell  
• BIOS interrupt programming  
• FAT filesystem experiments

This project was my entry point into **low-level systems development**.

---

# Areas of Interest

• Operating Systems  
• Kernel Engineering  
• Device Drivers  
• Datacenter & Infrastructure Systems  
• Distributed Systems Foundations  
• CPU Architecture (x86 & ARM)  
• Low-level Graphics Systems  
• Embedded & IoT systems

---

# Technologies & Tools

### Languages
Rust • C • C++ • Python • NASM Assembly

### Systems / Low-Level
x86-64 Architecture  
ARMv8 Architecture  
Bootloaders (Limine)  
Interrupt Systems  
Memory Management  
Device Drivers (PS/2, PCI, VirtIO, USB)  
Framebuffer Graphics  
Kernel Networking

### Tools
Git • QEMU • Linux • Makefiles • Bare-metal debugging

---

# Research & Engineering Work

• Research in **non-binary photonics computing**  
• Hardware + IoT engineering projects  
• Texas A&M **Invent for the Planet 2025 winner**  
• Innovation Ambassador (MoE IIC)

---

# Connect With Me

LinkedIn  
https://www.linkedin.com/in/aritrash-sarkar-50800b23b/

Email  
aritrashsarkar@gmail.com

GitHub  
https://github.com/aritrash

---

<p align="center">
<i>
"Understanding systems from the transistor to the application layer enables building truly reliable software."
</i>
</p>
