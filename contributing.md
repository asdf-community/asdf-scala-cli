# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test scala-cli https://github.com/asdf-community/asdf-scala-cli.git "scala-cli version"
```

Tests are automatically run in GitHub Actions on push and PR.
