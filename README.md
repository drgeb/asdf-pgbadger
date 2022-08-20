<div align="center">

# asdf-pgbadger [![Build](https://github.com/drgeb/asdf-pgbadger/actions/workflows/build.yml/badge.svg)](https://github.com/drgeb/asdf-pgbadger/actions/workflows/build.yml) [![Lint](https://github.com/drgeb/asdf-pgbadger/actions/workflows/lint.yml/badge.svg)](https://github.com/drgeb/asdf-pgbadger/actions/workflows/lint.yml)


[pgbadger](https://github.com/darold/pgbadger) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add pgbadger
# or
asdf plugin add pgbadger https://github.com/drgeb/asdf-pgbadger.git
```

pgbadger:

```shell
# Show all installable versions
asdf list-all pgbadger

# Install specific version
asdf install pgbadger latest

# Set a version globally (on your ~/.tool-versions file)
asdf global pgbadger latest

# Now pgbadger commands are available
pgbadger --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/drgeb/asdf-pgbadger/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Dr. Gerald E. Bennett](https://github.com/drgeb/)
