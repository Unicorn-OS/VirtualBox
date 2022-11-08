"If your system is using EFI Secure Boot you may need to sign the
kernel modules (vboxdrv, vboxnetflt, vboxnetadp, vboxpci) before you can load
them. Please see your Linux system's documentation for more information."
—from: `sudo dnf install VirtualBox-7.0-*_fedora36-1.x86_64.rpm `

# Guide
https://gist.github.com/reillysiemens/ac6bea1e6c7684d62f544bd79b2182a4

[UEFI Linux Secure Boot Kernel Signing and Verification demo](https://youtu.be/SQ7Ajv2Cnzg)
- https://github.com/reachsameer911/UEFI_Secure_Boot

# Solution: Fedora
https://www.itzgeek.com/how-tos/linux/fedora-how-tos/install-virtualbox-on-fedora.html
>The problem is basically because secure boot requires VirtualBox kernel modules signed to run, you need to sign and compile. I found the solution here.
- https://ask.fedoraproject.org/t/virtualbox-still-cant-run-in-fedora-36-until-now/23664/14
