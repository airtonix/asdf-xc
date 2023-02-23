<div align="center">

# asdf-xcfile [![Build](https://github.com/airtonix/asdf-xcfile/actions/workflows/build.yml/badge.svg)](https://github.com/airtonix/asdf-xcfile/actions/workflows/build.yml) [![Lint](https://github.com/airtonix/asdf-xcfile/actions/workflows/lint.yml/badge.svg)](https://github.com/airtonix/asdf-xcfile/actions/workflows/lint.yml)


[xcfile](https://xcfile.dev/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add xcfile
# or
asdf plugin add xcfile https://github.com/airtonix/asdf-xcfile.git
```

xcfile:

```shell
# Show all installable versions
asdf list-all xcfile

# Install specific version
asdf install xcfile latest

# Set a version globally (on your ~/.tool-versions file)
asdf global xcfile latest

# Now xcfile commands are available
xcfile --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/airtonix/asdf-xcfile/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Zeno Jiricek](https://github.com/airtonix/)
