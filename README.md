# Budgeteer

> An HTTP API for managing financial budgets.

TODO: Installation, usage, etc.

## Development

### Python

Python dependencies are managed using [Poetry][01]. To install all dependencies
and enter the virtual environment, run the following:

```bash
poetry install && poetry shell
```

### Pre-Commit

This project is configured with [pre-commit][02]. Usage is optional, but using
it will decrease the chances of your contribution being flagged by the CI
pipeline. If you would like to use it, run the following to install the hooks:

```bash
poetry run pre-commit install
poetry run pre-commit install --hook-type commit-msg
```

The `markdownlint` hook requires the [markdownlint-cli][03] tool to be installed
locally. To do so, run:

```bash
npm install
```

It's recommended (but optional) to use a tool like [nave][04] or [nvm][05] for
isolating node versions.

### Nix

An optional `flake.nix` file is provided for setting up a preconfigured
development environment. If you have [Nix][06] installed, simply run:

```bash
nix  develop
```

Alternatively, if you have [direnv][07] installed, you can use the `.envrc` file
to automatically load the environment for you:

```bash
direnv allow
direnv reload
```

[01]: https://python-poetry.org/
[02]: https://pre-commit.com/
[03]: https://github.com/igorshubovych/markdownlint-cli
[04]: https://github.com/isaacs/nave
[05]: https://github.com/nvm-sh/nvm
[06]: https://nixos.org/
[07]: https://direnv.net/
