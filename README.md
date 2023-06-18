<div align="center">

# asdf-nnn [![Build](https://github.com/benit8/asdf-nnn/actions/workflows/build.yml/badge.svg)](https://github.com/benit8/asdf-nnn/actions/workflows/build.yml) [![Lint](https://github.com/benit8/asdf-nnn/actions/workflows/lint.yml/badge.svg)](https://github.com/benit8/asdf-nnn/actions/workflows/lint.yml)

[nnn](https://github.com/jarun/nnn) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `libncurses`
- `libreadline`

# Install

Plugin:

```shell
asdf plugin add nnn
# or
asdf plugin add nnn https://github.com/benit8/asdf-nnn.git
```

nnn:

```shell
# Show all installable versions
asdf list-all nnn

# Install specific version
asdf install nnn latest

# Set a version globally (on your ~/.tool-versions file)
asdf global nnn latest

# Now nnn commands are available
nnn -h
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/benit8/asdf-nnn/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Benoît Lormeau](https://github.com/benit8/)
