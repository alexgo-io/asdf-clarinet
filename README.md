<div align="center">

# asdf-clarinet [![Build](https://github.com/bestmike007/asdf-clarinet/actions/workflows/build.yml/badge.svg)](https://github.com/bestmike007/asdf-clarinet/actions/workflows/build.yml) [![Lint](https://github.com/bestmike007/asdf-clarinet/actions/workflows/lint.yml/badge.svg)](https://github.com/bestmike007/asdf-clarinet/actions/workflows/lint.yml)

[clarinet](https://github.com/hirosystems/clarinet/releases) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [asdf-clarinet  ](#asdf-clarinet--)
- [Contents](#contents)
- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add clarinet https://github.com/alexgo-io/asdf-clarinet.git
```

clarinet:

```shell
# Show all installable versions
asdf list-all clarinet

# Install specific version
asdf install clarinet latest

# Set a version globally (on your ~/.tool-versions file)
asdf global clarinet latest

# Now clarinet commands are available
clarinet --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/bestmike007/asdf-clarinet/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [bestmike007](https://github.com/bestmike007/)
