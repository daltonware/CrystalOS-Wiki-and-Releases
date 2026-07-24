# 💎 CrystalOS

> *A system made for you, all for you.*

CrystalOS is a custom, 32-bit (x86) operating system built entirely from scratch. Designed as a personal learning journey into low-level systems engineering, it features a custom graphical interface, hardware communication, and direct memory management without relying on external libraries or standard operating systems.

## 🚀 Features

- **Custom Graphical User Interface (GUI):** Direct pixel rendering via the Multiboot2 framebuffer, completely independent of X11 or Wayland.
- **Bitmap Font Rendering:** A built-in, lightweight 8x16 font reader for rendering text natively on the screen.
- **Hardware Interrupts (IDT/PIC):** Fully remapped Programmable Interrupt Controller and Interrupt Descriptor Table to handle hardware signals.
- **PS/2 Driver Support:** Custom written drivers for PS/2 Keyboard and Mouse interactions (in active development).
- **State Machine UI:** A structured, state-based visual setup process (Welcome Screen, Disk Manager, etc.).
- **Multiboot2 Compliant:** Bootable via GRUB and compatible with modern x86 emulation.

## 🛠️ Building and Running

To compile and run CrystalOS, you will need a Linux environment (or WSL) with the following tools installed:

*   `i686-elf-gcc` (Cross-compiler)
*   `nasm` (Assembler)
*   `grub-mkrescue` and `xorriso` (For ISO generation)
*   `qemu-system-i386` (For emulation)

### Instructions

1. Clone the repository:
   ```bash
   git clone [https://github.com/daltonware/CrystalOS.git](https://github.com/daltonware/CrystalOS.git)
   cd CrystalOS
