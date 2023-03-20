# Accelleran O-RAN Operation Guide

This is based on system release 2022.4.0

## Document Published Link

???

## Preview The Document

### Prerequest

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
- Start the server side.
```
cd docs
poetry shell
mkdocs serve --dev-addr 0.0.0.0:8000
```
- Access the document: 
[http://<machine_ip>:8000/ran-operation-guide/](http://<machine_ip>:8000/ran-operation-guide/)