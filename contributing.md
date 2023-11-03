# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test clarinet https://github.com/alexgo-io/asdf-clarinet.git "clarinet -V | grep clarinet"
```

Tests are automatically run in GitHub Actions on push and PR.
