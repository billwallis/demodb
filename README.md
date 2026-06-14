<span align="center">

[![Python](https://img.shields.io/badge/Python-3.13+-blue.svg)](https://www.python.org/downloads/)
[![uv](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/uv/main/assets/badge/v0.json)](https://github.com/astral-sh/uv)
[![tests](https://github.com/billwallis/demodb/actions/workflows/tests.yaml/badge.svg)](https://github.com/billwallis/demodb/actions/workflows/tests.yaml)
[![coverage](https://raw.githubusercontent.com/billwallis/demodb/refs/heads/main/coverage.svg)](https://smarie.github.io/python-genbadge/)

[![pre-commit.ci status](https://results.pre-commit.ci/badge/github/billwallis/demodb/main.svg)](https://results.pre-commit.ci/latest/github/billwallis/demodb/main)
[![GitHub last commit](https://img.shields.io/github/last-commit/billwallis/demodb)](https://shields.io/badges/git-hub-last-commit)

</span>

---

# DemoDB

RDBMS system built for demonstration purposes.

## Revealing the ✨ magic ✨

Many database systems do a lot of magic under the hood.

Since they're often built for high-performance use cases, they're often built with lower-level languages, making it harder to understand how they work if you don't know those languages.

This project is built in Python, and aims to be a simple, easy-to-understand database system that can be used to demonstrate how databases work. It **does not** aim to be high-performance.

This implementation has been inspired by the [SQLite](https://sqlite.org/src/doc/trunk/README.md) and [AriaSQL](https://github.com/ariasql/ariasql), and is built following the guidance in:

- [Build Your Own Database From Scratch in Go](https://build-your-own.org/database/)

## Contributing

Install [uv](https://docs.astral.sh/uv/getting-started/installation/) and then install the dependencies:

```shell
uvx --from poethepoet poe install
```
