# kido

kido runs macOS command-line tools in small Darwin VMs on Apple Silicon Macs. You use it like
Docker, and each container boots a real Darwin kernel in about half a second.

```console
$ kido run --rm darwin sw_vers
ProductName:	KidoDarwin
ProductVersion:	26.5
BuildVersion:	25F74
```

- [kido](https://github.com/kido-sh/kido): the command-line tool. Start here.
- [darwin](https://github.com/kido-sh/darwin): KidoDarwin, the Darwin system inside every container
- [homebrew-tap](https://github.com/kido-sh/homebrew-tap): `brew install kido-sh/tap/kido`, from the
  first release on
- [kido.sh](https://kido.sh): the website

kido is open source under the Apache License 2.0. It is not affiliated with Apple or Docker.
