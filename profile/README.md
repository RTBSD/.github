# RTBSD

> RTBSD, an embedded system development solution that combines RTOS and BSD

RTBSD (RTOS + BSD) is an environment specifically designed for embedded system development. It integrates an RTOS kernel with BSD driver components. This environment is mainly targeted at microprocessor unit (MPU) systems equipped with a memory management unit (MMU), covering architectures such as ARM64, x86, and RISCV64. These systems can obtain excellent driver support under general-purpose operating systems like FreeBSD and Linux, especially for complex buses such as USB and PCIe. However, real-time operating systems (RTOS) often lack support for these complex bus drivers. With RTBSD, developers can seamlessly integrate mature driver components from UNIX-like general-purpose systems such as FreeBSD, NetBSD, and OpenBSD into the RTOS kernel, significantly enhancing the driver capabilities of the real-time operating system.

> RTBSD, 融合 RTOS 与 BSD 的嵌入式系统开发方案

RTBSD（RTOS + BSD）是一款专为嵌入式系统开发量身打造的环境，它将 RTOS 内核与 BSD 驱动组件相结合。该环境主要面向配备内存管理单元（MMU）的微处理器单元（MPU）系统，涵盖 ARM64、x86 和 RISCV64 等架构。这些系统在 FreeBSD、Linux 等通用操作系统下能获得出色的驱动支持，尤其是针对 USB、PCIe 等复杂总线的驱动。然而，实时操作系统（RTOS）在这些复杂总线驱动方面的支持往往较为匮乏。借助 RTBSD，开发者能够将 FreeBSD、NetBSD、OpenBSD 等类 UNIX 通用系统中成熟的驱动组件无缝整合到 RTOS 内核里，显著增强实时操作系统的驱动能力
