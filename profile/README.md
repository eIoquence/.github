![Eloquence Logo](./eloquence.png#gh-dark-mode-only)
![Eloquence Logo](./eloquence.png#gh-light-mode-only)

<p align="center"><strong>Eloquence</strong> — a hardware-first exokernel research project</p>
<p align="center">we do behind-the-scenes operations</p>

## About

Eloquence explores how an operating system can give software explicit, controlled ownership of hardware resources while retaining isolation and a measurable kernel boundary. Research focus: a hardware resource lifecycle — Discovery → Authorization → Allocation → Ownership → Revocation → Release.

## Projects

- **eloquence** — experimental x86-64 exokernel with QEMU baseline, capability-mediated MMIO, VirtIO block, FAT32 VFS, static ELF loader, and a ring-3 shell.

## Status

Kernel bring-up in progress. x86-64 boots under QEMU with a serial monitor and a user-space shell. AArch64, RV64 and MIPS32 have bootstrap sources.

## Links

- Repository: https://github.com/eIoquence/eloquence
