<div align="center">

# asdf-reviewdog [![Build](https://github.com/t1732/asdf-reviewdog/actions/workflows/build.yml/badge.svg)](https://github.com/t1732/asdf-reviewdog/actions/workflows/build.yml) [![Lint](https://github.com/t1732/asdf-reviewdog/actions/workflows/lint.yml/badge.svg)](https://github.com/t1732/asdf-reviewdog/actions/workflows/lint.yml)


[reviewdog](https://github.com/reviewdog/reviewdog) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add reviewdog https://github.com/t1732/asdf-reviewdog.git
```

reviewdog:

```shell
# Show all installable versions
asdf list-all reviewdog

# Install specific version
asdf install reviewdog latest

# Set a version globally (on your ~/.tool-versions file)
asdf global reviewdog latest

# Now reviewdog commands are available
reviewdog --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# License

See [LICENSE](LICENSE) © [t1732](https://github.com/t1732/)
