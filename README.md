# pliers-waters-4a-kit

Validate JSON files and print a normalized form.

Small, dependency-free Python utility package generated for day-to-day file chores.
Standard library only — no third-party imports.

## Install

```bash
pip install -e .
```

## Usage

```bash
python -m pliers_waters_4a_kit.cli --help
```

```python
from pliers_waters_4a_kit.core import PliersWaters4aTool

tool = PliersWaters4aTool()
print(tool)
```

## Layout

```
pliers_waters_4a_kit/
  __init__.py
  core.py
  cli.py
tests/
  test_core.py
```

## License

MIT © 2026 pliers-waters-4a
