# Agent Python Tools

- repo: facebookresearch/hydra
- repo_uri: https://github.com/facebookresearch/hydra.git

## File: facebookresearch_hydra/noxfile.py

Prompts

```
['run black, isort, mypy, flake8, yamllint, and bandit linting checks on the Hydra codebase', 'run pytest on the Hydra core tests and standalone application test suites', 'run pytest on a selected Hydra plugin after installing it and its dependencies', 'run coverage analysis across Hydra core and all compatible plugins with a fail-under threshold', 'run nbval pytest on Jupyter notebook examples to validate notebook outputs']
```

Usage

```
{'run_lint': 'run black, isort, mypy, flake8, yamllint, and bandit linting checks on the Hydra codebase', 'run_test_core': 'run pytest on the Hydra core tests and standalone application test suites', 'run_test_plugins': 'run pytest on a selected Hydra plugin after installing it and its dependencies', 'run_coverage': 'run coverage analysis across Hydra core and all compatible plugins with a fail-under threshold', 'run_test_jupyter_notebooks': 'run nbval pytest on Jupyter notebook examples to validate notebook outputs'}
```

