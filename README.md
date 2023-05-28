<div align="center">

# asdf-tlsgcli [![Build](https://github.com/0ghny/asdf-tlsgcli/actions/workflows/build.yml/badge.svg)](https://github.com/0ghny/asdf-tlsgcli/actions/workflows/build.yml) [![Lint](https://github.com/0ghny/asdf-tlsgcli/actions/workflows/lint.yml/badge.svg)](https://github.com/0ghny/asdf-tlsgcli/actions/workflows/lint.yml)

[tlsg10x-cli](https://github.com/0ghny/tlsg10x-cli) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [asdf-tlsgcli ](#asdf-tlsgcli--)
- [Contents](#contents)
- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- **Optional**: `ASDF_TLSGCLI_OVERWRITE_ARCH` if present you can specify arch to download an specific one.

# Install

Plugin:

```shell
asdf plugin add tlsg-cli https://github.com/0ghny/asdf-tlsgcli.git
```

tlsg-cli:

```shell
# Show all installable versions
asdf list-all tlsg-cli

# Install specific version
asdf install tlsg-cli latest

# Set a version globally (on your ~/.tool-versions file)
asdf global tlsg-cli latest

# Now tlsg-cli commands are available
tlsg-cli --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/0ghny/asdf-tlsgcli/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [0ghny](https://github.com/0ghny/)
