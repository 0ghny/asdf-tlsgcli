# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test tlsg-cli https://github.com/0ghny/asdf-tlsgcli.git "tlsg-cli --help"
```

Tests are automatically run in GitHub Actions on push and PR.
