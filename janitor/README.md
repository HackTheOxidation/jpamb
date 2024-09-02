# `janitor` - THE program analyzer* for Java

NOTE - Can only detect the following types of errors:

* Assertion errors
* Out of Bounds
* Null pointer exceptions
* ... (non-termination)


## Getting started

This project uses `poetry` to manage virtual environments and dependencies.

To install dependencies and setup the environment, run:

```sh
poetry install
```

To build a distributable (python .whl), run:

```sh
poetry build
```

(TODO) To execute the application, run:
```sh
poetry run <main>
```

### Future improvements

Consider [`tree-sitter`](https://github.com/tree-sitter/py-tree-sitter) as an alternative to `antlr4`?
