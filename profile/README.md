# kido

Fast, lightweight macOS micro-VMs on Apple Silicon Macs and ARM64 Linux hosts. Each container boots
a real Darwin kernel in around a second with Apple's Virtualization.framework on macOS or kido's
built-in KVM VMM on ARM64 Linux, with no QEMU required.

```console
$ curl -fsSL https://kido.sh/install.sh | sh
$ kido run --rm darwin sw_vers
ProductName:	KidoDarwin
ProductVersion:	26.5
BuildVersion:	25F74
```

- [kido](https://github.com/kido-sh/kido): the CLI, macOS Virtualization.framework VMM, Linux KVM VMM and guest agent. Start here.
- [darwin](https://github.com/kido-sh/darwin): KidoDarwin, the ~30 MB open-source Darwin guest OS built with Nix
- [homebrew-tap](https://github.com/kido-sh/homebrew-tap): `brew install kido-sh/tap/kido`
- [kido.sh](https://kido.sh): website and install script

kido is open source under the Apache License 2.0. It is not affiliated with Apple.
