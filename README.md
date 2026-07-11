# KhanOS
KhanOS Feodal v1.0 - Hardened Linux Distro with Post-Quantum Encryption &amp; 1000-Year SSL. 
​I want to introduce a project I've been working on: KhanOS Feodal v1.0. It’s a minimalist, ARM-based, hardened Linux distribution (0.98 GB) designed with a "Digital Fortress" philosophy. It is now officially archived on Archive.org.


​Key Technical Features:




​Kernel: Hardened Linux 6.6.117.


​Architecture: Optimized for ARM, booting via UEFI with a focus on Secure Boot integrity.


​Read-Only Root: The system operates on a Read-Only filesystem, making it immune to persistent malware. Every reboot restores the "Fortress" to its original state.


​Post-Quantum Cryptography: Implements X25519MLKEM768 (Kyber) for key exchange, ensuring the traffic remains secure even against future quantum computing threats.


​Anonymity by Default: Integrated Toorg protocol. All incoming ports are closed/stealth by default (verified via Nmap).


​The 1000-Year Shield: I have generated a custom Root CA and SSL certificates with a 1000-year validity (expiring in 3026). The certificate is hard-coded with my identity and locality: C=AZ, L=Sumgait. It’s built to outlast us all.




​Design Philosophy:

​
The UI follows the Y2K / Classic Windows Skeuomorphic (inspired by Windows XP/Longhorn) and Retro Cyberpunk aesthetic—aiming to make security feel transparent and optimistic... It uses the Sway(Wayland) window manager for maximum efficiency.And Support True color(32 Bit , native resolution)


​Disclaimer/Warning:

KhanOS is currently optimized for the ARM64 (AArch64) architecture (Kernel 6.6.117-virt). If booted directly inside standard x86_64 (Intel/AMD) virtual environments (such as VirtualBox or VMware running on a traditional PC), you will encounter the EFI Shell screen due to architecture mismatch.

​Recommended Environments:

​Apple Silicon Mac (M1/M2/M3/M4): UTM or VMware Fusion (Native ARM64 virtualization)


​Classic PC (x86_64): A custom-configured qemu-system-aarch64 emulator with ARM64 UEFI firmware (QEMU_EFI.fd).

​Made with pride in Azerbaijan! 🇦🇿


​I’d love to hear your thoughts on the 1000-year certificate approach and the Post-Quantum integration.


​Archive Link: https://archive.org/details/khanos_feodal_arm_test

The link and ISO file are on archive.org 

We have 66 votes on Distrowatch in the waiting list

#contact - kmailhan@atomicmail.io
