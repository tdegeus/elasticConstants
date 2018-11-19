# elasticConstants

Simple Python library/function to convert elastic constants.

## Usage

```python
import elasticConstants

print(elasticConstants.convert(E=1.0, nu=0.3))
```

## Installation

```bash
python -m install elasticConstants
```

## Develop

After completing an update, change the version number and upload to GitHub and then to PyPi using

```bash
python setup.py bdist_wheel --universal
twine upload dist/*
```
