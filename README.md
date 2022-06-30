<div align="center">

# asdf-reviewdog


[reviewdog](https://github.com/reviewdog/reviewdog) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add reviewdog https://github.com/<YOUR GITHUB USERNAME>/asdf-reviewdog.git
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
