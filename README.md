
# Testing The Doc

## Prerequest

- Assuming **docs** directory is already available
```
cd docs
curl -sSL https://install.python-poetry.org | python3 -
poetry install
poetry shell
pip3 install mkdocs
pip3 install mkdocs-material
pip3 install mike
pip3 install mkdocs-section-index
```
- Exit for the actions to take effect.
```
exit
```

## To Run

```
cd docs
poetry shell
mkdocs serve --dev-addr 0.0.0.0:8000
```