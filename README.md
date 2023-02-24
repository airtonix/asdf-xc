<div align="center">

# asdf-xc

[![Release](https://github.com/airtonix/asdf-xc/actions/workflows/release.yml/badge.svg)](https://github.com/airtonix/asdf-xc/actions/workflows/release.yml) [![Build](https://github.com/airtonix/asdf-xc/actions/workflows/build.yml/badge.svg)](https://github.com/airtonix/asdf-xc/actions/workflows/build.yml) [![Lint](https://github.com/airtonix/asdf-xc/actions/workflows/lint.yml/badge.svg)](https://github.com/airtonix/asdf-xc/actions/workflows/lint.yml)

[xc](https://xcfile.dev/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [asdf-xc](#asdf-xc)
- [Contents](#contents)
- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)
  - [Tasks](#tasks)
    - [setup-dev](#setup-dev)
    - [install](#install-1)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Plugin:

```shell
# asdf plugin add xc
# waiting for PR
# or
asdf plugin add xc https://github.com/airtonix/asdf-xc.git
```

xc:

```shell
# Show all installable versions
asdf list-all xc

# Install specific version
asdf install xc latest

# Set a version globally (on your ~/.tool-versions file)
asdf global xc latest

# Now xc commands are available
xc --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/airtonix/asdf-xc/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Zeno Jiricek](https://github.com/airtonix/)

## Tasks

This section is an actual task list for `xc`

### setup-dev

Sets up local development on the plugin

```sh
rm -rf ~/.asdf/plugins/xc
ln -s $(pwd) $HOME/.asdf/plugins/xc
asdf list-all xc
asdf install xc latest
```

### install

installs plugin from asdf

```sh
asdf plugin remove xc
asdf plugin add xc https://github.com/airtonix/asdf-xc.git
```
