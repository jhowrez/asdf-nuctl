<div align="center">

# asdf-nuctl [![Build](https://github.com/jhowrez/asdf-nuctl/actions/workflows/build.yml/badge.svg)](https://github.com/jhowrez/asdf-nuctl/actions/workflows/build.yml) [![Lint](https://github.com/jhowrez/asdf-nuctl/actions/workflows/lint.yml/badge.svg)](https://github.com/jhowrez/asdf-nuctl/actions/workflows/lint.yml)

[nuctl](https://docs.nuclio.io/en/stable) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add nuctl
# or
asdf plugin add nuctl https://github.com/jhowrez/asdf-nuctl.git
```

nuctl:

```shell
# Show all installable versions
asdf list-all nuctl

# Install specific version
asdf install nuctl latest

# Set a version globally (on your ~/.tool-versions file)
asdf global nuctl latest

# Now nuctl commands are available
nuctl version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/jhowrez/asdf-nuctl/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [jhowrez](https://github.com/jhowrez/)
