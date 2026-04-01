# Gunball Kernel v1.0

A modular, Unix-like x86_64 microkernel designed for simplicity, educational purposes, and community-driven expansion.

---

## 👤 Author & Original Creator
**Gabriel Ramos**
> This project was conceived and built by Gabriel Ramos. While I am the original creator, Gunball Kernel is an **Open Source** project. 

## ⚖️ License
This project is licensed under the **MIT License**. 
* You **can** use, modify, and distribute this code.
* You **must** keep the original copyright notice (crediting Gabriel Ramos).
* The software is provided "as is", without warranty of any kind.

---

## 🚀 About Gunball Kernel
Gunball Kernel is a lightweight 64-bit "all-in-one" monolithic-modular kernel. It is built to be a starting point for developers interested in OS development (OSDev).

### Core Features:
* **Pure x86_64:** Runs in Long Mode for 64-bit performance.
* **Direct Hardware Access:** Includes basic drivers for:
    * **VGA Text Mode:** Direct writing to video memory (`0xB8000`).
    * **ATA PIO:** Basic Hard Drive (HD) identification and communication.
    * **PS/2 Keyboard:** Polling-based input for shell interaction.
* **Expandable Architecture:** Features a command registry system that allows anyone to add new features without modifying the core kernel logic.
* **Built-in Shell:** A Unix-like interface with essential commands:
    * `dir`: List system files.
    * `sudo`: Gain kernel-level privileges.
    * `ram`: Check memory status.
    * `hd`: Hardware disk diagnostics.
    * `exit`: Halt the system.

---
