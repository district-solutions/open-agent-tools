# Agent Python Tools

- repo: facebookresearch/nocturne
- repo_uri: https://github.com/facebookresearch/nocturne

## File: facebookresearch_nocturne/third_party/pybind11/noxfile.py

Prompts

```
['run pre-commit hooks on all files to lint the pybind11 codebase', 'run cmake-based tests across multiple Python versions including pypy with catch and eigen', 'run pytest on the extra_python_package directory to validate packaging', 'build HTML or PDF documentation using sphinx and optionally serve locally', 'build SDists and wheels for both normal and PYBIND11_GLOBAL_SDIST variants', 'build a hex version string from MAJOR, MINOR, PATCH, level, and serial version components', 'create a function that reads a template file and substitutes variables using string.Template', 'build a source distribution that replaces template files with version-substituted content in the release tree', 'create a context manager that removes specified directories on exit using shutil.rmtree', 'run cmake to configure and install pybind11 headers into the pybind11 package directory']
```

Usage

```
{'run_lint_session': 'run pre-commit hooks on all files to lint the pybind11 codebase', 'run_tests_session': 'run cmake-based tests across multiple Python versions including pypy with catch and eigen', 'run_tests_packaging_session': 'run pytest on the extra_python_package directory to validate packaging', 'build_docs_session': 'build HTML or PDF documentation using sphinx and optionally serve locally', 'build_wheels_session': 'build SDists and wheels for both normal and PYBIND11_GLOBAL_SDIST variants'}
```

## File: facebookresearch_nocturne/third_party/pybind11/setup.py

Prompts

```
['run pre-commit hooks on all files to lint the pybind11 codebase', 'run cmake-based tests across multiple Python versions including pypy with catch and eigen', 'run pytest on the extra_python_package directory to validate packaging', 'build HTML or PDF documentation using sphinx and optionally serve locally', 'build SDists and wheels for both normal and PYBIND11_GLOBAL_SDIST variants', 'build a hex version string from MAJOR, MINOR, PATCH, level, and serial version components', 'create a function that reads a template file and substitutes variables using string.Template', 'build a source distribution that replaces template files with version-substituted content in the release tree', 'create a context manager that removes specified directories on exit using shutil.rmtree', 'run cmake to configure and install pybind11 headers into the pybind11 package directory']
```

Usage

```
{'build_expected_version_hex': 'build a hex version string from MAJOR, MINOR, PATCH, level, and serial version components', 'get_and_replace': 'create a function that reads a template file and substitutes variables using string.Template', 'SDist_make_release_tree': 'build a source distribution that replaces template files with version-substituted content in the release tree', 'remove_output': 'create a context manager that removes specified directories on exit using shutil.rmtree', 'run_cmake_install': 'run cmake to configure and install pybind11 headers into the pybind11 package directory'}
```

