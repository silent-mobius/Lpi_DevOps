# 201

## Linux Kernel

### 201.1 Kernel Components

Weight: 2
Description: Candidates should be able to utilize kernel components that are necessary to specific hardware, hardware drivers, system resources and requirements. This objective includes implementing different types of kernel images, identifying stable and development kernels and patches, as well as using kernel modules.
Key Knowledge Areas:
    • Kernel 2.6.x, 3.x and 4.x documentation
Terms and Utilities:
    • /usr/src/linux/
    • /usr/src/linux/Documentation/
    • zImage
    • bzImage
    • xz compression

### 201.2 Compiling a kernel
Weight: 3
Description: Candidates should be able to properly configure a kernel to include or disable specific features of the Linux kernel as necessary. This objective includes compiling and recompiling the Linux kernel as needed, updating and noting changes in a new kernel, creating an initrd image and installing new kernels.
Key Knowledge Areas:
    • /usr/src/linux/
    • Kernel Makefiles
    • Kernel 2.6.x/3.x make targets
    • Customize the current kernel configuration.
    • Build a new kernel and appropriate kernel modules.
    • Install a new kernel and any modules.
    • Ensure that the boot manager can locate the new kernel and associated files.
    • Module configuration files
    • Use DKMS to compile kernel modules.
    • Awareness of dracut

### 201.3 Kernel runtime management and troubleshooting

Weight: 4
Description: Candidates should be able to manage and/or query a 2.6.x, 3.x or 4.x kernel and its loadable modules. Candidates should be able to identify and correct common boot and run time issues. Candidates should understand device detection and management using udev. This objective includes troubleshooting udev rules.
Key Knowledge Areas:
    • Use command-line utilities to get information about the currently running kernel and kernel modules
    • Manually load and unload kernel modules
    • Determine when modules can be unloaded
    • Determine what parameters a module accepts
    • Configure the system to load modules by names other than their file name.
    • /proc filesystem
    • Content of /, /boot/ , and /lib/modules/
    • Tools and utilities to analyze information about the available hardware
    • udev rules

