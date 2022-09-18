<div align="center">

# asdf-jhipster [![Build](https://github.com/mskutlu/asdf-jhipster/actions/workflows/build.yml/badge.svg)](https://github.com/mskutlu/asdf-jhipster/actions/workflows/build.yml) [![Lint](https://github.com/mskutlu/asdf-jhipster/actions/workflows/lint.yml/badge.svg)](https://github.com/mskutlu/asdf-jhipster/actions/workflows/lint.yml)


[jhipster](https://www.jhipster.tech/) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add jhipster
# or
asdf plugin add jhipster https://github.com/mskutlu/asdf-jhipster.git
```

jhipster:

```shell
# Show all installable versions
asdf list-all jhipster

# Install specific version
asdf install jhipster latest

# Set a version globally (on your ~/.tool-versions file)
asdf global jhipster latest

# Now jhipster commands are available
jhipster --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/mskutlu/asdf-jhipster/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [mehmet sakir kutlu](https://github.com/mskutlu/)
