# Agent Python Tools

- repo: facebookresearch/rlmeta
- repo_uri: https://github.com/facebookresearch/rlmeta

## File: facebookresearch_rlmeta/third_party/pybind11/noxfile.py

Prompts

```
['run pre-commit lint checks on the entire pybind11 codebase', 'run the pybind11 test suite with cmake across multiple Python versions', 'run pytest against the extra_python_package packaging tests', 'build the pybind11 documentation as HTML or PDF with Sphinx', 'build SDists and wheels for pybind11 including global SDist variants', 'build a pybind11 source distribution by running python setup.py sdist with version templating', 'build the expected PYBIND11_VERSION_HEX string from MAJOR, MINOR, PATCH version components', 'get a template file and replace placeholders with provided key-value substitution options', 'review the SDist class that overrides make_release_tree to substitute version into pyproject.toml and setup.py', 'run cmake to configure and install pybind11 headers into the pybind11 directory with NOPYTHON enabled']
```

Usage

```
{'run_lint': 'run pre-commit lint checks on the entire pybind11 codebase', 'run_tests': 'run the pybind11 test suite with cmake across multiple Python versions', 'run_packaging_tests': 'run pytest against the extra_python_package packaging tests', 'build_docs': 'build the pybind11 documentation as HTML or PDF with Sphinx', 'build_wheels': 'build SDists and wheels for pybind11 including global SDist variants'}
```

## File: facebookresearch_rlmeta/third_party/pybind11/setup.py

Prompts

```
['run pre-commit lint checks on the entire pybind11 codebase', 'run the pybind11 test suite with cmake across multiple Python versions', 'run pytest against the extra_python_package packaging tests', 'build the pybind11 documentation as HTML or PDF with Sphinx', 'build SDists and wheels for pybind11 including global SDist variants', 'build a pybind11 source distribution by running python setup.py sdist with version templating', 'build the expected PYBIND11_VERSION_HEX string from MAJOR, MINOR, PATCH version components', 'get a template file and replace placeholders with provided key-value substitution options', 'review the SDist class that overrides make_release_tree to substitute version into pyproject.toml and setup.py', 'run cmake to configure and install pybind11 headers into the pybind11 directory with NOPYTHON enabled']
```

Usage

```
{'build_pybind11_sdist': 'build a pybind11 source distribution by running python setup.py sdist with version templating', 'build_expected_version_hex': 'build the expected PYBIND11_VERSION_HEX string from MAJOR, MINOR, PATCH version components', 'get_and_replace_template': 'get a template file and replace placeholders with provided key-value substitution options', 'review_SDist_class': 'review the SDist class that overrides make_release_tree to substitute version into pyproject.toml and setup.py', 'run_cmake_install_pybind11': 'run cmake to configure and install pybind11 headers into the pybind11 directory with NOPYTHON enabled'}
```

