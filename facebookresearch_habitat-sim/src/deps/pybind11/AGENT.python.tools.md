# Agent Python Tools

- repo: facebookresearch/habitat-sim
- repo_uri: https://github.com/facebookresearch/habitat-sim

## File: facebookresearch_habitat-sim/src/deps/pybind11/noxfile.py

Prompts

```
['run pre-commit hooks on all files to lint the pybind11 codebase', 'run the pybind11 test suite using cmake across multiple Python versions', 'run pytest on the extra_python_package directory to validate packaging', 'build HTML or PDF documentation using Sphinx and optionally serve locally', 'build source distributions and wheels including pybind11-global variants', 'build a pybind11 source distribution by running setup.py with the sdist command', 'build the expected PYBIND11 version hex string from MAJOR, MINOR, and PATCH version matches', 'get a template file and replace placeholders with provided key-value options', 'review the SDist class that customizes setuptools sdist to substitute version into pyproject.toml and setup.py', 'run cmake to configure and install pybind11 headers and share files into the pybind11 directory']
```

Usage

```
{'run_lint': 'run pre-commit hooks on all files to lint the pybind11 codebase', 'run_tests': 'run the pybind11 test suite using cmake across multiple Python versions', 'run_packaging_tests': 'run pytest on the extra_python_package directory to validate packaging', 'build_docs': 'build HTML or PDF documentation using Sphinx and optionally serve locally', 'build_sdist_wheels': 'build source distributions and wheels including pybind11-global variants'}
```

## File: facebookresearch_habitat-sim/src/deps/pybind11/setup.py

Prompts

```
['run pre-commit hooks on all files to lint the pybind11 codebase', 'run the pybind11 test suite using cmake across multiple Python versions', 'run pytest on the extra_python_package directory to validate packaging', 'build HTML or PDF documentation using Sphinx and optionally serve locally', 'build source distributions and wheels including pybind11-global variants', 'build a pybind11 source distribution by running setup.py with the sdist command', 'build the expected PYBIND11 version hex string from MAJOR, MINOR, and PATCH version matches', 'get a template file and replace placeholders with provided key-value options', 'review the SDist class that customizes setuptools sdist to substitute version into pyproject.toml and setup.py', 'run cmake to configure and install pybind11 headers and share files into the pybind11 directory']
```

Usage

```
{'build_pybind11_sdist': 'build a pybind11 source distribution by running setup.py with the sdist command', 'build_expected_version_hex': 'build the expected PYBIND11 version hex string from MAJOR, MINOR, and PATCH version matches', 'get_and_replace_template': 'get a template file and replace placeholders with provided key-value options', 'review_SDist_class': 'review the SDist class that customizes setuptools sdist to substitute version into pyproject.toml and setup.py', 'run_cmake_install_pybind11': 'run cmake to configure and install pybind11 headers and share files into the pybind11 directory'}
```

