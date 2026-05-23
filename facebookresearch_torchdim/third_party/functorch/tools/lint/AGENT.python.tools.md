# Agent Python Tools

- repo: facebookresearch/torchdim
- repo_uri: https://github.com/facebookresearch/torchdim

## File: facebookresearch_torchdim/third_party/functorch/tools/lint/black_linter.py

Prompts

```
['run the black linter on a list of Python files to check formatting', 'check a single Python file against black formatting rules and return lint messages', 'run a subprocess command with automatic retries on timeout and logging', 'create a LintMessage named tuple with path, severity, code, and description fields', 'use the LintSeverity enum to classify lint issues as error, warning, advice, or disabled', 'run flake8 on one or more Python files and output JSON lint messages to stdout', 'run flake8 linter with custom severity mappings like B950:advice for specific error codes', 'run flake8 linter with a custom plugins path via the --flake8-plugins-path flag', 'call check_files to lint a list of filenames and get a list of LintMessage objects', 'call get_issue_severity to classify a flake8 error code as error, warning, or advice', 'run pip_init.py to install specified pip packages with version pinning for linting tools', 'run pip_init.py with --dry-run 1 to preview package installation without executing', 'run pip_init.py with --verbose to get detailed logging output during package installation', 'run a subprocess command with timing and debug logging via the run_command helper function', 'install linter packages using pip_init.py with versioned package arguments like flake8==5.0.4']
```

Usage

```
{'run_black_linter': 'run the black linter on a list of Python files to check formatting', 'check_file_with_black': 'check a single Python file against black formatting rules and return lint messages', 'run_command_with_retries': 'run a subprocess command with automatic retries on timeout and logging', 'create_lint_message': 'create a LintMessage named tuple with path, severity, code, and description fields', 'use_lint_severity_enum': 'use the LintSeverity enum to classify lint issues as error, warning, advice, or disabled'}
```

## File: facebookresearch_torchdim/third_party/functorch/tools/lint/flake8_linter.py

Prompts

```
['run the black linter on a list of Python files to check formatting', 'check a single Python file against black formatting rules and return lint messages', 'run a subprocess command with automatic retries on timeout and logging', 'create a LintMessage named tuple with path, severity, code, and description fields', 'use the LintSeverity enum to classify lint issues as error, warning, advice, or disabled', 'run flake8 on one or more Python files and output JSON lint messages to stdout', 'run flake8 linter with custom severity mappings like B950:advice for specific error codes', 'run flake8 linter with a custom plugins path via the --flake8-plugins-path flag', 'call check_files to lint a list of filenames and get a list of LintMessage objects', 'call get_issue_severity to classify a flake8 error code as error, warning, or advice', 'run pip_init.py to install specified pip packages with version pinning for linting tools', 'run pip_init.py with --dry-run 1 to preview package installation without executing', 'run pip_init.py with --verbose to get detailed logging output during package installation', 'run a subprocess command with timing and debug logging via the run_command helper function', 'install linter packages using pip_init.py with versioned package arguments like flake8==5.0.4']
```

Usage

```
{'run_flake8_linter': 'run flake8 on one or more Python files and output JSON lint messages to stdout', 'run_flake8_with_custom_severity': 'run flake8 linter with custom severity mappings like B950:advice for specific error codes', 'run_flake8_with_plugins': 'run flake8 linter with a custom plugins path via the --flake8-plugins-path flag', 'check_files_programmatically': 'call check_files to lint a list of filenames and get a list of LintMessage objects', 'get_issue_severity': 'call get_issue_severity to classify a flake8 error code as error, warning, or advice'}
```

## File: facebookresearch_torchdim/third_party/functorch/tools/lint/pip_init.py

Prompts

```
['run the black linter on a list of Python files to check formatting', 'check a single Python file against black formatting rules and return lint messages', 'run a subprocess command with automatic retries on timeout and logging', 'create a LintMessage named tuple with path, severity, code, and description fields', 'use the LintSeverity enum to classify lint issues as error, warning, advice, or disabled', 'run flake8 on one or more Python files and output JSON lint messages to stdout', 'run flake8 linter with custom severity mappings like B950:advice for specific error codes', 'run flake8 linter with a custom plugins path via the --flake8-plugins-path flag', 'call check_files to lint a list of filenames and get a list of LintMessage objects', 'call get_issue_severity to classify a flake8 error code as error, warning, or advice', 'run pip_init.py to install specified pip packages with version pinning for linting tools', 'run pip_init.py with --dry-run 1 to preview package installation without executing', 'run pip_init.py with --verbose to get detailed logging output during package installation', 'run a subprocess command with timing and debug logging via the run_command helper function', 'install linter packages using pip_init.py with versioned package arguments like flake8==5.0.4']
```

Usage

```
{'run_pip_init_install': 'run pip_init.py to install specified pip packages with version pinning for linting tools', 'run_pip_init_dry_run': 'run pip_init.py with --dry-run 1 to preview package installation without executing', 'run_pip_init_verbose': 'run pip_init.py with --verbose to get detailed logging output during package installation', 'run_command_subprocess': 'run a subprocess command with timing and debug logging via the run_command helper function', 'install_linter_packages': 'install linter packages using pip_init.py with versioned package arguments like flake8==5.0.4'}
```

