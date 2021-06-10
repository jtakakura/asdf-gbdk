<div align="center">

# asdf-gbdk ![Build](https://github.com/jtakakura/asdf-gbdk/workflows/Build/badge.svg) ![Lint](https://github.com/jtakakura/asdf-gbdk/workflows/Lint/badge.svg)

[GBDK](https://github.com/gbdk-2020/gbdk-2020) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add gbdk
# or
asdf plugin add gbdk https://github.com/jtakakura/asdf-gbdk.git
```

gbdk:

```shell
# Show all installable versions
asdf list-all gbdk

# Install specific version
asdf install gbdk latest

# Set a version globally (on your ~/.tool-versions file)
asdf global gbdk latest

# Now gbdk commands are available
llc -?
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/jtakakura/asdf-gbdk/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Junji Takakura](https://github.com/jtakakura/)
