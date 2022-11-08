"If your system is using EFI Secure Boot you may need to sign the
kernel modules (vboxdrv, vboxnetflt, vboxnetadp, vboxpci) before you can load
them. Please see your Linux system's documentation for more information."

# Solution: Fedora
https://www.itzgeek.com/how-tos/linux/fedora-how-tos/install-virtualbox-on-fedora.html
>The problem is basically because secure boot requires VirtualBox kernel modules signed to run, you need to sign and compile. I found the solution here.
- https://ask.fedoraproject.org/t/virtualbox-still-cant-run-in-fedora-36-until-now/23664/14

tested: Doesn't work, but the default directory in "/sbin/vboxconfig" helptext Does!
