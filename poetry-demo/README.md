# poetry-demo

## Before you start
Install `poetry` and run
```sh
poetry install
# or for production environment
poetry install --no-dev

# List the installed packages
poetry show
```

## Trying it out
```sh
poetry shell
python
>>> import poetry_demo
>>> poetry_demo.hello()
>>> exit()
exit
```

## Running Test
```sh
poetry run pytest
```

## Adding dependency
Just edit `pyproject.toml` or run
```sh
poetry add logzero
# or
poetry add flake8 mypy --dev
```

## Updating dependencies
```sh
poetry update
```
