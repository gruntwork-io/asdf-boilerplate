# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# Example
asdf plugin test boilerplate https://github.com/gruntwork-io/asdf-boilerplate.git "boilerplate --version"
```

Tests are automatically run in GitHub Actions on push and PR.
