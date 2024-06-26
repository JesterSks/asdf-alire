<div align="center">

# asdf-alire [![Build](https://github.com/JesterSks/asdf-alire/actions/workflows/build.yml/badge.svg)](https://github.com/JesterSks/asdf-alire/actions/workflows/build.yml) [![Lint](https://github.com/JesterSks/asdf-alire/actions/workflows/lint.yml/badge.svg)](https://github.com/JesterSks/asdf-alire/actions/workflows/lint.yml)

[alire](https://alire.ada.dev/docs/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add alire
# or
asdf plugin add alire https://github.com/JesterSks/asdf-alire.git
```

alire:

```shell
# Show all installable versions
asdf list-all alire

# Install specific version
asdf install alire latest

# Set a version globally (on your ~/.tool-versions file)
asdf global alire latest

# Now alire commands are available
alr --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/JesterSks/asdf-alire/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Robert Burghart](https://github.com/JesterSks/)
