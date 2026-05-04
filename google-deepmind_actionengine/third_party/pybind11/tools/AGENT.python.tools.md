# Agent Python Tools

- repo: google-deepmind/actionengine
- repo_uri: https://github.com/google-deepmind/actionengine

## File: google-deepmind_actionengine/third_party/pybind11/tools/codespell_ignore_lines_from_errors.py

Prompts

```
['run the script to parse a codespell error log and extract unique source lines that triggered spelling warnings', 'parse a codespell error output file to extract filenames and line numbers from each error entry', 'extract the actual source code lines from files referenced in codespell error output', 'deduplicate source lines extracted from codespell errors so each unique line is printed only once', 'rebuild a .codespell-ignore-lines file by piping extracted source lines from a codespell error log', 'run the make_global script to print a modified pyproject.toml as a global wheel config', 'call get_global to return a stripped pyproject.toml string renamed to pybind11-global', 'generate a global pyproject.toml with experimental scikit-build and install dir set to /data', 'use get_global to produce a pyproject.toml with entry-points, scripts, and optional-dependencies removed', 'configure the wheel install directory to /data by calling get_global on the pyproject.toml']
```

Usage

```
{'run_codespell_ignore_lines': 'run the script to parse a codespell error log and extract unique source lines that triggered spelling warnings', 'parse_codespell_errors': 'parse a codespell error output file to extract filenames and line numbers from each error entry', 'extract_source_lines': 'extract the actual source code lines from files referenced in codespell error output', 'deduplicate_codespell_lines': 'deduplicate source lines extracted from codespell errors so each unique line is printed only once', 'rebuild_codespell_ignore_file': 'rebuild a .codespell-ignore-lines file by piping extracted source lines from a codespell error log'}
```

## File: google-deepmind_actionengine/third_party/pybind11/tools/make_global.py

Prompts

```
['run the script to parse a codespell error log and extract unique source lines that triggered spelling warnings', 'parse a codespell error output file to extract filenames and line numbers from each error entry', 'extract the actual source code lines from files referenced in codespell error output', 'deduplicate source lines extracted from codespell errors so each unique line is printed only once', 'rebuild a .codespell-ignore-lines file by piping extracted source lines from a codespell error log', 'run the make_global script to print a modified pyproject.toml as a global wheel config', 'call get_global to return a stripped pyproject.toml string renamed to pybind11-global', 'generate a global pyproject.toml with experimental scikit-build and install dir set to /data', 'use get_global to produce a pyproject.toml with entry-points, scripts, and optional-dependencies removed', 'configure the wheel install directory to /data by calling get_global on the pyproject.toml']
```

Usage

```
{'run_make_global_script': 'run the make_global script to print a modified pyproject.toml as a global wheel config', 'get_global_function': 'call get_global to return a stripped pyproject.toml string renamed to pybind11-global', 'generate_global_pyproject': 'generate a global pyproject.toml with experimental scikit-build and install dir set to /data', 'remove_entry_points_and_scripts': 'use get_global to produce a pyproject.toml with entry-points, scripts, and optional-dependencies removed', 'configure_wheel_install_dir': 'configure the wheel install directory to /data by calling get_global on the pyproject.toml'}
```

