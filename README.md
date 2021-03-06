# Democritus Fun

[![PyPI](https://img.shields.io/pypi/v/d8s-fun.svg)](https://pypi.python.org/pypi/d8s-fun)
[![CI](https://github.com/democritus-project/d8s-fun/workflows/CI/badge.svg)](https://github.com/democritus-project/d8s-fun/actions)
[![Lint](https://github.com/democritus-project/d8s-fun/workflows/Lint/badge.svg)](https://github.com/democritus-project/d8s-fun/actions)
[![codecov](https://codecov.io/gh/democritus-project/d8s-fun/branch/main/graph/badge.svg?token=V0WOIXRGMM)](https://codecov.io/gh/democritus-project/d8s-fun)
[![The Democritus Project uses semver version 2.0.0](https://img.shields.io/badge/-semver%20v2.0.0-22bfda)](https://semver.org/spec/v2.0.0.html)
[![The Democritus Project uses black to format code](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
[![License: LGPL v3](https://img.shields.io/badge/License-LGPL%20v3-blue.svg)](https://choosealicense.com/licenses/lgpl-3.0/)

Fun Democritus functions<sup>[1]</sup>.

[1] Democritus functions are <i>simple, effective, modular, well-tested, and well-documented</i> Python functions.

We use `d8s` (pronounced "dee-eights") as an abbreviation for `democritus` (you can read more about this [here](https://github.com/democritus-project/roadmap#what-is-d8s)).

## Installation

```
pip install d8s-fun
```

## Usage

You import the library like:

```python
from d8s_fun import *
```

Once imported, you can use any of the functions listed below.

## Functions

  - ```python
    def spinner(cycles: int = 10, *, frames_per_second: int = 10) -> None:
        """Print a spinner."""
    ```
  - ```python
    def assumption_make():
        """."""
    ```
  - ```python
    def password_create(*, length: int = 15, character_set: str = PASSWORD_CHARACTER_SET) -> str:
        """Create a password of the given length using the given character_set."""
    ```
  - ```python
    def spin_until_done(func):
        """Show a spinner until the function is done."""
    ```

## Development

👋 &nbsp;If you want to get involved in this project, we have some short, helpful guides below:

- [contribute to this project 🥇][contributing]
- [test it 🧪][local-dev]
- [lint it 🧹][local-dev]
- [explore it 🔭][local-dev]

If you have any questions or there is anything we did not cover, please raise an issue and we'll be happy to help.

## Credits

This package was created with [Cookiecutter](https://github.com/audreyr/cookiecutter) and Floyd Hightower's [Python project template](https://github.com/fhightower-templates/python-project-template).

[contributing]: https://github.com/democritus-project/.github/blob/main/CONTRIBUTING.md#contributing-a-pr-
[local-dev]: https://github.com/democritus-project/.github/blob/main/CONTRIBUTING.md#local-development-
