![NetHunter_banner](https://github.com/user-attachments/assets/1a49a2cd-bb47-47b2-b8bd-437ad003415c)

# NetHunter Kernel - OnePlus 6 SDM845 (enchilada)

Official lineage documentation has been moved to <a href="Documentation/README">Documentation</a>

This is a Kernel port for Kali NetHunter from LineageOS 22.2

Made for OnePlus 6 SDM845 (enchilada)

## Building

You can find official build on Kali Linux website, or build it yourself from my sources.

First, clone this repository with it's submodules.

```
git clone --recurse-submodules https://github.com/V0lk3n/nethunter_kernel_oneplus_sdm845.git -b nethunter-lineage-22.2
```

Enter into Kali Linux Kernel Builder and copy local.config to it.

```
cd nethunter_kernel_oneplus_sdm845/kali-nethunter-kernel-builder
cp ../nh_files/local.config .
```
Build the kernel.

```
./build.sh
```

For more informations, take a read of the official Kali Linux Nethunter documentations.
