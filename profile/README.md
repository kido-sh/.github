# kido

macOS command-line tools in tiny Darwin containers on Apple Silicon, with the commands you know from
Docker. Each container is its own micro-VM that boots an open-source Darwin guest in about half a
second.

- [kido](https://github.com/kido-sh/kido): the CLI, its guest agent and the Virtualization.framework helper
- [darwin](https://github.com/kido-sh/darwin): the Darwin guest system (in progress)
- [homebrew-tap](https://github.com/kido-sh/homebrew-tap): `brew install kido-sh/tap/kido` (from the first release on)
- [kido.sh](https://kido.sh): the website and the installer

kido is open source under the Apache License 2.0 and is not affiliated with Apple.
