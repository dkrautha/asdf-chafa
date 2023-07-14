<div align="center">

# asdf-chafa [![Build](https://github.com/dkrautha/asdf-chafa/actions/workflows/build.yml/badge.svg)](https://github.com/dkrautha/asdf-chafa/actions/workflows/build.yml) [![Lint](https://github.com/dkrautha/asdf-chafa/actions/workflows/lint.yml/badge.svg)](https://github.com/dkrautha/asdf-chafa/actions/workflows/lint.yml)

[chafa](https://hpjansson.org/chafa/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add chafa
# or
asdf plugin add chafa https://github.com/dkrautha/asdf-chafa.git
```

chafa:

```shell
# Show all installable versions
asdf list-all chafa

# Install specific version
asdf install chafa latest

# Set a version globally (on your ~/.tool-versions file)
asdf global chafa latest

# Now chafa commands are available
chafa --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/dkrautha/asdf-chafa/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [David Krauthamer](https://github.com/dkrautha/)
