# Agent Python Tools

- repo: facebookresearch/recipes
- repo_uri: https://github.com/facebookresearch/recipes

## File: facebookresearch_recipes/torchrecipes/paved_path/tools/linter/pip_init.py

Prompts

```
['run the pip initializer CLI to install versioned pip packages for linter setup', 'run a subprocess command with timing and debug logging via run_command', 'install linter packages with pinned versions using pip3 install in user or venv mode', 'preview pip install commands without executing by passing --dry-run 1 to the CLI', 'validate that all pip packages have explicit versions specified before installation', 'run the ufmt linter on one or more Python files to check formatting with black and usort', 'check a single Python file for formatting issues using ufmt and return lint messages', 'create a LintMessage named tuple with path, severity, code, and optional original and replacement content', 'format an exception into a LintMessage with ADVICE severity for failed lint operations', 'use the LintSeverity enum to classify lint issues as ERROR, WARNING, ADVICE, or DISABLED']
```

Usage

```
{'run_pip_init_cli': 'run the pip initializer CLI to install versioned pip packages for linter setup', 'run_run_command': 'run a subprocess command with timing and debug logging via run_command', 'install_linter_packages': 'install linter packages with pinned versions using pip3 install in user or venv mode', 'dry_run_pip_init': 'preview pip install commands without executing by passing --dry-run 1 to the CLI', 'validate_package_versions': 'validate that all pip packages have explicit versions specified before installation'}
```

## File: facebookresearch_recipes/torchrecipes/paved_path/tools/linter/ufmt_linter.py

Prompts

```
['run the pip initializer CLI to install versioned pip packages for linter setup', 'run a subprocess command with timing and debug logging via run_command', 'install linter packages with pinned versions using pip3 install in user or venv mode', 'preview pip install commands without executing by passing --dry-run 1 to the CLI', 'validate that all pip packages have explicit versions specified before installation', 'run the ufmt linter on one or more Python files to check formatting with black and usort', 'check a single Python file for formatting issues using ufmt and return lint messages', 'create a LintMessage named tuple with path, severity, code, and optional original and replacement content', 'format an exception into a LintMessage with ADVICE severity for failed lint operations', 'use the LintSeverity enum to classify lint issues as ERROR, WARNING, ADVICE, or DISABLED']
```

Usage

```
{'run_ufmt_linter': 'run the ufmt linter on one or more Python files to check formatting with black and usort', 'check_file_formatting': 'check a single Python file for formatting issues using ufmt and return lint messages', 'create_lint_message': 'create a LintMessage named tuple with path, severity, code, and optional original and replacement content', 'format_error_message': 'format an exception into a LintMessage with ADVICE severity for failed lint operations', 'use_lint_severity': 'use the LintSeverity enum to classify lint issues as ERROR, WARNING, ADVICE, or DISABLED'}
```

