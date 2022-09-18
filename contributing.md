# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test jhipster https://github.com/mskutlu/asdf-jhipster.git "jhipster --version"
```

Tests are automatically run in GitHub Actions on push and PR.
