# Pylama pre-commit hooks

Want to use [pylama](https://github.com/klen/pylama) with [pre-commit](https://pre-commit.com/)?

So did I, but I wasn't able to find any hooks created to allow for it.  Now this one does.. and it's worked for the small surface area I've tested so far.

## Installation

Once you've installed `pre-commit`:

```shell
pip install pre-commit
```

You should be able to edit your `.pre-commit-config.yaml` file to include the configuration from this repository:

```yaml
-   repo: https://github.com/gvanderest/pylama-pre-commit
    rev: 0.1.2
    hooks:
    - id: pylama
```
