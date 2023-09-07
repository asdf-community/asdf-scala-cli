<div align="center">

# asdf-scala-cli [![Build](https://github.com/rlemaitre/asdf-scala-cli/actions/workflows/build.yml/badge.svg)](https://github.com/rlemaitre/asdf-scala-cli/actions/workflows/build.yml) [![Lint](https://github.com/rlemaitre/asdf-scala-cli/actions/workflows/lint.yml/badge.svg)](https://github.com/rlemaitre/asdf-scala-cli/actions/workflows/lint.yml)

[scala-cli](https://scala-cli.virtuslab.org/docs/overview) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add scala-cli
# or
asdf plugin add scala-cli https://github.com/rlemaitre/asdf-scala-cli.git
```

scala-cli:

```shell
# Show all installable versions
asdf list-all scala-cli

# Install specific version
asdf install scala-cli latest

# Set a version globally (on your ~/.tool-versions file)
asdf global scala-cli latest

# Now scala-cli commands are available
scala-cli --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/rlemaitre/asdf-scala-cli/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Raphaël Lemaitre](https://github.com/rlemaitre/)
