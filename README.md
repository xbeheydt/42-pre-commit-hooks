# 42 School - pre-commit-hooks

This is a collection of hooks for 42 School projects.

See also: https://github.com/pre-commit/pre-commit

## Installation

To use pre-commit, you must be have `pre-commit` installed.
To make it, I use `pipx` :

```bash
pipx install pre-commit
```

## Configure

Configuration is easy, you can copy `samples/pre-commit.config.sample.yaml`
in your project, as a model :

```bash
# inside top level project or in submodule folders
curl https://raw.githubusercontent.com/xbeheydt/42-pre-commit-hooks/master/samples/pre-commit.config.sample.yaml > .pre-commit.config.yaml
```

To activate pre-commit :

```bash
# inside top level project or in submodule folders
pre-commit install
```

## Hooks available

[`check-norm`](https://github.com/42School/norminette)

This helper run norminette in your project.
- You can use all arguments used by norminette.

`run-munit`

This hook can run compilation tests and project with run unit tests.

## Credits

Developped by [xbeheydt](xavier.beheydt@gmail.com)

## License

This is a MIT License.
