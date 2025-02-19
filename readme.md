
# Linux 0.0.1 Kernel (32-bit Port)

## Overview

This project is a **32-bit port of the original Linux v0.0.1 kernel**, which was initially developed by **Linus Torvalds** for the **16-bit 8086 microprocessor**. The goal is to adapt the earliest version of Linux to run on a **modern 32-bit Intel i3 processor**, preserving its historical significance while enhancing compatibility.

### Major Changes
- **Assembly Code Updated to 32-bit Format**: The original 16-bit assembly has been rewritten to support protected mode.
- **Recursive Makefiles Updated**: The build system used very old tools and has been modernized for today's toolchains.
- **New Toolchain Compatibility**: The code is now compatible with modern **GCC, Binutils, and NASM**.

## Features

- **Bootable 32-bit Kernel**: Modified to support **protected mode** on Intel i3 processors.
- **Memory Management Updates**: Adapts original segmentation to a **flat memory model**.
- **Filesystem Handling**: Retains early Linux filesystem structure.
- **Process Management**: Supports **basic task scheduling and system calls**.
- **Enhanced Debugging**: Includes modifications for **32-bit system diagnostics**.

## Installation

### Prerequisites

- **QEMU** or **Bochs** for testing.
- **GCC and Binutils** with cross-compilation support for **i386**.
- **NASM** for assembling boot code.

### Building the Kernel

1. Clone the repository:

   ```bash
   git clone https://github.com/Low-Level-Tiwari/Linux-0.0.1-Kernel.git
   cd Linux-0.0.1-Kernel
   ```

2. Compile the kernel:

   ```bash
   make
   ```

3. Run using QEMU:

   ```bash
   qemu-system-i386 -kernel linux-0.0.1.bin
   ```

## Future Improvements

- Implement a **fully functional 32-bit user space**.
- Add **basic device driver support**.
- Improve **memory management for extended RAM**.

## License

This project follows the original **GPL license** of Linux.

## Contact

For questions and discussions, open an issue on **GitHub**.
