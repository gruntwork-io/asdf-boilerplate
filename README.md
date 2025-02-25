<div align="center">

# asdf-boilerplate [![Build](https://github.com/gruntwork-io/asdf-boilerplate/actions/workflows/build.yml/badge.svg)](https://github.com/gruntwork-io/asdf-boilerplate/actions/workflows/build.yml) [![Lint](https://github.com/gruntwork-io/asdf-boilerplate/actions/workflows/lint.yml/badge.svg)](https://github.com/gruntwork-io/asdf-boilerplate/actions/workflows/lint.yml)

[boilerplate](https://github.com/gruntwork-io/boilerplate) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add boilerplate
# or
asdf plugin add boilerplate https://github.com/gruntwork-io/asdf-boilerplate.git
```

boilerplate:

```shell
# Show all installable versions
asdf list-all boilerplate

# Install specific version
asdf install boilerplate latest

# Set a version globally (on your ~/.tool-versions file)
asdf global boilerplate latest

# Now boilerplate commands are available
boilerplate --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/gruntwork-io/asdf-boilerplate/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Gruntwork](https://github.com/gruntwork-io/)
