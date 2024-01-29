<div align="center">

# asdf-starkli [![Build](https://github.com/ptisserand/asdf-starkli/actions/workflows/build.yml/badge.svg)](https://github.com/ptisserand/asdf-starkli/actions/workflows/build.yml) [![Lint](https://github.com/ptisserand/asdf-starkli/actions/workflows/lint.yml/badge.svg)](https://github.com/ptisserand/asdf-starkli/actions/workflows/lint.yml)

[starkli](https://book.starkli.rs/) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add starkli
# or
asdf plugin add starkli https://github.com/ptisserand/asdf-starkli.git
```

starkli:

```shell
# Show all installable versions
asdf list-all starkli

# Install specific version
asdf install starkli latest

# Set a version globally (on your ~/.tool-versions file)
asdf global starkli latest

# Now starkli commands are available
starkli --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/ptisserand/asdf-starkli/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Patrice Tisserand](https://github.com/ptisserand/)
