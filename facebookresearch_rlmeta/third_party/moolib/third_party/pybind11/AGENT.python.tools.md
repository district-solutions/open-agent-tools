# Agent Python Tools

- repo: facebookresearch/rlmeta
- repo_uri: https://github.com/facebookresearch/rlmeta

## File: facebookresearch_rlmeta/third_party/moolib/third_party/pybind11/noxfile.py

Prompts

```
['run pre-commit lint checks on all files in the pybind11 codebase', 'run pybind11 test suite with cmake across multiple Python versions', 'run pytest on the extra_python_package directory for packaging validation', 'build HTML or PDF documentation using Sphinx and optionally serve locally', 'build SDists and wheels for pybind11 including global SDIST variant', 'build the pybind11 C++ extension module by running setup.py with cmake and setuptools', 'build the expected PYBIND11 version hex string from major, minor, patch, level, and serial components', 'get a template file and replace placeholders with provided key-value options', 'create a source distribution release tree with substituted pyproject.toml and setup.py files', 'remove specified output directories after a context block completes using a cleanup context manager']
```

Usage

```
{'run_lint_session': 'run pre-commit lint checks on all files in the pybind11 codebase', 'run_tests_session': 'run pybind11 test suite with cmake across multiple Python versions', 'run_packaging_tests': 'run pytest on the extra_python_package directory for packaging validation', 'build_docs_session': 'build HTML or PDF documentation using Sphinx and optionally serve locally', 'build_wheels_session': 'build SDists and wheels for pybind11 including global SDIST variant'}
```

## File: facebookresearch_rlmeta/third_party/moolib/third_party/pybind11/setup.py

Prompts

```
['run pre-commit lint checks on all files in the pybind11 codebase', 'run pybind11 test suite with cmake across multiple Python versions', 'run pytest on the extra_python_package directory for packaging validation', 'build HTML or PDF documentation using Sphinx and optionally serve locally', 'build SDists and wheels for pybind11 including global SDIST variant', 'build the pybind11 C++ extension module by running setup.py with cmake and setuptools', 'build the expected PYBIND11 version hex string from major, minor, patch, level, and serial components', 'get a template file and replace placeholders with provided key-value options', 'create a source distribution release tree with substituted pyproject.toml and setup.py files', 'remove specified output directories after a context block completes using a cleanup context manager']
```

Usage

```
{'build_pybind11_extension': 'build the pybind11 C++ extension module by running setup.py with cmake and setuptools', 'build_expected_version_hex': 'build the expected PYBIND11 version hex string from major, minor, patch, level, and serial components', 'get_and_replace_template': 'get a template file and replace placeholders with provided key-value options', 'sdist_make_release_tree': 'create a source distribution release tree with substituted pyproject.toml and setup.py files', 'remove_output_directories': 'remove specified output directories after a context block completes using a cleanup context manager'}
```

