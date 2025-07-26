# Pardus-EYLÜL Operating System

### https://github.com/Alperen-developer/NeOx-OS-Project

**Pardus-EYLÜL** is an experimental, security-focused operating system architecture based on UNIX principles. It is designed with a modular kernel-layer interface, BIOS/UEFI compatibility, TPM 2.0 integration, and custom hardware interaction layers. The project serves as a forward-looking implementation of a fully auditable and customizable system software stack, aiming for high assurance computing on local infrastructure.

### https://github.com/Alperen-developer/NeOx-OS-Project

---

## 🎯 Project Objectives

- To develop a national and independent UNIX-compatible OS with emphasis on kernel-level security and BIOS-hardware compliance.
- To explore alternative kernel-hardening models and early-boot chain validation mechanisms.
- To establish a minimal, deterministic, and maintainable kernel infrastructure as a foundation for secure userland environments.

---

## ⚙️ Core Features

| Feature | Description |
|--------|-------------|
| 🧠 **Custom Kernel Interface** | Modular UNIX-like kernel interface with pre-defined system call filters |
| 🔐 **TPM 2.0 Support** | Trusted Platform Module initialization and secure boot binding |
| 🧩 **BIOS/UEFI Layer Analysis** | BIOS interrupt tracing and UEFI runtime mapping for system-level boot consistency |
| 🛡️ **Early Boot Security** | Secure Boot, GRUB-hardening, and multistage boot script control |
| 🧬 **Hardware-Level Abstraction** | PCI, ACPI, and SMBIOS table parsing with system-specific optimizations |
| 📉 **Low Latency Kernel Patching** | Near-real-time interrupt response tuning and latency-lowering syscalls |
| 📊 **System Integrity Framework** | SHA-256 based integrity tree for read-only system partitions (planned) |

---

## 📈 Development Roadmap

- [x] Project architectural documentation (v1.0)
- [x] Initial BIOS/TPM compatibility table creation
- [ ] Custom kernel init (first-stage boot setup)
- [ ] QEMU ISO prototype and testbed integration
- [ ] GUI installer (TUI fallback planned)
- [ ] Secure memory allocation model (Rust/WASM research phase)

---

## 🤖 Technologies Used

- **UNIX (POSIX compatibility subset)**
- **GRUB2** (custom scripts & validation)
- **x86_64 Assembly** (bootloader and early init)
- **C/C++ (kernel core modules)**
- **TPM 2.0 & UEFI runtime specs**
- **Bash/Python for tooling & diagnostics**

---

## Team İnformation
- e-mail : *timonto43@gmail.com*
- localtion : *Turkiye/Çankaya*
- https://gitlab.com/datakral/Pardus-EYLUL
- https://github.com/Alperen-developer/NeOx-OS-Project

