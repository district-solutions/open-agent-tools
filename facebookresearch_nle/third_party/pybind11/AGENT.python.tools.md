# Agent Python Tools

- repo: facebookresearch/nle
- repo_uri: https://github.com/facebookresearch/nle

## File: facebookresearch_nle/third_party/pybind11/noxfile.py

Prompts

```
['run pre-commit lint checks on all files in the pybind11 codebase', 'run pybind11 tests across Python 3.6 through 3.11 and PyPy versions using cmake', 'run pytest on the extra_python_package test suite for packaging validation', 'build HTML or PDF documentation using Sphinx and optionally serve locally on port 8000', 'build SDists and wheels for both normal and PYBIND11_GLOBAL_SDIST variants', 'build the expected PYBIND11 version hex string from MAJOR, MINOR, and PATCH version matches', 'get a template file and replace placeholders with provided key-value options', 'build a source distribution release tree with substituted version and template files', 'remove specified CMake output directories after a build context completes', 'run the pybind11 setup script to configure cmake and install headers into the package']
```

Usage

```
{'run_lint_session': 'run pre-commit lint checks on all files in the pybind11 codebase', 'run_tests_session': 'run pybind11 tests across Python 3.6 through 3.11 and PyPy versions using cmake', 'run_tests_packaging_session': 'run pytest on the extra_python_package test suite for packaging validation', 'build_docs_session': 'build HTML or PDF documentation using Sphinx and optionally serve locally on port 8000', 'build_wheels_session': 'build SDists and wheels for both normal and PYBIND11_GLOBAL_SDIST variants'}
```

## File: facebookresearch_nle/third_party/pybind11/setup.py

Prompts

```
['run pre-commit lint checks on all files in the pybind11 codebase', 'run pybind11 tests across Python 3.6 through 3.11 and PyPy versions using cmake', 'run pytest on the extra_python_package test suite for packaging validation', 'build HTML or PDF documentation using Sphinx and optionally serve locally on port 8000', 'build SDists and wheels for both normal and PYBIND11_GLOBAL_SDIST variants', 'build the expected PYBIND11 version hex string from MAJOR, MINOR, and PATCH version matches', 'get a template file and replace placeholders with provided key-value options', 'build a source distribution release tree with substituted version and template files', 'remove specified CMake output directories after a build context completes', 'run the pybind11 setup script to configure cmake and install headers into the package']
```

Usage

```
{'build_expected_version_hex': 'build the expected PYBIND11 version hex string from MAJOR, MINOR, and PATCH version matches', 'get_and_replace': 'get a template file and replace placeholders with provided key-value options', 'SDist_make_release_tree': 'build a source distribution release tree with substituted version and template files', 'remove_output': 'remove specified CMake output directories after a build context completes', 'run_setup_pybind11': 'run the pybind11 setup script to configure cmake and install headers into the package'}
```

