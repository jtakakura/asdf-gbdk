# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test gbdk https://github.com/jtakakura/asdf-gbdk.git "llc -?"
```

Tests are automatically run in GitHub Actions on push and PR.
