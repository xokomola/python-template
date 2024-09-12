# Python Project Template

This is a good starter that has most of the tools we use in our organization already set up.

We have picked a couple of reasonable defaults from the large Python ecosystem.

- VS Code editor (with the Microsoft Python extensions: Python, Python Debugger, Flake and Black)
- Conda virtual environments
- Poetry
- Setuptools
- Flake8
- Black

## Getting started

Do not fork or clone this project.

```
poetry new DIR
cd DIR
git init
conda env create -f environment.yaml
conda activate dverse
pre-commit install
poetry install
code .
```


## Notes

## Todo

- GitHub actions