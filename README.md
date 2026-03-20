<div align="center">

# asdf-mdvi [![Build](https://github.com/phealy/asdf-mdvi/actions/workflows/build.yml/badge.svg)](https://github.com/phealy/asdf-mdvi/actions/workflows/build.yml) [![Lint](https://github.com/phealy/asdf-mdvi/actions/workflows/lint.yml/badge.svg)](https://github.com/phealy/asdf-mdvi/actions/workflows/lint.yml)

[mdvi](https://github.com/taf2/mdvi) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `cargo` (Rust toolchain): mdvi is built from source. Install via [rustup](https://rustup.rs) or `asdf install rust latest`.

# Install

Plugin:

```shell
asdf plugin add mdvi
# or
asdf plugin add mdvi https://github.com/phealy/asdf-mdvi.git
```

mdvi:

```shell
# Show all installable versions
asdf list-all mdvi

# Install specific version
asdf install mdvi latest

# Set a version globally (on your ~/.tool-versions file)
asdf global mdvi latest

# Now mdvi commands are available
mdvi --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/phealy/asdf-mdvi/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Patrick Healy](https://github.com/phealy/)
