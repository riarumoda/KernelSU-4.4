**Warning: this repo is only intended to integrate KernelSU into Android with Linux Kernel 4.4. This is why manager, website, userspace, js, SECURITY.md, justfile has been removed.**

# KernelSU

<img src="https://kernelsu.org/logo.png" style="width: 96px;" alt="logo">

A Kernel-based root solution for Android devices.

[![Main Repo](https://img.shields.io/badge/Main_repository-8A2BE2)](https://github.com/tiann/KernelSU)
[![License: GPL v2](https://img.shields.io/badge/License-GPL%20v2-orange.svg?logo=gnu)](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html)
[![GitHub License](https://img.shields.io/github/license/tiann/KernelSU?logo=gnu)](/LICENSE)

## Features

1. Kernel-based `su` and root access management.
2. Module system based on [OverlayFS](https://en.wikipedia.org/wiki/OverlayFS).
3. [App Profile](https://kernelsu.org/guide/app-profile.html): Lock up the root power in a cage.

## Compatibility State

- This KernelSU fork unofficially supports Android kernels (kernel 4.4+), but the kernel will have to be built manually.
- Also, please use the "Manually modify the kernel source" way of integrating KernelSU into your device, not by using kprobes.

## Usage

- [Integrate KernelSU into your kernel](https://kernelsu.org/guide/how-to-integrate-for-non-gki.html)
- [SELinux patch to make modules working properly](https://github.com/F-19-F/android_kernel_oneplus_msm8998/commit/1042d5601a1c0db08c9a9cea89d1895e74576a27)
- [Official Website](https://kernelsu.org/)

## Discussion

- Telegram: [@KernelSU](https://t.me/KernelSU)
- Editor of this fork: [@TheRealModder](https://t.me/TheRealModder)

## License

- Files under the `kernel` directory are [GPL-2.0-only](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html).
- All other parts except the `kernel` directory are [GPL-3.0-or-later](https://www.gnu.org/licenses/gpl-3.0.html).

## Credits

- [KernelSU](https://github.com/tiann/KernelSU): the original repo and the creator.
- [kernel-assisted-superuser](https://git.zx2c4.com/kernel-assisted-superuser/about/): the KernelSU idea.
- [Magisk](https://github.com/topjohnwu/Magisk): the powerful root tool.
- [genuine](https://github.com/brevent/genuine/): apk v2 signature validation.
- [Diamorphine](https://github.com/m0nad/Diamorphine): some rootkit skills.
