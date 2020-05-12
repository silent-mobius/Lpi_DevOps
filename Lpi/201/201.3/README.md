# 201


## System Startup

### 202.1 Customizing SysV-init system startup

Weight: 3
Description: Candidates should be able to query and modify the behaviour of system services at various targets / run levels. A thorough understanding of the systemd, SysV Init and the Linux boot process is required. This objective includes interacting with systemd targets and SysV init run levels.
Key Knowledge Areas:
    • Systemd
    • SysV init
    • Linux Standard Base Specification (LSB)

### 202.2 System Recovery

Weight: 4
Description: Candidates should be able to properly manipulate a Linux system during both the boot process and during recovery mode. This objective includes using both the init utility and init-related kernel options. Candidates should be able to determine the cause of errors in loading and usage of bootloaders. GRUB version 2 and GRUB Legacy are the bootloaders of interest. Both BIOS and UEFI systems are covered.
Key Knowledge Areas:
    • BIOS and UEFI
    • NVMe booting
    • GRUB version 2 and Legacy
    • grub shell
    • boot loader start and hand off to kernel
    • kernel loading
    • hardware initialisation and setup
    • daemon/service initialisation and setup
    • Know the different boot loader install locations on a hard disk or removable device.
    • Overwrite standard boot loader options and using boot loader shells.
    • Use systemd rescue and emergency modes.

### 202.3 Alternate Bootloaders

Weight: 2
Description: Candidates should be aware of other bootloaders and their major features.
Key Knowledge Areas:
    • SYSLINUX, ISOLINUX, PXELINUX
    • Understanding of PXE for both BIOS and UEFI
    • Awareness of systemd-boot and U-Boot
Topic 203: Filesystem and Devices


