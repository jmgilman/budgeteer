# Budgeteer

> An HTTP API for managing financial budgets.

TODO: Installation, usage, etc.

## Development

Python dependencies are managed using [Poetry][01]. To install all dependencies
and enter the virtual environment, run the following:

```bash
poetry install && poetry shell
```

Additionally, this project is configured with [pre-commit][02]. Usage is
optional, but will increase the chances of your contribution not being flagged
by the CI pipeline. If you would like to use it, run the following to install
the hooks:

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

[01]: https://python-poetry.org/
[02]: https://pre-commit.com/
[03]: https://github.com/igorshubovych/markdownlint-cli
[04]: https://github.com/isaacs/nave
[05]: https://github.com/nvm-sh/nvm
